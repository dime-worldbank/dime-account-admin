# DIME/WB GitHub Account Guidelines

### Git/GitHub trainings resources

This repo includes instructions related to DIME's GitHub account.
For Git/GitHub trainings and DIME Analytics other
Git/GitHub resources see here see
[here](https://osf.io/e54gy/)
and/or [here](https://github.com/worldbank/dime-github-trainings).  

## Requests for the DIME and WB Accounts:

These requests may differ depending on which account your repo is/will be hosted on. So first, make sure you know which account your repo is or should be hosted on. Repos with URLs starting with:
https://github.com/dime-worldbank is hosted on the DIME account and repos with URLs starting with:
https://github.com/worldbank is hosted on the WB account.
Read more about why we use multiple accounts [here](./resources/why-multiple-accounts.md).


| Action | DIME Account | WB Account|
|---|---|----|
| Add new internal user as member | [New Member DIME account](#dime-account-request-membership) | [New Member WB account](#wb-account-request-membership) |
| Give user access to repo | [DIME Account Repo](#dime-account-repo-access)<br>(Both internal member and external collaborator) | [WB Account Repo](#wb-account-repo-access)<br>(Both internal member and external collaborator) |
| Repo creation on the account| [Request New DIME Account Repo](#dime-account-repo-creation)| [Request New WB Account Repo](#wb-account-repo-creation)                                        

### Why add users as members first?

Who can become a member?

* Users with an active WB account may be added as members to either the DIME or the WB account. Users without an active WB email must be added as external collaborators directly to individual repositories.

Who should be added to which account as member?

* Any user with an active WB account should be added as a member of the WB account if they work on WB account hosted repos.
* Users with active WB accounts mapped to either DIME unit, should be added as a member of the DIME account if they work on DIME account hosted repos.
* Users with active WB accounts _not_ mapped to a DIME unit, may still be added to the DIME account. This makes sense if the user works across a portfolio of DIME account hosted repos. 

Adding a users as account members has these advantages:

* Project teams can give and revoke access to their repos when people join or leave the team without having to involve DIME Analytics
* Collaboration across teams is easier as other users can
quickly be given access to repos without having to involve DIME Analytics
* This provides a way to manage access to content on the DIME account to DIME members only. (DIME Account only)

## General GitHub Actions:

* **Change name of a GitHub repository**
  * [Request repository name change](./instructions/request-name-change.md)

For any other request, send an email to DIME Analytics with your question.

## DIME Account requests

These instructions applies to repos with URLs starting with:
https://github.com/dime-worldbank.

### DIME Account: Request membership

* **DIME users:** [eServices request](https://worldbankgroup.service-now.com/wbg?id=wbg_sc_catalog&sys_id=910e1739db1a54903c5960ab13961912) (_WB intranet access only - if you do not have access to the eServices portal someone else can make the request on your behalf_)
* **WB non-DIME users:** If you have an active WB contract and work on a portfolio of DIME projects you may still be added as a member. Discuss with your DIME contact and then submit the request for DIME users and list the DIME contact in the request when asked to.
* **External users**: External users are only given access on per repo basis. See repo access section below.

**_Quick notes:_**
* You must have a YubiKey or a WB computer to be able to access the WB account as a member. WB users without this can still be added as external users.
* Joining the DIME account do not by itself give access to any repo hosted there. See repo access below.

_See pages with instructions for more details._

### DIME Account: Repo access

* **DIME account members:** [Add DIME account member to team](https://github.com/dime-worldbank/dime-account-admin-private/blob/main/instructions/dime-repo-access-member.md). (_DIME account member access only - see [here](./resources/dime-only-resources.md) if link does not work_)
* **External collaborators:** [Request access to repo on behalf of external collaborator](https://github.com/dime-worldbank/dime-account-admin-private/blob/main/instructions/dime-repo-access-external.md). (_DIME account member access only - see [here](./resources/dime-only-resources.md) if link does not work_)

**_Quick notes:_**
* Users who already are members of the DIME account (see above how to become a member) are given access to the repo by adding them to the GitHub team used for that repo.
* The maintainer of the GitHub team can add DIME account members to the team without involving DIME Analytics. (DIME Analytics can help but will reach out to maintainer for approval.)
* To see who is maintainer of a GitHub team,
see the [team reports](https://github.com/dime-worldbank/dime-account-admin-private/tree/main/reports/team-reports).
To see what GitHub team is used for a repo,
see the [repo reports](https://github.com/dime-worldbank/dime-account-admin-private/tree/main/reports/repo-reports).
(_DIME account member access only - see [here](./resources/dime-only-resources.md) if link does not work_)
* External collaborators are not added to the DIME account and can therefore not be added to GitHub teams. Instead, external collaborators are added to individual repos.
* The request to add external collaborators to a repo should be sent to DIME Analytics by a person at DIME.

_See pages with instructions for more details._

### DIME Account: Repo creation

* [Repo creation instructions](https://github.com/dime-worldbank/dime-account-admin-private/blob/main/instructions/dime-create-repo.md). (_DIME account member access only - see [here](./resources/dime-only-resources.md) if link does not work_)

**_Quick notes:_**
* The request to create a new repo can be sent by anyone in DIME (does not need to be a member of the DIME account or even have a GitHub account)
* The request to create a new repo needs to be approved by a DIME manager

_See pages with instructions for more details._

## WB Account requests

These instructions applies to repos with URLs starting with:
https://github.com/worldbank.

### WB Account: Request membership

* **WB users:** [eServices request](https://worldbankgroup.service-now.com/wbg?id=wbg_sc_catalog&sys_id=910e1739db1a54903c5960ab13961912) (_WB intranet access only - if you do not have access to the eServices portal someone else can make the request on your behalf_)
* **External users**: External users are only given access on per repo basis. See repo access section below.

**_Quick notes:_**
* You must have a YubiKey or a WB computer to be able to access the WB account as a member. WB users without this can still be added as external users.
* Anyone with an active WB contract and a GitHub account can use the eServices request to join the WB account
* Joining the WB account do not by itself give access to any repo hosted there

_See pages with instructions for more details._

### WB Account: Repo access

* **WB account member:** [Add WB account member to team](https://github.com/dime-worldbank/dime-account-admin-private/blob/main/instructions/wb-repo-access-member.md). (_DIME account member access only - see [here](./resources/dime-only-resources.md) if link does not work_)
* **External collaborators:** [Request access to repo on behalf of external collaborator](https://github.com/dime-worldbank/dime-account-admin-private/blob/main/instructions/wb-repo-access-external.md). (_DIME account member access only - see [here](./resources/dime-only-resources.md) if link does not work_)

**_Quick notes:_**
* Similarly to the DIME account, WB account members are given access to repos through maintainers adding them to GitHub teams on the WB account.
* GitHub teams on the DIME account cannot be used for repos on the WB account
* DIME Analytics does not generate repo and team reports
(i.e. [these](https://github.com/dime-worldbank/dime-account-admin-private/tree/main/reports)) for the WB account.
Instead, browse this page https://github.com/orgs/worldbank/teams (_WB account member access only_) to find which team is used for which repo.
* External collaborators are not added to the DIME account and can therefore not be added to GitHub teams. Instead, external collaborators are added to individual repos.
* The request to add external collaborators to a repo should be sent to DIME Analytics by a person at DIME.

_See pages with instructions for more details._

### WB Account: Repo creation

* [Repo creation instructions](https://github.com/dime-worldbank/dime-account-admin-private/blob/main/instructions/wb-create-repo.md). (_DIME account member access only - see [here](./resources/dime-only-resources.md) if link does not work_)

**_Quick notes:_**
* Most repos should be created on the DIME account, but reach out to DIME Analytics if you think your repo should be hosted on the WB account
* The request to create a new repo can be sent by anyone in DIME (does not need to be a member of the DIME account or even have a GitHub account)
* The request to create a new repo needs to be approved by a DIME manager

_See pages with instructions for more details._
