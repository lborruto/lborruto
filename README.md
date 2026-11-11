## Luca Borruto

**DevOps / Platform Engineer, based near Geneva.**<br>
<sub>Archamps, France · 20 min from Geneva · French (native), English (fluent)</sub>

[luca-borruto.com](https://luca-borruto.com) · [CV](https://luca-borruto.com/luca-borruto-cv.pdf) · [LinkedIn](https://www.linkedin.com/in/lborruto/) · [Notes](https://docs.luca-borruto.com)

At [Agicap](https://agicap.com) I built and run the internal platform: Kubernetes (GKE, AKS),
Terraform applied through Atlantis, GitOps with ArgoCD, Vault, Prometheus, Grafana and Loki. I also
build the tools that run on it. Before that, six years in IT: system administration, infrastructure
projects on a SEVESO-classified industrial site, and technical support.

<table>
  <tr>
    <td align="center" width="25%"><b>8 yrs</b><br><sub>in IT</sub></td>
    <td align="center" width="25%"><b>49</b><br><sub>apps on the platform</sub></td>
    <td align="center" width="25%"><b>&lt; 90 s</b><br><sub>to roll back</sub></td>
    <td align="center" width="25%"><b>2,871</b><br><sub>Okta resources in Git</sub></td>
  </tr>
</table>

### At work

- **Kubernetes platform with GitOps CI/CD.** GKE with Terraform, Atlantis, ArgoCD and Vault.
  Rollback went from ~2 h to under 90 s, and every infrastructure change is reviewed by pull request.
- **Kubernetes operator for Okta.** Accounts, groups and applications are declared in Git and
  applied by the operator, with guards against mass deletion and a preview environment.
- **Alfred, an LLM IT-support bot on Slack.** 766 messages from 104 people in its first 30 days
  company-wide; only 12% became tickets.
- **Telephony migration on a SEVESO high-threshold site** (Elkem Silicones). VoIP for 570
  employees, with no safety-related downtime.

The full case studies are on [luca-borruto.com](https://luca-borruto.com).

### Side projects

<table>
  <tr>
    <td width="46%"><a href="https://github.com/lborruto/kelvin"><img src="https://raw.githubusercontent.com/lborruto/kelvin/main/docs/screenshots/home.webp" alt="Kelvin's home screen: each room with its temperature, this month's cost and today's schedule"></a></td>
    <td valign="top">
      <a href="https://github.com/lborruto/kelvin"><b>Kelvin</b></a><br>
      Self-hosted control for Cozytouch electric radiators: rooms, weekly schedules, Linky energy
      history and what it costs on your tariff, with a read-only MCP server for Claude.<br>
      <sub>Python · PWA · Docker</sub>
    </td>
  </tr>
  <tr>
    <td width="46%"><a href="https://github.com/lborruto/indexof"><img src="https://raw.githubusercontent.com/lborruto/indexof/main/docs/screenshots/listing.webp" alt="indexof's listing: nginx's Index of / with download, zip, rename and delete links"></a></td>
    <td valign="top">
      <a href="https://github.com/lborruto/indexof"><b>indexof</b></a><br>
      A file server for the home network: nginx's "Index of /" plus login, uploads, search, zips
      and direct play.<br>
      <sub>nginx · Shell · Docker</sub>
    </td>
  </tr>
</table>

- **[jackstream](https://github.com/lborruto/jackstream)**: a Stremio addon that streams torrents
  found by your Jackett. One 20 MB Go container.
- **[mcp-leclerc-drive](https://github.com/lborruto/mcp-leclerc-drive)**: an MCP server that fills an
  E.Leclerc Drive cart from Claude, through a real Chrome. Hardened continuation of an unmaintained
  project. TypeScript.

### For fun

- **[Pokémon Fulldex](https://github.com/mamesj/pokemon-fulldex)** (contributor): the Pokémon DS and
  GBA games in widescreen at 60 fps, on PC, Mac, handhelds, phones and Switch. French ROM support:
  tested on the original seven DS games, added the missing weather functions. C++.
- **Black Ops II Zombies mods** (Plutonium T6): [Magmagat for Mob of the Dead](https://github.com/lborruto/t6_motd_magmagat)
  and [Dead Frequency](https://github.com/lborruto/t6_dead_frequency), a new Easter egg for TranZit.
  GSC.

### Toolbox

<table>
  <tr><td><b>Cloud &amp; platform</b></td><td>Kubernetes, GCP, Azure, AWS, Docker, vSphere</td></tr>
  <tr><td><b>IaC &amp; delivery</b></td><td>Terraform, Atlantis, ArgoCD, Helm, GitHub Actions</td></tr>
  <tr><td><b>Observability</b></td><td>Prometheus, Grafana, Loki, ELK</td></tr>
  <tr><td><b>Identity &amp; security</b></td><td>Okta, Vault, Intune, Apple Business Manager, FreeRADIUS</td></tr>
  <tr><td><b>Networking</b></td><td>Cisco Meraki, Fortinet</td></tr>
  <tr><td><b>Languages</b></td><td>Go, Python, TypeScript, Bash, Node.js</td></tr>
</table>
