# Ex.05 Book Front Cover Page Design
# Date:25.05.2026
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:

<!DOCTYPE html>
<html>
<head>
<title>Wings of Fire</title>

<style>

body{
display:flex;
justify-content:center;
align-items:center;
height:100vh;
background:#cfe6ff;
font-family:Arial;
}

.book{
width:500px;
height:980px;
background:url('https://images.unsplash.com/photo-1500530855697-b586d89ba3ee');
background-size:cover;
color:white;
text-align:center;
padding:30px;
position:relative;
border-radius:15px;
}

h1{
color:gold;
font-size:55px;
}

h2{
font-size:30px;
margin-bottom:20px;
}

.mainimg{
width:100px;
height:100px;
border:4px solid white;
border-radius:15px;
}

.summary{
background:rgba(0,0,0,0.45);
padding:18px;
font-size:20px;
line-height:1.6;
border-radius:15px;
margin-top:25px;
text-align:justify;
}

.author{
display:flex;
align-items:center;
gap:20px;
background:white;
color:black;
padding:15px;
border-radius:15px;
margin-top:100px;
text-align:left;
}


.author h3{
color:#003366;
margin-bottom:8px;
}

.author p{
font-size:17px;
line-height:1.5;
}

.footer{
position:absolute;
bottom:0;
left:0;
width:92%;
border-radius: 20%;
background:#001f54;
padding:18px;
display:flex;
justify-content:space-between;
font-size:22px;
}

.price{
color:yellow;
font-weight:bold;
}

</style>
</head>

<body>

<div class="book">

<h1>WINGS OF FIRE</h1>
<h2>Dr. A.P.J. Abdul Kalam</h2>

<div class="summary">
"Wings of Fire" is the autobiography of Dr. A.P.J. Abdul Kalam. 
The book describes his journey from a small town in Rameswaram 
to becoming one of India’s greatest scientists and the Missile Man 
of India through hard work, dedication, and dreams.
</div>

<div class="author">

<img src="abdul Kalam.png" width="120" height="120" alt="A.P.J. Abdul Kalam">

<div>
<h3>About the Author</h3>

<p>
Dr. A.P.J. Abdul Kalam was an Indian scientist and the 11th President of India. 
He inspired millions through his achievements, leadership, and motivational thoughts.
</p>

</div>

</div>

<div class="footer">
<div>Inspire India Publications</div>
<div class="price">₹599</div>
</div>

</div>

</body>
</html>

# OUTPUT:

![alt text](image.png)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
