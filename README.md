# Kakao (kakao)

Kakao Corp. is the South Korean technology group behind
KakaoTalk — the dominant mobile messenger in Korea — along with
KakaoPay (payments), Kakao Bank (digital bank), KakaoMobility
(taxi, navigation, parking), KakaoMap, Kakao Games, Kakao
Entertainment (Melon, Kakao Webtoon, Daum), and KakaoCloud.
Kakao runs its public developer platform at developers.kakao.com,
exposing REST APIs for Kakao Login (OAuth 2.0), Kakao Sync,
KakaoTalk Share / Message / Friend Picker / Channel, KakaoStory,
KakaoNavi, KakaoMap, Local search, Daum Search, KakaoPay (PG /
online easy-pay), and KoGPT generative AI. KakaoMobility and
Kakao Enterprise / KakaoCloud each operate additional partner-
facing developer surfaces.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/kakao/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/kakao/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** Public

## Tags

- Messaging
- Maps
- Navigation
- Payments
- Search
- Korea
- Identity
- OAuth2
- KakaoTalk
- LLM

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Kakao Login (OAuth 2.0) API

Kakao Login is Korea's most widely used social-identity
provider, built on OAuth 2.0 / OpenID Connect. The API
issues access and refresh tokens, returns user profile
attributes (nickname, profile image, email, gender, age
range), and supports auto-linking to in-app accounts.

