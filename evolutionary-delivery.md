# Evolutionary Delivery

## Intro

## Summary

- Balances between:
  - Staged Delivery's _control_.
  - Evolutionary Prototyping's _flexibility_.
  - Maintains both of their _signs of progress to customer_.
- Main Characteristics
  - Delivers _some_ portions earlier.
  - Does not deliver entire product earlier.
  - Allows mid-course product changes based on customer feedback.
- Grocery shopping analogy:
  - Staged Delivery: take a complete list to the store.
  - Evolutionary Prototyping: take no list to the store; improvise!
  - Evolutionary Delivery: Take a list to the store, improvise a bit when you get there.

## Risks

- Feature Creep.
- Diminished Project Control.
- Unrealistic budget/schedule expectations.
- Inefficient use of development time by developers.

## Interactions and Tradeoffs

- Requires skill designing for change.
- Recall: good design lets us change X without changing Y.

## Benefits

- Reduces risk of delivering a product the customer does not want.
- Makes progress visible by delivering early and often.
- Reduces estimation error via recallibration after each delivery.
- Reduces integration problems by integrating early and often.
- Improves morale because devs see success from the first "Hello World!"

# Sidebar

> - Question: What happes if you do not follow all these steps?
> - Answer: What happens if you play an 'off book' move in the Sicilian?
>   - find a new variation,
>   - fall into a classic trap,
>   - find a workable approach for this particular game.
> - Lifecycle patterns, like chess opening, continue to evolve over time.
> - Stand on the shoulders of giants but avoid dogmatism.

# Using Evolutionary Delivery

1. Architect the fundamental core of the system.
   - Define what the customer fundamentally wants.
   - Create a system architecture core based on that.
   - Creating a flexible system core determines your success.
2. For each iteration, lean more toward Staged Delivery or Evolutionary Prototyping.
   - How many interations can you afford to make?
   - How often can you afford to change your mind?
   - After each delivery, clarify expectaions on control vs flexibility.
   - Consider sticking to a firm number of iterations.
3. Loop through iterations:
   - Develop the version.
   - Release the version.
   - Solicit customer feedback.
   - Incorporate customer feedback.
4. Deliver final version.
   - Does this every _really_ happen in SaaS?
   - When can we call a project "done" in SaaS?

# Release Order

- Release the flexible system core, "Hello world!"
- Then release the functionality you feel most confident that the customer wants.
- Make sure the customer really wants it - before you start to work on it.

# When to Use Evolutionary Delivery

- Staged Delivery
  - Well understood system.
  - Few surprises.
- Evolutionary Prototyping
  - Poorly understood system
  - Lots of surprises (especially fundamental ones).
- Evolutionary Delivery
  - Know enough about the system.
  - Able to design core architecture from the outset.
