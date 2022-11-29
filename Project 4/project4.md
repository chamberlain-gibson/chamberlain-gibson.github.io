[Back to Portfolio](/index.md)

Network Namespaces
===============

-   **Network Security** 
-   **100** 
-   **Bash, Linux Commands** 
-   **Source Code Repository:** [Project-4]()  
    (Please [email me](mailto:clgibson@csustudent.net) to request access.)

## Project description
Create two emulated isolated hosts connected together through openVswitch. Setup the indivudal Red and Green Namespaces. Check IP Ling on network ns and install openVswitch. Then, start creating the first bridge with openVswitch through the Veith Pipe Creation. This is how the second bridge will also be created. With this connection we can run "sudo ip link" to see if the bridges were set up correctly.

## How to compile and run the program

How to compile (if applicable) and run the project.

```
Kali Linux Installer for Virtualbox
Linux commands- very similar to Ubuntu BUT slightly different

```
## UI Design

Kali Linux has a very unique design that is extremely different from other virtual machines. To be able to create two separate Linux networking namespaces and send information to each other is the main idea. 
-- Multiple isolated networking environments running on a single physical host or virtual machine.
-- Each network namespace (ns) has its own interfaces, routing tables,
and forwarding tables
-- Processes can be dedicated to one network ns

![screenshot](/images/Network%20Security_2.png)  
Fig 1. Ping command that the Red Namespaces can get information from the Green Namespaces is reachable.

![screenshot](/images/Network%20Security_1.png)  
Fig 2. The "ip a" command shows all the IP Addresses and it demonstrates the Red and Green Namespaces were properly created for the connection. 

![screenshot](/images/Network%20Security_3.png)  
Fig 3. Command to show the display link between the Red Namespaces and Green Namespaces.

## 3. Additional Considerations

Linux commands should be any Cyber Security professional's second language. To be able to use RedHat or Debian is absolutely vital for certain jobs. This can allow any Cyber Security major to potentially consider the CompTIA Linux+ Certification.

[Back to Portfolio](/index.md)