# Zero releases

Builds of the Zero apps, read by Beacon (the Zero Store catalog) — devices never talk to this repo directly.

## `apps` release

One rolling release holds every app. Each publish replaces that app's files in place.

| Asset | App | Package | Runs on |
|---|---|---|---|
| `catalog.json` | the catalog: version, versionCode, size, SHA-256 and signing key of every APK below | | |
| `zero-media-phone.apk` | Zero Media | com.j4ckgrey.zero.media | phone, tablet, TV (64-bit), glasses |
| `zero-media-tv.apk` | Zero Media (32-bit TV build) | com.j4ckgrey.zero.media | Fire TV / Android TV (32-bit) |
| `zero-media-quest.apk` | Zero Media (Quest) | com.j4ckgrey.zero.media | Meta Quest |
| `zero-pilot.apk` | Zero Pilot | com.j4ckgrey.pilot | phone |
| `zero-dash.apk` | Zero Dash | com.j4ckgrey.zerodash | phone |
| `zero-dash-car.apk` | Zero Dash Car | com.j4ckgrey.zerodash.car | car head unit |
| `zero-store.apk` | Zero Store | com.j4ckgrey.zero.store | phone, TV |
| `zero-tv-installer.apk` | Zero TV Installer | com.j4ckgrey.zero.tvinstall | phone |

## `addons/directory.json`

The add-on directory every Zero server loads (`zero_server/src/lib/addonDirectory.ts`). Keep this repo public and keep this path.
