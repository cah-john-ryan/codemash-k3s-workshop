# Getting Started

## k3d (Docker)

1. DONE - Install OpenLens, https://github.com/MuhammedKalkan/OpenLens
```shell
brew install --cask openlens
```
2. DONE - Install k3d (https://github.com/k3d-io/k3d/releases)
```shell
brew install k3d
```
3. DONE - Create 2 node cluster
```shell
k3d cluster create codemash --agents 2 -p "8081:80@loadbalancer"
```
4. Launch OpenLens
5. Select Catalog from the left-hand pane
6. Hovered over the k3d-codemash cluster and click the Pin icon to add it to the left-hand pane



## OpenLens

1. Install OpenLens (https://github.com/MuhammedKalkan/OpenLens)
2. Open OpenLens and go to File > Extensions
3. Install **@alebcay/openlens-node-pod-menu** extension from https://github.com/alebcay/openlens-node-pod-menu
4. Re-open OpenLens and go to File > Extensions
5. Enable the **@alebcay/openlens-node-pod-menu** extension




