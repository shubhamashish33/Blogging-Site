# Blogging-Site
This website is made of pure Bootstrap. I've used CSS to design some stuff according to my liking. This is not responsive one if I do that I will modify the code. Also there is no CSS file as I have used internal CSS.
## Setup
Step 1: First you have to add following code in head tag
```html
 <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KyZXEAg3QhqLMpG8r+8fhAXLRk2vvoC2f3B09zVXn8CA5QIVfZOJ3BCsw2P0p/We" crossorigin="anonymous">
```
Step 2: Here is following [cheatsheet](https://hackerthemes.com/bootstrap-cheatsheet/) to use in the project. \
Step 3: If you need to import [icons](https://icons.getbootstrap.com/) from Bootstrap Website you have to add following code to the head tag.
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.5.0/font/bootstrap-icons.css">
```
## Sample Code
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blogger's Zone</title>
    <link rel="stylesheet" href="style.css">
    <link rel="shortcut icon" href="./5.png" type="image/x-icon">
    <!-- CSS only -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-KyZXEAg3QhqLMpG8r+8fhAXLRk2vvoC2f3B09zVXn8CA5QIVfZOJ3BCsw2P0p/We" crossorigin="anonymous">
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.5.0/font/bootstrap-icons.css">
</head>
<style>
    @import url('https://fonts.googleapis.com/css2?family=Roboto+Mono:wght@300&display=swap');

    .border-bottom {
        border-bottom: 2px solid gray !important;
    }

    .hh{
        width: 100px;
        height: 100px;
        border-radius: 50%;
    }
    .fs-5 {
        font-family: 'Roboto Mono', monospace;
    }

    .btn {
        margin-left: 37% !important;
    }
    .text-dark{
        flex: 1;
    }
</style>

<body>
    <div class="m-5 border-bottom pb-3">
        <h3 class="text-center fs-1">The <span class="text-warning">Blogging</span> Site</h3>
    </div>
    <div class="row m-3">
        <h3 class="text-center mb-3">
            Top Blogger of the Week!???
        </h3>
        <div class="col-md-4 p-3">
            <div class="pp d-flex">
                <img src="./1.jpeg" alt="" class="hh img-fluid mb-3">
                <a href="" class="btn btn-primary m-5 px-5">Follow</a>
            </div>
            <p class="fs-5">@kdstra</p>
            <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio at praesentium vero minus, tempore omnis
                tenetur hic esse ab assumenda alias necessitatibus? Iure assumenda delectus saepe aut ipsum reiciendis
                vero? Impedit pariatur, nam magni eaque, excepturi reprehenderit repellat voluptatem qui dolore
                voluptate laudantium corrupti blanditiis expedita exercitationem ex hic repudiandae.
            </p>
        </div>
        <div class="col-md-4 p-3">
            <div class="pp d-flex">
                <img src="./2.jpeg" alt="" class="hh img-fluid mb-3">
                <a href="" class="btn btn-outline-primary m-5 px-5">Following</a>
            </div>
            <p class="fs-5">@syswrit</p>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ab repellat obcaecati quae vero vel explicabo,
                nihil, architecto adipisci voluptatibus ipsum minima harum sunt quaerat suscipit, veritatis quod
                voluptas officiis assumenda?</p>
        </div>
        <div class="col-md-4 p-3">
            <div class="pp d-flex">
                <img src="./3.jpeg" alt="" class="hh img-fluid mb-3">
                <a href="" class="btn btn-primary m-5 px-5">Follow</a>
            </div>
            <p class="fs-5">@mdtra</p>
            <p>
                Lorem ipsum dolor, sit amet consectetur adipisicing elit. Non accusantium numquam, nihil dolore a vel
                iste consectetur mollitia delectus dignissimos.
            </p>
        </div>
    </div>
    <div class="card m-5 rounded">
        <h3 class="text-center mt-3">Today's Blog</h3>
        <div class="card-body d-flex">
            <img src="./4.jpeg" alt="" class="img-fluid m-5">
            <p class="m-5">
                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Accusantium obcaecati nisi ipsum illo maxime, fugit sit culpa ipsa minus porro atque nobis tempora repellat, quos corporis eius voluptatibus. Officiis officia dolore in reprehenderit eaque, deleniti placeat ipsum dolorem sequi quasi tenetur adipisci tempora accusamus minus numquam, sed voluptatum quisquam aut ipsa impedit temporibus. Voluptas atque cupiditate voluptatem ipsam, necessitatibus culpa alias sit ad sunt! Facere accusamus maiores ullam enim eaque odio quidem adipisci officia ipsa saepe? Ullam aut error modi? Alias enim fugiat, voluptas suscipit quas sapiente, rerum molestiae nisi autem pariatur laborum, ipsa quasi veritatis vel rem beatae totam.
            </p>
        </div>
        <div class="d-flex">
        <a href="" class="text-dark fs-5 text-center mb-5 mt-1 m-5"><i class="bi bi-heart"></i></a>
        <a href="" class="text-dark fs-5 text-center mb-5 mt-1 m-5"><i class="bi bi-chat-left"></i></a>
    </div>
    </div>
    <footer>
        <h5 class="text-center m-5">
        Made with ??? by Shubham Ashish
    </h5>
    </footer>
</body>

</html>
```

## Screenshot 
![screencapture-127-0-0-1-5500-index-html-2021-08-05-22_35_48](https://user-images.githubusercontent.com/78084828/128391739-fa2425c3-4dd3-4e71-aba5-88b82bf88db5.png)
