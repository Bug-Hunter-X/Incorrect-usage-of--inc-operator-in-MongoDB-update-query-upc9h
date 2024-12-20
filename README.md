# MongoDB $inc Operator Bug
This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries. The issue arises from using a negative value to decrement the counter instead of incrementing it as intended.  The solution provides the corrected approach.
## Bug
The original code attempts to increment a counter using the `$inc` operator. However, due to the negative value provided, the counter value gets decremented instead. This can lead to unexpected behavior and data corruption.
## Solution
The solution demonstrates the correct use of `$inc` to increment a counter.  It shows that positive values are needed to increment and negative values to decrement. Always double check your parameters.
