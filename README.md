# Yuki Xu · AI Engineer

I build AI agents, evaluation systems, and developer tools with enough evidence
to support a real **ship / no-ship decision**.

At Thoughtworks, I work across TypeScript, React, Node.js, and Java/Spring Boot,
turning LLM workflows into tools that teams can review, measure, and deliver. My
current focus is agent evaluation, grounded generation, local-first safety, and
the engineering boundaries that make AI systems trustworthy.

## Selected work

| Project | Status | What it proves |
|---|---|---|
| [pace-triage-agent](https://github.com/yuki-uix/pace-triage-agent) | Working prototype | A two-stage insurance enquiry agent with Pydantic contracts, human review, a frozen golden set, and a 2×2 evaluation matrix. All tested configurations miss the safety bars, so the project recommends **against** production release. |
| [RepoCoach](https://github.com/yuki-uix/RepoCoach) | Completed experiment | A source-learning agent with constructive grounding and safety gates. Across 638 tests and 22 merged PRs, the project measured where agent cost actually comes from and documented why development stopped. |
| [rag-generative-ui-explorer](https://github.com/yuki-uix/rag-generative-ui-explorer) | In progress | A schema-constrained generative UI over grounded RAG evidence. On its 60-question set, dense retrieval reached 63.7% Recall@10 versus 47.6% for BM25; fusion did not beat the best single retriever. |
| [agent-cost-lab](https://github.com/yuki-uix/agent-cost-lab) | Measurement lab | Tests the difference between saving tokens and saving money. Its first offline result found a compaction payback of 18–19 turns—far beyond the locked 2–4 turn prediction. |
| [agent-eval-harness](https://github.com/yuki-uix/agent-eval-harness) | Small open-source tool | A zero-dependency, single-file regression harness that preserves paired case outcomes and uses McNemar's exact test instead of comparing two aggregate pass rates. |
| [beforeshare](https://github.com/yuki-uix/beforeshare) | Product specification | A local-first file preflight concept for people and agents, with immutable originals, review-before-mutation, independent verification, safety gates, and a pilot acceptance plan. Implementation has not started. |

## Production impact

- Helped build a project-level AI code review platform that runs on every PR
  across multiple TypeScript repositories. It caught a runtime-crash defect
  missed by both ESLint and AI-generated tests.
- Codified a multi-market rollout as an AI coding-agent workflow, reducing the
  implementation from roughly one week to half a day.
- Built an agent-configuration evaluation engine and human-in-the-loop improvement
  cycle, piloted by two delivery teams and recognized as an APAC Top 3 project at
  the Thoughtworks AI/works Hackathon.
- Migrated an evaluation worker from Express to Hono + Bun, reducing its bundle
  from 1,018 KB to 92 KB while adding 31 HTTP integration tests.

## How I work

- **Measure the real path.** Probes belong on the production call path; reconstructed
  requests and aggregate scores can hide the thing that matters.
- **Make evidence structural.** Grounding, safety, and approval boundaries should
  be enforced at system exits—not left as prompt instructions.
- **Keep failed hypotheses.** A negative result or a no-ship recommendation is useful
  when the method is reproducible and the evidence is visible.
- **Design for people around the model.** Human review, explicit partial states, and
  honest failure modes are product features, not cleanup work.

## Toolbox

**AI engineering:** Agent evaluation · RAG / embeddings · MCP · LLM APIs ·
Prompt / Skill Engineering · AI code review · CI-integrated agents

**Product engineering:** TypeScript · React · Next.js · Node.js · Hono · Python ·
Java · Spring Boot · GraphQL · Kafka

**Delivery:** Azure DevOps · CI/CD · Google Cloud · Playwright · Honeycomb

## A different route into engineering

I studied architecture before I wrote code. It trained me to see software as a
system people move through—not just a set of screens—and still shapes how I design
agent interactions, failure paths, and developer tools.

## Writing & contact

[Portfolio](https://www.yukiuix.com/) ·
[Juejin](https://juejin.cn/user/3582625834347100) ·
[LinkedIn](https://www.linkedin.com/in/kunyu-xu/) ·
[Dev.to](https://dev.to/yuki-uix) ·
[Email](mailto:yuki.uix@gmail.com)

![Profile Views](https://komarev.com/ghpvc/?username=yuki-uix&color=2b6cb0&style=flat&label=Profile+Views)

<!--
**yuki-uix/yuki-uix** is a special repository because its README.md (this file) appears on your GitHub profile.
-->
