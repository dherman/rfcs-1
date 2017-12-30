- Feature Name: zero_config_deployment
- Start Date: 2017-12-29
- RFC PR: 
- Neon Issue: 

# Summary
[summary]: #summary

This RFC proposes a deployment flow that requires as close to zero configuration and setup as possible, allowing developers to build and publish binaries of their Neon libraries once per release and have them work across multiple versions of Node.

# Motivation
[motivation]: #motivation

Neon should have two primary goals for the deployment workflow:

- **Easy setup:** The experience of getting started with Neon or a new Neon project should require as little setup as possible--ideally none.
- **Easy maintenance:** Publishing a Neon library shouldn't require tracking new releases of Node and rebuilding and republishing new releases for each Node release.

This RFC takes the approach 

# Guide-level explanation
[guide-level-explanation]: #guide-level-explanation

Explain the proposal as if it were already included in Neon and you were teaching it to another programmer. That generally means:

- Introducing new named concepts.
- Explaining the feature largely in terms of examples.
- Explaining how programmers should _think_ about the feature, and how it should impact the way they use Neon. It should explain the impact as concretely as possible.
- If applicable, describe the differences between teaching this to existing Rust programmers and new Rust programmers.

# Reference-level explanation
[reference-level-explanation]: #reference-level-explanation

This is the technical portion of the RFC. Explain the design in sufficient detail that:

- Its interaction with other features is clear.
- It is reasonably clear how the feature would be implemented.
- Corner cases are dissected by example.

This section should return to the examples given in the previous section, and explain more fully how the detailed proposal makes those examples work.

# Drawbacks
[drawbacks]: #drawbacks

Why should we _not_ do this?

# Rationale and alternatives
[alternatives]: #alternatives

- Why is this design the best in the space of possible designs?
- What other designs have been considered and what is the rationale for not choosing them?
- What is the impact of not doing this?

# Unresolved questions
[unresolved]: #unresolved-questions

- What parts of the design do you expect to resolve through the RFC process before this gets merged?
- What parts of the design do you expect to resolve through the implementation of this feature before stabilization?
- What related issues do you consider out of scope for this RFC that could be addressed in the future independently of the solution that comes out of this RFC?
