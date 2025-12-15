# AI Product Engineer Challenge

## About Us

We help enterprises deploy and operate private AI systems, building AI infrastructure that solves real business problems.

---

## The Challenge

**Choose one of the following tasks and complete it within 48 hours.**

---

### A. Contextual Retrieval

Given 100 enterprise internal messages, build a semantic search system.

```
Input:  Natural language query
Output: Top 5 relevant messages + relevance scores
Constraint: Do not use off-the-shelf vector databases
```

Test data: [`data/messages.json`](data/messages.json)

*Hint: We care about how you define "relevance"*

---

### B. Memory Compression

Given a 20-turn conversation, compress it while preserving key information.

```
Input:  Full conversation history
Output: Compressed context under token limit
Require: Design compression strategy + evaluation method
```

Test data: [`data/conversation.json`](data/conversation.json)

*Hint: Compression is easy. Losing nothing important is hard.*

---

### C. Tool-Use Agent

Build an agent that can call tools and handle errors gracefully.

```
Require: Tool definitions + call chains + error handling
Deliver: Interactive demo
```

*Hint: We will test edge cases you didn't think of*

---

## Deliverables

- **GitHub Repo** - Your code and documentation
- **Live URL** - Accessible demo
- **README** - More important than code. Explain your decisions, not just your implementation.

---

## Hints

- Free LLM APIs with tool-use support exist. Finding them is part of the challenge.
- Good retrieval considers more than recency.
- Good compression defines what "important" means.
- Good engineering handles what can go wrong.
- Good documentation explains why, not just how.

---

## We Value

- Problem-solving approach over perfect code
- Engineering taste over feature quantity
- Honest limitations over hidden flaws
- Clear thinking over complex solutions

---

## Timeline

**48 hours** from when you start.

---

## Submission

Send to yuxinyue3@gmail.com with:
- GitHub repo link
- Live demo URL
- Which task you chose (A/B/C)

---

Good luck. Show us how you think.
