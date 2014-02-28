Updates the group. Only the group owner is allowed to update the group, and the only editable options are the group's name and the description of the group.

=
#### Authentication

The user needs to be logged in and have valid credentials to use this route.

=
#### Parameters

:name - Varchar, passed in through the post data. Is derived from the 'name' field of the 'groups' table.

:description - Text, passed in through the post data. Is derived from the 'description' field of the 'groups' table.

=
####JSON request example:
```
http://0.0.0.0:3000/groups/234
```

=
####Post Data
```
{ group: 
  { name: "Groups are Awesome", 
    description: "New Description" } 
 }
```
=
####JSON response example:

```
NO JSON RESPONSE
```

This requests provides a <strong>HTML 204</strong> on success.