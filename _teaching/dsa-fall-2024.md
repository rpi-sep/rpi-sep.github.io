---
layout: widelayout
page.sidebar: false
title: "CSCI 4510/6510: Distributed Systems and Algorithms"
permalink: /teaching/dsa-fall-2024
---


## General Information
**Instructor:** Stacy Patterson (sep@cs.rpi.edu)  
**Instructor Office Hours:**  T 1pm - 3pm in Lally 301

**TA:** Michael Zuo (zuom@rpi.edu)   
**TA Office Hours:** T 3pm-4pm in Amos Eaton 118, W 11am - 1pm in Lally 02

**Lectures:** MR 12pm - 1:50pm

## Course Description
This course explores the principles of distributed systems, 
emphasizing fundamental issues underlying the design of such systems: 
communication, coordination, synchronization, and fault-tolerance. 
We will study key algorithms and theoretical results
and explore how these foundations play out in modern systems and applications 
like cloud computing, edge computing, and peer-to-peer systems.
- [Course Syllabus](/files/dsa_f24_syllabus.pdf)
- [Gradescope](https://www.gradescope.com/) (for quiz grades and written homework submission)
- [Submitty](https://submitty.cs.rpi.edu/) (for course materials, discussion forum, and coding homework submission)

## Quiz Schedule
Quizzes will be held during the scheduled lecture time.
- Quiz 1: Thursday 9/12/24
- Quiz 2: Monday 9/30/24
- Quiz 3: Monday 10/21/24
- Quiz 4: Monday 11/11/24
- Quiz 5: Thursday 12/5/24
             
## Review Problems
- Part 1: [Questions](https://submitty.cs.rpi.edu/courses/f24/csci4510/course_material/review/ReviewQuestionsPart1.pdf) [Solutions](https://submitty.cs.rpi.edu/courses/f24/csci4510/course_material/review/ReviewSolutionsPart1.pdf)

## Homework
The coding homework will be evaluated using Submitty's autograding feature for networked applications. 
Submitty uses Docker to deploy and test your application. It is not necessary for you to use 
Docker to test your code, but it is a good idea. Below are instructions for configuring and using Docker, 
as well as instructions for replicating the Submitty test environment on your own machine.  
- [Basic instructions](https://docs.google.com/document/d/e/2PACX-1vTzW9hN_boFWx7kf3agpkSVFWdt8tTanaCLjKZlzh9uQgXi7Wok3DA3BeoAiUXO53zGb6wxsFwLgwiB/pub) for working Docker containers and networks.
- Submitty provides a [tool](https://github.com/Submitty/StudentTools/tree/main/network_generator) to automatically create Docker containers and the Docker Network, and to deploy your code to these containers. The solution_directory should be your bin directory (after running build.sh), and replace submittyrpi/csci4510:default with  submittyrpi/csci4510:spring24_java
- Example [knownhosts.json](/files/f24/knownhosts.json) file
- Examples project skeletons with build.sh for compilation and run.sh to run code: [Java](/files/java.zip) [Python](/files/python.zip)  [Go](/files/go.zip) [Rust](/files/rust.zip)

**Homework 1 (due September 19, 2024)**
- [Code Specification](https://docs.google.com/document/d/1D04U6FFLJGgf3xUeZZFk7_R2Sqaxnz4fPFgF3SQfD3I/pub)
- [Problem Set](https://submitty.cs.rpi.edu/courses/f24/csci4510/course_material/homework/hw1_problems.pdf)
- [Description of Submitty Public Test Cases](https://docs.google.com/document/d/1WGtLD2P2xTws_bLa-w4zn_7oKq9EN1E_kv13CQr6Eos/pub)
  
## Papers and Readings
Some papers are behind a pay wall and can only be accessed from the RPI network.
- [Time, clocks, and the ordering of events in a distributed system](https://www.microsoft.com/en-us/research/publication/time-clocks-ordering-events-distributed-system/), Leslie Lamport, Communications of the ACM, 1978.
- [Efficient solutions to the replicated log and dictionary problems](https://dl.acm.org/doi/10.1145/800222.806750), Gene T.J. Wuu and Arthur J. Bernstein, Proceedings of the third annual ACM symposium on Principles of distributed computing, 1984.
