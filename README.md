# DIME GitHub Resources

This repo includes instructions for access and management
for DIME's repos hosted on GitHub.
For general GitHub resources see [here](https://osf.io/e54gy/).

## Table of Content

* [Why does DIME use both a DIME account and a WB account?](#why-does-dime-use-both-a-dime-account-and-a-wb-account)
* [Why do we use GitHub teams to provide access to repos?](#why-does-dime-use-both-a-dime-account-and-a-wb-account)
* [Access to DIME repos](#actions-for-the-dime-account)
* [DIME GitHub Training Slides](#dime-github-training-slides)

## Why does DIME use both a DIME account and a WB account?

Initially there was just the WB account (https://github.com/worldbank).
Eventually, DIME projects used almost half of the quota
of the WB account subscription,
making it difficult for other teams to use the WB account.
Therefore DIME Analytics ended up
creating its own account (https://github.com/dime-worldbank).

Today, most DIME repos has been moved to the DIME account,
and it should be the default location for all new repos.
Private repos should be created on the DIME account.
It is the least amount of work for everyone involved if public repos
are also created on the DIME account,
but if the team has a preference to create them on the WB account,
then that is a possibility.
The repos created on the WB account in the past that are still on that account,
are public repos for which the URL had already been widely published.
For example, repos with open source tools or reproducibility packages.

The one exception when private repos can be created on the WB account
is if the project is a collaboration with non-DIME WB teams.
DIME Analytics pays a small fee for each month for each user
on private repos on the DIME account.
In cases where there are about as many non-DIME WB users as DIME users,
then it is more appropriate that the repo
sits on the WB account using the WB subscription.

## Why are GitHub teams used to provide access to repos?

This section will use "_project team_" and "_GitHub team_"
to mean two similar but different things.
A project team is a set of people working on a project,
and a GitHub team is a set of GitHub user accounts.
They are sometimes similar but not always.

The default is that DIME Analytics does not
give project team members admin access to the repos.
Admin access gives access to features that can permanently delete content.
Without admin access, users do not have access to any feature that
the account admins in DIME Analytics cannot undo.
Another reason is that admin access gives access
to features that can incur a cost.
Since all costs incurred on the DIME account are charged to DIME Analytics,
any such action should go though one on the account admins in DIME Analytics.

The drawback, however, of not giving anyone in the project team
admin access to the repo is that no one in the project team has access to
give and revoke direct access to repos
as members join and leave the project team.
This is exactly what GitHub teams provide a solution to.
The account admins in DIME Analytics can create a GitHub team and
give access for that team to one or several repos
which in turn gives access to those repos for anyone added to that team.
Then one or several members of the project team
are made maintainers of the GitHub team,
which allows to add and remove users from that team.
This way the project team can give access to their repos to new members
without having to ask the account admins in DIME Analytics each time.

It is possible to have a 1-to-1 relation
between project team, repo and GitHub team,
but it is not the best and most efficient usage of GitHub teams.
When a single project team has multiple repos,
then they should always use the a single GitHub team for those repos.
What is even better and less work is that, when possible,
several project team share a single GitHub team for all their repos.
For example, several DIME project portfolios, for example ieConnect, DeJure,
use a single team for all repos for all project teams in that portfolio.
This does indeed mean that a some users will have access
to some repos they do not strictly need access to.
However, this has never caused any issues.
On the contrary, it makes collaboration across projects easier,
and it does not require coordination between maintainers of many small teams.

Team maintainers can only add user that have already
[requested and joined](#actions-for-the-dime-account) the DIME account.
External collaborators can not be added to GitHub teams.
Instead, their DIME contact must [request](#actions-for-the-dime-account)
that DIME Analytics gives them access
by adding them directly to each repo they need access to.
DIME Analytics pays a small monthly fee for each external collaborator,
so the DIME teams are asked to only request access to external users
who really need access to the repo.
## Actions for the DIME account

These actions only applies to repos with and URL starting with: https://github.com/dime-worldbank.
See section below if this does not apply to your team's repo.

Click the following links below to access instructions for how to request actions for the DIME GitHub account. You have to already be a member of the DIME GitHub account (and be logged in to GitHub.com) to access the links that say "(member access only)".

* [Request to be added to the DIME GitHub account](https://github.com/dime-worldbank/dime-account-admin/blob/main/instructions/request-access-dime-org.md)
* [Request to create a new repository on DIME GitHub account](https://github.com/dime-worldbank/dime-account-admin-private/blob/main/instructions/request-new-repo-dime-org.md) - only member access (see below)
* [Request to add an external collaborator to a single repo on DIME GitHub account](https://github.com/dime-worldbank/dime-account-admin-private/blob/main/instructions/add-external-collaborator-dime-org.md) - only member access (see below)

**(Only member access)** - Links with this note can only be accessed by users who are already members of the DIME GitHub account. 
See instructions above if you are not a member and you are eligible to request to be added. 
Make sure you are logged in to GitHub.com before trying to access links with only member access. 
If it says `Sign up`/`Sign in` in the header above you are not signed in in the browser you are currently using. 
If you are not sure which account you are logged in to, 
then see the menu that pops up when you click your profile picture furthest to the right in the header. 
If nothing of this solves your access, you may reach out to dimeanalytics@worldbank.org.

## Actions for the WB account

These actions only applies to repos with and URL starting with: https://github.com/worldbank
See section above if this does not apply to your team's repo.

Click the link below for instructions related to the WB account:

* Use this [eServices request](https://worldbankgroup.service-now.com/wbg?id=wbg_sc_catalog&sys_id=910e1739db1a54903c5960ab13961912) (WB Intranet) if you are on a WB contract and want to request to be added to the WB GitHub account
* [All other requests related to the WB GitHub account](https://github.com/dime-worldbank/dime-account-admin-private/blob/main/instructions/wb-github-account.md)  - only member access (see below)

**(Only member access)** - Links with this note can only be accessed by users who are already members of the DIME GitHub account. 
See instructions above if you are not a member and you are eligible to request to be added. 
Make sure you are logged in to GitHub.com before trying to access links with only member access. 
If it says `Sign up`/`Sign in` in the header above you are not signed in in the browser you are currently using. 
If you are not sure which account you are logged in to, 
then see the menu that pops up when you click your profile picture furthest to the right in the header. 
If nothing of this solves your access, you may reach out to dimeanalytics@worldbank.org.

## Why does DIME use both a DIME account and a WB account?

In the beginning there was just the WB account (https://github.com/worldbank).
Eventually, DIME projects used almost half of the quotas of the WB account subscription,
so DIME ended up creating its own account (https://github.com/dime-worldbank).
The default is that all private DIME repositories should be created at the DIME Account
but it is up to the team where a public repository should be created.

On one hand it is easier for teams to have both
private and public repositories on the same account
as managing user access is easier.
But on the other hand it is sometimes desirable to put public repositories
on the WB account as it gets more traffic.
A common way how DIME teams deal with this
is to use a private repository on the DIME account before publishing results,
and use a public repo on the WB account for replication packages
after the research is published.
But exactly how to do this is ultimately up to each team.

We can make exceptions and create private repos on the WB account if,
for example, the project is a collaboration with non-DIME WB teams.
You may invite external collaborators to repos hosted on the DIME Account.
However, DIME Analytics pays a small fee for each user
(including external collaborators) so we ask you to only request that for
non-DIME users that need active access to the repo.

## DIME GitHub Training Slides

Some of these slides are for trainings that are meant to be interactive and might therefore not be optimal for self learning. But we are still happy to share these slides and hope that you will find them useful. The source code for these slides can be found [here](https://github.com/worldbank/dime-github-trainings/tree/main/GitHub-trainings).

* [Intro to Git/GitHub - Observer](https://osf.io/a2htb/) - How to use GitHub to browse code and to provide feedback on code.
* [Intro to Git/GitHub - Contributor](https://osf.io/2mz4j/) - How to use GitHub to collaborate on code.
* [GitHub Team Maintainer Training](https://osf.io/arpyc/) - Intro to GitHub's Team feature that we use to allow the project teams to be able togrant and revoke access to the project teams' repositories.
