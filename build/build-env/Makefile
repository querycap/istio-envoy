VERSION=$(shell cat .version)

NAME ?= build-env
TAG ?= $(VERSION)

prepare:
	@echo ::set-output name=image::$(NAME):$(TAG)
	@echo ::set-output name=build_args::VERSION=$(VERSION)