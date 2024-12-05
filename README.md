<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NHÓM 6 LỚP 12 LÝ</title>
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
            background-color: #007bff;
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
    <h1>NHÓM 6</h1>
    <div class = "backgroundvideo">
    </div>
 </header>
 <input type="text" id="ten" placeholder="Tên giáo viên">
    <p id="ketqua">Xin chào!</p>
    <script>
        const inputTen = document.getElementById('ten');
        const ketQua = document.getElementById('ketqua');
        inputTen.addEventListener('input', () => {
            ketQua.textContent = `Xin chào, ${inputTen.value}!`;
        });
    </script>
 <main>
    <div class="content">
        <h2>Kính chào</h2>
        <p>Đây là trang web của nhóm 6, Cảm ơn thầy và các bạn đã xem qua</p>
        <img src="images1829911_diem_10_do_ruc_hoc_ba_den_my_con_khong_duoc_nhu_the.jpg" alt="Hoa điểm 10 của nhóm em">
    </div>
    <div class="content">
        <h2>Mục Đích</h2>
        <p>Trang web được tạo ra với mục đích giúp các bạn có thể đăng kí làm thành viên của nhóm 6</p>
        <a href="https://tructamcute.github.io/DangKi/">Đăng kí thành viên</a>
    </div>
 </main>
 <footer>
    <a href="https://tructamcute.github.io/thanhviennhom6/">Những người đã tạo ra trang web này</a>
    <br>
    <a href="https://www.canva.com/design/DAGWUno2RiE/Ek5QNr1wtd8SDvla8EMnpg/edit">Thành tựu bài tập vận dụng của nhóm</a>
    <br>
    <c>Đặt câu hỏi cho admin qua sdt : 0776859230</c>
 </footer>
</body>
</html>
