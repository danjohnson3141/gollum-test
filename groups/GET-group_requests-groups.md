<!-- --- title: GET /group_requests/groups -->

Returns all of the outstanding requests for the logged in user. Should not return any groups that the user is already a member of.

=
####Authentication:

The user needs to be logged in and have valid credentials to use this route.

=
####Parameters:

None; default only.

=
####Response:

This requests provides a <strong>HTML 200</strong> on success.

=
####API request example:
```html
http://example.com/group_requests/groups
```

=
####JSON response example:

returns an array of group requests

[[include:/json/JSON_GET_group_requests_group]]

=
####Response Data Detail:

[[include:/serializers/group_request_group]]