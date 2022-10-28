# Staged Delivery

## Introduction

- Delivery/ship in stages.
- Ship from most important to least important.
- Does NOT reduce the time needed to build the software.
- Does reduce risks and increase progress visibility.
- Requires careful upfront planning.
- You must know exactly what you're going to build when you set out.
   - similar here to waterfall.
   - dissimilar here to evolutionary prototyping

## Risks

Feature Creep

## How does it work?

Waterfall phase:

1. Software Concept
1. Requirements Analysis
1. Architectural Design

Staged delivery starts here!

Plan a series of deliverables...

1. Stage 1: Detailed design, code, debug, test, delivery...
2. Stage 2: Detailed design, code, debug, test...
3. Stage 3: Detailed design, code, debug...
4. Et cetera.

Guidlines:

- Each stage has a _delivery date._
- First stage delivers the germ of the product. 
- Last stage completes the project.
- Planning the first stage requires the most architectural insight.
- You may "deliver" early stages internally to aid integration / QA / progress tracking...
- Each stage ends with a truly releasable product.
- Caution with technical dependency planning.
- Themed releases help reduce feature-by-feature negotiations.

## Advantages?

- More visible progress for customer-driven software.
- Shorter product-release cycles for shrink-wrap software development.
- Early warning of problems.
- Less overhead.
- Makes more options available.
- Minimizes integration problems.

---

- Delivers useful features to the customers earlier than waterfall does.
- Deliver the _most important_ features first.
- This follows the Minimum Viable Product approach at each stage.
- Tangible signs of progress reduces schedule pressure.

## Disadvantages?

- Some developers find delivery dates too restrictive.
- Requires careful planning by management and engineering.
- Understanding what stages customers find meaningful.
- Distribute work to engineers to complete work by the stage deadline.
- Needs to account for technical dependencies among stages.
    - Classic mistake:
    - Plan a feature for delivery in stage 2,
    - that feature relies on feature from stage 4.
    - :-(

## When to use?

* Well understood projects.
* Very large projects.
* Customers will accept incremental releases.
* Possible to design incremental releases.