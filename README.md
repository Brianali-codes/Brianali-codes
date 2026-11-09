# Brian Ali [View Portfolio](https://brian-ali.netlify.app/)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Segoe+UI&size=15&pause=1000&color=F7F7F7&repeat=false&width=426&height=40&lines=Hello+There+I+am+Brian.)](https://git.io/typing-svg)

Information Technology undergraduate and mobile software engineer specializing in cross-platform Android application engineering, serverless system architectures, and client-side performance optimization. Focused on delivering privacy-first, zero-telemetry software with modern frontend design systems.




## Languages, Tools and Technologies

<p align="start">
  <a href="https://go-skill-icons.vercel.app/">
    <img src="https://go-skill-icons.vercel.app/api/icons?i=react,css,html,javascript,nodejs,typescript,tailwindcss,materialui,git,vite,python,nextjs,reactbootstrap,netlify,mysql,supabase,framer,tauri,arch,mongodb,canva,postman,vscode,webpack,markdown,styledcomponents,devto,stackoverflow,notion,jest" alt="Tech Stack Icons" />
  </a>
</p>

### Primary Skill Matrix
* **Languages & Frameworks:** TypeScript, JavaScript (ES6+), Python, React Native, Expo, React, Next.js, Node.js, HTML5, CSS3/Sass.
* **UI/UX & Styling Systems:** Tailwind CSS, NativeWind, Material UI (MUI), Styled Components, React Native Paper, Framer Motion.
* **Architecture & State Management:** Redux Toolkit, Context API, Async Storage, RESTful API Integration, Serverless Client Architecture.
* **Tools, Build Systems & Platforms:** Git, Webpack, Vite, Postman, Jest, Linux (Arch), Supabase, Netlify, Vercel, Expo CLI.

---

## Maintained Applications

### FRAPP (Freebie Radar App)

<p align="left">
  <img width="48" height="48" alt="FRAPP Logo" src="https://github.com/user-attachments/assets/5e1b953c-1093-43d2-b5f4-018a08ff1336" />
  <a href="https://rankcert.com/product/frapp" target="_blank" rel="nofollow noopener">
    <img src="https://rankcert.com/badge/frapp?style=card&theme=light" alt="Frapp - Certified on RankCert"  height="48" />
  </a>
  <a href="https://rookieenough.github.io/Orion-Data/redirect.html?id=frapp&icon=https%3A%2F%2Fraw.githubusercontent.com%2FBrianali-codes%2FFrapp%2Frefs%2Fheads%2Fmain%2Fassets%2Fimages%2FFRAPP_ICON1.png" target="_blank"  rel="nofollow noopener">
    <img src="https://raw.githubusercontent.com/RookieEnough/Orion-Store/refs/heads/main/assets/orion-badge.png" alt="Get it on Orion Store"  height="48"/>
  </a>
  <a href="https://ko-fi.com/brianalicodes" target="_blank">
    <img  height="48" alt="Support on Ko-fi" src="https://github.com/user-attachments/assets/5eadacfb-c20e-48d9-b592-a306c96e5833" />
  </a>
</p>

<p align="left">
  <a href="https://github.com/brianali-codes/frapp"><img src="https://img.shields.io/github/downloads/brianali-codes/frapp/total.svg" alt="Github All Releases" /></a>
  <a href="https://choosealicense.com/licenses/gpl-3.0/"><img src="https://img.shields.io/badge/License-GPL--3.0-blue.svg" alt="GPL-3.0 License" /></a>
  <img src="https://img.shields.io/badge/Latest_version-v1.1.6-green" alt="Latest Version v1.1.6"/>
</p>

#### Architecture & Technical Overview
FRAPP is a cross-platform mobile software solution engineered using React Native and Expo CLI. The core application functions as a decentralized, privacy-focused aggregator that tracks limited-time video game giveaways and active retail discounts across major digital distribution platforms, including Steam, Epic Games Store, GOG, and itch.io. 

The client architecture interfaces directly with the GamerPower and CheapShark RESTful APIs to process real-time payload updates without reliant intermediary application servers.

#### Engineering Highlights
* **Zero-Telemetry Serverless Architecture:** Eliminates centralized user tracking, external telemetry, and ad frameworks. All user states, preferences, and saved deals are persisted locally on-device.
* **Asynchronous Background Processing:** Utilizes native background notification services to check for active promotion updates and issue local system alerts before limited-time giveaways expire.
* **Multi-Parametric Filter Engine:** Features dynamic sorting mechanisms by storefront, operational platform (Windows, macOS, Linux, Android, iOS), claim status, and percentage price reductions.
* **Localization System:** Built-in internationalization infrastructure supporting runtime switching across 8 languages.

Get it <a href="https://frappgiveaways.vercel.app" target="_blank">here</a>



---

### Shiori

<p align="left">
  <img width="48" height="48" alt="Shiori Logo" src="https://github.com/user-attachments/assets/6d1d5d51-b47f-40c1-9940-7cf6fb8392d1" />
  <a href="https://rookieenough.github.io/Orion-Data/redirect.html?id=shiori&icon=https%3A%2F%2Fraw.githubusercontent.com%2FBrianali-codes%2FShiori%2Fmaster%2Fassets%2Fimages%2Fshiori-icon.png" target="_blank" rel="nofollow noopener">
    <img src="https://raw.githubusercontent.com/RookieEnough/Orion-Store/refs/heads/main/assets/orion-badge.png" alt="Get it on Orion Store"  height="48" />
  </a>
  <a href="https://ko-fi.com/brianalicodes" target="_blank">
    <img height="48" alt="Support on Ko-fi" src="https://github.com/user-attachments/assets/5eadacfb-c20e-48d9-b592-a306c96e5833" />
  </a>
</p>

<p align="left">
  <a href="https://github.com/brianali-codes/shiori"><img src="https://img.shields.io/github/downloads/brianali-codes/shiori/total.svg" alt="Github All Releases" /></a>
  <a href="https://choosealicense.com/licenses/mit/"><img src="https://img.shields.io/badge/License-MIT-green.svg" alt="MIT License" /></a>
  <img src="https://img.shields.io/badge/Latest_version-v1.1.6-green" alt="Latest Version v1.1.6"/>
</p>

#### Architecture & Technical Overview
Shiori is a Material Design wallpaper discovery application constructed with React Native, Redux Toolkit, and React Native Paper. The software communicates directly with the Wallhaven API to query, filter, render, and manage high-resolution artwork and photography.

Designed around modern UI guidelines, Shiori features Google Pixel-inspired vector iconography, smooth transition pipelines, and strict memory management to ensure stable rendering across diverse display densities.

#### Engineering Highlights
* **High-Performance Image Caching:** Implements hardware-accelerated image pipeline rendering and aggressive local caching strategies via Async Storage to maximize scroll performance and reduce network overhead.
* **Advanced API Search Querying:** Enables multi-criteria search configurations based on target resolutions, aspect ratios, color hex palettes, purity levels, and relevance sorting algorithms.
* **Native Media Integration:** Includes an asynchronous asset management layer for direct local downloads and one-tap native wallpaper application to Android lock and home screens.
* **Reactive State Management:** Driven by Redux Toolkit for unified handling of favorites, local storage sync, theme contexts (Light/Dark/System), and cached search parameters.

<p>A modern React Native mobile application for discovering and using beautiful wallpapers powered by the Wallhaven API. </p>
  
Get it <a href="https://shiori.framer.website" target="_blank">here</a>

