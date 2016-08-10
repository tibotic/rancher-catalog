
FROM svlentink/pokemongo-bot:stable
ADD https://raw.githubusercontent.com/tasanakorn/rancher-catalog/master/templates/pokemongo-bot/1/configs/config.json /usr/src/app/configs/config.json
ADD https://raw.githubusercontent.com/tasanakorn/rancher-catalog/master/templates/pokemongo-bot/1/docker-entrypoint.sh /usr/src/app/docker-entrypoint.sh
ENTRYPOINT ["./docker-entrypoint.sh"]
EXPOSE 4000