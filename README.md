# Robocop
Robocop is a **prototype** Mixture of Experts (MoE) model with a focus on aiding cybersecurity professionals detect and triage incidents. 

Robocop consists of a centralized, fine tuned Large Language Model which is aided by several classifiers which analyze PCAP files, executables, and various logs commonly found in desktop devices and IoT devices. By aggregating the results of these classifiers across an entire system, Robocop is able to form a comprehensive, global view of a system, thwarting attackers attempts at obfuscation.

Robocop takes automated actions to stop attacks while also preserving logs stored in a non-local database so that human responders can make sense of what happened. Robocop acts as both a Managed Detection Response (MDR) service and an aid to incident handlers. 
