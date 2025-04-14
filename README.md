# TML Cyber Threat Monitor

A real-time cybersecurity monitoring solution using Transactional Machine Learning, Docker, Apache Kafka, and PrivateGPT.

## Project Structure

- `docker/`: Contains the Dockerfile and run commands.
- `kafka/`: Kafka topic configurations.
- `screenshots/`: Visual evidence used in analysis.
- `solution/`: Final write-up in PDF format.

## Docker Run Commands

Detailed Docker run commands are available in `docker/run-commands.txt`.

## Dashboard Access

Once the containers are running, access the real-time dashboard at:
[http://localhost:9000/tml-cisco-network-privategpt-monitor.html?topic=cisco-network-preprocess,cisco-network-privategpt&offset=-1&groupid=&rollbackoffset=150&topictype=prediction&append=0&secure=1](http://localhost:9000/tml-cisco-network-privategpt-monitor.html?topic=cisco-network-preprocess,cisco-network-privategpt&offset=-1&groupid=&
## Cisco Packet Tracer Lab

The `packettracer/` folder includes the full `.pkt` simulation file used to generate synthetic network traffic for testing the cyber threat detection pipeline.

### Contents:
- `tml-hacker-networksecurity-setup v3.pkt`: Main Packet Tracer simulation environment
- `readme.txt`: Description of the simulation setup

Use this `.pkt` file to simulate compromised hosts, ping failures, and varied traffic conditions for live anomaly testing.

To open this file, use **Cisco Packet Tracer v8.2 or later**.
