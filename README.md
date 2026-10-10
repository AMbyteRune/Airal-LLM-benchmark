# Airal-LLM-benchmark
Airal will test and benchmark your local llm interfrence server.
built in python and Locust

Airal simulates concurrent API requests to evaluate server performance under stress, tracking metrics like Time To First Token (TTFT) and Time Per Output Token (TPOT)
testing enterprise configurations like vLLM, LM Studio, or Ollama before production deployments


Airal can do several things for U


-Test how your GPU handles parallel requests and PagedAttention memory allocations.


-Calculates precise TTFT and token generation speeds using streaming endpoints 


Prerequisites
Python 3.x
An active LLM inference server (e.g., vLLM endpoint running on `http://localhost:8000`)

installing:  
  
  Clone the repository:
  
   git clone [https://github.com/yourusername/llm-infer-bench.git](https://github.com/yourusername/llm-infer-bench.git)
  
   
   cd llm-infer-bench

i hope you find Airal useful and help you to find exact metrics needed. if you think you can help Airal growth, fear not to do it!
