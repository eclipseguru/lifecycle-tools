all : \
	lifecycle_charter_v1.html

.PHONY : all

lifecycle_charter_v1.html : lifecycle_charter.adoc
	asciidoctor -a version=v1,stylesheet=charter.css -b html5 -d book -o lifecycle_charter_v1.2.html lifecycle_charter.adoc
