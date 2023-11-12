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
</head>
<body>
  <header class="header">
    <img class="logo" src={logo} alt="Logo">
  </header>
  <div class="container">
    <section class="section">
      <h2>About Me</h2>
      <div class="userinfo">
        <img class="profilepicture" src={profilepicture} alt="Profile Picture">
        <p class="name">Peter Hamilton</p>
        <p>I am a passionate and motivated back-end developer.</p>
        <p2>Currently learning: Rust and Svelte.</p2>
        <h3>Languages and Tools</h3>
        <ul class="languages-list">
          <li>
            <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="Bash" title="Bash">
          </li>
          <li>
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="C" title="C">
          </li>
          <li>
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="C++" title="C++">
          </li>
          <li>
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="C#" title="C#">
          </li>
          <li>
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS" title="CSS">
          </li>
          <li>
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="Docker" title="Docker">
          </li>
          <li>
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dot-net/dot-net-original-wordmark.svg" alt=".NET" title=".NET">
          </li>
          <li>
            <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git" title="Git">
          </li>
          <li>
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML" title="HTML">
          </li>
          <li>
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java" title="Java">
          </li>
          <li>
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" title="JavaScript">
          </li>
          <li>
            <img src="https://upload.wikimedia.org/wikipedia/commons/1/13/Arch_Linux_%22Crystal%22_icon.svg" alt="Arch Linux" title="Arch Linux">
          </li>
          <li>
            <img src="https://www.vectorlogo.zone/logos/mariadb/mariadb-icon.svg" alt="MariaDB" title="MariaDB">
          </li>
          <li>
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL" title="MySQL">
          </li>
          <li>
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" alt="MongoDB" title="MongoDB">
          </li>
          <li>
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" alt="Nginx" title="Nginx">
          </li>
          <li>
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="PHP" title="PHP">
          </li>
          <li>
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" title="Python">
          </li>
          <li>
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/raspberrypi/raspberrypi-original.svg" alt="Raspberry Pi" title="Raspberry Pi">
          </li>
          <li>
            <img src="https://www.vectorlogo.zone/logos/godotengine/godotengine-icon.svg" alt="Godot Engine" title="Godot Engine">
          </li>
          <li>
            <img src="https://upload.wikimedia.org/wikipedia/commons/1/1b/Svelte_Logo.svg" alt="Svelte" title="Svelte">
          </li>
        </ul>
        
        <h3>Contact</h3>
        <ul class="contacts-list">
          <li>
            <a href="mailto:peterhamilton522@gmail.com">
              <img src={mail} alt="Mail icon" />
              <span>Email</span>
            </a>
          </li>
          <li>
            <a href="https://github.com/Pa1yn-dev">
              <img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" alt="Github logo">
              <span>Github</span>
            </a>
          </li>
          <li>
            <a href="https://www.linkedin.com/in/phamilton360/">
              <img src="https://upload.wikimedia.org/wikipedia/commons/c/ca/LinkedIn_logo_initials.png" alt="LinkedIn logo">
              <span>LinkedIn</span>
            </a>
          </li>
        </ul>                
      </div>
    </section>
    <section class="section">
      <h2>Portfolio</h2>
      <div class="portfolio">
        <a href="https://github.com/NET-RMSI" class="item-link">
          <div class="item">
            <img src={netrmsilogo} alt="NET-RMSI LOGO">
            <h3>NET-RMSI</h3>
            <p>An open-source networked remote management server interface.</p>
          </div>
        </a>
        <a href="https://gamejolt.com/games/Infected-Depths/781949" class="item-link">
          <div class="item">
            <img src={infecteddepthslogo} alt="NET-RMSI LOGO">
            <h3>Infected-Depths</h3>
            <p>A work in progess top-down 2D rogue-like shooter built in the Godot engine.</p>
          </div>
        </a>
        <a href="https://github.com/Pa1yn-dev/Pa1yn-dev-Website" class="item-link">
          <div class="item">
            <img src={favicon} alt="Portfolio Logo">
            <h3>Portfolio website</h3>
            <p>Built with Svelte and Typescript, being my first main frontend project.</p>
          </div>
        </a>
        <a href="https://github.com/Pa1yn-dev/MailLobbyer" class="item-link">
          <div class="item">
            <img src={maillobbyer} alt="MailLobbyer Logo">
            <h3>MailLobbyer</h3>
            <p>Built with ASP.NET Core Blazor, a CSV-based emailing solution with SMTP server integration.</p>
          </div>
        </a>
        <a href="https://github.com/UOL-LASER/AreYouDeadBot" class="item-link">
          <div class="item">
            <img src={laser} alt="LASER Logo">
            <h3>LASER Safety Service</h3>
            <p>A safety compliance program that monitors LASER's lab space.</p>
          </div>
        </a>
        <a href="https://github.com/UOL-LASER/LASERWebsite" class="item-link">
          <div class="item">
            <img src={laser} alt="LASER Logo">
            <h3>LASER Website</h3>
            <p>Built with ASP.NET Core WASM, LASER's website.</p>
          </div>
        </a>
      </div>
      <h2>Other projects</h2>
      <div class="portfolio">
        <a href="" class="item-link">
          <div class="item">
            <img src="" alt="">
            <h3>A2 Technology and Design coursework</h3>
            <p>A portable desktop AIO solution for hybrid workers | Currently under examination, more project details after clearance.</p>
          </div>
        </a>
    </section>
  </div>
  <footer class="footer">
    <a href="https://pa1yn-dev.flarenet.co.uk"><p>© 2023 Peter Hamilton - pa1yn-dev.flarenet.co.uk</p></a>
  </footer>
</body>


