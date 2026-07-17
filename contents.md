# SimpleTimesheeet Series: Content Table

51 posts across 6 arcs. Written-up entries link to their full log.

---

## Arc 0: Why & The Stack (posts 1-5)
1. [Why I built SimpleTimesheet and what advantages it brings over other apps](logs/01-why-i-built-simpletimesheeet.md)
2. [The full tech stack on one slide (and why)](logs/02-the-full-tech-stack-on-one-slide.md)
3. [Four repos, One product, Simple but effective Architecture](logs/03-four-repos-one-product.md)
4. [Why I run it all on Hetzner instead of the big clouds](logs/04-why-hetzner-instead-of-big-clouds.md)
5. [Why I picked Go for the backend](logs/05-why-i-picked-go-for-the-backend.md)

## Arc 1: The Backend (posts 6-18)
6. Structuring a Go backend with domain-driven packages
7. Choosing Fiber v3 as the web framework
8. Postgres + JSONB: a whole month of timesheets in one column
9. My SQL migration strategy (and the duplication trap)
10. One auth layer, two identity providers
11. Verifying JWTs in middleware
12. Pulling public holidays from an open API and caching them
13. Adding holiday-name tooltips end to end
14. Subscriptions with Stripe and Svix webhooks
15. Sending transactional email with AWS SES
16. Self-hosted file storage with MinIO (S3 without AWS)
17. Keeping bots out: captcha and abuse protection
18. Testing against a real Postgres with Testcontainers

## Arc 1.5: Local Dev Environment (posts 19-20)
19. Why every developer gets prod-on-their-laptop with Docker Compose
20. Inside my local Docker Compose stack: Postgres, MinIO, mail, and friends

## Arc 2: The App Frontend / Next.js (posts 21-30)
21. Next.js App Router behind a gateway (the /app basePath)
22. Bilingual from day one with next-intl
23. ApiAuthBridge: giving non-React services an auth token
24. Designing the timesheet grid (day, week, month, compact)
25. Auto-generating a month of timesheets from one pattern
26. The time-validation rules nobody asks for but everyone needs
27. Exporting timesheets to PDF and styled Excel
28. Multi-currency checkout UX with Stripe
29. Dark mode with zero flash on load
30. Shipping Next.js as a standalone Docker build

## Arc 3: The Marketing Site / Vite (posts 31-36)
31. Why the landing page is a separate Vite app
32. Hand-rolled i18n: when a library is overkill
33. One build, many domains: hostname-based locale
34. Scroll reveals and the little polish that sells
35. Serving the site and the app from a single image
36. The CEO hat: making product, pricing, and positioning decisions as a solo engineer

## Arc 4: Infrastructure & Ops (posts 37-46)
37. Provision once, deploy often: my Ansible role boundaries
38. Describing Hetzner infrastructure with Terraform
39. Encrypting the data volume with LUKS (and the gotcha that bit me)
40. Idempotency war stories in Ansible
41. Rate limiting at the edge with OpenResty + Lua
42. Automating TLS and HSTS with certbot
43. Logs without a SaaS bill: Loki, Promtail, Grafana on one box
44. Off-site encrypted backups to object storage
45. One Docker image, three apps, one supervisor
46. Handling secrets with ansible-vault (no .env on disk)

## Arc 5: Compliance, Cost & Lessons (posts 47-51)
47. GDPR by design: pseudonymous consent and audit logs
48. Deleting data on schedule with a systemd timer
49. Analytics that respect consent: GA4 Consent Mode v2
50. What it really costs to run a SaaS like this
51. Lessons from building a compliant SaaS solo
