# IP ranges assignments

## VLANs
ID | IP/Range     | Name | Notes
---|--------------|------|---------
10 | single ip    | external | Provided by ???
20 | 10.20.0.0/24 | mgmt |
21 | 10.21.0.0/22 | wired | wired clients / workshop
22 | 10.22.0.0/22 | wireless | ap
23 | 10.23.0.0/24 | video | video team
24 | 10.24.0.0/24 | overflow | overflow TV's
25 | 10.25.0.0/24 | reception | Reception related

## Assignments

### MGMT
IP  | Name    | Notes
----|---------|------
.1  | CORESRV | router/services
.11 | coresw  | CORE

### Wifi
IP  | Name    | Notes
--- |---------|------
.50 | ap-fl     | ap conf floor left foaier
.51 | ap-fr     | ap conf floor right foaier
.52 | ap-voc-a1 | ap room A stage
.53 | ap-voc-a2 | ap room A back
.54 | ap-voc-b  | ap room B stage
.55 | ap-ws-c   | ap room C zone C3
.56 | ap-team   | ap conf floor chillout area
.57 | ap-ws-l   | ap workshop floor workshop area
.58 | ap-ws-r   | ap workshop floor workshop area

### Video
IP | Name    | Notes
---|---------|------
.1 | CORESRV |

### Overflow
IP | Name    | Notes
---|---------|------
.1 | CORESRV |

### Wired
IP | Name    | Notes
---|---------|------
.1 | CORESRV |

### Reception
IP | Name    | Notes
---|---------|------
.1 | CORESRV |
