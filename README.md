# TRAKT TP-900m by API

[## Overview]

## Requirements

Zabbix server version 6.0 or higher.

## Tested version

Not yet. But ToDo.

### Macros used

|Name|Description|Default|
|----|-----------|-------|
|{$AESIN_STATE}|<p>Expected AES input state (true)</p>|`1`|
|{$ANALOGIN_STATE}|<p>Expected Analog input state (true)</p>|`1`|
|{$API_PORT}|<p>The TCP port that the REST API runs on</p>|`8919`|
|{$FMPRESET_NAME}|<p>Sets the name of the desired preset FM processing</p>|``|
|{$PLAYERMODE_STATE}|<p>Expected value of PlayerMode (Auto)</p>|`0`|
|{$REDU_STATUS_SA}|<p>Expected redundancy status for ServerA (Active))</p>|`1`|
|{$REDU_STATUS_SB}|<p>Expected redundancy status for ServerB (Active)</p>|`1`|
