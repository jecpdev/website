# jecp.dev — landing page

Public website for the **Joint Execution Capability Protocol** (JECP).

- Production: https://jecp.dev
- Specification: https://github.com/jecpdev/jecp-spec
- Reference server: https://github.com/jecpdev/jecp-server
- Operator: JobDoneBot Inc.

## Stack

Static HTML + CSS. No JavaScript framework required. Deploy to Vercel / Cloudflare Pages / any static host.

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

Site content is Apache 2.0 (same as the protocol).
