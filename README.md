# Unified Developer API Hub (North Star Vision)

### ▶ [View the live prototype](https://snwl-wchen.github.io/API-Hub-North-Star/)

A working prototype for a unified developer portal, designed to consolidate fragmented API documentation across multiple product lines into a single reference partners can actually navigate.

---

## The problem

API documentation lived in different places, in different formats, with different conventions depending on which product a partner was integrating against. Getting credentials meant going through a support process rather than self-serving. The result was avoidable friction for developers and avoidable support volume.

## What this prototype covers

- **Product card landing page** so developers can find the right API surface immediately
- **Sidebar navigation** with endpoint listings and HTTP method badges
- **Parameters and Responses tabs** on each endpoint, with JSON examples
- **Try It Out** interaction for testing calls against a reference
- **Credential flow** supporting both OAuth 2.0 for third-party integrations and API keys for server-to-server
- Built against a spec-first model using OpenAPI 3.1

## How I approached it

I built this as a working prototype rather than a specification document, because information architecture is difficult to evaluate in the abstract. Putting a navigable version in front of stakeholders surfaced structural problems that a wireframe would not have exposed, and it gave engineering something concrete to build against.

The measure of success for a developer portal is whether someone can accomplish what they need without asking anyone for help. Every decision here was made against that standard.

---

**Role:** Product Manager. I owned the requirements, information architecture, and interaction design, and built this prototype myself.

**Stack:** HTML, CSS, JavaScript

---

