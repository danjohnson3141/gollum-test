| name              | description                                       | type                 |
|-------------------|---------------------------------------------------|----------------------|
| id                | The ID of this record                             | integer              |
| first_name        | The user's first name                             | string               |
| last_name         | The user's last name                              | string               |
| title             | The user's title                                  | string               |
| name              | The named used internally; usually two characters | string               |
| organization_name | The organization the user is associated with      | string               |
| photo             | URL of a photo of the user                        | string               |
| user              | Info on the user                                  | object; UserShort    |
| event_council     | Info on the event_council                         | object; EventCouncil |