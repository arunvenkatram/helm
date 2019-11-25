helm install hello-world
helm upgrade helloweb --set image.repository='gcr.io/google-samples/echo-node' hello-world/
helm rollback helloweb 1
helm delete helloweb
