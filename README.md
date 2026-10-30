# Kakao

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Kakao Corp. is the South Korean technology group behind KakaoTalk — the dominant mobile messenger in Korea — along with KakaoPay (payments), Kakao Bank (digital bank), KakaoMobility (taxi, navigation, parking), KakaoMap, Kakao Games, Kakao Entertainment (Melon, Kakao Webtoon, Daum), and KakaoCloud. Kakao runs its public developer platform at developers.kakao.com, exposing REST APIs for Kakao Login (OAuth 2.0), Kakao Sync, KakaoTalk Share / Message / Friend Picker / Channel, KakaoStory, KakaoNavi, KakaoMap, Local search, Daum Search, KakaoPay (PG / online easy-pay), and KoGPT generative AI. KakaoMobility and Kakao Enterprise / KakaoCloud each operate additional partner- facing developer surfaces.

**Areas:** Messaging · Maps · Navigation · Payments · Search · South Korea · Identity · Authentication · KakaoTalk · LLM

## Kakao on APIs.io

Everything profiled for Kakao is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/kakao/](https://apis.io/providers/kakao/)** — or go straight to one of the APIs or properties below.

### APIs (21)

- [Kakao Login (OAuth 2.0) API](https://apis.io/apis/kakao/kakao-login/) — Kakao Login is Korea's most widely used social-identity provider, built on OAuth 2.0 / OpenID Connect. The API issues access and refresh tokens, returns…
- [Kakao Sync API](https://apis.io/apis/kakao/kakao-sync/) — Kakao Sync extends Kakao Login with a one-click signup experience that simultaneously creates an in-app account and (optionally) adds a KakaoTalk Channel…
- [KakaoTalk Sharing API](https://apis.io/apis/kakao/kakaotalk-share/) — KakaoTalk Sharing lets external apps and websites share rich "Feed", "List", "Location", "Calendar", "Commerce", and custom-template messages into KakaoTalk…
- [KakaoTalk Message API](https://apis.io/apis/kakao/kakaotalk-message/) — KakaoTalk Message sends template-based messages from a Kakao-Linked app to the authenticated user themselves or to consenting KakaoTalk friends.
- [KakaoTalk Channel API](https://apis.io/apis/kakao/kakaotalk-channel/) — KakaoTalk Channel APIs manage a brand's Channel relationship with users — including add-friend status, Alimtalk-style notification messages (delivered via…
- [KakaoTalk Friends API](https://apis.io/apis/kakao/kakaotalk-friends/) — Returns the list of KakaoTalk friends who have also signed into a Kakao-Linked app, for friend-picker, invite, and social-feature experiences subject to…
- [KakaoStory API](https://apis.io/apis/kakao/kakaostory/) — KakaoStory APIs let apps publish posts and read user content on Kakao's social timeline product (legacy but still supported in Korea).
- [Kakao Local API](https://apis.io/apis/kakao/local/) — Kakao Local API offers address-to-coordinate (and reverse) geocoding, keyword and category place search, and administrative-region lookup for Korean…
- [KakaoMap Web / JavaScript SDK](https://apis.io/apis/kakao/kakaomap-web/) — KakaoMap exposes Korean tile maps, markers, overlays, static maps, and roadview / panorama services for web and mobile applications.
- [KakaoNavi (Driving Directions) API](https://apis.io/apis/kakao/kakaonavi/) — KakaoNavi exposes driving directions, multi-waypoint route planning, ETA, and Future Driving directions (predictive ETA), and a native "Send to Kakao Navi"…
- [Daum Search API](https://apis.io/apis/kakao/daum-search/) — Daum Search API returns search results from Daum's web, vClip video, image, blog, book, café, and Q&A indexes, complementing Kakao Local for content discovery.
- [KakaoPay Online (Easy-Pay) API](https://apis.io/apis/kakao/kakaopay-online/) — KakaoPay Online (also known as KakaoPay Easy-Pay) lets online merchants accept KakaoPay wallet payments for one-time and subscription purchases, with order…
- [KakaoPay Subscription Payments API](https://apis.io/apis/kakao/kakaopay-subscription/) — Subscription Payments API enables recurring KakaoPay billing for SaaS, content, and membership models — using a one-time SID (subscription ID) handshake…
- [KakaoPay PG (Payment Gateway) API](https://apis.io/apis/kakao/kakaopay-pg/) — KakaoPay PG is the full Korean payment-gateway product offering card, bank-transfer, point, and KakaoPay wallet acceptance for enterprise merchants.
- [KoGPT API](https://apis.io/apis/kakao/kogpt/) — KoGPT is Kakao Brain's Korean-language large language model. The KoGPT API provides text generation, summarization, paraphrasing, and classification for…
- [Karlo (Text-to-Image) API](https://apis.io/apis/kakao/karlo/) — Karlo is Kakao Brain's diffusion-based text-to-image generation API, supporting Korean and English prompts and multiple aspect ratios.
- [KakaoMobility Business API](https://apis.io/apis/kakao/kakaomobility-business/) — KakaoMobility's Business API powers KakaoT corporate mobility — letting enterprise platforms book Kakao T taxi rides, manage corporate accounts, and…
- [Kakao OIDC API](https://apis.io/apis/kakao/kakao-oidc-api/) — OpenID Connect discovery, JWKS, and user info.
- [Kakao Service Terms API](https://apis.io/apis/kakao/kakao-service-terms-api/) — Manage Kakao Sync service-terms consent.
- [Kakao User API](https://apis.io/apis/kakao/kakao-user-api/) — Logged-in user information, scopes, and account linking.
- [Kakao O Auth API](https://apis.io/apis/kakao/kakao-oauth-api/) — Kakao Login OAuth 2.0 authorization, token, and logout flows.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Kakao Agentic Access](https://apis.io/agentic-access/kakao/kakao-agentic-access/)

#### Collections (5)

Postman and Open Collection request collections.

- [Kakao Login REST API](https://apis.io/collections/kakao/open-kakao/)
- [Kakao Login REST OAuth API](https://apis.io/collections/kakao/open-kakao-oauth-api/)
- [Kakao Login REST OAuth OIDC API](https://apis.io/collections/kakao/open-kakao-oidc-api/)
- [Kakao Login REST OAuth Service Terms API](https://apis.io/collections/kakao/open-kakao-service-terms-api/)
- [Kakao Login REST OAuth User API](https://apis.io/collections/kakao/open-kakao-user-api/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Kakao Authentication](https://apis.io/security/kakao/kakao-authentication/)
- [Kakao Domain Security](https://apis.io/security/kakao/kakao-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Kakao Plans Pricing](https://apis.io/plans/kakao/kakao-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Kakao Rate Limits](https://apis.io/rate-limits/kakao/kakao-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Kakao Finops](https://apis.io/finops/kakao/kakao-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.kakaocorp.com/)
- [Documentation](https://developers.kakao.com/docs)
- [Blog](https://tech.kakao.com/feed/)

## API Evangelist rating

**Kin Score 25.6** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 67.0 |
| Contract quality | 47.8 |
| Contract governance | 0.0 |
| Operational transparency | 10.5 |
| Developer ergonomics | 33.3 |
| Access clarity | 5.3 |

**Agent readiness 17.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 10.0** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/kakao/](https://apis.io/providers/kakao/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Kakao: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/kakao/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
