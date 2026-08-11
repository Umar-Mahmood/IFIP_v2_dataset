# NetPolAgent Dataset

2,310 Kubernetes `NetworkPolicy` intents across six classes (Reachability,
Isolation, NamespaceSelector, CombinedIngressEgress, MultiPort,
MultiLabelSelector).

- `kubernetes_policies.csv` — 1,410-row base dataset (Reachability,
  Isolation), derived from the NetConfEval/Config2Spec network-specification
  dataset and augmented with Kubernetes-specific fields
- `kubernetes_policies_v2.csv` — 900-row extension (150 rows per class
  across all six classes)
- `ground_truth_yaml/` — verified `NetworkPolicy` YAML for each row in
  `kubernetes_policies.csv`, produced by a large-model pipeline
  configuration and confirmed passing on a live cluster

## Code

https://github.com/Umar-Mahmood/IFIP_v2
# IFIP_v2_dataset
