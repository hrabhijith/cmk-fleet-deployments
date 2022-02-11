export INSTALL_K3S_VERSION="v1.19.1+k3s1"
export K3S_NODE_NAME="alderlake"
export K3S_TOKEN="K10a14508c44ca9d213ab5fb9d9bfea56321fc68b9abcbc1f0378d387e0f3353145::server:b1cd2dd54cbd360adee4da946fe78444"
curl -sfL https://get.k3s.io | sh -s - agent --server https://10.62.226.108:6443
