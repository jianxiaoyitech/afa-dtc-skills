# Polaris AFA DTC Domain Pack

`main.ord` is the Polaris Business DSL representation of the user-facing
workflows described by the AFA DTC Skills Hub.

The pack keeps the AFA worker system as domain knowledge. DSL ports are
capability contracts only; they do not embed prompts, local paths, commands,
credentials, or an execution adapter.

Install from the Wanghai repository root:

```bash
pnpm --dir ../polaris run polaris -- pack add \
  "$PWD/third_party/afa-dtc-skills/polaris-domain-pack"
```

The pack contains the eleven Hub workflows: from-zero, bottleneck diagnosis,
advertising, retention, content, brand refresh, promotion readiness, channel
expansion, emergency stabilization, Level 0 guidance, and premium growth.
