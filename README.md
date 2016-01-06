##Hubot with slack adapter running on docker

ImageLayers : [![](https://badge.imagelayers.io/camil/hubot:latest.svg)](https://imagelayers.io/?images=camil/hubot:latest)

Source:[https://github.com/camilb/docker-hubot-slack](https://github.com/camilb/docker-hubot-slack)

###Use


        docker pull camil/hubot
        docker run --name=hubot -d -e 'HUBOT_SLACK_TOKEN=xxx-12345-xxxx' camil/hubot
        