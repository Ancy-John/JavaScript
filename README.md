# JavaScript
Code of JS for web development
*******************************************************************************************************************************8


const logregBox = document.querySelector('.logreg-box');
const loginLink = document.querySelector('.login-link');
const registerLink = document.querySelector('.register-link');

registerLink.addEventListener('click',()=> {logregBox.classList.add('active');});

loginLink.addEventListener('click',()=> {logregBox.classList.remove('active');});
