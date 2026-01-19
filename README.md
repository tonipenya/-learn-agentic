# 🤖 Agentic Playground

This repo is a **hands-on playground to learn agentic AI libraries** by actually building things, breaking them, and understanding why.

It’s intentionally small, informal, and focused on _how these systems behave in practice_, not on shipping a product or polishing abstractions.

## What’s in here

- A **LangGraph quickstart**, followed more deeply than the docs:
    - stepping through state, nodes, edges, and control flow
    - inspecting how decisions propagate through the graph
    - understanding what’s implicit vs what you have to manage yourself
- A **mock travel assistant** built to explore:
    - tool calling (e.g. flight status, reservation changes)
    - short-term vs long-term memory
    - retrieval-augmented generation
    - human-in-the-loop interruptions
    - lightweight multi-agent delegation

Everything is simplified on purpose. The goal is learning, not realism.

## Why this exists

I wanted a place to:

- move past “hello world” agent demos
- see where agentic abstractions help — and where they leak
- experiment freely without framework lock-in or demo pressure

No claims of best practices. No benchmarks. Just working notes turned into code.

## How to use it

Open the notebooks and read them top to bottom:

- [`quickstart.ipynb`](./quickstart.ipynb) — LangGraph fundamentals, explored slowly
- [`travel_assistant.ipynb`](./travel_assistant.ipynb) — a slightly more opinionated, end-to-end example

Tweak things. Break flows. Print state. That’s the point.

## What this is _not_

- Not a production system
- Not a reference architecture
- Not a framework comparison

## Status

This is a **learning project**. Expect experiments, rough edges, and changing ideas.

If you’re curious about agentic systems beyond the slides, this kind of repo is fun to build.
