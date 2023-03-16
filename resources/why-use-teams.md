# Why are GitHub teams used to provide access to repos?

This section will use "_project team_" and "_GitHub team_"
to mean two similar but different things.
A project team is a set of people working on a project,
and a GitHub team is a set of GitHub user accounts.
The rest of this section explains how they are similar but also different,
as well as how GitHub teams are used on the DIME account.

## Admin access are not given to project members

The default is that DIME Analytics does not
give project team members admin access to the repos.
This is due to two reasons.
First, admin access gives users access to "_destructive features_"
(for example permanently delete a repo)
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

## Best practice for GitHub teams

It is possible to have 1-to-1 relations
between project team, repo and GitHub team,
but it is not the best or most efficient usage of GitHub teams.
When a single project team has multiple repos,
then they should always use the a single GitHub team for all those repos.
And, what is even better and even less work is that, when possible,
several project teams share a single GitHub team for all their repos.
Several DIME project portfolios,
for example ieConnect, DeJure, DIME Analytics etc.,
use a single team for all repos for all project teams in that portfolio.
This does indeed mean that some users will have access
to some repos they do not strictly need access to.
However, this has never caused any issues.
On the contrary, it makes collaboration across projects easier,
and it does not require coordination between maintainers of many small teams.

## How to be a team maintainer

Users are added and removed from the team on the member tab
of the team's page on the DIME account.
Team maintainers can only add user that have already
[requested and joined](#request-to-join-the-dime-account) the DIME account.
External collaborators can not be added to GitHub teams.
Instead, their DIME contact must
[request](#request-external-collaborator-access-to-a-repo-on-the-dime-account)
that DIME Analytics gives them access
by adding them directly to each repo they need access to.

## List of all teams used on the DIME account

If you are a member of the DIME account already,
then you can see a list of reports for each team
[here](https://github.com/dime-worldbank/dime-account-admin-private/tree/main/reports/team-reports).
In these reports you can see who is a maintainer for that team
(i.e. who can add you to that team)
and which repos this team is used for.
These reports are updated on a weekly basis.
