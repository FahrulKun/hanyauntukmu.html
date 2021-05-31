<html>
<head>
<title> INI SERIUS </title>

<script type="text/javascript">
flag=1
function f1()
{
    alert("Oke Mulai Hari Ini Kita Pacaran Yah")
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
            Bn.style.top=400
            Bn.style.left=166
            flag=1
        }
}
</script>

</head>
<body>
<h1> Surat Cinta Untukmu <h1>
<img alt="EvilicaCell" src="https://i.ibb.co/3r06M4x/a0cdcd089c31.jpg" height="200" />
<h1 style="#">Kamu Mau Ga Jadi Pacarku?</h1>
<div id="By" style="position:absolute; left:64px; top:370px; width:210px;
height:210px;">
<input type="button" value=" YA " onClick="f1()" />
</div>
<div ID="Bn" style="position:absolute; left:166px; top:370px; width:210px; height:210px;">
<input type="button" value=" TIDAK " onMouseOver="f()" />
</div>

</body>
</html>
