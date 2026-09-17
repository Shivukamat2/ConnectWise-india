# ConnectWise India

A React/Vite/Tailwind-style consumer telecom platform built from the original Indian Telecom Network & Router Diagnostic Console.

## Product flow
Location → availability → providers/plans/routers → People’s Choice + ConnectWise Choice → compare → diagnose → decide.

## Key product decisions
- Broadband & Router Availability Map is a primary feature.
- Mobile/SIM network exploration is a separate map/data experience.
- People’s Choice is an anonymous/local Wi-Fi-environment signal where device/OS permissions permit; it does not identify neighbours.
- ConnectWise Choice is a concrete platform/data-driven option, not an “AI winner.”
- AI is persistent assistance for explanations, confusion, diagnostics and learning; it is not positioned as the main recommendation engine.
- Demo data is explicitly simulated/estimated unless later replaced by verified provider or measured data.
- Checkout is a demo only and does not process or store real payment card data.

## Run
npm install
npm run dev

## Build
npm run build

## Structure
src/components reusable UI and shell
src/pages route-level screens
src/data simulated provider/router/mobile data
src/services diagnostic engine
src/context centralized app state
legacy original diagnostic console preserved for reference

## Production integration still required
- Authoritative provider address-level feasibility APIs or approved integrations
- Real measurement service/backend
- Secure database/authentication
- Android/native Wi-Fi and cellular telemetry where permitted
- Privacy/consent system for crowdsourced measurements
- Production payment provider only if explicitly needed
