# jecp.dev — landing page

Public website for **JECP — Joint Execution & Commerce Protocol**.

The open protocol for agent-to-service commerce. Apache 2.0.

- Production: https://jecp.dev
- Specification: https://github.com/jecpdev/jecp-spec
- Reference server: https://github.com/jecpdev/jecp-server
- Operator: Tufe Company Inc.

## Naming history

The protocol was originally coined as "JobDoneBot Execution Capability Protocol" (May 2026, when the reference implementation went live).
It was renamed to **"Joint Execution & Commerce Protocol"** upon transition to a multi-vendor standard track.
The acronym `JECP` and all URLs (`jecp.dev`, `github.com/jecpdev`) are preserved.

## Stack

Static HTML + CSS. No JavaScript framework. Deploys to Vercel / Cloudflare Pages / any static host.

## Local development

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

```bash
vercel deploy --prod
```

## License

Apache License 2.0.
