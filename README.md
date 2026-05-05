# hi, i'm max
_[undivisible.dev](https://undivisible.dev/)_ <br>
i make things for people. <br>
part-time language learner, part-time philosopher, full-time schemer. <br>
i build systems, runtimes, interfaces, developer tools, and small pieces of software that feel inevitable.

## projects

### [atechnology company](https://atechnology.company/)

#### soliloquy
an experimental operating system model for the web — immutable, browser-native, and built on a modified alpine base with servo and v8.
it hosts plates, a WIP agentic ai assistant for every device, native to the web and keeps you in touch with whats important.

#### experiences
a project exploring a more accessible spatial web, built on unity wasm.

#### atmosphere
a native sync and ecosystem layer for every device, with support for local-first setups and homelabs.

### [semitechnological](https://github.com/semitechnological)

### [crepuscularity](https://crepuscularity.undivisible.dev)
a framework for building cross-platform applications from a single web-based codebase.

crepuscularity is a framework for building:
- desktop apps with gpui
- [aurorality](https://github.com/semitechnological/aurorality) to turn your web frontends into swiftui, write swift, javascript/typescript, or rust as your backend.
- tuis on top of ratatui in an opentui style
- websites
- browser extensions
- mobile experiences built on top of jetpack compose and swiftui
- with crepuscularity lite and aurorality-js, you can bundle js/ts into your existing websites and webapps to connect your native frontend to js backend.
- **solely by writing react + tailwindcss type code and a js/ts or rust backend**

#### [equilibrium](https://github.com/semitechnological/equilibrium)
load code from c-compiling languages into rust with one call.
equilibrium auto-detects source files, compiles them through a c-compatible path, and exposes them as usable rust modules. bindings exist when needed, but `load()` is the primary path.

for rust into swift, see [eqswift](https://github.com/semitechnological/eqswift).

#### [stalwart lite](https://github.com/tschk/stalwart-lite)
a lightweight fork of stalwart designed to run in-process as a rust crate.
the main build removes the bundled web admin, while the lite branch reduces the server to core mail functionality: imap for clients, smtp for delivery and submission, with the management api still available.
built for embedding, local-first setups, and environments where running a full mail server stack is unnecessary.

#### [wax](https://github.com/semitechnological/wax)
a fast homebrew-compatible package manager in rust.
uses homebrew’s ecosystem (formulae, bottles, casks, api) without the ruby/git overhead — compiled, async, parallel installs, with lockfiles and clean interoperability.
experimental support for other package managers (winget, scoop, linux) with nix-like behaviour.

<span style="color:#999">
#### otto (wip)
in progress ai powered ottocomplete anywhere on your mac

#### rover (wip)
a set of utilities and plugin system for your mac, based on raycast.

#### [tile (wip)](https://github.com/semitechnological/tile)
mosaic type tiling window manager + canvas + multiplexer for macos.

<br><br><br>
## miniapps

### [anywhere](https://github.com/undivisible/anywhere)
a browser extension that turns ai chat responses into interactive interfaces.
renders widgets, panels, forms, charts, and tools directly inside chat using custom response tags.
built with crepuscularity’s rust-based mv3 extension framework.

### [poke around](https://github.com/undivisible/poke-around)
lets [poke](https://poke.com) interact with your computer across major operating systems.

### [unthinkmail](https://unthinkmail.undivisible.dev/)
mcp for imap-supported email.

### [drift](https://github.com/undivisible/drift-wallpaper)
the macos drift screensaver as a wallpaper across linux macos and windows, based on [flux](https://github.com/sandydoo/flux), with spotify and apple music now playing support. built with crepuscularity for fast hardware accelerated ui.

### [unelaborate](https://github.com/undivisible/unelaborate)
a minecraft client built with native swiftui, with feather type modrinth connections for modpack, shader and resource pack loading directly in client, share, import and export your mods and instances.

### [notes](https://notes.undivisible.dev/)
a minimal note taker based from the now-defunct zen.unit.ms. write notes, and they will be there when you come back, with complete google font and notion type markdown editing.

### [bublik](https://bublik.undivisible.dev/)
a canvas tool for generating custom frequency soundscapes.

### [alphabets](https://alphabets.undivisible.dev)
learn any unicode-supported alphabet through cards, quizzes, and completion tables.
</span>
