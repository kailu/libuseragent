lib_LTLIBRARIES = libuseragent.la
libuseragent_la_SOURCES = uap-cpp/UaParser.cpp
libuseragent_la_LDFLAGS = -lboost_regex -lyaml-cpp

AM_CXXFLAGS = -std=c++0x -Wall -Werror -fPIC -g -O3

include_HEADERS = uap-cpp/UaParser.h

libuseragent_ladir = /usr/local/share/uap
libuseragent_la_DATA = uap-core/regexes.yaml
