### Ben Montesinos
**Math-CS @ UCSD | Full-Stack Development | Data Analysis | Applied ML**

Undergraduate at UC San Diego studying Mathematics-Computer Science. Building production-minded systems in Java/TypeScript/Python. From ecommerce storefronts to data pipelines and analytical tooling.

<p>
  <a href="mailto:benjimontesinos@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/benmontesinos/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### [SilvrStns](https://github.com/BenMonte/silvrstns)
Custom ecommerce storefront for a gothic jewelry brand.

- Next.js 16 App Router with React 19 and Tailwind CSS v4
- Stripe Checkout with server-side session creation
- Inventory-aware cart logic and dynamic product pages
- Integrated Google Analytics 4 and Microsoft Clarity

`TypeScript` `Next.js` `React` `Tailwind CSS` `Stripe` `Vercel`

</td>
<td width="50%" valign="top">

### [Trade Journal Analyzer](https://github.com/BenMonte/Trade-Journal-Analyzer)
Java CLI that reads Excel trade journals and computes deterministic performance metrics.

- Excel ingestion via Apache POI with formula-cell and malformed-row handling
- 12 metrics computed in pure Java: win rate, expectancy, profit factor, max drawdown, and more
- Dual JSON + Markdown report output
- Optional LLM narrative summary via OpenAI (fully skippable)

`Java` `Maven` `Apache POI` `JUnit 5` `OpenAI API`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Drugs, Traits & Status: A Behavioral Link](https://github.com/BenMonte/Drugs-Traits-and-Status-A-Behavioral-Link)
Behavioral data analysis of drug use, personality traits, and socioeconomic status.

- Jupyter notebook pipeline for cleaning, EDA, OLS regression, and correlation matrices
- Python export script packages findings into structured JSON
- Java CLI report viewer with interactive section-by-section menu
- Key finding: personality traits predict substance use better than age or SES

`Python` `Jupyter` `Java` `Data Analysis` `Statistics`

</td>
<td width="50%" valign="top">
</td>
</tr>
</table>

---

## Architecture Tradeoffs

| Decision | Why this choice | Tradeoff |
|---|---|---|
| Next.js App Router + Stripe server sessions | Keeps payment logic server-side for security; App Router enables streaming and fine-grained caching | Tighter coupling to Vercel deployment model |
| Pure-Java analytics (no Pandas/NumPy) | Deterministic, dependency-light metrics with full test coverage and a single fat JAR artifact | More implementation effort than a Python one-liner, but zero runtime ambiguity |
| Jupyter → JSON → Java CLI reporting pipeline | Separates exploratory analysis from structured output; Java CLI is portable and dependency-free | Requires a well-defined JSON contract between the Python and Java layers |
| Tailwind CSS v4 + Turbopack | Fast dev iteration with zero-config utility classes and near-instant HMR | Utility-first CSS can be verbose in markup; Turbopack is still maturing |

---

## Engineering Snapshot

- Undergraduate at UC San Diego studying Mathematics-Computer Science.
- 150+ contributions in the past year across 16 repositories.
- Building and shipping across full-stack, data analysis, and tooling layers.
- Comfortable working end-to-end: from frontend storefronts to CLI analytics engines.

---

## Core Stack

**Languages:** Java, TypeScript, Python, SQL  
**Frontend:** Next.js, React, Tailwind CSS  
**Backend:** Next.js API Routes, Express  
**Data:** PostgreSQL  
**Infra:** Vercel, Docker, GitHub Actions

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,typescript,python,postgres,docker,nextjs,react,tailwind,vercel,linux,git&theme=light&perline=11" alt="Tech stack" />
</p>
