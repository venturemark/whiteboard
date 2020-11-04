# Consistent Codebase



### Context

- Venturemark wants to deliver high quality products and services while being
  able to move insanely fast.
- Depending on the proficiency and ambition to develop and maintain a healthy
  codebase, the actually delivered quality may vary.
- In order to succeed with any venture we aim for we have to own our destiny and
  always be in control of our own technology.
- Inconsistent codebases increase complexity. Increased complexity is harder to
  manage. Hard to manage codebases are unpredictable. Unpredictability in
  codebases will cause unpredictable incidents on the product and service we
  deliver to our users. This is unacceptable.



### Alternatives

- There are probably different ways to approach the current situation, though we
  move forward based on our current educated guess.



### Decisions

- We will only maintain consistent codebases. This means we cannot afford to
  stay for too long in transitioning phases. One example for this may be any
  structural technical debt like javascript to typescript migrations. Another
  example might be any data migration like removing properties from resources
  throughout the technical stack.
- We will adhere to several best practices where applicable, though without
  compromise. One example may be seperation of concerns like defining distinct
  modules or packages per use case. Another example might be automated testing.



### Consequences

- [Tim](https://github.com/xh3b4sd) will be requested to review any pull request
  being made in order to enable more collaboration. That aims to help sharing
  knowledge on best practices and influence the quality of our codebases for the
  better.
- We will establish a rule that allows us to migrate our existing react app to
  use typescript exclusively, without allowing to write any bare javascript
  ourselves anymore. The rule is, that no pull request can be merged anymore if
  it contains the additional of plain javascript. That means, if javascript has
  to be written, refactoring has to be done in typescript with as little impact
  as possible. We understand that this process might take some time. We will
  iterate here as usual.
