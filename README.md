# AdvCol

This repository contains a proof-of-concept implementation of a web service 
for organizing and authoring adversarial collaborations. Its design is 
experimental; it has yet to be tested.

## Adversarial collaborations

An adversarial collaboration is a collaborative effort by two individuals who 
disagree over a proposition, to attempt to reach an agreement, and to
document the process of coming to that agreement. Short of reaching an 
agreement, they may also produce insight into the nature of their
disagreement. It is related to
[Double Crux](http://rationality.org/resources/updates/2016/double-crux).

## Design

Users can submit to and vote on a public list of propositions, which will be 
sorted based on some function of number of upvotes, number of downvotes, and 
number of active ongoing collaborations on the topic. Users can indicate 
their credence in the proposition, and a matchmaking algorithm will pair 
individuals who disagree. Once the two adversaries have agreed to collaborate,
a referee will be assigned to manage their correspondence. Referees are 
volunteers selected by the site administrators on the basis of a demonstrated 
ability for and commitment to the facilitation of collaborative disagreement.

Collaboration happens in private until the collaborators choose to publish. 
The referee acts as a proxy through which the adversaries communicate. Once 
the adversaries have agreed to collaborate and the referee has been assigned, 
the referee will compose a greeting to the adversaries for the purpose of 
initiating the dialog an drawing attention to any potential pitfalls the 
adversaries should be aware of (concerns about the proposition, the 
similarity or lack thereof of the adversaries intellectual backgrounds, etc.)
The referee will ask the collaborators to describe in detail their attitudes 
toward the proposition, and to identify the cruxes of their belief that the 
proposition is true/false. Adversaries will then compose responses, which 
will be sent to the referee for review. The referee can either choose to 
approve the correspondence, in which case it is sent to the other adversary, 
or comment on the correspondence, returning it to the sender for revision. 
The referee's role is purely to enforce norms of discourse and encourage
[scout mindset](https://www.ted.com/talks/julia_galef_why_you_think_you_re_right_even_if_you_re_wrong/up-next).
They should not involve themselves in the substance of the discussion.

After identifying shared cruxes, the adversaries can elect to shift their 
focus to a particular crux, in which case the process described for the 
original proposition will be repeated for the shared crux. Once at least one 
shared crux has been found, the adversaries can choose to publish their 
collaboration, which requires the approval of the referee.

## Possible future alterations

### Financial incentive

Since a successful collaboration requires the adversaries to both commit to a 
potentially lengthy process, it might be necessary to require adversaries to 
make a financial investment in their collaboration. One possibility: 
adversaries must pay $x to begin a collaboration, and will have their 
investment refunded when they successfully publish.

Along the same lines, the site could also support competitions, where users 
can sponsor propositions by offering a bounty for successful collaborations 
submitted before a deadline. The $x×2 from failed entries into the 
competition could be distributed between all successful entries, while the 
bounty is paid out as determined by the sponsor.
