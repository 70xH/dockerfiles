#
# podman run --rm \
# 	 -it \
#	 -v ${PWD}/hosts:/etc/ansible/hosts \
# 	 -v ${PWD}/ansible.cfg:/etc/ansible/ansible.cfg \
# 	 -v ${HOME}/.ssh:/root/.ssh:ro \
#	 ansible all -m ping
#
FROM ansible

RUN python3 -m pip install ansible

ENTRYPOINT [ "ansible" ]

