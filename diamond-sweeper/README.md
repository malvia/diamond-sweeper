# Diamond Sweeper

To start the Application:

* Install the dependencies : `npm install`
* Compile Assets: `npm run compile`
* Start the webserver: `npm start`
* Visit `http://localhost:3000` to see the application

Algorithm for diamond Sweeper:

Render a 8X8 table with unique Ids from 0 to 63.

Generating co-ordinates of each box based on Id.

Generating position of 8 random diamonds.

attaching clickhandler.

Getting nearest diamond position from the box.

Calculate the slope of hint arrow (between nearest diamond and clicked box).

Rotate the arrow png to the calculated angle.

At the end Dispaly Score.