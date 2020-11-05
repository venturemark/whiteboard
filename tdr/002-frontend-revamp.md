# Frontend Revamp



### Context

- Venturemark wants to move insanely fast while being in control of our own
  technology.
- The current frontend app contains a lot of legacy that makes it very hard to
  move forward in a reasonable way.
- We could refactor the existing codebase, though this does not seem to be the
  best option considering the effort required.
- Starting over from scratch is promising because it gives us the chance to half
  the associated complexity.
- We want to start on a green field and be able to move insanely fast again.



### Decisions

- We will abandon the current frontend app and start over again from scratch.
- We will start over again with a fresh React App in pure Typescript.
- We will start over again without Redux and see how far we come without it.
- No plain Javascript is allowed anymore. We must be strict with it.



### Alternatives

- The alternative is to take all the effort required for refactoring the
  existing codebase.



### Consequences

- We are free to start out with Typescript only.
- We are free to start without Redux.
- [Tim](https://github.com/xh3b4sd) gets a fair chance to start participating in
  the frontend development.
- [Tim](https://github.com/xh3b4sd) and [Marcus](https://github.com/marcusellison)
  get a fair chance to start sharing knowledge on the frontend architecture so
  that we can evolve our mental models together.
