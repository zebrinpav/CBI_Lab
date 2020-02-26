Objective
In this lab, you will use the data collected by a statistical debugging tool, Cooperative Bug
Isolation (CBI) to identify and report bugs in Linux applications. CBI exploits the size of user
communities to identify bugs in real-world runs of an application by using a random sampling
method to instrument application code, collect data about failures, and isolate the cause of a wide
variety of bugs.
On a small program and a large program called ​jpegtran​, you will do the following things:
1) Run a program multiple times (to simulate real-world runs of the application by the user
community)
2) Generate CBI reports using the runs
3) Locate and inspect bugs
