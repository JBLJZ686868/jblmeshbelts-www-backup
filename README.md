# www.jblmeshbelts.com Redirect Project

Backup date: 2026-07-03

This Codex project points `https://www.jblmeshbelts.com/` to the official JBL Mesh Belt website at `https://www.jblmeshbelt.com/`.

## Original Finding

The live domain returned a small `Redirecting...` HTML page served by `openresty`.
Windows Defender blocked the downloaded HTML as virus or potentially unwanted software, so the active downloaded page was removed from this local backup.

The current deployment now redirects visitors to the official production website.

## Current DNS

`www.jblmeshbelts.com` currently resolves to:

- `172.234.25.42`
- `172.232.24.235`
- `172.232.24.161`

Nameservers observed for `jblmeshbelts.com`:

- `ns1.dnsowl.com`
- `ns2.dnsowl.com`
- `ns3.dnsowl.com`

## HTTP Snapshot

Observed response:

- Status: `200`
- Title: `Redirecting...`
- Server: `openresty`
- Content-Type: `text/html`
- Cache-Control: `no-store, max-age=0`
- Permissions policy references `parklogic.com`

## Local Preview

Run:

```powershell
npm run serve
```

Then open the printed local URL.

## Current Behavior

Vercel redirects all paths from `www.jblmeshbelts.com` to `https://www.jblmeshbelt.com/`.
