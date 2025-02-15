---
name: List notifications for the authenticated user
example: octokit.rest.activity.listNotificationsForAuthenticatedUser()
route: GET /notifications
scope: activity
type: API method
---

# List notifications for the authenticated user

List all notifications for the current user, sorted by most recently updated.

```js
octokit.rest.activity.listNotificationsForAuthenticatedUser();
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
    <tr><td>all</td><td>no</td><td>

If `true`, show notifications marked as read.

</td></tr>
<tr><td>participating</td><td>no</td><td>

If `true`, only shows notifications in which the user is directly participating or mentioned.

</td></tr>
<tr><td>since</td><td>no</td><td>

Only show notifications updated after the given time. This is a timestamp in [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601) format: `YYYY-MM-DDTHH:MM:SSZ`.

</td></tr>
<tr><td>before</td><td>no</td><td>

Only show notifications updated before the given time. This is a timestamp in [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601) format: `YYYY-MM-DDTHH:MM:SSZ`.

</td></tr>
<tr><td>per_page</td><td>no</td><td>

Results per page (max 100).

</td></tr>
<tr><td>page</td><td>no</td><td>

Page number of the results to fetch.

</td></tr>
  </tbody>
</table>

See also: [GitHub Developer Guide documentation](https://docs.github.com/rest/reference/activity#list-notifications-for-the-authenticated-user).
