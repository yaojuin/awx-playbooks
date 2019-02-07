# awx-playbooks

Windows Machines additional host variables:

ansible_connection: winrm

ansible_winrm_transport: basic (change this to the appropriate type) CredSSP, Kerberos, NTLM, Certificate

ansible_winrm_server_cert_validation: ignore
