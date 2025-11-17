# CAFFEE-LIBADU-
Phần mền quản lý quán cà phê LIBADU
<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<title>LIBADU Cafe - Quản Lý Nâng Cao</title>
<link rel="stylesheet" href="style.css">
<!-- Chart.js -->
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<!-- jsPDF -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
<!-- SheetJS -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/xlsx/0.18.5/xlsx.full.min.js"></script>
</head>
<body>
  <div class="sidebar">
    <h2>LIBADU Cafe</h2>
    <nav>
      <button onclick="showPOS()">POS</button>
      <button onclick="showMenu()">Menu</button>
      <button onclick="showInventory()">Kho</button>
      <button onclick="showStaff()">Nhân Viên</button>
      <button onclick="showCustomer()">Khách Hàng</button>
      <button onclick="showReport()">Báo Cáo</button>
    </nav>
  </div>
  <div class="main" id="main"></div>

<script src="script.js"></script>
</body>
</html>
