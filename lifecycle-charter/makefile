.PHONY: \
	lifecycle_charter_v1.html \
	lifecycle_charter_v1.pdf

all: \
	lifecycle_charter_v1.html \
	lifecycle_charter_v1.pdf

lifecycle_charter_v1.html: lifecycle_charter.adoc
	asciidoctor -a version=v1 -a hide-uri-scheme -b html5 -d article -o lifecycle_charter_v1.html lifecycle_charter.adoc

lifecycle_charter_v1.pdf: lifecycle_charter.adoc
	asciidoctor -a version=v1 -a hide-uri-scheme -r asciidoctor-pdf -b pdf -d article -o lifecycle_charter_v1.pdf lifecycle_charter.adoc