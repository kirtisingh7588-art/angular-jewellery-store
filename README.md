<!DOCTYPE html>
<html lang="en">
<head>

<meta charset="UTF-8">
<title>Jewellery Store</title>

<style>

body{
font-family:Arial;
margin:0;
background:#f5f5f5;
}

header{
background:black;
color:white;
padding:15px;
text-align:center;
}

nav a{
color:white;
margin:10px;
text-decoration:none;
}

.container{
display:flex;
justify-content:center;
gap:20px;
padding:20px;
}

.card{
background:white;
border:1px solid gray;
padding:15px;
width:220px;
text-align:center;
border-radius:10px;
}

.card img{
width:100%;
height:150px;
object-fit:cover;
border-radius:5px;
}

button{
background:gold;
border:none;
padding:10px;
margin-top:10px;
cursor:pointer;
}

button:hover{
background:orange;
}

footer{
background:black;
color:white;
text-align:center;
padding:10px;
margin-top:20px;
}

</style>

</head>

<body>

<header>

<h1>💎 Kirti Jewellery Store</h1>

<nav>
<a href="#">Home</a>
<a href="#">Necklace</a>
<a href="#">Rings</a>
<a href="#">Contact</a>
</nav>

</header>


<div class="container">

<div class="card">
<img src="https://cdn.pixabay.com/photo/2017/08/06/11/59/gold-2590899_1280.jpg">
<h3>Gold Necklace</h3>
<p>Price: ₹50,000</p>
<button onclick="buy()">Buy Now</button>
</div>

<div class="card">
<img src="https://cdn.pixabay.com/photo/2016/11/29/04/17/ring-1867213_1280.jpg">
<h3>Diamond Ring</h3>
<p>Price: ₹25,000</p>
<button onclick="buy()">Buy Now</button>
</div>

<div class="card">
<img src="https://cdn.pixabay.com/photo/2017/08/06/22/01/bangles-2591221_1280.jpg">
<h3>Gold Bangles</h3>
<p>Price: ₹30,000</p>
<button onclick="buy()">Buy Now</button>
</div>

</div>


<footer>
<p>© 2026 Kirti Jewellery Store</p>
</footer>


<script>

function buy(){
alert("Item added to cart!");
}

</script>

</body>
</html>
