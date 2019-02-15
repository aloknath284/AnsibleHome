1.create encrpted password for user and save in .user_pass.yml
	#ansible-vault encrypt_string 'nnath.1234' --name 'nnath_pass' >> roles/BOA_Role/credential/.user_pass.yml
2.Running playbook
	#ansible-playbook runSetup.yml --extra-vars '{"password":"pkakati.1234"}'
