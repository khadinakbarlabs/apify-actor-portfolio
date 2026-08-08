# Catalog policy

## Allowed content

Each entry may include only public-facing portfolio metadata:

- Actor slug and title
- Direct Actor URL
- MCP entry point
- A short, evidence-backed scope statement when separately reviewed

## Prohibited content

Do not add Actor source code, Dockerfiles, package manifests, schemas, build
settings, credentials, session cookies, API tokens, private Console URLs,
customer information, run output, or unpublished task data.

## Link rules

Every Actor link must use the canonical `https://apify.com/khadinakbar/<slug>`
shape. Every MCP entry point must use
`https://mcp.apify.com?tools=khadinakbar/<slug>`. Links must not contain
credentials, tracking parameters, redirects, or misleading availability claims.

Only add contextual cross-links when they explain a real workflow. Do not add
all-to-all link lists, generic promotional copy, or keyword-stuffed anchors.

## Release gate

Before changing repository visibility, review the complete Git history and the
current tree for prohibited content. Confirm that each linked Actor page is
appropriate for public referral at that time. This catalog never changes an
Actor's Apify publication state.
