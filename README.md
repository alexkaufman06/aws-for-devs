# AWS for Devs

This is documentation of my learnings from from the Linkedin course on [AWS for Developers](https://www.linkedin.com/learning/learning-amazon-web-services-aws-for-developers-2).

## Identity and Access Management (IAM)

New accounts come with a root level user that has permissions to do everything including deleting the account.
  * It is best practice to another user and give that user permissions for administration access but it will not be able to delete the account
  * Users get `permissions` through `policies` that are attached to a user
    * You can create `policies` in bulk by using groups
  * `Services` have `roles` and a `user` has `permissions` for determining their access
    * `Roles` have `policies` just like `permissions`
