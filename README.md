# hi, i'm max
_[undivisible.dev](https://undivisible.dev/)_ <br>
i make things for people. <br>
i build systems, runtimes, interfaces, developer tools, and small pieces of software that feel inevitable.

## projects

### [atechnology company](https://atechnology.company/)

#### soliloquy
an immutable operating system for the web, built from a modified alpine base with servo and v8.
- plates is a WIP ai assistant built on top of soliloquy and rv8 to sync your browser state everywhere, it uses ai agents to dynamically show you what's relevant in your life and in your activities.

#### experiences
a project exploring a more accessible spatial web, built on unity wasm.

#### atmosphere
a native sync and ecosystem layer for every device, with support for local-first setups and homelabs.

### [semitechnological](https://github.com/semitechnological)

#### [crepuscularity](https://crepuscularity.undivisible.dev)
write web code for everywhere.

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
load foreign code into rust with one call.

equilibrium auto-detects source files across c-compiling languages, builds them through a c-compatible path, and gives rust a usable module handle. bindings are there when you need them, but load() is the main path.

for rust into swift, see [eqswift](https://github.com/semitechnological/eqswift).

#### [stalwart lite](https://github.com/tschk/stalwart-lite)
a lightweight fork of stalwart to work as a crate.
the main build removes the bundled web admin, while the lite branch cuts the server down to standard mail: imap for clients, smtp for delivery and submission, with the management api still available.

#### [wax](https://github.com/semitechnological/wax)
a fast homebrew-compatible package manager in rust.
wax uses homebrew’s formulae, bottles, casks, and json api, but skips the ruby/git overhead with a compiled async binary, fast search, parallel installs, lockfiles, and clean homebrew interoperability.
wax also can integrate (in alpha) with other package managers like winget and scoop, and linux package managers with nix type behaviour.

#### otto (wip)
in progress ai powered ottocomplete anywhere on your mac

#### rover (wip)
a set of utilities and plugin system for your mac, based on raycast.

#### [tile (wip)](https://github.com/semitechnological/tile)
mosaic type tiling window manager + canvas + multiplexer for macos.

## miniapps

### [anywhere](https://github.com/undivisible/anywhere)
a browser extension that lets ai chats render interactive widgets, panels, forms, charts, and visualisations from special response tags. built with crepuscularity's web extensions framework for writing mv3 webextensions in rust.

### [poke around](https://github.com/undivisible/poke-around)
lets [poke](https://poke.com) interact with your computer across major operating systems.

### [unthinkmail](https://unthinkmail.undivisible.dev/)
mcp for imap-supported email.

### [drift](https://github.com/undivisible/drift-wallpaper)
the macos drift screensaver as a wallpaper across linux macos and windows, based on [flux](https://github.com/sandydoo/flux), with spotify and apple music now playing support. built with crepuscularity for fast hardware accelerated ui.

### [unelaborate](https://github.com/undivisible/unelaborate)
a minecraft client built with native swiftui, with feather type modrinth connections for modpack, shader and resource pack loading directly in client, share, import and export your mods and instances.

### [notes](https://notes.undivisible.dev/)
a minimal note websites based from the now-defunct zen.unit.ms. write notes, and they will be there when you come back, with complete google font and notion type markdown editing.

### [bublik](https://bublik.undivisible.dev/)
a canvas tool for generating custom frequency soundscapes.

### [alphabets](https://alphabets.undivisible.dev)
learn any unicode-supported alphabet through cards, quizzes, and completion tables.
