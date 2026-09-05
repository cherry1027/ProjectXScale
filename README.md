# ProjectXScale 2040

ProjectXScale 2040 is an interactive React and TypeScript prototype developed for a Master’s thesis exploring how project-management practices can support a major increase in nuclear-site project volume between 2030 and 2040.

> **Important:** This prototype uses synthetic demonstration data only. 

## Live demo

[Open ProjectXScale 2040](https://projectscale-2040.charanvaranasi44.workers.dev)

## Features

The prototype includes six interactive views:

1. **Current-State Dashboard**
   - Cost variance
   - Schedule adherence
   - Resource utilization
   - Safety and quality issues
   - Lessons-learned reuse
   - Supplier dependency
   - Portfolio risk

2. **Project Comparison**
   - Side-by-side project performance
   - Schedule, cost, resource, supplier, and risk indicators

3. **Project Maturity Assessment**
   - Governance and decision-making
   - Portfolio prioritization
   - Planning standardization
   - Resource management
   - Risk integration
   - Knowledge reuse
   - Supplier integration

4. **Resource & Dependency Map**
   - Shared specialist resources
   - Supplier dependencies
   - Capacity bottlenecks
   - Cross-project risk concentration

5. **Future Volume Simulator**
   - Interactive project-volume control
   - Capacity-load calculations
   - Expected delay estimates
   - Portfolio risk projections
   - Governance staffing requirements

6. **Recommended Operating Model**
   - Current operating model
   - Standardized stage-gate model
   - PMO-led model
   - Program-based model
   - Suggested 2030–2040 implementation roadmap

## Technology

- React
- TypeScript
- Vinext/Vite
- Tailwind CSS
- Lucide icons
- Cloudflare Workers

The application is frontend-only and does not require a backend, database, authentication system, or external API.

## Run locally

Requirements:

- Node.js 22.13 or newer
- npm

Clone the repository:

```bash
git clone https://github.com/cherry1027/ProjectXScale.git
cd ProjectXScale
