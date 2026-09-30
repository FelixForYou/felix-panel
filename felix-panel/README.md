# FELIX PANEL

Neomorphic responsive frontend foundation for an Auto Order Pterodactyl marketplace. The UI follows the supplied specification and keeps payment/Pterodactyl secrets server-side.

## Run
npm install
npm run dev

## Production integration
Connect the UI to a relational database, authentication/session layer, AustinPay backend service, Pterodactyl service, queue/worker, idempotent payment state machine, and admin APIs. Use `.env.example` for server-side configuration; never ship secrets to the client.

The current starter intentionally does not fake real payments or server provisioning.
