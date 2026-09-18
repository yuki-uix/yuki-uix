<h1 align="center">Kunyu Xu (Yuki)</h1>

<p align="center">
  <img src="./assets/intro-chat.svg" width="600" alt="Hey Yuki! What do you build? I started with buildings. Now I build AI agents and developer tools. What keeps you curious? The jump from it works to it is useful: building it, testing it, finding out." />
</p>

<p align="center">
  <a href="https://www.yukiuix.com/"><img src="https://img.shields.io/badge/Portfolio-7AA2F7?style=for-the-badge&logo=safari&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/kunyu-xu/"><img src="https://img.shields.io/badge/LinkedIn-BB9AF7?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:yuki.uix@gmail.com"><img src="https://img.shields.io/badge/Email-2AC3DE?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center">
  <code>agent evaluation</code> ·
  <code>grounded generation</code> ·
  <code>local-first safety</code> ·
  <code>developer experience</code>
</p>

I build AI agents, evaluation systems, and developer tools that turn LLM demos
into measurable delivery decisions. At Thoughtworks, I work across TypeScript,
React, Node.js, Python, and Java/Spring Boot—from prototypes and eval harnesses
to production workflows.

## `01 / live metrics`

<p align="center">
  <img
    src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=yuki-uix&theme=tokyonight&animation=stagger"
    alt="Yuki's live GitHub stats"
    height="180"
  />
  <img
    src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=yuki-uix&theme=tokyonight&utcOffset=8&animation=load"
    alt="Yuki's commit activity by hour in UTC plus 8"
    height="180"
  />
</p>

## `02 / systems, not demos`

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/yuki-uix/pace-triage-agent">🧪 pace-triage-agent</a></h3>
      <p>Insurance enquiry triage and reply drafting with a frozen golden set, human review queue, and 2×2 evaluation matrix.</p>
      <p><strong>The useful result:</strong> every tested configuration missed the safety bars, producing a defensible no-ship decision.</p>
      <img src="https://img.shields.io/badge/decision-NO--SHIP-F7768E?style=flat-square" alt="Decision: no ship" />
      <img src="https://img.shields.io/badge/eval-2%C3%972_matrix-7AA2F7?style=flat-square" alt="2 by 2 evaluation matrix" />
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/yuki-uix/RepoCoach">🛰️ RepoCoach</a></h3>
      <p>A source-learning agent with constructive grounding, complete exit-path safety gates, and measured agent-loop economics.</p>
      <p><strong>Validated:</strong> agent-loop economics and exit-path safety across 638 tests and 22 merged PRs, with the findings turned into reusable engineering guidance.</p>
      <img src="https://img.shields.io/badge/tests-638-9ECE6A?style=flat-square" alt="638 tests" />
      <img src="https://img.shields.io/badge/merged_PRs-22-BB9AF7?style=flat-square" alt="22 merged pull requests" />
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/yuki-uix/rag-generative-ui-explorer">🧭 RAG Generative UI Explorer</a></h3>
      <p>Grounded evidence becomes schema-constrained, interactive knowledge cards—not arbitrary model-generated UI code.</p>
      <p><strong>Measured:</strong> dense retrieval reached 63.7% Recall@10 versus 47.6% for BM25; fusion did not beat the best single retriever.</p>
      <img src="https://img.shields.io/badge/Recall%4010-63.7%25-2AC3DE?style=flat-square" alt="Recall at 10: 63.7 percent" />
      <img src="https://img.shields.io/badge/questions-60-7AA2F7?style=flat-square" alt="60 evaluation questions" />
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/yuki-uix/agent-cost-lab">⚡ agent-cost-lab</a></h3>
      <p>A measurement lab for the uncomfortable fact that fewer tokens can still mean a larger bill when cache economics change.</p>
      <p><strong>First result:</strong> one compaction paid back after 18–19 turns, not the 2–4 turns predicted before measurement.</p>
      <img src="https://img.shields.io/badge/payback-18%E2%80%9319_turns-E0AF68?style=flat-square" alt="Compaction payback: 18 to 19 turns" />
      <img src="https://img.shields.io/badge/predictions-locked_before_runs-9ECE6A?style=flat-square" alt="Predictions locked before runs" />
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/yuki-uix/agent-eval-harness"><code>agent-eval-harness</code></a>
  &nbsp;•&nbsp;
  <a href="https://github.com/yuki-uix/pr-review-agent"><code>pr-review-agent</code></a>
  &nbsp;•&nbsp;
  <a href="https://github.com/yuki-uix/beforeshare"><code>beforeshare</code></a>
