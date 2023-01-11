# Setup

<b>1. Copy files</b>
Copy the docker-compose.yml and mailserver.env files to a directory.

<b>2. Edit docker-compose.yml</b>
Edit the 6th line (domainname: franciscorego.local) to whichever domain you want.

<b>3. Deploy the containers</b>
docker compose up

<b>4. Create a admin account</b>
docker exec -it mailserver setup email add admin@franciscorego.local

# Notes

user: admin@franciscorego.local
pass: ...
