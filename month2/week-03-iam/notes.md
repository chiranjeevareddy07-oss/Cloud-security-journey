## Day 2 – Groups (Hands-On)

### What I did
- Created a group called `readers`
- Added `test-user` to the `readers` group
- Attached the S3 read-only policy to the group instead of the user directly
- Verified with list-groups-for-user and list-attached-group-policies

### What I learned
- When a policy is attached to a group, every user inside that group automatically gets that access — you don't attach it to each person one by one
- This is why companies use groups: manage permissions in one place instead of repeating the same policy across many users
- If someone's role changes, you move them to a different group instead of editing individual policies

### Why this matters for security
- Fewer places for permissions to go wrong = easier to audit and less chance of mistakes
