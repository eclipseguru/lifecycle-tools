.PHONY: lifecycle_charter_v1.html

all: \
	lifecycle_charter_v1.html

lifecycle_charter_v1.html: lifecycle_charter.adoc
        asciidoctor -a version=v1 -a hide-uri-scheme -b html5 -d book -o lifecycle_charter_v1.html lifecycle_charter.adoc
