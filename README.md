# Django CMS (django-cms)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Django CMS is an open-source, enterprise-grade content management system built on Django and Python. It provides a REST API via the djangocms-rest package (built on Django REST Framework and drf-spectacular) that exposes pages, plugins, placeholders, navigation menus, breadcrumbs, and content structures as a browsable, read-only JSON/OpenAPI 3 interface. The API enables headless CMS deployments, allowing decoupled frontend applications — SPAs, static site generators, and mobile apps — to consume CMS-managed content with full multi-language and multi-site support.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/django-cms/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/django-cms/refs/heads/main/apis.yml)

## Tags

- CMS
- Content Management
- Django
- Python
- Headless CMS
- REST API
- Open Source
- Pages
- Plugins
- Placeholders

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### djangocms-rest API

Read-only REST/JSON API for Django CMS that enables decoupled frontend applications to consume CMS-managed content. Built on Django REST Framework with OpenAPI 3 schema generation via drf-spectacular. Exposes endpoints for languages, pages, page trees, page search, placeholders, plugins, navigation menus, breadcrumbs, and a health check. Supports multi-language, multi-site, draft/preview access, and is compatible with Redis/Memcached caching.

- **Human URL:** [https://djangocms-rest.readthedocs.io/](https://djangocms-rest.readthedocs.io/)
- **Base URL:** `https://example.com/api/`

#### Tags

- Pages
- Plugins
- Placeholders
- Navigation
- Headless CMS
- REST
- OpenAPI

#### Properties

- [Documentation](https://djangocms-rest.readthedocs.io/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/django-cms/main/openapi/djangocms-rest-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/django-cms/main/json-schema/djangocms-page-content-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/django-cms/main/json-ld/djangocms-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [GitHub Repository](https://github.com/django-cms/djangocms-rest)
- [Py P I](https://pypi.org/project/djangocms-rest/)

## Common Properties

- [Website](https://www.django-cms.org/en/)
- [Documentation](https://docs.django-cms.org/en/latest/)
- [Git Hub Org](https://github.com/django-cms)
- [LinkedIn](https://www.linkedin.com/company/django-cms-association)
- [Blog](https://www.django-cms.org/en/blog/)
- [Pricing](https://www.django-cms.org/en/)
- [Status Page](https://status.django-cms.org/)
- [X (Twitter)](https://x.com/djangocms)
- [Plans](plans/django-cms-plans-pricing.yml)
- [Rate Limits](rate-limits/django-cms-rate-limits.yml)
- [Fin Ops](finops/django-cms-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