</p>

## `03 / measured impact`

<table>
  <tr>
    <td align="center"><strong>≈90% less time</strong><br /><sub>multi-market rollout setup</sub></td>
    <td align="center"><strong>1,018 KB → 92 KB</strong><br /><sub>evaluation worker bundle</sub></td>
    <td align="center"><strong>31 HTTP tests</strong><br /><sub>integration coverage</sub></td>
    <td align="center"><strong>Top 3 · APAC</strong><br /><sub>Thoughtworks AI/works challenge</sub></td>
  </tr>
</table>

- Built a project-wide AI code review platform that runs on every PR across
  multiple TypeScript repositories; it caught a runtime crash missed by ESLint
  and AI-generated tests.
- Built and piloted an agent-configuration evaluation engine with two delivery
  teams, including a human-in-the-loop improvement cycle.
- Encoded multi-market rollout knowledge into a reusable coding-agent workflow,
  reducing setup from roughly one week to half a day.

## `04 / latest writing`

Fresh notes on AI delivery, design engineering, and the parts of software that
only become visible after the demo works.

<!-- BLOG-POST-LIST:START -->
- `2026-08-27` — [We Can Build an Agent in Ten Minutes — Why Does Shipping It Still Take Weeks?](https://www.yukiuix.com/en/writing/agent-demo-to-delivery)
- `2026-05-31` — [Reading baoyu-skills Source Code Through a Design Systems Lens — Three Familiar Patterns](https://mp.weixin.qq.com/s/YSckbphLlJbh6DMwzplLXg)
- `2026-05-28` — [I Thought All 9 Token Styles Were Valid — Until I Changed the IA](https://dev.to/yuki-uix/built-a-token-switcher-with-9-profiles-they-all-worked-that-made-me-ask-questions-2f6a)

<!-- BLOG-POST-LIST:END -->

<p align="right">
  <a href="https://www.yukiuix.com/en/writing">Read the full archive →</a>
</p>

## `05 / contribution city`

<p align="center">
  <a href="https://github.com/yoshi389111/github-profile-3d-contrib">
    <img
      src="https://raw.githubusercontent.com/yuki-uix/yuki-uix/profile-3d/profile-night-rainbow.svg"
      alt="Yuki's 3D GitHub contribution calendar"
      width="100%"
    />
  </a>
</p>

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/yuki-uix/yuki-uix/output/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/yuki-uix/yuki-uix/output/github-contribution-grid-snake.svg"
  />
  <img
    alt="Animated snake eating Yuki's GitHub contributions"
    src="https://raw.githubusercontent.com/yuki-uix/yuki-uix/output/github-contribution-grid-snake.svg"
    width="100%"
  />
</picture>

## `06 / toolbox`

<p align="center">
  <img
    src="https://skillicons.dev/icons?i=ts,react,nextjs,nodejs,python,java,spring,postgres,gcp,docker,git,githubactions&perline=12"
    alt="TypeScript, React, Next.js, Node.js, Python, Java, Spring, PostgreSQL, Google Cloud, Docker, Git, and GitHub Actions"
  />
</p>

<p align="center">
  <strong>AI engineering:</strong> Agent evaluation · RAG / embeddings · MCP · LLM APIs · Prompt / Skill Engineering<br />
  <strong>Product engineering:</strong> TypeScript · React · Next.js · Node.js · Hono · Python · Java · Spring Boot<br />
  <strong>Delivery:</strong> Azure DevOps · CI/CD · Google Cloud · Playwright · Honeycomb
</p>

<details>
  <summary><strong>Why architecture still matters to my engineering</strong></summary>
  <br />
  I studied architecture before I wrote code. It trained me to see software as
  a system people move through—not just a set of screens—and still shapes how I
  design agent interactions, failure paths, and developer tools.
</details>

<br />

<p align="center">
  <a href="https://www.yukiuix.com/">Portfolio</a> ·
  <a href="https://juejin.cn/user/3582625834347100">Juejin</a> ·
  <a href="https://www.linkedin.com/in/kunyu-xu/">LinkedIn</a> ·
  <a href="https://dev.to/yuki-uix">Dev.to</a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=yuki-uix&color=7aa2f7&style=flat-square&label=PROFILE+VIEWS" alt="Profile views" />
</p>
