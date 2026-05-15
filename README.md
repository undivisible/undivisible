# hi, i'm max &nbsp;_[undivisible.dev](https://undivisible.dev/)_

i make things for people.  
part-time language learner, part-time philosopher, full-time schemer.  
i build systems, runtimes, interfaces, developer tools, and small pieces of software that feel inevitable.

***

## [crepuscularity](https://crepuscularity.undivisible.dev) · [aurorality](https://github.com/semitechnological/aurorality)

> a framework for building cross-platform applications from a single web-based codebase — solely by writing react + tailwindcss and a js/ts or rust backend.

crepuscularity builds for: desktop apps (gpui), swiftui & jetpack compose mobile, tuis on ratatui, websites, and browser extensions. [aurorality](https://github.com/semitechnological/aurorality) turns web frontends into native swiftui for macos and ios, accepting swift, js/ts, or rust as your backend. with crepuscularity lite and aurorality-js, you can drop into existing sites to connect native frontends to js backends.

### subprojects

- **[inauguration](https://github.com/semitechnological/inauguration)** - an experimental multi-frontend compiler/runtime platform targeting Core IR, SIL analysis, hot reload, and ultrafast incremental workflows.
- **[equilibrium](https://github.com/semitechnological/equilibrium)** — load c-compatible code into rust with one call. auto-detects sources, compiles, exposes as rust modules. `load()` is the primary path. for rust → swift, see [eqswift](https://github.com/semitechnological/eqswift).
- **[wax](https://github.com/semitechnological/wax)** — fast homebrew-compatible package manager in rust. uses homebrew's ecosystem (formulae, bottles, casks) without the ruby/git overhead — compiled, async, parallel installs, lockfiles, and experimental winget/scoop/nix-like support.

***

## [atechnology company](https://atechnology.company/)

## [soliloquy](https://github.com/atechnology-company/soliloquy)

an experimental operating system model for the web — immutable, browser-native, built on a modified alpine base.

### [rv8](https://github.com/atechnology-company/rv8)
it uses rv8, a custom browser engine built with servo and v8.

### other

- **experiences** — a project exploring a more accessible spatial web, built on unity wasm.
- **atmosphere** — a native sync and ecosystem layer for every device, with local-first and homelab support.

***

## [semitechnological](https://github.com/semitechnological)

- **[tile (wip)](https://github.com/semitechnological/tile)** — mosaic-style tiling window manager + canvas + multiplexer for macos.
- **otto (wip)** — ai-powered ottocomplete anywhere on your mac.
- **rover (wip)** — utilities and plugin system for mac, based on raycast + ghostty.

***



## miniapps

- **[standpoint](https://standpoint.undivisible.dev)** - the ultimate opinion based platform for sharing tierlists, voting on polls, and playing spectrum - a party game to guess on a spectrum based on a prompt.
- **[unthinkmail](https://unthinkmail.undivisible.dev/)** — mcp for imap-supported email.
- **[drift](https://github.com/undivisible/drift-wallpaper)** — macos drift screensaver as a live wallpaper on linux, macos, windows. spotify and apple music now playing support.
- **[vro](https://github.com/undivisible/vro)** - minimal micro inspired text editor written in v.
- **[notes](https://notes.undivisible.dev/)** — minimal note taker with google font and notion-style markdown editing.
- **[bublik](https://bublik.undivisible.dev/)** — canvas tool for generating custom frequency soundscapes.
- **[alphabets](https://alphabets.undivisible.dev)** — learn any unicode-supported alphabet through cards, quizzes, and completion tables.
- **[unthinkclaw](https://github.com/undivisible/unthinkclaw)** - openclaw but <1/100 of the size, with a better ux (subjectively), with speed and with the ability to deploy agent swarms.
- **[poke around](https://github.com/undivisible/poke-around)** — lets [poke](https://poke.com) interact with your computer across major oses.
- **[anywhere](https://github.com/undivisible/anywhere)** — browser extension that turns ai chat responses into interactive interfaces. renders widgets, panels, forms, charts inside chat via custom response tags.
- **[unelaborate](https://github.com/undivisible/unelaborate)** — minecraft client in native swiftui with modrinth modpack, shader, and resource pack loading.

## libraries and other stuff
- **[stalwart lite](https://github.com/tschk/stalwart-lite)** — stalwart fork that runs in-process as a rust crate. imap, smtp, management api — no web admin, no overhead. built for embedding and local-first setups.
- **[crosspost-rs](https://github.com/tschk/crosspost-rs)** - a rust crossposting library for multiple social media platforms
- **[ark-protocol](https://github.com/tschk/ark-protocol)**
  - open protocol and reference implementation for exposing many local VPS services behind one standardized HTTPS/WebSocket ingress. defines a manifest-based routing layer, adapter APIs, and Cloudflare-compatible edge integration for multiplexing internal ports through a single public endpoint.
- **[rs_ai](https://github.com/undivisible/rs_ai)**
  - rust ai sdk for building across cloud and local providers with one async-first api with on-device runtimes through `rs_ai_local` — including gemini nano on android and google chrome (browser prompt api), foundationmodels on macos, and phi silica on windows and microsoft edge (browser prompt api).
