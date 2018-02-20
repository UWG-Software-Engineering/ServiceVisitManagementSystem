# ServiceVisitManagementSystem
Running example for SE2 Spring 2018

# Installation Instructions
## Service Tech Mobile App
1. Install Java 9 (http://www.oracle.com/technetwork/java/javase/downloads/jdk9-downloads-3848520.html)
2. Get Eclipse IDE for Java Developers (http://www.eclipse.org/downloads/eclipse-packages/)
3. Import the Service Tech Mobile App project into Eclipse

## Service Visit Server
1. Install Java 9 (http://www.oracle.com/technetwork/java/javase/downloads/jdk9-downloads-3848520.html)
2. Install Python 3.6+ (https://www.python.org/downloads/)
3. Get Eclipse IDE for Java Developers (http://www.eclipse.org/downloads/eclipse-packages/)
4. Install PyDev (within Eclipse select help->Eclipse MarketPlace, then search for and install PyDev)
5. Install ZeroMQ 4.0.4 (http://zeromq.org/intro:get-the-software)
6. Install the Python bindings for ZeroMQ (from cmd line 'pip install pyzmq' OR see http://zeromq.org/bindings:python for more instructions)
7. Import the Service Visit Server Project into Eclipse
8. (optional) Import the ZeroMQ Samples project into Eclipse
  
NOTE: You may need to specify zmq as a builtin to avoid Eclipse indicating (false-positive) build errors due to failing to find certain zmq items (e.g., zmq.REQ). Within Eclipse select Window->Preferences->PyDev->Interpreters->Python Interpreter->Forced Builtins->New and add zmq.
