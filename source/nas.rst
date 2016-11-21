Network Adaptation Service
==========================

The NAS manages the high-level network processor unit (NPU) abstraction and adaptation. The NAS abstracts and aggregates the core functionality required for networking access at Layer 1 (physical layer), Layer 2 (VLAN, link aggregation), Layer 3 (routing), ACL, QoS, and network monitoring.

The NAS enables adaptation of the low-level switch abstraction provided by the switch abstraction interface (SAI) for standard Linux networking APIs and interfaces, and SONiC-specific object library API functionality.

The NAS is also responsible for providing packet I/O services, using the Linux kernel IP stack.
