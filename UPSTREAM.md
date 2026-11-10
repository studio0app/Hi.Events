# UPSTREAM

This repository is a public GitHub fork kept by **studio0**
([studio0.app](https://studio0.app), GitHub org [studio0app](https://github.com/studio0app))
for Aiden's music, events and record label.

studio0 is the product and umbrella brand. It is **built on ArtCraft**
(the open-source Crafting Apps and related tools from the ArtCraft team)
and, where this repository is an events/ticketing project, on the named
upstream event platform. This file is a studio0 provenance note. It does
not rebrand, relicense or replace upstream credits.

## Upstream

- Upstream repository: <https://github.com/HiEventsDev/Hi.Events>
- Upstream default branch: `develop`
- Licence(s): AGPL-3.0 with additional terms (see LICENCE)
- Mirrored / forked for studio0 on: 10 November 2026 (Australia/Sydney, AEDT, UTC+11)

## Remotes

When you clone this repository:

```sh
git remote add upstream https://github.com/HiEventsDev/Hi.Events.git
git fetch upstream
# origin should already point at https://github.com/studio0app/Hi.Events
```

Pull upstream updates with `git fetch upstream` and merge or rebase onto
the upstream default branch. Do not rewrite upstream history. Do not
strip, move or overwrite licence files, NOTICE, ATTRIBUTION, copyright
headers, or trademark-notice files that arrived from upstream.

## Licence and attribution (do not weaken)

Upstream licence files in this repository are authoritative. Keep them
intact. In particular:

Licensed under GNU AGPL v3 with additional Section 7(b) terms in LICENCE: retain a clearly visible 'Powered by Hi.Events' footer (or a rephrased 'Powered by [studio0] based on Hi.Events') linking to https://hi.events; do not hide or obscure it. If the software is modified and offered to users over a network, AGPL section 13 requires offering the corresponding source of the modified version to those users at no charge. Files under backend/ee/ and frontend/src/ee/ are NOT AGPL — they are under the Hi.Events Enterprise Licence. Reserved seating, box office and enterprise SSO in production need a commercial licence from Hi.Events Ltd. Do not remove or bypass licence-key checks. This fork is public because of the AGPL obligations.

ArtCraft names, wordmarks and logos that appear in upstream `docs/brand/`
(or equivalent) are trademarks of the ArtCraft Team and are **not**
covered by the MIT/Apache licences on the Crafting Apps. Do not treat
those marks as open source, and do not reuse them as studio0 branding.

studio0 branding belongs in studio0's own docs and notes (this file, the
integration document in `studio0app/studio0`, and similar). It does not
belong in place of upstream credits.

## What this mirror is for

Primary candidate for studio0 event management and ticketing (concerts, club nights, merch add-ons, lineups, check-in, embeds). Keep this fork public. Do not combine this AGPL code into the private studio0 app or the MIT/Apache ArtCraft apps; integrate only over APIs, webhooks or embeds.

It is not a relicensing, and it is not permission to combine this code
with differently licensed studio0 or ArtCraft code in a way the upstream
licence forbids.
