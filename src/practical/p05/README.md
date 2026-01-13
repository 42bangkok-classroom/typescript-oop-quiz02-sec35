# Subject 5 — Safe Fetch Comment

## API Endpoint

```
https://jsonplaceholder.typicode.com/comments/{id}
```

## Function name

`safeFetchComment`

## Function interface

```tsx
safeFetchComment(commentId)
```

## Description

Fetch a single comment by `commentId`.

Rules:

- If any error occurs, return `null`
- If successful, return an object with `id` and `body`

## Example input

```tsx
safeFetchComment(1)
```

## Example output

```json
{ id: 1, body: "laudantium enim quasi..." }
```

## Example input

```tsx
safeFetchComment(9999)
```

## Example output
```ts
null
```

## Global Rules

- Use **axios**
- Use **async / await**
- Use **try / catch**
- One function per subject
- Use at least one **array or object method**
- No `any`
- Function must **return value only** (no console.log)

