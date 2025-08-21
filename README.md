# ML_Algo_Mental-Health-Analysis-from-Journaling
This dataset simulates anonymized journaling entries from users of a mental health journaling app. Each row represents one journal entry with text and derived features (sentiment, emotions, etc.). The goal is to detect early signs of mental health deterioration and classify users into risk categories.
Column Descriptions

entry_id → Unique identifier for each journal entry (UUID).

user_id → Anonymized user ID (helps track multiple entries from same user).

timestamp → Date and time when the entry was written.

journal_text → The raw journaling text written by the user (main NLP input).

sentiment_score → Numeric score from -1 (negative) to +1 (positive), representing overall sentiment.

emotion_scores → Dictionary of detected emotions with intensity values (e.g., {sadness: 0.7, anxiety: 0.4}).

word_count → Number of words in the entry (can show engagement level).

topic_category → The main topic of the entry (e.g., work, relationships, health, loneliness).

time_of_day → Time period when entry was written (morning, afternoon, evening, night).

keyword_flags → Whether sensitive keywords appear (e.g., “depressed”, “anxious”, “hopeless”).

entry_frequency → Number of entries the user made per week (reflects journaling behavior).

mental_health_label → Target column – the mental health state of the user.


Target Column

mental_health_label

Type: Categorical

Values:

stable → user is mentally stable

mild_distress → signs of stress or anxiety are present

severe_distress → strong indications of mental health deterioration
