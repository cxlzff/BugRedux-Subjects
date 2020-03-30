allfile: allfile.o
	cc -o allfile allfile.o
	ln allfile gzip

allfile.o: allfile.c crypt.h getopt.h gzip.h lzw.h revision.h tailor.h
	cc -c -DSTDC_HEADERS=1 -DHAVE_UNISTD_H=1 -DDIRENT=1 -DHAVE_ALLOCA_H=1 -DFAULTY_F_KL_1 allfile.c

clean:
	rm -f allfile.o allfile allfile.c.inst.exe allfile.int.c gzip

all: clean allfile
build: all
