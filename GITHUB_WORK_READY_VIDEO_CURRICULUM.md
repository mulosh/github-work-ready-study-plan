# GitHub Work-Ready Video Curriculum (16 Weeks)

**Learner:** mulosh  
**Start date:** October 5, 2026  
**Duration:** 16 weeks  
**Weekly commitment:** 8–12 hours (target split: ~30% learning, ~70% hands-on practice)

> This curriculum turns the original study plan into a lesson-by-lesson sequence you can follow without redesigning the program yourself.

## How to use this curriculum

1. Complete each week in order.
2. For each lesson: study first, then do the hands-on task in the listed repository.
3. Save all evidence (commits, PRs, issues, workflow logs, screenshots, releases, notes).
4. Finish each week with the Sunday deliverable.
5. Keep the 30/70 split: short structured learning + larger practical execution.

## Video-source legend

- **[Official]** GitHub Docs, GitHub Skills, GitHub CLI docs, Git docs, Open Source Guides, Microsoft Learn GitHub training, Microsoft certification pages.
- **[Supplementary]** Reputable third-party video tutorials used only where official resources are not enough for a beginner walkthrough.
- **Important accuracy note:** Microsoft Learn items in this plan are labeled as **interactive/video-based learning** (not all are literal videos).

---

## Week 1 (Oct 5–11, 2026) — Git/GitHub setup and first commits

**Weekly objective:** Understand Git vs GitHub, clone a repo, and produce clean commit history in `stargazers-log`.

