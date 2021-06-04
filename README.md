### Description

Installing and setting up your personal computer with the software tools required for this course, practicing using software tools, practicing terminal or shell commands, practicing keyboard shortcuts, and creating your first Node.js server-side JavaScript file.

### Code

/*
    CIT 281 Lab 1
    Name: Troy Munson
*/
function square(num) {
    return num*num;
}
console.log('Square operations:')
for (let i = 2; i <= 10; i+=2) {
    console.log(`Square of ${i} is ${square(i)}`);
}
