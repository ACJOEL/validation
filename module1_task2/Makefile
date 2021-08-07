build : 
	hugo
post : joel
	hugo new posts/$(POST_NAME).md
clean : 
	echo "cleand comment"
joel : 
	echo -e "---\ntitle:\"$(POST_TITLE)\"\ndate: {{ .Date }}\ndraft: true\n---">>./archetypes/posts.md
help : ## help
	
