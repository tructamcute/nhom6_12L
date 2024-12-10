<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NHÓM 6 LỚP 12 LÝ</title>
    <style>
svg {
  overflow: visible;
}
svg path#line {
  fill: none;
  stroke: #e00000;
  stroke-width: 2;
  stroke-linecap: butt;
  stroke-linejoin: round;
  stroke-miterlimit: 4;
  stroke-dasharray:none;
  stroke-opacity: 1;
  stroke-dasharray: 1;
  stroke-dashoffset: 1;
  animation: dash 4s linear infinite;
}
svg path#heart {
  transform-origin: 50% 50%;
  animation: blink 4s linear infinite;
}
@keyframes dash {
  0% {
    stroke-dashoffset: 1;
  }
  80% {
    stroke-dashoffset: 0;
  }
  100% {
    stroke-dashoffset: 0;
  }
}
@keyframes blink {
  0% {
    opacity: 0;
    transform: scale(0);
  }
  60% {
    opacity: 0;
    transform: scale(0);
  }
  70% {
    opacity: 1;
    transform: scale(1.2);
  }
  75% {
    opacity: 1;
    transform: scale(1.0);
  }
  80% {
    opacity: 1;
    transform: scale(1.2);
  }
  85% {
    opacity: 1;
    transform: scale(1.0);
  }
  100% {
    opacity: 0;
    transform: scale(1.0);
  }
}
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background: url('z6116961084847_09d160a6908b97be4b820364d23084c6.jpg') no-repeat center center;
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
        table, th, td {
            border: 1px solid black;
            border-collapse: collapse;
            padding: 15px;
        }
    </style>
</head>
<body>
 <header>
    <h1>NHÓM 6</h1>
    <div class = "backgroundvideo">
    </div>
 </header> 
 <br>
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
        <br>
        <img src="images1829911_diem_10_do_ruc_hoc_ba_den_my_con_khong_duoc_nhu_the.jpg" alt="Hoa điểm 10 của nhóm em">
    </div>
    <div class="content">
        <h2>Mục Đích</h2>
        <p>Trang web được tạo ra với mục đích giúp các bạn có thể đăng kí làm thành viên của nhóm 6</p>
        <br>
        <p>Đây là các đối tác quan trọng của nhóm trong tương lai</p>
        <br>
        <video controls>
          <source src="6053805756567.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
        <br>
    </div>
     <div class="content">
        <h2>Giới thiệu </h2>
        <p>Nhóm 6 là một nhóm nghệ sĩ trẻ, luôn tràn đầy năng lượng và sáng tạo. Chúng tôi yêu nghệ thuật và muốn chia sẻ niềm đam mê đó với mọi người. Qua các tác phẩm của mình, chúng tôi mong muốn truyền tải những thông điệp tích cực, góp phần làm đẹp cuộc sống.</p>
         <br>
         <p>Đây là thành tựu của 1 số thành viên </p>
         <br>
         <table>
    <tr>
        <th>         </th>
        <th>Toán</th>
        <th>Tin</th>
        <th>Lý</th>
    </tr>
    <tr>
        <td>Huỳnh Thiên Kim</td>
        <td>10</td>
        <td>10</td>
        <td>10</td>
    </tr>
    <tr>
        <td>Nguyễn Thị Yến Vy</td>
         <td>10</td>
        <td>10</td>
        <td>10</td>
    </tr>
    <tr>
        <td>Phan Anh Khoa</td>
        <td>10</td>
        <td>10</td>
        <td>10</td>
    </tr>
    <tr>
        <td>Huỳnh Phát</td>
         <td>10</td>
        <td>10</td>
        <td>10</td>
    </tr>
    <tr>
        <td>Trần Trung Nguyên</td>
         <td>10</td>
        <td>10</td>
        <td>10</td>
    </tr>
         </table>
         <br>
         <p style="color:red">Nếu thấy hay, hãy đăng kí tham gia nhóm bằng cách nhấn vào "Đăng kí thành viên" bên dưới nhé!!!!!</p>
        <a href="https://tructamcute.github.io/DangKi/">Đăng kí thành viên</a>
    </div>
 </main>
 <footer>
    <a href="https://tructamcute.github.io/thanhviennhom6/">Những người đã tạo ra trang web này</a>
    <br>
    <a href="https://www.canva.com/design/DAGWUno2RiE/Ek5QNr1wtd8SDvla8EMnpg/edit">Thành tựu bài tập vận dụng của nhóm</a>
    <br>
    <c>CSKH: 0776859230</c>
     <svg xmlns="http://www.w3.org/2000/svg" id="svg5" version="1.1" viewBox="0 0 502.98 108.61">
  <path id="heart" d="M213.35 29.43c19.41-15.19 33.68 10.86 37.73 18.82-.28-13.61 11.64-40.98 25.94-34.01 32.3 15.74-15.88 83.8-26.4 81.76-13.24-9-51.35-53.3-37.27-66.57Z" style="fill:#ff9999;stroke:#ff9999;stroke-width:device-width;stroke-linecap:butt;stroke-linejoin:miter;stroke-miterlimit:4;stroke-dasharray:none;stroke-opacity:0.8"/>
  <path  pathLength="1" id="line" d="M5.32 78.13c.96-.01 5-8.5 5.54-8.54.58-.05 6.1 8.51 7.1 8.51 3.66 0 9.29.06 10.71.05 2.53-.01 4.82-72.88 4.82-72.88l4.76 97.28 3.97-24.45 20.45-.22C64 77.86 77.1 63.66 78.36 63.8c1.31.15 6.68 14.08 7.94 14.07 2.3-.03 33.32.04 35.76.02.96 0 5-8.5 5.53-8.53.59-.05 6.1 8.51 7.1 8.5 3.66 0 9.3.07 10.72.06 2.53-.02 4.81-72.89 4.81-72.89l4.77 97.28 3.97-24.44s83.34-3.33 74.69 7.67c-8.65 11-45.3-42.94-31.65-53.58 25.6-19.96 49.96 36.94 40.26 36.5-12.2-.53 1.8-62.32 23.41-51.7 32.24 15.86-17.56 84.92-26.4 81.77-5.73-2.05-.68-21.68 31.4-26.58 26.65-6.42 29.5 2.35 52.62 7.11 2.53-.02 4.82-72.89 4.82-72.89l4.76 97.28 3.97-24.44 20.45-.22c1.31-.02 14.41-14.22 15.68-14.07 1.32.15 6.7 14.08 7.95 14.07 2.29-.03 33.32.04 35.76.02.95 0 5-8.5 5.53-8.54.58-.04 6.1 8.52 7.1 8.52 3.66 0 9.3.06 10.72.05 2.53-.02 4.81-72.89 4.81-72.89l4.77 97.28 3.97-24.44 20.45-.23c1.31-.01 14.4-14.22 15.68-14.07 1.32.16 6.69 14.09 7.94 14.07" />
</svg>
 </footer>
</body>
</html>
