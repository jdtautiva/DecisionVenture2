# DecisionVenture2
> **Interactive financial viability simulator for evaluating innovation projects through guided calculations, financial indicators, and managerial decision-making.**
> Developed for the **Viabilidad de la Innovación** course by **Julián Díaz Tautiva, PhD**

---
## Overview
**DecisionVenture2** is a browser-based pedagogical simulation tool designed for undergraduate and graduate courses on innovation viability, entrepreneurship, project evaluation, and applied finance. Students work in teams and take the role of decision-makers evaluating whether an innovation project should be accepted, rejected, or conditionally advanced.

The simulator guides students through a sequential financial case. Teams select one of six innovation contexts, review the business narrative and financial assumptions, calculate key financing and cash-flow components, and then interpret the project’s financial viability using NPV, IRR, WACC, payback, sensitivity logic, risk analysis, and managerial reasoning.

The simulator emphasizes the practical use of financial indicators in uncertain innovation contexts. Rather than asking students to mechanically calculate every indicator, the tool combines guided numerical exercises with interpretive questions that require students to connect financial results with market adoption, cost structure, financing, scalability, operational risk, and managerial action.

The simulator runs entirely as a single self-contained HTML file — no backend, no installation, and no external dependencies are required beyond a modern web browser. It can be opened locally, shared through a learning management system, hosted on a web server, or published using static hosting services such as GitHub Pages.
---
## Learning Objectives
By completing the simulation, students are able to:
- Estimate the after-tax cost of debt by applying the tax shield effect
- Calculate and interpret the Weighted Average Cost of Capital (WACC)
- Construct free cash flow components for innovation projects
- Distinguish between initial investment, operating cash flows, additional investments, working capital recovery, and terminal value
- Interpret Net Present Value (NPV/VAN) as a measure of value creation or value destruction
- Interpret Internal Rate of Return (IRR/TIR) in relation to WACC and project risk
- Interpret payback period as an indicator of liquidity, recovery speed, and exposure to uncertainty
- Evaluate the role of terminal value in the financial attractiveness of an innovation project
- Identify critical assumptions that may affect project viability
- Analyze financial risk through market, operational, technological, regulatory, and financing mechanisms
- Justify innovation investment decisions using financial indicators and business context
- Recommend managerial actions such as piloting, scaling, delaying, redesigning, or abandoning an innovation project

---
## Key Features

**Six differentiated innovation cases** — teams select among six innovation contexts, allowing instructors to assign different cases across groups while preserving a common decision framework.

**Team registration** — students enter team member names before beginning the simulation. Additional team members can be added dynamically using the “Agregar integrante” button. The names are included in the final report.

**Sequential case logic** — the simulator presents one question at a time. Students must validate each response before moving forward, creating a step-by-step case experience.

**Guided calculation procedure** — each calculation question includes a procedural guide explaining how students should approach the task. The guide includes the relevant formula, intermediate logic, and common points of attention.

**Formative feedback without revealing final answers** — when students enter an incorrect numerical value, the simulator indicates that the answer is wrong and explains what should be reviewed, without revealing the final correct value. This preserves the learning process while still providing feedback.

**Business-oriented analytical guidance** — each question includes a section explaining what elements should be considered from a managerial perspective, such as market adoption, scalability, liquidity, financing structure, value terminal dependence, and execution risk.

**Financial calculations embedded in the simulator** — the tool internally calculates after-tax cost of debt, WACC, free cash flows, NPV/VAN, IRR/TIR, payback, and project viability benchmarks.

**NPV, IRR, and payback used for interpretation** — the simulator provides VAN, TIR, WACC, and payback values to students in later stages so that they can focus on interpretation, justification, and decision-making rather than mechanical recalculation.

**Managerial justification questions** — students must justify the project decision using financial indicators and business logic. The simulator rewards responses that connect VAN, TIR, WACC, payback, risk, adoption, scalability, financing, and operational capacity.

**Sensitivity and risk analysis** — students identify critical assumptions and explain how changes in adoption, revenue, costs, WACC, terminal value, or investment could affect the project’s viability.

**Managerial action recommendation** — the final stage asks students to propose an implementation action such as a pilot, phased investment, minimum contract threshold, validation milestone, financing condition, or abandonment criterion.

**Final performance report** — at the end of the simulation, teams receive a complete report showing the selected case, participants, each question, the answer submitted, evaluation status, points earned, total score, and final feedback.

**PDF export** — the final report can be exported to PDF using the browser’s native print functionality. Print-specific CSS is included to produce a clean report format.

---
## Technical Details

| Attribute              | Detail                                            |
| ---------------------- | ------------------------------------------------- |
| Format                 | Single `.html` file, fully self-contained         |
| Dependencies           | None                                              |
| Backend required       | None                                              |
| External libraries     | None                                              |
| Main technologies      | HTML, CSS, JavaScript                             |
| Financial calculations | JavaScript functions embedded in the file         |
| PDF export             | Browser-native print/export to PDF                |
| Print styling          | Internal `@media print` CSS                       |
| Storage                | Runtime state handled in JavaScript               |
| Browser support        | Any modern browser: Chrome, Firefox, Safari, Edge |
| Screen                 | Desktop optimized; responsive down to tablet      |
| Language               | Spanish                                           |
| Estimated duration     | 30–45 minutes                                     |
| Course context         | Viabilidad de la Innovación                       |
| Instructor attribution | Julián Díaz Tautiva, PhD                          |

---
## Suggested Citation

Díaz Tautiva, J.A. (2026). *DecisionVenture2 — Innovation Project Financial Viability Simulator*. Viabilidad de la Innovación teaching simulator.
