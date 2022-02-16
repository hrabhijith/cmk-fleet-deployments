export INSTALL_K3S_VERSION="v1.19.1+k3s1"
export K3S_NODE_NAME="alderlake"
export K3S_TOKEN="K10d2bcee0640a878e8159383734951bdfca3b67149e07ae5ee563d169339429734::server:d35b6ee1f3307a1b9a73660d6cb07b1b"
curl -sfL https://get.k3s.io | sh -s - agent --server https://10.62.226.108:6443
