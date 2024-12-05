<html>
    <head>
            <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
            display: flex;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
        }
        .form-container {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            width: 100%;
            max-width: 500px;
        }
        .form-container h2 {
            text-align: center;
            margin-bottom: 20px;
            color: #333;
        }
        .form-container label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
            color: #555;
        }
        .form-container input,
        .form-container select,
        .form-container button {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .form-container button {
            background-color: #007BFF;
            color: white;
            border: none;
            cursor: pointer;
            font-size: 16px;
        }
        .form-container button:hover {
            background-color: #0056b3;
        }
    </style>
        <script>
        function hienThiTen() {
          // Lấy giá trị từ ô nhập liệu có ID là "ten"
          let tenGiaoVien = document.getElementById("ten").value;
        
          // Thay đổi nội dung của đoạn văn có ID là "ketqua"
          document.getElementById("ketqua").textContent = "Xin chào, " + tenGiaoVien + "!";
        }
        </script>
       <b style="font-size:50px; font-family:monospace"> Day la mot kiet tac nghe thuat  </b>
       <link rel="stylesheet" href="style.css">
       <link rel="stylesheet" href="style1.css">
    </head>
    <head>
    <body>
        <div class="form-container">
        <h2>Don xin tham gia nhom ^</h2>
        <form action="/submit-tour" method="POST">
            <label for="fullname">Họ và Tên</label>
            <input type="text" id="fullname" name="fullname" placeholder="Nhập họ và tên của bạn" required>

            <label for="email">Email</label>
            <input type="email" id="email" name="email" placeholder="Nhập email" required>

            <label for="phone">Số Điện Thoại</label>
            <input type="tel" id="phone" name="phone" placeholder="Nhập số điện thoại" required>
            <label for="date">Ngày Tham Quan</label>
            <input type="date" id="date" name="date" required>

            <label for="tickets">Số Lượng Vé</label>
            <input type="number" id="tickets" name="tickets" placeholder="Nhập số lượng vé" min="1" required>

            <button class="btn" onclick="window.location.href='cauvang.html'">
                Đặt vé
            </button>
        </form>
    </div>
       <p style="color: blue;">Chào mừng đến với Trang Web của nhom 6</p>
       <b> Kính chào thầy Đức thân mến, chúng em rất quý mến thầy, hôm nay chúng em tạo web này nhằm tri ân những lời giảng của thầy đã giúp chúng em rất nhiều</b>
      <br>
      <b> Chúc thầy phát tài phát lộc 8386</b>
    <p>Cac thanh vien nhom<p>
                     <a>Thien Kim, Anh Khoa, Huynh Phat, Yen Vy, Trung Nguyen</a>
      <p> ước mơ của chúng em: <p>
     <img src="images.png">
    <video width="320" height="240" controls>
    <source src="lop.mp4" type="video/mp4">
    <source src="lop.ogg" type="video/ogg">
    Your browser does not support the video tag
    </video>
      <table style="border-collapse: collapse;">
   <tr>
       <th rowspan="3" style="border: 2px solid blue;"> môn học       </th>
   </tr>
   <tr>
   
     <td style="border: 2px solid red;">Toán </td>
   
     <td style="border: 2px solid yellow;">Vật lí </td>
   
     <td style="border: 2px solid green;">Hóa học </td>
    
   </tr>
   <br>
   <tr>
           <th rowspan="3" style="border: 2px solid red;">9.8</th>
   </tr>
   <tr>
           <td style="border: 2px solid blue;">Điểm thi</td>
   
    <td style="border: 2px solid yellow;">10</td>
    <td style="border: 2px solid green;"> 9.8</td>
   </tr>
   
   </table>
      <a href="https://www.vietjack.com/">Hoc nua hoc mai </a>
    <br>
     <a href="https://www.canva.com/design/DAGWUno2RiE/Ek5QNr1wtd8SDvla8EMnpg/edit/">luyện tập vận dụng </a>
    <br>
     <a href="https://tructamcute.github.io/ProfileThienKim/"> Kim </a>
     <a href="https://tructamcute.github.io/ProfileAnhKhoa/"> Khoa </a>
     <a href="https://tructamcute.github.io/ProfileYenVy/"> Vy </a>
     <a href="https://tructamcute.github.io/ProfileHuynhPhat/"> Phát </a>
     <a href="https://tructamcute.github.io/ProfileTrungNguyen/"> Nguyên </a>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">


    </body>
    <html>
   
   
