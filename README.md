# Principles
A Statement of Ethics and Principles for the Dukkhaless project.

If something seems to be missing, please create a pull request as a proposal.


## Inviolable Limits

- No third party javascript that is not part of the application shall ever be served to the user.
  - Example: This means no external tools for data collection.
- No embedded content from third parties will ever be served to the user.
- A user will never be required to pay to use the application for their own health and wellbeing.
- No personal information about users will ever be collected in a way that the application maintainers or anyone but the user themselves has access to.
- Metadata about user activities will be limited to the bare minimum to provide a useful service. At the time of writing this, this means the following:
  - Time a document was initially created
  - Time when a document was most recently changed
- All user data except their public key and username and the afforementioned minimum metadata must be hashed or encrypted to ensure user privacy.


## More Abstract Guiding Principles

- The application should not have behaviours that contribute to user anxiety or other struggles, such as performing more push notifications than are requested.
- The application should emphasise ease of use as much as possible to reduce barriers to entry and reduce anxiety during its use.
