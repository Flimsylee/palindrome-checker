function palindromeCheck(str){
 str = str.replace(/[^A-Za-z]/g, '').toLowerCase();
  if (str === str.split('').reverse().join('')) {
    
    console.log(`${str} is a palindrome`);
    
  }
  else {
    console.log(`${str} is not a palindrome`);
  }
}

palindromeCheck("dad");
palindromeCheck("kettle");
palindromeCheck("mo2m");
