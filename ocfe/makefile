.PHONY: install start clean test help

# Default target executed when no arguments are given to make.
default: 
	npm run start

## install dependencies
deps:
	npm install 

dev:
	npm run dev

## Clean all files created by the build and/or tests
clean:
	rm -rf ./node_modules

## Show available commands by parsing Makefile comments
help:
	@grep '##' $(MAKEFILE_LIST) | sed 's/^.*##//'