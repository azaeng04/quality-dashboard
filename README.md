# Code Quality Dashboard

A GitHub Pages dashboard showing code quality metrics across all repositories.

## View Dashboard

**Live URL:** https://azaeng04.github.io/quality-dashboard/

## Metrics Tracked

| Metric | Description |
|--------|-------------|
| Quality Grade | Overall code quality (A-F) |
| Security | Number of vulnerabilities |
| Maintainability | Ease of maintenance (A-F) |
| Tech Debt | Estimated time to fix code smells |
| Bugs | Potential bugs detected |
| Duplication | Percentage of duplicated code |
| Mutation Score | Test effectiveness (mutants killed %) |

## Repositories Monitored

- [commerce.express](https://github.com/azaeng04/commerce.express) - Java
- [api-online-ecommerce](https://github.com/azaeng04/api-online-ecommerce) - Java
- [budget](https://github.com/azaeng04/budget) - TypeScript
- [ip3shoppingcartazatra](https://github.com/azaeng04/ip3shoppingcartazatra) - PHP

## How It Works

1. Each repository runs quality analysis via GitHub Actions
2. Results are aggregated in `data.json`
3. Dashboard reads from `data.json` and displays metrics
4. GitHub Pages serves the static dashboard

## Tech Stack

- Pure HTML/CSS/JS (no frameworks)
- GitHub Pages hosting
- GitHub Actions for automation
