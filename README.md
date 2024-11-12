## Nội dung của file `<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang Web Của Tôi</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Chào Mừng Đến Với Trang Web Của Tôi!</h1>
            <p>Trang web này được tạo ra để giới thiệu với bạn một số tính năng cơ bản.</p>
        </div>
    </header>
    
    <main>
        <section>
            <h2>Giới thiệu</h2>
            <p>Đây là một trang web đơn giản được xây dựng với HTML, CSS, và JavaScript.</p>
        </section>
        
        <section>
            <h2>Thử Một Tính Năng JavaScript</h2>
            <button onclick="showMessage()">Nhấn để xem thông báo</button>
            <p id="message"></p>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>© 2024 Trang Web Của Tôi</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
[index.html.txt](https://github.com/user-attachments/files/17713858/index.html.txt)
`
file.content = '[* Cấu hình cơ bản cho trang */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
    line-height: 1.6;
}

/* Header */
header {
    background-color: #333;
    color: white;
    padding: 1rem;
    text-align: center;
}

header nav ul {
    list-style: none;
}

header nav ul li {
    display: inline;
    margin-right: 20px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

/* Main content */
main {
    padding: 20px;
    max-width: 900px;
    margin: 0 auto;
}

/* Section */
section {
    margin-bottom: 30px;
}

section h1, section h2 {
    color: #333;
}

/* Footer */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1rem;
    margin-top: 20px;
}ding styles.css…]()
