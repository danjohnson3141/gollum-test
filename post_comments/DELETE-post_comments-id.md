<!-- --- title: DELETE /post_comments/:id -->

Deletes *one* comment that exists associated with a post. The user has to be listed as the creator of the post in order for this route to be succseful. 

=
####Authentication:

The user needs to be logged in and have valid credentials to use this route.

=
####Parameters:

(post comment) :id - Integer, passed in throug the URL. Is derived form the 'id' field on the 'post_comments' table.

=
####Response:

This requests provides a <strong>HTML 204</strong> on success.

=
####API request example:
```html
http://example.com/post_comments/234
```

=
####JSON response example:

[[include:/json/JSON_NO_RESPONSE]]