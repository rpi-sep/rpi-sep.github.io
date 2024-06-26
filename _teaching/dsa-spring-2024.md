---
layout: widelayout
page.sidebar: false
title: "CSCI 4510/6510: Distributed Systems and Algorithms"
permalink: /teaching/dsa-spring-2024
---


## General Information
**Instructor:** Stacy Patterson (sep@cs.rpi.edu)  
**Instructor Office Hours:**  T 1pm - 3pm in Lally 301

**TA:** Linh Tran (tranl3@rpi.edu)

**Lectures:** MR 12pm - 1:50pm

## Quiz Schedule
Quizzes will be held during the scheduled lecture time.
- Quiz 1: Thursday 1/25/24
- Quiz 2: Thursday 2/15/24 
- Quiz 3: Thurdsay 3/14/24
- Quiz 4: Monday 4/1/24
- Quiz 5: Thursday 4/18/24

## Course Description
This course explores the principles of distributed systems, 
emphasizing fundamental issues underlying the design of such systems: 
communication, coordination, synchronization, and fault-tolerance. 
We will study key algorithms and theoretical results
and explore how these foundations play out in modern systems and applications 
like cloud computing, edge computing, and peer-to-peer systems.
- [Course Syllabus](/files/dsa_s24_syllabus.pdf)
- [Gradescope](https://www.gradescope.com/) (for quiz grades)
- [Submitty](https://submitty.cs.rpi.edu/) (for course materials, discussion forum, and projects)

## Projects
The projects will be evaluated using Submitty's autograding feature for networked applications. 
Submitty uses Docker to deploy and test your application. It is not necessary for you to use 
Docker to test your code, but it is a good idea. Below are instructions for configuring and using Docker, 
as well as instructions for replicating the Submitty test environment on your own machine. 
See the Project 1 description for more information on how to configure your projects.

- [Basic instructions](https://docs.google.com/document/d/e/2PACX-1vTzW9hN_boFWx7kf3agpkSVFWdt8tTanaCLjKZlzh9uQgXi7Wok3DA3BeoAiUXO53zGb6wxsFwLgwiB/pub) for working Docker containers and networks.
- Submitty provides a [tool](https://github.com/Submitty/StudentTools/tree/main/network_generator) to automatically create Docker containers and the Docker Network, and to deploy your code to these containers. The solution_directory should be your bin directory (after running build.sh), and replace submittyrpi/csci4510:default with the name of the container image for this class.
- Example [knownhosts.json](/files/knownhosts.json) file
- Examples projects with build.sh and run.sh scripts: [Python](/files/python.zip)  [Go](/files/go.zip) [Rust](/files/rust.zip)

**Project 1**
- [Project Specification](https://docs.google.com/document/d/e/2PACX-1vTsU7LS38_2nIjwVgbwtu8xRuYxAAAU0Dov9BuX0CcJqrFrIs06jmlD5X1o3l7Q7rkPXqjvdKksh018/pub)
- [Autograding Public Tests](https://docs.google.com/document/d/e/2PACX-1vTzZlf5YeyxO3XvXM181uN84dCOeztscZ6q9BJPglOimC_DMn8XZ8JNmP3y3yaXl-RSeH1JRt5LqkJ1/pub)
- [Example UDP client/server](https://people.cs.umass.edu/~arun/590CC/lectures/Sockets.pdf)

**Project 2**
- [Project Specifcation](https://docs.google.com/document/d/e/2PACX-1vTToRDbgXjxFk1RbGT6db109FeC7WUhDY6vStm4ybeAWGemZdnwABfb0ZeTeZRdJ6QWVW7Nev28pCaT/pub)
- [Autograding Public Tests](https://docs.google.com/document/d/e/2PACX-1vT3FpQ47yneP9V7RVc-BGpHXna8zp_R1LHNMgJt7qTc2x2jYqshv9WwNfC-jkOdbOXIkp9zmElptMfr/pub)
- [Manual Test Cases](https://docs.google.com/document/d/e/2PACX-1vQQasqStTnuow7pz8V7mASbQTiYvaojBrCnqb7om4pFkYOH2nVa67sWOxpsParq7ui7ksJ9umMydg8U/pub)

**Project 3 (due April 10)**
- [Project Specification](https://docs.google.com/document/d/e/2PACX-1vRXQJEjxtYXY0kAySdQf9xa5oGwmSL05SVcUa0NxWLfhUSuagyXNja2NIacUPIUIDnbjpd7UNb5K8GS/pub)
- [Autograding Public Tests](https://docs.google.com/document/d/e/2PACX-1vTLLydQYvOX4d3IayzIAHd_gAIqSXEPA-wJPeFXMQfmP3OOBgmEmDkBO13cw69XL-xG7_iaTpIr7c-I/pub)
- [Manual Test Cases](https://docs.google.com/document/d/e/2PACX-1vQcMoitW1beSblAtjS4XDMVpJM8k4RjaYrBnft0DdSU9xTTMkKDHCZGxRrFyPxCWZW79q4haAhRLnSh/pub)

**Extra Credit Project (due April 18)**
- [Project Specification](https://docs.google.com/document/d/e/2PACX-1vTYGMB6QG9NcDQsCFba0pm_qx6H5ne3eq9uwhX7gJS8BENz_QzkpVrjb4meuLMk1HVBal_SupHMpJ1r/pub)
  
## Papers and Readings
Some papers are behind a pay wall and can only be accessed from the RPI network.
- [Time, clocks, and the ordering of events in a distributed system](https://www.microsoft.com/en-us/research/publication/time-clocks-ordering-events-distributed-system/), Leslie Lamport, Communications of the ACM, 1978.
- [Efficient solutions to the replicated log and dictionary problems](https://dl.acm.org/doi/10.1145/800222.806750), Gene T.J. Wuu and Arthur J. Bernstein, Proceedings of the third annual ACM symposium on Principles of distributed computing, 1984.
- [A optimal algorithm for mutual exclusion in computer networks](http://dl.acm.org/citation.cfm?id=358537), Glenn Ricart and Ashok K. Agrawala, Communications of the ACM, 1981.
- [A tree-based algorithm for distributed mutual exclusion](https://dl.acm.org/doi/10.1145/58564.59295), Kerry Raymond, ACM Transactions on Computer Systems, 1989.
- [A sqrt(N) algorithm for mutual exclusion in decentralized systems](https://dl.acm.org/doi/10.1145/214438.214445), Mamoru Maekawa, ACM Transactions on Computer Systems, 1985. 
- [The Information Structure of Distributed Mutual Exclusion Algorithms](https://dl.acm.org/doi/10.1145/24068.28052), Beverly Sanders, ACM Transactions on Computer Systems, 1987.
- [Distributed Snapshots: Determining Global States of a Distributed System](https://www.microsoft.com/en-us/research/publication/distributed-snapshots-determining-global-states-distributed-system/), K. Mani Chandy and Leslie Lamport, ACM Transactions on Computer Systems, 1985.
- [Concurrency Control and Recovery in Database Systems](https://www.microsoft.com/en-us/research/people/philbe/book/), Philip A. Bernstein, Vassos Hadzilacos, Nathan Goodman, 1987. 2PC and 3PC are in Chapter 7.
- [The Part-Time Parliament](https://lamport.azurewebsites.net/pubs/lamport-paxos.pdf), Leslie Lamport, ACM Transactions on Computer Systems, 1998.
- [Paxos Made Simple](https://www.microsoft.com/en-us/research/publication/paxos-made-simple/), Leslie Lamport, ACM SIGACT News, 2001.
- [Elections in a Distributed Computing System](https://homepage.divms.uiowa.edu/~ghosh/Bully.pdf), Héctor García-Molina,  IEEE Transactions on Computers, 1982.
- [Impossibility of Distributed Consensus with One Faulty
Process ](https://groups.csail.mit.edu/tds/papers/Lynch/jacm85.pdf), Michael J. Fischer, Nancy A. Lynch, Michael, S. Patterson, Journal of the ACM, 1985.
- [The Byzantine Generals Problem](https://lamport.azurewebsites.net/pubs/byz.pdf), Leslia Lamport, Robert Shostak, and Marshall Pease, ACM Transactions on Programming Languages and Systems, 1982.
- [Foundations of Distributed Consensus and Blockchains](https://www.distributedconsensus.net/), Elaine Shi, 2020.
- [Dynamo: amazon's highly available key-value store](https://dl.acm.org/doi/abs/10.1145/1323293.1294281), Giuseppe DeCandia, Deniz Hastorun, Madan Jampani, Gunavardhan Kakulapati,
Avinash Lakshman, Alex Pilchin, Swaminathan Sivasubramanian, Peter Vosshall
and Werner Vogels, ACM SIGOPS Operating Systems Review, 2007.

## Back Quizzes
These quizzes are provided to give you some idea of the types of questions that may be asked. The specific topics and the order in which they are presented may vary somwhat from year to year.
- Quiz 1: [Questions](https://submitty.cs.rpi.edu/courses/s24/csci4510/course_material/quiz/f20_exam1.pdf) [Solutions](https://submitty.cs.rpi.edu/courses/s24/csci4510/course_material/quiz/f20_exam1_solutions.pdf)
- Quiz 2: [Questions](https://submitty.cs.rpi.edu/courses/s24/csci4510/course_material/quiz/f20_exam2.pdf) [Solutions](https://submitty.cs.rpi.edu/courses/s24/csci4510/course_material/quiz/f20_exam2_solutions.pdf)
- Quiz 3: [Questions](https://submitty.cs.rpi.edu/courses/s24/csci4510/course_material/quiz/f20_exam3.pdf) [Solutions](https://submitty.cs.rpi.edu/courses/s24/csci4510/course_material/quiz/f20_exam3_solutions.pdf)
- Quiz 4: [Questions](https://submitty.cs.rpi.edu/courses/s24/csci4510/course_material/quiz/f20_exam4.pdf) [Solutions](https://submitty.cs.rpi.edu/courses/s24/csci4510/course_material/quiz/f20_exam4_solutions.pdf)
- Quiz 5: [Questions](https://submitty.cs.rpi.edu/courses/s24/csci4510/course_material/quiz/f20_exam5.pdf) [Solutions](https://submitty.cs.rpi.edu/courses/s24/csci4510/course_material/quiz/f20_exam5_solutions.pdf)
  
