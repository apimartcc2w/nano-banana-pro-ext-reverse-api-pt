# Nano Banana Pro Ext — engenharia reversa route (Português)

> **1K $0.03; 4K $0.04** · model ID `gemini-3-pro-image-preview` · **engenharia reversa/reverse-engineered** route.

**[Ver preços](https://go.apimart.ai/k-3252aa)** · **[Obter chave de API](https://go.apimart.ai/k-f9074c)**

nano-banana-pro-ext-reverse-api-pt é uma rota **engenharia reversa** para Nano Banana Pro Ext: ID chamável `gemini-3-pro-image-preview`, em paralelo com a rota oficial (`nano-banana-pro (gemini-3-pro-image-preview-official)`) a um preço unitário menor.

## Pricing (snapshot 2026-09-28)

| Tier | Price |
| --- | --- |
| `1K` | $0.03 |
| `4K` | $0.04 |

Prices are per delivered image; `n` in the request multiplies the total. Snapshot date **2026-09-28** — the live pricing page is authoritative.

## Quickstart

```bash
curl -X POST https://api.apimart.ai/v1/images/generations \
  -H 'Authorization: Bearer $APIMART_KEY' \
  -H 'Content-Type: application/json' \
  -d '{"model":"gemini-3-pro-image-preview","prompt":"cozy reading nook, warm lamp, cinematic","size":"1:1","resolution":"1K","n":1}'
```

Async: submit → get `task_id` → poll `GET https://api.apimart.ai/v1/tasks/<task_id>` → read `cost` / `credits_cost` from the result. Parameter tables, `version`/`resolution`/`size` options and idempotency headers are documented on the model page reachable from the pricing link above.

## Reverse vs official route

| Route | Callable ID | Price |
| --- | --- | --- |
| **engenharia reversa** | `gemini-3-pro-image-preview` | 1K $0.03; 4K $0.04 |
| roteamento oficial | `nano-banana-pro (gemini-3-pro-image-preview-official)` | official list price, billed at ×0.8 group ratio |


## Keywords

`nano-banana-pro-ext` · `gemini-3-pro-image-preview` · `engenharia reversa` · `reverse-engineered` · `gateway de API` · `relay de API` · `nano banana 2 api` · `gpt-image-2.5 api` · `ai api pricing` · `pay-as-you-go`

## Platform facts

- USD settlement, pay-as-you-go, **$1 minimum top-up**, no subscription.
- Operating since last year; ~100,000 registered users, mostly enterprise accounts.
- International invoices available on request.
- 307 models online (live `/v1/models`) as of 2026-09-28.

## Disclosure

This repository documents **APIMart**, a third-party API aggregator/gateway. It is **not affiliated with, endorsed by, or sponsored by** OpenAI, Google, Anthropic, xAI, ByteDance or any model vendor. Model names and trademarks belong to their owners. Prices are a point-in-time snapshot and may change; the vendor's console billing is authoritative.

