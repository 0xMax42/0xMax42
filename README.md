# 0xMax42

Developer and infrastructure generalist focused on Deno, TypeScript, Linux, self-hosted systems, reproducible automation, and documentation pipelines.

I build tools and infrastructure that make systems more explicit: typed where possible, reproducible by default, documented well enough to survive future me, and boring enough to operate without rituals.

Deno-first, dependency-suspicious, but not anti-tooling.
Dependencies are allowed. They should just explain themselves first.

---

## What I work on

* **Deno / TypeScript tooling**
  CLIs, APIs, automation tools, typed service components, and small systems that prefer explicit structure over framework magic.

* **Self-hosted infrastructure**
  Gitea, act_runner, Traefik, ACME, containers, CI/CD pipelines, artifact handling, deployment workflows, and services that should remain understandable after the initial setup.

* **Linux operations and systemd**
  User and system services, timers, sandboxing, logging, service hardening, reproducible host configuration, and the occasional fight with reality at PID 1.

* **Containers with operational boundaries**
  Docker where needed, Podman where possible, rootless setups, systemd integration, hardened runtime assumptions, and fewer privileges than “just add the user to the docker group”.

* **Packaging and reproducible builds**
  Debian packages, release automation, pinned build environments, internal repositories, CI artifacts, and software that can be built again without archaeological work.

* **Documentation engineering**
  Markdown, Pandoc, LaTeX, PDF/A, custom templates, structured technical writing, and documentation that is treated as part of the system rather than decorative paperwork.

* **Flatfile and metadata-driven workflows**
  File-based architectures, YAML/Markdown metadata, project automation, and storage formats that can still be inspected with a text editor.

---

## Selected themes

### Self-hosted development infrastructure

I run and build infrastructure around Gitea, CI runners, containerized services, reverse proxies, package registries, deployment automation, and internal tooling.

The goal is not to recreate every cloud platform badly.
The goal is to keep the important parts inspectable, reproducible, and under control.

### Deno-first automation

I prefer Deno and TypeScript for most new tools: explicit permissions, native TypeScript support, integrated tooling, and a runtime model that does not immediately summon a `node_modules` demon circle.

Some demons remain. At least they come with a Debian package.

### Reproducible operations

I like systems that can answer basic questions:

* What is running?
* Why is it running?
* How was it built?
* How is it updated?
* How do I roll it back?
* Will future me understand this without swearing too much?

If the answer is “check the CI logs and pray”, something is probably missing.

### Documentation as infrastructure

I use Markdown-based workflows, Pandoc, LaTeX, custom templates, and generated PDFs for technical and formal documentation.

Good documentation is not an afterthought.
It is the control plane for human memory.

---

## Projects

🧩 **[0xMax42.io](https://0xmax42.io)**
A technical blog about architecture, infrastructure, automation, flatfiles, documentation, self-hosting, and things I do not want to reverse-engineer from my own repositories later.

📜 **Markdown-based Project Management**
A custom Obsidian-oriented workflow for managing tasks and projects with YAML metadata, recurrence, dependencies, and readable long-term structure.

📦 **Packaging and release automation**
Debian packaging, internal repositories, CI-generated artifacts, changelog-driven releases, and build pipelines that try very hard not to be powered by vibes.

🔧 **Patching software instead of forking it**
I regularly adapt existing applications to fit my workflows: custom patches, packaging adjustments, configuration overlays, build-time modifications, and small behavioral changes that are easier to maintain than carrying a permanent fork.

The goal is usually to stay close to upstream, keep updates practical, and only change what actually needs changing.

🧰 **Small tools, CLIs, and infrastructure glue**
Deno/TypeScript and Python tools for automation, system integration, documentation, deployment, backups, and operational workflows.

---

## What you won’t find here

* Product marketing
* Badge farms
* Build pipelines powered by vibes
* “Works on my machine” as a deployment strategy
* Framework magic without an exit plan
* Dependencies that joined the project without introducing themselves

---

## Contact

Open an issue, follow the trail at [0xMax42.io](https://0xmax42.io), or look for the repository that explains why the other repository exists.

---

## Statistics

![Since 21 Dec 2023](https://img.shields.io/endpoint?url=https://waka.0xmax42.io/api/compat/shields/v1/0XMax42/interval:all_time&label=Since%2021%20Dec%202023&color=blue)

<details>
<summary>WakaTime language breakdown</summary>

Generated from my own WakaTime-compatible instance.

![All time WakaTime Stats](https://git.0xmax42.io/maxp/.profile/raw/branch/main/cards/waka.svg)

</details>