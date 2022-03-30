function palindrome(str) {
  // cleaning the code
  let str1 = str.replace(/[.,\/#!$%\^&\*;:{}=\-_`~()]/g,"");
  let str2 = str1.replace(/ /g, "");
  let str3 = str2.toLowerCase();
  
  let len = str3.length;
  
  for(let i = 0 ; i < len/2 ; i++) {
    if(str3[i] != str3[len - 1 - i])
        { console.log(str3[i] + " " + str3[len - 1 - i])
          return false;
        } 
    }
    return true;
}

console.log(palindrome("1 eye for of 1 eye."))
