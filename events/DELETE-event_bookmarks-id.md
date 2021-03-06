<!-- --- title: DELETE /event_bookmarks/:id -->

Removes **one** one event_bookmark record from the database. The active user is only able to remove records for which they are the creator.

=
####Authentication:

The user needs to be logged in and have valid credentials to use this route.

=
####Parameters:

:id - Integer, passed in through the URL. Is derived from the 'id' field on the 'event_bookmarks' table.

=
####Response:

This requests provides a <strong>HTML 204</strong> on success.

=
####API request example:
```html
http://example.com/event_bookmarks/234
```

=
####JSON response example:

[[include:/json/JSON_NO_RESPONSE]]