* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

header {
    width: 100%;
    height: 100vh;
    background: url('../img/b1.png'), url('../img/bg1.jpeg');
    background-size: 50% 100%, cover;
    background-position: right, center;
    background-repeat: no-repeat, no-repeat;
    -webkit-clip-path: polygon(50% 0%, 100% 0, 100% 75%, 50% 100%, 0% 75%, 0 0);
    clip-path: polygon(50% 0%, 100% 0, 100% 75%, 50% 100%, 0% 75%, 0 0);
    background-attachment: fixed;
}

.logo {
    color: white;
    font-size: 50px;
    padding-left: 30px;
    letter-spacing: 5px;
}

.menu a {
    color: white;
    text-decoration: none;
    padding: 10px 20px;
    margin: 5px;
    font-size: 20px;
    font-weight: bold;
}

.menu {
    margin-right: 100px;
}

nav {
    width: 100%;
    height: 70px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo span {
    color: #e74c3c;
}

.menu a:hover {
    background: #e74c3c;
    transition: 0.4;
}

.text {
    color: white;
    margin-top: 100px;
    margin-left: 100px;
    max-width: 450px;
}

.text h1 {
    font-size: 50px;
    margin: 10px 0px;
}

.text p {
    font-size: 25px;
}

.c-btn {
    border: none;
    outline: none;
    color: white;
    background: crimson;
    padding: 10px;
    margin-top: 20px;
}

#about {
    padding: 100px 50px;
}

.section-info {
    font-weight: bold;
    text-align: center;
}

.section-info h1 {
    font-size: 50px;
}

.section-info p {
    font-size: 25px;
    color: crimson;
}

.about-row {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
}

.about-left-col {
    flex-basis: 50%
}

.about-left-col img {
    width: 100%;
    padding: 50px;
}

.about-right-col {
    flex-basis: 50%;
}

#pro {
    font-size: 20px;
    font-weight: bold;
}

.about-right-col p {
    font-size: 20px;
    text-align: justify;
}

#skills {
    padding: 100px 50px;
    background: url("../img/bg2.jpg");
    background-size: cover;
    color: white;
    background-attachment: fixed;
}

.skills-row {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    background: rgb(45, 52, 54);
    padding: 50px;
}

.skills-left-col {
    flex-basis: 50%;
    text-align: justify;
}

.skills-left-col p {
    font-size: 20px;
}

.skills-right-col {
    flex-basis: 50%;
}

progress {
    width: 80%
}

.progress-div {
    width: 70%;
    margin: auto;
}

.progress-div p {
    margin-bottom: 10px;
    font-size: 20px;
    padding-left: 80px;
    text-align: justify;
}

#service {
    padding: 100px 50px;
}

.service-row {
    display: flex;
    justify-content: space-around;
    align-items: center;
    flex-wrap: wrap;
}

.service-box {
    flex-basis: 25%;
    text-align: center;
    box-shadow: 2px 3px 5px grey;
    padding: 20px;
    margin-top: 20px;
}

.service-box:hover {
    background: #e74c3c;
    color: white;
    transition: 0.4s;
}

.service-box img {
    width: 50%;
}

#contact {
    padding: 100px 50px;
    background: linear-gradient(160deg, #e74c3c 45%, white 0%);
}

.contact-row {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
}

.contact-left-col {
    flex-basis: 50%;
    margin-left: 30px;
}

.contact-right-col {
    flex-basis: 50%;
}

.contact-right-col form {
    text-align: center;
}

.contact-right-col form h2 {
    margin-bottom: 20px;
}

.contact-right-col form input {
    width: 60px;
    padding: 10px;
    margin-bottom: 10px;
}

.contact-right-col form textarea {
    width: 60%;
    padding: 10px;
}

#footer {
    background: #e74c3c;
    color: white;
    padding: 20px;
    display: flex;
    justify-content: space-around;
    align-items: center;
    font-size: 20px;
}
