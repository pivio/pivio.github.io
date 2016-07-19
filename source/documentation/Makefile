all:
	rm -rf ../../docs/*
	asciidoctor -r asciidoctor-diagram -D ../../docs -a toc -d book index.adoc
clean:
	rm -rf ../../docs/*
publish:
	cd ../../docs
	git add --all *
	git commit -a -m 'New version'
	git push
