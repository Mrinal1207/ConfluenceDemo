# Test app for Confluence4 from Ericsson Testing SMS

This is a quick app cobbled together for the purposes of demonstrating a basic CI/CD workflow with Docker Hub on using Amazon Cloud.
All the Open Source Tools used. Hence the cost is Zero.

## Instructions for use

1. Prepare all Code Files.
2. Move code files from Local to GitHub (using GitBash or DesktopGit).
3. Initializing a Git repo and making a remote of it on GitHub.
4. Need to have account on - GitHUb, CircleCI, Docker Hub, Tutum and AWS.
5. Trigger Token = bf3de517-ca11-4d39-9a0a-99361ba3652e
6. Trigger URL = https://registry.hub.docker.com/u/mrinal1207/confluencedemo/trigger/bf3de517-ca11-4d39-9a0a-99361ba3652e/
7. Curl Site = curl -H "Content-Type: application/json" --data '{"build":true}' -X POST 
8. Redirect URL - https://cloud.docker.com/api/app/v1/service/95afbf42-86d2-4673-a0a5-25db117aa42b/trigger/415e533f-a1b8-49a5-8771-432131d08e55/call/
