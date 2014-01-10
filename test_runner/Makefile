test:
	npm install
	rm -rf node_modules/network-constants
	mkdir  node_modules/network-constants
	cp -r ../*.js         node_modules/network-constants
	cp -r ../package.json node_modules/network-constants
	cp -r ../README.md    node_modules/network-constants
	cp -r ../spec         node_modules/network-constants
	./node_modules/.bin/mocha \
		--debug \
		--reporter nyan \
		--check-leaks \
		--require tests_init.js \
		node_modules/network-constants/spec/*

run:
	./run.sh

.PHONY: test
