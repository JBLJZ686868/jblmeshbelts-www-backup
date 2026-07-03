# www.jblmeshbelts.com Local Backup

Backup date: 2026-07-03

This Codex project records the current public state of `https://www.jblmeshbelts.com/`.

## Important Finding

The live domain returned a small `Redirecting...` HTML page served by `openresty`.
Windows Defender blocked the downloaded HTML as virus or potentially unwanted software, so the active downloaded page was removed from this local backup.

The safe local `public/index.html` is a placeholder that documents the issue. It is not a full copy of the live site.

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

## Next Step

To make `www.jblmeshbelts.com` show the real JBL Mesh Belt website, update DNS or hosting so this domain points to the same production site as `www.jblmeshbelt.com`, or configure a 301 redirect from `www.jblmeshbelts.com` to `https://www.jblmeshbelt.com/`.
