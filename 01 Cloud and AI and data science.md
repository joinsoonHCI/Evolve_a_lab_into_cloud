
- The big 3，the technology part： we have three elements, cloud, AI, and data science. Among them, cloud is providing the supporting structure; so, for now, it is playing the leading role. Cloud is leading the business. But those three are together; they support each other and have synergy with each other. 

    * AI is also related to another low profile but important thing, text and git. The path of the relationship is:  
        - AI -> natural language processing -> speech to text -> the importance of text -> markdown and ymal -> git. 
            * So, AI is not just in-depth AI, it has broader impact -- it will change UI.
		- Conversely, UI has impact on AI also -- the HCI: modern AI practice will always be HCI. 
		
	* DevOps: cloud is making Dev and Ops into one thing, by integrating 4 things: network-security, server-database-admin, architect, and development. 
		- One small but significant thing to make Ops closer to Dev: Windows scripting (powershell) is now similar to Linux's.  
		- Recent years, agile CI/CD is making Dev closer to Ops.    
        - Recent years, micro-services is also making Dev closer to Ops.
		- Parallel processing brings Dev and Ops together. And, it goes deeper: it brings functional programming. 
        - Git has direct impact on DevOps. 
    * Big data: it has deeper meaning -- datababses now finally become agile. 
	    - Conversely, agile is completely changed also. Agile can and should be data-centric now.
            - Finally, agile does not need to be painfully evasive from database anymore. Agile is now established in the middle of databases. As a result, agile can and should use relational model and related transaction log and concurrent model， as its most important modeling tool. 
	    - Git has direct impact on agile process also.
		
    * Summary of the above: the "string theory architecture" in cloud: 
	    - Natural Language Processing, text/git. Note that git has impact on all 3 parts.  
		- Microservice, functional language
        - NoSQL database, log-centric/stream processing/event sourcing 

    * The "string theory architecture" is important to navigate and understand cloud.
	    - The roles in cloud are in three groups: AI, users; dev, ops; big data and IoT.
		    * Agile is most obvious in cloud: creating value for business is the key. So, the differences among roles are much less rigid than before. It is like the early days of Internet: everyone can do everything. But now it is at a higher and therefore cleaner level: we do everything in a secure and orderly manner.			
		- The areas in cloud are also in those three groups. 

- The big 3, the company part: AWS, GCP, Azure.
    * We should use all 3, for the following reasons. 
	    * We are learning. So, we need to try all 3. 
	    * Also, at this early stage, if we need something, we have to pick whatever works among those 3.  
        * It is too early to call which one will win. 
        * It is likely it will not like the OS war(s); it is likely that the focus will be inter-operation. 
    * For now, the big 3 each has its own pros and cons. 
	    * AWS is good at cloud per se, the "Ops" part.
		* GCP is good at the "Dev" part, but especially (and unfortunately only) on brand new things (e.g. AI and big data). 
		* Azure is also good at the "Dev" part, on all kinds of apps. 
			- Among the big 3, only Azure has strong business-line application development tradition.
			    * Even for Java and other non-MS languages, if it is for business-line applications, it is likely Azure will have more and better support.  
			- So, although we should use all big 3, and although cloud is inherently "integration-oriented", it is likely that Azure will have a special role among the big 3 -- we will use Azure to integrate AWS, Azure, and GCP, with business-line applications. 
  	        
- The big 2 -- the two old rivaries: MS C# vs Java-and-others 
    * The differences between MS and Sun (Oracle) and later Google, the traditional MS vs open source, are less obvious now, because MS open sourced many things. 
    * So, we should treat .Net, C#, F# the same as Java, Python, Node.js, and other languages. 
    * As a matter of fact, in cloud, the focus is not "standardize on this or that"; instead, it is to synthesize， orchestra， or choreography multiple parts regardless their languages. 


- The big 1 -- off-the-shelve: all those elements, such as cloud, AI, data science, and DevOps, are about the whole system. As a result, we cannot obtain them by buying; instead, we have to grow them -- evolve the system and the DevOps team, and, the user community (the "business"). 
    * In other words, move the current system to the cloud, piece by piece.  
    * This repo is the architecture, the agile process, and, mostly importantly, the continuously learning, of the journey.

