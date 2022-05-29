# AIP 1: Correct 18.5B Max Supply

- Author(s): @theauthtoken
- Start Date: 2022-05-27
- Category: tokenomics
- Tracking Issue: TBD
- Status: In Discussion

# Summary
[summary]: #summary

When the pre-minted supply of AUTH was created there was a bug in the code that minted
the total supply, yielding a supply of 18,446,744,073.709553 instead of 18.5B. The goal
of this AUTH Improvement Proposal is to correct the total supply to a clean round
number that is easy to reference and discuss with both the community as well as new
vendors joining the AUTH ecosystem.

# Drawbacks
[drawbacks]: #drawbacks

* Fixed calculations in any systems, code, and third-party tools that reference the old supply will need to be updated.

* Any vendors that set a non-binding floor price for AUTH will may need to adjust their floors.

# Rationale and Alternatives
[alternatives]: #rationale-and-alternatives

This is important as new vendors are onboarded and have to explain the rational
behind the total supply being a strange number, vs 18.5B.

This should be done as early as possible in the lifecycle of the community as these
kinds of changes only become harder and harder once AUTH becomes used by more
vendors, third party tools, etc.

# Success Metrics
[success-metrics]: #success-metrics

Success is simple: the total supply becomes 18,500,000,000,000.00
