Why concurrency with threading is faster.
Improved I/O performance which allows programs to handle multiple I/O operations (like network requests or file access) simultaneously, preventing the program from being blocked while waiting for a response. it is relatively simple to implement but can be less efficient for high concurrency due to context switching overhead.
 helps utilize CPU cores more effectively by allowing multiple tasks to be run concurrently, even if they’re not strictly CPU-bound. 
And helping responsiveness by not blocking the main thread, it can keep the user interface responsive even while preforming lengthy operations in the background.


