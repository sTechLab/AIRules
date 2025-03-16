# Longitudinal Subreddit Set

Subreddit metadata and rules for english-language subreddits that were seen in both a July 2023 and Novemeber 2024 crawl.

## Dataset Schema

| Column | Type | Description |
|--------|------|-------------|
| `id` | string | Unique identifier for each subreddit |
| `name_jul23` | string | Subreddit name as of July 2023 |
| `public_description_jul23` | string | Public description of the subreddit as of July 2023 |
| `subscribers_jul23` | integer | Number of subscribers as of July 2023 |
| `rules_jul23` | list/object | Raw rules data of the subreddit as of July 2023 |
| `cleaned_rules_jul23` | string | Processed/cleaned version of rules as of July 2023 |
| `has_ai_rule_label_jul23` | boolean | Label indicating if the subreddit had AI-related rules as of July 2023 |
| `name_nov24` | string | Subreddit name as of November 2024 |
| `public_description_nov24` | string | Public description of the subreddit as of November 2024 |
| `subscribers_nov24` | integer | Number of subscribers as of November 2024 |
| `rules_nov24` | list/object | Raw rules data of the subreddit as of November 2024 |
| `cleaned_rules_nov24` | string | Processed/cleaned version of rules as of November 2024 |
| `has_ai_rule_label_nov24` | boolean | Label indicating if the subreddit had AI-related rules as of November 2024 |
