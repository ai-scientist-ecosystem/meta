# AI Scientist Ecosystem (Meta Repo)

This meta repository coordinates the multi-repo architecture for the AI Scientist Ecosystem.

## Repositories

| Module | Description | Link |
|--------|-------------|------|
| **core** | Foundational agent framework, plugin interfaces | [ai-scientist-ecosystem/core](https://github.com/ai-scientist-ecosystem/core) |
| **workflow** | Experiment orchestration, pipeline engine, scheduling | [ai-scientist-ecosystem/workflow](https://github.com/ai-scientist-ecosystem/workflow) |
| **knowledge** | Knowledge ingestion, retrieval, embeddings, semantic stores | [ai-scientist-ecosystem/knowledge](https://github.com/ai-scientist-ecosystem/knowledge) |
| **frontend** | Dashboard UI (Next.js + TypeScript), progress visualization | [ai-scientist-ecosystem/frontend](https://github.com/ai-scientist-ecosystem/frontend) |
| **infra** | Infrastructure as Code (Terraform), deployment automation | [ai-scientist-ecosystem/infra](https://github.com/ai-scientist-ecosystem/infra) |
| **docs** | Centralized documentation and planning materials | [ai-scientist-ecosystem/docs](https://github.com/ai-scientist-ecosystem/docs) |

## Branching Model
- main: Stable integration.
- feature/*: New capabilities per repository.
- fix/*: Bug/security patches.
- docs/*: Documentation changes.

## Pull Request Flow
1. Create feature branch.
2. Conventional commits (feat:, fix:, docs:, chore:, refactor:).
3. PR with linked issue and checklist.
4. Automated CI must pass before merge.

## Governance
CODEOWNERS file assigns review responsibility. Use GitHub Projects for backlog, labeling scheme for prioritization.

## Next Steps
1. Populate module-specific tech stacks.
2. Convert .docx to Markdown gradually.
3. Define initial CI workflows per repository.

## License
MIT (see LICENSE).
