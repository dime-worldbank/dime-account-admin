# DIME GitHub Resources

This repo includes instructions related to DIME's GitHub repos.
For general GitHub resources, including all of DIME Analytics GitHub trainings,
see [here](https://osf.io/e54gy/).  

## Table of Content

* [Why are GitHub teams used for access to repos?](#why-does-dime-use-both-a-dime-account-and-a-wb-account)
* [Actions for the DIME account](#actions-for-the-dime-account).
Join the DIME Github account, invite external collaborators, create a new repo.
* [Actions for the WB account](#actions-for-the-dime-account).
Join the WB GitHub account, invite external collaborators, create a new repo.
* [Why does DIME use both a DIME account and a WB account?](#why-does-dime-use-both-the-dime-account-and-the-wb-account)

## Why are GitHub teams used to provide access to repos?

This section will use "_project team_" and "_GitHub team_"
to mean two similar but different things.
A project team is a set of people working on a project,
and a GitHub team is a set of GitHub user accounts.
The rest of this section explains how they are similar but also different,
as well as how GitHub teams are used on the DIME account.

#### Admin access are not given to project members

The default is that DIME Analytics does not
give project team members admin access to the repos.
This is due to two reasons.
First, admin access gives users access to "_destructive features_"
(for example permanently delete a repo)
the account admins in DIME Analytics cannot undo.
Second, admin access gives users access to features that can incur a cost.
Since all costs incurred on the DIME account are charged to DIME Analytics,
any such action should go through DIME Analytics.

#### GitHub teams solves repo access management without admin access

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

#### Best practice for GitHub teams

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

#### How to be a team maintainer

Users are added and removed from the team on the member tab
of the team's page on the DIME account.
Team maintainers can only add user that have already
[requested and joined](#request-to-join-the-dime-account) the DIME account.
External collaborators can not be added to GitHub teams.
Instead, their DIME contact must
[request](#request-external-collaborator-access-to-a-repo-on-the-dime-account)
that DIME Analytics gives them access
by adding them directly to each repo they need access to.

## Actions for the DIME account

These instructions only applies to repos hosted on the DIME account.
Most DIME repos are hosted on the DIME account but not all
([read more here](#why-does-dime-use-both-the-dime-account-and-the-wb-account)).
Your repo is hosted on the DIME account if it has `dime-worldbank` in its URL.
For example: https://github.com/dime-worldbank/dime-account-admin.
(If your repo says `worldbank` instead of `dime-worldbank` then use
[these instructions](#actions-for-the-wb-account) instead.

#### Request to join the DIME account

This request is open to you if you are mapped to any of the DIME units.
You may also use this request if you work extensively on a DIME project
with a DIME TTL, that DIME project has a repo on the DIME account,
and you have a World Bank email even if you are not mapped to DIME.
If you are not sure if this applies to you, then talk to your DIME supervisor.
If you do not have a World Bank email, then ask your DIME contact to request
[external collaborator access](#request-external-collaborator-access-to-a-repo-on-the-dime-account)
on your behalf.

If this request applies to you, then you find the instructions for this request
[here](https://github.com/dime-worldbank/dime-account-admin/blob/main/instructions/request-access-dime-org.md).
This page is open to anyone.

#### Request external collaborator access to a repo on the DIME account

If you are mapped to any of the DIME units you can request that
an external collaborator is invited to
one or several of your project team's repo.
This requires you sending an email with the terms and conditions
to the external collaborator, who then replies to that email to you
saying they accept the terms and conditions.
Then you forward that email to DIME Analytics who then
invite the external collaborator to that or those repos.

DIME Analytics pays a small fee for
each external collaborator added to private repos.
We therefore ask the DIME teams to only request access
for external collaborators who actually needs access to the repo.
We are not charged for external collaborators
that are only added to public repos.
We are never charged more than once per external collaborator
no matter how many private repos they are given access to.

The terms and conditions to send to the external collaborators
and more details about this request can be found
[here](https://github.com/dime-worldbank/dime-account-admin-private/blob/main/instructions/add-external-collaborator-dime-org.md).
This page is only visible to users currently logged in to GitHub.com
with a GitHub account already added to the DIME GitHub account.
If you cannot see the page and it says "_Sign up_"/"_Sign in_" at
the top of the page, then you are currently not signed to GitHub.com
with any account in the browser you are currently using.
Reach out to DIME Analytics if think you should be able to see it,
but are not able to do so.

#### Request a new repo to be created on the DIME account

If you are mapped to a DIME unit you can request that
a new repo is created for your team.
You find instructions for requesting the creation of a repo on the DIME account
[here](https://github.com/dime-worldbank/dime-account-admin-private/blob/main/instructions/request-new-repo-dime-org.md)
This page is only visible to users currently logged in to GitHub.com
with a GitHub account already added to the DIME GitHub account.
If you cannot see the page and it says "_Sign up_"/"_Sign in_" at
the top of the page, then you are currently not signed to GitHub.com
with any account in the browser you are currently using.
Reach out to DIME Analytics if think you should be able to see it,
but are not able to do so.

## Actions for the WB account

These instructions only applies to repos hosted on the WB account.
Your repo is hosted on the DIME account if it has `worldbank` in its URL.
For example: https://github.com/worldbank/ietoolkit.
(If your repo says `dime-worldbank` instead of `worldbank` then use
[these instructions](#actions-for-the-dime-account) instead.

Anyone with an active WB contract can join the WB account by using this
[eServices request](https://worldbankgroup.service-now.com/wbg?id=wbg_sc_catalog&sys_id=910e1739db1a54903c5960ab13961912).
This page is only visible if you have access to the WB intranet.

Requests for new repos and adding external collaborators to the repos hosted on the WB account can be found [here](https://github.com/dime-worldbank/dime-account-admin-private/blob/main/instructions/wb-github-account.md)
This page is only visible to users currently logged in to GitHub.com
with a GitHub account already added to the DIME GitHub account.
If you cannot see the page and it says "_Sign up_"/"_Sign in_" at
the top of the page, then you are currently not signed to GitHub.com
with any account in the browser you are currently using.
Reach out to DIME Analytics if think you should be able to see it,
but are not able to do so.

## Why does DIME use both the DIME account and the WB account?

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
