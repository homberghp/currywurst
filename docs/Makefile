

all: index.html


%.html: %.adoc
	asciidoctorj \
             -a linkcss -a stylesheet=css/asciidoctor.css $<

index.html: index.adoc css/*.css *.adoc # hardproblems.adoc rules.adoc teaching.adoc badpractices.adoc

clean:
	rm -f index.html
