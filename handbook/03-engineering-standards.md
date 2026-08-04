Chapter 03 — Engineering Standards

Overview

Engineering standards bring much-needed consistency to projects. Even as tools and requirements change, sticking to the same standards makes software easier to maintain, improves how people communicate, keeps documentation clear, and just raises the bar for quality. The guidelines laid out here set the baseline for how projects should run—and they’re meant to shape all future work, too.

Engineering Workflow

Every project works better with a clear path. Don’t just jump from idea straight to code. There’s a process:

1. Understand
2. Design
3. Build
4. Verify
5. Improve

Each step builds off the last. If you skip ahead, you just complicate things for yourself down the line.

The flow looks like this:
Understand → Design → Document → Build → Verify → Reflect → Improve

Stage 1 — Understand

Start by getting a clear picture of what you’re tackling.

- Spell out the problem.
- Figure out who cares about or is affected by it.
- Know the business terms that matter.
- List any assumptions.
- Write down all questions you still have.
- Set project goals.
- Decide what success looks like.

Get your questions on paper before hunting for solutions.

Stage 2 — Design

Keep things simple. Focus on making the next stage (building!) as pain-free as possible.

- Check out different architectures.
- Draw boundaries around your system.
- Organize your repos.
- Set naming rules.
- Note what documentation you’ll need.
- Log important decisions as ADRs.
- Make your system easy to update before you worry about speed.

Stage 3 — Build

As you start building, stick to what you’ve planned and documented.

- Make your code easy to read.
- Write code others can maintain.
- Break things into modules.
- Stay consistent.

Take it one step at a time—small changes are way easier to review and manage than huge overhauls.

Stage 4 — Verify

Testing is just the beginning. Make sure what you’ve built actually meets the original needs.

- Validate requirements.
- Do exploratory and smoke tests.
- Run regression tests.
- Review the docs.
- Test usability.
- Take a look at the architecture.

The point is to confirm you really solved the problem you started with.

Stage 5 — Improve

Don’t just call it a day when you’re “done.” Every finished project should leave you smarter than before.

- Write down lessons learned.
- Update project journals.
- Polish up documentation.
- Fix templates.
- Tune engineering standards.
- Spot future project ideas.

Improvement isn’t optional—it’s just how things go forward.

Documentation Standards

Documentation should grow with the code—it’s not optional or an afterthought.

Every important project needs:

- A README
- Project journal
- Architecture docs
- Roadmap
- Architecture Decision Records (ADRs)
- Testing docs
- Setup instructions
- Ideas for future changes

Make sure your docs explain what you built and why you built it that way.

Repository Standards

Keep your repos organized and consistent.

At a minimum, include:

- A clear README
- The right license
- Well-organized folders
- Docs directory (if you need it)
- Clean commit history

Think long-term—organize now for future maintenance, not just what’s fastest today.

Naming Standards

Consistency helps everyone read and understand code faster.

Stick to these basics:

- All repository names in lowercase
- Use hyphens for repo names
- Pick filenames that actually describe what’s inside
- Give variables real meaning—don’t be vague
- Use clear terms from your domain

Good names show intent, not just how something works inside.

Decision Standards

Record big technical decisions so others can follow your logic.

Every major decision needs:

- Context
- The decision itself
- Alternatives you considered
- Why you chose what you did
- What you expect as a result

ADRs are the standard way to keep track of this info.

Quality Standards

Aim for high quality throughout—not just at the end.

Hold every project to these standards:

- Correctness
- Maintainability
- Simplicity
- Consistency
- Traceability
- Reproducibility
- Clear docs

Test what you’ve documented, not what you assume.

AI Collaboration Standards

AI should make your work smoother, not take over decision-making.

Use AI for:

- Reviewing docs
- Spotting inconsistencies
- Explaining new stuff
- Creating first drafts
- Suggesting tweaks
- Reviewing architecture
- Helping with repetitive bits

But keep all big engineering calls in human hands.

Definition of Done

A project milestone isn’t finished until:

- It meets all requirements
- Docs are updated
- You’ve recorded important decisions
- You’ve completed testing
- Known issues are documented
- Future improvements are listed where they make sense

You’re not done until you’ve documented everything—not just delivered code.

Continuous Refinement

Standards aren’t carved in stone. As you learn and discover better ways, update the handbook. Consistency matters, but don’t stick with something just because “that’s how we do it.” Let standards grow as your team does.

Chapter Information

Version

1.0.0

Status

Draft

Revision History

Version Description
1.0.0 Initial chapter
