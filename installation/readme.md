


## ToDo 

# Change cmd git

    # - name: Tear down existing services
    #   community.general.docker_compose:
    #     project_src: ~/mssoftware/main/homepage
    #     state: absent

    # - name: Create and start services
    #   community.general.docker_compose:
    #     project_src: ~/mssoftware/main/homepage
    #   register: output

    # - ansible.builtin.debug:
    #     var: output

    # - name: Run `docker-compose up` again
    #   community.general.docker_compose:
    #     project_src: ~/mssoftware/main/homepage
    #     build: no
    #   register: output

    # - ansible.builtin.debug:
    #     var: output


# Online Server
    # 147.182.252.105