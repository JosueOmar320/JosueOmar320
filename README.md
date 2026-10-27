<div align="center">

# Hi, I'm Josue Omar 👋

**Backend & Full-Stack Developer** · C# / .NET · React / TypeScript · Managua, Nicaragua 🇳🇮

I build APIs and web apps with clean architecture, automated tests and CI/CD:
code that is easy to change and ships with confidence.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge)](https://linkedin.com/in/josue-flores-00356a2a2)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge)](mailto:josue.omar.75@hotmail.com)
[![Vitrina](https://img.shields.io/badge/Try_it-Vitrina_dashboard-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://catalogo-saas-nu.vercel.app)
[![Universe Explorer](https://img.shields.io/badge/Live_demo-Universe_Explorer-222222?style=for-the-badge&logo=githubpages&logoColor=white)](https://josueomar320.github.io/universe-explorer/)

</div>

## 🔭 Right now

- Building **[Vitrina](https://github.com/JosueOmar320/catalogo-saas)**, a multi-tenant SaaS with
  Next.js, Supabase (PostgreSQL) and an AI assistant, deployed on Vercel
- Growing as a **full-stack** developer on top of a .NET backend foundation: React, TypeScript
  and modern frontend testing
- Going deeper into **Azure** and **software architecture**
- Open to **backend and full-stack** opportunities

## 🧾 Featured projects

### 🛍️ Vitrina: website, catalog and PDF builder for small businesses

[![Vitrina: the site editor with Garfield, the AI assistant](https://raw.githubusercontent.com/JosueOmar320/catalogo-saas/main/docs/images/panel-garfield.jpg)](https://catalogo-saas-nu.vercel.app)

A multi-tenant SaaS where a small business builds its website **without code**. The site doubles
as a product catalog that takes orders over WhatsApp and exports to a print-ready PDF, and an AI
assistant edits it from plain-language requests. **Try the real dashboard without signing up:**
each visitor gets a private, pre-filled test business that is deleted after 24 hours.

[![CI](https://github.com/JosueOmar320/catalogo-saas/actions/workflows/ci.yml/badge.svg)](https://github.com/JosueOmar320/catalogo-saas/actions/workflows/ci.yml)
![Next.js 16](https://img.shields.io/badge/Next.js-16-black?logo=nextdotjs)
![TypeScript](https://img.shields.io/badge/TypeScript-strict-3178C6?logo=typescript&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-Postgres_%2B_RLS-3ECF8E?logo=supabase&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-deployed-000000?logo=vercel&logoColor=white)

- **Tenant isolation in the database:** Row Level Security on all 26 tables and on Storage, so a
  bug in the app or a direct API call cannot cross businesses, verified by 436 database tests
- **AI that can't go rogue:** the assistant only proposes typed, validated actions that run
  through the same code and permissions as the UI, and works without an API key
- **One model, two renderers:** the same sections and design tokens render the website (React) and
  the PDF catalog, so they never drift apart
- **Built for real use:** order inbox, customers, push notifications, sales funnel analytics,
  custom domains, sandboxed custom code, an admin console and a Spanish/English UI
- **Shipped like production code:** every change through a pull request with typecheck, lint,
  unit, database and end-to-end tests, CodeQL and a production build

| 1,000+ automated tests | 94% coverage | RLS on 26 tables | 60+ PRs through CI |
| :--------------------: | :----------: | :--------------: | :-----------------: |

<table>
  <tr>
    <td><a href="https://catalogo-saas-nu.vercel.app/demo"><img src="https://raw.githubusercontent.com/JosueOmar320/catalogo-saas/main/docs/images/site-home.jpg" alt="Public site of a business"></a></td>
    <td><a href="https://catalogo-saas-nu.vercel.app"><img src="https://raw.githubusercontent.com/JosueOmar320/catalogo-saas/main/docs/images/panel-orders.jpg" alt="Order inbox"></a></td>
    <td><a href="https://catalogo-saas-nu.vercel.app"><img src="https://raw.githubusercontent.com/JosueOmar320/catalogo-saas/main/docs/images/panel-stats.jpg" alt="Sales funnel analytics"></a></td>
    <td><a href="https://catalogo-saas-nu.vercel.app/demo/pdf"><img src="https://raw.githubusercontent.com/JosueOmar320/catalogo-saas/main/docs/images/pdf-catalog.jpg" alt="PDF catalog"></a></td>
  </tr>
</table>

**[Try the dashboard](https://catalogo-saas-nu.vercel.app)** ·
**[Repository](https://github.com/JosueOmar320/catalogo-saas)** ·
[Engineering highlights](https://github.com/JosueOmar320/catalogo-saas#engineering-highlights) ·
[Architecture](https://github.com/JosueOmar320/catalogo-saas#architecture)

### 🪐 Universe Explorer

[![Universe Explorer: one shell, many universes](https://raw.githubusercontent.com/JosueOmar320/universe-explorer/main/public/og-image.png)](https://josueomar320.github.io/universe-explorer/)

Four public APIs (Rick and Morty, Pokémon, Star Wars, Harry Potter), each with its own themed
interface and data strategy, inside one shared, type-safe React shell.

[![CI/CD](https://github.com/JosueOmar320/universe-explorer/actions/workflows/ci.yml/badge.svg)](https://github.com/JosueOmar320/universe-explorer/actions/workflows/ci.yml)
![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-strict-3178C6?logo=typescript&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-5-FF4154?logo=reactquery&logoColor=white)
![WCAG 2.2 AA](https://img.shields.io/badge/WCAG_2.2-AA-005A9C)

- **A data strategy per API:** server-side search, a cached index searched locally, whole
  collections filtered in memory and next-page prefetching, each chosen for what its API allows
- **Type-safe architecture:** a universe registry drives navigation, routing and the global ⌘K
  search; a half-registered universe doesn't compile
- **Accessible and bilingual:** WCAG 2.2 AA checked with axe on every page type, keyboard and
  focus management, English and Spanish
- **Shipped like production code:** 233 unit and integration tests (92% coverage), 106
  end-to-end tests and Lighthouse budgets in a CI/CD pipeline that only deploys when everything
  passes

| 233 unit & integration tests | 92% coverage | 106 E2E tests | Lighthouse a11y 100 |
| :--------------------------: | :----------: | :-----------: | :-----------------: |

<table>
  <tr>
    <td><a href="https://josueomar320.github.io/universe-explorer/rick-and-morty/"><img src="https://raw.githubusercontent.com/JosueOmar320/universe-explorer/main/docs/screenshots/rick-and-morty.png" alt="Rick and Morty universe"></a></td>
    <td><a href="https://josueomar320.github.io/universe-explorer/pokemon/"><img src="https://raw.githubusercontent.com/JosueOmar320/universe-explorer/main/docs/screenshots/pokemon.png" alt="Pokémon universe"></a></td>
    <td><a href="https://josueomar320.github.io/universe-explorer/star-wars/"><img src="https://raw.githubusercontent.com/JosueOmar320/universe-explorer/main/docs/screenshots/star-wars.png" alt="Star Wars universe"></a></td>
    <td><a href="https://josueomar320.github.io/universe-explorer/harry-potter/"><img src="https://raw.githubusercontent.com/JosueOmar320/universe-explorer/main/docs/screenshots/harry-potter.png" alt="Harry Potter universe"></a></td>
  </tr>
</table>

**[Live demo](https://josueomar320.github.io/universe-explorer/)** ·
**[Repository](https://github.com/JosueOmar320/universe-explorer)** ·
[Architecture](https://github.com/JosueOmar320/universe-explorer#-architecture) ·
[Testing](https://github.com/JosueOmar320/universe-explorer#-testing--quality)

### 💳 [Banking API](https://github.com/JosueOmar320/BankingApp)

![.NET 8](https://img.shields.io/badge/.NET-8-512BD4?logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-Web_API-512BD4?logo=dotnet&logoColor=white)
![EF Core](https://img.shields.io/badge/EF_Core-SQLite-003B57?logo=sqlite&logoColor=white)
![NUnit](https://img.shields.io/badge/tests-NUnit_%2B_Moq-25A162)
![Swagger](https://img.shields.io/badge/docs-Swagger-85EA2D?logo=swagger&logoColor=black)

REST API for customers, bank accounts and transactions: deposits, withdrawals, interest and
balance summaries.

- **Clean Architecture** in four projects (Domain, Application, Infrastructure, API), with
  repositories and services behind interfaces
- Business rules validated in the application services (positive amounts, no withdrawal over the
  available balance)
- **39 unit tests** for controllers, services and repositories with NUnit, Moq and EF Core InMemory
- Interactive API documentation with **Swagger**

## 🛠️ Tech stack

|                    |                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| ------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Languages**      | ![C#](https://img.shields.io/badge/C%23-239120) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-336791)                                                                                                                                                                                                                                    |
| **Backend**        | ![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?logo=dotnet&logoColor=white) ![EF Core](https://img.shields.io/badge/Entity_Framework_Core-512BD4?logo=dotnet&logoColor=white) ![REST APIs](https://img.shields.io/badge/REST_APIs-555555) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?logo=supabase&logoColor=white) ![Swagger](https://img.shields.io/badge/Swagger-85EA2D?logo=swagger&logoColor=black)                                                                                 |
| **Frontend**       | ![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black) ![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?logo=reactquery&logoColor=white) ![React Router](https://img.shields.io/badge/React_Router-CA4245?logo=reactrouter&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white) ![HTML & CSS](https://img.shields.io/badge/HTML_%26_CSS-E34F26?logo=html5&logoColor=white) |
| **Testing**        | ![xUnit](https://img.shields.io/badge/xUnit-512BD4) ![NUnit](https://img.shields.io/badge/NUnit-25A162) ![Vitest](https://img.shields.io/badge/Vitest-6E9F18?logo=vitest&logoColor=white) ![Testing Library](https://img.shields.io/badge/Testing_Library-E33332?logo=testinglibrary&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33)                                                              |
| **Databases**      | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927) ![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white)                                                                                                                                                                                                                                                                                  |
| **Cloud & DevOps** | ![Azure](https://img.shields.io/badge/Azure-0078D4) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white) ![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?logo=githubpages&logoColor=white)                                                                                                                                                                    |

## 🧭 How I work

- **SOLID** and **Clean Architecture**: business logic independent of frameworks and databases
- **Security in depth**: authorization enforced in the database too, not only in the app
- **Tests are part of the feature**, not an afterthought
- **Small, reviewable commits** and a CI pipeline that catches problems before they ship
- **Accessibility and performance are measured**, not assumed

## 📫 Let's connect

I'm open to backend and full-stack roles. The fastest way to reach me is
**[LinkedIn](https://www.linkedin.com/in/josue-flores-00356a2a2)** or
**[email](mailto:josue.omar.75@hotmail.com)**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Josue_Flores-0A66C2?style=for-the-badge)](https://www.linkedin.com/in/josue-flores-00356a2a2)

<div align="center">

<sub>Outside of code: reading about technology and playing adventure and strategy games 🎮</sub>

</div>
