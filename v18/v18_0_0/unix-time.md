## Getting unix time

|name|ops/sec|samples|
|-|-|-|
|new Date().getTime()|7,347,548|96|
|Date.now()|15,420,928|97|


<details>
<summary>Environment</summary>

* __Machine:__ linux x64 | 2 vCPUs | 6.8GB Mem
* __Run:__ Wed Oct 25 2023 05:17:54 GMT+0000 (Coordinated Universal Time)
</details>

<!--
{"environment":{"platform":"linux","arch":"x64","cpus":2,"totalMemory":6.7597503662109375},"benchmarks":[{"name":"new Date().getTime()","opsSec":7347548.065973262,"samples":5},{"name":"Date.now()","opsSec":15420928.031221354,"samples":6}]}-->