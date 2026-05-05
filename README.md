# AxonRing — axonring.online

Landing page for [axonring.online](https://axonring.online).

## Deployment

This repo is connected to Vercel and auto-deploys on every push to `main`.

## Structure

```
├── index.html      # Main landing page
├── vercel.json     # Vercel deployment config + security headers
└── README.md
```

## Custom Domain

Domain `axonring.online` is configured in Vercel project settings.
DNS is managed via IONOS — point the following records to Vercel:

- `A` record: `76.76.21.21`
- `CNAME` record: `cname.vercel-dns.com`
