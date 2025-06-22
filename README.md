# KServe
Kserve agent with check Triton connectivity via same probeContainer
- added param on [startModelPuller](https://github.com/ptishkin/kserve-agent-probe/blob/master/cmd/agent/main.go#L150C28-L150C33)
- check on cycle [results of probe](https://github.com/ptishkin/kserve-agent-probe/blob/master/cmd/agent/main.go#L323)
- added default [repeat interval](https://github.com/ptishkin/kserve-agent-probe/blob/master/cmd/agent/main.go#L353) in probe init function
