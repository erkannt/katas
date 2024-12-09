.PHONY: test
test: node_modules
	pnpm jest

.PHONY: test
test-watch: node_modules
	pnpm jest --watch

.PHONY: lint
lint: node_modules
	pnpm eslint .

node_modules: package.json pnpm-lock.yaml
	pnpm install