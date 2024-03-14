# Robocop
Robocop is a **prototype** intrusion detection system (IDS) with automated incident
triage capabilities. 

Robocop's core detection system is an Ensemble method -- a collection of machine 
learning methods that aggregate their predictions and coordinate to
analyze network traffic and keep the bad guys out. 

At the base there are several anomaly detectors monitoring the network
and processes for anomalous traffic. If anything out of the ordinary is
found, the suspicious activity is then passed to a more specialized
classifier model to figure out what exactly is going on. Then the
results of this model, along with metadata about the traffic are passed
to an Agentic Large Language Model that creates a report for incident
handlers and takes steps to counteract the detected attack (e.g. closing
ports, killing processes, backing up data, etc.)
