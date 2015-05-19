# Cron Backup Docker
This docker container provides a cron job which backups a volume and uploads it to a GitHub repository.

## Usage instructions

	docker run -d -e GITREPO='<ssh clone url>' -v '<.shh directory>:/root/.ssh' -v '<backup 		directory>':/var/lib/cron-backup-docker


