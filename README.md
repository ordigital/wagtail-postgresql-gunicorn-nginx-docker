# Wagtail + PostgreSQL + Gunicorn + Nginx

1. Download repository: `git clone git@github.com:ordigital/wagtail-postgresql-gunicorn-nginx-docker.git`
2. Create `.dev`, `.dev.db`, `.prod` and `.prod.db` config files in `env/` folder (you can rename and edit sample files)
3. Make `wag` file executable: `chmod +x ./wag`
4. Use: `./wag` to stop, build and start developement server (Django internal server on port 8000) and `./wag prod` to stop, build and start production server (with gunicorn and nginx proxy on port 8000)
