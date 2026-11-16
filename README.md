<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7F00FF,50:E100FF,100:00D4FF&height=230&section=header&text=Duy%20Nguyen&fontSize=72&fontColor=ffffff&fontAlignY=38&desc=Game%20Dev%20%E2%80%A2%20Reverse%20Engineering%20%E2%80%A2%20Emulators&descSize=20&descAlignY=60&animation=fadeIn" width="100%" alt="Duy Nguyen" />

<a href="https://github.com/duykhongphai">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=E100FF&center=true&vCenter=true&width=640&lines=Building+JVMs+from+scratch;J2ME+games+on+iPhone+and+in+the+browser;Game+servers+%E2%80%A2+Reverse+engineering+%E2%80%A2+AI+tools;Low-level+C+%2F+Java+%2F+C%23+%2F+TypeScript" alt="Typing SVG" />
</a>

<p>
  <a href="https://www.youtube.com/@DuyKhongPhai"><img src="https://img.shields.io/badge/YouTube-DuyKhongPhai-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" /></a>
  <a href="https://github.com/duykhongphai"><img src="https://img.shields.io/badge/GitHub-duykhongphai-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <img src="https://komarev.com/ghpvc/?username=duykhongphai&color=blueviolet&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile views" />
</p>

</div>

## About me

```java
public class DuyNguyen {
    String role      = "Software Developer";
    String[] loves   = { "game servers", "reverse engineering", "emulators", "deep learning OCR" };
    String[] builds  = { "a JVM in C for iOS", "a JVM in TypeScript for the web", "anti-bot captchas" };
    String  motto    = "Clean, fast, low-level code.";
}
```

- Game server development with high-concurrency tuning
- Retro mobile games: **J2ME emulators** for iPhone and the web, J2ME → LibGDX conversions
- Reverse engineering and binary analysis with IDA Pro
- Deep learning OCR and automation tools

## Tech stack

<div align="center">

<img src="https://skillicons.dev/icons?i=java,c,cpp,cs,py,ts,js&theme=dark" alt="Languages" /><br/>
<img src="https://skillicons.dev/icons?i=unity,androidstudio,apple,pytorch,tensorflow,docker,mysql,nodejs,vite,git,linux,vscode&theme=dark" alt="Tools" />

</div>

## Spotlight

<table>
<tr>
<td width="50%" valign="top">

### [J2ME4iOS](https://github.com/duykhongphai/J2ME4iOS)
**Play J2ME games on iPhone.** A Java VM written from scratch in portable C (no JIT), with the
CLDC/MIDP library reimplemented in Java.

- **3D:** M3G (JSR-184) + Mascot Capsule v3, software rasterizer
- Built-in General MIDI synth, tone sequences, Nokia ringtones
- Several games at once, 5 save slots, SOCKS5 / HTTP proxy per slot
- MFi / Xbox / PlayStation controllers, sliding on-screen keypad
- Nokia, Samsung, Siemens, Motorola, LG APIs

<a href="https://github.com/duykhongphai/J2ME4iOS/releases/latest"><img src="https://img.shields.io/badge/Download-IPA-E100FF?style=for-the-badge&logo=apple&logoColor=white" alt="Download IPA" /></a>
<a href="https://github.com/duykhongphai/J2ME4iOS"><img src="https://img.shields.io/badge/Source-C%20%2B%20Java-7F00FF?style=for-the-badge&logo=github&logoColor=white" alt="Source" /></a>

</td>
<td width="50%" valign="top">

### [J2ME4W](https://github.com/duykhongphai/J2ME4W)
**Play J2ME games in the browser.** A JVM written in TypeScript plus a MIDP implementation;
nothing is uploaded, the JAR stays in your browser.

- Game library with icons, per-game settings
- Several games in tabs, grid view, synced input
- Keypad editor, keyboard and gamepad remapping
- General MIDI synth, WebAudio sound
- Network bridge for online games

<a href="https://duykhongphai.github.io/J2ME4W/"><img src="https://img.shields.io/badge/Live-Demo-00D4FF?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Live demo" /></a>
<a href="https://github.com/duykhongphai/J2ME4W"><img src="https://img.shields.io/badge/Source-TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="Source" /></a>

</td>
</tr>
</table>

## More projects

<table>
<tr>
<td width="50%" valign="top">

