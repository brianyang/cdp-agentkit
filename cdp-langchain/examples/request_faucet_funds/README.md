# CDP Agentkit Langchain Extension Examples - Request Faucet Funds

This example demonstrates how to request test tokens from a faucet and store them in the wallet using the CDP Agentkit Langchain Extension.

## Requirements
- Python 3.10+
- [CDP API Key](https://portal.cdp.coinbase.com/access/api)
- [OpenAI API Key](https://platform.openai.com/docs/quickstart#create-and-export-an-api-key)

### Checking Python Version
Before using the example, ensure that you have the correct version of Python installed. The example requires Python 3.10 or higher. You can check your Python version by running the following code:

```bash
python --version
pip --version
```

## Installation
```bash
pip install cdp-langchain
```

## Run the Request Faucet Funds Example

### Set ENV Vars
- Ensure the following ENV Vars are set:
  - "CDP_API_KEY_NAME"
  - "CDP_API_KEY_PRIVATE_KEY"
  - "OPENAI_API_KEY"
  - "NETWORK_ID" (Defaults to `base-sepolia`)

```bash
python request_faucet_funds.py
```
