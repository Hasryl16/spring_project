# TODO: Fix Workflow Stuck at Clean Docker Resources

- [x] Update .github/workflows/ci-cd.yml: Modify "Clean Docker resources" step to use non-sudo method for killing processes on port 8080 and add timeout to docker compose down
- [x] Update .github/workflows/ci-cd.yml: Change health check to directly check app on port 8080 instead of via Nginx

Followup: Test the workflow to ensure the "Clean Docker resources" step no longer hangs.
