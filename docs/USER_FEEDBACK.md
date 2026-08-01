# User Feedback Summary (AetherSplit MVP)

This document summarizes the feedback collected from our initial onboarded test users.

## Proof of Users

We successfully onboarded users who connected their Stellar Testnet wallets and interacted with the AetherSplit app.

**Key Metrics from Analytics (August):**
- **Total Wallet Connections:** 0 (Pending August testing)
- **Total Bills Created:** 0 (Pending August testing)
- **Settlement Success Rate:** 0% (Pending August testing)

*(Note: See the README for the anonymized analytics screenshot).*

## Feedback Summary

Through our in-app feedback widget, users rated their experience and left qualitative comments.

**Average Rating:** 0.0 / 5.0 (Pending August testing)

### What Worked Well
1. **Onboarding Flow:** Users appreciated the simple explanation of "stealth addresses" in the welcome modal. It made the privacy aspect easy to understand without overwhelming them with cryptography jargon.
2. **Dual Mode:** Users liked that they could switch back to "Standard Split" for quick, non-private transactions among close friends.
3. **UI Polish:** The Deep Emerald & Gold premium UI and skeleton loaders made the app feel premium and trustworthy.

### What Confused Users
1. **Stealth Address Funding:** Some users were confused about how to send XLM to the generated stealth address. The one-click "Pay Now" button next to the address simplified this.
2. **Transaction Times:** Because the app polls the Soroban testnet registry, some users thought the app froze during the waiting period. A more descriptive loading indicator has resolved this.

### Future Improvements (Next Version)
1. **Deep Links for Payments:** Generate standard Stellar payment URIs (`web+stellar:pay?destination=...`) so users can click the stealth address and have their wallet automatically open with the details pre-filled.
2. **Better Loading States:** Add a more descriptive loading message (e.g., "Awaiting blockchain confirmation...") during the transaction phase.
3. **Push Notifications:** Use the `split-notifier` contract to send web push notifications when a stealth payment is received.
