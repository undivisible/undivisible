# hi, i'm max &nbsp;_[undivisible.dev](https://undivisible.dev/) [tsc.hk](https://tsc.hk)_

unthinking things for people.  
i build systems, runtimes, interfaces, developer tools, and small pieces of software that feel inevitable since the age of 8. <br>
[every single piece of major hardware i've used + stories](https://github.com/undivisible/undivisible/blob/main/hardware.md) <br>
stories about software + ai coming soon <br>
<br>
[![crates.io download history](https://cratesdownloadhistory.undivisible.dev/api/svg/undivisible?theme=octocat&date=dmy&crates=1)](https://crates.io/users/undivisible) <br>
i made this widget! - [github](https://github.com/undivisible/cratesdownloadhistory) [website](https://cratesdownloadhistory.undivisible.dev)

***

## [crepuscularity](https://crepuscularity.undivisible.dev) · [aurorality](https://github.com/tschk/aurorality)

> a framework for building cross-platform applications from a single web-based codebase — solely by writing react + tailwindcss and a js/ts or rust backend.

crepuscularity builds for: desktop apps (gpui), swiftui & jetpack compose mobile, tuis on ratatui, websites, embedded with a custom framebuffer or lvgl and browser extensions. [aurorality](https://github.com/semitechnological/aurorality) turns web frontends into native swiftui for macos and ios, accepting swift, js/ts, or rust as your backend. with crepuscularity lite and aurorality-js, you can drop into existing sites or electron apps to connect native frontends to js backends.

### **[inauguration](https://inauguration.tsc.hk)** 
an ultra-fast, general-purpose compiler pipeline for multiple languages designed around explicit capability management and deterministic execution graphs. it features a native language (inlang) that supports two synchronized syntaxes—a strict, explicit form ideal for tooling, agents, and deterministic builds, and a lightweight, human-friendly form optimized for readability.

### [alpenglow](https://alpenglow.tsc.hk)
is my distro of linux. the minimal build is smaller than an image taken on a modern day phone, standard is smaller than a 50MP image. boots in under a second and runs completely in RAM. ships with my own custom package manager oil, which has been lightened for this operating system. there is a work in progress desktop environment – [alpenglowed](https://github.com/tschk/alpenglowed) built on top of wayland to render the entire desktop environment in crepuscular gpui, and [soliloquy](https://github.com/tschk/soliloquy), an experimental flavor of this os which is immutable, lightened further solely for its browser-native desktop environment based on rv8.

### [space](https://space.tsc.hk)
is a work in progress (it boots!) ground-up operating system built on top of inauguration. it focuses on having seperate services as distributed components, with the compiler natively sandboxing based on authority scheduling capabilities permissions etc.]

### [rv8](https://github.com/tschk/rv8) (roverite)
a custom browser engine built with servo and v8 with in house optimisations.

### other
- **[equilibrium](https://github.com/tschk/equilibrium)** — load c-compatible code into rust with one call. auto-detects sources, compiles, exposes as rust modules. `load()` is the primary path. for rust → swift, see [eqswift](https://github.com/semitechnological/eqswift).
- **[telekinesis](https://github.com/semitechnological/telekinesis)** — minimal extensible cli and gui host for the rotary agent harness engine. built with rotary and crepuscularity. supports pi plugins and oauth + api key. 
- **[rx4](https://github.com/tschk/rotary)** (rotary) — general-purpose agent harness engine and crate in rust owns the loop, tools, providers, sessions, permissions and computer-use (with rs_peekaboo).
- **[wax](https://github.com/plyght/wax)** — fast homebrew-compatible package manager in rust. uses homebrew's ecosystem (formulae, bottles, casks) without the ruby/git overhead — compiled, async, parallel installs, lockfiles, and experimental winget/scoop/nix-like support.
- **[oil](https://github.com/semitechnological/oil)** – fast system package manager in rust for all major *nix systems based on wax with linuxbrew support and interop with existing package managers.
- **atmosphere** — a native sync and ecosystem layer for every device, with local-first and homelab support.
***

## miniapps

### web apps
- **[crates download history](https://cratesdownloadhistory.undivisible.dev/)** - see cumulative download history for a user on [crates.io](https://crates.io) with embeddable svg charts into markdowns and websites.
- **[standpoint](https://standpoint.undivisible.dev)** — the ultimate opinion based platform for sharing tierlists, voting on polls, and playing spectrum - a party game to guess on a spectrum based on a prompt.
- **[notes](https://notes.undivisible.dev/)** — minimal note taker with full google font support, code highlighting and editing and notion-style markdown editing.
- **[bublik](https://bublik.undivisible.dev/)** — canvas tool for generating custom frequency soundscapes.
- **[alphabets](https://alphabets.undivisible.dev)** — learn any unicode-supported alphabet through cards, quizzes, and completion tables.
- **[infrastruct](https://infrastruct.undivisible.dev)** — belief agnostic jurisprudence local ai search engine platform with searx & ddg, transformers.js and browser prompt api.
- **[akh](https://akh.undivisible.dev)** — islamic uniplatform for when i was previously interested in islam.

### developer tools
- **[herdr-gui](https://github.com/undivisible/herdr-gui)** - a gui surface for [herdr](https://herdr.dev) built with crepuscularity and [ghostty](https://ghostty.org/)
- **[incisor](https://github.com/undivisible/incisor)** - a rust + crepuscularity rewrite of balenaetcher to flash os images to sd cards and usbs

### browser extensions
- **[rs_vimium](https://github.com/undivisible/rs_vimium)** — a rust rewrite of the [vimium](https://github.com/philc/vimium) browser extension built with the [crepuscularity webextension framework](https://github.com/tschk/crepuscularity).
- **[anywhere](https://github.com/undivisible/anywhere)** — browser extension that turns ai chat responses into interactive interfaces. renders widgets, panels, forms, charts inside chat via custom response tags, also built with the [crepuscularity webextension framework](https://github.com/tschk/crepuscularity).

### mobile & desktop
- **[unthinkmail](https://unthinkmail.undivisible.dev/)** — mcp for imap-supported email.
- **[folk around](https://github.com/undivisible/folk-around)** - lets [folk](https://getfolk.app) or any hermes agent or openclaw interact with your computer p2p on macos.
- **[poke around](https://github.com/undivisible/poke-around)** — lets [poke](https://poke.com) interact with your computer across major oses.
- **[unthinkclaw](https://github.com/undivisible/unthinkclaw)** — self learning ai agent that lives on your computer. <1/100 of the size of openclaw, with a better ux (subjectively). can deploy agent swarms and is easily extensible.
- **[drift](https://github.com/undivisible/drift-wallpaper)** — macos drift screensaver as a live wallpaper on linux, macos, windows. spotify and apple music now playing support.
- **[vro](https://github.com/undivisible/vro)** — minimal micro inspired text editor written in v.
- **[ycyestim](https://github.com/undivisible/YCYEStim)** — ios controller for ycy yokonex gen 1 and 2 electrostimulation hardware over btle (optional user-owned http/websocket bridge); dual-channel waveforms, presets and programs, safety limits, healthkit and watchos heart-rate adaptive output.

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
- **[tree-sitter-v](https://github.com/undivisible/tree-sitter-v)** - tree sitter parsing and grammars for [v](https://github.com/vlang/v).
- **[tree-sitter-holyc](https://github.com/undivisible/tree-sitter-holyc)** - tree sitter parsing and grammars for the [holiest programming language on earth](https://github.com/Jamesbarford/holyc-lang).
- **[ark-protocol](https://github.com/tschk/ark-protocol)** - open protocol and reference implementation for exposing many local vps services behind one standardized https/websocket ingress. defines a manifest-based routing layer, adapter apis, and cloudflare-compatible edge integration for multiplexing internal ports through a single public endpoint.
- **[monoprotocol](https://github.com/atechnology-company/monoprotocol)** — normative draft sync protocol: wire format, crypto (hkdf, aes256gcm), replicated object model, journals, capabilities; rust reference crate on crates.io with golden conformance vectors (json/cbor).

and yes im scared of uppercase letters
