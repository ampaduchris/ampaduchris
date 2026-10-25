## Chris Nana Ampadu

I build systems where a language model does the one job that needs language, and
plain code does everything else — because most of what looks like an AI problem
is arithmetic wearing a costume.

**[german-b1-tutor](https://github.com/ampaduchris/german-b1-tutor)** — a Goethe
B1 writing tutor built spec-first by directing a coding agent, with no
hand-written code. The interesting part is not that an agent wrote it; it is
where the boundary was drawn:

- Two thirds of the behaviour is deterministic. Counting, sorting, validation and
  every file write are plain Python, covered by 170+ tests that pass with no API
  key on Python 3.10 through 3.13.
- The model writes into a closed thirteen-category vocabulary it cannot extend,
  because an open set silently under-reports the user's worst weakness.
- The prompt is a contract of eleven numbered obligations, and a regression
  harness measures whether the model honours them on the wire — five planted
  errors, graded by set comparison, against a pinned model, in a sandbox that
  hashes the real log before and after to prove it was never touched.
- The build log records what went wrong: a vocabulary left open too long, two
  acceptance criteria still unverified, one failure mode deliberately unhandled.

Currently working through Goethe-Zertifikat B1 in Frankfurt, which is what the
tutor is for.
