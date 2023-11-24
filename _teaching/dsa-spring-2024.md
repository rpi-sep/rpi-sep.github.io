---
layout: widelayout
page.sidebar: false
title: "CSCI 4510/6510 - Distributed Systems and Algorithms"
permalink: /teaching/dsa-fall-2024
---


## General Information
**Instructor:** Stacy Patterson (sep@cs.rpi.edu)

**Lectures:** MR 12pm - 1:50pm

**Instructor Office Hours:**  TBD

## Course Description
This course explores the principles of distributed systems, 
emphasizing fundamental issues underlying the design of such systems: 
communication, coordination, synchronization, and fault-tolerance. 
We will study key algorithms and theoretical results
and explore how these foundations play out in modern systems and applications 
like cloud computing, edge computing, and peer-to-peer systems.

- [Course Syllabus](#)
- [Gradescope](https://www.gradescope.com/) (for quiz grades)
- [Submitty](https://submitty.cs.rpi.edu/) (for course materials, discussion forum, and projects)

## Projects
The projects will be evaluated using Submitty's autograding feature for networked applications. 
Submitty uses Docker to deploy and test your application. It is not necessary for you to use 
Docker to test your code, but it is a good idea. Below are instructions for configuring and using Docker, 
as well as instructions for replicating the Submitty test environment on your own machine. 
See the Project 1 description for more information on how to configure your projects.

- [Basic instructions](dsa/docker_info.html) for working Docker containers and networks.
- Submitty provides a [tool](https://github.com/Submitty/StudentTools/tree/main/network_generator) to automatically create Docker containers and the Docker Network, and to deploy your code to these containers. The solution_directory should be your bin directory (after running build.sh), and replace submittyrpi/csci4510:default with the name of the container image for this class.
- Example [knownhosts.json](dsa/knownhosts.json) file
- Examples projects with build.sh and run.sh scripts: [Python](dsa/python.zip)   [Java](java.zip)

### Project 1
- Project Specification
- Autograding Public Tests
 - Java tutorial for UDP echo client/server
 - Python tutorial for UDP client/server - This tutorial is not for an echo server, but the example code can be easily modified to work as an echo server.

### Papers and Readings
Some papers are behind a pay wall and can only be accessed from the RPI network.

- [Time, clocks, and the ordering of events in a distributed system](https://www.microsoft.com/en-us/research/publication/time-clocks-ordering-events-distributed-system/), Leslie Lamport, Communications of the ACM, 1978.


