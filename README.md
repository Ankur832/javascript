//string and templates

// const firstName="Jonas";
// const job="teacher";
// const birthday=2002;

// const string=`I am a ${firstName} and my profession if ${job} and i am born in ${birthday}`;
// console.log(string)

// let isIsland = false;
// let language;

// console.log(typeof isIsland);  //bolean
// console.log(typeof population); //undefinned
// console.log(typeof country); //undefined
// console.log(typeof language);//undefined


// language = 'portuguese';
// const country = 'Portugal';
// const continent = 'Europe';
// const isIsland = false;
// isIsland = true;

//string 

const gameName=  new String('hitesh')

//for upper the string
console.log(gameName.toUpperCase());
//for find the lenght we use lenght prototype
console.log(gameName.length)
//for find the position of the char
console.log(gameName.charAt(2))
//for reverse the of that to find the char with position then use index
console.log(gameName.indexOf('t'));
//another method slice we use alos - values for get the result
const newString= gameName.slice(0,3)
console.log(newString)
// substring also used but negative value not working its ignore 
const newSubstring= gameName.substring(0,4);
console.log(newSubstring);
//for remove the extra space in starting or ending
const name='   hitech';
console.log(name);
console.log(name.trim());
// for replace we also used this to replace anthing with anything 
const url='htttpls:ankur123%.com'
const replaceString=url.replace('123','321')
console.log(replaceString)
//split is ussed for split the string 
console.log(replaceString.split('%'))
console.log(replaceString)
console.log(gameName)
