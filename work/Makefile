all:
	vasmm68k_mot -Fhunkexe -nosym -ldots -no-opt -wfail -o ./oracle rawdecompresseddata.asm


	vasmm68k_mot -devpac -nocase -Fhunk   -o ./oracle.o ./rawdecompresseddata.asm
	vlink -bamigahunk -o ./oracle13 -s  ./oracle.o