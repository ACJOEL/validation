build :
	hugo
post : joel
	hugo new posts/$(POST_NAME).md
clean :
	rm -rf ./dist/*
joel :
	echo -e "---\ntitle:\"$(POST_TITLE)\"\ndate: {{ .Date }}\ndraft: true\n---">>./archetypes/posts.md
help : ## Show this help usage
	echo "help: Show this help usage"
