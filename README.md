# mloda-skills

[Agent Skills](https://github.com/anthropics/skills/tree/main/spec) for [mloda](https://github.com/mloda-ai/mloda),
the declarative data-access layer for AI agents.

Each skill under [`skills/`](skills/) teaches a coding or A2A agent how to use mloda for a specific task. They
are consumed directly (drop the `SKILL.md` into an agent's skills directory) or via any catalog that indexes
this repo, such as the [Inference Gateway skills catalog](https://github.com/inference-gateway/skills).

## Skills

| Skill | Path | Description |
|-------|------|-------------|
| [`mloda`](skills/mloda/SKILL.md) | `skills/mloda/SKILL.md` | Declarative data access for AI agents: checking the mloda-registry index first, the LLM Tool Function pattern, context-window assembly, RAG feature-name chaining, and the two-phase `prepare`/`run` API. |
| [`mloda-plugins`](skills/mloda-plugins/SKILL.md) | `skills/mloda-plugins/SKILL.md` | Building mloda plugins: checking the mloda-registry index first, then FeatureGroup, ComputeFramework, and Extender classes, and the journey from writing one to publishing it to mloda-registry. |

## License

MIT, see [LICENSE](LICENSE).
