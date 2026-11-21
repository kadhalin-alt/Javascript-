"Javascript"


<html>
<head>
    <script language="JavaScript">
        function upper()
        {
            var x,y;
            x=document.frm.text1.value;
            y=x.toUpperCase();
            document.frm.text1.value=y;
        }

        function lower()
        {
            var x,y;
            x=document.frm.text1.value;
            y=x.toLowerCase();
            document.frm.text1.value=y;
        }
    </script>
</head>

<body>
    <form name="frm">
        <center>
            Enter a text <br>
            <input type="text" name="text1"><br>

            <input type="button" value="ToUpperCase" onclick="upper()">
            <input type="button" value="ToLowerCase" onclick="lower()">
        </center>
    </form>
</body>
</html>