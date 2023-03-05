.PHONY: buildck
PATH := $(PATH):$(shell pwd)/bin
RESET=\033[0m
GREEN=\033[92m
YELLOW=\033[1;33m

buildck:
	@echo "${YELLOW}Building...${RESET}"
	@docker run --rm -u 1000:1000 -v ${PWD}:/app -w /app node npm run build
	@echo "${GREEN}Done${GREEN}"

