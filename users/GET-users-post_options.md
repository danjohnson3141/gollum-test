<!-- --- title: GET /users/post_options -->

PLAIN ENGLISH DESCRIPTION OF THE ROUTE

=
#### Authentication

The user needs to be logged in and have valid credentials to use this route.

=
#### Parameters

none; default only

=
####JSON request example:
```json
http://0.0.0.0:3000/users/post_options
```

=
####JSON response example:

```json
{"app_sponsors"=>
  [{"id"=>105,
    "name"=>"Harvey-Bruen",
    "description"=>
     "Delectus labore quia cum quaerat sed ratione qui et sit nam.",
    "logo"=>nil,
    "url"=>nil,
    "sponsor_type"=>

     {"id"=>144, "name"=>"A type of Sponsor", "description"=>"A Sponsor Type"},
    "users"=>[]},
   {"id"=>106,
    "name"=>"Zboncak Inc",
    "description"=>
     "Itaque officia quibusdam necessitatibus laboriosam consequatur officiis qui aspernatur unde.",
    "logo"=>nil,
    "url"=>nil,
    "sponsor_type"=>
     {"id"=>145, "name"=>"A type of Sponsor", "description"=>"A Sponsor Type"},
    "users"=>[]}]}
```

This requests provides a <strong>HTML 200</strong> on success.