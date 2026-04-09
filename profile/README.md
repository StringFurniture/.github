# String Furniture

We build and run the software behind String Furniture and Grythyttan Stalmobler.

That means commerce, configurators, reseller tooling, internal portals, and the integrations that keep products, prices, documents, orders, and customer workflows in sync across the stack.

## What we ship

### Commerce and storefronts

-   D2C and market-specific commerce flows for String Furniture.
-   Modern Laravel + Inertia storefront work for the next generation of web platforms.
-   Legacy and transitional commerce architecture where business reality refuses to wait for a clean greenfield rewrite.

### Planners and configurators

-   The String planner ecosystem, including embedded configurators, saved designs, partner-facing APIs, and BYO payload conversion.
-   Wrapper and host applications for public planner experiences.
-   Supporting experiments and playgrounds used to harden UX and integration contracts before rollout.

### Portals and internal operations

-   Reseller and admin portals for ordering, claims, media, documents, and other backoffice workflows.
-   Internal dashboards and support tooling for day-to-day operations.
-   Debug and observability utilities for tracing problems before they ruin somebody's afternoon.

### Integrations

-   Commerce integrations between storefronts, PIM, ERP, shipping providers, and external services.
-   API and sync layers for product data, carts, orders, and price lists.
-   Shared runtime packages and infrastructure glue for keeping multiple apps aligned instead of drifting into chaos.

## Selected product streams

### String Furniture

-   `string-web-inertia`: the current Inertia-based web platform work.
-   `string-portal` and `string-portal-inertia`: backoffice and reseller workflows.
-   `string-planner`, `string-planner-inertia`, and related planner tooling: configurator hosting, saved designs, and public integration APIs.
-   `String.BigComIntegration-main`: BigCommerce-era architecture tying together storefronts, microservices, ERP, and PIM.
-   `string-dashboard`, `string-elevate`, and related internal tools: operational visibility and debugging.
-   `string-norce` and adjacent integration work: commerce service connectivity and API orchestration.

### Grythyttan

-   `grythyttan-portal`: portal and operational tooling for the Grythyttan business.
-   `grythyttan-inertia`: newer Inertia-based application work aligned with the broader platform direction.

## How we work

-   Laravel, Inertia, Vue, TypeScript, Tailwind, and a very low tolerance for accidental complexity.
-   Incremental modernization over rewrite theater.
-   Product systems built to survive real-world catalog, pricing, localization, and reseller constraints.

## Themes across the repos

-   Multi-market commerce
-   Configurable products
-   Reseller and partner workflows
-   PIM and ERP integrations
-   Operational tooling
-   Migration from legacy stacks to cleaner Laravel + Inertia platforms

## Repository landscape

You will find a mix of:

-   active production applications
-   successor platforms replacing older systems
-   integration services and experiments
-   internal tools that exist because waiting for off-the-shelf software was a bad joke

Some repositories are public packages or prototypes. Many are operational company systems and are intentionally private.

## Hiring signal

If you enjoy untangling commerce edge cases, building admin UX that people actually use, and shipping pragmatic software for physical products at scale, you would probably feel at home here.
