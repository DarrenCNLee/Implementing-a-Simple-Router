Implements routing between devices on different
subnets and firewalls for certain subnets. The idea is to simulate an actual production network.
Constructs a Mininet topology, and implements
the rules allowing for traffic to flow through the network.

We will be constructing a network for a small company. The company has a 2-floor building, with
each floor having its own switches and subnets. Additionally, we have a switch and subnet for all the servers in
the data center, and a core switch connecting everything together.

Files:

project.pdf - Contains my project report with the
screenshots for the commands that I ran to test my code and explanations
for the command outputs

final_skel.py - Contains my code for the mininet topology

finalcontroller_skel.py - Contains my code for the mininet controller
