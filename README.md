Attempting to package loomio for runtipi

# TODO
- [] Incorporate updating: `docker system prune -a -f && docker compose pull && docker compose down && docker compose run app rake db:migrate && docker compose down && docker compose up -d --remove-orphans`