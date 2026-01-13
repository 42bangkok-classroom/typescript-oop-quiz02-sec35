# Subject 2 — Filter Posts By User

## API Endpoint

```
https://jsonplaceholder.typicode.com/posts
```

## Function name

`getPostsByUser`

## Function interface

```tsx
getPostsByUser(userId)
```

## Description

Fetch posts and return only posts that belong to the given `userId`.

Return only `id` and `title`.

## Example input

```tsx
getPostsByUser(1)
```

## Example output

```json
[
  { id: 1, title: "sunt aut facere repellat provident occaecati" },
  { id: 2, title: "qui est esse" }
]
```

## Global Rules

- Use **axios**
- Use **async / await**
- Use **try / catch**
- One function per subject
- Use at least one **array or object method**
- No `any`
- Function must **return value only** (no console.log)

