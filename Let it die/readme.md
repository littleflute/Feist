[v0.0.6](https://github.com/littleflute/Feist/edit/master/Let%20it%20die/readme.md)

[show this page](https://littleflute.github.io/Enya/Shepherd%20moons)

[home](..)



<audio controls id="player"> 
  <source src="https://littleflute.github.io/Feist/Let%20it%20die/cd/01 曲目 1 未知艺术家 未知唱片集 (2015-11-28 23-33-51) 未知 192kbps.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
<div id="xd"> 
</div>
<script>
var d = document.getElementById("xd"); 
var html = d.innerHTML; 
for(var n=1; n<=12; n++)
{	
 	html += fNewBtn(n);

} 
d.innerHTML = html;

var p = document.getElementById("player");
function f(i)
{
    var s = "https://littleflute.github.io/Feist/Let%20it%20die/cd/";
    if(i<10) 
    {
    	s += "0";
    } 
    s += i;
    s += " 曲目 ";
    s += i;
    s += " 未知艺术家 未知唱片集 (2015-11-28 23-33-51) 未知 192kbps.mp3";
    
	p.src = s; 
    p.play();
}
function fNewBtn(i)
{
	var rHTML = "";
    rHTML = "<button onclick='f(";
    rHTML += i;
    rHTML += ");'>";
    rHTML += i;
    rHTML += "</button>";
    return rHTML;
}
</script>
