<div align="center">

<a href="https://leaningtech.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="/profile/company-logotype-dark.svg" />
    <img alt="Leaning Technologies" src="/profile/company-logotype-light.svg" width="280" />
  </picture>
</a>

### Native runtimes for the browser

Browser runtimes for [AI coding CLIs][browsercode], [Node.js][browserpod], [Rust][browserpod], [Python][browserpod], [C/C++][cheerp], [Java][cheerpj], [Flash][cheerpx-flash], and [x86 binaries][cheerpx] via WebAssembly.

Interested in our technologies, or in compilers, virtual machines and WebAssembly in general?

**👉 Join our [Discord!](https://discord.leaningtech.com/?utm_medium=social&utm_source=GitHub&utm_campaign=github+org+readme)**

</div>

<br />

---

<br />

<a href="https://browserpod.io/">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="/profile/browserpod-logotype-dark.svg" />
    <img alt="BrowserPod" src="/profile/browserpod-logotype-light.svg" height="60" />
  </picture>
</a>

**Run AI code securely on any device**

[ Website ][browserpod] · [ Repository ][browserpod-repo] · [ Documentation ][browserpod-docs]

- Sandboxed server runtimes that run entirely client-side, on a Linux-compatible kernel in WebAssembly
- Node.js and Rust, with Python in preview. Ruby and Go are in development
- Bash, git and core Linux utilities included, plus npm for Node.js
- Runs the frameworks and build tools you already use, such as React, Next.js, Express and Vite
- Expose a running dev server at a public URL with Portals
- Run multiple processes and threads concurrently
- Persistent or ephemeral filesystem, stored locally in the browser
- Built for AI agent sandboxes, web IDEs, interactive tutorials and runnable documentation

<br />

---

<br />

<a href="https://browsercode.io">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="/profile/browsercode-logotype-dark.svg" />
    <img alt="BrowserCode" src="/profile/browsercode-logotype-light.svg" height="60" />
  </picture>
</a>

**A browser-based coding playground, fully client-side**

[ Live demo ][browsercode] · [ Repository ][browsercode-repo] · [ Announcement ][browsercode-blog]

- Start from a framework template (Vite, React, Svelte, Vue, Next.js, Nuxt, Express) or clone any GitHub repository
- Run Claude Code, Codex CLI and Pi, with Antigravity, OpenCode and more coming soon
- File tree, code editor, terminal and live preview, with bash and git
- Share what you build at a public URL with Portals
- Embed it in your docs, tutorials or landing pages
- Built on [BrowserPod][browserpod], at near-native speed with instant startup
- Free and open source

<br />

---

<br />

<a href="https://webvm.io/">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="/profile/webvm-logotype-dark.svg" />
    <img alt="WebVM" src="/profile/webvm-logotype-light.svg" height="60" />
  </picture>
</a>

**A Linux virtual machine that runs entirely in the browser**

[ Live demo ][webvm] · [ Repository ][webvm-repo]

- Runs an unmodified Debian distribution, with many native development toolchains
- Built on [CheerpX](#cheerpx), our x86 virtualization engine
- Networking through Tailscale: reach your private network and, with an exit node, the internet
- A graphical [Alpine desktop](https://webvm.io/alpine.html) with Xorg and i3
- Works with Claude, using your own API key
- Fork it to deploy your own, with custom images

<br />

---

<br />

<a id="cheerpx" href="https://cheerpx.io/">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="/profile/cheerpx-logotype-dark.svg" />
    <img alt="CheerpX" src="/profile/cheerpx-logotype-light.svg" height="60" />
  </picture>
</a>

**Run virtual machines in your web apps**

[ Website ][cheerpx] · [ Repository ][cheerpx-repo] · [ Documentation ][cheerpx-docs]

- A JavaScript library that runs unmodified x86 binaries in any browser, client-side
- An x86-to-WebAssembly JIT compiler that handles dynamically generated and self-modifying code
- A virtual block-based file system and a Linux syscall emulator, enough to run complete Linux distributions
- Sandboxed by WebAssembly and the browser, even for untrusted code
- The engine behind [WebVM][webvm]
- [CheerpX for Flash][cheerpx-flash] runs Flash Player, so Flash content works in modern browsers
- Free for personal and open-source projects

<br />

---

<br />

<a href="https://cheerpj.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="/profile/cheerpj-logotype-dark.svg" />
    <img alt="CheerpJ" src="/profile/cheerpj-logotype-light.svg" height="60" />
  </picture>
</a>

**Real Java in the browser**

[ Website ][cheerpj] · [ Repository ][cheerpj-repo] · [ Documentation ][cheerpj-docs] · [ Playground ][cheerpj-playground]

- A full OpenJDK distribution in WebAssembly, with a JVM that runs your bytecode unchanged
- Supports Java 8, 11 and 17
- Run existing applications, applets, Java Web Start apps, and Oracle Forms and E-Business Suite clients, from unmodified JARs
- Integrate Java libraries in JavaScript, fully client-side
- Swing and AWT interfaces drawn with HTML elements and canvases
- One script tag loads it, from our CDN or your own server. Works in Chrome, Edge, Firefox and Safari
- Browser extensions run applets and Java Web Start apps in Chrome and Edge, for 170,000+ users
- 1M+ sessions a month from our public CDN
- An [agent skill][cheerpj-skill] for coding agents bringing Java apps to the browser

<br />

---

<br />

<a href="https://cheerp.io/">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="/profile/cheerp-logotype-dark.svg" />
    <img alt="Cheerp" src="/profile/cheerp-logotype-light.svg" height="60" />
  </picture>
</a>

**An enterprise-grade, open-source C/C++ compiler for WebAssembly and JavaScript**

[ Website ][cheerp] · [ Repository ][cheerp-repo] · [ Documentation ][cheerp-docs]

- Port C/C++ libraries and applications to the browser, with the right JavaScript interfaces exposed
- Write high-performance web applications and WebAssembly components in C++
- Built on LLVM/Clang and tracks upstream, with custom optimisations for speed and output size
- Apache 2.0 licence with LLVM exceptions, the same as LLVM/Clang

<br />

---

<!-- Reference links -->

[cheerp]: https://cheerp.io/
[cheerp-docs]: https://cheerp.io/docs/overview
[cheerp-repo]: https://github.com/leaningtech/cheerp-meta

[cheerpj]: https://cheerpj.com
[cheerpj-docs]: https://cheerpj.com/docs/
[cheerpj-repo]: https://github.com/leaningtech/cheerpj-meta
[cheerpj-playground]: https://javafiddle.leaningtech.com/
[cheerpj-skill]: https://cheerpj.com/skills/cheerpj/SKILL.md

[cheerpx]: https://cheerpx.io/
[cheerpx-docs]: https://cheerpx.io/docs/overview
[cheerpx-repo]: https://github.com/leaningtech/cheerpx-meta
[cheerpx-flash]: https://labs.leaningtech.com/docs/cheerpx-for-flash

[webvm]: https://webvm.io/
[webvm-repo]: https://github.com/leaningtech/webvm

[browserpod]: https://browserpod.io/
[browserpod-repo]: https://github.com/leaningtech/browserpod-meta
[browserpod-docs]: https://browserpod.io/docs/

[browsercode]: https://browsercode.io
[browsercode-repo]: https://github.com/leaningtech/browsercode
[browsercode-blog]: https://browserpod.io/blog/announcing-browsercode/
