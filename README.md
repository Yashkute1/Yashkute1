<p align="center">
  <img src="assets/header.svg" alt="Yash Kute, founder of Shadowtrace Solution, building DineSlip and PC Part Hunt" width="100%">
</p>

<p align="center">
  <a href="https://shadowtracesolution.com"><img src="https://img.shields.io/badge/Shadowtrace-Solution-0B0E12?style=flat-square&labelColor=5EEAD4" alt="Shadowtrace Solution"></a>
  <a href="https://dineslip.com"><img src="https://img.shields.io/badge/DineSlip-POS-0B0E12?style=flat-square&labelColor=B8321F" alt="DineSlip"></a>
  <a href="https://pcparthunt.com"><img src="https://img.shields.io/badge/PC_Part_Hunt-Prices-0B0E12?style=flat-square&labelColor=22C55E" alt="PC Part Hunt"></a>
  <a href="https://anticheat.shadowtrace.in"><img src="https://img.shields.io/badge/ShadowTrace-AC-0B0E12?style=flat-square&labelColor=A78BFA" alt="ShadowTrace AC"></a>
  <a href="https://linkedin.com/in/yashkute"><img src="https://img.shields.io/badge/LinkedIn-yashkute-0B0E12?style=flat-square&labelColor=38BDF8" alt="LinkedIn"></a>
  <img src="https://komarev.com/ghpvc/?username=Yashkute1&style=flat-square&color=0B0E12&label=views" alt="profile views">
</p>

I run Shadowtrace Solution out of Mumbai. Clients come to us for pentests, DPDP compliance and hosting, and the rest of the time I build our own products. Most of that is backend and server work. The fun part is Rust Samrajya, my game server, where I get to test anti-cheat and DDoS ideas on real players.

### What I'm building

<table>
<tr>
<td width="50%"><a href="https://dineslip.com"><img src="assets/cards/dineslip.svg" alt="DineSlip" width="100%"></a></td>
<td width="50%"><a href="https://pcparthunt.com"><img src="assets/cards/pcparthunt.svg" alt="PC Part Hunt" width="100%"></a></td>
</tr>
<tr>
<td width="50%"><a href="https://anticheat.shadowtrace.in"><img src="assets/cards/shadowtrace-ac.svg" alt="ShadowTrace AC" width="100%"></a></td>
<td width="50%"><a href="https://shadowtracesolution.com"><img src="assets/cards/kavach.svg" alt="Kavach" width="100%"></a></td>
</tr>
<tr>
<td width="50%"><a href="https://leaderboard.shadowtracehosting.com/"><img src="assets/cards/samrajya.svg" alt="Rust Samrajya" width="100%"></a></td>
<td width="50%"><a href="https://github.com/Yashkute1/rust-stats-leaderboard"><img src="assets/cards/leaderboard.svg" alt="Rust Stats Leaderboard" width="100%"></a></td>
</tr>
<tr>
<td width="50%"><a href="https://shadowtracesolution.com"><img src="assets/cards/shadowtrace.svg" alt="Shadowtrace Solution" width="100%"></a></td>
<td width="50%"><a href="https://shadowtracesolution.com"><img src="assets/cards/datacentre.svg" alt="Edge data centre" width="100%"></a></td>
</tr>
</table>

Open source here: the [PC Part Hunt scraper](https://github.com/Yashkute1/pph-scraper-v2), the [leaderboard](https://github.com/Yashkute1/rust-stats-leaderboard), the [skins crawler](https://github.com/Yashkute1/RustLabs-Skins-Crawler) and the [Notion to Discord bot](https://github.com/Yashkute1/rust-samrajya-notion-discord-devlog).

### Security

<p align="center">
  <img src="assets/security.svg" alt="How my systems are protected: Cloudflare, origin firewall, Caddy, API with 2FA and audit log, PostgreSQL with row-level security; Kavach XDP filter, IP challenge, Rust server, ShadowTrace AC" width="100%">
</p>

This is how my own systems are protected. The web side keeps the origin hidden behind Cloudflare and lets the database enforce which restaurant can see which rows, so a bug in the API can't leak another tenant's bills. On the game side, Kavach throws away spoofed packets before the kernel even allocates memory for them, and ShadowTrace AC handles the players who get through legitimately and then cheat.

For client work and practice I use Burp Suite, Metasploit, Wireshark and Hashcat. I harden servers with nftables, ufw and WireGuard.

### Stack

**Languages**<br>
<img src="https://skillicons.dev/icons?i=ts,js,python,go,c,cs,dart,php,bash&theme=dark" alt="TypeScript, JavaScript, Python, Go, C, C#, Dart, PHP, Bash">

**Apps and data**<br>
<img src="https://skillicons.dev/icons?i=nodejs,react,vite,astro,flutter,postgres,mysql,vitest&theme=dark" alt="Node.js, React, Vite, Astro, Flutter, PostgreSQL, MySQL, Vitest">

**Servers and cloud**<br>
<img src="https://skillicons.dev/icons?i=linux,ubuntu,aws,gcp,cloudflare,githubactions,git&theme=dark" alt="Linux, Ubuntu, AWS, Google Cloud, Cloudflare, GitHub Actions, Git">

<sub>Also: Fastify, Kysely, Playwright, Caddy, eBPF/XDP, nftables, WireGuard, Carbon and Oxide plugins, ESC/POS receipt printers.</sub>

### Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Yashkute1/Yashkute1/output/snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Yashkute1/Yashkute1/output/snake.svg">
  <img alt="contribution graph being eaten by a snake" src="https://raw.githubusercontent.com/Yashkute1/Yashkute1/output/snake.svg">
</picture>
