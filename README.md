# DSD_Project_CORBA

This is a robust and resilient system designed to ensure continuous functionality in a distributed theater environment. It consists of three server components, allowing it to keep providing responses even if one server fails.

To improve reliability, the project includes a fault tolerance mechanism that checks the accuracy of responses from each server. This mechanism detects and addresses incorrect or inconsistent responses, ensuring clients receive reliable information.

The implementation incorporates various concepts from distributed systems, such as multicast communication for efficient message distribution, a total order algorithm to maintain message consistency, and the UDP protocol for fast and lightweight server communication.

Additionally, the project employs CORBA (Common Object Request Broker Architecture) for seamless communication between clients and servers. This enables transparent and standardized interactions, simplifying development and integration.

By combining these technologies and concepts, the Distributed Theater High Availability and Software Crash Recovery project achieves a resilient and dependable system that ensures uninterrupted operation, improves fault tolerance, and delivers a smooth experience for both theater management and clients.





