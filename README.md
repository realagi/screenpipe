# TODO: Add [Pipe](https://github.com/realagi/screenpipe/tree/main/pipes) with following React interface: 

 - vertical folding panels with "-" / "+" markings and grey headers on the black background
   - Screen(s)
      - Screen: Shows streaming of the screen or latest screenshot
         - OCR Numbered Screen Element Frame Overlay: Can be in focused, selected, normal state, looks like a frame of green, white, grey with number in Ariel black in the corner
         - "-" / "+" Panel for Accessibitity UI Elements Breakdown
         - "-" / "+" Panel for List of Text Fields For LLM Generation
   - Chats
      - Messages of Computer's Voice Chat (As Heard On Mic)
         - monospaced dark rainbow colorized of ISO datetime
         - guessed name of talker in monospaced font with designated to this talker color
         - heard message in italic Times New Roman
      - Voice Chat Text Input
         - button "Say Aloud" with icon only
      - Chatbot Text Input
         - Response popup
            - Go to Chat session button (opens history of previous conversations and full chat interface, tbd, now just opens history)
   - Popups
      - Popup Prompt list horizontal container
         - LRU horizontal stripe of generated slugs of the prompts  
         - Search field
            -  Search button
      - Vertical list of Popup Windows, sorted by screen number they are on / last recently opened
         -  Popup Window (on pressing on it except of popup window must blink)
            - gothic, grey id of the physical screen popup window is currently located
            - white, monospace: Popup Window's Promp slug
            - grey, times new roman italic in parenthesis: Popup Window's id
            - close button
         - "-" / "+" Panel for Popup Prompts editor
          


# TODO: animate interface for mock heard talkers using llm

<img referrerpolicy="no-referrer-when-downgrade" src="https://static.scarf.sh/a.png?x-pxid=c3628864-a0cb-47a1-a822-2f936cff50b2" />
<p align="center">
   <a href="README.md">English</a> | <a href="README-zh_CN.md">简体中文</a> | <a href="README-ja.md">日本語</a>
</p>

<p align="center">
   <a href ="https://screenpi.pe">
      <img src="https://github.com/user-attachments/assets/d3b1de26-c3c0-4c84-b9c4-b03213b97a30" alt="logo" width="200">
   </a>
</p>

<p align="center">
   <a href="https://trendshift.io/repositories/11785" target="_blank"><img src="https://trendshift.io/api/badge/repositories/11785" alt="mediar-ai%2Fscreenpipe | Trendshift" style="width: 250px; height: 55px;" width="250" height="55"/></a>
</p>


<!-- ScreenPipe Title and Subtitle -->
<p align="center" style="font-family: 'Press Start 2P', monospace;">
   <h1 align="center">[ screenpipe ]</h1>
   <p align="center">library & platform to build, distribute, monetize ai apps that have the full context (like rewind, granola, etc.)</p>
   <p align="center">open source | 100% local | dev friendly | 24/7 screen, mic, keyboard recording and control</p>
</p>

<!-- Slogan -->
<p align="center" style="font-family: monospace;">
   <code>[ recording reality, one pixel at a time ]</code>
</p>

<p align="center">
    <a href="https://screenpi.pe" target="_blank">
        <img src="https://img.shields.io/badge/Download%20The-Desktop%20App-blue?style=for-the-badge" alt="Download the Desktop App">
    </a>
</p>

<p align="center">
    <a href="https://www.youtube.com/@mediar_ai" target="_blank">
       <img alt="YouTube Channel Subscribers" src="https://img.shields.io/youtube/channel/subscribers/UCwjkpAsb70_mENKvy7hT5bw">
    </a>
</p>


<p align="center">
    <a href="https://discord.gg/dU9EBuw7Uq">
        <img src="https://img.shields.io/discord/823813159592001537?color=5865F2&logo=discord&logoColor=white&style=flat-square" alt="Join us on Discord">
    </a>
   <a href="https://twitter.com/screen_pipe"><img alt="X account" src="https://img.shields.io/twitter/url/https/twitter.com/diffuserslib.svg?style=social&label=Follow%20%40screen_pipe"></a>
   <a href="https://console.algora.io/org/mediar-ai/bounties?status=completed">
       <img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fconsole.algora.io%2Fapi%2Fshields%2Fmediar-ai%2Fbounties%3Fstatus%3Dcompleted" alt="Rewarded Bounties">
   </a>
   <a href="https://console.algora.io/org/mediar-ai/bounties?status=open">
       <img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fconsole.algora.io%2Fapi%2Fshields%2Fmediar-ai%2Fbounties%3Fstatus%3Dopen" alt="Open Bounties">
   </a>
