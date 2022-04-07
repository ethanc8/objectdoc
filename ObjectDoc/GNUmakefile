include $(GNUSTEP_MAKEFILES)/common.make

LIBRARY_NAME = libObjectDoc
libObjectDoc_HEADER_FILES = ObjectDoc.h PLAdditions.h PLClangAvailability.h PLClangAvailabilityPrivate.h PLClangComment.h PLClangCommentPrivate.h PLClangCursor.h PLClangCursorPrivate.h PLClangDiagnostic.h PLClangDiagnosticPrivate.h PLClang.h PLClangNSString.h PLClangPlatformAvailability.h PLClangPlatformAvailabilityPrivate.h PLClangSourceIndex.h PLClangSourceLocation.h PLClangSourceLocationPrivate.h PLClangSourceRange.h PLClangSourceRangePrivate.h PLClangToken.h PLClangTokenPrivate.h PLClangTokenSet.h PLClangTranslationUnit.h PLClangTranslationUnitPrivate.h PLClangType.h PLClangTypePrivate.h PLClangUnsavedFile.h PLClangVersion.h PLClangVersionPrivate.h PLSourceLocation.h
libObjectDoc_HEADER_FILES_INSTALL_DIR = ObjectDoc
libObjectDoc_OBJC_FILES = PLClangAvailability.m PLClangComment.m PLClangCursor.m PLClangDiagnostic.m PLClang.m PLClangNSString.m PLClangPlatformAvailability.m PLClangSourceIndex.m PLClangSourceLocation.m PLClangSourceRange.m PLClangToken.m PLClangTokenSet.m PLClangTranslationUnit.m PLClangType.m PLClangUnsavedFile.m PLClangVersion.m PLSourceLocation.m

# Not portable - set up libclang

libObjectDoc_LIBRARIES_DEPEND_UPON += -lclang

ADDITIONAL_LIB_DIRS += -I/usr/lib/llvm-11/lib
ADDITIONAL_INCLUDE_DIRS += -I/usr/lib/llvm-11/include

include $(GNUSTEP_MAKEFILES)/library.make