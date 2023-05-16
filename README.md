# NguyenCV
Nguyen
<html lang="en">
 
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport"
          content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="resume.css">
</head>
 
<body>
    <div class="full">
        <div class="left">
            <div class="image">
                <img src= TOM.jpg
                     style="width:100px;height:100px;">
            </div>
            <div class="Contact">
                <h2>Contact</h2>
                <p><b>Email id: </b>NguyenNCCE170104@gmail.com</p>
                <p><b>Mobile no :</b>091234567</p>
            </div>
            <div class="Skills">
                <h2>Skills</h2>
                <ul>
                    <li><b>Programming Languages :
                      Java, C++</b></li>
                    <li><b>Frontend : HTML5, CSS3,
                      JavaScript</b></li>
                </ul>
            </div>
            <div class="Language">
                <h2>Language</h2>
                <ul>
                    <li>English</li>
                    <li>Russian</li>
			  <li>Japanese</li>
                </ul>
            </div>
            <div class="Hobbies">
                <h2>Hobbies</h2>
                <ul>
                    <li>Playing League of Legends</li>
                    <li>Shooting</li>
                </ul>
		    <br><br>
		    <a href= "https://www.youtube.com/watch?v=dQw4w9WgXcQ" style="color:blue" > more </a>
            </div>
        </div>
        <div class="right">
            <div class="name">
                <h1>Tomcat</h1>
            </div>
            <div class="title">
                <p>Software Developer</p>
            </div>
            <div class="Summary">
                <h2>Summary</h2>
                <p>To secure a challenging position in a
                  reputable organization
                    to expand my learning knowledge and skill
                </p>
            </div>
            <div class="Experience">
                <h2>Experience</h2>
                <h3>Java programming</h3>
                <p>January 2023 to Present</p>
                <ul>
                    <li>Actively participate in programming a book 
			   	management project for the library.</li>
                    <li>Designing project & planning</li>
                </ul>
                <h3>C++ programing</h3>
                <p>September 2022 to December 2022</p>
                <ul>
                    <li>Actively create and develop computational software.</li>
                    <li>Designing project & planning</li>
                </ul>
            </div>
            <div class="Education">
                <h2>Education</h2>
                	<h3>FPT university</h3>
			<p>September 2021 to now</p>
			<h3>Coursera education</h3>
			<p>September 2022 to now</p>
                    
            </div>
            <div class="project">
                <ul>
                    <li>
                        <h2>Project1</h2>
                        <p>Create and develop computational software.</p>
                    </li>
                    <li>
                        <h2>Project2</h2>
                        <p>Programming a book management project for the library.</p>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</body>
 
</html>

/* Write CSS Here */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    background-color: rgb(253, 254, 255);
    display: flex;
    justify-content: center;
    align-items: center;
}
.full {
    width: 50%;
    max-width: 1000px;
    min-height: 100px;
    background-color: rgb(245, 239, 231);
    margin: 0px;
    display: grid;
    grid-template-columns: 2fr 4fr;
}
.left {
    position: initial;
    background-color: rgb(126, 219, 231);
    padding: 20px;
 
}
.right {
    position: initial;
    background-color: rgb(162, 202, 206);
    padding: 20px;
 
}
.image, .Contact, .Skills, .Language, .Hobbies, .title,
.Summary, .Experience, .Education, .project {
    margin-bottom: 30px;
}
.h2 {
    background-color: rgb(4, 96, 150);
}
