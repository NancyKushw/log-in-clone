# log-in-clone
here's my first project from html and css
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css" integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="rhino.css">
</head>
<body>
    <div class="wrapper">
        <form action="">
            <h1> login</h1>
            <div class="input-box"> <input type="text" placeholder="username or email" required>
                <i class="fa-solid fa-user"></i>
            </div>
            <div class="input-box"> <input type="password" placeholder="enter password" required>
                <i class="fa-solid fa-lock"></i>
            </div>
            <!--<div class="remember"><input type="text"></div> -->
            <div class="remember">
                <label> <input type="checkbox"> remember me </label>
                <a href="#"> forgot password?</a>
            </div>
            <div class="bun">
            <button type="submit" > log-in</button>
            </div>
            <div class="register">
                <p> Don't have an account? <a href="#" > register now ! </a></p>
            </div>
        </form>
    </div>
</body>
</html>


* {
    margin: o;
    padding: 0;
    box-sizing: border-box;
    font-family:cursive;
}

body{
    display:flex;
    justify-content:center;
    align-items: center;
    min-height: 100vh;
    background-image: url("not.jpg");
    /*background-position: center;*/
    background-size: cover;
}
.wrapper{
    width: 420px;  
    color: #fff;
    background-color: transparent;
    border: 2px solid rgba(255 ,255 ,255 ,.2);
    border-radius: 10px;
  /*  padding: 30px 40px;
*/
}
.wrapper h1{
    text-align: center;
    font-size: 36px;

}
.wrapper .input-box{
  width: 200px;
  height: 50px;
  margin: 30px 0;
  position: relative;
 left: 110px;
 margin-top: 40px;
}
.input-box input {
 width: 100%;
 height: 100%px;
 background-color: transparent;
 border: none;
 outline: none;
 border:2px solid rgba(255 ,255 ,255 ,.2);
 border-radius: 40px;
 padding: 20px 40px 20px 20px;
 
 display: flex;
 justify-content: center;
 

}
.input-box input ::placeholder{
 color: #fff;

}
.input-box i{
    position: absolute;
    right:20px;
    top: 50%;
    transform: translateY(-50%);
    font-size: 20px;


}
.remember{
    display: flex;
    justify-content: space-evenly;
    font-size: 14px;
    margin: -15px 0 15px;
}
.remember label input{
     accent-color: #fff;
     margin-right:3px;
}
.remember a {
    text-decoration: none;
    color: #fff;
    }
.remember a:hover{
        text-decoration: underline;
    }
.register p a{
        color:#fff;
        text-decoration: none;
     
    }

.register p a:hover{
        text-decoration: underline;
    }

.bun {
            text-align: center;
            margin-top: 20px;
            margin:0 auto;
           
         
}
        
    

