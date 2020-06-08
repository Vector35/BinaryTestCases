all:
	nasm -f elf64 x86_lifting.s
	ld -o x86_lifting x86_lifting.o
	rm x86_lifting.o
	mv x86_lifting ../test_corpus
	rm -f ../test_corpus/x86_lifting.zip