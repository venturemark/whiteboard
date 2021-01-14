# Shadow Networks



### Context

- We use feedback sessions to balance hypothesis with truth. Based on our feedback sessions January 4th, 2021 - January 9th, 2021 we've gained more insights:

- Our new target destination is codename shadow networks, aka private twitter,
  aka progress tracker.
- We want to:
 1. enable startup founders to send organization updates to different stakeholders
 2. for members if organizations to provide updates to timelines in an organization.
 3. provide a space for members with access to the timeline a place to engage.
- Our goal is to come as close as we can in 1 week to a functional product that allows founders to feel the application experience. However, we suspect this product may be more prototype than production-ready.



### Alternatives

- Continue to optimize product for metric-updates
- Focus on a single player mode experience.



### Decisions

- We will rush out a hacked-together version in order to deploy our next iteration within 1 week. This allows us to not be blocked by current backend changes.
- Within 7 days we would like to schedule our next feedback sessions with potential customers.
- We want to build a frontend prototype without backend during this iteration.
  The backend is mocked using local storage or similarly trivial to implement alternative.
- It does not have to be perfect right now. It does not have to be pretty.
- Generic backend functionality can be implemented  in preparation for a beta launch.
- Conceptually, our first class citizen is an organization. An organization has
  timelines. A timeline is accessible for an audience. An audience is a group of
  users. A timeline is the place to write updates. As a bonus, an update has
  comments and replies.



### Consequences

- [Marcus] continues business development and strategy.
- [Thiago] gets synchronized and builds the frontend. This is the only focus we
  need right now.
- [Tim] prepares a technical spec and pairs with Thiago. Further Tim tries to
  continue building generic backend technology that can prove to be useful in
  any case of strategy deviation.


[Marcus]: https://github.com/marcusellison
[Thiago]: https://github.com/thiagovasconcellos
[Tim]: https://github.com/xh3b4sd
