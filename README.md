# module-2sol
module-2sol
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <title>Assignment Solution for Module 2</title>
    <link href="https://fonts.googleapis.com/css?family=Raleway|Roboto|Sansita" rel="stylesheet">
    <link rel="stylesheet" type="text/css" href="stylesheet.css">
</head>

<body>
<h1>Our Menu</h1>

<div id="container">
<!-- Chicken Container -->
    <div id="op-1" class="menu">
        <div class="food-type chicken">Chicken
        </div>

            <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet nec, vulputate eget, arcu.</p>
    </div>

<!-- Beef Container -->
    <div id="op-2" class="menu">
        <div class="food-type beef">Beef
        </div>
            <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet nec, vulputate eget, arcu.</p>
    </div>


<!-- Sushi Container -->
    <div id="op-3" class="menu">
        <div class="food-type sushi">Sushi
        </div>
        <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet nec, vulputate eget, arcu.</p>
    </div>

</div>
</body>
</html>
 {
    box-sizing: border-box;
}


body {
    background: #fff;
    box-sizing: border-box;
    font-family: raleway; roboto; ransita; sans-serif;
    font-size: 200%;
    margin: 0;
}


h1 {
   text-align: center;
   font-weight: bold;
   margin: 30px 0 50px 0;
}
4
#container {
    width: 100%;
    max-width: 100%;
    margin: 0px;
    padding: 10px;
     /*display: flex;
    justify-content: space-between; */
}

.menu {
    float:left;
    width:30%;
    margin: 10px;
    background: grey;
    border: 1px solid #000;
    font-size: .75em;
    position: relative;
}
/*
div.foo {
    background: grey;
    border: 1px solid #000;
    font-size: .75em;
    position: relative;
}
*/

div.food-type {
    text-align: center;
    font-weight: bold;
    padding: 10px;
    width: 30%;
    position: relative;
    float: right;
    /*left: 70%;*/
    border-bottom: 1px solid #000;
    border-left: 1px solid #000;
}

div.chicken {
    background: pink;
}

div.beef {
    background: blue;
    color: #fff;
}

div.sushi {
    background: red;
}

p {
    color: #fff;
    padding: 10px;
    font-size: .75em;
    clear: right;
}

@media all (min-width: 992px) {
     .menu {width: 33.33%;}
}

@media all (min-width: 768px) and (max-width: 991px) {
    #op-1.menu #op-2.menu {width: 50%;}
    #id-3.menu {width: 100%;}
}

@media all (max-width: 767px) {
     .menu {width: 100%;}
}
