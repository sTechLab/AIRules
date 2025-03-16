# AI Rules Set 

Subreddit rules and labels for rules gathered in Novemeber 2024 that were identified as being about AI. The labels have been applied using the prompts in the paper appendix. 

## Dataset Schema

### Identifier Columns
| Column | Type | Description |
|--------|------|-------------|
| `subreddit_id` | string | Unique identifier for the subreddit to which the rule belongs |
| `rule_ind` | integer | Index or position of the rule within the subreddit's rule list |

### Rule Content Columns
| Column | Type | Description |
|--------|------|-------------|
| `rule_description` | string | Full text description of the rule |
| `rule_short_name` | string | Brief name or title of the rule |
| `rule_violation_reason` | string | Text shown when a post/comment violates this rule |
| `cleaned_rule` | string | Processed version of the rule text for analysis |

### Is AI Rule Column
| Column | Type | Description |
|--------|------|-------------|
| `is_ai_rule_label` | boolean | Flag indicating if the rule specifically addresses AI |

### AI Rule Usage Columns 
| Column | Type | Description |
|--------|------|-------------|
| `usage_generate_label` | boolean | Rule addresses AI-generated content |
| `usage_assist_label` | boolean | Rule addresses AI-assisted content |
| `usage_general_label` | boolean | Rule broadly addresses AI without specific usage type |

### AI Rule Rationale Columns 
| Column | Type | Description |
|--------|------|-------------|
| `rationale_lowquality_label` | boolean | Rule cites low quality |
| `rationale_loweffort_label` | boolean | Rule cites low effort |
| `rationale_spam_label` | boolean | Rule cites spam concerns |
| `rationale_misleading_label` | boolean | Rule cites misleading nature |
| `rationale_inaccurate_label` | boolean | Rule cites factual inaccuracies |
| `rationale_inauthentic_label` | boolean | Rule cites lack of authenticity |
| `rationale_inhuman_label` | boolean | Rule cites "inhuman" qualities |
| `rationale_offtopic_label` | boolean | Rule cites AI content as off-topic |
| `rationale_policy_label` | boolean | Rule cites policy reasons for AI restrictions |
| `rationale_ethics_label` | boolean | Rule cites ethical concerns about AI content |
| `rationale_original_content_label` | boolean | Rule cites original content requirements |

### AI Rule Form Columns 
| Column | Type | Description |
|--------|------|-------------|
| `form_text_label` | boolean | Rule addresses AI-generated text |
| `form_images_label` | boolean | Rule addresses AI-generated images |
| `form_videos_label` | boolean | Rule addresses AI-generated videos |
| `form_art_label` | boolean | Rule addresses AI-generated art |
| `form_deepfake_label` | boolean | Rule addresses deepfakes or similar technologies |
| `form_fakes_label` | boolean | Rule addresses fake/synthetic content generally |
| `form_bots_label` | boolean | Rule addresses AI bots or automated accounts |
| `form_content_label` | boolean | Rule addresses content, but nothing more specific |
| `form_general_label` | boolean | Rule does not address a specific form of AI |

### AI Rule Stance Columns 
| Column | Type | Description |
|--------|------|-------------|
| `stance_unqualified_ban_label` | boolean | Rule completely bans AI use |
| `stance_qualified_ban_label` | boolean | Rule bans some uses of AI |
| `stance_disclosure_label` | boolean | Rule requires disclosure of AI use |
| `stance_enabling_label` | boolean | Rule permits AI use |
| `stance_requiring_label` | boolean | Rule requires AI use in some cases |

### General Rule Columns 
| Column | Type | Description |
|--------|------|-------------|
| `advertising_and_commercialization_label` | boolean | Rule addresses advertising/commercial content |
| `consequences_moderation_enforcement_label` | boolean | Rule describes enforcement actions |
| `content_behavior_label` | boolean | Rule governs general content/behavior |
| `copyright_piracy_label` | boolean | Rule addresses copyright/piracy issues |
| `doxxing_personal_info_label` | boolean | Rule addresses doxxing/personal information |
| `post_format_label` | boolean | Rule discusses specific post formats |
| `harassment_label` | boolean | Rule discusses harassment |
| `hate_speech_label` | boolean | Rule discusses hate speech |
| `images_label` | boolean | Rule governs image submissions |
| `links_and_outside_content_label` | boolean | Rule governs external links/content |
| `low_quality_content_label` | boolean | Rule discusses low-quality content |
| `nsfw_label` | boolean | Rule governs NSFW content |
| `off_topic_label` | boolean | Rule discusses off-topic content |
| `personal_army_label` | boolean | Rule addresses rallying users against others |
| `personality_label` | boolean | Rule governs personality/tone of interactions |
| `politics_label` | boolean | Rule giverns political content |
| `prescriptive_label` | boolean | Rule is prescriptive in nature |
| `reddiquette_sitewide_label` | boolean | Rule references sitewide Reddit policies |
| `reposting_label` | boolean | Rule governs reposting content |
| `restrictive_label` | boolean | Rule is restrictive in nature |
| `spam_label` | boolean | Rule discusses spam |
| `spoilers_label` | boolean | Rule governs spoiler content |
| `trolling_label` | boolean | Rule discusses trolling |
| `voting_label` | boolean | Rule addresses voting behavior |
