[![License badge](https://img.shields.io/badge/license-Apache2-orange.svg)](http://www.apache.org/licenses/LICENSE-2.0)


Copyright © 2013-2016 [Kurento]. Licensed under [Apache 2.0 License].

Modified for use in a web conference system by 
students of Reutlingen University

This system is designed to replace the accelerator at Reutlingen University, taking its place as a webconference tool including audio comms, video transcieving and screen sharing, as well as a text chat.

This project will continue to evolve over the coming semesters


Prerequisites:
Ubuntu 14.4 Trusty Tahr
Kurento Media Server 6
OpenJDK 7

How to run:
1) Make sure Apache Maven is installed
2) Clone the repository
3) Navigate your bash to the projects folder (audiovideo_conftool)
4) Execute "mvn compile", wait for the process to finish
5) Finally execute mvn "exec:java" (if the application crashes, the server is likely not running,
verify this using the service command and start it if neccessary)
6) Connect to it using your web browser
