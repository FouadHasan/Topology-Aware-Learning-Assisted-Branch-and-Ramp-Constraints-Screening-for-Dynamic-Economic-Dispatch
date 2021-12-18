# Topology-Aware-Learning-Assisted-Branch-and-Ramp-Constraints-Screening-for-Dynamic-Economic-Dispatch
# keywords—Dynamic economic dispatch, branch and ramp constraints, topology change, constraint classification.
Multi-interval or dynamic economic dispatch (D-ED) is
the core of various power system management functions. This
optimization problem contains many constraints, a small subset of
which is sufficient to enclose the D-ED feasible region. This paper
presents a topology-aware learning-aided iterative constraint
screening algorithm to identify a feasibility outlining subset of
network and generating units ramp up/down constraints and
create a truncated D-ED problem. We create a colorful image
from nodal demand, thermal unit generation cost, and network
topology information. Convolutional neural networks are trained
for constraint status identification using colorful images
corresponding to system operating conditions and transfer
learning. Filtering inactive line flow and ramp up/down
constraints reduces optimization’s size and computational burden,
resulting in a reduction in solution time and memory usage.
Dropping all inactive branch and ramp constraints may activate
some of these originally inactive constraints upon solving the
truncated D-ED. A loop is added to form a constraints coefficient
matrix iteratively during training dataset preparation and
algorithm utilization. This iterative loop guarantees truncated DED results feasibility and optimality. Numerical results show the
proposed algorithm’s effectiveness in constraint status prediction
and reducing the size and solution time of D-ED
