
// Use the jquery-Validation library To check input data  https;
//jqueryvalidation.org/;
Button1.onclick = function() {
  if($("#Container1").valid()) {
    NSB.MsgBox("Form checked - all fields OK!");
 } else {
    NSB.MsgBox("Please fix indicated fields.");
  }
};

function Main() {

var validateRules = {  rules: {  Input1: "required",Input2: { required: true,email: true },Textarea1: "required",Select1: "required",},messages: {  Input2: "Please enter a valid email address.",Select1: "Please choose one of the values.",},};

  NSB.validation(Container1, validateRules);

}


Form1.onshow=function(){
  alert("Enter anything into the required input, a SSN, an email address, and a phone number")
}