# Shared Protocol Buffers Contracts

This repository holds protocol buffers (`.proto`) files for every service that we have.
Each proto file must not be copied into the repository that is using it. Instead, you
should use [Git submodule](https://www.atlassian.com/git/tutorials/git-submodule).
That way, the proto files can be tracked and versioned over time.

If you don't know what protocol buffers are, you can visit this link:
https://developers.google.com/protocol-buffers/

The way this repository works is simple, just create a PR of new proto file,
if the proto file for that service does not exist. Both frontend and backend
team will be notified to review the PR.
