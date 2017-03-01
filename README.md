# OPNFV-ODL-SFC
This is a repository for K-ONE OPNFV Subtask 2 (OPNFV#2-2) that aims to develop Integrated Forwarding Graph (IFG) construction framework.

# Load and Path-Aware SF Selection Algorithm in OpenDaylight Service Function Chaining
In Figure 1, it is shown that the proposed load/path-aware SF selection algorithm is running within the SFC plugin of ODL. The creation procedures for service function chain (SFC) which consists of an ordered list of abstract SF types are shown with the dashed lines. Network administrators store the SFC (i.e., textsfSFC1) into the model-driven service ab- straction layer (MD-SAL) datastore via RESTCONF protocol. The SFC plugin gets notified with the created SFC and the load/path-aware SF selection algorithm takes the SFC as an input.
