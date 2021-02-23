### Deploy VM
`ansible-playbook -i 'localhost,' k8s.yml --tag=deploy_vm --extra-vars "@example/vars.json"`