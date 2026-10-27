# Darliane Ribeiro Cunha, PhD

**Port & maritime decarbonisation data scientist | Emissions inventories, ESG analytics and SDG indicators for ports**

[ribeirocunha.com](https://ribeirocunha.com) · [LinkedIn](https://www.linkedin.com/in/darlianecunha/) · [ORCID](https://orcid.org/0000-0003-2548-1237) · [Google Scholar](https://scholar.google.com/citations?user=BGRlXo0AAAAJ) · [Hugging Face](https://huggingface.co/Darliane)

I turn public maritime data (ANTAQ, EU MRV, EU ETS, Copernicus) into open datasets, models and tools that port authorities, regulators and researchers can act on. Full Professor at the Federal University of Maranhão (Brazil); postdoctoral research at Erasmus University Rotterdam (2024-2025) and the Autonomous University of Barcelona (2017-2018). Open to data, applied AI and sustainability analytics roles in the Netherlands and across Europe.

## Three flagship products

| Product | What it is | Links |
|---|---|---|
| **Brazil Port Data** | Consolidated ANTAQ statistics for 247 port installations, 2010-2026 (ODbL), served as a web hub, a citable dataset and an MCP server that lets Claude query the data with sources in every answer | [Site](https://brazilportdata.com) · [Dataset DOI](https://doi.org/10.5281/zenodo.23158267) · [MCP server](https://github.com/darlianecunha/port-emissions-mcp) |
| **DecarbPort + maritimeco2** | IMO-based at-berth CO₂ calculator for liquid bulk vessels and the tested Python library behind it (OPS-avoidable emissions) | [App](https://www.decarbport.com) · [Library](https://github.com/darlianecunha/maritimeco2) · [DOI](https://doi.org/10.5281/zenodo.20708090) |
| **SDG Port Hub** | Peer-reviewed sustainability assessment framework for ports: 84 indicators, 8 SDGs, scenario simulator (*Marine Policy*, 2025; 1st place, Inova Itaqui 2026) | [Simulator](https://sdg-port-hub-sable.vercel.app) · [Code](https://github.com/darlianecunha/atributosods) · [Paper](https://doi.org/10.1016/j.marpol.2025.106841) |

## Code worth reading

| Repository | Competency | Result |
|---|---|---|
| [port-emissions-mcp](https://github.com/darlianecunha/port-emissions-mcp) | LLM tooling (MCP) | Six tools, offline test suite, method and source cited in every answer |
| [vessel-efficiency-ml](https://github.com/darlianecunha/vessel-efficiency-ml) | Machine learning | Leakage-free scikit-learn pipeline predicting CO₂ efficiency grades (A-E) from EU MRV |
| [blueport-ai2](https://github.com/darlianecunha/blueport-ai2) | Computer vision | CLIP + linear probe, 6 waste streams, 94.6% CV accuracy on 11,451 images, runs in the browser ([demo](https://blue-port-ia.vercel.app/#try)) |
| [antaq-port-sql](https://github.com/darlianecunha/antaq-port-sql) | SQL / data engineering | DuckDB star-schema warehouse of Brazilian port operations with documented queries |
| [shipping-methane-monitor](https://github.com/darlianecunha/shipping-methane-monitor) | Regulatory analytics | Verified CH₄ and N₂O from 16,664 ships (EU MRV 2024-2025) |
| [textmining](https://github.com/darlianecunha/textmining) | NLP / bibliometrics | PDFs to VOSviewer co-occurrence networks, in the browser (method of the *Marine Policy* 2026 paper) |

More tools: [cunha-data-science.vercel.app](https://cunha-data-science.vercel.app)

## How I work

```text
question → public data → cleaning and harmonisation → statistics, ML, CV, NLP
→ open dataset with DOI → tool people use (app, library, MCP server) → decision
```

Every project ships with documented methods, stated limitations, a licence and citation metadata.

**Stack:** Python (pandas, scikit-learn, pytest) · SQL (DuckDB) · CLIP / ONNX · Claude API and MCP · Streamlit · React / TypeScript · Vercel

## Selected publications

- Cunha, D. R., Oliveira, C. B. M., Santos, V. R. P., & Pinheiro, R. E. P. (2026). At-berth CO2 emissions at a Brazilian bulk-heavy multi-cargo port: Drivers, shore power potential and implications for port decarbonisation management. *Case Studies on Transport Policy*, 26, 102005. [doi:10.1016/j.cstp.2026.102005](https://doi.org/10.1016/j.cstp.2026.102005)
- Cunha, D. R., & Pereira, N. N. (2026). Mapping ESG evolution in Brazilian ports: A text-mining approach to sustainability reporting. *Marine Policy*, 195, 107287. [doi:10.1016/j.marpol.2026.107287](https://doi.org/10.1016/j.marpol.2026.107287)
- Cunha, D. R., Costa, M. D. C., Oliveira, C. B. M., & Pereira, N. N. (2025). SDG attributes: A sustainability assessment framework for Brazilian ports. *Marine Policy*, 181, 106841. [doi:10.1016/j.marpol.2025.106841](https://doi.org/10.1016/j.marpol.2025.106841)

20 peer-reviewed articles (6 Scopus Q1), h-index 11, reviewer for 26 journals. Full list on [ORCID](https://orcid.org/0000-0003-2548-1237).

## Currently building

Weekly newsletter [Port Decarbonisation Data](https://www.linkedin.com/in/darlianecunha/) · LLM evaluation against human coders on ESG reports · agents that combine MCP servers with open datasets.
