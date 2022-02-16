export INSTALL_K3S_VERSION="v1.19.1+k3s1"
export K3S_NODE_NAME="alderlake"
export K3S_TOKEN="K10ad4aef087952b19bfab47effc90f8dd70eb6a346d7d7773b8cfa24a265c7c593::server:f3728d1c2967ecbbdcc571189cdecc86"
curl -sfL https://get.k3s.io | sh -s - agent --server https://10.62.226.108:6443
