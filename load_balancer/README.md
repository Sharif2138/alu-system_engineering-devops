Web Server Redundancy Project
Background
This project aims to improve a web stack by adding redundancy with two web servers (web-01 and web-02) and a load balancer (lb-01). The goal is to:

Increase traffic handling capacity.
Ensure high availability by automatically redirecting traffic if one server fails.
Requirements
Operating System: Ubuntu 16.04 LTS
Editors Allowed: vi, vim, emacs
File Requirements:
All Bash scripts must be executable.
Scripts must pass Shellcheck (version 0.3.7) with no errors.
The first line of scripts should be #!/usr/bin/env bash.
The second line should describe the script’s purpose.
Tasks
Set up Load Balancer: Configure HAProxy on lb-01 to distribute traffic between web-01 and web-02.
Configure Web Servers: Set up web-02 to mirror the configuration of web-01.
Health Checks: Implement checks on lb-01 to ensure traffic is sent only to healthy servers.
Structure
Bash Scripts: Automate server setup and configuration.
README.md: Provides instructions for setting up the environment.

