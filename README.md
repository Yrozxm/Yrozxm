<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1000&center=true&vCenter=true&multiline=true&width=600&height=80&lines=Olá,+eu+sou+Mateus+Jesus+👋;Desenvolvedor+Back-End+em+formação;Aprendendo+React,+Java,+PHP+e+mais..." alt="Typing SVG" />
</div>

---
<div align="center" style="margin-top: 10px; margin-bottom: 20px;">
  <img src="https://komarev.com/ghpvc/?username=mateusjesus&style=for-the-badge&color=a855f7" alt="Visualizações de perfil" />
</div>

<h2> ☕ Cafés Tomados </h2>

<div align="center">
  <!-- Badge estilizado -->
  <img
    src="https://img.shields.io/badge/Caf%C3%A9s%20Tomados-106-%236f4e37?style=flat-square&logo=coffeescript&logoColor=white"
    alt="Cafés Tomados"
  />

  <!-- Texto de acompanhamento -->
  <p style="margin-top: 8px;">
    Já são <strong>106</strong> cafés ☕
  </p>
</div>

---

## 🚀 Sobre mim

<div align="center">

🎓 Estudante de desenvolvimento de software  
🛠️ Foco em Back-End, com conhecimentos em Front-End  
🌱 Atualmente aprendendo React, aprimorando Java, PHP e JavaScript  

</div>

---

## 🧰 Tecnologias que uso

<div align="center">
  <img src="https://skillicons.dev/icons?i=html,css,php,java,javascript,react,git,vscode&theme=light" alt="Tecnologias" />
</div>

---

## 📈 Minhas Estatísticas

<div align="center">
  <img height="180px" src="https://github-readme-stats.vercel.app/api?username=mateusjesus&show_icons=true&theme=radical&hide_border=true&count_private=true" alt="GitHub stats" />
  <img height="180px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mateusjesus&layout=compact&theme=radical&hide_border=true&langs_count=6" alt="Top linguagens" />
</div>

---

## 📫 Onde me encontrar

<div align="center">
  <a href="https://discord.com/users/pawsbny_" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/Discord-pawsbny_-%23a855f7?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" />
  </a>
</div>

---

<p align="center" style="margin-top: 20px;">
  Feito com 💜 por <strong>Mateus Jesus</strong>
</p>

---
Add-Type -AssemblyName PresentationFramework

$window = New-Object System.Windows.Window
$window.WindowStyle = 'None'
$window.WindowState = 'Maximized'
$window.Topmost = $true
$window.Background = 'Blue'
$window.Cursor = 'None'

$text = @"
A problem has been detected and Windows has been shut down to prevent damage
to your computer.

If this is the first time you've seen this stop error screen,
restart your computer. If this screen appears again, follow
these steps:

Check to make sure any new hardware or software is properly installed.
If this is a new installation, ask your hardware or software manufacturer
for any Windows updates you might need.

Technical information:

*** STOP: 0x0000007B (0xFFFFFFFF, 0x00000000, 0x00000000, 0x00000000)

Press any key to exit...
"@

$textBlock = New-Object System.Windows.Controls.TextBlock
$textBlock.Text = $text
$textBlock.Foreground = 'White'
$textBlock.FontFamily = 'Consolas'
$textBlock.FontSize = 24
$textBlock.TextWrapping = 'Wrap'
$textBlock.Margin = '40'

$window.Content = $textBlock

$window.Add_KeyDown({ $window.Close() })

$window.ShowDialog() | Out-Null

