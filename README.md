<html>
    <head>
        <title></title>
    </head>
    <body>
        <input type="button" id="clickme" value="Click Me"/>
        <script language="javascript">
        
        // Lấy element có id=clickme lưu vào biến button
        var button = document.getElementById('clickme');
        
        // Khi click vào element chứa trong button thì thực hiện một function, 
        // bên trong function thông báo lên Hello World!
        button.addEventListener('click', function(){
            alert('Hello World!');
        });
        </script>
    </body>
</html>
