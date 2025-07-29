
Project Plan — Food Ordering Platform

## 10-Day Timeline & Milestones

| Day | Goal                        | Output / Notes                        |
|-----|-----------------------------|----------------------------------------|
| 0   | Kick-off                    | PLAN.md, repo setup                    |
| 1-2 | Frontend Scaffold           | React + Tailwind base, routing         |
| 3-4 | Menu + Cart                 | Fetch mock menu, local cart logic      |
| 4-6 | Checkout + Tracker UI      | Forms + stub WS                        |
| 4-6 | Backend Scaffold            | Express + DB + JSON-RPC skeleton       |
| 5-6 | Core RPC APIs               | placeOrder, listOrders, etc            |
| 6-7 | WebSocket Events            | order_created, order_updated           |
| 7    | Analytics Widget + WS      | Historical + Live chart                |
| 8    | Docker + CI (optional)     | docker-compose, GitHub Actions         |
| 9    | Deployment                 | Live links: frontend, backend          |
| 10   | Docs + Polish              | README, ARCHITECTURE.md, GIF demo      |

## Risks & Mitigation

| Risk | Impact | Mitigation |
|------|--------|------------|
| WebSocket complexity | Medium | Reuse tested reconnection logic, test early |
| JSON-RPC learning curve | Low | Stick to JSON-RPC 2.0 spec with examples |
| Deployment bugs | High | Deploy early on Day 7–8 to find issues |
| Timeline overrun | Medium | Focus on MVP first, polish later |

---

GitHub Repo: [your-github-link-here](https://github.com/YOUR_USERNAME/food-platform)
