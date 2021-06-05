Docker image for AutoSub (bootstrap bill version from BenjV)

````docker run -d -i -t \
	--name autosub \
	-p 9960:9960 \
	--restart=unless-stopped \
	-v /path/to/series:/series \
	bechrissed/autosub-docker````
