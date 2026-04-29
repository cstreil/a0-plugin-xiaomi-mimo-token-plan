# Xiaomi MiMo Token Plan Provider for Agent Zero

Adds Xiaomi MiMo Token Plan EU/AMS as an OpenAI-compatible LLM provider for Agent Zero.

## Provider details

| Field | Value |
|---|---|
| Provider ID | `xiaomi_mimo_token_plan` |
| Provider name | `Xiaomi MiMo Token Plan` |
| LiteLLM provider | `openai` |
| API base | `https://token-plan-ams.xiaomimimo.com/v1` |
| Suggested model | `mimo-v2.5-pro` |

## Installation

Install this repository as an Agent Zero community plugin, or copy the repository contents to:

```text
/a0/usr/plugins/xiaomi_mimo_token_plan/
```

Restart Agent Zero or reload plugin/provider configuration after installation.

## Usage

1. Open Agent Zero model/provider settings.
2. Select **Xiaomi MiMo Token Plan**.
3. Enter your existing provider API key in the provider API-key field.
4. Use model `mimo-v2.5-pro` or another compatible model exposed by the provider.

## Notes

- Uses the EU/AMS Token Plan OpenAI-compatible endpoint.
- Token Plan keys typically use the `tp-...` format.
- Model discovery uses the conventional `/models` endpoint.

## Disclaimer

This is an independent community plugin. It is not affiliated with, sponsored by, or endorsed by the respective model provider. Use at your own risk.

## License

MIT License. See [`LICENSE`](LICENSE).
