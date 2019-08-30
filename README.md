# Overview
This charm allows to instantiate mininet wifi simulation framework

# Usage
Charm exposes openflow southbound interface. User can connect openflow SDN controller on standard openflow port.


# Local provider

Once bootstrapped, deploy the Floodlight charm :

    juju deploy cs:~sheenam/mininet-wifi-1

Have a look at what's going on:

    watch juju status --format tabular


