HTTP Status Codes
=================

Some status codes have a specific meaning

403
    You have made a valid request, but you lack permissions to the object you are trying to interact with.

409
    There was a conflict when your request was processed.
    Normally this is due to your data not including all of the required fields, having invalid fields or values,
    or there is a conflict between your object and another (e.g. some resources require a unique <name>).
    Check your data and reattempt.

