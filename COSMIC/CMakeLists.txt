
include_directories(${CMAKE_CURRENT_SOURCE_DIR}/HDR)
include_directories(${CMAKE_CURRENT_SOURCE_DIR})

add_library(simpleskts Saccept.c Sclose.c Sgets.c Sinit.c Smaskwait.c 
Smkskt.c Sopen.c Sopenv.c Speek.c Speeraddr.c Speername.c Sprintf.c 
Sprtskt.c Sputs.c Sread.c Sreadbytes.c Srmsrvr.c Sscanf.c Stest.c 
Stimeoutwait.c Svprintf.c Swait.c Swrite.c cprt.c error.c fopenv.c 
outofmem.c rdcolor.c sprt.c srmtrblk.c stpblk.c stpnxt.c strnxtfmt.c)
