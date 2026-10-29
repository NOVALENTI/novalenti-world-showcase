# NOVALENTI WORLD — Interactive Music Environment

**Private application · Public engineering case study**  
**Project creator:** Valentino Herrera (NOVALENTI)

NOVALENTI WORLD is a prototype of an interactive music environment: a navigable 3D city acts as a hub for audiovisual spaces, community sessions, and a broadcaster-facing control surface. This repository describes the project without exposing its private application source, business logic, infrastructure, or credentials.

> **Development status (October 2026):** prototype, **not** a public game, subscription service, production deployment, or finished commercial product.

## Implemented in the private development branch

- **3D city hub:** a Three.js city renderer, camera, scene lighting, and navigation between destination areas.
- **Club rehearsal route:** a standalone soundcheck environment with local audio import/playback and audio-reactive visual effects. Audio is not uploaded by the prototype.
- **Community interface:** guest sessions, room selection, and basic voting with server-side state for local development.
- **Broadcaster controls:** stage preview and owner-controlled room/poll interfaces designed for streaming workflows.
- **Experimental modules:** independently testable offline garden timing rules, remix-permission checks, and an avatar-animation research route.

### Not yet delivered

- Verified secure public launch, production database and monitoring, fully built worlds for all rooms, Twitch identity verification, large-scale multiplayer, payments, NFTs, monetization, or finished avatars.
- Rehearsal interfaces and offline tests are **not** evidence of a production-ready release.

## Technical areas demonstrated

TypeScript · React · Vite · Three.js · Node.js · server session design · testing · streaming interface planning · real-time UI prototypes

## Case study

See **[System design and project boundaries](docs/CASE_STUDY.md)** for the development approach, separation of user/public surfaces, known risks, and the responsible release plan.

## Code and commercial licensing

The complete NOVALENTI WORLD source remains in a **private repository**. This repository provides non-confidential descriptions and a separately authored, static presentation page, not the proprietary app.

Copyright © 2026 Valentino Herrera. All rights reserved. No commercial use, redistribution of original materials, or derivative commercial implementations are authorized by this showcase without a separate written agreement. GitHub's platform terms and applicable law still apply. For licensing or commissioning discussions: **valentinoherreraofficial@gmail.com**.

This notice is not a payment contract and does not make anyone owe a fee for merely viewing the repository.
