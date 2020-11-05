# Frontend Guidelines



### Context

- Venturemark wants to move insanely fast while being in control of our own
  technology.
- We want to implement the frontend in Typescript since this appears to be the
  most reasonable choice.
- Writing Typescript does still somehow mean to write a form of Javascript and
  the primitives and complexity allowed can still become very dangerous if one
  does not know what they are doing.
- We always want to reduce complexity and adhere to certain best practices so
  that the dark forest will not be so dark anymore.



### Decisions

- We will not make use of "classes" anywhere in our code.
- We will not make use of "variadics" anywhere in our code.
- We will not make use of "overloading" anywhere in our code.
- We will try to design the system in a way that allows us to define modules and
  components which do one single thing very well.
- We will not mix different responsibilities within the packages and libraries
  we define.
- We will consciously implement well defined interfaces for our modules.



### Alternatives

- The alternative is to allow anyone to do whatever they think is right without
  being assured that the right decisions have been made in the first place.



### Consequences

- Reducing complexity should make the frontend development more predictable and
  reliable.
- Establishing a few well understood concepts and best practices increases speed
  of development and reduces the risk of degrading quality of service.
