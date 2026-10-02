# Changelog

Versions bump minor when skill text changes behavior, patch for docs and
evals. Protocol changes land with a `./evals/regress.sh` run and its
scorecard; the judge mean is part of the entry. Release steps: RELEASING.md.

## Unreleased

- README and homepage explain the lens vocabulary before using it: the two
  lenses come before the protocol, a short glossary defines the residuality
  terms and links to the full vocabulary, and the terse lines on options,
  coupling, new technology, and absurd stressors say why. A courtesy of @cquiros

## 0.2.0 - 2026-09-30

Fidelity audit against the published source material.

- Residuality reference now matches O'Reilly's pipeline: contagion analysis
  runs over component dependencies before the incidence matrix, and the
  procedure holds back a test set of stressors the adjusted architecture was
  never tuned for, which is the empirical core of the method.
- Contagion is defined over dependencies and information flows (a design
  structure matrix), not loosely as "failure spreads".
- Elevator reference states the Black-Scholes intuition: option value rises
  with uncertainty.
- Fixed dead residuality.io links; both O'Reilly books now link to Leanpub
  and Black Tulip Technology.
- Regression: opus-judged deepseek mean 37.0 of 50, unchanged from the
  0.1.0 baseline.

## 0.1.0 - 2026-09-30

Initial release.

- The turtleneck protocol: gate, six rungs, banned moves, decision-record
  output. Levels napkin, full, deep; the gate picks the level from undo cost
  when none is named.
- Skills: `turtleneck`, `turtleneck-review`, `turtleneck-stress`,
  `turtleneck-help`, plus reference files for the elevator lens, the
  residuality lens, the record template, and the banned-move table.
- Install adapters for the skills CLI, Claude Code, Codex, and pi, all
  pointing at the same `skills/` folder.
- Eval harness: deterministic compliance checks with skill-vs-baseline arms,
  six Ford and Neward architectural katas, and an LLM quality judge with
  pluggable models. Compliance 96 to 100% with the skill against 44% baseline
  across deepseek and opus generators.
- Protocol hardening driven by the kata judge: stressors written as
  hypotheses rather than client facts, prices anchored to the brief or one
  stated assumption, owner-stressor candidates instead of an empty slot,
  stressors must discriminate or reveal coupling. Sonnet-judged trend 45.3 to
  46.8 of 50; series closed. Opus-judged baseline 37.0 of 50.
- Homepage on GitHub Pages, pixel-art hanger logo, worked examples from the
  kata suite.
