# DIME/WB GitHub Account Guidelines

### Git/GitHub Training Resources

This page includes instructions related to DIME's GitHub account.  
For Git/GitHub training and other DIME Analytics resources, see  
[here](https://osf.io/e54gy/) and/or [here](https://github.com/worldbank/dime-github-trainings).

## Requests for the DIME and WB Accounts

Requests may differ depending on which account your repository is or will be hosted on.  
First, confirm which account your repository is or should be hosted on:

- Repositories with URLs starting with `https://github.com/dime-worldbank` are hosted on the DIME account.
- Repositories with URLs starting with `https://github.com/worldbank` are hosted on the WB account.

Read more about why we use multiple accounts [here](./resources/why-multiple-accounts.md).

| Request | DIME Account | WB Account |
|---|---|---|
| Add new internal user as member | [New Member DIME account](#dime-account-request-membership) | [New Member WB account](#wb-account-request-membership) |
| Give user access to repo | [DIME Account Repo](#dime-account-repo-access)<br>(Both internal member and external collaborator) | [WB Account Repo](#wb-account-repo-access)<br>(Both internal member and external collaborator) |
| Repo creation on the account | [Request New DIME Account Repo](#dime-account-repo-creation) | [Request New WB Account Repo](#wb-account-repo-creation) |

### Why Add Users as Members First?

**Who can become a member?**

- Users with an active WB account may be added as members to either the DIME or WB account.
- Users without an active WB email must be added as external collaborators directly to individual repositories.

**Who should be added to which account as member?**

- Any user with an active WB account should be added as a member of the WB account if they work on WB account-hosted repositories.
- Users with active WB accounts mapped to the DIME unit should be added as members of the DIME account if they work on DIME account-hosted repositories.
- Users with active WB accounts _not_ mapped to a DIME unit may still be added to the DIME account if they work across a portfolio of DIME account-hosted repositories.

**Advantages of adding users as account members:**

- Project teams can grant or revoke access to their repositories when people join or leave, without involving DIME Analytics.
- Collaboration across teams is easier, as users can quickly be given access to repositories without involving DIME Analytics.
- This provides a way to manage access to content on the DIME account for DIME members only (DIME Account only).

## General GitHub Actions

- **Change name of a GitHub repository:**  
  [Request repository name change](./instructions/request-name-change.md)

For any other request, send an email to DIME Analytics with your question.

## DIME Account Requests

These instructions apply to repositories with URLs starting with:  
`https://github.com/dime-worldbank`

### DIME Account: Request Membership

- **DIME users:** [eServices request](https://worldbankgroup.service-now.com/wbg?id=wbg_sc_catalog&sys_id=910e1739db1a54903c5960ab13961912) (_WB intranet access only. If you do not have access to the eServices portal, someone else can make the request on your behalf._)
- **WB non-DIME users:** If you have an active WB contract and work on a portfolio of DIME projects, you may still be added as a member. Discuss with your DIME contact and then submit the request for DIME users, listing the DIME contact in the request when asked.
- **External users:** External users are only given access on a per-repository basis. See the repo access section below.

**_Quick notes:_**

- You must have a YubiKey or a WB computer to access the WB account as a member. WB users without this can still be added as external users.
- Joining the DIME account does not by itself give access to any repository hosted there. See repo access below.

_See pages with instructions for more details._

### DIME Account: Repo Access

- **DIME account members:** [Add DIME account member to team](https://github.com/dime-worldbank/dime-account-admin-private/blob/main/instructions/dime-repo-access-member.md). (_DIME account member access only. See [here](./resources/dime-only-resources.md) if the link does not work._)
- **External collaborators:** [Request access to repo on behalf of external collaborator](https://github.com/dime-worldbank/dime-account-admin-private/blob/main/instructions/dime-repo-access-external.md). (_DIME account member access only. See [here](./resources/dime-only-resources.md) if the link does not work._)

**_Quick notes:_**

- Members of the DIME account are given access to repositories by being added to the GitHub team for that repository.
- The maintainer of the GitHub team can add DIME account members to the team without involving DIME Analytics. (DIME Analytics can help but will reach out to the maintainer for approval.)
- To see who is the maintainer of a GitHub team, see the [team reports](https://github.com/dime-worldbank/dime-account-admin-private/tree/main/reports/team-reports). (_DIME account member access only. See [here](./resources/dime-only-resources.md) if the link does not work._)
- To see which GitHub team is used for a repository, see the [repo reports](https://github.com/dime-worldbank/dime-account-admin-private/tree/main/reports/repo-reports). (_DIME account member access only. See [here](./resources/dime-only-resources.md) if the link does not work._)
- External collaborators are not added to the DIME account and cannot be added to GitHub teams. Instead, external collaborators are added to individual repositories.
- The request to add external collaborators to a repository should be sent to DIME Analytics by a person at DIME.

_See pages with instructions for more details._

### DIME Account: Repo Creation

- [Repo creation instructions](https://github.com/dime-worldbank/dime-account-admin-private/blob/main/instructions/dime-create-repo.md). (_DIME account member access only. See [here](./resources/dime-only-resources.md) if the link does not work._)

**_Quick notes:_**

- The request to create a new repository can be sent by anyone in DIME (does not need to be a member of the DIME account or even have a GitHub account).
- The request to create a new repository needs to be approved by a DIME manager.

_See pages with instructions for more details._

## WB Account Requests

These instructions apply to repositories with URLs starting with:  
`https://github.com/worldbank`

### WB Account: Request Membership

- **WB users:** [eServices request](https://worldbankgroup.service-now.com/wbg?id=wbg_sc_catalog&sys_id=910e1739db1a54903c5960ab13961912) (_WB intranet access only. If you do not have access to the eServices portal, someone else can make the request on your behalf._)
- **External users:** External users are only given access on a per-repository basis. See the repo access section below.

**_Quick notes:_**

- You must have a YubiKey or a WB computer to access the WB account as a member. WB users without this can still be added as external users.
- Anyone with an active WB contract and a GitHub account can use the eServices request to join the WB account.
- Joining the WB account does not by itself give access to any repository hosted there.

_See pages with instructions for more details._

### WB Account: Repo Access

- **WB account members:** [Add WB account member to team](https://github.com/dime-worldbank/dime-account-admin-private/blob/main/instructions/wb-repo-access-member.md). (_DIME account member access only. See [here](./resources/dime-only-resources.md) if the link does not work._)
- **External collaborators:** [Request access to repo on behalf of external collaborator](https://github.com/dime-worldbank/dime-account-admin-private/blob/main/instructions/wb-repo-access-external.md). (_DIME account member access only. See [here](./resources/dime-only-resources.md) if the link does not work._)

**_Quick notes:_**

- WB account members are given access to repositories through maintainers adding them to GitHub teams on the WB account.
- GitHub teams on the DIME account cannot be used for repositories on the WB account.
- DIME Analytics does not generate repository and team reports (i.e. [these](https://github.com/dime-worldbank/dime-account-admin-private/tree/main/reports)) for the WB account.  
  Instead, browse [this page](https://github.com/orgs/worldbank/teams) (_WB account member access only_) to find which team is used for which repository.
- External collaborators are not added to the DIME account and cannot be added to GitHub teams. Instead, external collaborators are added to individual repositories.
- The request to add external collaborators to a repository should be sent to DIME Analytics by a person at DIME.

_See pages with instructions for more details._

### WB Account: Repo Creation

- [Repo creation instructions](https://github.com/dime-worldbank/dime-account-admin-private/blob/main/instructions/wb-create-repo.md). (_DIME account member access only. See [here](./resources/dime-only-resources.md) if the link does not work._)

**_Quick notes:_**

- Most repositories should be created on the DIME account, but reach out to DIME Analytics if you think your repository should be hosted on the WB account.
- The request to create a new repository can be sent by anyone in DIME (does not need to be a member of the DIME account or even have a GitHub account).
- The request to create a new repository needs to be approved by a DIME manager.

_See pages with instructions for more details._
