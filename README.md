# Central administration template

This is a basic template to centralize the Linux Administration with ansible-pull

## Requirements

go install the required packages on the client-machines:
    
    ansible-playbook deployansible.yml --ask-pass -i 172.16.80.35,

## Pull request

    ansible-pull -U https://github.com/laenglea/linuxcentralmgt.git -i hosts
