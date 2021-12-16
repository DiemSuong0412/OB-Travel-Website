# IE104_Web-Travel
Đồ án môn học IE104
## Get header.

    <head>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
    </head>
    
    <body>
        <div class="header"></div>
        <main></main>
        <script> 
            $(function(){
              $(".header").load("header.html"); 
            });
        </script>
    </body>

## Get footer
trong folder css có file footer.css
trong folder js có file footer.js
=> muốn get footer thì trong file .html muốn get, gán link vào:
    <div id="footer"></div>    
    <script> 
        $(function(){
            $("#footer").load("footer.html"); 
        });
        </script> 
