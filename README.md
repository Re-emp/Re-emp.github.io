<!DOCTYPE html>
<html lang="zh-CN">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Re-emp</title>
    <style>
        /* 全局样式 */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
        }

        /* 头部样式 */
        header {
            background-color: white;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            padding: 20px 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h1 {
            font-size: 36px;
            font-weight: 700;
            color: #007acc;
            display: flex;
            align-items: center;
        }

        /* 图片样式，适当增大高度 */
        header h1 img {
            height: 48px; /* 原来 36px，现在增大到 48px */
            margin-right: 10px;
        }

        /* 导航栏样式 */
        nav {
            background-color: #007acc;
        }

        nav ul {
            list-style-type: none;
            display: flex;
            justify-content: center;
            padding: 20px 0;
        }

        nav ul li {
            margin: 0 40px;
            /* 适当增大间距，让选项更舒展 */
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-size: 20px;
            /* 增大字体大小 */
            transition: color 0.3s ease;
        }

        nav ul li a:hover {
            color: #ffd700;
        }

       .banner {
            /* 使用相对路径 */
            background-image: url('/Re-emp/主页面/背景图.png');
            background-size: cover;
            background-position: center;
            height: 300px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
        }

       .banner h1 {
            font-size: 48px;
            margin-bottom: 10px;
        }

       .banner p {
            font-size: 18px;
        }

       .content {
            padding: 50px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

       .content-text {
            flex: 1;
        }

       .content-text h2 {
            color: #007acc;
            text-align: center;
            margin-bottom: 20px;
        }

       .content-text p {
            line-height: 1.6;
        }

       .content-img {
            flex: 1;
            text-align: center;
        }

       .content-img img {
            max-width: 100%;
            height: auto;
        }

       /* 新增样式类，将图片宽度设置为原来的 50% */
       .half-size {
            width: 50%;
        }

        footer {
            background-color: #007acc;
            color: white;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>

<body>
    <header>
        <h1>
            <!-- 使用相对路径 -->
            <img src="/Re-emp/主页面/logo.jpg" alt="Logo">
            Re-emp
        </h1>
    </header>
    <nav>
        <ul>
            <!-- 使用相对路径 -->
            <li><a href="主页面.html">首页</a></li>
            <li><a href="../简介/简介.html">简介</a></li>
            <li><a href="../资讯中心/资讯中心.html">资讯中心</a></li>
            <li><a href="../用户登录/用户登录.html">用户登录</a></li>
            <li><a href="../关于我们/关于我们.html">关于我们</a></li>
        </ul>
    </nav>
    <div class="banner">
        <h1>智赋未来，职财双赢</h1>
        <p>专业的财务规划技术与再就业服务提供商</p>
    </div>
    <div class="content">
        <div class="content-text">
            <h2>定制服务</h2>
            <p>  软件联合金融机构、职业培训机构和行业数据平台，为 35 - 40 岁高学历失业人群定制综合服务，包括进行应急资金规划、债务优化、资产配置等财务规划，开展技能提升课程定制、精准岗位匹配等再就业服务，提供行业趋势分析、简历面试辅导等求职辅助；同时面向中小企业提供定制服务，涵盖筛选高学历人才进行人才精准匹配，定制培训课程提供员工培训支持，以及通过岗位描述指导、建立人才库等方式进行招聘流程优化，以此助力失业人群再就业和中小企业优化人才配置</p>
        </div>
        <div class="content-img">
            <!-- 使用相对路径 -->
            <img src="/Re-emp/主页面/合作场景.jpg" alt="合作场景" class="half-size">
        </div>
    </div>
    <footer>
        <p>&copy;2025 - Re-emp 版权所有</p>
    </footer>
</body>

</html>
