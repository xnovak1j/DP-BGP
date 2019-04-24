# README #

### OMNeT++/INET BGPv4 protocol###

* BGPv4 with multi address-family support in OMNeT++ simulator 
* Version - bgpv4

### Version ###
* OMNeT++ 5.4.1
* INET 4.0

### Setup ###
* Install correct OMNeT++ IDE (https://omnetpp.org/download/)
* Download this project and import it to OMNeT++

### Changelog ###
* BGP Update message creation - more address prefixes can be added to the message
* BGP Update message processing - router can process more NLRI prefixes from the message
* Connect Retry Timer is correctly finished
* FSM - updated some states of finish state automat
* Multi address-family support (IPv4 and IPv6)
* Link failure reaction and reconnection
* Correct sending of BGP Update message on the iBGP multipoint segment
* Existence of iBGP peerings is independent on eBGP peerings

### Simulation examples ###
* Examples are available in directory: inet4/examples/bgpv4


