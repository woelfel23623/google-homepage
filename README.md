# google-homepage
nav {
  float: right;
  margin-right: 12px;
}
nav a {
  text-decoration: none;
  margin: 8px;
  font-family: arial;
  font-size: 13px;
  color: #000;
}

#gapps, #notifications, #user{
  position: relative;
}
#gapps {
  width: 16px;
  top: 3px;
  opacity: 0.5;
}
#gapps:hover {
  opacity: 1;
}
#notifications {
  width: 20px;
  top: 5px;
  opacity: 0.5;
}
#notifications:hover {
  opacity: 1;
}
#user {
  width: 32px;
  border-radius: 50px;
  top: 10px;
}

.main {
  position: relative;
}

.searchbox {
  position: absolute;
  top: 43%;
  left: 50%;
  transform: translate(-50%, -57%);
  /*border: 1px solid red;*/
}

.logo {
  width: 570px;
}
.logo img {
  display: block;
  margin: auto;
}

input {
  /*background-image: url(../images/mic.png);
  background-position: right center;
  background-repeat: no-repeat;
  background-size: 24px;*/
  font-size: 16px;
  width: 100%;
  padding: 12px;
  margin: 25px 0;
  border: 1px solid #e5e6e8;
  border-radius: 2px;
  box-shadow: 0 2px #d3d3d3;

}
input:focus, input:hover {
  outline: none;
  box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.2), 0 3px 5px 0 rgba(0, 0, 0, 0.19);
}

.mic {
  float: right;
  position: relative;
  top: -59px;
  right: 10px;
}
.mic img {
  width: 24px;
}


form {
  text-align: center;
}
button {
  padding: 10 16px;
  margin: 0 2px;
  font-family: arial;
  font-size: 13px;
  font-weight: 800;
  color: gray;
  border: 1px solid #f2f2f2;
  border-radius: 2px;
  background-color: #f2f2f2;
}
button:hover {
  border: 1px solid #d3d3d3;
}

footer {
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%;
  line-height: 40px;
  background-color: #f2f2f2;
  border-top: 1px solid #d3d3d3;
}

footer .leftside-links {
  float: left;
  margin-left: 17px;
}
footer .rightside-links {
  float: right;
  margin-right: 15px;
}

footer a, footer a:link {
  text-decoration: none;
  margin: 13px;
  font-family: arial;
  font-size: 13px;
  color: #666;