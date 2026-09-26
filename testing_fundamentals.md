# Concept: Testing vs. Debugging

## Definition
Testing and debugging are separate activities. Testing is the activity of triggering failures or finding defects, while debugging is the process of finding the causes of those failures (defects) and eliminating them.

## Key Characteristics
* Testing evaluates the software and identifies that a problem exists.
* Debugging is typically done by developers to diagnose and fix the root cause.
* Confirmation testing is required after debugging to ensure the fix resolved the problem.

## Real-World Application
As a QA tester, I run a test case that causes the login page to crash (Testing). The developer analyzes the code, finds a logic error, and rewrites the function (Debugging). I then rerun the exact same test to verify it works (Confirmation Testing).