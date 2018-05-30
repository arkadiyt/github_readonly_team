# github_readonly_team

### What's it for

Right now if you want to invite a 3rd party to have read-only access to your organization's code on Github the only way to do it is to create a new team and manually add all of your repositories to that team with read-only access.

This script automates this, by accepting an organization and team name as input and giving that team read-only permissions for all repositories in the organization.

### Usage

```
# Install dependencies, only needed once
$ bundle

# Run script
$ GITHUB_API_TOKEN='<GITHUB_API_TOKEN>' ./create <organization_name> <team_name>
```
