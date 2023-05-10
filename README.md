# Detailed Memories

A CK3 mod that expands on the current memory system, to include a wider range of events and interactions for the player to see whilst playing. The 

# Current Ideas List

## Alliances

| Event | Description | Associated Files | Added? | Tested? |
| :---: | :--- | :---: | :---: | :---: |
| on_alliance_added | When a character creates a new alliance | alliance_on_actions.txt | No | No |
| on_alliance_removed | Presumably whenever a character loses an alliance, no matter the reason? | alliance_on_actions.txt | No | No |
| on_alliance_broken | When a character breaks an alliance | alliance_on_actions.txt | No | No |

## Armies, Combat, Wars

| Event | Description | Associated Files | Added? | Tested? |
| :---: | :--- | :---: | :---: | :---: |
| on_siege_completion | When a siege completes, should fire for both holder and leige | army_on_actions.txt | No | No |
| on_raid_action_start | When someone begins raiding your territory? | army_on_actions.txt | No | No |
| on_raid_action_completion | When someone finished raiding your territory? | army_on_actions.txt | No | No |
| on_defeat_raid_army | When a raid army is defeated | army_on_actions.txt | No | No |
| on_combat_end_winner | Events that happen to the winner after a battle. Create memory for both commander and liege? | combat_on_actions.txt | No | No |
| on_combat_end_loser | Events that happen to the loser after a battle. Create memory for both commander and liege? | combat_on_actions.txt | No | No |
| on_holy_order_new_lease | Barony is on loan to a holy order | holy_order_on_actions.txt | No | No |
| on_holy_order_hired | Holy order hired by a character | holy_order_on_actions.txt | No | No |
| on_holy_order_destroyed | Holy order destroyed | holy_order_on_actions.txt | No | No |
| on_commander_combat_finished | Called for a commander when combat ends | knights_on_actions.txt | No | No |
| on_army_combat_finished | Called for the owner of the army when combat ends | knights_on_actions.txt | No | No |
| varangian_ongoing | Character is a member of varangian guard | knights_on_actions.txt | No | No |
| on_war_white_peace | War ends in white peace | war_on_actions.txt | No | No |

## Childhood

| Event | Description | Associated Files | Added? | Tested? |
| :---: | :--- | :---: | :---: | :---: |
| child_personality_gain | When a character gains a personality trait as a child | childhood_on_actions.txt | No | No |
| childhood_ongoing | When a character gains a crush, friendship, bully, etc. | childhood_on_actions.txt | No | No |
| on_16th_birthday | Gaining education trait on 16th birthday | childhood_on_actions.txt | No | No |
| on_action_add_sexuality | Sexuality decided roughly after they turn 10 years old | childhood_on_actions.txt | No | No |
| on_birthday_education_events | Linked to children getting education traits? | childhood_on_actions.txt | No | No |
| on_set_relation_guardian | When a child has a guardian set? | relation_on_actions.txt | No | No |

## Council and Court

| Event | Description | Associated Files | Added? | Tested? |
| :---: | :--- | :---: | :---: | :---: |
| on_leave_council | When the player (or character) leaves a council? | councillor_on_actions.txt | No | No |
| on_fired_from_council | When the player (or character) is fired from the council? | councillor_on_actions.txt | No | No |
| on_councillor_left | When a councillor leaves your court | councillor_on_actions.txt | No | No |
| train_commanders_success_effect | Marshal trains a new commander | councillor_on_actions.txt | No | No |
| task_find_secrets_outcome | Spymaster finds a secret in a court | councillor_on_actions.txt | No | No |
| on_join_court | Character joined a court | court_maintenance_on_actions.txt | No | No |
| inspiration_completed_events | Character completes an inspiration | ep1_inspirations_on_actions.txt | No | No |
| on_artifact_changed_owner | Artifact changes owners | inventory_on_actions.txt | No | No |
| on_artifact_succession | Artifact inherited | inventory_on_actions.txt | No | No |
| on_artifact_broken_through_decay | Artifact destroyed through decay | inventory_on_actions.txt | No | No |
| on_artifact_broken_through_effect | Artifact destroyed through, e.g. combat | inventory_on_actions.txt | No | No |

## Culture, Language and Religion

| Event | Description | Associated Files | Added? | Tested? |
| :---: | :--- | :---: | :---: | :---: |
| on_character_culture_change | Character changes their culture | culture_on_actions.txt | No | No |
| on_faith_conversion | Character "converts" religion? | religion_on_actions.txt | No | No |
| on_character_faith_change | Character "changes" religion? | religion_on_actions.txt | No | No |
| learn_language_success | Character learns a new language | learn_language_on_actions.txt | No | No |

## Dynasty and Family

| Event | Description | Associated Files | Added? | Tested? |
| :---: | :--- | :---: | :---: | :---: |
| on_dynasty_created | Character creates a dynasty, specific for bastard founders? | dynasty_on_actions.txt | No | No |
| parent_meddling_outcome | Interaction between character and their parent(s) | parent_on_actions.txt | No | No |
| court_politics_task_on_action | Events when spouse is set to court politics | parent_on_actions.txt | No | No |

## Health

| Event | Description | Associated Files | Added? | Tested? |
| :---: | :--- | :---: | :---: | :---: |
| disease_outbreak_pulse | Character gets a disease (ill, lover's pox, etc.) | health_on_actions.txt | No | No |
| wounded_recovery_pulse | Character recovers from wound. What about getting wounded? | health_on_actions.txt | No | No |
| commit_suicide | Character commits suicide | health_on_actions.txt | No | No |
| stress_threshold_level_1_event | Level 1 stress events | stress_on_actions.txt | No | No |
| stress_threshold_level_2_event | Level 2 stress events | stress_on_actions.txt | No | No |
| stress_threshold_level_3_event | Level 3 stress events | stress_on_actions.txt | No | No |

## Marriage

| Event | Description | Associated Files | Added? | Tested? |
| :---: | :--- | :---: | :---: | :---: |
| on_marriage | Character gets married | marriage_concubinage.txt | No | No |
| on_divorce | Character gets divorced | marriage_concubinage.txt | No | No |
| on_concubinage | Character becomes a concubine | marriage_concubinage.txt | No | No |
| on_concubinage_end | Character ceases to be a concubine | marriage_concubinage.txt | No | No |
| on_betrothal_broken | Broken betrothal | marriage_concubinage.txt | No | No |

## Schemes

| Event | Description | Associated Files | Added? | Tested? |
| :---: | :--- | :---: | :---: | :---: |
| abduct_succeeded | Character successfully adbucts another | abduct_on_actions.txt | No | No |
| claim_throne_succeeded | Character successfully claims leige's throne | claim_throne_on_actions.txt | No | No |
| seduce_success | Character successfully seduces another | seduce_on_actions.txt | No | No |
| steal_back_artifact_success | Successfully steal back an artifact | steal_back_artifact_on_actions.txt | No | No |

## Vassals and Titles

| Event | Description | Associated Files | Added? | Tested? |
| :---: | :--- | :---: | :---: | :---: |
| on_title_gain | Character gains a title | title_on_actions.txt | No | No |
| on_title_gain_inheritance | Character gains a title through inheritance | title_on_actions.txt | No | No |
| on_title_gain_usurpation | Title was usurped | title_on_actions.txt | No | No |
| on_title_lost | Character lost a title | title_on_actions.txt | No | No |
| on_rank_up | New title causes increase in rank | title_on_actions.txt | No | No |
| on_rank_down | Loss of a title causes decrease in rank | title_on_actions.txt | No | No |
| on_vassal_gained | Gained a character as a vassal | title_on_actions.txt | No | No |
