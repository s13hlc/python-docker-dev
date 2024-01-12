# python-docker-dev

A simple Python app for [Docker's Python Language Guide](https://docs.docker.com/language/python).

Once github and docker are configured:
git add -A
git commit -m "my commit"
git push -u origin main OR may have to use git push -f (force)

https://docs.docker.com/desktop/kubernetes/#install-and-turn-on-kubernetes

kubectl config get-contexts
kubectl config use-context docker-desktop
kubectl get nodes
Context List:  
*   crc-admin                                   
    crc-developer 
    docker-desktop
    myproject
    pythontest

    oc expose svc/service-entrypoint -n pythontest
    oc delete route service-entrypoint -n pythontest