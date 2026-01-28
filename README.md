<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Valentine?</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin-top: 80px;
      background: #111;
      color: #fff;
    }
    button {
      font-size: 20px;
      padding: 12px 30px;
      margin: 15px;
      cursor: pointer;
    }
    #msg {
      margin-top: 40px;
      font-size: 28px;
    }
  </style>
</head>
<body>

  <h1>Will you be my Valentine? 💘</h1>

  <button onclick="yes()">Yes</button>
  <button onclick="no()">No</button>

  <div id="msg"></div>

  <script>
    function yes() {
      document.getElementById("msg").innerText = "W RIZZ 😎💖";
    }

    function no() {
      const msg = document.getElementById("msg");
      msg.innerText = "…";
      setTimeout(() => msg.innerText = "……", 1000);
      setTimeout(() => msg.innerText = "………", 2000);
      setTimeout(() => msg.innerText = "damn. 💀", 3000);
    }
  </script>

</body>
</html>
