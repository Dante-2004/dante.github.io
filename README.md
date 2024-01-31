<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="/Projects/valentine.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
    <script>
        $(document).ready(function () {
    $('.container').mouseenter(function () {
        $('.card').stop().animate({
            top: '-90px'
        }, 'slow');
    }).mouseleave(function () {
        $('.card').stop().animate({
            top: 0
        }, 'slow');
    });
});
    </script>
    <title></title>
</head>
<body>

    <div class="container">
    <div class="valentines">
        <div class="envelope"></div>
        <div class="front"></div>
        <div class="card">
        <div class="text">Happy</br> Valentine's</br> Day!</div>
        <div class="heart"</div>
        </div>
        <div class="hearts">
            <div class="one"></div>
            <div class="two"></div>
            <div class="three"></div>
            <div class="four"></div>
            <div class="five"></div>
        </div>
    </div>
    </div>
    <div class="shadow"></div>
    </div>
</body>
</html>
