### Michael Kasch

Engineering leader and software/cloud architect near Munich.
Writing Go since 2014, running Kubernetes in production since 2016/17, across Azure, AWS, and GCP.

#### About the repositories here
My production work lives in private corporate repositories. This profile is my workshop: home-lab infrastructure, hardware reverse-engineering, and small tools I use every day.

- [`sloth`](https://github.com/MyChaOS87/sloth): GitOps-managed 3-node HA k3s cluster for home automation (Argo CD, Helm, Sealed Secrets, Longhorn, Keycloak OIDC). Deliberately a home lab: it runs on an isolated network, so I trade production rigor for fast experimentation.
- [`reverseLCN`](https://github.com/MyChaOS87/reverseLCN): Go bridge (`lcn2mqtt`) for a proprietary smart-home bus, reverse-engineered without vendor documentation.
- [`smallContainersWithGo`](https://github.com/MyChaOS87/smallContainersWithGo): step-by-step walkthrough from a 390 MB Go image to a hardened, unprivileged 7 MB scratch container, prepared for an internal tech session.
- [`antigravity-quota`](https://github.com/MyChaOS87/antigravity-quota) / [`dms-antigravity-quota`](https://github.com/MyChaOS87/dms-antigravity-quota): small desktop utilities, built as quick AI-generated experiments. At work, I use structured agentic workflows with documented quality gates instead.

#### Upstream contributions
- [golang/go `9f2c611fa7`](https://github.com/golang/go/commit/9f2c611fa7cccfacd317b88eff14d3ba64e855ff): `time`: parse IANA timezones denoted only by sign and offset (e.g. `+03`, `-04`), found while running broadcast playout across 36 global locations
- [hashicorp/terraform-provider-azurerm #29669](https://github.com/hashicorp/terraform-provider-azurerm/pull/29669): `azurerm_mongo_cluster`: fix exported connection strings containing `$`
- [influxdata/telegraf #13832](https://github.com/influxdata/telegraf/pull/13832): `inputs.modbus`: deprecation documentation
- [videolan/libdvbpsi `965e42968a`](https://code.videolan.org/videolan/libdvbpsi/-/commit/965e42968a59ae00939bcb2399451e4b7abb910c): fix a segfault when replacing the head of a DVB PSI section list

[LinkedIn](https://www.linkedin.com/in/mkasch/)
