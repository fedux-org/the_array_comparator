# API Guide

This very brief documentation should give you a good starting point on how to discover the API:

```
Comparator                           # Main class dispatching the work
|
-- Check, Result, Sample             # Helper classes for easier testing
|
-- SearchingStrategies               
|  |
|  -- ContainsAll                    # Strategies doing the hard work:
|  |                                 # compare data with keywords and
|  -- ...                            # return the result
|
-- CachingStrategies
|  |
|  -- SingleValueCaching             # Strategies doing the hard work:
|  |                                 # caching the objects
|  -- ...                            
 
```
