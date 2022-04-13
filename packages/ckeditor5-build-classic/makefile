PATH := $(PATH):$(shell pwd)/bin

build:
	@docker run --rm -u 1000:1000 -v ${PWD}:/app -w /app node npm run build