- **Human URL:** [https://developers.kakao.com/docs/latest/en/kakaologin/common](https://developers.kakao.com/docs/latest/en/kakaologin/common)
- **Base URL:** `https://kapi.kakao.com`

#### Tags

- Identity
- OAuth2
- Login
- Korea

#### Properties

- [Documentation](https://developers.kakao.com/docs/latest/en/kakaologin/common)
- [R E S T Reference](https://developers.kakao.com/docs/latest/en/kakaologin/rest-api)
- [Postman Collection](collections/kakao.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kakao.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kakao Sync API

Kakao Sync extends Kakao Login with a one-click signup
experience that simultaneously creates an in-app account
and (optionally) adds a KakaoTalk Channel friendship for
Korean services.

- **Human URL:** [https://developers.kakao.com/docs/latest/en/kakaosync/common](https://developers.kakao.com/docs/latest/en/kakaosync/common)
- **Base URL:** `https://kapi.kakao.com`

#### Tags

- Identity
- Onboarding
- KakaoTalk
- Korea

#### Properties

- [Documentation](https://developers.kakao.com/docs/latest/en/kakaosync/common)
- [Postman Collection](collections/kakao.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kakao.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### KakaoTalk Sharing API

KakaoTalk Sharing lets external apps and websites share rich
"Feed", "List", "Location", "Calendar", "Commerce", and
custom-template messages into KakaoTalk chats.

- **Human URL:** [https://developers.kakao.com/docs/latest/en/message/common](https://developers.kakao.com/docs/latest/en/message/common)
- **Base URL:** `https://kapi.kakao.com`

#### Tags

- Messaging
- Sharing
- KakaoTalk
- Templates

#### Properties

- [Documentation](https://developers.kakao.com/docs/latest/en/message/common)
- [Postman Collection](collections/kakao.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kakao.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### KakaoTalk Message API

KakaoTalk Message sends template-based messages from a
Kakao-Linked app to the authenticated user themselves or
to consenting KakaoTalk friends.

- **Human URL:** [https://developers.kakao.com/docs/latest/en/message/rest-api](https://developers.kakao.com/docs/latest/en/message/rest-api)
- **Base URL:** `https://kapi.kakao.com`

#### Tags

- Messaging
- KakaoTalk
- Notifications

#### Properties

- [Documentation](https://developers.kakao.com/docs/latest/en/message/rest-api)
- [Postman Collection](collections/kakao.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kakao.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### KakaoTalk Channel API

KakaoTalk Channel APIs manage a brand's Channel
relationship with users — including add-friend status,
Alimtalk-style notification messages (delivered via
Kakao's BizMessage partners), and consult routing.

- **Human URL:** [https://developers.kakao.com/docs/latest/en/kakaotalk-channel/common](https://developers.kakao.com/docs/latest/en/kakaotalk-channel/common)
- **Base URL:** `https://kapi.kakao.com`

#### Tags

- KakaoTalk
- Channel
- Notifications
- BizMessage

#### Properties

- [Documentation](https://developers.kakao.com/docs/latest/en/kakaotalk-channel/common)
- [Postman Collection](collections/kakao.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kakao.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### KakaoTalk Friends API

Returns the list of KakaoTalk friends who have also signed
into a Kakao-Linked app, for friend-picker, invite, and
social-feature experiences subject to user consent.

- **Human URL:** [https://developers.kakao.com/docs/latest/en/message/rest-api#friend](https://developers.kakao.com/docs/latest/en/message/rest-api#friend)
- **Base URL:** `https://kapi.kakao.com`

#### Tags

- KakaoTalk
- Friends
- Social Graph

#### Properties

- [Documentation](https://developers.kakao.com/docs/latest/en/message/rest-api#friend)
- [Postman Collection](collections/kakao.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kakao.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### KakaoStory API

KakaoStory APIs let apps publish posts and read user
content on Kakao's social timeline product (legacy but
still supported in Korea).

- **Human URL:** [https://developers.kakao.com/docs/latest/en/kakaostory/common](https://developers.kakao.com/docs/latest/en/kakaostory/common)
- **Base URL:** `https://kapi.kakao.com`

#### Tags

- Social
- KakaoStory
- Timeline

#### Properties

- [Documentation](https://developers.kakao.com/docs/latest/en/kakaostory/common)
- [Postman Collection](collections/kakao.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kakao.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kakao Local API

Kakao Local API offers address-to-coordinate (and reverse)
geocoding, keyword and category place search, and
administrative-region lookup for Korean addresses and POIs.

- **Human URL:** [https://developers.kakao.com/docs/latest/en/local/dev-guide](https://developers.kakao.com/docs/latest/en/local/dev-guide)
- **Base URL:** `https://dapi.kakao.com`

#### Tags

- Local Search
- Geocoding
- Places
- Korea

#### Properties

- [Documentation](https://developers.kakao.com/docs/latest/en/local/dev-guide)
- [Postman Collection](collections/kakao.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kakao.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### KakaoMap Web / JavaScript SDK

KakaoMap exposes Korean tile maps, markers, overlays,
static maps, and roadview / panorama services for web and
mobile applications.

- **Human URL:** [https://apis.map.kakao.com/web/documentation/](https://apis.map.kakao.com/web/documentation/)
- **Base URL:** `https://dapi.kakao.com`

#### Tags

- Maps
- Tiles
- Roadview
- Korea

#### Properties

- [Documentation](https://apis.map.kakao.com/web/documentation/)
- [Postman Collection](collections/kakao.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kakao.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### KakaoNavi (Driving Directions) API

KakaoNavi exposes driving directions, multi-waypoint route
planning, ETA, and Future Driving directions (predictive
ETA), and a native "Send to Kakao Navi" handoff for Korean
mobile apps.

- **Human URL:** [https://developers.kakao.com/docs/latest/en/kakaonavi/common](https://developers.kakao.com/docs/latest/en/kakaonavi/common)
- **Base URL:** `https://apis-navi.kakaomobility.com`

#### Tags

- Navigation
- Directions
- Driving
- Korea

#### Properties

- [Documentation](https://developers.kakao.com/docs/latest/en/kakaonavi/common)
- [Postman Collection](collections/kakao.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kakao.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Daum Search API

Daum Search API returns search results from Daum's web,
vClip video, image, blog, book, café, and Q&A indexes,
complementing Kakao Local for content discovery.

- **Human URL:** [https://developers.kakao.com/docs/latest/en/daum-search/common](https://developers.kakao.com/docs/latest/en/daum-search/common)
- **Base URL:** `https://dapi.kakao.com`

#### Tags

- Search
- Daum
- Web
- Images

#### Properties

- [Documentation](https://developers.kakao.com/docs/latest/en/daum-search/common)
- [Postman Collection](collections/kakao.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kakao.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### KakaoPay Online (Easy-Pay) API

KakaoPay Online (also known as KakaoPay Easy-Pay) lets
online merchants accept KakaoPay wallet payments for
one-time and subscription purchases, with order create,
approve, cancel, and refund operations.

- **Human URL:** [https://developers.kakaopay.com/docs/payment/online/single-payment](https://developers.kakaopay.com/docs/payment/online/single-payment)
- **Base URL:** `https://open-api.kakaopay.com`

#### Tags

- Payments
- KakaoPay
- Checkout
- Korea

#### Properties

- [Documentation](https://developers.kakaopay.com/docs/payment/online/single-payment)
- [Postman Collection](collections/kakao.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kakao.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### KakaoPay Subscription Payments API

Subscription Payments API enables recurring KakaoPay
billing for SaaS, content, and membership models — using
a one-time SID (subscription ID) handshake followed by
server-side recurring charge calls.

- **Human URL:** [https://developers.kakaopay.com/docs/payment/online/subscription-payment](https://developers.kakaopay.com/docs/payment/online/subscription-payment)
- **Base URL:** `https://open-api.kakaopay.com`

#### Tags

- Payments
- Subscriptions
- Recurring
- KakaoPay

#### Properties

- [Documentation](https://developers.kakaopay.com/docs/payment/online/subscription-payment)
- [Postman Collection](collections/kakao.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kakao.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### KakaoPay PG (Payment Gateway) API

KakaoPay PG is the full Korean payment-gateway product
offering card, bank-transfer, point, and KakaoPay
wallet acceptance for enterprise merchants.

- **Human URL:** [https://developers.kakaopay.com/docs/payment/pg](https://developers.kakaopay.com/docs/payment/pg)
- **Base URL:** `https://open-api.kakaopay.com`

#### Tags

- Payment Gateway
- Cards
- Bank Transfer
- Korea

#### Properties

- [Documentation](https://developers.kakaopay.com/docs/payment/pg)
- [Postman Collection](collections/kakao.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kakao.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### KoGPT API

KoGPT is Kakao Brain's Korean-language large language model.
The KoGPT API provides text generation, summarization,
paraphrasing, and classification for Korean text.

- **Human URL:** [https://developers.kakao.com/docs/latest/en/kogpt/rest-api](https://developers.kakao.com/docs/latest/en/kogpt/rest-api)
- **Base URL:** `https://api.kakaobrain.com`

#### Tags

- LLM
- Generative AI
- Korean
- KoGPT

#### Properties

- [Documentation](https://developers.kakao.com/docs/latest/en/kogpt/rest-api)
- [Postman Collection](collections/kakao.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kakao.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Karlo (Text-to-Image) API

Karlo is Kakao Brain's diffusion-based text-to-image
generation API, supporting Korean and English prompts and
multiple aspect ratios.

- **Human URL:** [https://developers.kakao.com/docs/latest/en/karlo/rest-api](https://developers.kakao.com/docs/latest/en/karlo/rest-api)
- **Base URL:** `https://api.kakaobrain.com`

#### Tags

- Text-to-Image
- Generative AI
- Diffusion
- Karlo

#### Properties

- [Documentation](https://developers.kakao.com/docs/latest/en/karlo/rest-api)
- [Postman Collection](collections/kakao.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kakao.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### KakaoMobility Business API

KakaoMobility's Business API powers KakaoT corporate
mobility — letting enterprise platforms book Kakao T taxi
rides, manage corporate accounts, and reconcile employee
trips for expense and HR systems.

- **Human URL:** [https://business.kakaomobility.com/](https://business.kakaomobility.com/)
- **Base URL:** `https://api.kakaomobility.com`

#### Tags

- Mobility
- Taxi
- Corporate
- Korea

#### Properties

- [Product Page](https://business.kakaomobility.com/)
- [Postman Collection](collections/kakao.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kakao.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Corporate Website](https://www.kakaocorp.com/)
- [Developer Portal](https://developers.kakao.com/)
- [Documentation](https://developers.kakao.com/docs)
- [Kakao Talk](https://www.kakaocorp.com/page/service/service/KakaoTalk)
- [Kakao Map Web](https://apis.map.kakao.com/)
- [Kakao Pay Developers](https://developers.kakaopay.com/)
- [Kakao Mobility](https://www.kakaomobility.com/)
- [Kakao Cloud](https://www.kakaocloud.com/)
- [Kakao Brain](https://www.kakaobrain.com/)
- [Git Hub](https://github.com/kakao)
- [Tech Blog](https://tech.kakao.com/)
- [Investor Relations](https://www.kakaocorp.com/page/ir/)
- [Newsroom](https://www.kakaocorp.com/page/detail)
- [Careers](https://careers.kakao.com/)
- [LinkedIn](https://www.linkedin.com/company/kakaocorp/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
