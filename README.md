# SubsSwitch

**Find every subscription you pay for, see what you'll be charged and when, and cancel, refund or switch in a few taps.**

SubsSwitch is a fintech app for iPhone and Android. It scans your mailboxes, bank accounts and statements, finds recurring charges and turns them into one clear list with costs and upcoming payment dates. It is live in **17 EU countries**.

🌐 [subsswitch.app](https://www.subsswitch.app)

> This is a public showcase of the product. The source code lives in a private repository.

---

## The problem

People pay for more subscriptions than they remember: streaming, apps, cloud storage, gyms, free trials that quietly converted. The evidence is scattered across email receipts and bank statements, so money leaks every month and cancelling is a chore.

## What SubsSwitch does

- **Connects your sources**: Gmail, Outlook and iCloud mailboxes, bank accounts through [Plaid](https://plaid.com), or uploaded statement files
- **Scans and detects subscriptions** across all of them, including bank statements in PDF and CSV
- **Shows what's coming**: every subscription, its price, and when the next charge lands, with reminders and push notifications
- **Helps you act**: cancel, request a refund, or switch to a better deal
- **Suggests savings** and answers questions through **Dot**, a built-in chat assistant

## Status

| | |
|---|---|
| Stage | Live, iOS and Android |
| Markets | 17 EU countries |
| Started | September 2026 |
| Security | CASA security assessment for Gmail access |

## How it's built

| Layer | Tech |
|---|---|
| Mobile app | Expo (SDK 54), React Native, Expo Router |
| Language | TypeScript |
| Sign-in | Email, Google, Apple |
| Data sources | Gmail, Outlook, iCloud, Plaid (EU banks), statement uploads |
| Statement parsing | Python service; PDFs read with Claude vision, CSVs parsed as tables |
| Builds & releases | EAS, GitHub Actions, TestFlight |
| Quality | Jest unit tests, Maestro end-to-end QA flows |
| Way of building | Lean team: founder + developer, AI-assisted development with Claude |

## My role

I'm the founder and product owner. I took SubsSwitch from idea to a live app in 17 EU countries: defined the problem and scope, hired and lead a developer, set up an AI-assisted workflow (Claude) that lets a very small team ship fast, and own priorities, QA, security review, EU compliance questions, releases and iteration from user feedback.

## About me

I'm **Helen Kostenko**, an operations leader with ~7 years in business operations, including ~3 years as COO in venture capital. I build systems that save teams time, and SubsSwitch is where I apply that mindset to my own product, with a lean team and AI in the loop.
