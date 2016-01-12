##Hubot with slack adapter running on docker

ImageLayers : [![](https://badge.imagelayers.io/camil/hubot:latest.svg)](https://imagelayers.io/?images=camil/hubot:latest)

Source:[https://github.com/camilb/docker-hubot-slack](https://github.com/camilb/docker-hubot-slack)

###Use


	docker pull camil/hubot
	
	docker run --name=hubot -d \
	-e 'HUBOT_SLACK_TOKEN=xxx-12345-xxxx' \ 
	camil/hubot
	
###Connect with Redmine Example

	docker run --name=hubot -d \
	-e HUBOT_REDMINE_SSL=1 \
	-e HUBOT_REDMINE_BASE_URL='https://redmine.example.com' \
	-e HUBOT_REDMINE_TOKEN='xxxxxxxxxxxxxxxxxxxxxxxxxxx' \ 
	-e 'HUBOT_SLACK_TOKEN=xxx-12345-xxxx' camil/hubot
