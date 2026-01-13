# Subject 4 — Count Comments Per Post

## API Endpoint

```
https://jsonplaceholder.typicode.com/comments
```

## Function name

`countCommentsByPost`

## Function interface

```tsx
countCommentsByPost()
```

## Description

Fetch comments and return an object that shows how many comments each post has.

Note: The object keys should be numbers (post IDs), not strings.

## Example output

```json
{
	1: 5,
	2: 5,
	3: 5
}
```

## Global Rules

- Use **axios**
- Use **async / await**
- Use **try / catch**
- One function per subject
- Use at least one **array or object method**
- No `any`
- Function must **return value only** (no console.log)

