<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>تطور مبيعات الشركة</title>
    <style>
        body { font-family: Arial, sans-serif; direction: rtl; text-align: center; }
        table { width: 100%; border-collapse: collapse; margin: 20px 0; }
        th, td { padding: 10px; border: 1px solid #ddd; }
        th { background-color: #f4b41a; color: white; }
        h2 { color: #333; }
    </style>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
</head>
<body>

    <h1>تطور مبيعات الشركة</h1>

    <!-- قسم Comptoir -->
    <h2>تطور المبيعات - قسم Comptoir</h2>
    <table>
        <tr>
            <th>الشهر</th>
            <th>المبيعات</th>
        </tr>
        <tr>
            <td>يناير</td>
            <td>8000</td>
        </tr>
        <tr>
            <td>فبراير</td>
            <td>8500</td>
        </tr>
        <!-- أكمل باقي الأشهر حسب بياناتك -->
    </table>
    <canvas id="comptoirChart" width="400" height="200"></canvas>

    <!-- قسم Carrosserie -->
    <h2>تطور المبيعات - قسم Carrosserie</h2>
    <table>
        <tr>
            <th>الشهر</th>
            <th>المبيعات</th>
        </tr>
        <tr>
            <td>يناير</td>
            <td>5000</td>
        </tr>
        <tr>
            <td>فبراير</td>
            <td>5500</td>
        </tr>
        <!-- أكمل باقي الأشهر حسب بياناتك -->
    </table>
    <canvas id="carrosserieChart" width="400" height="200"></canvas>

    <!-- قسم Mecanique -->
    <h2>تطور المبيعات - قسم Mecanique</h2>
    <table>
        <tr>
            <th>الشهر</th>
            <th>المبيعات</th>
        </tr>
        <tr>
            <td>يناير</td>
            <td>7000</td>
        </tr>
        <tr>
            <td>فبراير</td>
            <td>7500</td>
        </tr>
        <!-- أكمل باقي الأشهر حسب بياناتك -->
    </table>
    <canvas id="mecaniqueChart" width="400" height="200"></canvas>

    <!-- الرسوم البيانية -->
    <script>
        const comptoirData = [8000, 8500, 9000, 9500, 10000, 10500]; // استبدل ببيانات قسم Comptoir
        const carrosserieData = [5000, 5500, 6000, 6500, 7000, 7500]; // استبدل ببيانات قسم Carrosserie
        const mecaniqueData = [7000, 7500, 8000, 8500, 9000, 9500]; // استبدل ببيانات قسم Mecanique
        const labels = ['يناير', 'فبراير', 'مارس', 'أبريل', 'مايو', 'يونيو']; // استبدل بالشهور المتاحة

        // Comptoir Chart
        new Chart(document.getElementById('comptoirChart').getContext('2d'), {
            type: 'line',
            data: { labels: labels, datasets: [{ label: 'المبيعات', data: comptoirData, borderColor: 'rgba(75, 192, 192, 1)', borderWidth: 2, fill: false }] }
        });

        // Carrosserie Chart
        new Chart(document.getElementById('carrosserieChart').getContext('2d'), {
            type: 'line',
            data: { labels: labels, datasets: [{ label: 'المبيعات', data: carrosserieData, borderColor: 'rgba(255, 99, 132, 1)', borderWidth: 2, fill: false }] }
        });

        // Mecanique Chart
        new Chart(document.getElementById('mecaniqueChart').getContext('2d'), {
            type: 'line',
            data: { labels: labels, datasets: [{ label: 'المبيعات', data: mecaniqueData, borderColor: 'rgba(54, 162, 235, 1)', borderWidth: 2, fill: false }] }
        });
    </script>

</body>
</html>
