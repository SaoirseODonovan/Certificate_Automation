# Certificate_Automation
Certificates generated as mounted secrets in Kubernetes (K3s) for tls.
integration process, outlining the changes made to link up cert generation script to repo for internal use

pods still not in running state so sectrets have not been created and mounted: next steps for creating a secret, and then to mount: kubectl create secret tls my-tls-secret
--cert=path/to/cert/file
--key=path/to/key/file
