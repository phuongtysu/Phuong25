<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Combo Herbalife Giảm 50%</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #fff; color: #333; }
    .container { max-width: 600px; margin: auto; padding: 20px; }
    h1 { color: #E53935; text-align: center; }
    .hook { background: #f9f9f9; padding: 15px; border-radius: 6px; margin: 15px 0; font-size: 1.1em; }
    .product { border: 1px solid #ddd; padding: 15px; margin: 20px 0; border-radius: 8px; }
    .product img { width: 100%; border-radius: 8px; margin-top: 10px; }
    .cta { text-align: center; margin: 25px 0; }
    .btn { background: #E53935; color: #fff; padding: 15px 20px; text-decoration: none; border-radius: 5px; font-size: 1.2em; display: inline-block; }
    table { width: 100%; border-collapse: collapse; margin-top: 15px; }
    th, td { border: 1px solid #ddd; padding: 10px; text-align: center; }
    .countdown { font-size: 1.5em; color: #D32F2F; text-align: center; font-weight: bold; margin: 15px 0; }
  </style>
</head>
<body>
  <div class="container">
    <h1>🔥 ƯU ĐÃI GIẢM CÂN - GIẢM GIÁ 50% TRONG 5 NGÀY!</h1>

    <div class="countdown">
      ⏰ Kết thúc sau: <span id="countdown"></span>
    </div>

    <div class="hook">
      ❌ Ăn ít mà vẫn tăng cân?<br>
      ❌ Mệt mỏi, uể oải dù đã ngủ đủ?<br>
      ❌ Tập mãi không thấy giảm?<br>
      ❌ Mỡ bụng dưới không hề thay đổi?<br>
      ❌ Không muốn kiêng khắt khe mà vẫn muốn giảm cân?
    </div>

    <div class="product">
      <h2>Combo 1: F1 (Shake Dinh Dưỡng)</h2>
      <p><strong>Giá gốc:</strong> 1.200.000₫ → <strong style="color:green;">600.000₫</strong> (‑50%)</p>
      <p>Giúp no lâu, giảm thèm ăn, thay thế bữa ăn đủ chất.</p>
      <img src="https://herbalife.com.vn/wp-content/uploads/2020/06/F1-Vani.png" alt="Sản phẩm F1">
    </div>

    <div class="product">
      <h2>Combo 2: F1 + Đạm + Trà Nhiệt Đới</h2>
      <p><strong>Giá gốc:</strong> ~3.000.000₫ → <strong style="color:green;">1.500.000₫</strong></p>
      <p>Giảm mỡ, giữ cơ, tỉnh táo buổi sáng, kiểm soát cân nặng rõ rệt.</p>
      <img src="https://herbalife.com.vn/wp-content/uploads/2020/06/F1-Protein-Tra.png" alt="Combo 2">
    </div>

    <div class="product">
      <h2>Combo 3: F1 + Đạm + Trà + Lô Hội</h2>
      <p><strong>Giá gốc:</strong> ~4.200.000₫ → <strong style="color:green;">2.000.000₫</strong></p>
      <p>Full bộ giảm cân: detox - đốt mỡ - giữ cơ - kiểm soát cảm giác thèm ăn.</p>
      <img src="https://herbalife.com.vn/wp-content/uploads/2020/06/combo4-sp.png" alt="Combo 3">
    </div>

    <table>
      <tr><th>Combo</th><th>Sản phẩm</th><th>Giá gốc</th><th>Giá giảm</th></tr>
      <tr><td>1</td><td>F1</td><td>1.200.000₫</td><td>600.000₫</td></tr>
      <tr><td>2</td><td>F1 + Đạm + Trà</td><td>3.000.000₫</td><td>1.500.000₫</td></tr>
      <tr><td>3</td><td>F1 + Đạm + Trà + Lô Hội</td><td>4.200.000₫</td><td>2.000.000₫</td></tr>
    </table>

    <div class="cta">
      <a class="btn" href="https://www.facebook.com/share/15jRMC1g1j/?mibextid=wwXIfr>💬 TƯ VẤN MIỄN PHÍ – ĐẶT MUA NGAY</a>
    </div>

    <p style="text-align: center; color: #999; font-size: 0.9em;">
      Tư vấn 1-1 miễn phí. Không mua cũng được hỏi. Hỗ trợ Zalo, Messenger 24/7.
    </p>
  </div>

  <script>
    // Countdown 5 ngày
    const endDate = new Date();
    endDate.setDate(endDate.getDate() + 5);
    const countdownEl = document.getElementById("countdown");
    function updateCountdown() {
      const now = new Date();
      const diff = endDate - now;
      if (diff <= 0) {
        countdownEl.innerHTML = "ĐÃ KẾT THÚC!";
        return;
      }
      const days = Math.floor(diff / (1000 * 60 * 60 * 24));
      const hours = Math.floor((diff / (1000 * 60 * 60)) % 24);
      const minutes = Math.floor((diff / (1000 * 60)) % 60);
      const seconds = Math.floor((diff / 1000) % 60);
      countdownEl.innerHTML = `${days} ngày ${hours}h ${minutes}m ${seconds}s`;
    }
    setInterval(updateCountdown, 1000);
    updateCountdown();
  </script>
</body>
</html>
