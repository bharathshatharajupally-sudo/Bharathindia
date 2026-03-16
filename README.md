<!DOCTYPE html>
<html>
<head>
<title>Bharath Fashion Store</title>

<style>
body{
font-family: Arial;
background:#f5f5f5;
text-align:center;
}

header{
background:black;
color:white;
padding:20px;
font-size:28px;
}

.product{
border:1px solid #ccc;
width:220px;
display:inline-block;
margin:20px;
padding:10px;
background:white;
}

button{
background:black;
color:white;
padding:10px;
border:none;
cursor:pointer;
}
</style>

<script>
function buyProduct(price){
window.location.href="upi://pay?pa=9440093201@ybl&pn=BharathFashion&am="+price+"&cu=INR";
}
</script>

</head>

<body>

<header>Bharath Fashion Store</header>

<h2>Best Clothes Collection</h2>

<div class="product">
<h3>T Shirt</h3>
<p>Price: ₹499</p>
<button onclick="buyProduct(499)">Buy Now</button>
</div>

<div class="product">
<h3>Jeans</h3>
<p>Price: ₹999</p>
<button onclick="buyProduct(999)">Buy Now</button>
</div>

<div class="product">
<h3>Jacket</h3>
<p>Price: ₹1499</p>
<button onclick="buyProduct(1499)">Buy Now</button>
</div>

</body>
</html>
