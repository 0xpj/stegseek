AM_CPPFLAGS = -DLOCALEDIR=\"$(localedir)\"
bin_PROGRAMS = stegseek
noinst_HEADERS = \
AUtils.h Arg.h Arguments.h AssertionFailed.h AuData.h AuFile.h \
AuSampleValues.h AudioData.h AudioSampleValue.h DFSAPHeuristic.h BFSAPHeuristic.h \
BinaryIO.h BitString.h BmpFile.h BmpPaletteSampleValue.h BmpRGBSampleValue.h \
BmpSampleValue.h ColorPalette.h WKSConstructionHeuristic.h Cracker.h CvrStgFile.h \
CvrStgObject.h Edge.h EdgeIterator.h DMDConstructionHeuristic.h \
EmbData.h Embedder.h EncryptionAlgorithm.h EncryptionMode.h Extractor.h \
Globals.h Graph.h JpegFile.h JpegSampleValue.h MCryptPP.h MHashKeyGen.h \
MHashPP.h Matching.h MatchingAlgorithm.h PasswordCracker.h ProgressOutput.h PseudoRandomSource.h \
RGBTriple.h RandomSource.h SampleOccurence.h SampleValue.h \
SampleValueAdjacencyList.h Selector.h Session.h SeedCracker.h SteghideError.h Terminal.h \
Utils.h Vertex.h WavChunk.h WavChunkHeader.h WavChunkUnused.h WavFile.h \
WavFormatChunk.h WavPCMSampleValue.h common.h error.h msg.h \
SMDConstructionHeuristic.h gettext.h
stegseek_SOURCES = \
Arg.cc Arguments.cc AssertionFailed.cc AuFile.cc AuSampleValues.cc \
DFSAPHeuristic.cc BFSAPHeuristic.cc BinaryIO.cc BitString.cc BmpFile.cc \
BmpPaletteSampleValue.cc BmpRGBSampleValue.cc BmpSampleValue.cc \
WKSConstructionHeuristic.cc DMDConstructionHeuristic.cc Cracker.cc CvrStgFile.cc \
Edge.cc EdgeIterator.cc EmbData.cc Embedder.cc \
EncryptionAlgorithm.cc EncryptionMode.cc Extractor.cc Graph.cc JpegFile.cc \
JpegSampleValue.cc MCryptPP.cc MHashKeyGen.cc MHashPP.cc Matching.cc \
MatchingAlgorithm.cc PasswordCracker.cc ProgressOutput.cc PseudoRandomSource.cc RGBTriple.cc \
RandomSource.cc SampleValue.cc SampleValueAdjacencyList.cc Selector.cc \
Session.cc SeedCracker.cc SteghideError.cc Terminal.cc Utils.cc Vertex.cc WavChunk.cc \
WavChunkHeader.cc WavChunkUnused.cc WavFile.cc WavFormatChunk.cc \
WavPCMSampleValue.cc error.cc main.cc msg.cc SMDConstructionHeuristic.cc
LIBS = @LIBS@ -lpthread
localedir = $(datadir)/locale
MAINTAINERCLEANFILES = Makefile.in
