
<h1 align="center" style="color: #00ff00;">Certificados Y conocimientos | reddix6</h1>

<p align="center" style="color: #00ff00;">
  <i>They very funny hahahahaha</i>
</p>

---

$ whoami

> reddix6 | Hacker Ético | Dev | OSINT





$ pwd

> /home/github/reddix6





$ ls -la

> proyectos/ scripts/ secretos/ contacto/



---

## 👨‍💻 Habilidades Técnicas

<p align="left">
  <img src="https://img.icons8.com/color/48/000000/html-5--v1.png" title="HTML" />
  <img src="https://img.icons8.com/color/48/000000/css3.png" title="CSS" />
  <img src="https://img.icons8.com/color/48/000000/javascript--v1.png" title="JavaScript" />
  <img src="https://img.icons8.com/color/48/000000/python--v1.png" title="Python" />
  <img src="https://img.icons8.com/office/48/000000/react.png" title="React" />
  <img src="https://img.icons8.com/color/48/000000/mysql-logo.png" title="MySQL" />
  <img src="https://img.icons8.com/color/48/000000/firebase.png" title="Firebase" />
  <img src="https://img.icons8.com/color/48/000000/npm.png" title="NPM" />
</p>

---

## 🧠 Conocimientos en Sistemas Operativos

$ cat /etc/os-release

> Kali Linux 🐍 Parrot OS 🦜 Ubuntu 🐧 Otros entornos basados en Linux



---

## 📊 GitHub Stats

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=reddix6&theme=green&hide_border=true)
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=reddix6&show_icons=true&theme=tokyonight&hide_border=true)

---

## 🏆 Trofeos

[![trophy](https://github-profile-trophy.vercel.app/?username=reddix6&theme=algolia&no-frame=true)](https://github.com/ryo-ma/github-profile-trophy)

---

## 📈 Actividad

![GitHub Activity Graph](https://github-readme-activity-graph.cyclic.app/graph?username=reddix6&theme=github-compact&hide_border=true)

---

## 📡 Contacto

<p align="left">
  <a href="https://www.instagram.com/e0sd1s._.onion?igsh=MWlqM3ZmZzFvZGQ4YQ==" target="_blank">
    <img src="https://img.icons8.com/fluency/48/000000/instagram-new.png" alt="Instagram" title="Instagram" />
  </a>
</p>

$ ping instagram.com/e0sd1s._.onion
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>reddix6 | Terminal</title>
  <style>
    body {
      background-color: black;
      color: #00ff00;
      font-family: 'Courier New', Courier, monospace;
      padding: 1rem;
    }
    .terminal {
      border: 2px solid #00ff00;
      padding: 1rem;
      border-radius: 10px;
      box-shadow: 0 0 10px #00ff00;
      max-width: 700px;
      margin: auto;
    }
    .line::before {
      content: "$ ";
      color: #00ff00;
    }
    .cursor {
      display: inline-block;
      width: 10px;
      height: 18px;
      background: #00ff00;
      animation: blink 1s steps(1) infinite;
      vertical-align: bottom;
      margin-left: 3px;
    }
    @keyframes blink {
      50% {
        opacity: 0;
      }
    }
  </style>
</head>
<body>
  <div class="terminal" id="terminal">
    <div class="line">Initializing terminal...</div>
  </div>

  <script>
    const terminal = document.getElementById('terminal');
    const commands = [
      "whoami",
      "user: root",
      "cd /etc/ssh",
      "ls -la",
      "nano sshd_config",
      "service ssh restart",
      "nmap -A 192.168.1.1",
      "Establishing reverse shell...",
      "Uploading payload...",
      "Bypassing firewall rules...",
      "Access granted ✅",
      "Running E0SD1S scripts...",
      "They very funny hahahahaha",
      "System ready 🔥"
    ];

    let index = 0;

    function typeLine(text, delay = 60) {
      return new Promise(resolve => {
        let i = 0;
        const line = document.createElement('div');
        line.classList.add('line');
        terminal.appendChild(line);

        const typer = setInterval(() => {
          line.textContent += text[i++];
          if (i === text.length) {
            clearInterval(typer);
            resolve();
          }
        }, delay);
      });
    }

    async function runTerminal() {
      for (const cmd of commands) {
        await typeLine(cmd);
        await new Promise(r => setTimeout(r, 600));
      }
      const cursor = document.createElement('span');
      cursor.className = 'cursor';
      terminal.appendChild(cursor);
    }

    runTerminal();
  </script>
</body>
</html>

> Conectado. Mensaje directo listo para enviar.



---

## 🧠 Fun Fact

> “Los ojos pueden engañar, no confíes en ellos. La verdad está en el código.” - reddix6
