<!-- --- title: POST /group_requests -->

This creates a new record for the user trying to join a group that requires approval to join.

=
####Authentication:

The user needs to be logged in and have valid credentials to use this route.

=
####Parameters:

None; default only.

=
####Response:

This requests provides a <strong>HTML 201</strong> on success.

=
####API request example:
```html
http://example.com/group_requests
```

=
####Post data example:
```
{ group_request: 
  { group_id: 706 } 
 }
```

=
###Post data detail:

[[include:/post_data/post_group_request]]

=
####JSON response example:

[[include:/json/JSON_POST_group_request]]

=
####Response Data Detail:

[[include:/serializers/group_request]]