# 🏆 Domain 6 Boss Fight — Privacy, Security & Administration

> Score 10/12 or higher to defeat this boss! Honor system 🎖️
> Write your answers, then check against the key at the bottom.

---

### Q1. What is two-factor authentication (2FA) on GitHub?
- A) Using two different passwords
- B) An extra layer of security requiring a second verification method (like TOTP or a security key) in addition to your password
- C) Having two GitHub accounts
- D) Requiring two approvals on pull requests

### Q2. What are the three visibility levels for repositories on GitHub?
- A) Open, Closed, Archived
- B) Public, Internal, Private
- C) Free, Team, Enterprise
- D) Read, Write, Admin

### Q3. Which repository role allows a user to push to non-protected branches but NOT manage settings?
- A) Read
- B) Triage
- C) Write
- D) Maintain

### Q4. What do branch protection rules allow you to enforce?
- A) Automatic code formatting
- B) Requirements like required reviews, status checks, and restrictions on who can push to specific branches
- C) Repository deletion prevention only
- D) Automatic dependency updates

### Q5. What does Dependabot do?
- A) Reviews pull requests for code quality
- B) Monitors dependencies for known vulnerabilities and can automatically open PRs to update them
- C) Manages team permissions
- D) Enforces branch naming conventions

### Q6. What is GitHub code scanning?
- A) A tool that scans for large files
- B) An automated security feature that analyzes code for vulnerabilities and coding errors using tools like CodeQL
- C) A spell-checker for documentation
- D) A service that checks for license compliance

### Q7. What does GitHub secret scanning detect?
- A) Hidden files in a repository
- B) Accidentally committed secrets like API keys, tokens, and passwords in repository content
- C) Private repositories that should be public
- D) Unused branches

### Q8. What is the role of an organization owner on GitHub?
- A) They can only view repositories
- B) They have full administrative control including managing members, teams, settings, billing, and security policies
- C) They can only create repositories
- D) They can only manage billing

### Q9. What are audit logs used for in GitHub organizations?
- A) Tracking code quality metrics
- B) Reviewing actions performed by members such as permission changes, repository access, and security events
- C) Logging Git commit messages
- D) Monitoring CI/CD pipeline performance

### Q10. What is SAML single sign-on (SSO) in the context of GitHub?
- A) A way to sign in with two passwords
- B) An authentication method that allows organizations to manage access through their identity provider, centralizing authentication
- C) A type of branch protection rule
- D) A GitHub Actions trigger

### Q11. What are passkeys on GitHub?
- A) Temporary access tokens
- B) A passwordless authentication method using biometrics or device PINs that serve as both a password and 2FA method
- C) SSH keys stored in the cloud
- D) Organization invitation codes

### Q12. How does adding an SSH key to your GitHub account improve security?
- A) It encrypts all repository contents
- B) It enables authenticated, encrypted communication with GitHub without sending your password over the network
- C) It automatically enables 2FA
- D) It makes your repositories private

---

<details>
<summary>🔑 Answer Key (click to reveal)</summary>

| Q | Answer | Explanation |
|---|--------|-------------|
| 1 | B | 2FA adds a second verification step (TOTP app, SMS, or security key) beyond your password |
| 2 | B | Public repos are visible to everyone; Internal repos are visible within an enterprise; Private repos are restricted to granted users |
| 3 | C | The Write role can push code and manage issues but cannot change repository settings |
| 4 | B | Branch protection rules enforce review requirements, status checks, and push restrictions |
| 5 | B | Dependabot alerts you to vulnerable dependencies and can auto-create PRs with version updates |
| 6 | B | Code scanning uses static analysis (e.g., CodeQL) to find security vulnerabilities in your code |
| 7 | B | Secret scanning detects committed credentials like tokens, keys, and passwords |
| 8 | B | Organization owners have complete administrative access to all org settings and resources |
| 9 | B | Audit logs record org-level events — member changes, permission updates, and security actions |
| 10 | B | SAML SSO lets orgs enforce authentication through an external identity provider like Entra ID or Okta |
| 11 | B | Passkeys use device biometrics/PINs for passwordless sign-in and count as both password and 2FA |
| 12 | B | SSH keys authenticate via public-key cryptography, avoiding password transmission |

**Pass mark: 10/12 (83%)**

</details>
