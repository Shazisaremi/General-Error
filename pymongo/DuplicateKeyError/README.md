### MongoDB Command insert failed: E11000 duplicate key error collection
In this article we shall see how to resolve the error E11000 duplicate key error collection in the MongoDB command execution.

- E11000 duplicate key error could occur due to many factors depending on the type of operation you are performing.
- This error however indicates that the issue has occurred because the key with which you performed the Mongo operation key already exists with the value specified.
- This also meant the indexed key in the error is a unique key and not the non-unique key or sparsed key. That means only one key with a unique value can exist in the given mongo collection.
Generally, you will have default _id as a unique key in the mongo collection.
