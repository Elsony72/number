<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>الأرقام المتاحة للتحويل</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            direction: rtl;
            text-align: right;
            margin: 20px;
            background-color: #f9f9f9;
        }
        h1, h3 {
            color: #333;
        }
        .header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
            border-radius: 10px;
            margin-bottom: 30px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .numbers {
            margin-bottom: 30px;
        }
        .number-item {
            background: #fff;
            margin: 10px 0;
            padding: 10px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        button {
            margin-left: 10px;
            padding: 5px 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .call-btn {
            background-color: #4CAF50;
            color: white;
        }
        .unavailable-btn {
            background-color: #ccc;
            color: white;
            cursor: not-allowed;
        }
    </style>
</head>
<body>
    <!-- عنوان الصفحة -->
    <div class="header">
        <h1>تحويل فودافون كاش عطارة السني</h1>
        <p>اختار الرقم المتاح للتحويل بسهولة.</p>
    </div>

    <h3>الأرقام المتاحة للتحويل:</h3>

    <div class="numbers available">
        <div class="number-item">
            <span>01100909984</span>
            <button class="call-btn" onclick="callNumber('01100909984')">تحويل</button>
        </div>
        <div class="number-item">
            <span>01028932949</span>
            <button class="call-btn" onclick="callNumber('01027258929')">تحويل</button>
        </div>
        <div class="number-item">
            <span>01280100732</span>
            <button class="call-btn" onclick="callNumber('01280100732')">تحويل</button>
        </div>
    </div>

    <h3>الأرقام غير المتاحة:</h3>
    <div class="numbers unavailable">
        <div class="number-item">
            <span>01013520221</span>
            <button class="unavailable-btn" disabled>غير متاح</button>
        </div>
    </div>

    <script>
        // فتح لوحة الاتصال
        function callNumber(number) {
            window.location.href = `tel:${number}`;
        }
    </script>
</body>
</html>
