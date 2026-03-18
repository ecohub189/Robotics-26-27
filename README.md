# Robotics 26-27: Team Repository

Welcome to the team! This is our **official repository** for all robot code, planning, and documentation. Follow this workflow carefully to keep `main` safe and the robot working.

---

## Repo Structure


/plans → Markdown plans and pseudocode for autonomous and driver control
/docs → Robot hardware and strategy notes
/src → Actual C++ code (for later)
.github/ → GitHub settings, CODEOWNERS, PR templates
README.md → You are here


---

## Golden Rules

1. **Never push directly to `main`** – always create a branch.
2. **Commit often** – small, meaningful commits every 15–30 minutes.
3. **Write clear commit messages** – explain what changed and why.
4. **Respect the review process** – open a PR, wait for lead approval before merging.

---

## Student Workflow

### 1. Start with an Issue
Pick an assigned task or create a new issue describing your work.

### 2. Create a Branch
Branch names should be descriptive, like:

plan-left-auton
auton-vision-test
fix-intake-sequence


### 3. Write Your Plan (THIS SHOULD BE DONE BEFORE YOU EVEN START WRITING CODE)
Create a Markdown file in `/plans/` with pseudocode steps:

Drive forward 500mm

Turn right 90 degrees

Spin intake motors at 100% for 2 seconds

Drive reverse 200mm


### 4. Commit Your Changes
Commit to your branch with a meaningful message.

### 5. Open a Pull Request
- Request review from the lead (owner).  
- Wait for approval before merging.  
- Delete your branch after merge to keep the repo clean.

---

## Tips for Success

- Branch for every new idea or feature.
- Keep commits small and focused.
- Link PRs to Issues for tracking.
- Write Markdown plans first, then code in C++.

---

## Helpful Links (more links will be added on!)

- [Creating a Branch](https://docs.github.com/en/get-started/quickstart/hello-world#creating-a-branch)  
- [Pull Requests](https://docs.github.com/en/pull-requests)  
- [Markdown Guide](https://www.markdownguide.org)

---

**Stop Breaking the Robot!**  
Follow this workflow, and `main` will always be competition-ready. 🏆
