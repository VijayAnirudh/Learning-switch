# Learning-switch

This is the upgraded version of forwarder or act_like_hub. The main job of learning switch is to know the source and destination of a packet and their ports and do the appropriate action. This learning switch populates the source address and incoming port into a dictionary as key:value pair, same goes with the destination address and out port. After populating them, if the destination and its port is know it will send the packet and installs a flow mod into the switch conccurrently or else floods the packet to every port except the incoming.
