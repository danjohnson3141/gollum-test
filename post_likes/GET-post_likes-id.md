<!-- --- title: GET /post_likes/:id -->

Returns **one** post like based off the id passed in.

=
####Authentication:

The user needs to be logged in and have valid credentials to use this route.

=
####Parameters:

(post likes) :id - Integer, passed in through the URL. Is derived from the 'id' field on the 'post_likes' table.

=
####Response:

This requests provides a <strong>HTML 200</strong> on success.

=
####API request example:
```html
http://example.com/post_likes/553
```

=
####JSON response example:

[[include:/json/JSON_GET_post_likes_id]]

=
####Response Data Detail:

[[include:/serializers/EXAMPLE]]