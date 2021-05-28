clean:
	@echo "Clean up old files"

build: clean
	@echo "Build application"

deploy: build
	@echo "Deploy application to stage server"

test: deploy
	@echo "Test stage deployment"

.PHONY: clean build deploy test