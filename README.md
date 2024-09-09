## Hi there 👋
<body>
   <div class="container"> <div class="erath">
    <canvas class="hole h1">e</canvas>
    <canvas class="hole h2"></canvas>
    <canvas class="hole h3"></canvas>
    <canvas class="hole h4"></canvas>
    <canvas class="hole h5"></canvas>
    <canvas class="hole h6"></canvas>
    <canvas class="eye e1"></canvas>
    <canvas class="eye e2"></canvas>
    <canvas class="lip "></span>
</div>
<div id="orbit">
    <div id="rocket">
        <canvas id="r_body"></canvas>
        <canvas id="window"></canvas>
        <canvas id="wing"></canvas>
        <canvas id="engine"></canvas>
    </div>
</div>
</div>
    
</body>

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
    display: flex;
    width: 100vw;
    height: 100vh;
    background-color: #131948;
    justify-content: center;
    align-items: center;
}


.h1{
    position: relative;
    top: 85px;
    left: 20px;
    width: 25px;
    height: 25px;
    border-radius: 50%;
    background-color: #23A8FF;
    box-shadow: inset 05px 2px 5px #189DFC;
}
.h2{
    position: relative;
    top: 15px;
    left:20px;
    width: 20px;
    height: 20px;
    border-radius: 50%;
    background-color: #23A8FF;
    box-shadow: inset 05px 2px 5px #189DFC;
}
.h3{
    position: relative;
    top: 40px;
    left: 55px;
    width:35px;
    height: 35px;
    border-radius: 50%;
    background-color: #23A8FF;
    box-shadow: inset 05px 2px 5px #189DFC;
}
.h4{
    position: relative;
    top: 120px;
    left: 50px;
    width: 35px;
    height: 35px;
    border-radius: 50%;
    background-color: #23A8FF;
    box-shadow: inset 05px 2px 5px #189DFC;
}
.h5{
    position: relative;
    top: 80px;
    left:-75px;
    width: 10px;
    height: 10px;
    border-radius: 50%;
    background-color: #23A8FF;
    box-shadow: inset -05px 2px 5px #189DFC;
}
.h6{
    position: relative;
    top: 80px;
    left:-30px;
    width: 10px;
    height: 10px;
    border-radius: 50%;
    background-color: #23A8FF;
    box-shadow: inset 05px 2px 5px #189DFC;
}
.e1{
    position: relative;
    top: 60px;
    left:-85px;
    width: 10px;
    height: 10px;
    border-radius: 50%;
    background-color: #000;
    

}
.e2{
    position: relative;
    top: 60px;
    left:-75px;
    width: 10px;
    height: 10px;
    border-radius: 50%;
    background-color: #000;
}
.lip{
    position: relative;;
    top: 45px;
    left: 75px;
    width: 35px;
    height: 35px;
    border-bottom: 2px solid;
    border-radius: 50px;
}
.erath{
    position: relative;
    transform: scale(.9);
    z-index: -99;
    left: 50%;
    background-color: #2CB3FF;
    min-width: 200px;
    min-height: 200px;
    max-width: 200px;
    max-height: 200px;
    border-radius: 50%;
    box-shadow: inset -25px 8px 15px #068cec,
    inset 2px 2px 10px #068cec;

}
.container{
    display: flex;
    justify-content: center;
    align-items: center;
    width: 500px;
    height: 500px;
}
#orbit{
    position: absolute;
    left: -20%;
    z-index: 99;
    width: 500px;
    height: 500px;
    border-radius: 50%;
    position: relative;
    animation: router linear 5s infinite;
}
#rocket{
    position: absolute;
    transform: scale(1);
    position: relative;
    left: 0%;
    z-index: 50;
    top: 180px;
    min-width: 500px;
    min-height:500px;
    max-width: 500px;
    max-height:500px;
    animation: router 10s  linear  infinite;
}
@keyframes router {
    100%{transform:rotate(360deg);}
    
}
#r_body{
  position: relative;
  width: 50px;
  height: 120px;
  background-color: #fff;
  border-radius: 90% 90% 0 0  ;
  z-index: 100;
}
#window{
    width: 25px;
    height: 25px;
    background-color: rgba(0, 0, 0, 0.856);
    border-radius: 50%;
    position: relative;
    left: -42px;
    top: -65px;
    z-index: 101;
}
#wing{
    width: 120px;
    height: 40px;
    background-color: #2FB4FF;
    border-radius: 50% 50% 0 0 ;
    position: relative;
    left: -120px;
    z-index: 99;
}

#engine{
    z-index: 98;
    position: relative;
    left: -200.5px;
    border-radius: 0 0 20% 20%  ;
    top: 10px;
    width: 35px;
    height: 10px;
    background-color: #2FB4FF;
}



<!--
**nonle-dev/nonle-dev** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
