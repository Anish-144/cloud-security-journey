# AWS IAM Policies

## What I did:

- Learned IAM policy structure (JSON)
- Attached AWS managed policy to user
- Tested access using IAM user login
- Created custom policy
- Attached custom policy to user
- Verified permissions (allowed & denied actions)

---

## Key Learnings:

- IAM policies define permissions in AWS
- Policies follow Effect, Action, Resource format
- AWS managed policies are broad and not always secure
- Custom policies are best for real-world security
- Principle of least privilege is critical
- Explicit deny overrides allow
- Permissions must be explicitly defined

---

## Hands-on Summary:

- Attached `AmazonS3ReadOnlyAccess`
- Verified:
  - Can view S3 buckets ✅
  - Cannot upload objects ❌
- Created custom policy for limited access
- Tested policy behavior

---

## Mistakes to Avoid:

- Giving `AdministratorAccess` unnecessarily
- Overusing AWS managed policies
- Not testing permissions after attaching policies

---

