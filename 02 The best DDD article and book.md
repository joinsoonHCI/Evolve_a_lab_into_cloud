- The best article about DDD: Effective Aggregate Design by VAUGHN VERNON.
- The key point: the fundamental rule to define the scope of a microservice is "do not use 2-phase-commit between microservices".
- This makes it clear that "transaction" (and related concurrency) is the key, which is a data-centric. 
- "Data-centric" is not about data; it is about transaction and concurrency. 
- If we read/watch Eric's book and videos carefully, we would know that DDD is not OO; and, DDD is not necessarily against data-centric point of view.  
    * The deep reason DDD rejects data-centric is that in the past, data-centric is not agile. Now, because of NoSQL, data-centric can be agile; and, agile can and should be data-centric.      

- The best book about DDD, other than Eric's original, is Domain Modeling Made Functional, by Scott Wlaschin. 
- Many people, myself included some years ago, think that DDD is OO. That is because Eric's book was written when Java was at its peak.
- DDD is not about technology -- it can work with any technologies. Further, the interesting thing is, DDD de-emphasizes technologies. However, we can say with certainty that DDD is more naturally aligned with functional, event-driven, and text-based, perspective/paradigm.
