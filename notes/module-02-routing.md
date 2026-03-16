# Module 02 – Routing

## What this module teaches

Axum routing fundamentals.

## Core Concepts

- Router
- Route
- HTTP method handlers

## Key Code Pattern

```rust
Router::new()
    .route("/", get(handler))
```

## Mental Model

Router = map

`path + method → handler function`

## Lessons (Maxims)

1. Routes map HTTP requests to async functions

2. Handlers must be async

3. Router composition enables modular APIs

## Experiments I tried

- Added a new route

- Tested POST vs GET

## Questions

- How does Axum match dynamic routes?
