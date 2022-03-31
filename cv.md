# Evgeny Zavetny
## Contact information:

Location: Taganrog, Russia;    
Phone: +7(987)3317684;    
E-mail: [zyzyololozyzy@gmail.com](E-mail);    
Telegram: [https://t.me/Aslekiel](Telegram);   
Discord: [https://discordapp.com/users/Hopheylalaley#8852](Discord);    
GitHub: [https://github.com/Aslekiel](GitHub);   
Codewars: [https://www.codewars.com/users/AsleKiel12](Codewars).    

*********

## About Me

Greetings! I decided to radically change the direction of my activity, since I believe that only in programming I am able to realize myself in it 100%. I have experience in managing people, stress-resistant, determined, attentive, able to learn. I spend my free time improving my skills.

*********

## Skills and Proficiency:
HTML5, CSS3;
JavaScript Basics;
Git, GitHub;
VS Code.

*********

## Code example:

KATA from CODEWARS: Write an algorithm that takes an array and moves all of the zeros to the end, preserving the order of the other elements.
```
function moveZeros(arr) {
    let count = 0;
    let result = [];

    for (let i = 0; i < arr.length; i++) {
        if (arr[i] === 0) {
            count++;
            delete arr[i];
        };
    }
    for (let elem of arr) {
        if (elem !== undefined) {
            result.push(elem);
        }
    }

    for (let j = 0; j < count; j++) {
        result.splice(result.length, 0, 0);
    }

    return result;
}
```
KATA from CODEWARS: Well met with Fibonacci bigger brother, AKA Tribonacci. As the name may already reveal, it works basically like a Fibonacci, but summing the last 3 (instead of 2) numbers of the sequence to generate the next.
```
function tribonacci(signature,n){
    let oneNum = signature[0];
    let twoNum = signature[1];
    let threeNum = signature[2];
    let arr = [];
    if (signature.length == 1) {
        twoNum = signature.push(Math.round(Math.random() * 100));
    }
    if (signature.length == 2) {
        threeNum = signature.push(Math.round(Math.random() * 100));
    }
    if (n == 0) {return signature = []};
    if (n == 1) {return signature.splice(signature.length-1)};
    if (n == 2) {return signature.splice(signature.length-2)};
    for (let i = 0; i < n - 3; i++) {
        let sum = oneNum + twoNum + threeNum;
        oneNum = twoNum;
        twoNum = threeNum;
        threeNum = sum;
        arr.push(sum);
    }
    return signature.concat(arr);
}
```
*********

## Education:
1. Southern Federal University, Institute of Radio Engineering Systems and Control: Technical operation and repair of aircraft and engines.
2. Southern Federal University, Institute of Management in Economic, Ecological and Social Systems: Jurisprudence.
3. Southern Federal University, Institute of Nanotechnologies, Electronics and Equipment Engineering: Biotechnical systems and technologies.

## Courses:
1. learn.javascript.ru;
2. code.mu;
3. JavaScript/Front-end 2022Q1.

*********

## Languages:
1. Russian - Native;
2. English - B1.