SHELL := /bin/bash

.PHONY: all
all:
	pip install runcython
	makecython3++ stitch_wrapper.pyx "" "stitch_rects.cpp ./hungarian/hungarian.cpp"

