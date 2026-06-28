<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Paws - Tiersitting</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:#f8fafc;
    color:#333;
    line-height:1.6;
}

header{
    min-height:100vh;
    background:linear-gradient(135deg,#4CAF50,#6dd5ed);
    color:white;
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:25px 8%;
}

nav ul{
    list-style:none;
    display:flex;
    gap:30px;
}

nav a{
    color:white;
    text-decoration:none;
    font-weight:bold;
    transition:.3s;
}

nav a:hover{
    color:#ffe082;
}

.hero{
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    text-align:center;
    height:80vh;
    padding:20px;
}

.hero h2{
    font-size:3.5rem;
    margin-bottom:20px;
}

.hero p{
    font-size:1.2rem;
    max-width:700px;
}

.btn{
    margin-top:35px;
    background:white;
    color:#4CAF50;
    padding:15px 35px;
    border-radius:50px;
    text-decoration:none;
    font-weight:bold;
    transition:.3s;
}

.btn:hover{
    background:#333;
    color:white;
}

.section{
    padding:90px 8%;
}

.section h2{
    text-align:center;
    margin-bottom:50px;
    font-size:2.4rem;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:30px;
}

.card{
    background:white;
    border-radius:20px;
    padding:35px;
    text-align:center;
    box-shadow:0 10px 30px rgba(0,0,0,.08);
    transition:.3s;
}

.card:hover{
    transform:translateY(-10px);
}

.card span{
    font-size:60px;
}

.light{
    background:#eef7f0;
}

.features{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:30px;
    text-align:center;
}

.features div{
    background:white;
    padding:30px;
    border-radius:20px;
    box-shadow:0 10px 25px rgba(0,0,0,.08);
}

form{
    max-width:700px;
    margin:auto;
    display:flex;
    flex-direction:column;
    gap:20px;
}

input,
textarea{
    padding:16px;
    border:none;
    border-radius:12px;
    background:#fff;
    box-shadow:0 5px 15px rgba(0,0,0,.08);
    font-size:16px;
}

textarea{
    resize:vertical;
    min-height:150px;
}

button{
    background:#4CAF50;
    color:white;
    border:none;
    padding:16px;
    border-radius:12px;
    cursor:pointer;
    font-size:17px;
    transition:.3s;
}

button:hover{
    background:#388E3C;
}

footer{
    background:#222;
    color:white;
    text-align:center;
    padding:25px;
}

@media(max-width:768px){
    nav{
        flex-direction:column;
        gap:20px;
    }

    nav ul{
        flex-direction:column;
        text-align:center;
    }

    .hero h2{
        font-size:2.4rem;
    }
}
</style>

</head>
<body>

<!-- Hier kommt der HTML-Inhalt -->

</body>
</html>
