set(PXR_PREFIX pxr/base)
set(PXR_PACKAGE tracelite)

pxr_library(tracelite
    LIBRARIES
        arch

    PUBLIC_CLASSES
        trace
        
    PUBLIC_HEADERS
        api.h
)
