# alw3_data
Here we provide the announcements and subreddit participation data from
"The Discourse of Online Content Moderation: Investigating Polarized User Responses to Changes in Reddit's Quarantine Policy"

Data files:
  - author_faction_assignments.csv: This csv file contains authors' distribution of
    participation across the 5 subreddit categories found through community detection.
    Columns in the participation distribution field correspond to the following categories:
        - C0: Sports/technology subreddits
        - C1: Internet compilation subreddits
        - C2: Right-leaning subreddits
        - C3: Meme/social subreddits
        - C4: Left-leaning subreddits
        - C5: Miscellaneous/unlabelled subreddits
  - announcements_data.csv: Text and metadata from the September 2018 r/announcements thread.
    Descriptions of the fields are listed below:
        - id: Unique ID associated with a post (submission or comment)
        - parent_id: ID associated with the parent to a post
        - subreddit: Subreddit that a post takes place in
        - score: Fuzzed score associated with the post
        - gildings: Gildings given to the post
        - created: Date/time of post creation
        - author_id: ID of the user who authored the post
        - body: Raw text of the post
        - edited: Whether the post was edited at any point

Author information in all files have been replaced by anonymized numeric ids.
