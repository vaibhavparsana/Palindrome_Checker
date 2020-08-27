function palindrome(str) {
 

  var newString2 = str.split(/[\W_]/g).join().toLowerCase();
  var newStr = newString2.replace((/[\W_]/g), "");
  

  var strLength = newStr.length;
  console.log(" String Length: " + newStr.length);
  var frontCounter = 0;
  console.log(" Front Counter: " + frontCounter);
  var endCounter = newStr.length - 1;
  console.log(" End Counter: " + endCounter);
  var middleNumber = 0;
  if (strLength % 2 === 0) {
    middleNumber = strLength / 2;
  } else {
    middleNumber = (strLength / 2) + 0.5;
  }
  console.log(" Middle Number: " + middleNumber);

  for (var i = 0; i < newStr.length; i++) {
    if (i !== middleNumber) {
      if (newStr[i] === newStr[endCounter - i]) {
        console.log(newStr[i] + " Matching Condition True At: " + newStr[endCounter - i]);
      } else {
        console.log(newStr[i] + " Matching Condition False At: " + newStr[endCounter - i]);
        return false;
      }
    }
    else {
      console.log(" Middle Condition True At: " + i);
    }
  }
  console.log(" Final Output: " + newStr);
  return true;
}



palindrome("A man, a plan, a canal. Panama");
