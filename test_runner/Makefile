test:
	npm install
	rm -rf node_modules/generic_store
	mkdir  node_modules/generic_store
	cp -r ../*.js         node_modules/generic_store
	cp -r ../package.json node_modules/generic_store
	cp -r ../README.md    node_modules/generic_store
	cp -r ../spec         node_modules/generic_store
	cp -r ../node_modules node_modules/generic_store
	./node_modules/.bin/mocha \
		--debug \
		--reporter nyan \
		--check-leaks \
		--require tests_init.js \
		node_modules/generic_store/spec/*

.PHONY: test
