

The .py files in We did not test all architectures using Autogen and CAMEL, which is costly. Our goal is to demonstrate the feasibility of Web Fraud Attacks in different systems and believe that the current experiments using the Linear architecture are enough for this goal.

## Project Structure

```

├── autogen_example/               # AutoGen Framework Tests
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
```bash
pip install autogen-agentchat autogen-ext openai
```

**For CAMEL Framework:**
```bash
pip install camel-ai colorama python-dotenv
```

### 2. Configure API Keys

Edit `camel_example/.env` file:


For AutoGen tests, update the API keys directly in the Python files.

### 3. Run Tests

**AutoGen Tests:**
```bash
cd autogen_example
python test_attacks_1_4.py
python test_attacks_5_8_updated.py
python test_attacks_9_11_final.py
```

**CAMEL Tests:**
```bash
cd camel_example
python 1-4.py
python 5-8.py
python 9-11.py
```

