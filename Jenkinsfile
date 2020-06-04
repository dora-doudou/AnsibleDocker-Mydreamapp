node{
    stage('Clone repository') {
    git 'https://github.com/dora-doudou/AnsibleDocker-Mydreamapp.git'
    
    }
     
    stage('deloy my app docker') {
        sh """
        ansible-playbook deploy_mydreamapp.yml -i hosts.ini -u root
        """
        }
       
    }
