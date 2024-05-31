<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background-color: #f4f4f4;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      flex-direction: column;
    }
    .content-container {
      background: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      max-width: 800px;
      width: 100%;
      margin: 20px;
    }
    h2, h3 {
      color: #333;
      text-align: center;
    }
    .skills-list {
      display: flex;
      flex-wrap: wrap;
      list-style-type: none;
      padding: 0;
      margin: 0;
    }
    .skills-list li {
      background: #f9f9f9;
      margin: 5px;
      padding: 10px;
      border: 1px solid #ddd;
      border-radius: 4px;
      flex: 0 0 48%; /* Two columns */
      box-sizing: border-box;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    .skills-list li:hover {
      background: #f1f1f1;
    }
    .skills-list li::before {
      content: "•";
      color: #0073e6;
      font-weight: bold;
      margin-right: 8px;
    }
    a {
      color: #0073e6;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <div class="content-container">
    <h2>Hi 👋, I'm Abdullah</h2>
    <h3>A passionate Developer and Coder!</h3>
    <p>🔭 I’m currently working on <a href="https://laravel.com" id="laravel">Laravel</a> with <a href="https://vuejs.org" id="vuejs">VueJS</a>!</p>
    <p>📝 2024 Goals: Contribute more to Open Source projects</p>
    <p>⚡ Fun fact: I passionately love solving problems!</p>

    <h3>Reach me at:</h3>
    <p>Email: <a href="mailto:abdullah001rti@gmail.com">abdullah001rti@gmail.com <img width="11" src="https://user-images.githubusercontent.com/5141132/50740364-7ea80880-1217-11e9-8faf-2348e31beedd.png" alt="Email Icon"></a></p>
    <p>LinkedIn: <a href="https://www.linkedin.com/in/abd1rti/">Md. Abdullah <img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg" alt="LinkedIn" height="15" width="12"></a></p>
    
    <h3>Languages and Skills:</h3>
    <ul class="skills-list">
      <li>Laravel</li>
      <li>CodeIgniter</li>
      <li>Tailwind CSS</li>
      <li>Livewire</li>
      <li>Vue.js</li>
      <li>Nuxt.js</li>
      <li>PHP</li>
      <li>AWS</li>
      <li>MariaDB</li>
      <li>Bootstrap</li>
      <li>Chart.js</li>
      <li>CSS3</li>
      <li>HTML5</li>
      <li>MySQL</li>
      <li>Webpack</li>
    </ul>
  </div>
</body>
</html>
