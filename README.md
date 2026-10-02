# Ready Suit Go

Standalone Cedar River Labs sample. Post-wedding rental suit return: venue locker or scheduled pickup, photo checklist before anything changes hands.

Not a live service. Knotting Hills in Pevely, Missouri is the example in the copy, not a partner.

## Host

Cloudflare Worker, same pattern as `app.cedarriverlabs.com` and `wsc.cedarriverlabs.com`.

- Worker: `ready-suit-go`
- Domain: `https://readysuitgo.cedarriverlabs.com`

```
npx wrangler deploy
```

Assets live in `site/`.
