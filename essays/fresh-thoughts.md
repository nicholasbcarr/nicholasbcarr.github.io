---

layout: essay

type: essay

title: Fresh Thoughts on javaScript

# All dates must be YYYY-MM-DD format!

date: 2021-09-01

labels:

  - Software Engineering

  - Learning

  - javaScript

---

<img class="ui tiny left circular floated image" src="../img/kayak.jpg">



## Intro to javaSCript

My *introduction* to javaScript this semester went nicely. This is now the 4th language (java, C, C++ being the others) that I have learned. I remember my first ICS class, my professor said that each time you learn a language it will be easier. When I learned C/C++, I thought maybe this wasn't true but I realized that when I learned C/C++ that I had properly understood a language for the first time. When I looked backed on some old java programs I wrote, I realized that I fully grasped all the in and outs of that as well. 

### Big Differences

This week was my introduction to javaScript. My first assignment was to go through a coding bootcamp to solve a variety of small problems to get comfortable with the new syntax and tools. I noticed that javaScript was the easiest to pick up out of everything so far meaning that my old professor was obviously right. After taking ICS-212, javaScript seems to be much looser. The very first difference I noticed was how parameters were passed. I wondered how does the program know. Well, I realized it doesn't really. Essentially you could pass in any data type to a function and if the data types play nicely with the function it will work even though maybe it wasn't intended to. I thought this was pretty cool because it is not something I learned how to do in C/C++.

Arrays and objects were the next difference I noticed. In my opinion, building arrays and objects in javaScript is exactly in the middle of objects in java and structures in C/C++. The way they are represented and referenced in javaScript at first seemed kind of funky, but once I grasped how to properly navigate them, I started to enjoy it. Strings are also much less difficult to manipulate as they seem to be stored in an array type structure from the beginning. In C/C++, it was some work to split a string whereas with javaScript it seemed easier (when i learned C/C++ we were limited to certain libraries, data types, and functions). 

#### Strive for Greatness

My biggest weakness out of the code camp and assignments was the arrow functions. I understand what they do and how they strip away a lot of the typing I have to do, but I guess I need to get to an application standpoint first where I can personally see why it would be preferred over writing a function. So far in my education, I have written everything in a specific format and I think that this semester in javaScript we have the ability to have some freedom in our styling of programs. I look forward to learning more about javaScript and the other new tools it will provide me with.

In conclusion, I am feeling confident when it comes to using javaScript so far. I do know that learning a new language has its up and downs, I will have to be prepared to take on these challenges, but I believe my current knowledge and the resources I have available in class will lead to my ultimate success.

##### pWod Example

Here is a small example of our second small excersize used to warm up to javaScript. This function checks a string to make sure there are no repeated characters.

```

function isUnique(str) {

  for (let i = 0; i < str.length - 1; i++) {

    for (let j = i + 1; j < str.length; j++) {

      if (str[i] === str[j]) {

        return false;

      }

    }

  }

  return true;  

}

console.log(isUnique('abcde'));   

console.log(isUnique('abcdea')); //test

```




