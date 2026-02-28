<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Web Dev - Lab1</title>

<style>

body{
    background-color: #eeeeee;
    font-family: "Times New Roman", serif;
    border: 8px solid black;
    padding: 40px;
}

/* العنوان الرئيسي */
h1{
    text-align: center;
    font-size: 45px;
    margin-bottom: 10px;
}

/* العنوان الأحمر */
.lab-title{
    text-align: center;
    color: red;
    text-decoration: underline;
    font-size: 28px;
    margin-bottom: 50px;
}

/* تقسيم الصفحة قسمين */
.container{
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
}

/* الجهة اليسرى */
.info{
    width: 70%;
    font-size: 20px;
}

/* الكلمات باللون الأخضر */
.label{
    color: green;
    font-weight: bold;
}

/* الصورة */
.image{
    width: 30%;
}

.image img{
    width: 100%;
    height: auto;
}

</style>
</head>

<body>

<h1>Welcome to my Web Site</h1>

<div class="lab-title">
    Web Development (Lab1)
</div>

<div class="container">

    <div class="info">
        <p><span class="label">Full name:</span> Houri ben Omar</p>
        <p><span class="label">Age:</span> 20 years old</p>
        <p><span class="label">Class:</span> 2<sup>nd</sup> LMD computer Science</p>
        <p><span class="label">University:</span> University of EL OUED</p>
    </div>

    <div class="image">
        <img src="https://www.aljazeera.net/wp-content/uploads/2024/10/road-ruins-Lebanon-Tyre-1727946739.webp?resize=770%2C513&quality=80" alt="House">
    </div>
    </div>

</body>
</html>>
