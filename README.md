My first React-Redux App

Installation
	npm i --save-dev webpack
	npm i --save express
	npm i --save babel-core babel-loader babel-preset-es2015 babel-preset-stage-1 babel-preset-react
	npm i --save redux

THREE PRINCIPLES OF REDUX
1.SINGLE SOURCE OF TRUTH:
	The state of your whole application is stored in an object tree withon a single store.
2.STATE IS READ-ONLY:
	The only way to change the state is to emit an ACTION.
3.CHANGES ARE MADE WITH PURE FUNCTIONS:
	Reducers have to be pure-functions

IMMUTABILITY OF THE STATE
1.WHEN MAKING OPERATIONS WITH ARRAYS:
　DO NOT USE mutable methods: push() or splice()
	USE: concat(), slice() or ...spread operator