My second project in this repository, this one was quite an adventure. I learned much more about safe (very safe) (we aren't going to die I promise) multithreading, specifically `Arc` and `Mutex`. I have gained a much better understanding of their uses, as well as an appreciation for their designs. Unlike my project, I didn't decide in advance the workloads of each thread. Instead, threads picked up new assignments as they went, effectively ignoring the stragler's problem (thanks dad for explaining that to me, I'm sure it will make me sound very smart some day in a performace meeting), as well as introducing me to the need for `Arc` and `Mutex`. I considered trying to explain both of them here, but in trying so I realized how I little understanding I have of them even after this project. I'm very excited to continue working with them. God I love Rust. 