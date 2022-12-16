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

#### Admin access are not given to project members

The default is that DIME Analytics does not
give project team members admin access to the repos.
Admin access gives access to features that can permanently delete content.
Without admin access, users do not have access to any feature that
the account admins in DIME Analytics cannot undo.
Another reason is that admin access gives access
to features that can incur a cost.
Since all costs incurred on the DIME account are charged to DIME Analytics,
any such action should go though one on the account admins in DIME Analytics.

#### GitHub teams solves repo access management without admin access

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

#### Best practice for GitHub teams

It is possible to have a 1-to-1 relation
between project team, repo and GitHub team,
but it is not the best and most efficient usage of GitHub teams.
When a single project team has multiple repos,
then they should always use the a single GitHub team for those repos.
What is even better and less work is that, when possible,
several project team share a single GitHub team for all their repos.
For example, several DIME project portfolios, for example ieConnect, DeJure,
use a single team for all repos for all project teams in that portfolio.
This does indeed mean that some users will have access
to some repos they do not strictly need access to.
However, this has never caused any issues.
On the contrary, it makes collaboration across projects easier,
and it does not require coordination between maintainers of many small teams.

#### How to be a team maintainer

Users are added and removed from the member tab
on the team's page on the DIME account.
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

These instructions only applies to repos hosted on the DIME account.
Most DIME repos are hosted on the DIME account but not all
([read more here](#why-does-dime-use-both-the-dime-account-and-the-wb-account)).
You can know if your repo is hosted on the DIME account by checking
if your repo has `dime-worldbank` in its URL.
For example: https://github.com/dime-worldbank/dime-account-admin.
(If your repo says only `worldbank` instead of `dime-worldbank` then use
[these instructions](#actions-for-the-wb-account).

#### Request to join the DIME account

This request is open to you if you are mapped to any of the DIME units.
You may also use this request if even if you are not mapped to a DIME unit if
you work for extensively on a DIME project with a DIME TTL,
that project has a repo on the DIME account,
and you have a World Bank email.
If you are not sure if this applies to you, then talk to your DIME supervisor.
If you do not have a World Bank email, then ask your DIME contact to request
[external collaborator access](#request-external-collaborator-access-to-a-repo-on-the-dime-account)
on your behalf.

If this request applies to you, then you find the instructions for this request
[here](https://github.com/dime-worldbank/dime-account-admin/blob/main/instructions/request-access-dime-org.md).
This page is open to anyone.

#### Request external collaborator access to a repo on the DIME account

If you are mapped to any of the DIME units you can request that
an external collaborator is given access to the repo.
This requiring you sending an email with the terms and conditions
to the external collaborator who replies
to that email to saying they accept the terms and conditions.
Then you forward that email to DIME Analytics who then
give access to the external collaborator.

DIME Analytics pays a small fee for
each external collaborator added to private repos.
We therefore ask the DIME teams to only request access
for external collaborators who actually need access to the repo.
We are never charged more than once per external collaborator
no matter how many repos they have access to.
And we are not charged for external collaborators only added to public repos.

The terms and conditions to send to the external collaborators
and more details can be found
[here](https://github.com/dime-worldbank/dime-account-admin-private/blob/main/instructions/add-external-collaborator-dime-org.md)
This page is only visible users currently logged in to GitHub.com
with a GitHub account already added to the DIME GitHub account.
If you cannot see the page and it says `Sign up`/`Sign in` at
the top of the page then you are currently not signed to GitHub.com
with any account in the browser you are currently using. 
Reach out to DIME Analytics if think you should be able to see it,
but is not able to do so.

#### Request a new repo to be created on the DIME account

If you are mapped to a DIME unit you can request that
a new repo is created for your team. You find instructions for that
[here](https://github.com/dime-worldbank/dime-account-admin-private/blob/main/instructions/request-new-repo-dime-org.md)
This page is only visible users currently logged in to GitHub.com
with a GitHub account already added to the DIME GitHub account.
If you cannot see the page and it says `Sign up`/`Sign in` at
the top of the page then you are currently not signed to GitHub.com
with any account in the browser you are currently using.
Reach out to DIME Analytics if think you should be able to see it,
but is not able to do so.

## Actions for the WB account

These instructions only applies to repos hosted on the EB account.
You can know if your repo is hosted on the WB account by checking
if your repo has `worldbank` in its URL.
For example: https://github.com/worldbank/ietoolkit.
(If your repo says only `dime-worldbank` instead of `worldbank` then use
[these instructions](#actions-for-the-dime-account).

Anyone with an active WB contract can join the WB account by using this
[eServices request](https://worldbankgroup.service-now.com/wbg?id=wbg_sc_catalog&sys_id=910e1739db1a54903c5960ab13961912).
This page is only visible if you have access to the WB intranet.

Requests for new repos and adding external collaborators to the repos hosted on the WB account can be found [here](https://github.com/dime-worldbank/dime-account-admin-private/blob/main/instructions/wb-github-account.md)
This page is only visible users currently logged in to GitHub.com
with a GitHub account already added to the DIME GitHub account.
If you cannot see the page and it says `Sign up`/`Sign in` at
the top of the page then you are currently not signed to GitHub.com
with any account in the browser you are currently using.
Reach out to DIME Analytics if think you should be able to see it,
but is not able to do so.

## DIME GitHub Training Slides

Some of these slides are for trainings that are meant to be interactive and might therefore not be optimal for self learning. But we are still happy to share these slides and hope that you will find them useful. The source code for these slides can be found [here](https://github.com/worldbank/dime-github-trainings/tree/main/GitHub-trainings).

* [Intro to Git/GitHub - Observer](https://osf.io/a2htb/) - How to use GitHub to browse code and to provide feedback on code.
* [Intro to Git/GitHub - Contributor](https://osf.io/2mz4j/) - How to use GitHub to collaborate on code.
* [GitHub Team Maintainer Training](https://osf.io/arpyc/) - Intro to GitHub's Team feature that we use to allow the project teams to be able togrant and revoke access to the project teams' repositories.
