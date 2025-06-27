```python
from typing import TypedDict, List

class About(TypedDict):
    name: str

class Links(TypedDict):
    telegram: str
    codeforces: str
    leetcode: str

class Info(TypedDict):
    about: About
    links: Links
    tech_stack: List[str]

info_awayB02: Info = {
    "about": {
        "name": "Khabib Shakhbanov"
    },
    "links": {
        "telegram": "@stereotuple",
        "codeforces": "@502BadGateway",
        "leetcode": "@502BadGateway"
    },
    "tech_stack": ["Python", "FastAPI", "PostgreSQL"]
}

```
