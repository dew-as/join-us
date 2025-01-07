
About Me.
---------

1.Introduce yourself.
--------------------
I'm Aswindev S Namboothiri, a self-taught MERN stack developer from Trivandrum, Kerala. I am passionate about web development and have hands-on experience in building modern applications using technologies like JavaScript, React.js, Node.js, Express.js, and MongoDB. I strive for continuous learning and aim to work on innovative projects that help me expand my skills.

2.Do you own a personal computer?
----------------------------------
Yes, I own a personal computer and it is my primary device for development.

Describe your development environment.
---------------------------------------
My development environment consists of:

Operating System: Windows 10
IDE/Editor: Visual Studio Code (VSCode)
Config Manager: Git for version control, and Docker for containerized environments.

Social Profile
--------------

Linkdn : https://www.linkedin.com/in/aswin-dev-dewas/
------

Github : https://github.com/dew-as
------

Portfolio : https://portfolio-minimal-khaki.vercel.app/
---------

CV : https://docs.google.com/document/d/1JvX1jHqYNfDNZNyA92amQFyYutfW26Nz/edit?usp=sharing&ouid=105361527382138206482&rtpof=true&sd=true

StackOverflow : https://stackoverflow.com/users/29089810/aswindev

The real stuff
--------------

JavaScript (Primary language)

function that takes a number and returns a list of its digits in an array
--------------------------------------------------------

function numberToDigits(num) {
    const numStr = num.toString();
    const digitsArr = [];
    for (let i = 0; i < numStr.length; i++) {
        digitsArr.push(Number(numStr[i]));
    }
    return digitsArr;
}

Remove duplicates of an array and return an array of only unique elements.
----------------------------------------------------------

function removeDuplicates(arr) {
    const uniqueArr = [];
    for (let i = 0; i < arr.length; i++) {
        if (!uniqueArr.includes(arr[i])) {
            uniqueArr.push(arr[i]);
        }
    }
    return uniqueArr;
}

Write a function that translates a text to Pig Latin and back.
----------------------------------------------------------

function toPigLatin(text) {
    return text.split(' ').map(word => {
        let firstLetter = word[0];
        return word.slice(1) + firstLetter + 'ay';
    }).join(' ');
}

function toEnglish(pigLatinText) {
    return pigLatinText.split(' ').map(word => {
        return word.slice(0, word.length - 2) + word[word.length - 3];
    }).join(' ');
}

Write a function that rotates a list by k elements.
---------------------------------------------------

function rotateList(arr, k) {
    k = k % arr.length; 
    for (let i = 0; i < k; i++) {
        arr.push(arr.shift());
    }
    return arr;
}

"Thankyou For Considering My Application"
