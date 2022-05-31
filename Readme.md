# Documentation practices in Softeta

## Why we document

These practices are primarly aimed at projects Softeta fully owns and delivers e2e, although you are welcome to suggest all or some of the documentation artifacts to all project teams, including those that are managed and lead by our clients.
The main purposes of documentation are - easier onboarding of the new team members, easier search in Softeta organization github, a future reference and better knowledge retention.

## What we document

Following documentation artifacts are useful:

Must haves (for Softeta fully owned projects)

- **App launch guide**. Described in Readme.md file in root github repo directory.
- **Brief description** what is the repository for - purpose and motivation. Described in Readme.md file.
- **Architecture in format C4**. Described in Readme.md or Confluence/Draw.io link in Readme.md
- **Deployment architecture** in free format. Including useful environment links and description - monitoring, logs, etc. Described in Readme.md or Confluence/Draw.io link in Readme.md

Could haves

- **Detail architecture**, using 4+1 or other formats. Better to add it in separate directory in .md file format or in confluence project space.
- **Release notes**. High-level plan and major features. Readme.md file as a separate section
- **ADR (Architecture Decision Records)**. In Readme.md or Confluence. Simple structure describing decision and motivation.
- **BPM (Business process model)**. In Readme.md or Confluence. Provided by Business Analys, Product Owner or Domain expert.
- **Stakeholders**. Teams and members working on the project, project managers, clients, customers.
- **RFC (Request for comments)**. In separate document - repo or Confluence or agreed place.

## How we document

Our main documentation tool is github repo and markdown language we aim for concise information in single Readme.md. For ease of finding and maintaining.
For larger technical documentation we use confluence for ease of editing diagrams.

### Examples

Softeta Self Service
[Microsoft eShop On Containers](https://github.com/dotnet-architecture/eShopOnContainers)

### Templates
