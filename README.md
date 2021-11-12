*{
    padding: 0;
    margin: 0;
    font-family: sans-serif;
}

body{
    background: url('./12.jpg') no-repeat;
    background-size: cover;
}

.login-form {
    width: 350px;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    position: absolute;
    color: #4d3211;
}

.login-form h1 {
    font-size: 40px;
    text-align: center;
    text-transform: uppercase;
    margin: 40px 0;
}

.login-form p {
    font-size: 20px;
    margin: 15px 0;
}

.login-form input {
    font-size: 16px;
    width: 100%;
    padding: 15px 10px;
    border: 0;
    outline: none;
    border-radius: 5px;
}

.login-form button {
    font-size: 18px;
    font-weight: bold;
    margin: 20px 0;
    padding: 10px 15px;
    width: 50%;
    border-radius: 5px;
    border: 0;
}

.navbar{
    width: 1500px;
    height: 75px;
    margin: auto;
}

.icon{
    width: 200px;
    float: left;
    height: 70px;
}
 
.logo{
    color: rgb(8, 0, 0);
    font-size: 55px;
    font-family: Arial;
    padding-left: 30px;
    float: left;
    padding-top: 10px;
}

ul{
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
}

a:link,a:visited{
    display: block;
    font-weight: bold;
    margin-top: 20px;
    color: #ffffff;
    width: 150px;
    text-align: right;
    padding: 4px;
    text-transform: uppercase;
}

a:hover,a:active{
    background-color: #040500;
    text-decoration: none;
}
li{
    float: left;
}

.search{
    width: 500px;
    float: right;
    margin-left: 1200px;
}

.srch{
    font-family: 'Times New Roman';
    width: 330px;
    height: 40px;
    background: #fff;
    border: 1px solid #ff7200;
    margin-top: 13px;
    margin-left: 50px;
    color: #fff;
    border-right: none;
    font-size: 16px;
    float: left;
    padding: 10px;
    border-bottom-left-radius: 5px;
    border-top-left-radius: 5px;
    
}

.btn{
    width: 100px;
    height: 40px;
    background: #ff7200;
    border: 2px solid #ff7200;
    margin-top: 13px;
    color: #fff;
    font-size: 15px;
    border-bottom-right-radius: 5px;
    border-bottom-right-radius: 5px;
}

.btn:focus{
    outline: none;
}

.srch:focus{
    outline: none;
}

.content{
    width: 1500px;
    font-size: 10px;
    height: 10px;
    margin: auto;
    margin-left: 70px;
    color: rgba(255, 255, 255, 0.5);
    position: absolute;
}

.paragraph .par{
    padding-right: 10px;
    padding-bottom: 25px;
    margin-left: 100px;
    font-family: 'Segoe UI';
    font-size: 50px;
    color: #4d3211;
    letter-spacing: 1.2px;
    line-height: 50px;
}

.paragraph h1{
    font-family: 'Times New Roman';
    font-size: 60px;
    padding-left: 40px;
    margin-top: 5px;
    letter-spacing: 2px;

}

.paragraph .cn{
    width: 160px;
    height: 40px;
    background: #4d3211;
    border: none;
    margin-bottom: 10px;
    margin-left: 100px;
    font-size: 14px;
    border-radius: 10px;
    cursor: pointer;
    transition: .4s ease-in-out;
}

.paragraph .cn a{
    text-decoration: none;
    color: #f5f5ee;
    transition: .3s ease;
}
.cn:hover{
    background-color: #040500
}
