Today I practice Kubernetes Troubelshootin using Statefull-Set

What I learned: 

1. How Statefull-set is working in the enterprise application level.
2. How PVC is wokring.
3. What to do id error show like "default -scheduler 0/1 nodes are available: pod has unbound immediate PVC".


The Workflow how PVC will create

   Stateful-Set--->PVC---->StorageClass---->provision----->PV
