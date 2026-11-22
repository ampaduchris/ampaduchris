## Chris Nana Ampadu

I direct coding agents to build software. I write the specification, decide what evidence would prove the work wrong, and accept nothing without that evidence. I do not write the code by hand. Since November 2026 I approve and merge every pull request myself.

**[german-b1-tutor](https://github.com/ampaduchris/german-b1-tutor)**: a writing tutor for the Goethe-Zertifikat B1 German exam.

- Two thirds of the behaviour is plain Python with no model call. 172 tests pass with no API (application programming interface) key at the v1.0.0 release.
- The model writes into a closed vocabulary of thirteen error categories. It cannot add one, because an open set under-reports the learner's worst weakness.
- A regression harness plants five errors and measures whether the model reports them, against a pinned model.
- The build log records what went wrong and what is still not verified.

Every repository here carries its specification, a build log with the model and effort for each session, and a list of deviations.

I started building in public in July 2026.
