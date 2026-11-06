### Michael Kasch

Engineering leader and software/cloud architect based near Munich.  
Writing Go since 2014 and running Kubernetes since 2016/17 across Azure, AWS, and GCP.

#### About the repositories here
Most of my production work lives in private corporate repositories. What you find here is personal home-lab infrastructure, hardware reverse-engineering, and quick local tooling built with very different trade-offs than my day job:
- [`sloth`](https://github.com/MyChaOS87/sloth) is my local 3-node k3s home-automation cluster. Because it runs strictly on an isolated home network and is not internet-exposed, chart versions drift and I cut corners I would never accept in production.
- [`reverseLCN`](https://github.com/MyChaOS87/reverseLCN) is a Go bridge (`lcn2mqtt`) for a proprietary smart-home serial bus I reverse-engineered for my house.
- Newer desktop utilities ([`dms-antigravity-quota`](https://github.com/MyChaOS87/dms-antigravity-quota), [`antigravity-quota`](https://github.com/MyChaOS87/antigravity-quota)) are small daily-driver tools I use myself, built mainly by raw AI one-shotting rather than the structured agentic workflows and quality gates I set up at work.

#### Some of my upstream patches
- [golang/go (`9f2c611fa7`)](https://github.com/golang/go/commit/9f2c611fa7cccfacd317b88eff14d3ba64e855ff): `time`: support parsing IANA timezones denoted only by sign and offset (e.g. `+03`, `-04`)
- [hashicorp/terraform-provider-azurerm (`#29669`)](https://github.com/hashicorp/terraform-provider-azurerm/pull/29669): `azurerm_mongo_cluster`: fix connection string exports containing `$`
- [influxdata/telegraf (`#13832`)](https://github.com/influxdata/telegraf/pull/13832): `inputs.modbus`: deprecation documentation cleanup
- [videolan/libdvbpsi (`965e42968a`)](https://code.videolan.org/videolan/libdvbpsi/-/commit/965e42968a59ae00939bcb2399451e4b7abb910c): `src/dvbpsi.c`: fix segfault when replacing the head of a DVB PSI section list

LinkedIn: [linkedin.com/in/mkasch](https://www.linkedin.com/in/mkasch/)
