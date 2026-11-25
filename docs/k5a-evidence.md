# K5A Zone — public evidence and verification

[Français](k5a-evidence.fr.md) · English

**Sources reviewed: 25 November 2026 (Europe/Zurich).** This page shows what a visitor can check independently and how to test the activity-credit flow. It does not claim an independent audit of private account balances.

## Public sources anyone can inspect

| Source | What a reviewer can verify | Boundary |
| --- | --- | --- |
| [KOM-5A website](https://kom-5a.com/) and [About K5A](https://kom-5a.com/about) | The live public entry point and the project's published description of K5A as an internal participation and service unit | First-party product statements do not audit the reward ledger |
| [K5A Service Terms](https://kom-5a.com/service-terms?lang=en) | Published conditions for K5A services, including Publication Boost, quotes, eligibility and limits on promised results | Terms do not prove that a specific account received a reward or service |
| [Dated web walkthrough](demo.md) and [official App Store listing](https://apps.apple.com/ch/app/kom-5a/id6756894425) | Public product and app entry points | They do not demonstrate the private K5A reward ledger |
| [Polygon Amoy test contract](https://amoy.polygonscan.com/address/0x382c77b6646e7aef5650f0465b7b8e71697dcb79#code) and [verified source](https://sourcify.dev/server/v2/contract/80002/0x382c77b6646e7aef5650f0465b7b8e71697dcb79?fields=sources,creationMatch,runtimeMatch) | A deployed ERC-20 prototype with inspectable code on a test network | It is not a mainnet launch, security audit or proof of synchronization with app balances |

## Private-test evidence and its limit

The project supplied screenshots of the private K5A Zone for review. They are **not published** here because they contain private account details. A screenshot alone cannot independently establish the accuracy of a server ledger or show that an app reward reached a blockchain wallet.

A stronger public demonstration requires an eligible **demo account with no personal data**, a dated before-and-after recording, an exported activity CSV and a reconciliation of event IDs, amounts and balances. A reviewer should be able to repeat the same steps.

## Reproducible verification protocol

1. Record a demo account's starting K5A balance, time and most recent activity entry.
2. Perform one eligible action or start an available reward session. Record the action ID and time.
3. Compare the new balance, activity entry and session progress.
4. Export the account CSV. Reconcile entries with the displayed balance and check that the same action was not credited twice.
5. For a deeper review, compare the exported events with a controlled server-ledger extract. Publish only de-identified evidence and the reconciliation method.

**Blockchain status:** app-to-Amoy synchronization is **not active as of 25 November 2026**. No on-chain transaction is expected for an activity reward today. When a pilot becomes active, its transaction hash and reconciliation rules can be added to this page.

[Explore the K5A Zone guide](k5a.md) · [Join KOM-5A](https://kom-5a.com/register) · [Contact the project for a focused review](https://kom-5a.com/contact)
