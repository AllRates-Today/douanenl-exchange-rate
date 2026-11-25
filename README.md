# Netherlands Customs (Douane) Exchange Rates API — douanenl-exchange-rate

[![npm version](https://img.shields.io/npm/v/douanenl-exchange-rate.svg)](https://www.npmjs.com/package/douanenl-exchange-rate)
[![license](https://img.shields.io/npm/l/douanenl-exchange-rate.svg)](https://github.com/AllRates-Today/douanenl-exchange-rate/blob/main/LICENSE)
[![zero dependencies](https://img.shields.io/badge/dependencies-0-brightgreen.svg)](https://www.npmjs.com/package/douanenl-exchange-rate)
[![TypeScript](https://img.shields.io/badge/TypeScript-types%20included-3178C6.svg)](https://www.typescriptlang.org/)
[![EUR/USD today](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fallratestoday.com%2Fapi%2Fopen%2Fcentral-bank%2Fdouanenl%3Fsource%3DEUR%26target%3DUSD&query=%24.rate&label=EUR%2FUSD%20official%2C%20Netherlands%20Customs%20(Douane)&color=0A7E8C&cacheSeconds=3600)](https://allratestoday.com/tax-authority-rates-api/douanenl/)
[![rate date](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fallratestoday.com%2Fapi%2Fopen%2Fcentral-bank%2Fdouanenl%3Fsource%3DEUR%26target%3DUSD&query=%24.rate_date&label=rate%20date&color=555&cacheSeconds=3600)](https://allratestoday.com/tax-authority-rates-api/douanenl/)

**Official Netherlands Customs (Douane) (the Netherlands) monthly exchange rates for Node.js and TypeScript. The published tax authority rates behind tax filings, customs valuations, audits, and compliant invoicing — not market estimates, but the numbers Netherlands Customs (Douane) itself prints, every month.**

## 🚀 Why this client?

- 🏛️ **Official rates** — Netherlands Customs (Douane)'s own table, with the publisher's own `rate_date` on every response
- 📅 **History back to 2021** — point-in-time tables and daily series for any past date
- 🔀 **Official vs derived, always flagged** — computed inverse/cross pairs carry `derived: true`, never mixed with official prints
- ⚡ **Zero dependencies** — pure ESM + CJS over global `fetch`; Node 18+, Bun, Deno, and edge runtimes
- 🔷 **Type-safe** — full TypeScript definitions shipped with the package
- 🧾 **Compliance-grade metadata** — `rate_type`, publication date, and source disclaimer on every response

> **Official rate, not mid-market:** every value here is a number Netherlands Customs (Douane) itself published, fixed once printed and carrying the tax authority's own `rate_date` — what filings and audits require. Need the live mid-market rate for pricing or display instead? Use the [mid-market API](https://allratestoday.com/docs/) or [`@allratestoday/sdk`](https://www.npmjs.com/package/@allratestoday/sdk). The two can diverge by several percent.

## 🔑 Get your API key

Get a free API key at [allratestoday.com/register](https://allratestoday.com/register) — no credit card required. Latest rates are on every plan, including free.

## 📈 Latest official table

[![Latest Netherlands Customs (Douane) table](https://allratestoday.com/api/open/central-bank/douanenl/table.svg)](https://allratestoday.com/tax-authority-rates-api/douanenl/)

The image is rendered live from the keyless endpoint, so it follows the tax authority's publications on npm and on GitHub alike without a new release. The same table as text is folded below for search and copy-paste: on GitHub [a daily Action](.github/workflows/daily-table.yml) refreshes it whenever the tax authority publishes a new table; on npm it is as of the package's publish date.

<!-- daily-table:start -->
<details>
<summary>Table as text: published 2026-11-01 by Netherlands Customs (Douane) — 73 rates, first 60 shown. Updated 2026-11-25.</summary>

| Base | Quote | Type | Rate |
| --- | --- | --- | ---: |
| EUR | AED | monthly | 4.1187 |
| EUR | AOA | monthly | 1032.731 |
| EUR | AUD | monthly | 1.5971 |
| EUR | AWG | monthly | 2.0075 |
| EUR | BDT | monthly | 138.6847 |
| EUR | BHD | monthly | 0.422 |
| EUR | BND | monthly | 1.4338 |
| EUR | BRL | monthly | 5.6432 |
| EUR | BWP | monthly | 15.5548 |
| EUR | BYN | monthly | 3.3472 |
| EUR | CAD | monthly | 1.5779 |
| EUR | CHF | monthly | 0.9256 |
| EUR | CLP | monthly | 1100.33 |
| EUR | CNY | monthly | 7.4999 |
| EUR | CRC | monthly | 507.6358 |
| EUR | CZK | monthly | 24.262 |
| EUR | DKK | monthly | 7.4746 |
| EUR | DOP | monthly | 68.8899 |
| EUR | DZD | monthly | 150.8662 |
| EUR | EGP | monthly | 60.6421 |
| EUR | FJD | monthly | 2.5322 |
| EUR | GBP | monthly | 0.83825 |
| EUR | GHS | monthly | 13.0787 |
| EUR | GTQ | monthly | 8.5706 |
| EUR | HKD | monthly | 8.8155 |
| EUR | HUF | monthly | 365 |
| EUR | IDR | monthly | 20269.17 |
| EUR | ILS | monthly | 3.4726 |
| EUR | INR | monthly | 106.1265 |
| EUR | IQD | monthly | 1700.194 |
| EUR | ISK | monthly | 136.2 |
| EUR | JMD | monthly | 177.6253 |
| EUR | JOD | monthly | 0.7951 |
| EUR | JPY | monthly | 177.36 |
| EUR | KES | monthly | 145.6504 |
| EUR | KRW | monthly | 1489.15 |
| EUR | KWD | monthly | 0.347 |
| EUR | KZT | monthly | 506.44 |
| EUR | LKR | monthly | 371.9263 |
| EUR | MAD | monthly | 10.982 |
| EUR | MUR | monthly | 52.9942 |
| EUR | MWK | monthly | 1943.0386 |
| EUR | MXN | monthly | 20.7632 |
| EUR | MYR | monthly | 4.5843 |
| EUR | NGN | monthly | 1495.767 |
| EUR | NOK | monthly | 10.512 |
| EUR | NZD | monthly | 1.9735 |
| EUR | OMR | monthly | 0.4312 |
| EUR | PHP | monthly | 71.121 |
| EUR | PKR | monthly | 310.6501 |
| EUR | PLN | monthly | 4.3635 |
| EUR | QAR | monthly | 4.0823 |
| EUR | RON | monthly | 5.3365 |
| EUR | RSD | monthly | 117.3893 |
| EUR | RUB | monthly | 92.2369 |
| EUR | SAR | monthly | 4.2056 |
| EUR | SEK | monthly | 11.0975 |
| EUR | SGD | monthly | 1.4348 |
| EUR | SRD | monthly | 42.246 |
| EUR | THB | monthly | 37.718 |

</details>

[Full table on the Netherlands Customs (Douane) rates page](https://allratestoday.com/tax-authority-rates-api/douanenl/) · Source: [Official rates published by DOUANENL, served by AllRatesToday](https://allratestoday.com/tax-authority-rates-api/douanenl/). Rates are as printed by the tax authority; AllRatesToday is not affiliated with it.
<!-- daily-table:end -->

## 📦 Installation

```bash
npm install douanenl-exchange-rate
```

```bash
yarn add douanenl-exchange-rate
```

```bash
pnpm add douanenl-exchange-rate
```

Requires Node 18+ (global `fetch`); also runs on Bun, Deno and edge runtimes. Also published under the org scope as [`@allratestoday/douanenl-exchange-rate`](https://www.npmjs.com/package/@allratestoday/douanenl-exchange-rate) — same code, same versions.

## 🏁 Quick start

```js
import { getRate } from 'douanenl-exchange-rate';

const pair = await getRate('USD', 'EUR', { apiKey: 'art_live_...' });
console.log(pair.rate, pair.rate_date); // the official Netherlands Customs (Douane) rate, on the tax authority's own date
```

## 📚 API reference

- [Latest pair rate](#latest-pair-rate) — one pair from the latest official table
- [Full official table](#full-official-table) — everything the tax authority printed, in one call
- [Table for a date](#table-for-a-date) — the official table for an invoice or filing date
- [Daily time series](#daily-time-series) — one pair across a date range

---

### Latest pair rate

Free plan and up. Pairs the tax authority does not print directly are resolved from its table and flagged (see *Official vs derived rates* below).

```js
const pair = await getRate('USD', 'EUR', { apiKey: 'art_live_...' });
```

**Response:**

```javascript
{
  bank: 'douanenl',
  name: 'Netherlands Customs (Douane)',
  rate_date: '2026-11-01',   // Netherlands Customs (Douane)'s own publication date
  source: 'USD',
  target: 'EUR',
  rate: 0.890155,
  rate_type: 'monthly',
  derived: true,
  method: 'inverse',  // computed from the published EUR/USD print
  disclaimer: 'Official rates as published by the named central bank. On weekends/holidays the most recent published rate_date is returned.'
}
```

### Full official table

Free plan and up. The complete table for the latest publication date.

```js
import { getLatestRates } from 'douanenl-exchange-rate';

const table = await getLatestRates({ apiKey: 'art_live_...' });
console.log(table.rate_date, table.rates.length);
```

**Response:**

```javascript
{
  bank: 'douanenl',
  name: 'Netherlands Customs (Douane)',
  rate_date: '2026-11-01',
  rates: [
    { "base": "EUR", "quote": "USD", "type": "monthly", "value": 1.1234 },
    // … the rest of the official table (74 currencies vs EUR)
  ],
  disclaimer: '…'
}
```

### Table for a date

Paid plans. The official table for any date since 2021 — weekends and holidays return the most recent published date, flagged via `published_on_requested_date`, which is exactly the in-force rate a filing needs.

```js
import { getRatesForDate } from 'douanenl-exchange-rate';

const day = await getRatesForDate('2026-06-30', { apiKey: 'art_live_...' });
// Optionally narrow to one pair:
const one = await getRatesForDate('2026-06-30', { apiKey: 'art_live_...', source: 'USD', target: 'EUR' });
```

**Response:**

```javascript
{
  bank: 'douanenl',
  requested_date: '2026-06-30',
  rate_date: '2026-06-30',                // the date actually published
  published_on_requested_date: true,      // false when a weekend/holiday fell back
  rates: [ /* the full table for that date */ ],
  disclaimer: '…'
}
```

### Daily time series

Paid plans. One resolved rate per publication date — ready for charting, revaluation runs, or audit workpapers.

```js
import { getHistory } from 'douanenl-exchange-rate';

const series = await getHistory(
  { source: 'USD', target: 'EUR', from: '2026-01-01', to: '2026-11-01' },
  { apiKey: 'art_live_...' }
);
```

**Response:**

```javascript
{
  bank: 'douanenl',
  source: 'USD',
  target: 'EUR',
  from: '2026-01-01',
  to: '2026-11-01',
  count: 152,
  rates: [
    // one entry per publication date
    { date: '2026-11-01', rate: 0.890155, rate_type: 'monthly', derived: true, method: 'inverse' },
    // …
  ],
  disclaimer: '…'
}
```

Pass `{ symbol: 'USD' }` instead of `source`/`target` to get the raw published rows for one currency (all rate types, no pair resolution).

---

## 🗺️ Currencies covered

Netherlands Customs (Douane) currently publishes rates covering **74 currencies** against the EUR (as of the latest table):

🇦🇪 `AED` · 🇦🇴 `AOA` · 🇦🇺 `AUD` · 🇦🇼 `AWG` · 🇧🇩 `BDT` · 🇧🇬 `BGN` · 🇧🇭 `BHD` · 🇧🇳 `BND` · 🇧🇷 `BRL` · 🇧🇼 `BWP` · 🇧🇾 `BYN` · 🇨🇦 `CAD` · 🇨🇭 `CHF` · 🇨🇱 `CLP` · 🇨🇳 `CNY` · 🇨🇷 `CRC` · 🇨🇿 `CZK` · 🇩🇰 `DKK` · 🇩🇴 `DOP` · 🇩🇿 `DZD` · 🇪🇬 `EGP` · 🇫🇯 `FJD` · 🇬🇧 `GBP` · 🇬🇭 `GHS` · 🇬🇹 `GTQ` · 🇭🇰 `HKD` · 🇭🇺 `HUF` · 🇮🇩 `IDR` · 🇮🇱 `ILS` · 🇮🇳 `INR` · 🇮🇶 `IQD` · 🇮🇸 `ISK` · 🇯🇲 `JMD` · 🇯🇴 `JOD` · 🇯🇵 `JPY` · 🇰🇪 `KES` · 🇰🇷 `KRW` · 🇰🇼 `KWD` · 🇰🇿 `KZT` · 🇱🇰 `LKR` · 🇲🇦 `MAD` · 🇲🇺 `MUR` · 🇲🇼 `MWK` · 🇲🇽 `MXN` · 🇲🇾 `MYR` · 🇳🇬 `NGN` · 🇳🇴 `NOK` · 🇳🇿 `NZD` · 🇴🇲 `OMR` · 🇵🇭 `PHP` · 🇵🇰 `PKR` · 🇵🇱 `PLN` · 🇶🇦 `QAR` · 🇷🇴 `RON` · 🇷🇸 `RSD` · 🇷🇺 `RUB` · 🇸🇦 `SAR` · 🇸🇪 `SEK` · 🇸🇬 `SGD` · 🇸🇷 `SRD` · 🇹🇭 `THB` · 🇹🇳 `TND` · 🇹🇷 `TRY` · 🇹🇹 `TTD` · 🇹🇼 `TWD` · 🇹🇿 `TZS` · 🇺🇦 `UAH` · 🇺🇬 `UGX` · 🇺🇸 `USD` · 🇻🇳 `VND` · `XAF` · `XCG` · 🇿🇦 `ZAR` · 🇿🇲 `ZMW`

## 🏛️ Source

The monthly customs exchange rates (douanemaandwisselkoersen) that Dutch Customs sets for converting foreign-currency invoice amounts into euro when determining customs value. Each rate is in force for a full calendar month and is stated as units of foreign currency per 1 euro.

- Publisher's own page: [Monthly exchange rates for customs and tax](https://kennisbank.douane.nl/wisselkoers-checken/) · [kennisbank.douane.nl](https://kennisbank.douane.nl/)
- Publication: every month; the exact schedule, freshness status and any current delay are on the [Netherlands Customs (Douane) rates page](https://allratestoday.com/tax-authority-rates-api/douanenl/)
- Values are stored unmodified, with the publisher's own `rate_date` on every row — see the [methodology](https://allratestoday.com/official-rates-methodology/)

## 🧭 Reading the numbers

- `value` is always **quote currency per 1 unit of base currency** (`base: "EUR", quote: "USD", value: 1.15` means 1 EUR = 1.15 USD).
- Netherlands Customs (Douane) quotes **foreign currency per 1 EUR** (e.g. `base: "EUR", quote: "USD"` means USD per one EUR).
- Need the other way round? Ask `getRate(target, source)` and the API inverts or crosses for you, flagged `derived: true` — never divide a published rate yourself in a compliance workflow.
- `rate_type` tells you which of the tax authority's series a row belongs to (`monthly` here); some publishers print buy/sell or several fixings for the same pair.

## 🧩 ERP & accounting systems

Loading the official Netherlands Customs (Douane) rate into an accounting system is a supported workflow, not a hack. Step-by-step guides with the direction each system expects:

- [Dynamics 365 Business Central](https://allratestoday.com/docs/integrations/business-central/) — built-in Currency Exchange Rate Service, no code
- [Xero](https://allratestoday.com/docs/integrations/xero/) · [QuickBooks Online](https://allratestoday.com/docs/integrations/quickbooks/) · [SAP S/4HANA and ECC](https://allratestoday.com/docs/integrations/sap/) · [Odoo](https://allratestoday.com/docs/integrations/odoo/)

The same keyed endpoints return `?format=csv`, `?format=xml` and `?format=xlsx`, and accept the key as `?api_key=` on the URL for importers that cannot send headers:

```bash
curl "https://allratestoday.com/api/v1/central-bank/douanenl/latest?format=xml&api_key=art_live_..."
```

## 🤖 AI agents

- MCP server: `npx -y @allratestoday/central-bank-mcp` (stdio) or the hosted endpoint `https://allratestoday.com/api/mcp` — tools for official rates, history, cross-bank comparison and publication calendars
- Already using the general SDK or MCP server? Since 2026-10-01 [`@allratestoday/sdk`](https://www.npmjs.com/package/@allratestoday/sdk) 1.4+ has `officialRates('douanenl')` and [`@allratestoday/mcp-server`](https://www.npmjs.com/package/@allratestoday/mcp-server) 0.6+ has a `get_official_rates` tool — both return this source's latest table with no key, so you can add it without a second dependency
- Claude Code plugin (no key): `/plugin marketplace add AllRates-Today/claude-code-plugin` then `/plugin install allratestoday@allratestoday` — bundles both MCP servers plus an `/official-rate douanenl ...` command
- Evaluating? Agents can self-issue a trial key with no signup: `POST https://allratestoday.com/api/agent/keys` (send `Content-Type: application/json`) returns a 100-call key valid 7 days that covers the free-plan methods (latest table, pairs); dated tables and history need a [paid plan](https://allratestoday.com/pricing/). The MCP servers expose it as `request_trial_key`
- Machine-readable site guide: [llms.txt](https://allratestoday.com/llms.txt) · [for-ai-agents](https://allratestoday.com/for-ai-agents/)

## ⚖️ Official vs derived rates

If Netherlands Customs (Douane) does not print a pair directly, the API resolves it from the tax authority's own table and says so — official and computed values are never confused:

| `method` | `derived` | Meaning |
| --- | --- | --- |
| `published` | `false` | The tax authority printed this pair directly |
| `inverse` | `true` | Computed as 1 ÷ the published opposite direction |
| `cross` | `true` | Computed via EUR from two published rates |

## 🛡️ Error handling

Errors are thrown as `Error` with `status` (HTTP code) and `body` (the API's JSON error) attached:

```js
try {
  const pair = await getRate('USD', 'XXX', { apiKey: 'art_live_...' });
} catch (err) {
  console.log(err.message); // human-readable reason
  console.log(err.status);  // e.g. 404
}
```

| Status | Meaning |
| ------ | ------- |
| — | Missing `apiKey` (thrown before any request) |
| `400` | Malformed date or parameters |
| `401` | Invalid API key |
| `403` | Endpoint needs a [paid plan](https://allratestoday.com/pricing/) (historical dates & series) |
| `404` | Pair or date range not covered by Netherlands Customs (Douane) |
| `429` | Monthly quota exceeded |

## 🔷 TypeScript

Full definitions ship with the package — no `@types` install:

```ts
import type { LatestRates, PairRate, DatedRates, RateEntry, HistoryQuery, RequestOptions } from 'douanenl-exchange-rate';
```

## 📦 CommonJS

```javascript
const { getRate } = require('douanenl-exchange-rate');

getRate('USD', 'EUR', { apiKey: 'art_live_...' }).then((pair) => console.log(pair.rate));
```

## 💡 Quota tips

- Rates change once a month — cache the official table locally and a small monthly quota goes a long way.
- Every request counts toward your AllRatesToday quota, shared across all AllRatesToday endpoints on your key.

## 📖 Methods reference

| Method | Plan | Description |
| ------ | ---- | ----------- |
| `getRate(source, target, { apiKey })` | Free | Latest rate for one pair, resolved from the official table |
| `getLatestRates({ apiKey })` | Free | The tax authority's full latest official table |
| `getRatesForDate(date, { apiKey, source?, target? })` | Paid | The official table (or one pair) for a YYYY-MM-DD date |
| `getHistory({ symbol \| source+target, from?, to? }, { apiKey })` | Paid | Daily series since 2021 |

## 📥 Bulk data (no key)

Need the whole archive rather than an API call? The same official tables are mirrored daily as open data:

- Hugging Face: [AllRatesToday/central-bank-exchange-rates](https://huggingface.co/datasets/AllRatesToday/central-bank-exchange-rates) — one CSV per institution (`rates/douanenl.csv`)
- Kaggle: [allratestoday/central-bank-exchange-rates](https://www.kaggle.com/datasets/allratestoday/central-bank-exchange-rates)
- Raw JSON on GitHub: `https://raw.githubusercontent.com/AllRates-Today/central-bank-exchange-rates/main/data/douanenl/latest.json`

## 🔗 Links

- **Website:** [allratestoday.com](https://allratestoday.com)
- [Netherlands Customs (Douane) rates page](https://allratestoday.com/tax-authority-rates-api/douanenl/) — live table, publication cadence, FAQ
- [All tax authority sources](https://allratestoday.com/tax-authority-rates-api/) · [Full list of 120+ central banks and 50+ tax authorities](https://allratestoday.com/central-bank-rates-api/institutions/) — one API, the same response shape for every source
- [Download central bank rates](https://allratestoday.com/download-central-bank-rates/) — every bank's latest table and history as Excel, CSV or JSON
- [Bank Exchange Rate API](https://allratestoday.com/bank-exchange-rate-api/) — live buy and sell rates from 1,200+ commercial banks in 120+ countries · [npm](https://www.npmjs.com/package/bank-exchange-rates) · [GitHub](https://github.com/AllRates-Today/bank-exchange-rates)
- [Package docs on the site](https://allratestoday.com/docs/sdk/douanenl-exchange-rate/) · [ERP integration guides](https://allratestoday.com/docs/integrations/)
- [API documentation](https://allratestoday.com/docs/#central-bank) · [Interactive reference](https://allratestoday.com/api-reference/) · [Methodology](https://allratestoday.com/official-rates-methodology/)
- [Register (Free)](https://allratestoday.com/register) · [Dashboard](https://allratestoday.com/profile) · [Pricing](https://allratestoday.com/pricing/)
- [Status](https://allratestoday.com/status)
- [Postman collection](https://allratestoday.com/postman/)
- [ChatGPT app](https://chatgpt.com/plugins/plugin_asdk_app_6ae1e76098f48191a285ac3f5ab7a83b) — ask ChatGPT for live and official central bank rates
- [OpenAPI reference on Bump.sh](https://bump.sh/allratestoday/doc/allratestoday-api) — also on [SwaggerHub](https://app.swaggerhub.com/apis-docs/allratestoday/allratestoday-exchange-rate-central-bank-rates-api/2.2.0)
- [GitHub](https://github.com/AllRates-Today/douanenl-exchange-rate)

## 📜 License

MIT
