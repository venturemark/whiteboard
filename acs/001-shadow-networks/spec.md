# Shadow Networks



### Context

- We want to outline a rough list of acceptance criteria for the next iteration
  of our product. What we want to achieve is the next level PoC that helps us
  validate value.
- This acceptance criteria specification is related to its shadow network [PDR].



### Resources

- An organization is e.g. Venturemark or Baronfig. An organization has
  timelines.
- A timeline is the place to write updates. A timeline is accessible for an
  audience.
- An audience is a group of users. For now we just have a few of them hardcoded,
  e.g. customers, employees, investors and vendors.
- An update is written text on a timeline's timeline. An update has comments and
  replies.
- A founder is the user-owner of the organization
- A member is a user that has access to read/write timelines within an organization



### Components

- The sidebar to the left of the screen provides space for a list of resources
  like organizations or timelines. This acts as navigation mechanism.
- The editor is an input field that for now only needs to accept text for
  updates.



### Experiences

- As a founder I want to visit the Venturemark web-app to check my
  organization's progress. The first thing I see on the home screen is a list of
  timelines on the left side of the screen. Timelines might be "Recruiting" or
  "Marketing".
- There is an "All Updates (Private)" timeline that aggregates all the existing timelines.
- As a founder I want to see a project's progress. Therefore I click on a
  timeline in the sidebar. Then I see the name of the timeline and a
  description. I see the text editor and updates that have already been added.
  Every update shows the text, the date of its creation and the amount of
  comments it has.
- As a founder I want to see the comments of an update and be able to write my
  own reply. I do not want to see comments and replies of all updates all the
  time. I only want to see them if I choose to do so.
- As a founder I want to see the latest updates. Therefore the timelines in the
  sidebar are sorted based on two criteria. Primarily timelines are sorted based
  on recent updates. Secondarily timelines are sorted alphabetically. Recent
  updates on timelines are signified by some red notification dot on the
  timeline within the sidebar.
- As a founder I want to write updates myself. Choosing a timeline, I just write
  my update in the text editor and add it to the timeline by clicking some
  "send" button. If I try to add an update without choosing an audience there
  will be an error displayed. I can choose multiple of the hard-coded audiences.
  The new update gets added at the top of the list of updates I see. The red
  notification dot does not occur for me if I add an update in this particular
  timeline.

- As a member of an organization, I can create an update for a timeline I follow.
- As a member of an organization I can comment on an update.



[PDR]: /pdr/001-shadow-networks.md
