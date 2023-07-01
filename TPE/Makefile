informe:
	docker run --rm -v `pwd`:/pandoc dalibo/pandocker header.yaml README.md --output TPE.pdf
.PHONY: informe

# sudo apt install entr
loop:
	ls README.md header.yaml | entr make informe
.PHONY: loop
