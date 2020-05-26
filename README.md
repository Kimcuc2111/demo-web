
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="utf-8" />
    <meta name="author" content="Script Tutorials" />
    <title>Stylish responsive footer | Script Tutorials</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
 
    <!-- css font and stylesheet -->
    <link href="css/styles.css" rel="stylesheet">
</head>
<body>
    <!-- Your custom main content is here -->
 
    <footer>
        <div class="splitter"></div>
        <ul>
            <!-- three footer columns are here -->
        </ul>
 
        <div class="bar">
            <div class="bar-wrap">
                <ul class="links"> <!-- footer menu -->
                    <li><a href="#">Home</a></li>
                    <li><a href="#">License</a></li>
                    <li><a href="#">Contact Us</a></li>
                    <li><a href="#">Advertise</a></li>
                    <li><a href="#">About</a></li>
                </ul>
 
                <div class="social">
                    <!-- social icons are here -->
                </div>
                <div class="clear"></div>
                <div class="copyright">&copy;  2014 All Rights Reserved</div>
            </div>
        </div>
    </footer>
 
</body>
</html>
<ul>
    <li>
        <div class="icon" data-icon="E"></div>
        <div class="text">
            <h4>About</h4>
            <div>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin tristique justo eu sollicitudin pretium. Nam scelerisque arcu at dui porttitor, non viverra sapien pretium. Nunc nec dignissim nunc. Sed eget est purus. Sed convallis, metus in dictum feugiat, odio orci rhoncus metus. <a href="#">Read more</a></div>
        </div>
    </li>
    <li>
        <div class="icon" data-icon="a"></div>
        <div class="text">
            <h4>Archive</h4>
            <div>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin tristique justo eu sollicitudin pretium. Nam scelerisque arcu at dui porttitor, non viverra sapien pretium. Nunc nec dignissim nunc. Sed eget est purus. Sed convallis, metus in dictum feugiat, odio orci rhoncus metus. <a href="#">Read more</a></div>
        </div>
    </li>
    <li>
        <div class="icon" data-icon="s"></div>
        <div class="text">
            <h4>Cloud</h4>
            <div>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin tristique justo eu sollicitudin pretium. Nam scelerisque arcu at dui porttitor, non viverra sapien pretium. Nunc nec dignissim nunc. Sed eget est purus. Sed convallis, metus in dictum feugiat, odio orci rhoncus metus. <a href="#">Read more</a></div>
        </div>
    </li>
</ul>
<div class="bar">
    <div class="bar-wrap">
        <ul class="links">
            <li><a href="#">Home</a></li>
            <li><a href="#">License</a></li>
            <li><a href="#">Contact Us</a></li>
            <li><a href="#">Advertise</a></li>
            <li><a href="#">Telephone</a></li>
             <li><a href="#">About</a></li>
        </ul>
 
        <div class="social">
            <a href="#" class="fb">
                <span data-icon="f" class="icon"></span>
                <span class="info">
                    <span class="follow">Become a fan Facebook</span>
                    <span class="num">9,999</span>
                </span>
            </a>
 
            <a href="#" class="tw">
                <span data-icon="T" class="icon"></span>
                <span class="info">
                    <span class="follow">Follow us Twitter</span>
                    <span class="num">9,999</span>
                </span>
            </a>
 
            <a href="#" class="rss">
                <span data-icon="R" class="icon"></span>
                <span class="info">
                    <span class="follow">Subscribe RSS</span>
                    <span class="num">9,999</span>
                </span>
            </a>
        </div>
        <div class="clear"></div>
        <div class="copyright">&copy;  2014 All Rights Reserved</div>
    </div>
</div>
div#footer {
    clear: both;
}

div#footer div.fLeft {
    float: left;
    width: 340px;
}

div#footer div.fRight {
    float: right;
    width: 530px;
}

div#footer {
    zoom: 1;
}

div#footer:after {
    clear: both;
    content: ".";
    display: block;
    height: 0;
    line-height: 0;
    visibility: hidden;
}
