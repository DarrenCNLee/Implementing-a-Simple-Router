In the previous lab you implemented a simple firewall that allowed ARP and TCP packets, but blocked all other
packets. For your final project, you will be expanding on this to implement routing between devices on different
subnets and implementing firewalls for certain subnets. The idea is to simulate an actual production network.
You will be using ideas from Lab 1 to help construct the mininet topology, and ideas from Lab 3 to implement
the rules allowing for traffic to flow through your network. Please refer back to those Labs for guidance on how
to complete this assignment.

Assignment:
For this lab, we will be constructing a network for a small company. The company has a 2-floor building, with
each floor having its own switches and subnets. Additionally, we have a switch and subnet for all the servers in
the data center, and a core switch connecting everything together

Files:
project.pdf - Contains my project report with the
screenshots for the commands that I ran to test my code and explanations
for the command outputs
final_skel.py - Contains my code for the mininet topology
finalcontroller_skel.py - Contains my code for the mininet controller
