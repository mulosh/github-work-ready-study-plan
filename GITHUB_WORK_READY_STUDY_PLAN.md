# GitHub Work-Ready Study Plan

**Learner:** mulosh  
**Primary practice repository:** [mulosh/stargazers-log](https://github.com/mulosh/stargazers-log)  
**Start date:** October 5, 2026  
**Duration:** 16 weeks  
**Time commitment:** 8–12 hours per week

## Goal

Become ready to work with GitHub in a real software team. By the end, you should be able to use Git, collaborate through pull requests, manage work with issues and projects, troubleshoot GitHub Actions, deploy a site, apply basic repository security practices, contribute to open source, and present verifiable work to employers.

## Important distinction

This plan produces evidence of GitHub and software-development practice. Describe the work as **personal projects**, **independent technical research**, and **open-source contributions**. Do not describe it as professional employment or peer-reviewed research unless that is accurate.

---

## Official learning links

### Git and GitHub fundamentals

- [Git reference documentation](https://git-scm.com/docs)
- [GitHub Docs](https://docs.github.com/)
- [GitHub Skills](https://skills.github.com/)
- [GitHub Hello World course](https://docs.github.com/en/get-started/start-your-journey/hello-world)
- [GitHub flow](https://docs.github.com/en/get-started/using-github/github-flow)
- [GitHub glossary](https://docs.github.com/en/get-started/learning-about-github/github-glossary)

### Collaboration and project management

- [Issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues)
- [Projects](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/about-projects)
- [Pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests)
- [Code review](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/reviewing-changes-in-pull-requests)
- [Managing merge conflicts](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts)
- [Releases](https://docs.github.com/en/repositories/releasing-projects-on-github/about-releases)
- [Contributing to projects](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project)

### Pages, Actions, and security

- [GitHub Pages](https://docs.github.com/en/pages)
- [GitHub Actions](https://docs.github.com/en/actions)
- [Workflow syntax](https://docs.github.com/en/actions/reference/workflow-syntax-for-github-actions)
- [GitHub Actions quickstart](https://docs.github.com/en/actions/quickstart)
- [GitHub security features](https://docs.github.com/en/code-security)
- [Dependabot](https://docs.github.com/en/code-security/dependabot)
- [Code scanning](https://docs.github.com/en/code-security/code-scanning)
- [Secret scanning](https://docs.github.com/en/code-security/secret-scanning)
- [Branch protection](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-rulesets/about-rulesets)
- [CODEOWNERS](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners)

### Command-line and open source

- [GitHub CLI manual](https://cli.github.com/manual/)
- [GitHub CLI quickstart](https://docs.github.com/en/github-cli/github-cli/quickstart)
- [Open Source Guides](https://opensource.guide/)
- [Choose an open-source license](https://choosealicense.com/)

---

# Portfolio repositories

| Repository | Purpose | Evidence |
|---|---|---|
| `stargazers-log` | Git, HTML, GitHub Pages, issues, pull requests | Live site, commits, issues, PRs, deployment |
| `github-workflow-lab` | Simulated professional team workflow | Templates, branch protection, reviews, releases |
| `github-actions-lab` | CI/CD and automation | Workflows, checks, artifacts, failure analysis |
| `github-research-notes` | Independent technical research | Research questions, experiments, results, sources |

Create these gradually. `stargazers-log` is the starting repository; the other repositories can be created when their phases begin.

---

# Phase 1 — Git and collaboration fundamentals

## Weeks 1–2: Git basics and branches

Learn:

- Git versus GitHub
- Working tree, staging area, commits, and remotes
- `clone`, `status`, `diff`, `add`, `commit`, `push`, and `pull`
- Branches and remote tracking
- Clear commit messages

Practice in `stargazers-log`:

- Make at least 10 meaningful commits
- Create branches such as `docs/update-readme`, `feature/page-layout`, and `fix/mobile-layout`
- Push branches to GitHub
- Never commit directly to `main`

Useful commands:

```bash
git clone <repository-url>
git status
git log --oneline
git diff
git switch -c feature/name
git add .
git commit -m "Describe the change"
git push -u origin feature/name
git pull
git remote -v
```

## Weeks 3–4: Pull requests and history recovery

Learn:

- Issues linked to pull requests
- Pull request descriptions and reviews
- Draft pull requests
- Squash merges, merge commits, and rebasing
- Merge conflicts, `revert`, `restore`, and `reflog`

Deliverables:

- At least 4 merged pull requests
- At least 4 linked issues
- One deliberately created and resolved merge conflict
- One reverted commit
- One complete README update
- A written note explaining how the conflict was resolved

Every pull request should include:

```text
Summary
Related issue
Files changed
Testing performed
Screenshots, if applicable
Known limitations
```

---

# Phase 2 — Professional GitHub workflow

## Weeks 5–7: Issues, projects, governance, and releases

Create `github-workflow-lab` and configure it as a small professional project.

Add:

- `CONTRIBUTING.md`
- `CODE_OF_CONDUCT.md`
- `SECURITY.md`
- `CHANGELOG.md`
- Issue templates
- Pull request template
- Labels and milestones
- A project board with `Backlog`, `Ready`, `In progress`, `In review`, and `Done`
- CODEOWNERS
- Protected `main` branch
- Required pull request reviews and status checks
- At least one release with release notes

Deliverables:

- 10 well-written issues
- 6 pull requests
- 3 review cycles
- 1 revised pull request after feedback
- 1 completed milestone
- 1 public release

Each issue should contain:

- Problem statement
- Expected result
- Acceptance criteria
- Priority or labels
- Screenshots or examples when useful

## Week 8: GitHub Pages

Deploy `stargazers-log` with GitHub Pages.

Improve it with:

- Responsive layout
- Semantic HTML
- Accessible link text
- Page title and metadata
- Clear navigation
- Mobile-friendly presentation

Deliverables:

- A working public site
- A live-site link in the README
- A short deployment guide
- Documentation of one deployment problem and its solution

---

# Phase 3 — Automation and security

## Weeks 9–10: GitHub Actions

Create `github-actions-lab`.

Build workflows for:

1. HTML validation
2. Link checking
3. Pull request validation
4. Test execution
5. GitHub Pages deployment
6. Scheduled maintenance

Practice:

- Workflow triggers
- Jobs and steps
- Runners
- Artifacts
- Workflow permissions
- Reusable workflows or composite Actions
- Reading failed job logs

Deliberately break at least two workflows. For each failure, document:

```text
Failure
Root cause
Evidence from logs
Fix
Prevention
```

Deliverables:

- At least 5 workflow files
- 3 successful pull-request checks
- 2 documented failures and fixes
- 1 generated artifact
- 1 CI/CD process diagram

## Weeks 11–12: Security and governance

Create `github-security-lab`, or add this work to `github-actions-lab`.

Study and document:

- Least-privilege permissions
- Secrets versus variables
- Dependabot
- Dependency review
- Secret scanning
- Code scanning and CodeQL concepts
- Branch protection
- Signed commits, optionally
- Security incident response

Never commit real credentials or tokens.

Deliverables:

- Security policy
- Secret-handling policy
- Dependabot configuration
- Security-related pull request checks
- Threat model for one project
- Report on one intentionally introduced test vulnerability and its remediation

---

# Phase 4 — Research, open source, and portfolio

## Weeks 13–14: Independent technical research

Create `github-research-notes`.

Choose one research question:

- How does pull-request size affect review quality?
- How do squash merges, merge commits, and rebasing differ in practice?
- What failure patterns occur in GitHub Actions workflows?
- How does branch protection change contributor behavior?
- How can issue templates improve bug reports?
- How does manual deployment compare with GitHub Actions deployment?

Use this structure:

```markdown
# Research question

## Background
## Hypothesis
## Method
## Repository or workflow tested
## Observations
## Results
## Limitations
## Conclusion
## Sources
```

Complete:

- One clear research question
- At least 3 experiments
- A documented method
- Screenshots or workflow logs
- Data tables where appropriate
- Findings and limitations
- Links to official documentation and other sources

Describe this on your resume as an **independent technical research project**.

## Week 15: Open-source contribution

Submit at least one pull request to a repository you do not own.

Suitable first contributions:

- Documentation correction
- Accessibility improvement
- Broken-link fix
- Test improvement
- Small bug fix
- Example improvement

Preserve the public pull request and review discussion as evidence.

## Week 16: Portfolio and final assessment

Update your GitHub profile README with:

- Professional introduction
- Skills
- Pinned repositories
- Certification links or badges
- Open-source contribution
- Live project links
- Research project
- Contact information

Pin:

1. `stargazers-log`
2. `github-workflow-lab`
3. `github-actions-lab`
4. `github-research-notes`

---

# Certification plan

## 1. GitHub Foundations — GH-900

Official links:

- [Certification page](https://learn.microsoft.com/en-us/credentials/certifications/github-foundations/)
- [GH-900 study guide](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/gh-900)
- [Microsoft Learn GitHub fundamentals](https://learn.microsoft.com/en-us/training/paths/github-foundations/)

Take this after Weeks 6–8. Study repositories, collaboration, issues, projects, security basics, administration fundamentals, and GitHub community features.

## 2. GitHub Actions — GH-200

Official links:

- [Certification page](https://learn.microsoft.com/en-us/credentials/certifications/github-actions/)
- [GH-200 study guide](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/gh-200)
- [GitHub Actions learning paths](https://learn.microsoft.com/en-us/training/browse/?products=github-actions)

Take this after completing the Actions project. Prepare with workflow authoring, triggers, permissions, troubleshooting, artifacts, reusable workflows, custom Actions concepts, and secure automation.

## 3. Optional specialization

Choose based on your career direction:

- [GitHub Administration — GH-100](https://learn.microsoft.com/en-us/credentials/certifications/github-administration/) for repository governance, identity, access, enterprise administration, and platform operations.
- [GitHub Advanced Security — GH-500](https://learn.microsoft.com/en-us/credentials/certifications/github-advanced-security/) for application security, secret protection, dependency security, code scanning, and DevSecOps.
- [AWS Certified Cloud Practitioner](https://aws.amazon.com/certification/certified-cloud-practitioner/) for broader cloud fundamentals.

Always verify current exam objectives, prices, availability, and renewal rules with the official provider before scheduling an exam.

---

# Weekly schedule

| Day | Activity |
|---|---|
| Monday | Study one Git or GitHub concept |
| Tuesday | Follow a documentation example |
| Wednesday | Apply it to a repository |
| Thursday | Deliberately make and fix a mistake |
| Friday | Review diffs, issues, and workflow results |
| Weekend | Complete the weekly deliverable |

Use approximately 30% study and 70% hands-on work.

---

# Final evidence checklist

By completion, aim for:

- 3–4 polished public repositories
- 25–40 meaningful commits
- 12 or more merged pull requests
- 20 or more well-written issues
- 2–3 releases
- 5 or more GitHub Actions workflows
- 1 documented security project
- 1 open-source contribution
- 1 independent research project
- 1 GitHub Pages deployment
- GitHub Foundations certification
- GitHub Actions certification, if the practical work is complete

## Resume example

> Built and maintained a GitHub portfolio demonstrating Git branching, pull-request review, issue planning, protected branches, GitHub Actions CI/CD, GitHub Pages deployment, and secure development practices. Completed an independent technical study of GitHub workflow strategies and contributed documentation changes to an external open-source project.

## Readiness test

You are ready to claim basic professional GitHub experience when you can independently receive a feature request, turn it into issues, create a branch, implement the change, resolve a conflict, open a pull request, respond to review feedback, fix a failed Action, merge the change, deploy it, and document the release.
