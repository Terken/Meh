@font-face {
  font-family: Morris;
  src: url(https://cdn.statically.io/gh/EmmesCodes/Tipografias/dae9f5bb/MorrisInitials.ttf);
}
.MB4,
.MB4 * {
  box-sizing: border-box;
  transition: 0.5s;
}
.MB4 {
  width: 600px;
  margin: auto;
  background: url(http://i67.tinypic.com/1yvlgl.jpg) #111;
  font: 10px Merriweather;
  color: #999;
  position: relative;
  padding: 50px 0;
}
.riMB4 {
  position: absolute;
  top: -10px;
  left: 20px;
  width: 100px;
  height: 150px;
}
.riMB4::before,
.riMB4::after {
  content: "";
  position: absolute;
  width: 100%;
  height: 100%;
  box-shadow: inset 0 0 70px #000, inset 0 0 0 100px;
  top: 0;
  left: 0;
  clip-path: polygon(
    0 0,
    0 Calc(100% - 50px),
    50% 100%,
    100% Calc(100% - 50px),
    100% 0
  );
  z-index: 1;
}
.riMB4::after {
  margin: 5px;
  filter: blur(10px);
  box-shadow: inset 0 0 0 100px #000;
  z-index: 0;
}
.riMB4 span {
  font: 40px IM Fell English SC;
  z-index: 3;
  position: absolute;
  top: 45%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: #c3aa3e;
  text-shadow: 1px 1px 2px #000;
}
.ttMB4 {
  font: 20px IM Fell English SC;
  text-shadow: 1px 1px 2px #000;
  color: #fff;
  margin: 10px 0 0 130px;
  display: block;
  position: relative;
  z-index: 2;
}
.imMB4 {
  -webkit-mask-image: url(https://i.imgur.com/yD2UOz5.png);
  -webkit-mask-size: 100%;
  width: 100%;
  opacity: 0.6;
  margin-top: -50px;
}
.sepMB4 {
  height: 15px;
  background-image: url(https://i.imgur.com/xzjBiDM.png);
  background-size: auto 100%;
  margin-top: -10px;
  position: relative;
}
.daMB4 {
  position: relative;
  margin: -100px -10px 0 300px;
  height: 120px;
  padding: 10px 0;
}
.daMB4::before {
  content: "\7b";
  text-shadow: 1px 1px 2px #000;
  font: 120px/120px IM Fell English SC;
  position: absolute;
  top: -5px;
}
.daMB4 > div {
  margin: 5px 0 0 45px;
  height: 85px;
  overflow: auto;
}
.daMB4 > div > br {
  display: none;
}
.daMB4 > div > span {
  display: block;
}
.daMB4 > div > span {
  display: block;
  background: #1119;
  margin-bottom: 5px;
  padding: 5px;
  color: #999;
}
.daMB4 > div > span b {
  color: #c3aa3e;
  letter-spacing: 1px;
  margin-right: 5px;
  text-shadow: 1px 1px 2px #000;
}
.xxMB4 {
  margin: 30px 50px 0;
  text-align: justify;
  font-size: 12px;
}
.xxMB4::first-letter {
  color: #a48455;
  font: 60px Morris;
  float: left;
  margin: 10px 10px 0;
  text-shadow: 1px 1px 2px #000;
}
.miMB4 {
  display: block;
  text-align: right;
  color: #c3aa3e !important;
  text-shadow: 1px 1px 2px #000;
  font: 15px IM Fell English SC;
  margin: 40px -10px -55px;
  transition: 0.5s;
  letter-spacing: 5px;
}
.miMB4:hover {
  letter-spacing: 7px;
}
.MB4 div::-webkit-scrollbar {
  width: 5px !important;
  height: 5px !important;
  background: #FFF6 !important;
}
.MB4 div::-webkit-scrollbar-thumb {
  background: #FFF6 !important;
}
