## Project Structure

```

├── struct1/  # Linear
├── struct2/  # Review           
├── struct3/  # Debate
├── struct4/  # Vote

```

## 1. Install Dependencies
1. set up metagpt
```
pip install metagpt
```
## 2. Configure llm for agents
```
~/.metagpt/config2.yaml
llm:
    model: "deepseek-reasoner"
    base_url: "https://api.deepseek.com"  # or forward url / other llm url
    api_key: <DEEPSEEK_API_KEY>

```
## 3. Run
```
python struct1/linear_defense0.py
```
