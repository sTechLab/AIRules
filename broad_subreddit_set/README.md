# Broad Subreddit Set

Subreddit metadata and rules for english-language subreddits gathered in Novemeber 2024.

## Dataset Schema

| Column | Type | Description |
|--------|------|-------------|
| `id` | string | Unique identifier for each subreddit |
| `name` | string | Name of the subreddit |
| `public_description` | string | Public description of the subreddit |
| `subscribers` | integer | Number of subscribers |
| `rules` | json_object | Raw rules data of the subreddit |
| `cleaned_rules` | string | Processed/cleaned version of rules |
| `created_utc` | timestamp | Unix timestamp representing when the subreddit was created |
