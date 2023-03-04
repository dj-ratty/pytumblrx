# Migrating from pytumblr
pytumblrx trying to have same API, but there are some changes

## Python Version Change
Python 2.7 dropped. 3.9 and higher for now

## API change
- Changing API host isn't supported
- `type` parameter in functions renamed to `type_`
  - `TumblrRestClient.dashboard`
- `filter` parameter in functions renamed to `filter_`
  - `TumblrRestClient.tagged`
  - `TumblrRestClient.posts`
  - `TumblrRestClient.queue`
- `id` parameter in functions renamed to `id_`
  - `TumblrRestClient.posts`
  - `TumblrRestClient.like`
  - `TumblrRestClient.unlike`
  - `TumblrRestClient.reblog`
  - `TumblrRestClient.delete_post`
  - `TumblrRestClient.edit_post`
  - `TumblrRestClient.notes`
- `format` parameter in functions renamed to `format_`
  - `TumblrRestClient.create_photo`
  - `TumblrRestClient.create_text`
  - `TumblrRestClient.create_quote`
- `TumblrRestClient.send_api_request` removed