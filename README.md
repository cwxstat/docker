# docker


docker run --rm -it ubuntu /bin/bash

history
    1  apt-get update
    2  apt-get install kubectl
    3  apt-get install netcat
    4  netcat
    5  curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"
    6  apt-get install curl
    7  history


6  apt-get install curl
    7  history
    8  curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"
    9  install -o root -g root -m 0755 kubectl /usr/local/bin/kubectl
   10  kubectl
   11  kubectl version --client
   12  history


docker commit -m 'Update'  -a 'Mike Chirico' 5541469e936e mchirico/kubectlutils

docker push mchirico/kubectlutils:tagname
