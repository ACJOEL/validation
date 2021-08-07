build : 
	hugo
post : joel
	hugo new posts/$(POST_NAME).md
#clean
clean : # clean
	echo "cleand comment" # clean
joel : 
	echo -e "---\ntitle:\"$(POST_TITLE)\"\ndate: {{ .Date }}\ndraft: true\n---">>./archetypes/posts.md
help : ## help
	
