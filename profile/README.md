# rocketdeploy

rocketdeploy designs and delivers software systems built for real-world use —
from early architecture decisions to stable, production deployments.

We focus on **end-to-end delivery**:
architecture → build → production → operability.

Our responsibility does not stop at writing code.
We design systems that can be built, deployed, operated, maintained, and evolved over time.

---

## What we build

We work across multiple system layers:

- application and platform architecture
- backend and frontend systems
- production-grade SPAs
- MVPs that can grow into maintainable platforms
- microservices and event-driven systems
- modular monoliths and legacy modernization
- service extraction from existing platforms
- AI-assisted operational systems
- BFF, Core API, MCP, and gateway-style service layers
- CMS-based operational platforms
- runtime supervision and reliability layers
- CI/CD and deployment automation
- refactoring and production hardening

We’re typically brought in when:

- a new product needs a solid technical foundation,
- an MVP needs to be designed with future growth in mind,
- complexity begins to slow delivery,
- prototypes need to become maintainable platforms,
- legacy systems need clearer boundaries,
- operational reliability becomes critical,
- systems require better ownership, runtime separation, and long-term evolution.

---

## Repository structure in this organization

This organization contains:

1. **Public architecture showcases**
2. **Production-grade implementations**
3. **Runtime and infrastructure repositories**

Repositories are intentionally structured to reflect real system boundaries.

Public showcase repositories expose the architectural structure and engineering approach without sensitive business logic, credentials, or customer data.

Some production and runtime repositories are private and are described here only at a high level.

---

## Public architecture showcases

Some repositories in this organization are **reference architecture showcases**.

They present:

- system boundaries and layering,
- execution flow and responsibilities,
- operational constraints,
- engineering trade-offs,
- reliability and maintainability concerns,
- modernization and extraction paths,
- runtime and infrastructure boundaries,

while intentionally omitting business-specific logic and sensitive details.

These repositories are not demo apps.
They are structured, technical explanations of real-world systems.

Some showcases also include evolution logs that document how a system changes over time: which boundaries became explicit, which runtime responsibilities were separated, and which areas became ready for future extraction.

### Platform Architecture & Modernization

- `showcase-commerce-platform-modernization`  
  Architecture showcase of a long-running commerce platform being modernized from a PHP/Yii2 modular monolith toward explicit boundaries, Core API facades, MCP-style tool access, AI-assisted operations, runtime separation, and future service extraction.

### WooCommerce & CMS Extensions

- `showcase-ops-layer-for-woocommerce`  
  Architecture showcase of a CMS-based operational layer built on WooCommerce.

- `showcase-woocommerce-admin-extension`  
  Architecture showcase of a structured admin extension pattern.

### Frontend Applications (SPA)

- `showcase-kiosk-web-application`  
  Production-grade kiosk SPA for touch-first, constrained execution environments.

- `showcase-internal-operational-spa`  
  Role-based internal operational system using RBAC, OAuth2, and the BFF pattern.

### Runtime & Reliability

- `showcase-kiosk-runtime-watchdog`  
  Minimal runtime supervision layer ensuring resilience of public-facing applications.

### Company Website

- `showcase-company-website`  
  Architecture showcase of a static, content-driven frontend system.

---

## Production and private work

In addition to public showcases, this organization also contains private production and runtime repositories.

They support work such as:

- building new operational platforms,
- developing backend and frontend systems,
- modernizing long-running applications,
- extracting services from existing platforms,
- building Core API, BFF, MCP, and gateway-style layers,
- implementing AI-assisted operational tooling,
- maintaining infrastructure and runtime composition.

Private repositories are intentionally not listed in detail here.

---

## Public production repositories

- `woocommerce-order-status-manager`  
  Production-ready WooCommerce plugin for structured order status management.

- `rocketdeploy-dev.github.io`  
  Static company website built with Astro and a content-driven case-study structure.

---

## How we work

rocketdeploy operates in a **delivery-first model**.

That means:

- clear ownership,
- pragmatic technical decisions,
- realistic scope control,
- production-oriented architecture from day one.

We avoid over-engineering,
but we also avoid shortcuts that create long-term operational debt.

We build new systems with future operability in mind, and we modernize existing systems incrementally when continuity matters.

---

## For founders

If you’re a non-technical or semi-technical founder,
we often act as a technical partner — helping you:

- define system architecture,
- make correct early technical decisions,
- design and build new products,
- turn an MVP into a maintainable platform,
- prevent expensive rewrites later,
- modernize existing systems without stopping the business.

More:
https://rocketdeploy.dev/en/for-founders

---

## Contact

If your product needs a solid technical foundation,
your MVP needs to become a maintainable platform,
or your existing system is starting to accumulate operational complexity:

👉 https://rocketdeploy.dev/en/contact
