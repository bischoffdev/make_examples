final.txt: dependency.txt
	echo "This is the final file!" > final.txt
	cat dependency.txt >> final.txt

dependency.txt: clean
	echo "Hello world" > dependency.txt

.PHONY: clean
clean:
	rm -f dependency.txt
	rm -f final.txt
