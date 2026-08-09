# hi, i'm max &nbsp;_[undivisible.dev](https://undivisible.dev/) [tsc.hk](https://tsc.hk)_

unthinking things for people.  
i build systems, runtimes, interfaces, developer tools, and small pieces of software that feel inevitable since the age of 8. <br>
founding engineer at [based hardware](https://basedhardware.com), on [omi](https://github.com/BasedHardware/omi). <br>
[every single piece of major hardware i've used + stories](https://github.com/undivisible/undivisible/blob/main/hardware.md) <br>
stories about software + ai coming soon <br>
<br>
[![crates.io download history](https://cratesdownloadhistory.undivisible.dev/api/svg/undivisible?theme=octocat&date=dmy&crates=1)](https://crates.io/users/undivisible) <br>
i made this widget! - [github](https://github.com/undivisible/cratesdownloadhistory) [website](https://cratesdownloadhistory.undivisible.dev)

***

## [crepuscularity](https://crepuscularity.undivisible.dev) · [aurorality](https://github.com/tschk/aurorality)

> a framework for building cross-platform applications from a single web-based codebase — solely by writing react + tailwindcss and a js/ts or rust backend.

crepuscularity builds for: desktop apps (gpui), swiftui & jetpack compose mobile, tuis on ratatui, websites, embedded with a custom framebuffer or lvgl and browser extensions. [aurorality](https://github.com/tschk/aurorality) turns web frontends into native swiftui for macos and ios, accepting swift, js/ts, or rust as your backend. with crepuscularity lite and aurorality-js, you can drop into existing sites or electron apps to connect native frontends to js backends.

### [moonshine](https://moonshine.tsc.hk)
ground-up bun-first hybrid web framework with a signal-only kernel and opt-in compiler, routing, rendering, server, and deployment layers. [undivisible.dev](https://undivisible.dev) runs on it.

### **[inauguration](https://inauguration.tsc.hk)**
an ultra-fast, general-purpose compiler pipeline for multiple languages designed around explicit capability management and deterministic execution graphs. forty languages through one import graph, no llvm; self-hosts in under two seconds into a 9mb binary. it features a native language (inlang) that supports two synchronized syntaxes—a strict, explicit form ideal for tooling, agents, and deterministic builds, and a lightweight, human-friendly form optimized for readability.

### [alpenglow](https://alpenglow.tsc.hk)
is my distro of linux. the minimal build is smaller than an image taken on a modern day phone, standard is smaller than a 50MP image. boots in under a second and runs completely in RAM. ships with my own custom package manager oil, which has been lightened for this operating system. there is a work in progress desktop environment – [alpenglowed](https://github.com/tschk/alpenglowed) built on top of wayland to render the entire desktop environment in crepuscular gpui, and [soliloquy](https://github.com/tschk/soliloquy), an experimental flavor of this os which is immutable, lightened further solely for its browser-native desktop environment based on rv8.

### [space](https://space.tsc.hk)
is a work in progress (it boots!) ground-up operating system built on top of inauguration. five layers deep — .in → inauguration → sci → space → nanokernel — where the compiler defines authority, objects, scheduling and policy rather than only machine code. aarch64, arm and risc-v. no posix.

### [rv8](https://github.com/tschk/rv8)
(roverite) a custom browser engine built with servo for rendering and v8 for javascript, with in house optimisations.

### other systems
- **[rotary](https://github.com/tschk/rotary)** (rx4) — general-purpose agent harness engine and crate in rust. owns the loop, tools, providers, sessions, permissions, mcp, pi protocol compat and computer-use (with rs_peekaboo).
- **[apollo](https://github.com/tschk/apollo)** — local-first rust ai agent runtime. ~14mb binary, 10+ messaging channels, 20+ llm providers, autonomous coding mode, tool guardrails, plugin system.
- **[subspace](https://github.com/tschk/subspace)** — statically composed capability-safe embedded realtime operating system.
- **[equilibrium](https://github.com/tschk/equilibrium)** — load c-compatible code into rust with one call. auto-detects sources, compiles, exposes as rust modules. `load()` is the primary path. for rust → swift, see [eqswift](https://github.com/tschk/eqswift).
- **[nexnet](https://github.com/tschk/nexnet)** — local-first peer-to-peer social chat with wallet identity and encrypted messaging.
- **[zkr](https://github.com/tschk/zkr)** — evidence-backed temporal memory engine for personal agents.
- **[praefectus](https://github.com/tschk/praefectus)** — provider-neutral, verified computer-use execution for rust.
- **[darash](https://github.com/tschk/darash)** — provider-neutral async search client and crate for agents.
- **[wax](https://github.com/plyght/wax)** — fast homebrew-compatible package manager in rust. uses homebrew's ecosystem (formulae, bottles, casks) without the ruby/git overhead — compiled, async, parallel installs, lockfiles, and experimental winget/scoop/nix-like support.
- **[oil](https://github.com/semitechnological/oil)** – fast system package manager in rust for all major *nix systems based on wax with linuxbrew support and interop with existing package managers.
- **atmosphere** — a native sync and ecosystem layer for every device, with local-first and homelab support.

***

## miniapps

### web apps
- **[crates download history](https://cratesdownloadhistory.undivisible.dev/)** — see cumulative download history for a user on [crates.io](https://crates.io) with embeddable svg charts into markdowns and websites.
- **[standpoint](https://standpoint.undivisible.dev)** — the ultimate opinion based platform for sharing tierlists, voting on polls, and playing spectrum - a party game to guess on a spectrum based on a prompt.
- **[notes](https://notes.undivisible.dev/)** — minimal note taker with full google font support, code highlighting and editing and notion-style markdown editing.
- **[alphabets](https://alphabets.undivisible.dev)** — learn any unicode-supported alphabet through cards, quizzes, and completion tables.
- **[bublik](https://bublik.undivisible.dev/)** — canvas tool for generating custom frequency soundscapes.
- **[infrastruct](https://infrastruct.undivisible.dev)** — belief agnostic jurisprudence local ai search engine platform with searx & ddg, transformers.js and browser prompt api.

### developer tools
- **[herdr-gui](https://github.com/undivisible/herdr-gui)** — a gui surface for [herdr](https://herdr.dev) built with crepuscularity and [ghostty](https://ghostty.org/).
- **[incisor](https://github.com/undivisible/incisor)** — a rust + crepuscularity rewrite of balenaetcher to flash os images to sd cards and usbs.
- **[vro](https://github.com/undivisible/vro)** — an ultraminimal micro-inspired text editor written in v.
- **[arcanbar](https://github.com/undivisible/arcanbar)** — polybar for arcan, for the alpenglow desktop.

### browser extensions
- **[rs_vimium](https://github.com/undivisible/rs_vimium)** — a rust rewrite of the [vimium](https://github.com/philc/vimium) browser extension built with the [crepuscularity webextension framework](https://github.com/tschk/crepuscularity).
- **[anywhere](https://github.com/undivisible/anywhere)** — browser extension that turns ai chat responses into interactive interfaces. renders widgets, panels, forms, charts inside chat via custom response tags, also built with the [crepuscularity webextension framework](https://github.com/tschk/crepuscularity).

### mobile & desktop
- **[poke around](https://github.com/undivisible/poke-around)** — lets [poke](https://poke.com) interact with your computer across major oses.
- **[folk around](https://github.com/undivisible/folk-around)** — lets [folk](https://getfolk.app) or any hermes agent or openclaw interact with your computer p2p on macos.
- **[unthinkmail](https://unthinkmail.undivisible.dev/)** — mcp for imap-supported email.
- **[drift](https://github.com/undivisible/drift-wallpaper)** — macos drift screensaver as a live wallpaper on linux, macos, windows. spotify and apple music now playing support.
- **[ycyestim](https://github.com/undivisible/ycyestim)** — ios controller for ycy yokonex gen 1 and 2 electrostimulation hardware over btle (optional user-owned http/websocket bridge); dual-channel waveforms, presets and programs, safety limits, healthkit and watchos heart-rate adaptive output.

***

## libraries

- **[rs_ai](https://github.com/undivisible/rs_ai)** — rust ai sdk for building across cloud and local providers with one async-first api with on-device runtimes through `rs_ai_local` — including gemini nano on android and google chrome (browser prompt api), foundationmodels on macos, and phi silica on windows and microsoft edge (browser prompt api).
- **[rusty_foundationmodels](https://github.com/undivisible/rusty_foundationmodels)** — safe rust bindings for apple's foundationmodels on-device ai.
- **[rs_peekaboo](https://github.com/undivisible/rs_peekaboo)** — peter steinberger's [peekaboo](https://github.com/steipete/peekaboo) rewritten in rust with a shell tool and usable as a crate library for embedding into applications.
- **[rs_poke](https://github.com/undivisible/rs_poke)** — [poke by interaction's](https://poke.com) sdk in rust.
- **[rs_gbrain](https://github.com/undivisible/rs_gbrain)** — [garry tan's gbrain](https://github.com/garrytan/gbrain) for openclaw rewritten in rust.
- **[rs_imessage](https://github.com/undivisible/rs_imessage)** · **[rs_facetime](https://github.com/undivisible/rs_facetime)** — rust crates and clis for imessage and facetime on macos.
- **[stalwart lite](https://github.com/arkiecompany/stalwart-lite)** — stalwart fork that runs in-process as a rust crate. imap, smtp, management api — no web admin, no overhead. built for embedding and local-first setups.
- **[svelte-streamdown](https://sveltestreamdown.undivisible.dev/)** — a svelte version of [vercel's streamdown](https://github.com/vercel/streamdown) for streamable markdown rendering with interactive codeblocks and math rendering.
- **[ditherkit_flutter](https://ditherkit-flutter.undivisible.dev/)** — a flutter version of [boring software inc's dither kit](https://tripwire.sh/dither-kit) for data visual representations with dither effects.
- **flowtoken ports** — [ephibb's flowtoken](https://github.com/Ephibbs/flowtoken) for clean streaming animations with blur and opacity transitions, in [flutter](https://flowtoken-flutter.undivisible.dev/), [svelte](https://flowtoken-svelte.undivisible.dev/) and [swiftui](https://github.com/undivisible/flowtoken-swift/).
- **[monoprotocol](https://github.com/atechnology-company/monoprotocol)** — normative draft sync protocol: wire format, crypto (hkdf, aes256gcm), replicated object model, journals, capabilities; rust reference crate on crates.io with golden conformance vectors (json/cbor).

### tree-sitter grammars
parsers, grammars and rust bindings for languages that didn't have them.

- **[tree-sitter-holyc](https://github.com/undivisible/tree-sitter-holyc)** — the [holiest programming language on earth](https://github.com/Jamesbarford/holyc-lang).
- **[tree-sitter-v](https://github.com/undivisible/tree-sitter-v)** — [v](https://github.com/vlang/v).
- **[tree-sitter-crystal](https://github.com/undivisible/tree-sitter-crystal)** — [crystal](https://crystal-lang.org/).
- **[tree-sitter-nim](https://github.com/undivisible/tree-sitter-nim)** — [nim](https://nim-lang.org/).
- **[tree-sitter-lolcode](https://github.com/undivisible/tree-sitter-lolcode)** — [lolcode](http://www.lolcode.org/). yes, really.

and yes im scared of uppercase letters
