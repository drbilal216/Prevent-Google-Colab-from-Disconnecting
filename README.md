# Prevent-Google-Colab-from-Disconnecting
So to prevent this just run the following code in the console. Ctrl+ Shift + i to open inspector view . Then goto console. and paste code below


function ClickConnect(){
console.log("Working"); 
document.querySelector("colab-toolbar-button#connect").click() 
}
setInterval(ClickConnect,60000)
