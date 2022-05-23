# Mini-Project-5-Event-Listeners
Event Listeners
<!DOCTYPE HTML>
<HTML LANG="EN">
    <HEAD>
    <TITLE>Mini Project #5 Event Listeners</TITLE>
    </HEAD>
    <body>
    <h1>Mini Project #5 Event Listeners</h1>
        <div>
        <label for="bgColor">Background Color</label>
            <input  type="text" class="form-control js-bg-color" id="bgColor">
        </div>
        <div>
        <label for="textColor">Text Color</label>
            <input  type="text" class="form-control js-text-color" id="textColor">
        </div>
    <div>
       <label for="fontSize">Font Size</label>
            <input  type="text" class="form-control js-font-size" id="fontSize">
        </div>
        <script>
            var bgColor= document.querySelector(".js-bg-color")
            var textColor=document.querySelector(".js-text-color")
            var fontSize =document.querySelector(".js-font-size")
            var body = document.querySelector("body")
            bgColor.addEventListener('keyup',function(event){
                                     console.log(event.target.value)
                                     body.style.backgroundColor= event.target.value
                                     }) 
          textColor.addEventListener('keyup',function(event){
                                     console.log(event.target.value)
                                     body.style. Color= event.target.value
                                     }) 
            fontSize.addEventListener('keyup',function(event){
                                     console.log(event.target.value)
                                     body.style.fontSize= event.target.value + 'px'
                                     }) 
            
             
        
        </script>
    </body>

</HTML>
