# **********************************************************
# Makefile for rfilter1 Directory
# **********************************************************
SHELL = /bin/sh
PREFIX=/Users/anb32/Desktop/sctk-2.4.10
bindir = $(PREFIX)/bin
T=../test_suite

all: rttm2ctm.pl

rttm2ctm.pl: 
	chmod +x rttm2ctm.pl

check: all
	@echo "No Tests for rttm2ctm.pl"

install: all
	cp rttm2ctm.pl $(bindir)

clean:

distclean: clean
	rm -r *~ makefile
