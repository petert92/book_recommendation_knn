# book_recommendation_knn
K nearest neighbors model to recommend books


Ivestigation:

- Recommendation approach use: Collaborative filtering user-based
    "predictions (filtering) about the interests of a user by collecting preferences or taste information from many users (collaborating). The underlying assumption of the                 collaborative filtering approach is that if a person A has the same opinion as a person B on an issue, A is more likely to have B's opinion on a different issue than that         of a randomly chosen person". https://en.wikipedia.org/wiki/Collaborative_filtering 
    Common problems: Cold start (not enough data to new user) not apply; Sparcity (lot of users but just a few do ratings) apply; Scalability (lot of data so lot of preccesing);       Gray sheep (users whose don't feet); Synonyms (system uncapable of read synonyms); Shilling attacks (user rates their item); key problem is how to combine and weight the preferences of user neighbors.
    Data: imnplicit (could be rating=0); explicit (the rest)
    Large amount of data is need
    Common workflow: (https://en.wikipedia.org/wiki/Collaborative_filtering)
        1. User expresses preferences by rating items (an approximate representation of the user's interest)
        2. System matches this user's ratings against other users' and finds the people with most "similar" tastes.
        3. The system recommends items that the similar users have rated highly but not yet being rated by this user.
     
- Performance measures: user studies, online evaluations (A/B tests), and offline evaluations.
