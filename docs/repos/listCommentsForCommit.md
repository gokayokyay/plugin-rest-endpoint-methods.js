---
name: List commit comments
example: octokit.rest.repos.listCommentsForCommit({ owner, repo, commit_sha })
route: GET /repos/{owner}/{repo}/commits/{commit_sha}/comments
scope: repos
type: API method
---

# List commit comments

Use the `:commit_sha` to specify the commit that will have its comments listed.

```js
octokit.rest.repos.listCommentsForCommit({
  owner,
  repo,
  commit_sha,
});
```

## Parameters

<table>
  <thead>
    <tr>
      <th>name</th>
      <th>required</th>
      <th>description</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>owner</td><td>yes</td><td>

</td></tr>
<tr><td>repo</td><td>yes</td><td>

</td></tr>
<tr><td>commit_sha</td><td>yes</td><td>

commit_sha parameter

</td></tr>
<tr><td>per_page</td><td>no</td><td>

Results per page (max 100).

</td></tr>
<tr><td>page</td><td>no</td><td>

Page number of the results to fetch.

</td></tr>
  </tbody>
</table>

See also: [GitHub Developer Guide documentation](https://docs.github.com/rest/reference/repos#list-commit-comments).
