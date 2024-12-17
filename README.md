This repository demonstrates a common race condition bug in Java and its solution.  The `Counter` class is intended to increment a counter value, but due to lack of synchronization in the `getCount` method, concurrent threads can lead to incorrect results. The solution addresses this by synchronizing the `getCount` method.