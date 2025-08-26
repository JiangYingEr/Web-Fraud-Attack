
## Environment Setup 
1. set up metagpt
```
pip install metagpt
```
2. configure llm for agents
```
~/.metagpt/config2.yaml
llm:
    model: "deepseek-reasoner"
    base_url: "https://api.deepseek.com"  # or forward url / other llm url
    api_key: <DEEPSEEK_API_KEY>

```
