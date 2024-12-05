<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cầu Vàng - Đà Nẵng</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background: url('cbt1.jpg') no-repeat center center;
            background-size: cover;
            height: 60vh;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
        }
        header h1 {
            font-size: 3em;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }
        main {
            padding: 20px;
            max-width: 900px;
            margin: auto;
        }
        .content {
            margin: 20px 0;
        }
        .content h2 {
            color: #007bff;
            margin-bottom: 10px;
        }
        .content img {
            width: 100%;
            height: auto;
            border-radius: 8px;
            margin: 10px 0;
        }
        footer {
            background-color: #8B4513;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
        footer a {
            color: #ffdd57;
            text-decoration: none;
        }
        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<header>
    <h1>NHÓM 6 LỚP 12 LÝ</h1>
    <div class = "backgroundvideo">
        
    </div>
</header>

<main>
    <input type="text" id="ten" placeholder="Tên giáo viên">
    <p id="ketqua">Kính gửi</p>

    <script>
        // Lấy các phần tử
        const inputTen = document.getElementById('ten');
        const ketQua = document.getElementById('ketqua');

        // Thêm sự kiện lắng nghe khi giá trị trong input thay đổi
        inputTen.addEventListener('input', () => {
            ketQua.textContent = `Kính gửi, ${inputTen.value}!`;
        });
    </script>

    <div class="content">
        <h2>Lời chào đầu tiên</h2>
        <a>Cảm ơn thầy/cô đã xem trang web của chúng em</a>
        <br>
        <a>Chúng em chúc thầy/cô luôn tràng đầy sức khỏe, cung hỷ phát tài</a>
    </div>
</main>
<footer>
    <p><c href="">Xem các thành viên nhóm</c>.</p>
    <c href="">Đăng kí làm thành viên của nhóm 6</c>
    <br>
    <c href="">Bài tập vận dụng</c>
</footer>
</body>
</html>
