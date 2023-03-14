# study_Java

## Thread safe MAP implementation:
  * ConcurrentHashMap
    * Thread safe
    * Default locking mechanism - lock only the portion of the map being modified
    * High perfomance because of fine grained locking mechanism
  * HashMap:
    * Not thread safe
