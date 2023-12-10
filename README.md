# Typescript Labs

## Lab 12: Narrowing Down Union Types

file: `/src/12-typeof-narrowing.problem.ts`

Consider this function:

```ts
const coerceAmount = (amount: number | { amount: number }) => {};
```

What this is saying is that what we pass into `coerceAmount` can be either a number or an object that contains an `amount`.

Challenge
Your challenge is to write the function so that the tests pass.

There will be some little type errors along the way, but this is an interesting problem to solve.

