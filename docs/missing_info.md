# Missing information & comments for the Tasks API documentation

## Authentication

It is not clear if the `username` and `password` should be sent as header or query parameters.


## Parameters

- `taskID` vs. `encodedKey`: what's the difference?
- specify exact formats allowed for:
    - `taskID`
    - `encodedKey`
    - `assignedUserKey`
    - `taskLinkKey`
    - `clientId`
    - `groupId`


## Models

Even though `ErrorResponse` and `RestError`, as well as `PatchOperation` and `PatchOperationsList` are duplicates of each other, I did not remove these because there are references to both in the file (and potentially elsewhere in the API documentation).