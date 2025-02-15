---
name: List assignees
example: octokit.rest.issues.listAssignees({ owner, repo })
route: GET /repos/{owner}/{repo}/assignees
scope: issues
type: API method
---

# List assignees

Lists the [available assignees](https://help.github.com/articles/assigning-issues-and-pull-requests-to-other-github-users/) for issues in a repository.

```js
octokit.rest.issues.listAssignees({
  owner,
  repo,
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
<tr><td>per_page</td><td>no</td><td>

Results per page (max 100).

</td></tr>
<tr><td>page</td><td>no</td><td>

Page number of the results to fetch.

</td></tr>
  </tbody>
</table>

See also: [GitHub Developer Guide documentation](https://docs.github.com/rest/reference/issues#list-assignees).
