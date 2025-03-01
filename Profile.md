# New web for Bom ( I'm beginner TwT )

<!DOCTYPE html>
<html lang="th">
  <head>
    <meta charset="UTF-8" />
    <link
      rel="shortcut icon"
      href="https://static.vecteezy.com/system/resources/previews/011/973/413/non_2x/cat-face-cute-free-download-transparent-image-illustration-clipart-pet-wildlife-free-png.png"
      type="image/x-icon"
    />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Login | Bom web</title>
    <link rel="stylesheet" href="style.css" />
    <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
    />
  </head>
  <body>
    <center>
     <div class="container">
      <h1>เข้าสู่ระบบ</h1>
      <img id="statusImage" src="c:\Users\PC\Downloads\png-clipart-kitten-tabby-cat-whiskers-graphics-kitten-mammal-animals-Photoroom.png" 
        height="100" width="120" alt="Status Image" />
      <form id="loginForm">
        <div id="errorMessage" class="error-message"></div>
        <div class="input-group">
          <input type="text" id="username" placeholder="กรอกชื่อ" />
        </div>
        <div class="input-group">
          <input type="password" id="password" placeholder="กรอกรหัสผ่าน" />
        </div>
        <p> <button type="submit">เข้าสู่ระบบ</button> </p>
      </form>
     </div>

      <!-- ป๊อบอัพ -->
     <div class="modal" id="successModal">
      <div class="modal-content">
        <span class="close" id="closeModal">&times;</span>
        <h2>จัดทำโดย นายธนกฤต ศิริผล</h2>
        <img src="c:\Users\PC\Downloads\Scanned_20241109-2118.jpg" height="500" width="400" alt="Success Image" />
      </div>
     </div>
     <p>
        ช่องทางการติดต่อ
     </p>
     <p><button>
        <a id="round" href="https://www.instagram.com/02.3bqmx/" target="_blank">Instragram </a>
     </button></p>
    </center>
  </body>
</html>
