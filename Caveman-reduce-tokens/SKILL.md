---
name: Caveman
description: "Reduce LLM tokens by ~75% while keeping technical accuracy. Talk like caveman."
author: JuliusBrussee
version: 1.0.0
---
tags:
  - productivity
  - compression
  - communication
  - cost-saving
url: https://github.com/JuliusBrussee/caveman
install: npx skills add JuliusBrussee/caveman
modes:
  - name: Lite
    description: "Drop filler, keep grammar. Professional but no fluff"
    trigger: "/caveman lite"
  - name: Full
    description: "Default caveman. Drop articles, fragments, full grunt"
    trigger: "/caveman full"
  - name: Ultra
    description: "Maximum compression. Telegraphic. Abbreviate everything"
    trigger: "/caveman ultra"
  - name: Wenyan-Lite
    description: "Semi-classical Chinese. Grammar intact, filler gone"
    trigger: "/caveman wenyan-lite"
  - name: Wenyan-Full
    description: "Full classical Chinese terseness"
    trigger: "/caveman wenyan"
  - name: Wenyan-Ultra
    description: "Extreme ancient scholar mode"
    trigger: "/caveman wenyan-ultra"
skills:
  - name: caveman-commit
    description: "Terse commit messages. ≤50 char subject. Why over what."
    trigger: "/caveman-commit"
  - name: caveman-review
    description: "One-line PR comments. No throat-clearing."
    trigger: "/caveman-review"
  - name: caveman-help
    description: "Quick-reference card. All modes and commands."
    trigger: "/caveman-help"
  - name: caveman-compress
    description: "Compress memory files into caveman-speak. Save ~46% input tokens."
    trigger: "/caveman:compress"
activation:
  - "/caveman"
  - "talk like caveman"
  - "caveman mode"
  - "less tokens please"
deactivation:
  - "stop caveman"
  - "normal mode"
