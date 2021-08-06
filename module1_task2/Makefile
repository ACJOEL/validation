build :
	hugo
post : joel
	hugo new posts/$(POST_NAME).md
clean : #### limpiar el directorio dist
	@rm -rf ./dist/* ##limpia
joel : ## crear
	echo -e "---\ntitle:\"$(POST_TITLE)\"\ndate: {{ .Date }}\ndraft: true\n---">>./archetypes/posts.md
help : ## Show this help usage
	@fgrep -h "##" $(MAKEFILE_LIST) | fgrep -v fgrep | sed -e 's/\\$$//' | sed -e 's/##//'
post : ## crear post
