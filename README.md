<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TERMUX NB</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    }

    body {
      background-color: #050508;
      background-image: 
        radial-gradient(rgba(0, 240, 255, 0.1) 1px, transparent 1px),
        radial-gradient(rgba(189, 16, 224, 0.1) 1px, transparent 1px);
      background-size: 30px 30px;
      background-position: 0 0, 15px 15px;
      color: #fff;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      padding: 20px;
    }

    .container {
      width: 100%;
      max-width: 380px;
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
    }

    /* Vòng tròn Avatar phát sáng Neon */
    .avatar-glow {
      width: 140px;
      height: 140px;
      border-radius: 50%;
      border: 3px solid #7b2cbf;
      box-shadow: 
        0 0 15px #00f0ff,
        0 0 30px #7b2cbf,
        inset 0 0 15px #00f0ff;
      margin-bottom: 25px;
      background: #000;
    }

    /* Tiêu đề TERMUX NB */
    h1 {
      font-size: 2.2rem;
      font-weight: 900;
      letter-spacing: 2px;
      background: linear-gradient(to bottom, #ffffff, #00f0ff);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      text-shadow: 0 0 15px rgba(0, 240, 255, 0.6);
      margin-bottom: 6px;
      line-height: 1.1;
    }

    /* Username & Bio */
    .tag {
      font-size: 0.95rem;
      color: #a0a0b0;
      margin-bottom: 12px;
      font-weight: 500;
    }

    .bio {
      font-size: 0.9rem;
      color: #e0e0e0;
      margin-bottom: 35px;
    }

    /* Nhóm nút bấm */
    .btn-group {
      display: flex;
      gap: 15px;
      width: 100%;
      margin-bottom: 15px;
    }

    .btn {
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 14px 20px;
      border-radius: 14px;
      text-decoration: none;
      font-weight: 800;
      font-size: 0.85rem;
      letter-spacing: 1px;
      transition: all 0.3s ease;
    }

    /* Nút Giới thiệu (Cyan/Purple Gradient) */
    .btn-intro {
      flex: 1;
      background: linear-gradient(135deg, #00c6ff, #bd10e0);
      color: #fff;
      box-shadow: 0 0 15px rgba(0, 198, 255, 0.4);
      border: none;
    }

    /* Nút Dự án (Tối + Viền Neon Violet) */
    .btn-project {
      flex: 1;
      background: rgba(18, 12, 38, 0.8);
      color: #bd10e0;
      border: 1px solid #bd10e0;
      box-shadow: 0 0 12px rgba(189, 16, 224, 0.3);
    }

    /* Nút TikTok (Viền Hồng Neon) */
    .btn-tiktok {
      width: 100%;
      background: rgba(25, 10, 25, 0.8);
      color: #ff007f;
      border: 1px solid #ff007f;
      box-shadow: 0 0 12px rgba(255, 0, 127, 0.3);
    }

    .btn:active {
      transform: scale(0.96);
    }
  </style>
</head>
<body>

  <div class="container">
    <!-- Vòng tròn Avatar -->
    <div class="avatar-glow"></div>

    <!-- Tên & Thông tin -->
    <h1>TERMUX NB</h1>
    <p class="tag">@phong278.chuyenxulyphot</p>
    <p class="bio">Chia sẻ kiến thức công nghệ & kỹ thuật</p>

    <!-- Các nút bấm -->
    <div class="btn-group">
      <a href="#" class="btn btn-intro">GIỚI THIỆU</a>
      <a href="#" class="btn btn-project">DỰ ÁN</a>
    </div>
    
    <a href="#" class="btn btn-tiktok">TIKTOK</a>
  </div>

</body>
</html>
