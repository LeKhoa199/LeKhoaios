<!DOCTYPE html>
<html lang="vi">
<head>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&family=Roboto:wght@500&display=swap" rel="stylesheet">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LeKhoa</title>
    <link rel="stylesheet" href="hello.css">
</style>
</head>
<body>
    <div id="login" class="container">
        <h2>Đăng nhập</h2>
        <input type="password" id="passwordInput" class="password-input" placeholder="Nhập key vào đây">
        <button id="loginButton">Đăng nhập</button>
        <button id="contactButton">Get Key</button>
    </div>
    
    <div id="lekhoa" class="hidden">
        <h3>Cheat Menu</h3>
        <ul>
            <li>
                <span class="function-name">Tìm Speed</span>
                <label class="switch"><input type="checkbox" id="searchSpeedButton"><span class="slider"></span></label>
            </li>
            <li>
                <span class="function-name">Speed Run</span>
                <label class="switch"><input type="checkbox" id="activateSpeedButton"><span class="slider"></span></label>
            </li>
            <li>
                <span class="function-name">Xóa Speed</span>
                <label class="switch"><input type="checkbox" id="deactivateSpeedButton"><span class="slider"></span></label>
            </li>
            <li>
                <span class="function-name">Music Play</span>
                <label class="switch"><input type="checkbox" id="playMusicButton"><span class="slider"></span></label>
            </li>
            <li>
                <button id="toggleSubMenu" class="subMenuButton">Mở Profile</button>
            </li>
        </ul>
        <span class="function-name">Chọn Nhạc</span>
        <select id="songSelect">
            <option value="">Chọn một bài hát</option>
            <option value="0">Always With Me</option>
            <option value="1">Dối Lòng</option>
            <option value="2">Free Dom</option>
            <option value="3">Những Lời Dối Lòng</option>
            <option value="4">Six Usa V2</option> 
            <option value="5">Em Nào Có Tội</option>
            <option value="6">Sơn Tùng Chill</option>
            <option value="7">Nhạc Sex</option>
            <option value="8">Hành Lang Cũ</option>
            <option value="9">Nhạc Đi Tắm</option>
            <option value="10">Nhạc Tết 2</option>
            <option value="11">Nhạc Cách Mạng</option>
            <option value="12">Bạc Phận</option>
            <option value="13">Nhạc Tết</option>
            <option value="14">Future</option>
        </select>
    </div>

    <!-- Menu Phụ -->
    <div id="subMenu">
        <div id="profile">
            <img src="https://files.catbox.moe/prqe3y.jpeg" alt="Profile Picture">
            <div>
                <h4>Dang Le Khoa</h4>
            </div>
        </div>
        <button id="updateProfileButton">Tắt Profile</button>
    </div>


<audio id="backgroundMusic" loop></audio>
<div id="particles-js"></div>

<script src="https://cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js"></script>
    <script src="hello.js"></script>
</body>
</html>

