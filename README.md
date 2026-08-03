# NextOS — default community files

This repository holds the default community health files for every
[NextOs-Ports](https://github.com/NextOs-Ports) repository. Its
[`FUNDING.yml`](FUNDING.yml) is what puts the **Sponsor** button on the others.

> [!IMPORTANT]
> `FUNDING.yml` alone does **not** show the Sponsor button. Each repository has its own
> `hasSponsorshipsEnabled` toggle, off by default. After creating a repository, turn it on:
>
> ```sh
> id=$(gh repo view NextOs-Ports/<repo> --json id -q .id)
> gh api graphql -f query="mutation { updateRepository(input: {repositoryId: \"$id\", hasSponsorshipsEnabled: true}) { repository { hasSponsorshipsEnabled } } }"
> ```

## Community

💬 **Discord:** [discord.gg/DHfY62eDNN](https://discord.gg/DHfY62eDNN)

## Support this work

The ports take real time and real money to build. If you enjoy them:

- 💗 **GitHub Sponsors**: [github.com/sponsors/NextOs-Ports](https://github.com/sponsors/NextOs-Ports)
- ☕ **Ko-fi** (PayPal/card): [ko-fi.com/nextos](https://ko-fi.com/nextos)
- 🇧🇷 **PIX**: [livepix.gg/nextos](https://livepix.gg/nextos)

Every public repository here must carry both blocks above — Discord and the three support
links — plus the Sponsor toggle enabled.
