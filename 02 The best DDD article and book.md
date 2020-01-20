- Better late than never: the best article about DDD: https://dddcommunity.org/library/vernon_2011/
    * It by VAUGHN VERNON
    * The key point I get is: the fundamental rule to define the scope of a microservice is "do not use 2-phase-commit between microservices".
    * This makes it clear that "transaction" (and related concurrency) we should use a data-centric point of view on DDD, because "data-centric" is not about data, it is about transaction and concurrency. 
    * If we read/watch Eric's book and videos carefully, we would know that DDD is not OO; and, DDD is not necesssarily against data-centric point of view.  
    
- The best book about DDD, other than Eric's original, is Domain Modeling Made Functional, by Scott Wlaschin. 
    * Many people, myself included some years ago, think that DDD is OO. That is because Eric's book were written when Java was at it peak.     
	* DDD is not about technology -- it can work with any technologies. And further, the interesting thing is, DDD deemphasizes technologies. However, we can say with certainty that DDD is more naturally aligned with functional, event-driven, and text-based, perspective, or, paradigm.

