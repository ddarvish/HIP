# HIP Template

- Author(s): @ddarvish 
- Start Date: <!-- 2022-01-07 
- Category: Technical
- Original HIP PR: <!-- leave this empty; maintainer will fill in ID of this pull request -->
- Tracking Issue: <!-- leave this empty; maintainer will create a discussion issue -->

# Summary
[summary]: #summary

People are just putting up hotspots willy nilly without understanding the consequnces of overcrowding a particular hex and reducing the rewards for other users in the hex while also not maximizing the earnings they could make by placing it in a less crowded hex. In a 1 month period for example a hex went from a transmit scale of .8 down to .03. Those who setup hotspots there first got screwed in the earnings they make. Using information for when a hotspot asserts its location we can create a list of who came to a particular location first. We then scale rewards based on this factor. Any hotspot that comes in an area after some number of hotspots would effectively make no HNT in PoC challeneges but only in data transfer rewards. The idea is to not penalize those who installed their hotspots first in an area which later on gets oversatured. Ideally each person who installs a hotspot does some research to determine if adding another hotspot to that location makes sense in a technical aspect and finacncial ROI. This will also encourage hotspots installed to favor areas of little to no coverage and thus expan network faster.  

# Motivation
[motivation]: #motivation

The motivation is so that early adopters/users who supported the network in a particular area early on dont see diminishing returns on their rewards as more and more people install hotspots in the same area. It will make the hotspot owners also spend a few mintues to determine the value of installing a hotspot at a location and will hopefully cause a shift in hotspot supply going more towards areas that are undercovered or lack coverage. There is no reason a hex needs to have 45 hotspots in it.

# Stakeholders
[stakeholders]: #stakeholders

* Who is affected by this HIP? All spotpot owners will be affected.

* How are we soliciting feedback on this HIP from these stakeholders? Note that
  they may not be watching the HIPs repository or even aren't directly active in
  the Helium Community Slack channels.

# Detailed Explanation
[detailed-explanation]: #detailed-explanation

- Introduce and explain new concepts.

- It should be reasonably clear how the proposal would be implemented.

- Provide representative examples that show how this proposal would be commonly
  used.

- Corner cases should be dissected by example.

# Drawbacks
[drawbacks]: #drawbacks

- Why should we *not* do this?

# Rationale and Alternatives
[alternatives]: #rationale-and-alternatives

This is your chance to discuss your proposal in the context of the whole design
space. This is probably the most important section!

- Why is this design the best in the space of possible designs?

- What other designs have been considered and what is the rationale for not
  choosing them?

- What is the impact of not doing this?

# Unresolved Questions
[unresolved]: #unresolved-questions

- What parts of the design do you expect to resolve through the HIP process
  before this gets merged?

- What parts of the design do you expect to resolve through the implementation
  of this feature?

- What related issues do you consider out of scope for this HIP that could be
  addressed in the future independently of the solution that comes out of this
  HIP?

# Deployment Impact
[deployment-impact]: #deployment-impact

Describe how this design will be deployed and any potential impact it may have on
current users of this project.

- How will current users be impacted?

- How will existing documentation/knowlegebase need to be supported?

- Is this backwards compatible?

        - If not, what is the procedure to migrate?

# Success Metrics
[success-metrics]: #success-metrics

What metrics can be used to measure the success of this design?

- What should we measure to prove a performance increase?

- What should we measure to prove an improvement in stability?

- What should we measure to prove a reduction in complexity?

- What should we measure to prove an acceptance of this by it's users?
