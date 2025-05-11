# Implementing_CI-CD
## Running Tests Locally
Ensure dependencies are installed:
```bash
pip install -r requirements.txt


CI: Automatically runs tests on every push and pull request to main.

CD: Builds and uploads Python package as artifact on every successful merge to main.

Pull requests are blocked if tests fail.
