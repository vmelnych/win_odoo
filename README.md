# win_odoo

Odoo container configuration for Windows. Docker for Windows must be installed.

1. Copy $env to .env
2. Edit .env to define own secrets
3. start command: docker-compose up -d
4. stop command: docker-compose down
5. copy odoo.conf to c:\docker_storage\odoo\etc
6. addon folders should be stored in c:\docker_storage\odoo\addons
