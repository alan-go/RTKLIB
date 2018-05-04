cmake_minimum_required(VERSION 2.8)

#aux_source_directory(. SRC_RTKLIB)

add_library(rtklib 

convkml.c
convrnx.c
datum.c
download.c
ephemeris.c
geoid.c
ionex.c
lambda.c
options.c
pntpos.c
postpos.c
ppp_ar.c
ppp.c
preceph.c
qzslex.c
rcvraw.c
rinex.c
rtcm2.c
rtcm3.c
rtcm3e.c
rtcm.c
rtkcmn.c
rtkpos.c
rtksvr.c
sbas.c
solution.c
stream.c
streamsvr.c

)