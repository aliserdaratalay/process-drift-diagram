# Process-Drift Control Plane

An animated diagram of a process that protects itself when templates, rules and requirements change: a living ontology, a local SLM that adapts the rules, a confidence gate that decides who acts (auto-apply for low-risk changes only, hosted-LLM review, or a person), versioned ontology with one-step rollback, recurring gaps from real runs feeding the detector, and a failover chain (hosted model → local SLM → safe default). Shown for NextArc and AI4SWEng.

**Live page:** https://aliserdaratalay.github.io/process-drift-diagram/

![Process-drift control plane](https://aliserdaratalay.github.io/process-drift-diagram/process_drift_control_plane.png)

## Use it on your website

One line (loads the animated SVG from this site):

```html
<img src="https://aliserdaratalay.github.io/process-drift-diagram/process_drift_control_plane.svg" alt="Process-drift control plane" style="width:100%;max-width:1200px;height:auto;display:block;margin:0 auto">
```

Or paste the self-contained code from [`embed.html`](embed.html) into a Custom HTML block.

## Files

- `process_drift_control_plane.svg`: animated vector diagram (22 KB)
- `process_drift_control_plane.png`: static image
- `embed.html`: self-contained, responsive inline SVG for any web page

© AI4SEC OÜ · Saura.ai
