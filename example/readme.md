### Deploy VM
`ansible-playbook -i 'localhost,' k8s.yml --tag=deploy_vm --extra-vars "@example/vars.json" --ask-vault-pass`

ansible-playbook -i '172.16.20.22,' k8s.yml --tag=k8s_env -e '{"version":"1.18.0-0"}' -k --vault-password-file secret