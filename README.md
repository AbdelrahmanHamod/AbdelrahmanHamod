get elements into variable
var inputEle = document.getElementById("input");
var buttonEle = document.getElementById("btn");
var msgEl = document.getElementById("msg")

// Events

buttonEle.onclick = function() {

    // get value from input
    var inputValue = inputEle.value; 
    
    // put input Value into P
    msgEl.innerHTML = inputValue

    // empty input value
    inputEle.value = ""

}

<!---
AbdelrahmanHamod/AbdelrahmanHamod is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
