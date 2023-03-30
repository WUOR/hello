* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

html {
    scroll-behavior: smooth;
}

.navbar {
    width: 100%;
    height: 100px;
    background-color: rgba(0, 26, 0, 0.986);



}

.logo {
    width: 50%;
    float: left;
    padding-left: 5px;

}

nav {
    width: 50%;
    float: right;
    margin-top: 40px;
}

ul {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-around;
}

li {
    list-style-type: none;
}

a {
    text-decoration: none;
    text-transform: capitalize;
    font-family: Geneva;
    font-size: 20px;
    color: white;
    text-transform: uppercase;
    font-weight: bold;
}

.descri {
    text-decoration: none;
    text-transform: uppercase;
    text-align: center;
    font-size: 40px;
    font-family: Geneva;
    color: white;
    padding-top: 400px;
}

.intro {
    font-size: 40px;
    word-spacing: 3px;
    padding: 25px;
    font-family: Geneva;
}

.baa {
    font-size: 70px;
    word-spacing: 4px;
    font-family: Geneva;
}

a:hover {
    color: rgb(1, 75, 11);
    background-color: rgb(4, 216, 145);
}

#hero {
    width: 100%;
    height: 100vh;
    background-image: url('../img/4.jpeg');
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
}

.overlay {
    width: 100%;
    height: 100vh;
    background-color: rgba(0, 0, 0, 0.6);

}

.btn {
    margin-top: 600px
}

.btn {

    position: absolute;
    right: 15px;
    bottom: 0;

    border: 3px solid;
    font-weight: bolder;
    border-radius: 10;
    font-size: 30px;
    padding: 8px 5px;
    text-align: center;
    background: rgb(4, 158, 55);
    color: rgb(255, 255, 255);
    border-radius: 20px;
}

.btn:hover {
    color: rgb(255, 255, 255);
    background-color: rgb(56, 202, 183);
}

#about {
    width: 100%;
    height: 750px;
}

.about-head {
    width: 100%;
    margin-top: 35px;

}

.about-head h1 {
    text-align: center;
    text-transform: uppercase;
    font-size: 25px;
    font-family: candara;
    font-weight: bold;
    line-height: 1rm;
}

.row {
    width: 100%;
    height: 500px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-around;
    position: relative;


}

.row::after {
    content: "";
    left: 0;
    top: 0;
    background: rgba(0, 0, 0, 0.7);
    position: absolute;
    z-index: 1;

}

.col1 {
    width: 47%;
    height: 400px;

    background: linear-gradient(rgba(5, 24, 1, 0.822), rgba(2, 46, 0, 0.774)), url(../img/3.jpg);
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
}


.col2 {
    width: 47%;
    height: 400px;
    background: linear-gradient(rgba(5, 24, 0, 0.822), rgba(2, 46, 0, 0.863)), url(../img/2.jpg);
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
}

.mission1 {
    padding-top: 60px;
    text-align: center;
    color: rgb(28, 255, 8);
    text-transform: uppercase;
    font-family: Geneva;
    font-size: 20px;
}

.mission2 {
    padding-top: 100px;
    text-align: center;
    color: rgb(28, 255, 8);
    text-transform: uppercase;
    font-family: Geneva;
    font-size: 20px;
}

.texts {
    color: white;
    font-size: 18px;
    font-size: Geneva;
    line-height: 1rm;
    text-align: center;
    padding-top: 30px;
}

.para {
    color: white;
    font-size: 18px;
    font-family: Geneva;
    text-align: center;

}

#projects {
    width: 100%;
    height: auto;
    margin-top: 10px;
}

.project-head {
    width: 100%;

}

.project-head h1 {
    text-align: center;
    text-transform: uppercase;
    font-size: 30px;

}

.project-img {
    width: 90%;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-around;
    margin: 20px auto;
}

.project-img img {
    border: 2px solid white;
    border-radius: 15px;
}

.project-text {
    color: black;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    font-size: 15px;
    text-align: center;
    padding: 15px;
}

#team {
    width: 100%;
    height: auto;
    margin-top: 150px;
}

.team-head {
    width: 100%;

}

.team-head h1 {
    text-align: center;
    text-transform: uppercase;
    font-size: 30px;

}

.team-img {
    width: 100%;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-around;
    margin: 30px auto;
    padding-left: 20px;

}

.team-img img {
    width: 180px;
    height: 170px;
    border-radius: 50%;
}

.content-text {
    color: black;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    font-size: 15px;
    text-align: center;
    padding: 15px;
}

.vol-team {
    width: 100%;
    height: auto;
    margin-top: 150px;
}

.vol-team-head {
    width: 100%;

}

.vol-team-head h1 {
    text-align: center;
    text-transform: uppercase;
    font-size: 30px;

}

.vol-team-img {
    width: 100%;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-around;
    margin: 30px auto;
    padding-left: 20px;

}

.vol-team-img img {
    width: 180px;
    height: 170px;
    border-radius: 50%;
}

.row21 {
    background-color: rgba(0, 26, 0, 0.986);
    width: 1200px;
    height: 50%;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-around;
    position: relative;
    margin: 0 auto
}

input[type=text],
select,
textarea {
    width: 100%;
    padding: 12px;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
    margin-top: 6px;
    margin-bottom: 16px;
    resize: vertical;
}

input[type=submit] {
    background-color: #52a7df;
    color: rgb(255, 255, 255);
    padding: 12px 20px;
    border: none;
    border-radius: 4px;
}

.footer {
    text-align: center;
    padding-top: 40px;
    background-color: rgba(0, 26, 0, 0.986);
}

.footer-half {
    font-size: 15px;
    color: #ccc;
}

.footer-half-head {
    color: rgb(255, 254, 254);
    font-size: 10px;
}

.footer-half-head:hover {
    color: rgb(255, 255, 255);
    background: transparent;
}


/* style our service section */

#service {
    width: 100%;
    height: 500px;
    background-image: linear-gradient( rgba(12, 29, 19, 0.788) 30.48%, rgba(13, 58, 16, 0.863) 73.52%), url('../img/serv.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    margin-top: 50px;
    padding-top: 70px;
}

.row-service1 {
    width: 100%;
    height: auto;
    padding-bottom: 100px;

}

.row-service2 {
    width: 100%;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-around;
}

.column {
    margin-top: 65px;
}

.card {
    width: 300px;
}

.card h3 {
    margin-bottom: 40px;
    text-align: center;
    color: #fff;
    font-size: 18px;
    text-transform: capitalize;
}

.card p {
    color: #fff;
    font-size: 15px;
    text-align: center;
    

}
