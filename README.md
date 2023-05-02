# boat-headphone-css
*{
    box-sizing: border-box;
    font-family: 'josefin sans', sans-serif;
}
body{
    background-image: url('black-headphones-on-matte-background-260nw-1683931528.webp');
    background-size: cover;
    background-repeat: no-repeat;
    background-position: -5px -5px;
    width: 100%;
    position: fixed;
    
}
.hero{
    padding-right: 60px;
}
nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding-top: 40px;
    padding-left: 10%;
    padding-right: 10%;
}
.logo{
    color: white;
    font-size: 28px;
}
span{
    color: #ea1538;
}
nav ul li{
    list-style-type: none;
    display: inline-block;
    padding: 10px 20px;
}
nav ul li a{
    color: white;
    text-decoration: none;
    font-weight: bold ;
}
nav ul li a:hover{
    color: #ea1538;
    transition: .4s;
    text-transform: capitalize;
}
button{
    border: none;
    background: #ea1538;
    padding: 10px 20px;
    border-radius: 15px;
    color: white;
    font-weight: bold;
    font-size: 15px;
}
button:hover{
    transform: scale(1.3);
    cursor: pointer;
}
.continer{
    background: rgba(255, 255, 255, 0.2);
    border-radius: 16px;
    box-shadow: 0 4px 30px rgba(0, 0, 0, 0.1);
    backdrop-filter: blur(5px);
    -webkit-backdrop-filter: blur(5px);
    border: 1px solid rgba(255, 255, 255, 0.3);
}
.hi{
    padding-left: 65%;
    padding-top: 5%;
}
section{
    color: white;
    margin: 2px 5px;
}
section h2{
    color: lightgreen;
}
section h2:hover{
    color: yellow;
}
footer{
    border: none;
    background-color: red;
    float: right;
    padding: 15px 15px;
    border-radius: 15px;
}
footer a{ 
    text-decoration: none;
    text-transform: uppercase;
    color: white;
    font-size: large;
    font-weight: bold;
}
footer a:hover{
    color: yellow;
  transition: 0.6s;
}
