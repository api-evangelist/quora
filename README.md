# Quora (quora)

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

Quora is a question-and-answer platform where users ask questions, share knowledge, and learn from experts on a wide variety of topics.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/quora/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/quora/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Access:** 3rd-Party

## Tags

- Community
- Knowledge
- Q&A

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-05-19

## APIs

### Quora Ads Conversion API

The Quora Ads Conversion API (CAPI) allows advertisers to send events such as website events, app installs, and offline conversions directly to Quora Ads Manager. This server-to-server integration enables real-time data connections that improve conversion match rates, increasing return on ad spend (ROAS) and lowering cost per action (CPA).

- **Human URL:** [https://www.quora.com/ads/conversion_api_doc](https://www.quora.com/ads/conversion_api_doc)

#### Tags

- Advertising
- Conversions
- Marketing

#### Properties

- [Documentation](https://www.quora.com/ads/conversion_api_doc)
- [Getting Started](https://quoraadsupport.zendesk.com/hc/en-us/articles/23065751885069-Conversion-API-Overview)
- [Partners](https://business.quora.com/api-partners)
- [Postman Collection](collections/quora-poe-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quora-poe-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Poe API

The Poe API is a developer platform by Quora that provides access to hundreds of AI models and bots through a single OpenAI-compatible interface. Developers can access frontier models from major labs including Claude, GPT-4, Gemini, and open-source models, as well as millions of community-created bots, all through one API key and billing system. The platform supports text, image, video, and audio generation modalities.

- **Human URL:** [https://creator.poe.com/](https://creator.poe.com/)
- **Base URL:** `https://api.poe.com/v1`

#### Tags

- AI
- Chatbots
- Generative AI
- Large Language Models

#### Properties

- [Documentation](https://creator.poe.com/docs)
- [Getting Started](https://creator.poe.com/docs/quick-start)
- [API Reference](https://creator.poe.com/api-reference)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/quora/refs/heads/main/openapi/quora-poe-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Open A I Compatible](https://creator.poe.com/docs/external-applications/openai-compatible-api)
- [Anthropic Compatible](https://creator.poe.com/docs/external-applications/anthropic-compatible-api)
- [Specification](https://creator.poe.com/docs/server-bots/poe-protocol-specification)
- [S D Ks](https://creator.poe.com/docs/server-bots/fastapi_poe-python-reference)
- [Usage A P I](https://creator.poe.com/docs/resources/usage-api)
- [Changelog](https://creator.poe.com/changelog)
- [Authentication](https://poe.com/api/keys)
- [S D Ks](https://github.com/poe-platform/fastapi_poe)
- [Postman Collection](collections/quora-poe-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/quora-poe-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.quora.com/)
- [Sign Up](https://www.quora.com/)
- [Login](https://www.quora.com/)
- [Blog](https://quorablog.quora.com/)
- [Support](https://help.quora.com/)
- [Terms of Service](https://help.quora.com/hc/en-us/articles/360000470706-Platform-Policies)
- [Privacy Policy](https://www.quora.com/about/privacy)
- [About](https://www.quora.com/about)
- [Portal](https://business.quora.com/)
- [Portal](https://creator.poe.com/)
- [Website](https://poe.com/)
- [Support](https://help.poe.com/)
- [X (Twitter)](https://twitter.com/Quora)
- [LinkedIn](https://www.linkedin.com/company/quora-inc-)
- [Git Hub](https://github.com/quora)
- [Git Hub](https://github.com/poe-platform)
