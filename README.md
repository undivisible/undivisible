# hi, i'm max &nbsp;_[undivisible.dev](https://undivisible.dev/) [tsc.hk](https://tsc.hk)_

unthinking things for people.  
i build systems, runtimes, interfaces, developer tools, and small pieces of software that feel inevitable since the age of 8. <br>
[every single piece of major hardware i've used + stories](https://github.com/undivisible/undivisible/blob/main/hardware.md) <br>
stories about software + ai coming soon <br>
<br>
[![crates.io download history](https://cratesdownloadhistory.undivisible.dev/api/svg/undivisible?theme=octocat&date=dmy&crates=1)](https://crates.io/users/undivisible) <br>
i made this widget! - [github](https://github.com/undivisible/cratesdownloadhistory) [website](https://cratesdownloadhistory.undivisible.dev)

<p align="left">
 <a href="https://www.star-history.com/undivisible">
  <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/badge?user=undivisible&year=2026&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/badge?user=undivisible&year=2026" />
   <img alt="Top Committer" src="https://api.star-history.com/badge?user=undivisible&year=2026" />
  </picture>
 </a>
</p>

***

## [crepuscularity](https://crepuscularity.undivisible.dev) · [aurorality](https://github.com/softwarecorporation/aurorality)

> a framework for building cross-platform applications from a single web-based codebase — solely by writing react + tailwindcss and a js/ts or rust backend.

crepuscularity builds for: desktop apps (gpui), swiftui & jetpack compose mobile, tuis on ratatui, websites, embedded with a custom framebuffer or lvgl and browser extensions. [aurorality](https://github.com/semitechnological/aurorality) turns web frontends into native swiftui for macos and ios, accepting swift, js/ts, or rust as your backend. with crepuscularity lite and aurorality-js, you can drop into existing sites or electron apps to connect native frontends to js backends.

### [moonshine](https://moonshine.tsc.hk)
ground-up Bun-first hybrid web framework with a signal-only kernel and opt-in compiler, routing, rendering, server, and deployment layers.

### **[inauguration](https://inauguration.tsc.hk)** 
an ultra-fast, general-purpose compiler pipeline for multiple languages designed around explicit capability management and deterministic execution graphs. it features a native language (inlang) that supports two synchronized syntaxes—a strict, explicit form ideal for tooling, agents, and deterministic builds, and a lightweight, human-friendly form optimized for readability.

### [alpenglow](https://alpenglow.tsc.hk)
is my distro of linux. the minimal build is smaller than an image taken on a modern day phone, standard is smaller than a 50MP image. boots in under a second and runs completely in RAM. ships with my own custom package manager oil, which has been lightened for this operating system. there is a work in progress desktop environment – [alpenglowed](https://github.com/softwarecorporation/alpenglowed) built on top of wayland to render the entire desktop environment in crepuscular gpui, and [soliloquy](https://github.com/softwarecorporation/soliloquy), an experimental flavor of this os which is immutable, lightened further solely for its browser-native desktop environment based on rv8.

### [space](https://space.tsc.hk)
is a work in progress (it boots!) ground-up operating system built on top of inauguration. it focuses on having seperate services as distributed components, with the compiler natively sandboxing based on authority scheduling capabilities permissions etc.


### other
- **[subspace](https://github.com/softwarecorporation/subspace)** - statically composed capability-safe embedded realtime operating system.
- **[equilibrium](https://github.com/softwarecorporation/equilibrium)** — load c-compatible code into rust with one call. auto-detects sources, compiles, exposes as rust modules. `load()` is the primary path. for rust → swift, see [eqswift](https://github.com/softwarecorporation/eqswift).
- **[eqswift](https://github.com/softwarecorporation/eqswift)** — two lines to ffi rust to swift automagically.
- **[eqts](https://github.com/softwarecorporation/eqts)** — one rust api for typescript across node, bun, deno, and webassembly.
- **[rig](https://github.com/softwarecorporation/rig)** — cross-language native dependency manager — detects host language, adds libs via cli, exposes them in-process with equilibrium-ffi.
- **[apollo](https://github.com/softwarecorporation/apollo)** - local-first rust ai agent runtime. ~14mb binary, 10+ messaging channels, 20+ llm providers, autonomous coding mode, tool guardrails, plugin system.
- **[telekinesis](https://github.com/softwarecorporation/telekinesis)** — ai coding agent cli + tui powered by rotary (rx4) + crepuscularity-tui. [telekinesis.tsc.hk](https://telekinesis.tsc.hk).
- **[rv8](https://github.com/softwarecorporation/rv8)** (roverite) - a custom browser engine built with servo and v8 with in house optimisations.
- **[rx4](https://github.com/softwarecorporation/rotary)** (rotary) — general-purpose agent harness engine and crate in rust owns the loop, tools, providers, sessions, permissions and computer-use (with rs_peekaboo).
- **[zkr](https://github.com/softwarecorporation/zkr)** - evidence-backed temporal memory engine for personal agents.
- **[praefectus](https://github.com/softwarecorporation/praefectus)** - provider-neutral, verified computer-use execution for rust.
- **[darash](https://github.com/softwarecorporation/darash)** - provider-neutral async search client + crate for agents.
- **[wax](https://github.com/plyght/wax)** — fast homebrew-compatible package manager in rust. uses homebrew's ecosystem (formulae, bottles, casks) without the ruby/git overhead — compiled, async, parallel installs, lockfiles, and experimental winget/scoop/nix-like support.
- **[oil](https://github.com/semitechnological/oil)** – fast system package manager in rust for all major *nix systems based on wax with linuxbrew support and interop with existing package managers.
- **[nexnet](https://github.com/softwarecorporation/nexnet)** - local-first peer-to-peer social chat with wallet identity and encrypted messaging.
- **atmosphere** — a native sync and ecosystem layer for every device, with local-first and homelab support.
- **[lyceus](https://github.com/softwarecorporation/lyceus)** — experimental research into adaptive, growing model families, including native language models, memory and text diffusion experiments.
- **[roundhouse](https://github.com/softwarecorporation/roundhouse)** — always-on agentic operations built on rotary, with health checks, permission-gated tools and independent recovery verification.
- **[sdkkit](https://github.com/softwarecorporation/sdkkit)** — define one sdk contract and generate typed contracts for rust, python and typescript. service implementations and http clients are not generated yet.
- **[mono](https://github.com/atechnology-company/mono)** — object-centric encrypted replication for browsers and devices, with portable identity, capability-based access and cross-device continuity.
- **[ark](https://github.com/atechnology-company/ark)** — hosted app platform prototype with a rust control plane, v cli, svelte dashboard and declarative app manifests.
- **[arkie](https://github.com/arkiecompany/arkie)** — shared ai backend and mcp server for atechnology apps, with per-app tools, prompts and conversation history.
- **[cupboard](https://github.com/atechnology-company/cupboard)** — headless home hub for lan-first sync of files, photos, clipboard history and app handoff, with native companion apps.
- **[tofu](https://github.com/atechnology-company/tofu)** — an imessage-first personal agent foundation with a paired rust host, task daemon and approval-gated computer use. not an unattended deployed assistant.
- **[alpenglow rescue](https://github.com/undivisible/alpenglow-rescue)** — experimental rescue image based on pinned alpenglow, with reproducible virtual-machine storage, network and console checks; hardware repair workflows remain incomplete.
***

## miniapps

### web apps
- **[unthinkmail](https://unthinkmail.undivisible.dev/)** — mcp for imap-supported email.
- **[crates download history](https://cratesdownloadhistory.undivisible.dev/)** - see cumulative download history for a user on [crates.io](https://crates.io) with embeddable svg charts into markdowns and websites.
- **[standpoint](https://standpoint.undivisible.dev)** — the ultimate opinion based platform for sharing tierlists, voting on polls, and playing spectrum - a party game to guess on a spectrum based on a prompt.
- **[notes](https://notes.undivisible.dev/)** — minimal note taker with full google font support, code highlighting and editing and notion-style markdown editing.
- **[bublik](https://bublik.undivisible.dev/)** — canvas tool for generating custom frequency soundscapes.
- **[alphabets](https://alphabets.undivisible.dev)** — learn any unicode-supported alphabet through cards, quizzes, and completion tables.
- **[infrastruct](https://infrastruct.undivisible.dev)** — belief agnostic jurisprudence local ai search engine platform with searx & ddg, transformers.js and browser prompt api.
- **[akh](https://akh.undivisible.dev)** — islamic uniplatform for when i was previously interested in islam.
- **[qr-forge](https://github.com/undivisible/qr-forge)** — in-browser qr studio with live previews, palettes, shape masks, logo overlays and png, svg and jpeg export.
- **[atzel](https://github.com/arkiecompany/atzel)** — financial research dashboard bringing market data, news, economic indicators and sec filings into one interface.
- **[currant](https://github.com/arkiecompany/currant)** — ai sales agents and job management for trades businesses, from customer conversations and leads to quotes and invoices.
- **[experiences](https://github.com/atechnology-company/experiences)** — platform and sdk for creating and sharing interactive 3d spaces across web and xr clients.
- **[unthought](https://github.com/arkiecompany/unthought)** — business platforming project combining domain registration, generated sites, deployment and mail-service integration.
- **[diplomap](https://github.com/undivisible/DiploMap)** — flask and folium project using interactive maps to explain global conflicts.

### developer tools
- **[herdr-gui](https://github.com/undivisible/herdr-gui)** - a gui surface for [herdr](https://herdr.dev) built with crepuscularity and [ghostty](https://ghostty.org/)
- **[incisor](https://github.com/undivisible/incisor)** - a rust + crepuscularity rewrite of balenaetcher to flash os images to sd cards and usbs
- **[neptune](https://github.com/semicentric/neptune)** — firmware reverse-engineering research toolchain for disassembly, decompilation, rebuilding and vulnerability analysis on hardware you own.
- **[arcanbar](https://github.com/undivisible/arcanbar)** — polybar-shaped status surface for arcan, with small text-producing modules and external actions.
- **[graft mail](https://github.com/arkiecompany/graft-mail)** — remote mcp access to existing imap and smtp email accounts, gated by a subscription.
- **[tangent](https://github.com/undivisible/tangent)** — discord automation for digital product sellers, connecting stripe payments, fulfillment, tickets and ai support.
- **[hermes-workspaces](https://github.com/undivisible/hermes-workspaces)** — workspace-selection integration for isolated hermes profiles; source-aware gateway command integration remains unfinished.
- **[perplexity-mcp-poke](https://github.com/undivisible/perplexity-mcp-poke)** — perplexity search and filtered page content exposed through mcp for poke.
- **[opencode desktop gpui](https://github.com/semitechnological/rs_opencodedesktop)** — a crepuscularity gpui desktop-shell rewrite for opencode, replacing its web-based ui with native rendering.

### browser extensions
- **[rs_vimium](https://github.com/undivisible/rs_vimium)** — a rust rewrite of the [vimium](https://github.com/philc/vimium) browser extension built with the [crepuscularity webextension framework](https://github.com/softwarecorporation/crepuscularity).
- **[anywhere](https://github.com/undivisible/anywhere)** — browser extension that turns ai chat responses into interactive interfaces. renders widgets, panels, forms, charts inside chat via custom response tags, also built with the [crepuscularity webextension framework](https://github.com/softwarecorporation/crepuscularity).

### mobile & desktop
- **[folk around](https://github.com/undivisible/folk-around)** - lets [folk](https://getfolk.app) or any hermes agent or openclaw interact with your computer p2p on macos.
- **[poke around](https://github.com/undivisible/poke-around)** — lets [poke](https://poke.com) interact with your computer across major oses.
- **[headless display](https://github.com/undivisible/headless-display)** - native macos spoken screen mirroring chooser with kokoro using sidecarcore + accessibility.
- **[drift](https://github.com/undivisible/drift-wallpaper)** — macos drift screensaver as a live wallpaper on linux, macos, windows. spotify and apple music now playing support.
- **[vro](https://github.com/undivisible/vro)** — minimal micro inspired text editor written in v.
- **[ycyestim](https://github.com/undivisible/YCYEStim)** — ios controller for ycy yokonex gen 1 and 2 electrostimulation hardware over btle (optional user-owned http/websocket bridge); dual-channel waveforms, presets and programs, safety limits, healthkit and watchos heart-rate adaptive output.
- **[context](https://github.com/undivisible/context)** — consent-gated macos app that builds a private, cited profile from readable local context using rotary, codex app-server and zkr.
- **[kairo](https://github.com/semitechnological/kairo)** — macos-first video editor in c++ with a metal renderer, timeline editing and ai-assisted edit planning.
- **[tile](https://github.com/semitechnological/tile)** — macos tiling window manager with stacking, rectangle-compatible shortcuts and drag-to-snap zones.
- **[tabyrus](https://github.com/semitechnological/tabyrus)** — system-wide macos autocomplete, grammar checking and code reshaping with local mlx inference.
- **[rover](https://github.com/semitechnological/rover)** — macos launcher and ai assistant bar with app and file search, clipboard history, a calculator and a keyboard-driven browser.
- **[unelaborate](https://github.com/undivisible/unelaborate)** — native macos minecraft launcher with isolated instances, mod loaders, mod management and microsoft sign-in.
- **[omi v4](https://github.com/undivisible/omi-v4)** — proactive assistant spanning pendant, mobile, desktop, web and messaging, with evidence-backed memory and approval-gated desktop actions.
- **[plates](https://github.com/atechnology-company/plates)** — cross-device assistant clients combining arkie, atmosphere device services and cupboard local storage.
- **[subspace notes](https://github.com/atechnology-company/subspace)** — a separate note-taking app with handwriting, voice notes and an ai memory service; not the subspace realtime operating system.
- **[bluetooth terminal](https://github.com/undivisible/bluetooth-terminal)** — swiftui bluetooth scanner and terminal with device connection and signal-strength filtering.
- **[rs_ice](https://github.com/undivisible/rs_ice)** — in-progress rust rewrite of the ice macos menu-bar manager, with aurorality settings and incomplete upstream feature parity.
- **[fridge-agent](https://github.com/undivisible/fridge-agent)** — proof of concept for requesting samsung family hub photos and chert-managed facetime calls over imessage; not verified on a real fridge.

### games & experiments
- **[autophobia](https://github.com/chertlabs/autophobia)** — a week-long psychological horror told through imessage and facetime, with six character contacts.
- **[kyu](https://github.com/chertlabs/kyu)** — a customizable companion you build and text over imessage, backed by the chertlabs texting-games engine.
- **[strangers](https://github.com/chertlabs/strangers)** — concept for matching strangers over facetime and reconnecting over imessage, without ai personas.
- **[together](https://github.com/chertlabs/together)** — group facetime project for synchronized camera grids, browser broadcasts and watch parties; working title and undeployed site.
- **[duplex](https://github.com/undivisible/duplex)** — a unity game-design project from 2023.

## libraries

- **[rs_ai](https://github.com/undivisible/rs_ai)** - rust ai sdk for building across cloud and local providers with one async-first api with on-device runtimes through `rs_ai_local` — including gemini nano on android and google chrome (browser prompt api), foundationmodels on macos, and phi silica on windows and microsoft edge (browser prompt api).
- **[rs_poke](https://github.com/undivisible/rs_poke)** - [poke by interaction's](https://poke.com) sdk in rust.
- **[rs_peekaboo](https://github.com/undivisible/rs_peekaboo)** - peter steinberger's [peekaboo](https://github.com/steipete/peekaboo) rewritten in rust with a shell tool and usable as a crate library for embedding into applications.
- **[rs_gbrain](https://github.com/undivisible/rs_gbrain)** - [garry tan's gbrain](https://github.com/garrytan/gbrain) for openclaw rewritten in rust.
- **[rs_imessage](https://github.com/undivisible/rs_imessage)** - rust imessage crate and cli.
- **[rs_facetime](https://github.com/undivisible/rs_facetime)** - rust facetime crate and cli.
- **[stalwart lite](https://github.com/arkiecompany/stalwart-lite)** — stalwart fork that runs in-process as a rust crate. imap, smtp, management api — no web admin, no overhead. built for embedding and local-first setups.
- **[crosspost-rs](https://github.com/arkiecompany/crosspost-rs)** - a rust crossposting library for multiple social media platforms.
- **[svelte-streamdown](https://sveltestreamdown.undivisible.dev/)** - a svelte version of [vercel's streamdown](https://github.com/vercel/streamdown) for streamable markdown rendering with interactive codeblocks and math rendering.
- **[ditherkit_flutter](https://ditherkit-flutter.undivisible.dev/)** - a flutter version of [boring software inc's dither kit](https://tripwire.sh/dither-kit) for data visual representations with dither effects.
- **[flowtoken_flutter](https://flowtoken-flutter.undivisible.dev/)** — a flutter version of [ephibb's flowtoken](https://github.com/Ephibbs/flowtoken) for clean streaming animations with blur and opacity transitions.
- **[flowtoken-svelte](https://flowtoken-svelte.undivisible.dev/)** — a svelte version of [ephibb's flowtoken](https://github.com/Ephibbs/flowtoken) for clean streaming animations with blur and opacity transitions.
- **[flowtoken-swift](https://github.com/undivisible/flowtoken-swift/)** — a swiftui version of [ephibb's flowtoken](https://github.com/Ephibbs/flowtoken) for clean streaming animations with blur and opacity transitions.
- **[tree-sitter-v](https://github.com/undivisible/tree-sitter-v)** - tree sitter parsing and grammars for [v](https://github.com/vlang/v).
- **[tree-sitter-holyc](https://github.com/undivisible/tree-sitter-holyc)** - tree sitter parsing and grammars for the [holiest programming language on earth](https://github.com/Jamesbarford/holyc-lang).
- **[ark-protocol](https://github.com/arkiecompany/ark-protocol)** - open protocol and reference implementation for exposing many local vps services behind one standardized https/websocket ingress. defines a manifest-based routing layer, adapter apis, and cloudflare-compatible edge integration for multiplexing internal ports through a single public endpoint.
- **[monoprotocol](https://github.com/atechnology-company/monoprotocol)** — normative draft sync protocol: wire format, crypto (hkdf, aes256gcm), replicated object model, journals, capabilities; rust reference crate on crates.io with golden conformance vectors (json/cbor).
- **[silhouette shader](https://github.com/undivisible/silhouette-shader)** — original procedural webgl light studies for moonshine, driven by the sun's position at a chosen location, date and time.
- **[tree-sitter-crystal](https://github.com/undivisible/tree-sitter-crystal)** — experimental tree-sitter grammar for crystal classes, methods and expressions.
- **[tree-sitter-lolcode](https://github.com/undivisible/tree-sitter-lolcode)** — tree-sitter grammar for lolcode programs, expressions and control flow; not full lolcode 1.2 coverage.
- **[tree-sitter-nim](https://github.com/undivisible/tree-sitter-nim)** — experimental nim grammar with indentation-aware procedure and function bodies; language coverage remains incomplete.
- **[chertlabs engine](https://github.com/chertlabs/engine)** — shared rust cloudflare worker backend for texting games, with consent, memory, personas, scheduling and messaging transports.

and yes im scared of uppercase letters
