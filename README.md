| Known languages | GitHub Statistics | Languages used in public repositories |
|-----------|-------------------|---------------------------------------|
| [![Richard Ziupsnys knows Lua, Python, C, JavaScript and Java](https://skillicons.dev/icons?i=lua,python,java,go,c,js,html&perline=2)](https://richy.lol) | [![Richard Ziupsnys' GitHub Statistics](https://github-readme-stats-self-three.vercel.app/api?username=Richy-Z&show_icons=true&theme=radical)](https://richy.lol) | [![Languages that are used by Richard Ziupsnys in public repositories](https://github-readme-stats-self-three.vercel.app/api/top-langs/?username=Richy-Z&layout=compact&theme=radical&exclude_repo=Luobulesi-Research,github-readme-stats)](https://richy.lol) |

# 👋🏻 Hi, I'm Richard Ziupsnys

Hello - I'm Richard. I'm a Year 12 A-Level student who builds backend systems, programming tools, and infrastructure projects in my spare time.

I work primarily with **Lua/Luvit**, **Go**, and **C**, and I enjoy designing things close to the protocol layer - HTTP internals, routing engines, storage formats, and distributed infrastructure (the last one is my favourite).

Despite still being in school, I have independently built several production systems used by thousands of users, along with language tooling and low-level runtime components.

## 🔧 What do I build?
Backend systems, high-performance infrastructure, datastores, and protocol tooling. Some language design too, if you would like to include the [Nue Programming Language](https://nue.nu).

I enjoy:
- designing high-performance HTTP stacks,
- implementing RFC-compliant protocols like SMTP, TOTP, and OAuth2,
- building storage engines and KV databases,
- real-world systems optimuisation,
- Lua/Luvit internals, coroutines and event loops,
- and rewriting bottlenecks in C when necessary (although that might just be because I have outgrown Lua's purpose to the point where external intervention is required)

## 🐠 Projects
Of course, all of the above practically means nothing if I don't tell you about some real-world projects where I actually apply mentioned theory.

### [Numelon Rubiš](https://rubis.app) - High-performance paste and content platform
- 2M+ stored documents
- 10K+ monthly users
- Low-overhead HTTP server through a heavy extension of [`coro-http`](https://github.com/luvit/lit/blob/master/deps/coro-http.lua)
- Full telemetry with latency histograms, RPC counters, TTFB, and tag-based metrics
- MessagePack metadata pipeline with serialisation offloaded to C
- Burst-tested to ~12.5M requests without failure
- Used as the backend trust layer for [sUNC's](https://sunc.su) test result verification

### Numelon Passport - OAuth2 Identity Provider
*Currently being rewritten in Go using my in-progress framework, Rind*

- Full OAuth2 authorisation code flow
- Sessions, grants, and application management
- Strict CSRF protection and protection against replay attacks
- Passwordless login architecture
- TOTP 2FA implemented from RFC 6238 / RFC 4226 using OpenSSL's HMAC
- Custom SMTP client, "Letterbox", with persistent connections, MIME encoding, and connection pooling

### There's more...

There is A LOT more in *much* more detail, however I would like to keep my GitHub README concise. For more information, please visit [my website](https://richy.lol).

## Links

Website: [richy.lol](https://richy.lol)
LinkedIn: [richy-z](https://linkedin.com/in/richy-z)
Email: [hello@richy.lol](mailto:hello@richy.lol)
