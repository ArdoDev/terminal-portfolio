<div align="center">

## Live Demo

<a href="https://ardodev.github.io/terminal-portfolio/">
  <img src="https://img.shields.io/badge/Live%20Demo-Open%20Website-00ff88?style=for-the-badge&logo=googlechrome&logoColor=white">
</a>

</div>

# Terminal Style Portfolio Template

A single-file (HTML/CSS/JS) terminal-themed portfolio page for Roblox / Web developers and GFX designers.

## Features

- Terminal-style hero section (`whoami` / `cat roles.txt` style)
- Discord and Roblox profile cards (static, does not fetch live presence)
- Project list (displayed as a file explorer interface)
- Commission / service pricing cards
- Contact section
- Fully responsive, no external frameworks required

## Usage

1. Download the `index.html` file.
2. Update it with your own information:
   - Replace the values of `DISCORD_USERNAME`, `DISCORD_USER_ID`, `ROBLOX_USERNAME`, and `ROBLOX_USER_ID` variables inside the `<script>` section with your own information.
   - You can manually update the `href="#"` values in the elements with `id="discordCard"` and `id="robloxCard"` if needed (the JS automatically fills them when the page loads).
   - Replace the example project/service pricing information in the "Projects I've Worked On" and "Services" sections with your own details.
3. Upload the file to a web server or deploy it using a static hosting service such as GitHub Pages, Netlify, or Vercel.

## Notes

- Discord does not provide an official/public live status (presence) API for personal user profiles. This template intentionally uses a **static** card. If you want live status information (for example, using Lanyard), you need to add your own integration.
- Roblox's public API cannot be directly accessed from the browser due to CORS restrictions. For real-time data, you need to create a small backend/proxy service. This template therefore uses static profile links.

## License

You are free to use, modify, and distribute this template however you like.
