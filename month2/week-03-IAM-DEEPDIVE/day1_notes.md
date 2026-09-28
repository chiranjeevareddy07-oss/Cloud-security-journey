 Day 1 – Users, Groups, Roles

- User: A permanent identity for one person or app, like an employee. Has its own password or access keys.
- Group: A collection of users. Permissions attached to the group apply to everyone in it. A group has no login.
- Role: A set of permissions that a person or service *assumes* temporarily. No permanent password or keys. Credentials expire automatically.

### Why this matters for security
- Groups: permissions are managed in one place instead of per user, so fewer mistakes and easier changes when someone's job changes.
- Roles: no long-lived credentials to steal. If they leak, they expire.
