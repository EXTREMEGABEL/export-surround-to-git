TARGET = sscmhist.exe
LIBS = sscmapi.lib
CC = cl
INLCUDE_PATH = "C:\Program Files\Perforce\Surround SCM\API\include"
LIB_PATH = "C:\Program Files\Perforce\Surround SCM\API\lib64"

all: sscmhist

sscmhist:
	$(CC) /Fe:$(TARGET) /I $(INLCUDE_PATH) sscmhist.c $(LIBS) /link /LIBPATH:$(LIB_PATH)
