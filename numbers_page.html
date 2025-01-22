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
    <div id="available-numbers" class="numbers available"></div>

    <h3>الأرقام غير المتاحة:</h3>
    <div id="unavailable-numbers" class="numbers unavailable"></div>

    <script>
        // تحميل الأرقام من ملف JSON
        fetch('numbers.json')
            .then(response => response.json())
            .then(data => {
                const availableContainer = document.getElementById('available-numbers');
                const unavailableContainer = document.getElementById('unavailable-numbers');

                // عرض الأرقام المتاحة
                data.available.forEach(number => {
                    const numberItem = document.createElement('div');
                    numberItem.classList.add('number-item');
                    numberItem.innerHTML = `
                        <span>${number}</span>
                        <button class="call-btn" onclick="callNumber('${number}')">تحويل</button>
                    `;
                    availableContainer.appendChild(numberItem);
                });

                // عرض الأرقام غير المتاحة
                data.unavailable.forEach(number => {
                    const numberItem = document.createElement('div');
                    numberItem.classList.add('number-item');
                    numberItem.innerHTML = `
                        <span>${number}</span>
                        <button class="unavailable-btn" disabled>غير متاح</button>
                    `;
                    unavailableContainer.appendChild(numberItem);
                });
            });

        // فتح لوحة الاتصال
        function callNumber(number) {
            window.location.href = `tel:${number}`;
        }
    </script>
</body>
</html>
