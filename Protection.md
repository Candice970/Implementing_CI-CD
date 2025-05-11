# Branch Protection Rules Justification

To maintain high-quality code and prevent issues in production, the following branch protection rules are applied to the `main` branch:

1. **Require Pull Request Reviews:**  
   At least one review is required to ensure peer validation before merging changes. This avoids bugs and enforces accountability.

2. **Require Status Checks:**  
   All CI tests must pass before merging. This ensures that broken code is not introduced into the `main` branch.

3. **Disable Direct Pushes:**  
   All changes must go through pull requests. This supports traceability, review, and testing enforcement.

These rules help us adopt industry best practices and maintain a robust codebase.
