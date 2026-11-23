# Awesome-Code-Generation-Automated-Scaffolding

<FollowUp>
Would you like to **add a dedicated section for open-source AST codemods & database schema/ORM generators** (like `jscodeshift`, `Prisma`, `Drizzle Kit`, `sqlc`) or **generate the next `README.md` repository**?
</FollowUp>
# Awesome-Code-Generation-Automated-Scaffolding

# Awesome Cloud Storage & Decentralized Drive Sync 🌟

> **Top Cloud Storage Decentralized Drive Sync (Opensource)**  
> A curated list of the best cloud storage, file synchronization, and decentralized drive solutions — with a strong focus on **open-source** and self-hostable alternatives.  
> 🌟 **Star if you like it!** 🌟

Cloud storage and file sync services keep documents, photos, and data accessible across devices. Commercial platforms such as Dropbox, Google Drive, OneDrive, MEGA, and Tresorit dominate the hosted space, while a mature open-source ecosystem offers full data ownership through self-hosted servers (Nextcloud, Seafile), peer-to-peer sync (Syncthing), and decentralized networks (IPFS, Sia, Storj-related projects).

This list prioritizes **open-source GitHub projects and self-hostable tools** while keeping SaaS/hosted platforms clearly separated.

## Table of Contents

- [SaaS / Hosted Platforms](#saas--hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS / Hosted Platforms

These are popular commercial cloud storage and encrypted drive services (closed-source / hosted):

- **[Dropbox](https://www.dropbox.com/)** — Classic file sync and sharing platform with strong collaboration features.
- **[Google Drive](https://drive.google.com/)** — Integrated cloud storage tightly coupled with Google Workspace.
- **[OneDrive](https://www.microsoft.com/en-us/microsoft-365/onedrive/online-cloud-storage)** — Microsoft’s cloud storage, deeply integrated with Windows and Microsoft 365.
- **[Box](https://www.box.com/)** — Enterprise-focused content management and collaboration platform.
- **[pCloud](https://www.pcloud.com/)** — European cloud storage with client-side encryption options and lifetime plans.
- **[MEGA](https://mega.nz/)** — Privacy-oriented cloud storage with end-to-end encryption and generous free tiers.
- **[Sync.com](https://www.sync.com/)** — Canadian zero-knowledge encrypted cloud storage.
- **[Icedrive](https://icedrive.net/)** — Modern cloud storage with strong encryption and competitive pricing.
- **[Tresorit](https://tresorit.com/)** — High-security end-to-end encrypted cloud storage aimed at businesses and privacy-conscious users.
- **[Nextcloud Hub](https://nextcloud.com/)** — Hosted/managed offering of the popular open-source platform (commercial support available).

## Open-Source GitHub Projects

Open-source alternatives and self-hostable tools for file synchronization, personal clouds, and decentralized storage. These give you full control over your data.

### Self-Hosted Personal Cloud & File Sync

- **[nextcloud/server](https://github.com/nextcloud/server)** (Nextcloud)  
  The leading open-source personal cloud platform. File sync & share, calendar, contacts, office suites (Collabora/OnlyOffice), Talk, and a large app ecosystem. Closest full-featured alternative to Google Drive / Dropbox. AGPL-3.0.

- **[haiwen/seafile](https://github.com/haiwen/seafile)** (Seafile)  
  High-performance open-source file sync and share platform. Excellent delta sync, library-based organization, and strong reliability with large numbers of files. Community Edition is fully open-source.

- **[owncloud/core](https://github.com/owncloud/core)** (ownCloud)  
  Mature open-source file sync and collaboration platform. Focus on enterprise features, sharing, and integration. AGPL.

- **[pydio/cells](https://github.com/pydio/cells)** (Pydio Cells)  
  Modern open-source content collaboration platform with strong sharing and external collaboration capabilities.

### Peer-to-Peer & Lightweight Sync

- **[syncthing/syncthing](https://github.com/syncthing/syncthing)**  
  Continuous peer-to-peer file synchronization. No central server required — devices sync directly with each other. Extremely lightweight, private, and reliable. MPL-2.0. One of the most popular open-source sync tools.

- **rclone**  
  Command-line program to manage files on cloud storage. Supports dozens of providers (including S3-compatible, Google Drive, Dropbox, etc.) and can be used for backups, mounts, and synchronization.

### Decentralized & Distributed Storage

- **IPFS (InterPlanetary File System)** — [ipfs/kubo](https://github.com/ipfs/kubo) and related projects  
  Content-addressed, peer-to-peer distributed file system. Foundation for many decentralized storage solutions.

- **Sia / SiaFoundation projects**  
  Decentralized cloud storage network with open-source host and renter software. Files are encrypted, erasure-coded, and distributed across hosts.

- **Storj-related open-source components and connectors**  
  Decentralized object storage with S3-compatible APIs and community tools for integration with IPFS and other systems.

- **Filecoin ecosystem tools**  
  Incentivized decentralized storage layer often used together with IPFS for persistent, verifiable storage.

### Other Notable Open-Source Projects

- **[spacedriveapp/spacedrive](https://github.com/spacedriveapp/spacedrive)**  
  Open-source cross-platform file explorer powered by a virtual distributed filesystem written in Rust. Aims to unify local and remote storage in one interface.

- **[spacesdrive/twiligent](https://github.com/spacesdrive/twiligent)**  
  Self-hosted analytics and publishing dashboard (YouTube + Instagram focus). Included as referenced; demonstrates privacy-first, locally controlled data tools in a related domain.

- Additional tools such as SFTPGo, SeaweedFS, MinIO (S3-compatible object storage), and various WebDAV/SFTP servers that complement personal cloud setups.

> **Tip**: For a full Google Drive / Dropbox-style experience self-host **Nextcloud**. For maximum sync speed and reliability with large libraries try **Seafile**. For pure device-to-device sync with zero central server use **Syncthing**. Decentralized options (IPFS + Filecoin/Sia/Storj) suit censorship resistance and long-term archival use cases.

## How to Contribute

Contributions are welcome and encouraged!

1. Fork the repository
2. Add a new tool under the appropriate section (keep SaaS and Open-Source strictly separate)
3. Use the same format: **Name** — short description + key features + license/link
4. Prefer actively maintained projects with clear documentation, security track records, and preferably cross-platform clients
5. Submit a Pull Request

Please keep descriptions neutral and factual. Open-source and self-hostable projects are the primary focus of this list. Clearly note any enterprise editions or dual-licensing.

## Disclaimer

This is a community-curated list for informational and educational purposes only.  
Inclusion does not constitute an endorsement.  

Self-hosting means you are responsible for backups, security updates, encryption key management, and availability. Decentralized networks involve additional complexity (tokens, hosts, retrieval). Always review licenses, threat models, and operational requirements before migrating critical data.

Commercial services offer convenience and support at the cost of trusting a third party with your files. Choose according to your privacy needs, technical ability, and budget.

---

**Made with ❤️ for the open-source privacy and self-hosting community**  
If this list helped you, please ⭐ the repo!
