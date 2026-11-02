# releases.mbientlab.com

Serves the MetaWear firmware catalog at https://releases.mbientlab.com for the
legacy SDKs (e.g. the Python SDK, which fetches
`https://releases.mbientlab.com/metawear/info1.json`).

This repo holds no firmware. The files live in
[`mbientlab/mbientlab.com`](https://github.com/mbientlab/mbientlab.com) under
`releases/`, which also serves them at `https://mbientlab.com/releases/`. The
workflow here copies that folder to the root of this site.

## Updating

1. Add the firmware and catalog changes to `releases/` in `mbientlab/mbientlab.com`.
2. Once that is merged, run **Deploy releases to GitHub Pages** from this repo's
   Actions tab.
