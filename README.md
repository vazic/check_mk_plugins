check_mk_plugins
================

Various Nagios check_mk plugins for snmp-related checks



Juniper SRX plugin
================
- number of sessions
 show snmp mib walk jnxJsSPUMonitoringMIB 
jnxJsSPUMonitoringFPCIndex.1 = 1
jnxJsSPUMonitoringFPCIndex.9 = 1
jnxJsSPUMonitoringSPUIndex.1 = 0
jnxJsSPUMonitoringSPUIndex.9 = 0
jnxJsSPUMonitoringCPUUsage.1 = 0
jnxJsSPUMonitoringCPUUsage.9 = 0
jnxJsSPUMonitoringMemoryUsage.1 = 49
jnxJsSPUMonitoringMemoryUsage.9 = 49
jnxJsSPUMonitoringCurrentFlowSession.1 = 272
jnxJsSPUMonitoringCurrentFlowSession.9 = 229
jnxJsSPUMonitoringMaxFlowSession.1 = 524288
jnxJsSPUMonitoringMaxFlowSession.9 = 524288
jnxJsSPUMonitoringCurrentCPSession.1 = 270
jnxJsSPUMonitoringCurrentCPSession.9 = 222
jnxJsSPUMonitoringMaxCPSession.1 = 1048576
jnxJsSPUMonitoringMaxCPSession.9 = 1048576
jnxJsSPUMonitoringNodeIndex.1 = 0
jnxJsSPUMonitoringNodeIndex.9 = 1
jnxJsSPUMonitoringNodeDescr.1 = node0
jnxJsSPUMonitoringNodeDescr.9 = node1
jnxJsSPUMonitoringCurrentTotalSession.0 = 270
jnxJsSPUMonitoringMaxTotalSession.0 = 524288
jnxJsClusterMonitoringNodeIndex.0 = 0
jnxJsClusterMonitoringNodeIndex.1 = 1
jnxJsClusterMonitoringNodeDescr.0 = node0
jnxJsClusterMonitoringNodeDescr.1 = node1
jnxJsNodeCurrentTotalSession.0 = 270
jnxJsNodeCurrentTotalSession.1 = 222
jnxJsNodeMaxTotalSession.0 = 524288
jnxJsNodeMaxTotalSession.1 = 524288
jnxJsNodeSessionCreationPerSecond.0 = 5
jnxJsNodeSessionCreationPerSecond.1 = 0

- ssl related throughput
- nuymbers for VPN
locate st* interfaces and use their data
- alerts on license expiration
N/A
- IDP monitor:
.1.3.6.1.4.1.2636.3.39.1.11.1.1.1.0  6
.1.3.6.1.4.1.2636.3.39.1.11.1.1.2.0  0
.1.3.6.1.4.1.2636.3.39.1.11.1.1.3.0  131072
.1.3.6.1.4.1.2636.3.39.1.11.1.1.4.0  2
.1.3.6.1.4.1.2636.3.39.1.11.1.1.5.0  0
.1.3.6.1.4.1.2636.3.39.1.11.1.1.6.0  ""


