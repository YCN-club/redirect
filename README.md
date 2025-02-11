# ycn.club redirect

![Release](https://img.shields.io/github/v/release/YCN-club/redirect)
![Forks](https://img.shields.io/github/forks/YCN-club/redirect?style=flat)

> ⚠️ **Notice:** This repository has been archived and will no longer receive updates (not like we expect it to, honestly). For further information on the project's status and brand identity, please refer to the [organization's README](https://github.com/orgs/YCN-club).

It redirects, so... yeah.

## Usage

1. After forking the repository, go to **Settings > Pages**.

2. Select the following settings:

	- **Source:** Deploy from a branch
	- **Branch:** `main`, with `/(root)` directory.

3. Hit 'Save'. The 'Custom domain' section should automatically pick up the subdomain from the `CNAME` file.

4. Now, add a DNS record for your domain with the following:

	- **Type:** CNAME
	- **Name:** `YOUR_SUBDOMAIN` (ex: `redirect` for `redirect.mitblr.club`)
	- **Value:** `mitblr-club.github.io`

Now, after saving the record and waiting for changes to kick in, GitHub Pages should redirect to your required page.
