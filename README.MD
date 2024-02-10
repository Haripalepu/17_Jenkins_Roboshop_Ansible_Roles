Earlier the ansible was downloading the application code/package from S3. 
Now we have to configure it to download the artifact from Nexus repo.
Download specific version. 
So we need to give Nexus location and artifact version so we have to do the change in playbook.
From terraform we should send the artifact version to ansible.

Go to Roles-common-tasks-app_tasks.yml