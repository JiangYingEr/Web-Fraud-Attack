## Project Structure

```

├── struct1/               # AutoGen Framework Tests
│   ├── test_attacks_1_4.py    # Attack Commands 1-4
│   ├── test_attacks_5_8_updated.py  # Attack Commands 5-8
│   └── test_attacks_9_11_final.py   # Attack Commands 9-11
└── camel_example/                # CAMEL Framework Tests
    ├── .env                   # Environment Variables
    ├── 1-4.py                 # Attack Commands 1-4
    ├── 5-8.py                 # Attack Commands 5-8
    └── 9-11.py                # Attack Commands 9-11
```

## Quick Start

### 1. Install Dependencies

**For AutoGen Framework:**
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