</p>

<p align="center">
   
<img width="1312" alt="Screenshot 2024-12-11 at 1 39 09 PM" src="https://github.com/user-attachments/assets/26b2986d-01aa-43de-acf0-375a72752894" />
<img width="1312" alt="Screenshot 2024-12-16 at 2 39 32 PM" src="https://github.com/user-attachments/assets/0da6e948-4fa2-48ab-b18c-d8fbd1246261" />

<img width="1142" alt="Screenshot 2024-12-16 at 12 39 18 PM" src="https://github.com/user-attachments/assets/5b6f7015-b522-4894-a0d7-d91d648895f5" />
<img width="1312" alt="Screenshot 2024-12-11 at 1 39 09 PM" src="https://github.com/user-attachments/assets/08f1d8bd-803e-4cc5-8b8f-ad33bfebfd7e" />



---

*news* 🔥
- [2025/01] we're partnering with Different AI to bring you [financial automations based on your screen](https://github.com/different-ai/hypr-v0) and [drop-in replacement for granola within obsidian](https://github.com/different-ai/file-organizer-2000)
- [2024/12] pipe store stripe integration: devs build cool shit - few lines of JS and make passive income (available Reddit agent, LinkedIn agent, Timeline ...)
- [2024/11] [screenpipe is number 1 github trending repo (again)](https://x.com/louis030195/status/1859628763425931479)
- [2024/10] screenpipe has been backed by [Founders, Inc](https://f.inc/)
- [2024/09] [screenpipe is number 1 github trending repo & on hackernews!](https://x.com/louis030195/status/1840859691754344483)
- [2024/08] anyone can now [create, share, install pipes](https://docs.screenpi.pe/docs/plugins) (plugins) from the app interface based on a github repo/dir
- [2024/08] we're running bounties! contribute to screenpipe & make money, [check issues](https://github.com/mediar-ai/screenpipe/issues)
- [2024/08] we released Apple & Windows Native OCR.
- [2024/07] 🎁 screenpipe won Friends (the AI necklace) hackathon at AGI House (integrations soon)
- [2024/07] **we just launched the desktop app! [Download now!](https://screenpi.pe)**

---

# how it works?

- we record everything 24/7, 100% locally, uses 10% CPU, 4 GB ram, 15 gb/m
- we index it into an api
- dev build ai apps w user's full context, desktop native, nextjs, publish, monetize

<img src="./content/diagram2.png" width="800" />

<img src="https://github.com/user-attachments/assets/da5b8583-550f-4a1f-b211-058e7869bc91" width="400" />



# why?

1. context is the dark matter of intelligence
2. every second you are not recording is a missing context for AGI

## get started

macos, linux:

```bash
curl -fsSL get.screenpi.pe/cli | sh
```

or on windows

```bash
iwr get.screenpi.pe/cli.ps1 | iex
```

then

```bash
screenpipe
```

make sure to allow permissions on macos (screen, mic)

- [get the desktop app](https://screenpi.pe/)
- [docs & build from source](https://docs.screenpi.pe/docs/getting-started)

## create plugins

```bash
bunx @screenpipe/dev@latest create
```

screenpipe has a plugin system called "pipe" which lets you create desktop app in nextjs in a sandboxed environment within our Rust code, [read more](https://docs.screenpi.pe/docs/plugins)

you can then publish these to our store and make money:

```bash
bunx @screenpipe/dev@latest register --name foo [--paid --price 50] # subscription
bun run build
bunx @screenpipe/dev@latest publish --name foo
```

## community 

- [template to build screenpipe-powered desktop native app using Tauri](https://github.com/LorenzoBloedow/screenpipe-tauri-template-dev)
- [template to build screenpipe-powered desktop native app using Electron](https://github.com/neo773/screenpipe-electron)

## star history

![Star History Nov 24 2024](https://github.com/user-attachments/assets/c7e4de14-0771-4bbb-9a4c-7f2102a1a6cd)


## contributing

contributions are welcome! if you'd like to contribute, please read [CONTRIBUTING.md](CONTRIBUTING.md).

   <a href="https://console.algora.io/org/mediar-ai/bounties?status=completed">
       <img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fconsole.algora.io%2Fapi%2Fshields%2Fmediar-ai%2Fbounties%3Fstatus%3Dcompleted" alt="Rewarded Bounties">
   </a>
   <a href="https://console.algora.io/org/mediar-ai/bounties?status=open">
       <img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fconsole.algora.io%2Fapi%2Fshields%2Fmediar-ai%2Fbounties%3Fstatus%3Dopen" alt="Open Bounties">
   </a>
