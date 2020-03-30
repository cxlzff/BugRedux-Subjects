build:
	cc -o sed -DFAULTY_F_AG_19 sed.c
build-llvm:
	llvm-gcc -o sed.bc -DFAULTY_F_AG_19 -c -emit-llvm sed.c

#build-bt:
#	cfe sed.c
#	il-bt-2 sed.c
#	gcc -g -o sed.int.exe $(COMPILE_PARAMETERS) sed.int.c -I$(ARISTOTLE_DIR)/headers/ -L$(ARISTOTLE_DIR)/lib/sunos5/ -lIPF_bt -lglobalfunc -lm
#	gcc -g -o sed.bt.int.exe $(COMPILE_PARAMETERS) sed.int.c -I$(ARISTOTLE_DIR)/headers/ -L$(ARISTOTLE_DIR)/lib/sunos5/ -lIPF_bt -lglobalfunc -lm

#build-st:
#	cfe sed.c
#	il-st-2 sed.c
#	gcc -g -o sed.st.int.exe $(COMPILE_PARAMETERS) sed.int.c -I$(ARISTOTLE_DIR)/headers/ -L$(ARISTOTLE_DIR)/lib/sunos5/ -lIPF_st -lglobalfunc -lm
#
#clean:
#	rm -f *.o *.exe
#
#clean-bt:	clean
#	rm -f *.int.c