| Lesson | Est. time | Video / interactive link | What to learn | Hands-on activity | Evidence/output to save | Done |
|---|---:|---|---|---|---|---|
| **L01 — GitHub Foundations kickoff** | 90 min | [GitHub Foundations learning path (interactive/video-based)](https://learn.microsoft.com/en-us/training/paths/github-foundations/) **[Official]** | Platform basics, repositories, commits, collaboration vocabulary | In `stargazers-log`, create `notes/week1-learning-log.md` with key terms | Commit URL + screenshot of repo tree | - [ ] |
| **L02 — Hello World workflow** | 75 min | [GitHub Hello World walkthrough](https://docs.github.com/en/get-started/start-your-journey/hello-world) **[Official]** | Branch → commit → PR flow | Create branch `docs/week1-hello-world`; make small README or content edit; open draft PR | Draft PR URL + branch screenshot | - [ ] |
| **L03 — Core Git command loop** | 120 min | [Git reference docs](https://git-scm.com/docs) **[Official]** + [GitHub Skills](https://skills.github.com/) **[Official]** | `status`, `diff`, `add`, `commit`, `push`, `pull`, `log` | Make 3 meaningful commits on feature branch (no direct commits to `main`) | 3 commit SHAs + terminal screenshot | - [ ] |
| **L04 — Remotes and tracking** | 90 min | [GitHub Docs home](https://docs.github.com/) **[Official]** | `origin`, upstream tracking, safe pull/push habits | Push branch with `-u`, verify remote tracking, sync with latest remote changes | `git remote -v` output + `git branch -vv` screenshot | - [ ] |

**Sunday deliverable:** 4+ meaningful commits this week, at least 1 draft PR, and zero direct commits to `main`.

---

## Week 2 (Oct 12–18, 2026) — Branches, commit quality, and history readability

**Weekly objective:** Build branching discipline and complete at least 10 meaningful commits total across Weeks 1–2.

| Lesson | Est. time | Video / interactive link | What to learn | Hands-on activity | Evidence/output to save | Done |
|---|---:|---|---|---|---|---|
| **L05 — GitHub Flow in practice** | 90 min | [GitHub flow](https://docs.github.com/en/get-started/using-github/github-flow) **[Official]** | Small branch lifecycle and review-ready changes | Create branches `feature/page-layout` and `fix/mobile-layout`; commit focused updates | Branch list + commit list screenshot | - [ ] |
| **L06 — Commit-message quality** | 75 min | [Git docs reference](https://git-scm.com/docs) **[Official]** | Writing clear, scoped commit messages | Rewrite local WIP history before push (squash/fixup locally if needed), then push clean sequence | Screenshot of `git log --oneline` with readable messages | - [ ] |
| **L07 — Skills practice sprint** | 120 min | [GitHub Skills](https://skills.github.com/) **[Official]** | Repetition of PR and branch workflows | Complete one branch/PR-style Skills exercise; mirror pattern in `stargazers-log` | Course completion screenshot + mirrored PR URL | - [ ] |
| **L08 — Sync and recover basics** | 90 min | [Git docs](https://git-scm.com/docs) **[Official]** | Safe `pull`, resolving simple local divergence, diff-based verification | Perform pull/update cycle on active branch and document command sequence in repo notes | Notes file commit + terminal output screenshot | - [ ] |

**Sunday deliverable:** Reach at least **10 meaningful commits** total (Weeks 1–2) and maintain no direct commits to `main`.

---

## Week 3 (Oct 19–25, 2026) — Issues and pull requests

**Weekly objective:** Convert work requests into linked issues and PRs, including draft PR usage.

| Lesson | Est. time | Video / interactive link | What to learn | Hands-on activity | Evidence/output to save | Done |
|---|---:|---|---|---|---|---|
| **L09 — Issues as work contracts** | 90 min | [About issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues) **[Official]** | Problem statements, acceptance criteria, labels | Open 2 issues in `stargazers-log` with acceptance criteria | 2 issue URLs | - [ ] |
| **L10 — Pull request structure** | 120 min | [Pull requests docs](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests) **[Official]** | PR summaries, linked issues, testing notes | Open 2 PRs linked to issues using a consistent PR template block | 2 PR URLs with linked issue references | - [ ] |
| **L11 — Draft PR workflow** | 75 min | [GitHub Docs](https://docs.github.com/) **[Official]** | Draft-to-ready transitions and early feedback | Open 1 draft PR, request feedback, then mark ready | Timeline screenshot showing draft → ready | - [ ] |
| **L12 — Review basics** | 90 min | [Code review docs](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests) **[Official]** | Review comments, revisions, approvals | Perform one self-review checklist and one revision push on PR branch | Before/after PR diff screenshot + revision commit SHA | - [ ] |

**Sunday deliverable:** Minimum cumulative progress by end of Week 3: 2 linked issues and 2 PRs underway/merged.

---

## Week 4 (Oct 26–Nov 1, 2026) — Merge strategies, conflicts, and recovery tools

**Weekly objective:** Complete required collaboration evidence: 4 merged PRs, 4 linked issues, deliberate conflict, revert/restore/reflog practice.

| Lesson | Est. time | Video / interactive link | What to learn | Hands-on activity | Evidence/output to save | Done |
|---|---:|---|---|---|---|---|
| **L13 — Merge strategies** | 90 min | [Pull requests docs](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests) **[Official]** | Squash vs merge commit vs rebase merge concepts | Merge PRs using at least two different strategies (where allowed) | Merge method screenshots in PR timeline | - [ ] |
| **L14 — Deliberate merge conflict lab** | 120 min | [Managing merge conflicts](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts) **[Official]** | Conflict identification and manual resolution | Create intentional conflict in `stargazers-log`; resolve and merge | Conflict screenshot + resolution commit | - [ ] |
| **L15 — Revert, restore, reflog safety net** | 120 min | [Git reference docs](https://git-scm.com/docs) **[Official]** | Undo methods and history recovery mindset | Revert one commit, use restore on file change, inspect reflog | Command transcript + reverted commit URL | - [ ] |
| **L16 — README and conflict note polish** | 90 min | [GitHub Docs](https://docs.github.com/) **[Official]** | Documentation of process and troubleshooting | Complete README update + `docs/conflict-resolution-note.md` | README PR URL + conflict note file link | - [ ] |

**Sunday deliverable:** Hit all Weeks 3–4 targets: 4 merged PRs, 4 linked issues, deliberate conflict, reverted commit, README update, conflict-resolution note.

---

## Week 5 (Nov 2–8, 2026) — Start `github-workflow-lab` and repo standards

**Weekly objective:** Initialize professional repository structure and templates.

| Lesson | Est. time | Video / interactive link | What to learn | Hands-on activity | Evidence/output to save | Done |
|---|---:|---|---|---|---|---|
| **L17 — Repo governance baseline** | 90 min | [GitHub Skills](https://skills.github.com/) **[Official]** | Team workflow conventions and contribution flow | Create `github-workflow-lab` and baseline README/project goals | Initial repo URL + first commit SHA | - [ ] |
| **L18 — Issue and PR templates** | 120 min | [GitHub Docs](https://docs.github.com/) **[Official]** | Structured intake for bugs/features/PRs | Add issue templates and PR template in `.github/` | Template file links + sample issue/PR created from templates | - [ ] |
| **L19 — Contribution and conduct policies** | 120 min | [Open Source Guides](https://opensource.guide/) **[Official]** | Contributor expectations and community norms | Add `CONTRIBUTING.md` and `CODE_OF_CONDUCT.md` | File links + issue referencing contributor rules | - [ ] |
| **L20 — Security and changelog basics** | 90 min | [GitHub security docs](https://docs.github.com/en/code-security) **[Official]** | Security reporting path and release-note discipline | Add `SECURITY.md` and `CHANGELOG.md` | File links + PR URL adding docs | - [ ] |

**Sunday deliverable:** `github-workflow-lab` created with templates + governance docs committed through PR workflow.

---

## Week 6 (Nov 9–15, 2026) — Labels, milestones, and Projects board

**Weekly objective:** Build planning system and issue triage discipline.

| Lesson | Est. time | Video / interactive link | What to learn | Hands-on activity | Evidence/output to save | Done |
|---|---:|---|---|---|---|---|
| **L21 — Label taxonomy** | 90 min | [Issues docs](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues) **[Official]** | Priority/type labels and triage clarity | Create label set (`type`, `priority`, `status`) in `github-workflow-lab` | Label screenshot + naming rationale note | - [ ] |
| **L22 — Milestones and planning horizon** | 90 min | [Projects docs](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects) **[Official]** | Scope grouping and release planning | Create milestone and assign issues to it | Milestone URL + issue links | - [ ] |
| **L23 — Projects board workflow** | 120 min | [Projects docs](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects) **[Official]** | Backlog → Ready → In progress → In review → Done lifecycle | Create board with required columns and add work items | Board screenshot + item movement evidence | - [ ] |
| **L24 — Throughput drill** | 120 min | [GitHub Skills](https://skills.github.com/) **[Official]** | Breaking work into trackable slices | Open enough issues/PRs to move toward Week 7 targets | Count snapshot: issues + PRs + milestone progress | - [ ] |

**Sunday deliverable:** Active project board and milestone in use with clear issue/label workflow.

---

## Week 7 (Nov 16–22, 2026) — CODEOWNERS, branch protection, releases

**Weekly objective:** Simulate protected team workflow and ship a release.

| Lesson | Est. time | Video / interactive link | What to learn | Hands-on activity | Evidence/output to save | Done |
|---|---:|---|---|---|---|---|
| **L25 — CODEOWNERS and review routing** | 90 min | [About CODEOWNERS](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners) **[Official]** | Automatic reviewer ownership model | Add `CODEOWNERS` and verify request behavior on PR | PR screenshot showing auto-requested reviewer(s) | - [ ] |
| **L26 — Protected main and required checks** | 120 min | [Rulesets / branch protection](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-rulesets/about-rulesets) **[Official]** | Branch protection policies and quality gates | Configure protected `main` with required reviews/checks | Settings screenshot + blocked direct push evidence | - [ ] |
| **L27 — Review-cycle rehearsal** | 120 min | [Code review docs](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests) **[Official]** | Review feedback loops and PR revision discipline | Complete 3 review cycles and revise at least one PR after comments | PR conversation screenshots + revision commits | - [ ] |
| **L28 — Release creation** | 90 min | [Releases docs](https://docs.github.com/en/repositories/releasing-projects-on-github/about-releases) **[Official]** | Tagging, release notes, milestone closure | Publish at least one release with notes linked to merged PRs | Release URL + changelog reference | - [ ] |

**Sunday deliverable:** Reach Weeks 5–7 targets (10 issues, 6 PRs, 3 review cycles, 1 revised PR, 1 completed milestone, 1 release).

---

## Week 8 (Nov 23–29, 2026) — GitHub Pages and web quality

**Weekly objective:** Deploy `stargazers-log` publicly with accessibility/responsiveness improvements.

| Lesson | Est. time | Video / interactive link | What to learn | Hands-on activity | Evidence/output to save | Done |
|---|---:|---|---|---|---|---|
| **L29 — Pages publishing setup** | 120 min | [GitHub Pages docs](https://docs.github.com/en/pages) **[Official]** | Pages source configuration and deployment lifecycle | Enable Pages in `stargazers-log` and publish site | Live URL + Pages settings screenshot | - [ ] |
| **L30 — Responsive and semantic HTML improvements** | 120 min | [GitHub Skills](https://skills.github.com/) **[Official]** + [Git docs](https://git-scm.com/docs) **[Official]** | Semantic structure, mobile readability, clean change sets | Improve layout, headings, navigation, metadata | Before/after screenshots + PR URL | - [ ] |
| **L31 — Accessibility pass** | 90 min | [GitHub Docs](https://docs.github.com/) **[Official]** | Accessible link text and basic usability checks | Audit key pages and fix link text/structure | Checklist in repo + evidence screenshots | - [ ] |
| **L32 — Deployment troubleshooting note** | 90 min | [Pages docs](https://docs.github.com/en/pages) **[Official]** | Diagnosing failed builds/deployments | Document one deployment issue and fix in `docs/deployment-troubleshooting.md` | Troubleshooting doc link + workflow/build evidence | - [ ] |

**Sunday deliverable:** Working public Pages site, README live link, deployment guide, and one troubleshooting write-up.

---

## Week 9 (Nov 30–Dec 6, 2026) — Actions fundamentals in `github-actions-lab`

**Weekly objective:** Build core CI workflows and understand triggers/jobs/steps/runners.

| Lesson | Est. time | Video / interactive link | What to learn | Hands-on activity | Evidence/output to save | Done |
|---|---:|---|---|---|---|---|
| **L33 — Actions path part 1** | 120 min | [Automate your workflow with GitHub Actions (Part 1)](https://learn.microsoft.com/en-us/training/paths/automate-your-workflow-with-github-actions-part-1-of-2/) **[Official]** | Workflow structure and trigger model | Initialize `github-actions-lab`; add basic workflow with `push` and `pull_request` triggers | Workflow file URL + successful run screenshot | - [ ] |
| **L34 — Workflow syntax essentials** | 120 min | [Workflow syntax docs](https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions) **[Official]** | Jobs, steps, matrix, permissions | Create PR validation workflow with explicit least-privilege permissions | YAML diff + run URL | - [ ] |
| **L35 — HTML + link validation jobs** | 120 min | [GitHub Actions docs](https://docs.github.com/en/actions) **[Official]** | Multi-job pipelines and failure signals | Add HTML validation and link-check workflows | 2 workflow files + passing run links | - [ ] |
| **L36 — Runner and artifact basics** | 90 min | [Actions quickstart](https://docs.github.com/en/actions/quickstart) **[Official]** | Hosted runners and artifact upload concept | Add artifact upload step to one workflow | Artifact screenshot + run URL | - [ ] |

**Sunday deliverable:** 3+ workflow files with at least one successful PR-check run in `github-actions-lab`.

---

## Week 10 (Dec 7–13, 2026) — Debugging, deliberate failures, and CI/CD design

**Weekly objective:** Analyze failures deeply and complete required Actions deliverables.

| Lesson | Est. time | Video / interactive link | What to learn | Hands-on activity | Evidence/output to save | Done |
|---|---:|---|---|---|---|---|
| **L37 — Actions path part 2** | 120 min | [Automate your workflow with GitHub Actions (Part 2)](https://learn.microsoft.com/en-us/training/paths/automate-your-workflow-with-github-actions-part-2-of-2/) **[Official]** | Reusable workflows, advanced automation patterns | Add reusable workflow or composite action in lab repo | Workflow/action file links + run URL | - [ ] |
| **L38 — Failure analysis lab 1** | 120 min | [GitHub Actions docs](https://docs.github.com/en/actions) **[Official]** | Root-cause workflow debugging from logs | Intentionally break one workflow; document failure, fix, prevention | Failure report #1 with log snippets | - [ ] |
| **L39 — Failure analysis lab 2** | 120 min | [GitHub Actions docs](https://docs.github.com/en/actions) **[Official]** | Repeatable troubleshooting discipline | Intentionally break second workflow and remediate | Failure report #2 + fixed run link | - [ ] |
| **L40 — CI/CD process mapping** | 90 min | [GitHub Actions docs](https://docs.github.com/en/actions) **[Official]** | End-to-end pipeline communication | Create CI/CD diagram for lab workflows and trigger flow | Diagram file/image + README embed | - [ ] |

**Sunday deliverable:** Meet Weeks 9–10 targets: 5+ workflow files, 3 successful PR checks, 2 documented failures/fixes, 1 artifact, 1 CI/CD diagram.

---

## Week 11 (Dec 14–20, 2026) — Security foundations and repository governance

**Weekly objective:** Implement least-privilege and policy controls.

| Lesson | Est. time | Video / interactive link | What to learn | Hands-on activity | Evidence/output to save | Done |
|---|---:|---|---|---|---|---|
| **L41 — Security feature overview** | 120 min | [GitHub code security docs](https://docs.github.com/en/code-security) **[Official]** | Security feature map: Dependabot, scanning, alerts, policies | Add a security baseline checklist in `github-actions-lab` or `github-security-lab` | Security checklist file + commit SHA | - [ ] |
| **L42 — Secrets vs variables + least privilege** | 120 min | [GitHub Actions docs](https://docs.github.com/en/actions) **[Official]** | Secret storage, variables, token permissions | Update workflow permissions + add secret-handling policy doc | Policy doc + YAML diff links | - [ ] |
| **L43 — Dependabot and dependency review** | 90 min | [Dependabot docs](https://docs.github.com/en/code-security/dependabot) **[Official]** | Automated update flows and review gates | Add Dependabot config and capture first PR/update behavior | `dependabot.yml` link + PR/alert screenshot | - [ ] |
| **L44 — Branch protection security posture** | 90 min | [Rulesets docs](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-rulesets/about-rulesets) **[Official]** | Governance as risk reduction | Verify required checks/reviews align with security goals | Ruleset screenshot + policy note | - [ ] |

**Sunday deliverable:** Security policy docs, permissions hardening, Dependabot configuration, and governance evidence committed.

---

## Week 12 (Dec 21–27, 2026) — Secret scanning, code scanning concepts, incident response

**Weekly objective:** Practice detection/remediation cycle with one intentional test vulnerability.

| Lesson | Est. time | Video / interactive link | What to learn | Hands-on activity | Evidence/output to save | Done |
|---|---:|---|---|---|---|---|
| **L45 — Secret scanning practice** | 120 min | [Secret scanning docs](https://docs.github.com/en/code-security/secret-scanning) **[Official]** | Preventing and handling exposed secrets | Simulate a safe test pattern (no real credentials), document response steps | Incident log markdown + screenshots | - [ ] |
| **L46 — Code scanning and CodeQL concepts** | 120 min | [Code scanning docs](https://docs.github.com/en/code-security/code-scanning) **[Official]** | Static analysis concepts, alert triage basics | Enable/configure conceptual code scanning docs/config in lab repo | Config link + notes on findings/remediation path | - [ ] |
| **L47 — Incident response runbook** | 90 min | [GitHub code security docs](https://docs.github.com/en/code-security) **[Official]** | Triage, containment, remediation, retrospective | Write incident response runbook with escalation checklist | `SECURITY_INCIDENT_RUNBOOK.md` link | - [ ] |
| **L48 — Vulnerability remediation report** | 90 min | [GitHub Docs](https://docs.github.com/) **[Official]** | Clear security communication | Document one intentionally introduced test vulnerability and remediation | Remediation report URL + linked fix PR | - [ ] |

**Sunday deliverable:** Threat model + test vulnerability/remediation report + security checks/policies in place.

---

## Week 13 (Dec 28, 2026–Jan 3, 2027) — Research setup in `github-research-notes`

**Weekly objective:** Define a valid research question, hypothesis, and method with experiment plan.

| Lesson | Est. time | Video / interactive link | What to learn | Hands-on activity | Evidence/output to save | Done |
|---|---:|---|---|---|---|---|
| **L49 — Select a measurable GitHub workflow question** | 90 min | [GitHub Docs](https://docs.github.com/) **[Official]** | Choosing variables and measurable outcomes | Create `github-research-notes` and write research question + scope | Repo URL + question section link | - [ ] |
| **L50 — Hypothesis and method design** | 120 min | [Open Source Guides](https://opensource.guide/) **[Official]** | Basic experiment design and bias awareness | Write hypothesis, method, and data-collection template | Method section link + data template file | - [ ] |
| **L51 — Experiment instrumentation** | 120 min | [GitHub Actions docs](https://docs.github.com/en/actions) **[Official]** | Collecting reproducible logs/screenshots/data | Set up experiment logging structure (`/logs`, `/screenshots`, `/data`) | Directory tree screenshot + initial entries | - [ ] |
| **L52 — Source quality pass** | 90 min | [Git docs](https://git-scm.com/docs) **[Official]** + [GitHub Docs](https://docs.github.com/) **[Official]** | Citing authoritative references | Build source list with official links for research topic | `sources.md` link | - [ ] |

**Sunday deliverable:** Complete research question, hypothesis, method, and experiment plan with official-source citations.

---

## Week 14 (Jan 4–10, 2027) — Run 3 experiments and publish findings

**Weekly objective:** Execute experiments and produce an evidence-based report with limitations.

| Lesson | Est. time | Video / interactive link | What to learn | Hands-on activity | Evidence/output to save | Done |
|---|---:|---|---|---|---|---|
| **L53 — Experiment 1 execution** | 120 min | [GitHub Docs](https://docs.github.com/) **[Official]** | Controlled workflow observation | Run experiment #1 and record metrics | Experiment #1 log + screenshot links | - [ ] |
| **L54 — Experiment 2 execution** | 120 min | [GitHub Docs](https://docs.github.com/) **[Official]** | Repetition and comparison quality | Run experiment #2 with same method template | Experiment #2 log + data table | - [ ] |
| **L55 — Experiment 3 execution** | 120 min | [GitHub Docs](https://docs.github.com/) **[Official]** | Distinguishing signal from noise | Run experiment #3 and collect complete evidence | Experiment #3 log + workflow/PR links | - [ ] |
| **L56 — Results, limitations, conclusion** | 120 min | [Open Source Guides](https://opensource.guide/) **[Official]** | Honest reporting and practical conclusions | Publish full report structure (question → conclusion + limitations + sources) | Final report URL + summary screenshot | - [ ] |

**Sunday deliverable:** Completed research report with 3 experiments, logs/screenshots/data, results, limitations, and source links.

---

## Week 15 (Jan 11–17, 2027) — External open-source contribution

**Weekly objective:** Submit and manage at least one PR to a repository you do not own.

| Lesson | Est. time | Video / interactive link | What to learn | Hands-on activity | Evidence/output to save | Done |
|---|---:|---|---|---|---|---|
| **L57 — Find beginner-friendly issue** | 90 min | [Contributing to projects](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project) **[Official]** | Issue triage and contribution fit | Select one external issue (docs/accessibility/test/bugfix) | Issue link + selection rationale note | - [ ] |
| **L58 — Fork and contribution branch workflow** | 120 min | [Open Source Guides](https://opensource.guide/) **[Official]** | Fork sync model and focused commits | Fork target repo, create branch, implement scoped change | Fork URL + branch + commits | - [ ] |
| **L59 — Submit external PR** | 120 min | [Pull requests docs](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests) **[Official]** | External PR etiquette and evidence quality | Open PR to upstream repo with clear testing and context | External PR URL | - [ ] |
| **L60 — Respond to review feedback** | 90 min | [Code review docs](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests) **[Official]** | Collaborative iteration and reviewer communication | Address reviewer comments and update PR | Review-thread screenshot + updated commit SHA | - [ ] |

**Sunday deliverable:** Public external PR with discussion history preserved (merged or pending review).

---

## Week 16 (Jan 18–24, 2027) — Portfolio and readiness verification

**Weekly objective:** Package evidence for hiring readiness and certify next steps.

| Lesson | Est. time | Video / interactive link | What to learn | Hands-on activity | Evidence/output to save | Done |
|---|---:|---|---|---|---|---|
| **L61 — Portfolio README build-out** | 120 min | [GitHub Docs](https://docs.github.com/) **[Official]** | Professional presentation of technical evidence | Update profile README with intro, skills, project/research links, open-source PR | Profile README link + before/after snapshot | - [ ] |
| **L62 — Pin repositories and validate evidence links** | 90 min | [GitHub Docs](https://docs.github.com/) **[Official]** | Portfolio curation and navigation | Pin key repos: `stargazers-log`, `github-workflow-lab`, `github-actions-lab`, `github-research-notes` | Profile screenshot with pinned repos | - [ ] |
| **L63 — Certification prep (GH-900 + GH-200)** | 120 min | [GitHub Foundations certification](https://learn.microsoft.com/en-us/credentials/certifications/github-foundations/) **[Official]** + [GitHub Actions certification](https://learn.microsoft.com/en-us/credentials/certifications/github-actions/) **[Official]** + [Microsoft Learn GitHub catalog](https://learn.microsoft.com/en-us/training/github/) **[Official]** | Domain review and readiness gap analysis | Build a personal exam-prep checklist and mock-question log | Checklist file link + gap notes | - [ ] |
| **L64 — Final readiness assessment** | 120 min | [GitHub Skills](https://skills.github.com/) **[Official]** + [GitHub flow](https://docs.github.com/en/get-started/using-github/github-flow) **[Official]** | End-to-end execution confidence | Run full scenario: issue → branch → commit → PR → review response → merge → deployment note | Final capstone evidence index file | - [ ] |

**Sunday deliverable:** Completed portfolio package + final readiness self-assessment + certification preparation tracker.

---

## Certification preparation notes (verify before booking)

- **GH-900 (GitHub Foundations):** begin focused prep around Weeks 6–8.
- **GH-200 (GitHub Actions):** begin focused prep after Weeks 9–10 labs.
- Use official pages for current objectives, pricing, language availability, renewal, and exam policies:
  - [GitHub Foundations certification](https://learn.microsoft.com/en-us/credentials/certifications/github-foundations/)
  - [GitHub Actions certification](https://learn.microsoft.com/en-us/credentials/certifications/github-actions/)
- **Exam details can change. Always verify current information before scheduling.**

---

## Final evidence checklist

- [ ] 3–4 polished public repositories
- [ ] 25–40 meaningful commits
- [ ] 12+ merged pull requests
- [ ] 20+ well-written issues
- [ ] 2–3 releases
- [ ] 5+ GitHub Actions workflows
- [ ] 1 documented security project
- [ ] 1 open-source contribution PR to external repository
- [ ] 1 independent technical research report with 3 experiments
- [ ] 1 GitHub Pages deployment with troubleshooting note
- [ ] GH-900 prep complete (or exam passed)
- [ ] GH-200 prep complete (or exam passed)

## Final readiness assessment (self-check)

Rate each item **0 (no), 1 (partly), 2 (yes)**:

- [ ] I can turn a feature request into issues with acceptance criteria.
- [ ] I can create branches, commits, and PRs without committing directly to `main`.
- [ ] I can resolve a merge conflict and explain what happened.
- [ ] I can troubleshoot a failed GitHub Actions run from logs.
- [ ] I can configure repository governance (templates, CODEOWNERS, rules/protection).
- [ ] I can deploy and maintain a GitHub Pages site.
- [ ] I can apply basic security practices (secrets, Dependabot, scanning concepts).
- [ ] I can contribute to an external open-source repository.
- [ ] I can present all work as verifiable portfolio evidence.

**Scoring guide:**
- **15–18:** Work-ready for junior GitHub-centered collaboration.
- **10–14:** Near-ready; close top gaps and repeat weak labs.
- **0–9:** Repeat key practice blocks (Weeks 1–4 and 9–12 first).

---

## Resource appendix

### Git fundamentals

- [Git reference documentation](https://git-scm.com/docs) **[Official]**
- [Git documentation home](https://git-scm.com/) **[Official]**

### GitHub collaboration

- [GitHub Hello World walkthrough](https://docs.github.com/en/get-started/start-your-journey/hello-world) **[Official]**
- [GitHub flow](https://docs.github.com/en/get-started/using-github/github-flow) **[Official]**
- [Pull requests docs](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests) **[Official]**
- [Code review docs](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests) **[Official]**
- [GitHub Skills](https://skills.github.com/) **[Official]**

### Projects and governance

- [Issues docs](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues) **[Official]**
- [Projects docs](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects) **[Official]**
- [CODEOWNERS docs](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners) **[Official]**
- [Rulesets / branch protection docs](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-rulesets/about-rulesets) **[Official]**
- [Releases docs](https://docs.github.com/en/repositories/releasing-projects-on-github/about-releases) **[Official]**

### GitHub Pages

- [GitHub Pages docs](https://docs.github.com/en/pages) **[Official]**

### GitHub Actions

- [GitHub Actions docs](https://docs.github.com/en/actions) **[Official]**
- [Workflow syntax docs](https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions) **[Official]**
- [Actions quickstart](https://docs.github.com/en/actions/quickstart) **[Official]**
- [Actions learning path Part 1](https://learn.microsoft.com/en-us/training/paths/automate-your-workflow-with-github-actions-part-1-of-2/) **[Official]**
- [Actions learning path Part 2](https://learn.microsoft.com/en-us/training/paths/automate-your-workflow-with-github-actions-part-2-of-2/) **[Official]**

### Security

- [GitHub code security](https://docs.github.com/en/code-security) **[Official]**
- [Dependabot docs](https://docs.github.com/en/code-security/dependabot) **[Official]**
- [Secret scanning docs](https://docs.github.com/en/code-security/secret-scanning) **[Official]**
- [Code scanning docs](https://docs.github.com/en/code-security/code-scanning) **[Official]**

### CLI

- [GitHub CLI manual](https://cli.github.com/manual/) **[Official]**

### Open source contribution

- [Open Source Guides](https://opensource.guide/) **[Official]**
- [Contributing to projects](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project) **[Official]**

### Certifications

- [GitHub Foundations learning path](https://learn.microsoft.com/en-us/training/paths/github-foundations/) **[Official]**
- [Microsoft Learn GitHub catalog](https://learn.microsoft.com/en-us/training/github/) **[Official]**
- [GitHub Foundations certification (GH-900)](https://learn.microsoft.com/en-us/credentials/certifications/github-foundations/) **[Official]**
- [GitHub Actions certification (GH-200)](https://learn.microsoft.com/en-us/credentials/certifications/github-actions/) **[Official]**

### Supplementary (optional)

- [GitHub official YouTube channel](https://www.youtube.com/github) **[Supplementary]**

Use supplementary items only to reinforce fundamentals when an official walkthrough alone is not enough.
