## Synopsis

This project is an implementation of a Wit app and show all steps of its process. 
The objective of our application is to get colour information from voice recognition and change a *html* object with this colour "on the fly." 
The result is **an interactive webpage that "understands'' voice orders and modify its object colour according to the commands of the user**.

## Code Example

After activating the mic app and speaking the following order:
> "Change the coulour to blue"

the web page will display: 

``intent = colour``

``value_colour = blue``

and the *html* circle on the webpage will change its colour fill to blue.


## Motivation

This project is one research task of the class *CS 807: Interactive Hardware and Embedded Computing*.

This task in particulas is called **The Platform**, which requires to research and implement a practical example of an embedded, cloud, or high-performance computing platform, with a demonstration of the use of that platform. 
It has to show more than the simple "hello world" demo that comes with the platform, and it has to describe what happens "under the hood". 
It should be enough clear in details to allow another student to quickly get started with that platform, but critical enough to indicate the benefits and drawbacks compared to similar platforms.

Obviously, it requires code.


## Installation

Create a new folder for the app,  download the microphone app, and extract the archive:
```
	curl -L https://github.com/wit-ai/microphone/releases/download/0.7.0/microphone-0.7.0.tar.gz | tar xvzf -
	mv microphone-* microphone
```

Download these [index.html](https://github.com/andreeds/cs807-research-tasks/blob/master/B%20-%20The%20Platform/Wit/index.html) file.

The index.html already contains the *Client Access Token* for the App.
If you want to improve it or create on yourself, download the [ColourTest](https://wit.ai/andreeds/ColourTest) to your Wit app, create a new *Client Access Token* and replace it on the index.html file.

Serve your app with the webserver of your choice.
For example, using Python:
```
python -m SimpleHTTPServer
```
Go on Chrome, Firefox or Opera and hit ``http://localhost:8000``

For more details, please check the [PDF paper](https://github.com/andreeds/cs807-research-tasks/blob/master/B%20-%20The%20Platform/Paper/Task_B_Andre_200334126.pdf) inside.

## Tests

Click on the mic picture on the webpage. Say the name of a colour or ask to change the coulour specifying it. 

..or just say "Hello." 
The app is polite ;)

## License

**Free Software, Hell Yeah!**
