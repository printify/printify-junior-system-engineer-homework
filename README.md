Goal:
Serve a single page application on a Linux server.

Tasks:
- Prepare Vagrant box with Linux server installed
- Deploy https://github.com/Ismaestro/angular8-example-app application
    > It should live under /srv/app folder
- Use Nginx to serve the above application
- Use logrotate to manage Nginx logs of application

All of the above should be automated via shell scripts or other tools.

Bonus Task:
- Ensure that provisioning scripts are idempotent
- Execute script on hourly basis via cron

Deliverables:
- Vagrantfile with accompanying shell and configuration files. Do not send us exported VM.

Expectations:
Single ‘vagrant up’ command will provision Linux server that adheres to the tasks described above.
