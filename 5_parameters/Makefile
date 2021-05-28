BROWSER ?= firefox

test: deploy
	@test -n "$(BROWSER)" || (echo "BROWSER not set!" ; exit 1)
	@echo "Testing with browser ${BROWSER}"

deploy:
	@echo "Deploying web application"

.PHONY: deploy test