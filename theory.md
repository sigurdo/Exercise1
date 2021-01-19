Exercise 1 - Theory questions
-----------------------------
 
 ### What is the difference between concurrency and parallelism?
 > Concurrency is when multiple tasks run concurrently, but not necessarily at the exact same time. Concurrent tasks or processes is therefore often running on the same processor but with an OS loading and unloading their data at alternating times. Parallelism means that multiple processes run in parallell literally at the same time and that requires a multicore processor to be possible.
 
 ### Why have machines become increasingly multicore in the past decade?
 > Machines become multicore because it provides more processing power than singlecore machines. The reason it has happened so much the last decade is that the extreme processing power development that has been ongoing since the 1960s has previously been achieved buy higher clock rates, but we have reached a thermal limit at 5GHz where it is almost impossible to clock circuits higher without melting them in the process. Therefore to multicore processors are needed today to continue the development of fast processors.
 
 ### Why do we divide software (programs) into concurrently executing parts (like threads or processes)?
 > (Or phrased differently: What problems do concurrency help in solving?)
 We do it because we want a lot of processeses to intuitively run concurrently, but we only have 1 (or just a few) processor cores, so instead of having to manually syncronize intuitively meaningful processes into one chaotic mixed process make them run in different threads instead.
 
 ### Does creating concurrent programs make the programmer's life easier? Harder? Maybe both?
 > (Come back to this after you have worked on part 4 of this exercise)
 Easier. 100%.
 
 ### What is the conceptual difference between threads and processes?
 > I'm not exactly sure how the difference is defined, but threads are generally more lightweight than processes. Which means shared variables and stuff should be easier in another thread, but processes might increase performance by using mutliple cores for example.
 
 ### Some languages support "fibers" (sometimes called "green threads") or "coroutines"? What are they?
 > They are just like threads but instead of preemptive multitasking they use cooperative multitasking (according to wikipedia). That means the seperate threads stop them selves instead of an external scheduler stopping them when it is time for another thread to run. This might lead to better utilization of processing resources.
 
 ### What is the Go-language's "goroutine"? A C/POSIX "pthread"?
 > *Your answer here*
 
 ### In Go, what does `func GOMAXPROCS(n int) int` change? 
 > *Your answer here*



 
 
 
 
