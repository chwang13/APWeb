all:
	@echo "Generating embedded.c"
	@./embed.py *.html images/*.svg */*.js */*.json */*.css */*.jpg */*.bmp */*.png */*.mjpg data/*.xml data/*.parm
	@echo "Generating manifest"
	@./gen_manifest.sh
	@echo "Generating version.h"
	@./gen_version.sh

