# ros2-talker-listener-lan
The simplest demo showing how to connect two ROS 2 machines in the same LAN

## Quick Start

Connect two computers to the same LAN

### 1st machine

```
docker compose -f compose.talker.yaml up
```

### 2nd machine

```
docker compose -f compose.listener.yaml up
```