# Ready Suit Go

Customer-facing preview. A guest books a post-wedding rental return, drops the suit in a venue locker or hands it off, and gets a text when the shop has it.

Not a live service. Knotting Hills is an example venue in the form, not a partner.

## Host

Cloudflare Worker, same pattern as `app.cedarriverlabs.com` and `wsc.cedarriverlabs.com`.

- Worker: `ready-suit-go`
- Domain: `https://readysuitgo.cedarriverlabs.com`

```
npx wrangler deploy
```

Assets live in `site/`.
