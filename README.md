
<img src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif" alt="MasterHead" height="400" width="100%">

<h1 align="center">Animated Sweet Banner</h1>

<div align="center">
    <a href="https://sweetbanner.github.io" target="_blank"><img src="https://img.shields.io/badge/🪐_Try_Now-sweetbanner.github.io-f59e0b?style=for-the-badge" alt="Live Demo"/></a>
</div>
<br/>
<div align="center">
    <a href="https://github.com/SystemVll/readme-animated-sweetbanner/stargazers"><img src="https://img.shields.io/github/stars/SystemVll/readme-animated-sweetbanner" alt="Stars Badge"/></a>
    <a href="https://github.com/SystemVll/readme-animated-sweetbanner/network/members"><img src="https://img.shields.io/github/forks/SystemVll/readme-animated-sweetbanner" alt="Forks Badge"/></a>
    <a href="https://github.com/SystemVll/readme-animated-sweetbanner/pulls"><img src="https://img.shields.io/github/issues-pr/SystemVll/readme-animated-sweetbanner" alt="Pull Requests Badge"/></a>
    <a href="https://github.com/SystemVll/readme-animated-sweetbanner/issues"><img src="https://img.shields.io/github/issues/SystemVll/readme-animated-sweetbanner" alt="Issues Badge"/></a>
    <a href="https://github.com/SystemVll/readme-animated-sweetbanner/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/SystemVll/readme-animated-sweetbanner?color=2b9348"></a>
    <a href="https://github.com/SystemVll/readme-animated-sweetbanner/blob/master/LICENSE"><img src="https://img.shields.io/github/license/SystemVll/readme-animated-sweetbanner?color=2b9348" alt="License Badge"/></a>
</div>
<br/>
<div  align="center">
    <img width="96" height="96" src="https://github.com/user-attachments/assets/e3429152-086e-427c-a920-d89b8b16ccf4" />
</div>

<p align="center">
    A web-based editor for creating animated SVG banners for GitHub profiles. Build custom sweet banners with meteors, glowing avatars, and animated effects.
</p>

## Example

![Sweet Banner Example](https://github.com/user-attachments/assets/484c1d55-7321-4c2b-9d99-0648f5c7e92f)

## Features

- **Animated Meteors** - Add flying icon meteors with customizable trails, colors, and timing
- **Avatar Integration** - Display your GitHub avatar with animated glow effects
- **Live Preview** - See changes in real-time as you edit
- **SVG Export** - Download or copy the generated SVG code
- **Customizable Effects** - Adjust waves, particles, borders, and gradients

## Tech Stack

- React 19 + TypeScript
- Vite
- Tailwind CSS
- shadcn/ui components
- Lucide icons

## Getting Started

```bash
# Install dependencies
bun install

# Start development server
bun run dev

# Build for production
bun run build
```

## Usage

1. Configure banner dimensions and background color
2. Set your avatar URL and size
3. Add meteors with icons from Iconify
4. Customize colors, timing, and animation properties
5. Copy the SVG code or download the file
6. Add just the banner line at the end of the copied SVG code to the beginning of your Repos Readme.md, you can also **just drag and drop the svg file**
    ```markdown
    ![banner(1)](https://github.com/user-attachments/assets/...)
    ```

## Icon Libraries

- **[Iconify](https://iconify.design/)** - Icons aggregator. +50k icons

## Configuration Options

| Setting    | Description                               |
| ---------- | ----------------------------------------- |
| Border     | Border size, angle, and color             |
| Background | Solid color background                    |
| Avatar     | GitHub avatar URL and size                |
| Meteors    | Icon, trail color, angle, duration, delay |
| Particles  | Floating particle count and color         |
| Waves      | Animated wave gradient colors             |
| Glow       | Avatar glow gradient colors               |
| Border     | Optional border with radius and size      |

## License

MIT
