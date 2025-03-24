<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amar's Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f7fc;
            color: #333;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        header {
            background-color: #4CAF50;
            width: 100%;
            padding: 15px;
            color: white;
            text-align: center;
            font-size: 2em;
        }
        .content {
            margin-top: 20px;
            width: 90%;
            max-width: 1200px;
        }
        .content img {
            border-radius: 10px;
            box-shadow: 0px 4px 15px rgba(0, 0, 0, 0.1);
        }
        .content .tech-stack img {
            width: 50px;
            margin: 5px;
            transition: transform 0.3s ease;
        }
        .content .tech-stack img:hover {
            transform: scale(1.1);
        }
        footer {
            background-color: #333;
            color: white;
            width: 100%;
            padding: 10px;
            text-align: center;
        }
        .about-me {
            background-color: #ffffff;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0px 4px 15px rgba(0, 0, 0, 0.1);
            margin-top: 50px;
            width: 80%;
            max-width: 1000px;
        }
        .about-me h2 {
            text-align: center;
            color: #4CAF50;
        }
        .about-me p {
            font-size: 1.1em;
            line-height: 1.6;
        }
        .about-me a {
            text-decoration: none;
            color: #4CAF50;
            font-weight: bold;
        }
        .about-me div {
            display: flex;
            justify-content: space-around;
            margin-top: 30px;
        }
        .about-me img {
            border-radius: 50%;
            border: 5px solid #4CAF50;
            width: 120px;
            height: 120px;
            padding: 5px;
            box-shadow: 0px 4px 10px rgba(0,0,0,0.2);
            transition: transform 0.3s ease;
        }
        .about-me img:hover {
            transform: scale(1.1);
        }
    </style>
</head>
<body>
    <header>
        Amar's Portfolio
    </header>

    <div class="content">
        <div class="tech-stack">
            <h3>💻 Tech Stack</h3>
            <div>
                <img src="https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++">
                <img src="https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white" alt="C#">
                <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
                <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" alt="JavaScript">
                <img src="https://img.shields.io/badge/python-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white" alt="Python">
                <img src="https://img.shields.io/badge/mysql-%2300758F.svg?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
                <img src="https://img.shields.io/badge/git-%23F05032.svg?style=for-the-badge&logo=git&logoColor=white" alt="Git">
            </div>
        </div>

        <div class="about-me">
            <h2>👨‍💻 About Me</h2>
            <p>I am currently studying **Software Engineering** at **[FIT](https://www.fit.ba/)** (Faculty of Information Technologies).  
            I completed the **Computer-Aided Design** (CAD) specialization at **[Secondary School of Mechanical Engineering and Traffic](https://www.ms-skola.ba/)** in **Mostar**.  
            During my time there, I worked with tools like **AutoCAD**, **SolidWorks**, **Inventor**, and other essential engineering and design software.  
            Additionally, I had solid exposure to **programming** during high school, learning languages such as **C++**, **Python**, and more.  
            I also graduated from **[OŠ Suljo Čilić Jablanica](https://www.suljocilic.com.ba/)**, where I gained a strong foundation in academics and values.</p>
            <div>
                <a href="https://www.fit.ba/" target="_blank">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSwMBbQQ90pZL6B-Vy-UlVnHB78ZqK1UFLL2F835CQlAFNhX0ufP0VyjWiVQUuvwlGcq8s&usqp=CAU" alt="FIT Logo">
                </a>
                <a href="https://www.ms-skola.ba/" target="_blank">
                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRf549ytS42nRgw8PmhWJiplMafBA05lW4dLA&s" alt="Srednja Mašinska Saobraćajna Škola Mostar Logo">
                </a>
                <a href="https://www.suljocilic.com.ba/" target="_blank">
                    <img src="https://www.hercegovina.info/img/repository/2024/10/image_640x396/osnovna-skola-suljo-cilic-jablanica.jpg" alt="OŠ Suljo Čilić Jablanica Symbolic Image">
                </a>
            </div>
        </div>
    </div>

    <footer>
        <p>Created with ❤️</p>
    </footer>
</body>
</html>
