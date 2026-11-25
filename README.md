# BolaGo: Household Waste Pickup Scheduler

DCIT 415 Advanced Software Engineering, Capstone Project P14
Team BolaGo, Group 19, University of Ghana

## What BolaGo does

Many households in Ghana have no regular refuse collection, so waste ends up burnt or dumped in drains. BolaGo helps fix this. With BolaGo:

* Households sign up, choose a pickup plan and pay with mobile money (sandbox only)
* Each truck gets a daily route list, grouped by area
* Collectors mark every stop done or missed with a photo, even with no internet
* Households track their truck live on pickup day and see the photo proof once the bin is emptied
* Missed pickups are collected again within 48 hours at no cost
* Anyone can report illegal dumping, which is checked by a moderator and sent to the assembly
* Households can flag sorted plastics for recyclers to collect

## Project documents

| Milestone | Document | Status |
|---|---|---|
| M1 Requirements | [docs/requirements.md](docs/requirements.md) | Done |
| M2 Architecture | [docs/architecture](docs/architecture) and [docs/adr](docs/adr) | Coming in Week 6 |
| M3 Code quality | Coding standards and linter setup | Coming in Week 7 |
| M6 Testing | docs/TEST_STRATEGY.md | Coming in Week 10 |
| M7 Security and privacy | docs/THREAT_MODEL.md | Coming in Week 11 |
| M8 Plan and risk | docs/PLAN.md | Coming in Week 11 |
| AI use | [docs/ai-use.md](docs/ai-use.md) | Updated every milestone |

## Screen designs

Our screen designs are in Figma: [BolaGo Screen Designs](https://www.figma.com/design/5zeK4egHMAMkdoBlExFgIc)

## Folder layout

```
docs/            requirements, architecture, ADRs, test strategy, threat model, plan, AI use
src/             application code, one folder per bounded context
tests/
  unit/
  integration/
  features/      BDD tests written in Gherkin
  e2e/
```

## How to run

Coming with M4 (Week 8), when we add the Dockerfile and docker compose setup.

## Team

| Name | Role |
|---|---|
|Nureat Sey Ahmed |Product Owner / Team Lead |
| |Architect / Tech Lead |
|Adwoa Asor Gyasi |QA Lead |
|Ansah Larbi Edward Junior |DevOps / Platform Lead|
|Francis Akyeaw Amponsah |Security & Privacy Lead |
|Irene Adu Adwoa |UX & Documentation Lead |

## How we work together

1. Never change the main branch directly.
2. Make a new branch for each task, for example `add-route-list`.
3. Push your branch and open a pull request.
4. Another team member reviews it before it is merged into main.
