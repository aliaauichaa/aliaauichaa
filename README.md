# Hi, I'm Ali Aauicha 👋

**Cloud & AI Developer** · Barcelona, Spain

I build and run my own products on AWS: three apps in production with real users, Stripe payments and a generative-AI assistant (Claude) in each one. I came to software from operations and supply chain, so I care about what the data says and what the cloud bill says.

## Products in production

| Product | What it is | Stack | Code |
|---|---|---|---|
| **[Quillaflow](https://www.quillaflow.com)** | Workforce management for small businesses: roles, real-time collaboration, client portal, email/SMS alerts, Android/iOS app. In daily use by a real client. | Cognito · Lambda · API Gateway · S3 · CloudFront · SES/SNS · Capacitor | [quillaflow](https://github.com/aliaauichaa/quillaflow) · [mobile](https://github.com/aliaauichaa/quillaflow-mobile-capacitor) |
| **[Mi Campo con IA](https://www.micampoconia.com)** | Farm management: plots, costs, workdays, irrigation, stock, official market prices, satellite NDVI. Ready for IoT soil sensors. 1,500+ followers on [Instagram](https://www.instagram.com/micampoconia/). | Supabase / PostgreSQL (RLS) on Lightsail · 18 Lambdas (WebSockets, ETL, Cognito triggers) | [mi-campo-con-ia](https://github.com/aliaauichaa/mi-campo-con-ia) |
| **[ShootingStats](https://shootingstats.site)** | Football statistics for dozens of leagues: PWA in ES/EN/IT with 800+ generated SEO pages, Stripe subscriptions, data pipeline on Lambda + EventBridge. | Lambda · EventBridge · DynamoDB · Stripe · S3 · CloudFront · SES | [shootingstats](https://github.com/aliaauichaa/shootingstats) |

## How I work

- **Serverless first.** Lambda + API Gateway + S3/CloudFront, one region per workload, secrets only in environment variables or Secrets Manager.
- **Ship, then measure.** Scripted deployments with cache-busting and CloudFront invalidation, CloudWatch alarms, and an eye on cost (the 1,000 free invalidations are shared by the whole account, I learned that the expensive way).
- **Measure what ships.** Google Analytics 4 on all three products and Search Console on Mi Campo, with page titles rewritten from CTR and position data. On ShootingStats, a Lambda backend queries the GA4 Data API to show per-user usage time in the admin panel and tags Telegram links with UTM; active users up 272% in 30 days.
- **AI as a coworker.** Every product has a Claude-powered assistant behind a Lambda proxy, and I use Claude Code daily as a development assistant.
- **Real data or nothing.** If a value can't be verified it stays empty. No invented stats, no placeholder logos.

## Stack

`AWS` (Lambda, API Gateway, S3, CloudFront, Cognito, DynamoDB, SES, SNS, EventBridge, CloudWatch, Lightsail) · `JavaScript / Node.js` · `Supabase` · `PostgreSQL` · `Stripe` · `PWA` · `Capacitor` · `Claude API` · `GA4 Data API` · `Search Console` · `Power BI` · `SAP`

## Background

Master's in Economic and Business Analysis (University of Málaga) · AWS re/Start graduate · Master's in SAP BTP, S/4HANA and AI · 5 years in operations and supply chain analysis (Grupo Sesé, Paack, Fluiconnecto) across Spain and the UK.

## Resume

[Download CV (English)](cv/Ali-Aauicha-CV-EN.pdf) · [Descargar CV (español)](cv/Ali-Aauicha-CV-ES.pdf)

## Contact

[LinkedIn](https://www.linkedin.com/in/ali-aauicha/) · aliaauicha@gmail.com
