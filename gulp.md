#Gulp

##Repetition  
##Automation  
##Overview  
A.	Gulp CLI 
B.	Gulp API, [gulp api docs](https://github.com/gulpjs/gulp/blob/master/docs/API.md)
	1.	`.task` 
	>Defines a task
	2.	`.src`   
	>Emits files matching provided glob or an array of globs. Returns a stream of Vinyl 	files that can be piped to plugins.
	3.	`.dest`
	>Can be piped to and it will write files. Re-emits all data passed to it so you can 	pipe to multiple folders. Folders that don't exist will be created.
	4.	`.watch`
	>Watch files and do something when a file changes. This always returns an 	EventEmitter that emits change events.
C.	gulpfile.babel.js, ES6
##Conclusion