### [DataNro](https://github.com/duykhongphai/DataNro)
Items, monsters, NPCs, skills and maps of **Ngọc Rồng Online**, pulled straight from the game
servers and updated automatically every day. Static JSON + sprite API and a lookup site.

<a href="https://duykhongphai.github.io/DataNro/"><img src="https://img.shields.io/badge/Lookup-Site-00D4FF?style=for-the-badge&logo=githubpages&logoColor=white" alt="Lookup site" /></a>
<img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=dotnet&logoColor=white" alt="C#" />

</td>
<td width="50%" valign="top">

### [LoudLift](https://github.com/duykhongphai/LoudLift)
Make any video louder and evenly loud, without re-encoding the picture: the video stream is copied
bit for bit, only the audio is processed. Self-hosted web tool on FFmpeg, GPU + CPU.

<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
<img src="https://img.shields.io/badge/FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white" alt="FFmpeg" />

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [CaptchaGenerator](https://github.com/duykhongphai/CaptchaGenerator)
Randomized captcha images (backgrounds, glyphs, effects) that keep bots and auto tools out of
Ngọc Rồng Online servers, tuned for speed.

<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
<img src="https://img.shields.io/github/stars/duykhongphai/CaptchaGenerator?style=for-the-badge&color=E100FF" alt="Stars" />

</td>
<td width="50%" valign="top">

### [NinjaSchoolCaptcha](https://github.com/duykhongphai/NinjaSchoolCaptcha)
Lightweight captcha for Ninja School game servers: players answer visual arrow challenges,
bots do not.

<img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
<img src="https://img.shields.io/github/stars/duykhongphai/NinjaSchoolCaptcha?style=for-the-badge&color=E100FF" alt="Stars" />

</td>
</tr>
</table>

## GitHub stats

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/duykhongphai/duykhongphai/main/profile-summary-card-output/github_dark/0-profile-details.svg">
  <img src="https://raw.githubusercontent.com/duykhongphai/duykhongphai/main/profile-summary-card-output/github/0-profile-details.svg" width="100%" alt="Profile details" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/duykhongphai/duykhongphai/main/profile-summary-card-output/github_dark/3-stats.svg">
  <img src="https://raw.githubusercontent.com/duykhongphai/duykhongphai/main/profile-summary-card-output/github/3-stats.svg" width="49%" alt="Stats" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/duykhongphai/duykhongphai/main/profile-summary-card-output/github_dark/1-repos-per-language.svg">
  <img src="https://raw.githubusercontent.com/duykhongphai/duykhongphai/main/profile-summary-card-output/github/1-repos-per-language.svg" width="49%" alt="Repos per language" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/duykhongphai/duykhongphai/main/profile-summary-card-output/github_dark/2-most-commit-language.svg">
  <img src="https://raw.githubusercontent.com/duykhongphai/duykhongphai/main/profile-summary-card-output/github/2-most-commit-language.svg" width="49%" alt="Most commit language" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/duykhongphai/duykhongphai/main/profile-summary-card-output/github_dark/4-productive-time.svg">
  <img src="https://raw.githubusercontent.com/duykhongphai/duykhongphai/main/profile-summary-card-output/github/4-productive-time.svg" width="49%" alt="Productive time" />
</picture>

<a href="https://git.io/streak-stats">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/duykhongphai/duykhongphai/main/profile/streak-dark.svg">
  <img src="https://raw.githubusercontent.com/duykhongphai/duykhongphai/main/profile/streak.svg" alt="GitHub streak" />
</picture>
</a>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=duykhongphai&hide_border=true&area=true&custom_title=Contribution%20Graph&bg_color=0d1117&color=E100FF&title_color=E100FF&line=E100FF&point=00D4FF&area_color=7F00FF">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=duykhongphai&hide_border=true&area=true&custom_title=Contribution%20Graph&bg_color=ffffff&color=7F00FF&title_color=7F00FF&line=E100FF&point=00D4FF&area_color=E100FF" width="100%" alt="Contribution graph" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/duykhongphai/duykhongphai/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/duykhongphai/duykhongphai/output/github-contribution-grid-snake.svg">
  <img alt="Snake eating my contributions" src="https://raw.githubusercontent.com/duykhongphai/duykhongphai/output/github-contribution-grid-snake.svg">
</picture>

</div>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00D4FF,50:E100FF,100:7F00FF&height=120&section=footer" width="100%" alt="" />

</div>
