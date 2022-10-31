
<html>
<head>
<title>turbold</title>

<script type="text/javascript">
flag=1
function f1()
{
    var Name = prompt("minii hair hairdelda dime");
    
    if(Name == "" || Name == null) {
    alert("um bjkuol im um garj irn");
    } else {
    alert ("haira ene no dargdku hodlon ingsh ")
    alert("unji ")
    alert("buur mash ih haira mash ih ")
    alert("hairn jondoo ih hairdeshu da ")
    alert("mini hairi bjsen um, " + Name + ", ene bjsen umn hairdn hargdkushu da."); 
    }
}
function f()
{
    if(flag==1)
        {
            Bn.style.top=400
            Bn.style.left=300
            flag=2
        }
    else if(flag==2)
        {
            Bn.style.top=400
            Bn.style.left=50
            flag=3
        }
    else if(flag==3)
        {
            Bn.style.top=370
            Bn.style.left=166
            flag=1
        }
}
</script>

</head>
<body>
<h1>hairdenmu</h1>
<img src="https://media.tenor.com/AIpN-WzvXi8AAAAi/love.gif" height="200" />
<h1 style="#">haira mash ih hairdeshu ja yes no dern darj ujere</h1>
<div id="By" style="position:absolute; left:64px; top:370px; width:210px;
height:210px;">
<input type="button" value=" yes " onClick="f1()" />
</div>
<div ID="Bn" style="position:absolute; left:300px; top:370px; width:210px; height:210px;">
<input type="button" value=" no " onMouseOver="f()" />
</div>

</body> 
</html>
