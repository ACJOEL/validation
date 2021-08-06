build : 
	hugo
post : joel
	hugo new posts/$(POST_NAME).md
clean : ##make cleand limpiar dist
	rm -rf ./dist/*
joel : 
	echo -e "---\ntitle:\"$(POST_TITLE)\"\ndate: {{ .Date }}\ndraft: true\n---">>./archetypes/posts.md
help : ## Show this help usage
	@fgrep -h "##" $(MAKEFILE_LIST) | fgrep -v fgrep | sed -e 's/\\$$//' | sed -e 's/##//'
