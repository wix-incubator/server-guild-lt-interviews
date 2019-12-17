# Feedback

This document is aiming to aggregate a set of generic rules to make writing good feedback a little easier. Note that it is by far not covering everything.

P.S. Don't forget that common sense goes above all guidelines. Be smart.

## Purpose

Each point in feedback should be aimed to helping receiving person improve. Think about it when writing each of the points.

## Actionable Points

Feedback loses a lot of value if it's not clear what action receiver should take. In most cases it manifests as one of two properties:

A. Reference to a topic or source that covers the point.

B. Suggesting an alternative.

```
Yes:
- Design of X is not testable. One way would be to extract logic A and test it separately.

No:
- Design of X is not testable.
```

## Staying Specific

To avoid ambiguity and confusion, stay as specific as you can. If having hard time rephrasing, you could add an example.

```
Yes:
- Prone to race conditions. I.e. same ID could be picked for different records in createNewUser method.

No:
- Prone to race conditions.
```

## Staying Factual

Keeping feedback factual makes it easier to consume and act on.

```
Yes:
- Did not solve the problem without help.

No:
- Had hard time solving the problem.
```

## Targeting Criticism

Criticism (when possible) should be targeted at the submission/solution and not the candidate. It helps avoiding mental blocking.

```
Yes:
- Solution doesn't handle invalid inputs.

No:
- Didn't implement handling invalid inputs.
```
