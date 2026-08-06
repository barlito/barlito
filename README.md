# Hi, I'm Axel 👋

PHP / Symfony developer based in France. I build web apps end to end — and I self-host everything that runs them, on a Docker Swarm behind Traefik, with full observability. One service = one repo.

![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)
![Symfony](https://img.shields.io/badge/Symfony-000000?logo=symfony&logoColor=white)
![FrankenPHP](https://img.shields.io/badge/FrankenPHP-2C2C54)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Docker Swarm](https://img.shields.io/badge/Docker%20Swarm-2496ED?logo=docker&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?logo=traefikproxy&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)

## 🧰 Infrastructure toolkit

The reusable base every project of mine starts from:

| Repo | What it is |
|---|---|
| [php-starter](https://github.com/barlito/php-starter) | Symfony starter — FrankenPHP, Docker Swarm, quality tools and CI/CD pipeline ready to go |
| [php-make-rules](https://github.com/barlito/php-make-rules) | Reusable Make + Castor rules for Symfony projects, shared as a git submodule |
| [utils](https://github.com/barlito/utils) | Symfony utility library — Doctrine ID traits, reusable Behat contexts |
| [traefik-base](https://github.com/barlito/traefik-base) | Traefik 3 edge stack — TLS, security headers, Authelia, WireGuard, HTTP/3 |
| [observability-stack](https://github.com/barlito/observability-stack) | Metrics, logs and traces — Prometheus, Loki, Tempo, Alloy, Grafana |

## 🃏 The Youl ecosystem

Games and tools built for my Discord community:

| Repo | What it is |
|---|---|
| [youl-tcg](https://github.com/barlito/youl-tcg) | Trading card game — Symfony backend |
| [ytcg-game-client](https://github.com/barlito/ytcg-game-client) | React / TypeScript game client |
| [youl-tcg-showcase](https://github.com/barlito/youl-tcg-showcase) | Card showcase site — holographic effects in pure CSS |
| [youl-coin-api](https://github.com/barlito/youl-coin-api) | Virtual currency API behind the community's economy |
| [youls-analytics](https://github.com/barlito/youls-analytics) | Full-history Discord stats, exported and served as a static report |
| [yt-gif-discord-bot](https://github.com/barlito/yt-gif-discord-bot) | `/gif` slash command — turns YouTube segments into GIFs |

## 🐶 Side projects

- [dog-help-scheduler](https://github.com/barlito/dog-help-scheduler) — randomized "fake walk" ntfy reminders to help a dog with separation anxiety
- [minecraft-server](https://github.com/barlito/minecraft-server) — containerized game servers (Minecraft, Zomboid, and friends)
- carapp *(private)* — appointment-management PWA for a tattoo studio — Symfony UX, LiveComponents, FullCalendar
- perler-studio *(private)* — turns pixel-art sprites into perler bead patterns

---

<sub>Everything above runs self-hosted on Docker Swarm, deployed with GitHub Actions, behind <a href="https://github.com/barlito/traefik-base">traefik-base</a>, watched by <a href="https://github.com/barlito/observability-stack">observability-stack</a>.</sub>

