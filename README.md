 746  git clone https://github.com/ahmetb/kubectx /opt/kubectx
  747  ln -s /opt/kubectx/kubens /usr/local/bin/kubens
  748  kubens
  749  kubectl
  750  alias
  751  apt-get install -y ca-certificates curl
  752  echo "deb [signed-by=/etc/apt/keyrings/kubernetes-archive-keyring.gpg] https://apt.kubernetes.io/ kubernetes-xenial main" | sudo tee /etc/apt/sources.list.d/kubernetes.list
  753  apt-get install -y kubectl
  754  kubens
  755  exit
  756  pstree
  757  kubens
  758  k3s config
  759  k3s
  760  k3s kubectl config view --raw
  761  history
  762  k3s kubectl config view --raw > $HOME/.kube/config
  763  kubectl

# kustomize
