# TRAKT TR-900m by API

[## Overview]

## Requirements

Zabbix server version 6.0 or higher.

## Tested version

Not yet. But ToDo.

### Macros used

|Name|Description|Default|
|----|-----------|-------|
|{$AESIN_STATE}|<p>Expected AES input state</p>|`1`(true)|
|{$ANALOGIN_STATE}|<p>Expected Analog input state</p>|`1`(true)|
|{$API_PORT}|<p>The TCP port that the REST API runs on</p>|`8919`|
|{$FMPRESET_NAME}|<p>Sets the name of the desired preset FM processing</p>|``(not set)|
|{$PLAYERMODE_STATE}|<p>Expected value of PlayerMode</p>|`0`(Auto)|
|{$REDU_STATUS_SA}|<p>Expected redundancy status for ServerA</p>|`1`(Active)|
|{$REDU_STATUS_SB}|<p>Expected redundancy status for ServerB</p>|`1`(Active)|
|{$TR_ROOT_CAP_CRIT}|<p>The value of critical filling of the root partition (%)</p>|`90`|
|{$TR_ROOT_CAP_WARN}|<p>The value of the root partition filling warning (%)</p>|`80`|
|{$TR_SSD_CAP_CRIT}|<p>The importance of critical SSD overflow (%)</p>|`90`|
|{$TR_SSD_CAP_WARN}|<p>The value of the SSD overflow warning (%)</p>|`80`|
|{$TR_TEMP_CRIT_CPU}|<p>Critical value of CPU temperature Celsuis</p>|`70`|
|{$TR_TEMP_WARN_CPU}|<p>The value of the temperature warning about overheating of the CPU Celsuis</p>|`50`|
|{$TR_TEMP_CRIT_GPU}|<p>Critical value of GPU temperature Celsuis</p>|`70`|
|{$TR_TEMP_WARN_GPU}|<p>The value of the temperature warning about overheating of the GPU Celsuis</p>|`50`|
|{$TR_MEMORY_UTIL_MAX}|<p>This macro is used as a threshold in the memory utilization trigger.</p>|`90`|
|{$TR_SWAP_PFREE_MIN_WARN}|<p>This macro is used as a threshold in the swap utilization trigger.</p>|`50`|
