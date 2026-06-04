<!-- OLD -->
| Known languages | GitHub Statistics | Languages used in public repositories |
|-----------|-------------------|---------------------------------------|
| [![Richard Ziupsnys knows Lua, Go, C++, Python, Java, JavaScript, HTML, and uses TailwindCSS](https://skillicons.dev/icons?i=lua,go,cpp,python,java,js,html,tailwind&perline=2)](https://richy.lol) | [![Richard Ziupsnys' GitHub Statistics](https://github-readme-stats-self-three.vercel.app/api?username=Richy-Z&show_icons=true&theme=radical)](https://richy.lol) | [![Languages that are used by Richard Ziupsnys in public repositories](https://github-readme-stats-self-three.vercel.app/api/top-langs/?username=Richy-Z&layout=compact&theme=radical&exclude_repo=Luobulesi-Research,github-readme-stats,nwcdnfs,printersploit-codex,vyno-mica,discordgo,CpuTopologyRebuild,Marlin-CR10S)](https://richy.lol) |

<!-- | Known languages | GitHub Statistics |
|-----------|-------------------|
| [![Richard Ziupsnys knows Lua, Python, C, JavaScript and Java](https://skillicons.dev/icons?i=lua,go,cpp,python,java,js,html,tailwind&perline=8)](https://richy.lol) | [![Richard Ziupsnys' GitHub Statistics](https://github-readme-stats-self-three.vercel.app/api?username=Richy-Z&show_icons=true&theme=radical)](https://richy.lol) | -->

# Hi, I'm Richard Ziupsnys

Hello - I'm Richard. I'm a Year 12 A-Level student who builds backend systems, programming tools, and infrastructure projects in my spare time.

I work primarily with **Go**, **Lua/Luvit**, and **C**, and I enjoy designing things close to the protocol layer - HTTP internals, routing engines, storage formats, and distributed infrastructure (the last one is my favourite).

Despite still being in school, I have independently built several production systems used by thousands of users, along with language tooling and low-level runtime components.

## What do I build?
Backend systems, high-performance infrastructure, datastores, and protocol tooling. Some language design too, if you would like to include the [Nue Programming Language](https://nue.nu).

I enjoy:
- writing character-by-character scanners/parsers
- designing high-performance HTTP stacks,
- implementing RFC-compliant protocols like SMTP, TOTP, and OAuth2,
- building storage engines and KV databases,
- real-world systems optimisation,
- Lua/Luvit internals, coroutines and event loops,
- and rewriting bottlenecks in C when necessary (although that might just be because I have outgrown Lua's purpose to the point where external intervention is required)

## 🐠 Projects
Of course, all of the above practically means nothing if I don't tell you about some real-world projects where I actually apply some theory.

### [Numelon Rubiš](https://rubis.app) - High-performance paste and content platform
- 3M+ stored documents
- 10K+ monthly users
- ~~Low-overhead HTTP server through a heavy extension of [`coro-http`](https://github.com/luvit/lit/blob/master/deps/coro-http.lua)~~ Rubis now uses [Rind](https://numelon.fandom.com/wiki/Rind) in Go..
- Full telemetry with latency histograms, RPC counters, TTFB, and tag-based metrics
- ~~MessagePack metadata pipeline with serialisation offloaded to C~~
- Burst-tested to ~12.5M requests without failure
- Used as the backend trust layer for [sUNC's](https://sunc.su) test result verification

### [Sklair](https://sklair.numelon.com) - HTML compiler and build system
- HTML compilation with component expansion
- Head segmentation and deterministic ordering (resource hints, metadata, scripts, styles)
- Sandboxed pre- and post-build Lua hooks for data generation and build-time logic
- Strict filesystem sandboxing for hooks (project / cache / generated / built scopes)
- Live development server with filesystem watching and debounced rebuilds
- **Builds that are only a few milliseconds**
- Zero runtime dependencies in the browser

### Numelon Passport - OAuth2 Identity Provider
*Currently being rewritten in Go using [Rind](https://numelon.fandom.com/wiki/Rind)*

- Full OAuth2 authorisation code flow
- Sessions, grants, and application management
- Strict CSRF protection and protection against replay attacks
- Passwordless login architecture
- TOTP 2FA implemented from RFC 6238 / RFC 4226 using OpenSSL's HMAC
- Custom SMTP client, "Letterbox", with persistent connections, MIME encoding, and connection pooling

<!--
TODO: work on website!
### There's more...

There is A LOT more in *much* more detail, however I would like to keep my GitHub README concise. For more information, please visit [my website](https://richy.lol).
-->

### There's more...

There is *a lot* more in *much* more detail, however I would like to keep my GitHub README concise. For more information, request my CV by sending an email to [hello@richy.lol](mailto:hello@richy.lol).

## Links

Website: [richy.lol](https://richy.lol)
LinkedIn: [richy-z](https://linkedin.com/in/richy-z)
Email: [hello@richy.lol](mailto:hello@richy.lol)
