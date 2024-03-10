## Date toISOString

|name|ops/sec|samples|
|-|-|-|
|new Date().toISOString()|1,484,098|92|
|fromUnixToISOString(new Date())|2,214,258|95|


<details>
<summary>Environment</summary>

* __Machine:__ linux x64 | 4 vCPUs | 15.6GB Mem
* __Run:__ Sun Mar 10 2024 15:43:17 GMT+0000 (Coordinated Universal Time)
</details>

<!--
{"environment":{"platform":"linux","arch":"x64","cpus":4,"totalMemory":15.606491088867188},"benchmarks":[{"name":"new Date().toISOString()","opsSec":1484097.934859333,"samples":4},{"name":"fromUnixToISOString(new Date())","opsSec":2214257.53786107,"samples":6}]}-->