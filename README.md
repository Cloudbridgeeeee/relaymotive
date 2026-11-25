# RelayMotive

**Intelligent insights for vehicle maintenance.** Maintenance forecasting for workshops and fleets.

- Founder and CEO: Chibuike Okafor
- Co-founder and CTO: Ridwan Adekunle

## Structure

- `index.html`: the marketing page, built on the TasteSkill kit (`public/assets`) with a dealt hero, palette, type and moments. Design rules: `design.md`, `layout.md`, `product.md`.
- `demo/` and `src/demo`: the React demo workspace (overview, records with search and filters, a review queue with approve and decline, an audit log kept in localStorage).
- `privacy.html`, `terms.html`, `docs/architecture.md`, `vercel.json`.

```bash
npm install
npm run dev
npm run build
npm test
```

The demo runs on fixed data in the browser; no AI service is called.
