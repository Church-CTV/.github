# Church CTV

Television software for churches: one shared platform, several televisions, and
no software subscription for a congregation that runs it itself.

Owned and maintained by GitHub `@dominick253`, who is also the only person who
can decide ownership, permissions and commercial licensing.

## Four repositories, one platform

| Repository | What it is |
| --- | --- |
| `platform-server` | feeds, channel configuration, media, analytics, administration |
| `roku-app` | the configurable Roku application |
| `android-tv-app` | the Android TV and Fire TV application |
| `web-tv-app` | shared Samsung Tizen, LG webOS and Vizio application |

Channels are configuration, not code forks. Each platform keeps its own SDK,
signing and store boundaries, and they share versioned contracts, so the same
church profile drives all four.

## Public source, church-use license

The source is published under the **Church CTV Community Source License 1.0**
(`LICENSE` in each repository): an eligible church may run, modify and deploy it
for its own worship and ministry at no license fee, with no channel or viewer
cap and no requirement to buy hosting. Independent commercial operation, resale,
white-label products and competing managed hosting need separate rights from the
owner, and deployed modifications carry a share-back duty. It is source
available rather than OSI open source, on purpose: that is what keeps the
congestion-priced, self-hosted path free.

## Getting in touch

**Open an issue in the relevant repository for questions about the software.**
Anyone may, with no approval and no fee. Tell us the repository, version,
platform and what you expected versus what happened.

Email `dominick253@gmail.com` for commercial licensing, self-hosting quotes,
church-eligibility confirmation, permission requests, sales and support. Use the
**Report a vulnerability** form on a repository's Security tab for security
problems, never a public issue.

Do not post or email secrets: no passwords, API tokens, private keys, signing
material, member data, private endpoints or customer names attached to a
commercial fact.

## What is not promised

No hosted service, uptime commitment, support SLA, store approval or device
certification comes with this source; unrun device and store checks stay named
as unrun in each repository's `RELEASE-STATUS.md`. Production for the existing
channels is separate from this source and is not changed by publishing it.
