## Hey, I'm Sai Aike 
But people call me Sasta or Crow. 

CS undergrad. I spend most of my time below the application layer, but I also make apps in my free time. 

Started with Android/Kotlin, got more interested in what ran underneath it, and the bigger picture. Now I manage headless Linux servers, write Go tooling, and am building a self-hosted PaaS from scratch.

---

### What i am building right now

**`[paas-project](private for now)`** - a lightweight self-hosted Platform-as-a-Service in Go.
Push code, get a running container. Automatic TLS, Traefik reverse proxy, Prometheus/Grafana observability. Building it because I wanted to understand what Heroku and Render actually do under the hood.

---

### projects worth looking at

| project                            | what it does                                                                                                                                                 | tech                            |
| ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------- |
| [media-pipeline](https://github.com/sasta-kro/automated-content-farm)             | production automation pipeline: raw topic to short-form video. phonetic alignment, custom Thai text rendering, algorithmic anti-fingerprinting. 100k+ reach. | Python, FFmpeg, MFA, Gemini API |
| [dotfiles](https://github.com/sasta-kro/dotfiles)                   | unified config management across macOS and Fedora with GNU Stow. shared core, OS-specific overrides, one-command setup script.                               | Shell, Zsh, Neovim, Starship    |
| [go-learning-backend](https://github.com/sasta-kro/go-learning-backend)        | Go REST API with programmatic Docker daemon control -- pull images, manage container lifecycle via SDK. built to understand what orchestrators actually do.  | Go, Docker SDK                  |
| [simple-subtitles-generator](https://github.com/sasta-kro/simple-subtitles-generator) | .srt generator for video and audio. works cross-platform.                                                                                                    | Python                          |

---

### What i have run into recently

- built a Docker-inside-VM isolation layer to fix iptables forwarding conflicts between KVM and Docker networking
- managed remote VMs for friends via SSH and NX protocol -- provisioning, user management, systemd watchdogs
- wrote a dotfiles system with a shared zsh core and OS-specific overrides inspired by how Compose Multiplatform handles platform targets
- used the Docker Go SDK to programmatically manage container lifecycles (not docker run -- the actual daemon API)

---

### Stack

```
languages    Go, Python, Bash, Kotlin, SQL
infra        Linux (Fedora/RHEL), Docker, KVM/QEMU, systemd
networking   Tailscale, firewall-cmd, SSH/Mosh, Traefik, Nginx
tools        Neovim, Git, Cockpit, virsh, fzf, yazi, GNU Stow
learning     Kubernetes, Terraform, AWS
```

---

### Setup

- Fedora Linux + macOS 
- Colemak-DH, Vim motions, ~90 wpm
- Jetbrains IDEs, VS Code, Neovim with IDE config (LSP, treesitter, telescope)
- keyboard workflow: everything possible in the terminal

---

[My Linkedin](https://www.linkedin.com/in/sai-aike-shwe-tun-aung/)
