# ocp-bastion-setup
Configures OCP bastion host for install

## Instructions
Run the following command:
`ansible-playbook prep.yml -b`

## Tasks To Do
- [x] curl and unpack openshift installer
- [x] curl and unpack oc utility
- [x] install jq, vim, httpd 
- [ ] deploy haproxy
- [ ] setup httpd
