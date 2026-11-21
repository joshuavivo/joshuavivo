<p align="center">
<img src="banner.svg" alt="Joshua Vivo, software engineer, Shadow Vivo LLC. I take over live software and make it safe." width="100%">
</p>

<p align="center">
<img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-f6f4ef?style=for-the-badge&logo=typescript&logoColor=1f8a70">
<img alt="React" src="https://img.shields.io/badge/React-f6f4ef?style=for-the-badge&logo=react&logoColor=1f8a70">
<img alt="Node.js" src="https://img.shields.io/badge/Node.js-f6f4ef?style=for-the-badge&logo=nodedotjs&logoColor=1f8a70">
<img alt="Postgres" src="https://img.shields.io/badge/Postgres-f6f4ef?style=for-the-badge&logo=postgresql&logoColor=1f8a70">
<img alt="Python" src="https://img.shields.io/badge/Python-f6f4ef?style=for-the-badge&logo=python&logoColor=1f8a70">
<img alt="Cloudflare" src="https://img.shields.io/badge/Cloudflare-f6f4ef?style=for-the-badge&logo=cloudflare&logoColor=1f8a70">
</p>

I'm a software engineer in Connecticut and I run [Shadow Vivo LLC](https://shadowvivo.com). People bring me a web app that already has real users and real money moving through it, and I keep it running while I make the risky parts safe.

## What I do

**Takeovers**<br>
Inherit a production app with real users and payments. Keep it up, then own it end to end: frontend, backend, data and deploys.

**Hardening**<br>
Fix what hurts most when it breaks: payment ledgers, credential rotation, access control and personal data.

**Agent tooling**<br>
Build agents that keep a human in the loop. Reading and drafting are free. Anything that writes waits for a yes.

## How I work

<table>
<tr><td><code>money</code></td><td>Append-only. A correction is a reversal row, never an edit.</td></tr>
<tr><td><code>shipping</code></td><td>Nothing is "live" until the running site proves it.</td></tr>
<tr><td><code>bugs</code></td><td>Reproduce it, find the cause, change one thing.</td></tr>
<tr><td><code>agents</code></td><td>Reads and drafts are free. Writes wait for a human yes.</td></tr>
<tr><td><code>secrets</code></td><td>Rotate all of them, then confirm every old one is dead.</td></tr>
</table>

## Featured

**[exactly-once-webhooks](https://github.com/joshuavivo/exactly-once-webhooks)** — process a payment webhook once, even when the provider delivers it twice or two copies race. A library anyone can install. Postgres, Redis and in-memory stores all held to one shared contract test, no runtime dependencies, the double-credit race proven by a test.

**Start here:** its [payment-path example](https://github.com/joshuavivo/exactly-once-webhooks/tree/main/examples/payment-path) is the whole path in one place: signature check → exactly once → an append-only ledger row in the same Postgres transaction → dead letter, with a test for each step. `node examples/payment-path/demo.ts` runs it.

## More samples

<table>
<tr><td><a href="https://github.com/joshuavivo/ai-built-app-teardown">ai-built-app-teardown</a></td><td>A fictional AI-built app, audited: nine vulnerabilities, each with an exploit test that proves it and a fix that closes it.</td></tr>
<tr><td><a href="https://github.com/joshuavivo/agent-permission-gate">agent-permission-gate</a></td><td>A gate between an AI agent and its tools: reads run, writes wait for a person, and injected text can't approve anything.</td></tr>
<tr><td><a href="https://github.com/joshuavivo/append-only-ledger">append-only-ledger</a></td><td>A payments ledger where rows are never edited: database triggers block updates and deletes, corrections are reversal rows, and a hash chain catches tampering.</td></tr>
<tr><td><a href="https://github.com/joshuavivo/webhook-crm-alert">webhook-crm-alert</a></td><td>Payment webhook → CRM → chat alert, built for the failure cases: bad signatures, duplicates, retries and a dead-letter record.</td></tr>
</table>

Each is small, tested, CI-green, and documents its own limits (in a `DESIGN.md` or a Limits section).

## About this profile

My client work is private and stays that way. The repos pinned below are small samples of how I build — architected and directed by me, built fast with AI tooling (Claude). The design calls and the judgment are mine.

Proof you can check: the live site I run, [shadowvivo.com](https://shadowvivo.com), and a working demo of the support portal I built, [shadowvivo.com/support-demo](https://shadowvivo.com/support-demo/).

<p align="center">
<a href="https://shadowvivo.com"><img alt="shadowvivo.com" src="https://img.shields.io/badge/shadowvivo.com-1f8a70?style=for-the-badge"></a>
<a href="https://www.linkedin.com/in/joshuavivo/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-f6f4ef?style=for-the-badge"></a>
<a href="https://x.com/JvivoEng"><img alt="X" src="https://img.shields.io/badge/X-f6f4ef?style=for-the-badge"></a>
<a href="mailto:josh@shadowvivo.com"><img alt="Email" src="https://img.shields.io/badge/josh@shadowvivo.com-f6f4ef?style=for-the-badge"></a>
</p>
