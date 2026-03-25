# 🎯 Sicario: Autonomous Red-Team Swarm

**The AI Security Co-Founder for Modern Web Development.**

AI coding assistants (**Cursor, v0, GitHub Copilot**) allow you to ship full-stack applications in hours. But while they write beautiful React components, they frequently hallucinate critical **Business Logic Vulnerabilities**—like allowing users to bypass paywalls, mutate cart prices, or escalate their own privileges.

Legacy vulnerability scanners (like Snyk or Burp Suite) are built for enterprise compliance, not rapid development. They read static code and output dense, 40-page PDFs.

**Sicario** is different. It is an autonomous, locally-running AI swarm that plays your application like a video game. It hunts the logic flaws your AI generated, and gives you the exact prompt to fix them.

---

## 🚀 Zero-Friction Quickstart

No configuration files. No heavy desktop apps. No credit card required.

```bash
# Launch a continuous background siege on your local dev server
npx sicario-red-team@latest watch http://localhost:3000
```

---

## 🔪 The Vanguard Features

### 1. Intent-Based Sieges
Stop writing complex testing configurations. Just tell Sicario what you want it to steal in plain English, and the Swarm figures out how to execute the attack.

```bash
npx sicario-red-team hit --target http://localhost:3000 --intent "Try to manipulate the checkout payload to get the Pro Plan for free."
```

### 2. The Scribe (Prompt-to-Patch)
When Sicario confirms an exploit, it doesn't just give you a stack trace. The **Scribe Node** automatically generates a natural-language "Cursor-ready" prompt. Just copy and paste the Scribe's output back into your AI IDE, and it will write the patch for you.

### 3. Continuous Localhost Protection (The Lazy Watcher)
Run `sicario watch` in the background. Sicario uses a zero-cost local DOM-diffing engine to monitor your app. The moment you hit "Save" on a new form or feature, the Swarm wakes up, micro-sieges the new code for logic flaws, and goes back to sleep.

### 4. DOM Supremacy
Modern web apps aren't static HTML pages. Sicario utilizes a headless Chromium engine to intercept asynchronous fetch requests, wait for React hydration, and pierce Web Component Shadow DOMs. It attacks your app exactly how a real human would.

---

## 🛡️ Swarm Architecture & Safety

Sicario runs locally on your machine. By default, it operates in **SHADOW TIER** (Dry-Run mode), meaning it maps your application and simulates attacks without mutating your database.

To authorize active database mutations and live POST/PUT exploits on your local environment, pass the `--live-fire` flag.

---

## 💎 Sicario Operator Tier

The free NPM package is powered by a rate-limited, free-tier Critic Cascade.

For professional engineering teams that require:

*   **Unlimited Tokens** & Zero Rate Limits
*   **Enterprise Auth Vaulting** (Bypass Okta/Auth0)
*   **Unredacted Swarm Reasoning Logs**
*   **CI/CD Pipeline Integration**

Upgrade your license at [sicario-red-team.com](https://sicario-red-team.com).
