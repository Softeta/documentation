# Documentation practices in Softeta

## Why we document

These practices are primarily aimed at projects Softeta fully owns and delivers e2e, although you are welcome to suggest all or some of the documentation artifacts to all project teams, including those that are managed and led by our clients.
The main purposes of documentation are - easier onboarding of the new team members, easier search in Softeta organization GitHub, a future reference and better knowledge retention.

## What we document

Our main purpose remains for documentation to be useful and not to simply adhere to any managerial processes.

**Must-haves (for Softeta fully owned projects)**

- **App launch guide**. Described in Readme.md file in root GitHub repo directory. :link: [Example](https://github.com/dotnet-architecture/eShopOnContainers)
- **Brief description**. What is the repository for - purpose and motivation. Described in Readme.md file. :link: [Example](https://github.com/dotnet-architecture/eShopOnContainers)
- **Architecture in format C4**. Described in Readme.md or Confluence/Draw.io link in Readme.md file. :link: [Example](https://c4model.com/)
- **Deployment architecture** in free format. Including useful environment links and descriptions - monitoring, logs, etc. Described in Readme.md or Confluence/Draw.io link in Readme.md file. :link: [Example](https://d1.awsstatic.com/architecture-diagrams/ArchitectureDiagrams/amazon_supply_chain_data_lake_solution_ra.pdf?did=wp_card&trk=wp_card)

_Could haves_

- **Detail architecture**, using 4+1 or other formats. Better to add it in a separate directory in .md file format or in confluence project space. :link: [Example (Authenticated)](https://softeta.atlassian.net/wiki/spaces/POR/pages/401277141/Target+Architecture)
- **Release notes**. High-level plan and major features. Readme.md file as a separate section
- **ADR (Architecture Decision Records)**. In Readme.md or Confluence. Simple structure describing decision and motivation. :link: [Example](https://softeta.atlassian.net/wiki/spaces/POR/pages/401408101/Architecture+Decision+Record)
- **BPM (Business process model)**. In Readme.md or Confluence. Provided by Business Analyst, Product Owner or Domain expert. :link: [Example](https://www.stakeholdermap.com/bpm/example-bpm-business-process-models.html)
- **Stakeholders**. Teams and members working on the project, project managers, clients, and customers.
- **RFC (Request for comments)**. In separate document - repo or Confluence or agreed place. :link: [Example](https://github.com/brillout/rfcs/blob/main/text/0000-inject-to-stream.md)

## How we document

Our main documentation tool is GitHub repo and markdown language we aim for concise information in a single Readme.md. For ease of finding and maintaining.
For larger technical documentation we use confluence for ease of editing diagrams.

- Keep your documentation brief and concise
- Add documentation as part of your Definition Of Done or Acceptance Criteria of the user stories/sprint
- Consider the audience. Who is this for - someone new to the team/technology/project?
- Describe edge cases. There can never be enough.
- Provide examples, useful links, and a way to dig deeper.
- Documentation is communication, and communication is a skill. Read up, ask around, borrow :) if you need to.

### Examples

- [Softeta Self Service - Authenticated](https://github.com/Softeta/self-service-cms)
- [Microsoft eShop On Containers](https://github.com/dotnet-architecture/eShopOnContainers)
- [PerformanceMonitor](https://github.com/dotnet-architecture/PerformanceMonitor)

### Tooling

- draw.io
- miro.com
- plantuml.com
- grammarly.com
