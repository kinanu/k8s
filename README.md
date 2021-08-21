# k8s

curl -O https://raw.githubusercontent.com/kinanu/k8s/main/lets_encrypt_issuer.yaml && sed 's/EMAILADDRESS/YOUREMAIL/g' lets_encrypt_issuer.yaml >> out.yaml
kubectl apply -f out.yaml