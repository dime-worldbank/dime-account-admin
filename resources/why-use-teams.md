# GitHub Teams

This section will use "_project team_" and "_GitHub team_" to mean two similar but different things. A project team is a set of people working on a project, and a GitHub team is a set of GitHub user accounts. The rest of this section explains how they are similar but also different, as well as how GitHub teams are used on the DIME account.

# Why are GitHub teams used to provide access to repos?

GitHub Teams provide repository access management for users who are not organization account admins (Analytics). Each repository has at least one team assigned, and the team maintainer can grant or revoke access by adding or removing users from the team. The Analytics team is always happy to help with user management, but to reduce emails and waiting times, we recommend project teams use GitHub Teams to manage access directly.

## Admin access are not given to project members

The default is that DIME Analytics does not give project team members admin access to the repos. 
This is due to two reasons. 
First, admin access gives users access to "_destructive features_" (for example permanently delete a repo)
the account admins in DIME Analytics cannot undo.
Second, admin access gives users access to features that can incur a cost.
Since all costs incurred on the DIME account are charged to DIME Analytics,
any such action should go through DIME Analytics.

## GitHub teams solves repo access management without admin access

The drawback, however, of not giving admin access is that
no one in the project team is able to give and revoke direct access to repos
as members join and leave the project.
This is exactly what _GitHub teams_ provide a solution to.
The account admins in DIME Analytics create a GitHub team and
give access for that team to one or several repos,
which in turn gives users added to that team access to those repos.
Then one or several members of the project team
are made maintainers of the GitHub team,
which allows them to add and remove users from that team.
This way, the project team can indirectly
give and revoke access to repos for project team members,
without having to ask the account admins in DIME Analytics each time.

## How Many Repos for How Many Teams?

GitHub supports any one-to-one, many-to-one, or one-to-many relationships between repositories and GitHub teams. If the project team has a preference, Analytics can set up any combination of GitHub teams and repositories.

However, a general best practice—and what Analytics has seen work well for many project teams—is to have a single GitHub team for a portfolio of repositories. While this might give some users access to some repositories they do not strictly need, it makes team management much easier. If a new person joins the project team, adding them to a single GitHub team gives them access to all repositories they might need now and in the future.

It is also easier for project teams to remember which GitHub team is used for their repositories if a single large team is used.

Some examples of GitHub teams organized according to this practice are:

- [taxation-team](https://github.com/orgs/dime-worldbank/teams/taxation-team/repositories)
- [ieconnect](https://github.com/orgs/dime-worldbank/teams/ieconnect/repositories)
- [bureaucracy-lab](https://github.com/orgs/dime-worldbank/teams/bureaucracy-lab/repositories)
- [dime-wfp-team](https://github.com/orgs/dime-worldbank/teams/dime-wfp-team/repositories)

These teams are listed as examples of this organization style. More examples exist and this list is not intended to list the "best" teams. These teams also show some differences in who is made maintainer and how many maintainers each team has.

## Who should be maintainer?

There is no technical requirement for this. A general rule of thumb is that the most junior person who has an overview of the full portfolio is a good option for a team maintainer. This could be several people sharing the role. It is a good idea to have redundancy, and for this, a more senior member could be a good fit. Ultimately, this is up to the team, and many different practices work well.

There is no technical limitation to make everyone team maintainers; however, this tends to make it ambiguous who is responsible for adding and removing users as project team members join or leave. Another reason for limiting maintainers is that Analytics will occasionally contact the maintainers if there is a question related to the GitHub team or the repositories the team manages.

In addition to adding and removing members, a maintainer can also elevate any member of the team to maintainer status. All these actions are done on the team's Members page. See below for how to find this page.

## How to be a team maintainer

Users are added and removed from the team on the member tab
of the team's page on the DIME account.
Team maintainers can only add users that have already
[requested and joined](#request-to-join-the-dime-account) the DIME account.
External collaborators cannot be added to GitHub teams.
Instead, their DIME contact must
[request](#request-external-collaborator-access-to-a-repo-on-the-dime-account)
that DIME Analytics gives them access
by adding them directly to each repo they need access to.

## Where can I see what team is used for my repo and who is the maintainer?

Unfortunately, GitHub only gives organization account admins access to the overview of which teams are used for a specific repository. However, Analytics uses its admin access to generate reports that make this information available to all members of the DIME account. 

There are both [repo reports](https://github.com/dime-worldbank/dime-account-admin-private/tree/main/reports/repo-reports) and [team reports](https://github.com/dime-worldbank/dime-account-admin-private/tree/main/reports/team-reports) for all repositories and teams. These reports are only updated once per week and may therefore not reflect recent changes. To view these reports you already need to be a member of the DIME account.

In the team reports you can see who is members of a team and which of those member also is a maintainer for the team
(i.e. who can add you to that team). The team report links to the Member page for that team, where the team maintainers can perform all their tasks.

## What team actions still require the Analytics team's manual input

Most regular tasks can be done by the team maintainer without waiting for Analytics, but here are some tasks where the team needs to reach out to Analytics at dimeanalytics@worldbank.org:

- Change the name of a team
- Change which repositories a team has access to
- Merge two or more teams into a bigger team
- Assign a new maintainer if previous maintainers have lost access, left the WB, etc.

Analytics is always happy to help with any regular tasks the maintainer can otherwise do themselves.
