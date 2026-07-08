function showMsg(){
let name=document.getElementById("name").value;

if(name==""){
document.getElementById("msg").innerHTML="Please enter your name";
}
else{
document.getElementById("msg").innerHTML=
"Hello " + name + "! Welcome to Cloud Lab Website";
}
}