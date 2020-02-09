#### Description

Code doesn't seem to work when data stored in redis Hash

#### Steps to Reproduce

items=redis_instance.hgetall(key)

##### Expected Behavior

Return all records from the Redis db

##### Actual Behavior

Only returns the last record.

#### Additional Information

Perhaps you didn't design this example if the data in Redis is stored as a Hash?  Can't seem to figure out why only the last record is displayed?
