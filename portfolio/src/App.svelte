<script lang="ts">
  import profilepicture from './assets/profile.jpg'
  import netrmsilogo from './assets/netrmsi.png'
  import infecteddepthslogo from './assets/infecteddepths.png'
  import mail from './assets/mail.png'
  import logo from './assets/logo.svg'
  import favicon from '/favicon.svg'
  import gamejolt from './assets/gamejolt.svg'
  import maillobbyer from './assets/maillobbyer.svg'
  import laser from './assets/laser.png'
  
</script>
<head>
  <title>Pa1yn-dev</title>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
</head>
<body>
  <header class="header">
    <div class="file-structure">portfolio / pa1yn-dev</div>  
  </header>
  <div class="container">
    <section class="section">
      <h2>About Me</h2>
      <div class="userinfo">
        <img class="profilepicture" src={profilepicture} alt="Profile Picture">
        <p class="name">Peter Hamilton</p>
        <p class="about">Computer Science student at UOL | Self-taught programmer with experience in C#, .NET, C/C++, Python, Java, and more | Enthusiastic about full-stack development, machine learning, and game development | Proficient in Linux and adept at version control with Git | Passionate about software development, particularly in open-source projects and developing skills related to DevOps and SysAdmin tasks | Currently learning Sveltekit and Rust along with staying updated on and learning more about technologies I already work with.</p>
        <h3>Languages and Tools</h3>
        <ul class="languages-list">
          <li><img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="Bash" title="Bash"></li>
          <li><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="C" title="C"></li>
          <li><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="C++" title="C++"></li>
          <li><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="C#" title="C#"></li>
          <li><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS" title="CSS"></li>
          <li><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="Docker" title="Docker"></li>
          <li><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dot-net/dot-net-original-wordmark.svg" alt=".NET" title=".NET"></li>
          <li><img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git" title="Git"></li>
          <li><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML" title="HTML"></li>
          <li><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java" title="Java"></li>
          <li><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" title="JavaScript"></li>
          <li><img src="https://upload.wikimedia.org/wikipedia/commons/1/13/Arch_Linux_%22Crystal%22_icon.svg" alt="Arch Linux" title="Arch Linux"></li>
          <li><img src="https://www.vectorlogo.zone/logos/mariadb/mariadb-icon.svg" alt="MariaDB" title="MariaDB"></li>
          <li><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL" title="MySQL"></li>
          <li><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" alt="MongoDB" title="MongoDB"></li>
          <li><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" alt="Nginx" title="Nginx"></li>
          <li><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="PHP" title="PHP"></li>
          <li><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" title="Python"></li>
          <li><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/raspberrypi/raspberrypi-original.svg" alt="Raspberry Pi" title="Raspberry Pi"></li>
          <li><img src="https://www.vectorlogo.zone/logos/godotengine/godotengine-icon.svg" alt="Godot Engine" title="Godot Engine"></li>
          <li><img src="https://www.vectorlogo.zone/logos/unity3d/unity3d-icon.svg" alt="Unity" title="Unity"></li>
          <li><img style="filter: invert();" src="https://raw.githubusercontent.com/rust-lang/rust-artwork/master/logo/rust-logo-blk.svg" alt="Rust" title="Rust"></li>
          <li><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/svelte/svelte-original.svg" alt="Svelte" title="Svelte"></li>
        </ul>
        <h3>Contact</h3>
        <ul class="contacts-list">
          <li><a href="https://www.linkedin.com/in/phamilton360/"><img style="filter: invert();" src="https://img.icons8.com/ios-filled/50/000000/linkedin.png" alt="LinkedIn" title="LinkedIn"> LinkedIn</a></li>
        </ul>
      </div>
    </section>
    <section class="section">
      <h2>Portfolio</h2>
      <div class="portfolio">
        <div class="item">
          <img src="{maillobbyer}" alt="MailLobbyer Icon">
          <h3>MailLobbyer</h3>
          <p>Built with ASP.NET Core Blazor and Electron.NET, a batch CSV-based emailing solution with SMTP server integration.</p>
        </div>
        <div class="item">
          <img src="{infecteddepthslogo}" alt="Infected Depths Icon">
          <h3>Infected Depths</h3>
          <p>A work in progess top-down 2D rogue-like shooter built in the Godot engine.</p>
        </div>
        <div class="item">
          <img src="{laser}" alt="LASER Icon">
          <h3>LASER Safety Compliance Service</h3>
          <p>A safety compliance program that monitors LASER's lab space.</p>
        </div>
        <div class="item">
          <img src="{laser}" alt="LASER Icon">
          <h3>LASER Website</h3>
          <p>A website built with SvelteKit.</p>
        </div>
        <div class="item">
          <img src={netrmsilogo} alt="NET-RMSI LOGO">
          <h3>NET-RMSI</h3>
          <p>An open-source networked remote management server interface.</p>
        </div>
      </div>
    </section>
  </div>
  <footer class="footer">
    <p>&copy; 2024 Pa1yn-dev | <a href="https://github.com/Pa1yn-dev">GitHub</a></p>
  </footer>
</body>