# Rules Subreddit Set 

Subreddit metadata, rules, and labels for english-language subreddits with non-empty rules gathered in Novemeber 2024. The labels have been applied using the prompts in the paper appendix. 

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
| `topic_label` | string | Topic label assigned to the subreddit |
| `has_ai_rule_label` | boolean | Label indicating if the subreddit has rules about AI |
| `is_topical_question_and_answer_ca_label` | boolean | Label indicating if the subreddit belongs to the 'Topical Question and Answer' Community Archetype |
| `is_learning_and_perspective_broadening_ca_label` | boolean | Label indicating if the subreddit belongs to the 'Learning and Perspective Broadening' Community Archetype |
| `is_social_support_ca_label` | boolean | Label indicating if the subreddit belongs to the 'Social Support' Community Archetype |
| `is_content_generation_ca_label` | boolean | Label indicating if the subreddit belongs to the 'Content Generation' Community Archetype |
| `is_affiliation_with_an_entity_ca_label` | boolean | Label indicating if the subreddit belongs to the 'Affiliation With an Entity' Community Archetype |
