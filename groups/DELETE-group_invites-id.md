<!-- --- title: DELETE /group_invites/:id -->

This allows the recipient of a group invite to delete the invite. The sender of the invite is not allowed to delete the invite, only the recipient. Deletion of the invite is the action taken when the user rejects the invite.

=
####Authentication:
The user needs to be logged in and have valid credentials to use this route.

=
####Parameters:
:id (group_invite_id) - Integer, passed in through the URL. Is derived from the 'id' field on the 'group_invites' table.

=
####Response:

This requests provides a <strong>HTML 204</strong> on success.

=
####API request example:
```html
http://example.com/group_invites/234
```

=
####JSON response example:

[[include:/json/JSON_NO_RESPONSE]]