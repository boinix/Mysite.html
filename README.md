# Mysite.html
<!DOCTYPE html>
<html>
<head>
    <title>Shoe Store</title>
</head>

<body bgcolor="#f2f2f2">

<center>
    <h1>👟 Welcome to Shoe World 👟</h1>
    <p>Your one-stop shop for quality shoes</p>
</center>

<hr>

<h2>Our Shoes</h2>

<table border="1" width="100%" cellpadding="10">
    <tr>
        <th>Image</th>
        <th>Name</th>
        <th>Description</th>
        <th>Price</th>
    </tr>

    <tr>
        <td align="center">
            <img src="https://via.placeholder.com/150" alt="Running Shoes">
        </td>
        <td>Running Shoes</td>
        <td>Comfortable and lightweight shoes for daily running.</td>
        <td>$59.99</td>
    </tr>

    <tr>
        <td align="center">
            <img src="https://via.placeholder.com/150" alt="Casual Shoes">
        </td>
        <td>Casual Shoes</td>
        <td>Perfect for everyday wear and casual outings.</td>
        <td>$49.99</td>
    </tr>

    <tr>
        <td align="center">
            <img src="https://via.placeholder.com/150" alt="Formal Shoes">
        </td>
        <td>Formal Shoes</td>
        <td>Elegant shoes suitable for office and formal events.</td>
        <td>$79.99</td>
    </tr>
</table>

<hr>

<h2>Order Now</h2>

<form>
    <p>
        Name:<br>
        <input type="text" name="name">
    </p>

    <p>
        Email:<br>
        <input type="email" name="email">
    </p>

    <p>
        Select Shoe:<br>
        <select name="shoe">
            <option>Running Shoes</option>
            <option>Casual Shoes</option>
            <option>Formal Shoes</option>
        </select>
    </p>

    <p>
        Size:<br>
        <input type="number" name="size">
    </p>

    <p>
        <input type="submit" value="Buy Now">
    </p>
</form>

<hr>

<center>
    <p>© 2026 Shoe World | All Rights Reserved</p>
</center>

</body>
</html>
