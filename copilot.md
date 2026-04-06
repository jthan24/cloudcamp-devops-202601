# Instructions to Create a Good Merge Request (MR)

## 1. Clear Title
Summarize what the MR does in a brief, descriptive title.

## 2. Detailed Description
- Explain the reason for the changes.
- List main tasks or features included.
- Mention any issues fixed (use `closes #issue_number` if applicable).

## 3. Clean Commits
Squash or organize commits to make the history easy to follow.

## 4. Self-review
Check your code and add comments to guide reviewers if needed.

## 5. Testing
- List steps for how reviewers can test your changes.
- Mention any tests added or documentation updated.

## 6. Minimal Scope
Limit the MR to a single purpose or feature. Split unrelated changes into separate MRs.

## 7. Request Reviewers
Tag teammates or maintainers for review.

## 8. Follow Project Guidelines
Ensure you follow coding/style guidelines for the repository.

---

## Example MR Template

**Title:** `:sparkles: Add user authentication system`

**Description:**
This MR implements a user authentication system with the following features:
- User registration with email validation
- Login with JWT tokens
- Password reset functionality
- Tests added for all authentication flows

**How to test:**
1. Create a new user account using the /register endpoint
2. Log in with the credentials
3. Verify JWT token is returned
4. Test password reset flow

Closes #42