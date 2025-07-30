# GitHub Activity Viewer

This is a simple tool I built because there wasn’t an easy way on GitHub to see, in one place, all the issues, PRs, and discussions where I’ve been active—sorted by most recent activity.

With this page, you can quickly see your (or any user’s) last activity across issues, PRs, and (per-repo) discussions you participated in.

Try it live here:
[https://githubajh.z19.web.core.windows.net/](https://githubajh.z19.web.core.windows.net/)

---

## Features

* See a user’s most recently active issues, PRs, and discussions
* Sorted by last activity (most recent first)
* Works for any GitHub user
* **Supports filling the form via URL query string**
* No sign-in required

---

## Why?

GitHub doesn’t provide a simple global view of all issues and discussions you’ve commented on, ordered by last activity.
This page fills that gap for anyone who wants a quick, unified view.

---

## How to use

1. Enter your GitHub username.
2. Optionally, enter one or more repos (for discussions): `owner/repo,owner2/repo2`
3. Click **Load Activity** to see your latest involvement.

---

## Quick-link support (URL query string)

You can also pre-fill and auto-run the search via URL parameters:

```
https://githubajh.z19.web.core.windows.net/?user=YOUR_GITHUB_USERNAME&repos=owner/repo,owner2/repo2
```

**Examples:**

* Just username:
  `https://githubajh.z19.web.core.windows.net/?user=aherrick`

* Username and one repo:
  `https://githubajh.z19.web.core.windows.net/?user=aherrick&repos=microsoft/azure-devops-mcp`

* Username and multiple repos:
  `https://githubajh.z19.web.core.windows.net/?user=aherrick&repos=dotnet/runtime,microsoft/semantic-kernel`

Open the link in your browser and the form will auto-fill and auto-run.

---

*Not affiliated with GitHub. Built just for convenience!*
