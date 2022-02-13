export INSTALL_K3S_VERSION="v1.19.1+k3s1" /
export K3S_NODE_NAME="alderlake" /
export K3S_TOKEN="K1048b6af34fb7b2bb6561b0d226f9da3d755a619697dbdb8a6f9030d78734bbf17::server:6e92be23663bd79adcb28d1110821b49" /
curl -sfL https://get.k3s.io | sh -s - agent --server https://10.62.226.108:6443
