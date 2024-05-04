## Getting unix time

|name|ops/sec|samples|
|-|-|-|
|new Date().getTime()|13,122,481|92|
|Date.now()|23,624,890|97|


<details>
<summary>Environment</summary>

* __Machine:__ linux x64 | 4 vCPUs | 15.2GB Mem
* __Run:__ Sat May 04 2024 02:04:00 GMT+0000 (Coordinated Universal Time)
</details>

<!--
{"environment":{"platform":"linux","arch":"x64","cpus":4,"totalMemory":15.245216369628906},"benchmarks":[{"name":"new Date().getTime()","opsSec":13122481.229870748,"samples":5},{"name":"Date.now()","opsSec":23624889.849400196,"samples":5}]}-->