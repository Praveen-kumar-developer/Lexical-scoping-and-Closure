# Lexical-scoping-and-Closure

function outer() {  
  let username = "Mr praveen kumar";
  function inner() {
    console.log("inner", username);
  }
  inner();
}
 outer();
