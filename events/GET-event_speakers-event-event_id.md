<!-- --- title: GET /event_speakers/event/:event_id -->

Returns all of the speakers for one event.

=
####Authentication:

The user needs to be logged in and have valid credentials to use this route.

=
####Parameters:

:event_id - Integer, passed in through the URL. Derived from the 'id' field on the 'events' table.

=
####Response:

This requests provides a <strong>HTML 200</strong> on success.

=
####API request example:
```html
http://example.com/event_speakers/event/1947
```

=
####JSON response example:

[[include:/json/JSON_GET_event_speakers_event_event_id]]

=
####Response Data Detail:

[[include:/serializers/EXAMPLE]]