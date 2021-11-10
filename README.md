# FreeCodeCamp5




50 const myDog = {
  "name": "Happy Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"]
};
 
 myDog["bark"] = "Гав";


51  // Setup
const myDog = {
  "name": "Happy Coder",
  "legs": 4,
  "tails": 1,
  "friends": ["freeCodeCamp Campers"],
  "bark": "woof"
};
  delete myDog["tails"]
// Only change code below this line


52  // Setup
function phoneticLookup(val) {
  let result = "";

  // Only change code below this line
 const lookup = {
   
     "alpha":"Adams",
      
    "bravo": "Boston",
      
     "charlie": "Chicago",
     
     "delta":"Denver",
      
   "echo":"Easy",
      
    "foxtrot": "Frank"
  }

   result = lookup[val];
  

  // Only change code above this line
  return result;
}

phoneticLookup("charlie");



53  function checkObj(obj, checkProp) {
  // Only change code below this line
 if(obj.hasOwnProperty(checkProp) === true){
   return obj[checkProp]
 } else{
   return "Not Found"
 }




  return "Change Me!";
  
  // Only change code above this line
}


54   const myMusic = 
[
  {
    "artist": "Billy Joel",
    "title": "Piano Man",
    "release_year": 1973,
    "formats": [
      "CD",
      "8T",
      "LP"
    ],
    "gold": true
  },
{
"artist":"",
 "title":"",
  "release_year": 1925,
 "formats":["1","2"]
}
];


55   const myStorage = {
  "car": {
    "inside": {
      "glove box": "maps",
      "passenger seat": "crumbs"
     },
    "outside": {
      "trunk": "jack"
    }
  }
};

const gloveBoxContents = myStorage.car.inside["glove box"];



56   const myPlants = [
  {
    type: "flowers",
    list: [
      "rose",
      "tulip",
      "dandelion"
    ]
  },
  {
    type: "trees",
    list: [
      "fir",
      "pine",
      "birch"
    ]
  }
];

const secondTree = myPlants[1].list[1];




57  // Setup
const myArray = [];

// Only change code below this line
let i = 0;

while (i <= 5) {
  myArray.unshift(i);
  i++;
}


58 // Setup
const myArray = [];

// Only change code below this line
for(let i = 1; i<6;i++){
  myArray.push(i)
}


59 // Setup
const myArray = [];

// Only change code below this line
for(let i = 1; i<=9;i+=2){
  myArray.push(i)
}
