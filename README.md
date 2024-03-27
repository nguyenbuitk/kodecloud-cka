# kodecloud-cka
## useful command
k run nginx --image nginx:alpine --dry-run=client -oyaml

k replace -f webapp.yaml --force

### check init system
ps -p 1
