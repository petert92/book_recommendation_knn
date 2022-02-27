# book_recommendation_knn
K nearest neighbors model to recommend books


Ivestigation:

- Recommendation approach use: Collaborative filtering 
    "  predictions (filtering) about the interests of a user by collecting preferences or taste information from many users (collaborating). The underlying assumption of the collaborative filtering approach is that if a person A has the same opinion as a person B on an issue, A is more likely to have B's opinion on a different issue than that of a randomly chosen person". https://en.wikipedia.org/wiki/Collaborative_filtering 
    Common problems: Cold start (not enough data to new user) not apply; Sparcity (lot of users but just a few do ratings) apply; Scalability (lot of data so lot of preccesing)
    Data: imnplicit (could be rating=0); explicit (the rest)
    Large amount of data is need
