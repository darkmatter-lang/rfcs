# RFC policy - language design

Pretty much every change to the language needs an RFC. Note that new
lints (or major changes to an existing lint) are considered changes to
the language.


## Amendments

Sometimes in the implementation of an RFC, changes are required. In general
these don't require an RFC as long as they are very minor and in the spirit of
the accepted RFC (essentially bug fixes). In this case implementers should
submit an RFC PR which amends the accepted RFC with the new details. Although
the RFC repository is not intended as a reference manual, it is preferred that
RFCs do reflect what was actually implemented. Amendment RFCs will go through
the same process as regular RFCs, but should be less controversial and thus
should move more quickly.

When a change is more dramatic, it is better to create a new RFC. The RFC should
be standalone and reference the original, rather than modifying the existing
RFC. You should add a comment to the original RFC with referencing the new RFC
as part of the PR.

Obviously there is some scope for judgment here. As a guideline, if a change
affects more than one part of the RFC (i.e., is a non-local change), affects the
applicability of the RFC to its motivating use cases, or there are multiple
possible new solutions, then the feature is probably not 'minor' and should get
a new RFC.
