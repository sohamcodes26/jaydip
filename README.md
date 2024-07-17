<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My own Card</title>
    <style>
      body{
    background-color: rgb(235, 227, 216);
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}
.card{
    width: 22vw;
    border-radius: 15px;
    overflow: hidden;
    text-align: center;
    box-shadow: 0px 4px 8px rgb(125, 117, 117);
}
.card-image img{
    width: 100%;
    height: 100%;
}
.card-content{
    padding: 20px;
}
.tags{
    display: flex;
    justify-content: center;
    gap: 40px;
    margin-bottom: 15px;
    list-style-type: none;
}
.tag{
    border-radius: 50px;
    padding: 5px 10px;
    font-size: 13px;
    background-color: rgb(192, 186, 179);
    font-weight: 500;
}
.card-heading{
    margin: 10px 0;
    font-size: 24px;
    color: #333;
}
.card-description{
    font-size: 14px;
    color: #4a4747;
    margin-bottom: 20px;
}
.read-more{
    display: inline-block;
    padding: 10px 20px;
    background-color: rgb(134, 205, 233);
    color: rgb(58, 60, 151);
    border-radius: 50px;
    text-decoration: none;
    font-size: 14px;
}
.read-more:hover{
    background-color: rgb(27, 150, 199);
}
    </style>
</head>
<body>
    <div class="card">
        <div class="card-image">
            <img src="https://static.vecteezy.com/system/resources/previews/031/535/490/non_2x/flowers-in-the-sun-lake-mountains-flowers-nature-nature-hd-wallpaper-ai-generated-free-photo.jpg" alt="Image Not Loading">
        </div>
        <div class="card-content">
            <div class="tags">
                <li class="tag">Nature</li>
                <li class="tag">Lake</li>
            </div>
            <h2 class="card-heading">Lago di Braies</h2>
            <p class="card-description">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dignissimos, perferendis optio illum debitis numquam tempora.</p>
            <a href="#" class="read-more">Read More</a>
        </div>
    </div>
    
</body>
</html>
