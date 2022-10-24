# memo
純粋にメモ記録する

Katalon Recorder 录制神器
Listary 快速查找软件
clibor 剪贴板

alt+enter 打开属性窗口


###click
```batch
<html>
    <head>
        <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
        <title>I need you still work!</title>
    </head>
    <body bgcolor="#215E21">
        <script type="text/javascript">
            function PressKey(){
                var objWs = new ActiveXObject("Wscript.Shell");
                objWs.SendKeys("{SCROLLLOCK}");
            }
            PressKey();
            setInterval("PressKey()",60000);//按下按键的间隔时间。
        </script>
    </body>
</html>
```
