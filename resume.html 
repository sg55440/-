<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>个人专属简历</title>
    <style>
        * { font-family: 'Microsoft YaHei', sans-serif; }
        body { background: #f5f7fa; padding: 20px; }
        .resume-container {
            max-width: 800px;
            margin: 0 auto;
            background: white;
            box-shadow: 0 0 20px rgba(0,0,0,0.1);
            border-radius: 10px;
            overflow: hidden;
        }
        .header {
            background: linear-gradient(135deg, #6a11cb 0%, #2575fc 100%);
            color: white;
            padding: 30px;
            text-align: center;
        }
        .photo {
            width: 120px;
            height: 160px;
            border: 3px solid white;
            border-radius: 5px;
            margin: 0 auto 15px;
            background: #ddd;
        }
        h1 { 
            margin: 10px 0; 
            letter-spacing: 2px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            padding: 12px 15px;
            border-bottom: 1px solid #e0e6ef;
            text-align: left;
        }
        th {
            background-color: #f8fafc;
            font-weight: 600;
            color: #3c4858;
            width: 25%;
        }
        .section-title {
            background: #f1f5f9;
            padding: 10px 20px;
            font-size: 1.2em;
            color: #2c3e50;
            border-left: 4px solid #2575fc;
        }
        .signature {
            text-align: right;
            padding: 30px;
            color: #7e8c9a;
        }
        @media print {
            body { background: white; }
            .resume-container { box-shadow: none; }
        }
    </style>
</head>
<body>
    <div class="resume-container">
        <div class="header">
            <div class="photo"></div>
            <h1>你的姓名</h1>
            <p>职位/职业方向 | 所在地</p>
        </div>
        
        <div class="section-title">基本信息</div>
        <table>
            <tr><th>姓名</th><td>请在此填写</td><th>电话</th><td>请在此填写</td></tr>
            <tr><th>邮箱</th><td colspan="3">请在此填写</td></tr>
            <tr><th>地址</th><td colspan="3">请在此填写</td></tr>
        </table>
        
        <div class="section-title">教育背景</div>
        <table>
            <tr><th>时间</th><th>学校</th><th>专业</th><th>学历</th></tr>
            <tr><td>20XX-20XX</td><td>请在此填写</td><td>请在此填写</td><td>请在此填写</td></tr>
            <!-- 可复制此行添加更多 -->
        </table>
        
        <div class="section-title">工作经历</div>
        <table>
            <tr><th>时间</th><th>公司</th><th>职位</th><th>工作内容</th></tr>
            <tr><td>20XX-至今</td><td>请在此填写</td><td>请在此填写</td><td>请在此填写</td></tr>
            <!-- 可复制此行添加更多 -->
        </table>
        
        <div class="section-title">专业技能</div>
        <table>
            <tr><th>技术领域</th><td colspan="3">请在此填写（建议用逗号分隔）</td></tr>
            <tr><th>语言能力</th><td colspan="3">请在此填写</td></tr>
        </table>
        
        <div class="signature">
            最后更新: <span id="current-date"></span> | 专属简历
        </div>
    </div>

    <script>
        // 自动更新日期
        document.getElementById('current-date').textContent = new Date().toLocaleDateString('zh-CN', {
            year: 'numeric',
            month: 'long',
            day: 'numeric'
        });
        
        // 示例：未来可添加登录功能
        /* 
        const user = {
            name: "你的名字",
            contact: "138xxxxxxx"
        };
        */
    </script>
</body>
</html>
