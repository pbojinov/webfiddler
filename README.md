# webfiddler

webfiddler is a web browser based debugging proxy written in Node.js, inspired by [Fiddler](http://www.fiddler2.com/)

It is currently a work-in-progress in development and by no means stable, nor as featureful as Fiddler.


## Getting Started

First install the dependencies
		
	npm install


## How to run

Now run the server

```
node server.js
```

Finally, configure your favorite webbrowser to use `http://localhost:8080/` as a HTTP proxy. In Chromium, this would be easily achieved by running:

```
chromium-browser --proxy-server="http://localhost:8080/"
```

## TODO

* Implement a proper backend store mechanism
* Implement selective request decoding
* Implement SSL decryption (man-in-the-middle attack)
* Implement a Auto-Responder style UI
* Allow for future plugins


## License + Credits

This software was originally developed by [adammw](http://github.com/adammw), and is released under a GPL license.