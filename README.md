<p align="center">
  <img src="./assets/profile-banner.svg" alt="Oniel Alejo Feliz — Software Engineer" width="100%" />
</p>

<p align="center">
  <strong>Software Engineer</strong><br />
  TypeScript · Node.js · React / Next.js · PostgreSQL<br />
  Existing codebases · Reliability · Testing · Debugging
</p>

<p align="center">
  <a href="https://oniel-portfolio.vercel.app">Portfolio</a> ·
  <a href="https://oniel-portfolio.vercel.app/services">Maintenance services</a> ·
  <a href="mailto:Onielbf10@gmail.com">Email</a> ·
  <a href="https://www.linkedin.com/in/oniel-alejo-feliz-45b293312">LinkedIn</a>
</p>

## Engineering profile

I am a software engineer in Tampa, Florida, focused on TypeScript systems across React and Next.js interfaces, Node.js services, and PostgreSQL data boundaries. My strongest public work shows how I enter an unfamiliar repository, reproduce real behavior, respond to maintainer review, add regression coverage, and deliver a focused change through upstream CI.

I am open to software-engineering, full-stack, product-engineering, backend-leaning TypeScript, and React roles in Tampa or remote. I am a U.S. permanent resident and do not require employer sponsorship.

## Maintainer-reviewed open source

### [Reticle #278 — Persist learned routes](https://github.com/reticlehq/reticle/pull/278)

- Added bounded, batched persistence for routes learned through crawls and ordinary navigation.
- Preserved flows, run history, concurrency behavior, and absent-versus-empty semantics.
- Addressed growth and write-contention review findings; full cross-platform, unit, E2E, desktop, and install gates passed.
- Maintainer feedback: “the strongest PR in the queue right now.” [Read the review in context](https://github.com/reticlehq/reticle/pull/278#issuecomment-5289373138).

### [Apache Maka #2989 — Bound repeated MCP tool rediscovery](https://github.com/apache/maka/pull/2989)

- Stopped an MCP server from causing an unbounded tool-list refresh loop.
- Revised the design after substantive edge-case review covering slow notifications, snapshot preservation, and disconnect behavior.
- Maintainers confirmed the blockers were resolved before merge; upstream checks passed.

### [Apache Fineract #475 — Migrate client tests to Vitest](https://github.com/apache/fineract-backoffice-ui/pull/475)

- Migrated fifteen client-area specification files while preserving behavioral coverage.
- Passed maintainer approval plus unit, build, formatting, security, CodeQL, and extensive browser gates.

### [Code.Sydney / BlueHex #29 — Add production-build Playwright coverage](https://github.com/codesydney/bluehex/pull/29)

- Added desktop and mobile browser coverage for routes, focus behavior, navigation, form submission, and structural accessibility.
- Strengthened the assertions and CI workflow in response to maintainer review before merge.

### [Clarvia #269 — Improve checklist accessibility](https://github.com/clarvia-org/clarvia-graph/pull/269)

- Fixed focus containment and restoration, question labels, selected-state semantics, and keyboard-operable result cards.
- Merged after maintainer approval and repository validation.

Also merged: [Apache Fineract #431 — Accounting route titles](https://github.com/apache/fineract-backoffice-ui/pull/431). Open contributions remain labeled separately: [Agenta #6224](https://github.com/Agenta-AI/agenta/pull/6224) and [FinVerify #70](https://github.com/FinVerify/Finverify/pull/70).

## Selected systems

### [Relay — Webhook delivery and failure recovery](https://github.com/XonkelX/relay-webhook-delivery)

TypeScript, React, Cloudflare Workers, D1, Queues, Hono, Vitest, and Playwright. Relay demonstrates durable scheduling, signed requests, deterministic retries, lease recovery, encrypted endpoint secrets, replay lineage, and inspectable failure evidence. [Open the Failure Lab](https://relay-console.sinmanos.workers.dev/).

### [Next — Authorization and real-time queue state](https://github.com/XonkelX/next-queue)

Next.js, TypeScript, Supabase, PostgreSQL, Realtime, pgTAP, and Playwright. Next demonstrates database-enforced RLS, transactional commands, idempotency, private and public data boundaries, concurrency control, and reconnect recovery. [Open the live application](https://next-queue-omega.vercel.app).

## Need an existing TypeScript app fixed?

I work on scoped maintenance and reliability problems in React, Next.js, Node.js, Supabase, and PostgreSQL codebases:

- authentication, sessions, permissions, tenant isolation, and Supabase RLS
- API, query, data-loading, React state, forms, filters, and dashboard bugs
- build, Vercel, environment, runtime, CI, and unstable-test failures
- Playwright and Vitest regression coverage
- independent review and stabilization of AI-built or AI-assisted applications

The working pattern is simple: existing codebase → root-cause diagnosis → focused safe fix → regression evidence → clean pull request → clear explanation.

**[Start with one scoped issue](mailto:Onielbf10@gmail.com?subject=Scoped%20TypeScript%20maintenance%20issue)** or [review the service details](https://oniel-portfolio.vercel.app/services).
