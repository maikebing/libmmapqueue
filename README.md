# libmmapqueue

 Created on: 2014-5-5
     Author: Shaneyu <shaneyu@tencent.com>

 Based on transaction pool, features:
 1) support multiple writer and multiple reader processes/threads
 2) support timestamping for each data
 3) support auto detecting and skipping corrupted elements
 4) support variable user data size
 5) use highly optimized gettimeofday() to speedup sys time
 
