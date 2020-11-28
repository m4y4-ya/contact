
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>
<style>
*::selection{
  color: white;
  background-color: black;
}

body{
  margin: 0;
  padding: 0;
  text-align: center;
  font-family: arial;
  background: url(https://cutewallpaper.org/21/aesthetic-backgrounds-for-computer/Aesthetic-PC-Wallpapers-Wallpaper-Cave.jpg);
  background-size: 145%;
}

.contact-title{
  margin-top: 100px;
  color: #fff;
  text-transform: uppercase;
  transition: all 4s ease-in-out;
}

.contact-title h1{
  font-size: 32px;
  line-height: 10px;
}

.contact-title h2{
  font-size: 16px;
}

form{
  margin-top: 50px;
  transition: all 4s ease-in-out;
}

.form-control{
  width: 600px;
  background: transparent;
  border: none;
  outline: none;
  border-bottom: 1px solid white;
  color: #fff;
  font-size: 18px;
  margin-bottom: 16px;
}

.form-control::placeholder{
  color: white;
}

input{
  height: 45px;
}

form .submit{
  background: #285f7a;
  border-color: transparent;
  border-radius: 10px;
  color: #fff;
  font-size: 20px;
  font-weight: bold;
  height: 50px;
  margin-top: 20px;
}

form .submit:hover{
  background-color: #114a66;
  cursor: pointer;
}
</style>

<div class="contact-title">
  <h1>Say Hello</h1>
  <h2>We are always ready to serve you!</h2>
</div>

<div class="contact-form">
  <form id="contact-form" method="post" action="contact form.php">
    <input name="name" type="text" class="form-control" placeholder="Your Name Here..." required>
    <br>
    <input name="email" type="email" class="form-control" placeholder="Your Email Here..." required>
    <br>
    <textarea style="font-family: arial;" name="message" class="form-control" placeholder="Message" row="4" required></textarea>
    <br>
    
    <input type="submit" class="form-control submit" value="SEND MESSAGE">
    
  </form>
</div>

</body>
</html>
