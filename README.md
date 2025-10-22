# 👋 Hi, I'm Geoffroy Lorieux

**CTO @ [Simul'impact](https://simul-impact.fr)** | Building the future of sustainable impact simulation

📍 Nantes, France | 🍵 Currently focusing on environmental & social impact modeling

## 🚀 Current Stack

**Backend:** Elixir, Phoenix LiveView, Ecto, SQLite (SpatiaLite).  
**Frontend:** Tailwind CSS, VegaLite.  
**Quality:** Property-based testing (PropCheck), Dialyzer, Boundary, 100% documentation coverage.

---

## 🎯 What I'm Building: Simul'impact

Simul'impact is a SaaS platform that helps French municipalities and engineering firms simulate the environmental, social, and economic impacts of public infrastructure projects.

**Current Simulations:**
- **Public Lighting** - CO₂ emissions, energy consumption, financial ROI, accident reduction.
- **Urban Requalification** - Deimpermeabilization, mobility impacts, biodiversity restoration.

**Architecture Highlights:**
- 809+ commits in the last year.
- 100% documentation coverage with enforced doctests.
- Compile-time dependency validation for simulation graphs.
- Property-based testing across 50+ simulation modules.
- Real-time LiveView interfaces with French-first UX.

---

## 🏗️ Architecture Principles

**What guides my technical decisions:**

1. **Fail Fast** - Compile-time validation beats runtime errors.
2. **Make Illegal States Unrepresentable** - Use types to prevent bugs at the source.
3. **Security First** - Fail loudly on security issues (mismatched IDs, permission violations).
4. **No Silent Failures** - Every error is handled explicitly.
5. **YAGNI** - Every feature must overcome the "You Aren't Gonna Need It" argument.
6. **Test-Driven Development** - Property-based testing for complex domains.
7. **Documentation as Code** - 100% coverage with enforced doctests.

**Patterns I Use:**
- **Domain-Driven Design** - Clear bounded contexts (Lighting, Requalification, Accounts).
- **Macro-Driven Code Generation** - DSLs reduce boilerplate by 80%+.
- **Polyglot Persistence** - SQLite for transactional data, data warehouse and spatial queries.
- **Boundary Enforcement** - Compile-time dependency checks prevent architectural violations.
- **Audit-First Operations** - Every significant action logged by default.

---

## 📫 Let's Connect

- **GitHub:** [@glorieux](https://github.com/glorieux)
- **Company:** [Simul'Impact](https://simul-impact.fr)
- **Location:** Nantes, France
