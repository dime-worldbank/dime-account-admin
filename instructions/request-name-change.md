# Request repository name change

You will need admin access to the repository you want to change name of.
For repositories hosted on either https://github.com/dime-worldbank or
https://github.com/worldbank you can always request DIME Analytics
to help you with this.

## Things to consider before changing name

GitHub has implemented a lot of support to make name changes as seamless as possible,
but below are still a few things good to consider before changing the name.

### Use a best practice for a new name

Select a repo name that is descriptive, but will be simple to type in a URL. Here are some guidelines on what is simple to type as a URL.

* No spaces. Spaces are not allowed in URLs. For that reason spaces are not even allowed in repo names on GitHub. Instead, use hyphens: `-`
* No underscores: `_`. URLs are often formatted as blue underlined text, and underscores do not blend well with underlined text. It usually looks messy. Instead, use hyphens `-`.
* No upper-case letters. In some uses, URLs _are_ case-sensitive, but in others they _are not_. This can cause confusion or failure to connect. The best way to avoid this is to use only lower-case. That also looks better, as the other parts of your repo URL (`https`, `github.com` and `dime-worldbank`) will all be lower-case.
* Use only lower-case letters (a-z) and numbers (0-9), and do not start with a number. Do not use any special characters (like `&`, `!`, `()`, etc). They might make your URL error-prone. The one exception to this rule is the hyphen character `-`. It is a URL-safe character and it is good for splitting the repo names into words without using a space.
* Avoid long repo names as it will make the URL too long. If someone at some point needs to enter the URL manually it will be cumbersome and error prone. And a long URL might not display well when you include it in a text or on the front page of a publication, etc.

### Redirect of old URLs

GitHub will re-direct most old URLs to the new URLs, but not all.
Links that you can rely on will re-direct are, for example, links to file contents in the repository
(ex: `https://github.com/dime-worldbank/old-name/blob/main/README.md`) and links to basic standard GitHub features
(ex: `https://github.com/dime-worldbank/old-name/issues`).
I.e., a URL like
`https://github.com/dime-worldbank/old-name/blob/main/README.md` will seamlessly
re-direct to `https://github.com/dime-worldbank/new-name/blob/main/README.md`.
This will work perpetually, unless a new repository will be created
on the same account using the old name.

Some URLs, for example GitHub Pages URLs on the format https://worldbank.github.io/old-name/,
will not re-direct.
Exactly what type of links will re-direct changes as GitHub implements, change or remove features.
If you have any links your work relies on that is neither links to file content in the repository or
basic standard features, then research if your important link will re-direct.
DIME Analytics is happy to help in this research if wanted.

### Update existing clones

Existing clones will in most major Git clients automatically update the next time
the user either push to or pulls from the renamed repository.
Similarly to URLs, this will only work as long as no new repo is created with the old name in the same account.

Since there are a large number of Git clients, we cannot guarantee that that it will be this seamless in all clients.
In those cases it is typically easiest to delete the clone and re-clone the repository.
However, make sure that you have a backup of any not yet committed edits
or any ignored files you cannot easily re-create before deleting the clone.

If you want to be abundantly cautious, then you can make sure that the whole team push
any uncommitted edits to the repo, and do not make edits to the code for this repo until
they have updated their clone with the new name of the repo.
This is typically not needed, but we there are so many types of clients and features on GitHub,
that this is what we recommend for anyone who want to be guaranteed nothing can be lost.

Most Git clients that does update the clone tends to keep the old name of the repo
as the name of the folder that contains the clone.
This is to not break any existing file paths.
Git won't complain if you manually change the name of this folder,
but make sure that you fix any links that become broken after changing the name of the folder.

## How to request name change from DIME Analytics

Send an email to dimeanalytics@worldbank.org. In this email include the following:

* Give the email subject: `GitHub: Repo change name <old-repo-name>`
* Let us know if you need help with anything above before we make the change
* Provide the full URL to the repo
* Provide the new name to the repo

This request can be sent to us by anyone, but in case you are not DIME
or do not have active `write` access to the repo,
then please copy someone who fits that description or the TTL in the email.
