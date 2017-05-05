# simpleP5Arduino
An example of Arduino and p5.js talking to each other with p5.serialserver. 

### Dependencies

* Install Node.js and npm with:

`curl "https://nodejs.org/dist/latest/node-${VERSION:-$(wget -qO- https://nodejs.org/dist/latest/ | sed -nE 's|.*>node-(.*)\.pkg</a>.*|\1|p')}.pkg" > "$HOME/Downloads/node-latest.pkg" && sudo installer -store -pkg "$HOME/Downloads/node-latest.pkg" -target "/"`

* Install p5.serialserver with: 

`sudo npm install -g p5.serialserver` 

### Usage

* Run p5.serialserver with `p5serial`.
* Open the index.html file
