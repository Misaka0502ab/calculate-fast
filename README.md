<!DOCTYPE html>
<html lang="en">
    <style>
        /* 模态框样式 */
        .modal {
            display: none; /* 默认隐藏 */
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.5); /* 半透明背景 */
            justify-content: center;
            align-items: center;
            z-index: 1000; /* 确保在最上层 */
        }
        
        .modal-content {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            max-width: 300px;
            text-align: center;
        }
        
        .modal-button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 4px;
            cursor: pointer;
            margin-top: 15px;
        }
    </style>
<head>
    <!-- 主要Favicon（PNG格式，推荐现代浏览器） -->
    <link rel="icon" type="image/png" sizes="32x32" href="favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="favicon-16x16.png">
    
    <!-- 兼容旧版浏览器的ICO格式 -->
    <link rel="icon" href="favicon.ico" type="image/x-icon">
    
    <!-- iOS设备主屏幕图标 -->
    <link rel="apple-touch-icon" sizes="180x180" href="apple-touch-icon.png">
    
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>绿色网站，绿色发财 </title>
</head>
    <!-- 其他标签保持不变 -->
    
    <!-- 路径指向images文件夹 -->
    <link rel="icon" href="images/favicon.ico" type="image/x-icon">
    <link rel="shortcut icon" href="images/favicon.ico" type="image/x-icon">
</head>
</head>
<p>
    <h1 style="text-align: center;color: rgb(255, 217, 0);">来发财</h1>
    <div>
<select name="" id="">
    <option value=""></option>
    <option value="">发大财</option>
    <option value="">发中财</option>
    <option value="">发小财</option>
</select>
</p>
 <style>
        /* 让 body 内的所有行内/行内块元素水平居中 */
        body {
            text-align: center; 
        }
        /* 如果输入框是块级元素，需单独设置 margin 居中 */
        input[type="text"], 
        input[type="password"] {
            display: block;       /* 转为块级元素 */
            margin: 0 auto;       /* 水平居中 */
            margin-bottom: 10px; /* 增加间距 */
        }
    </style>
<body> 
    <script src="java.js">
   
    </script>

    <h2 style="text-align: center;">账号</h2>
    <input type="text">
    <p>

    </p>
    <h3 style="text-align: center;">密码</h3>
    <input type="password" id="passwordInput">
    
   <div id="myModal" class="modal">
        <div class="modal-content">
            <p>你的账户余额为0，哈哈哈！</p>
            <button class="modal-button" onclick="closeModal()">确定</button>
        </div>
    </div>

    <script>
        const passwordInput = document.getElementById('passwordInput');
        const modal = document.getElementById('myModal');

        // 监听回车键
        passwordInput.addEventListener('keydown', function(event) {
            if (event.key === 'Enter') {
                openModal();
            }
        });

        // 打开模态框
        function openModal() {
            modal.style.display = 'flex';
        }

        // 关闭模态框
        function closeModal() {
            modal.style.display = 'none';
        }

        // 点击模态框外部也可以关闭
        modal.addEventListener('click', function(event) {
            if (event.target === modal) {
                closeModal();
            }
        });
    </script>

    <p><i><b>真的灵
        <p>
            
        </p>
    </b></i>旺旺发财</p>
<a href="https://www.bilibili.com/" target="_blank"> <img src="https://tse3-mm.cn.bing.net/th/id/OIP-C.V6Lstu8wWMfZSx0hryzLVwHaHa?r=0&rs=1&pid=ImgDetMain&cb=idpwebpc2" alt="发财了"></a>
</div>
</body>
</html>
