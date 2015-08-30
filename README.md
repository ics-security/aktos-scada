# INSTALL

* install [aktos-dcs](https://github.com/ceremcem/aktos-dcs)

  * `cd test-folder`
  * `git clone https://github.com/ceremcem/aktos-dcs`
  * follow [installation notes](https://github.com/ceremcem/aktos-dcs/blob/master/README.md#install)

* install global dependencies: 

  * as root: `npm install -g livescript brunch pm2`
  * install libzmq-4.x
        
          sudo apt-get install libzmq3-dev  # or install from source

* clone this project and install rest of the dependencies

  * `cd test-folder`
  * clone or download this project
  * open terminal in project directory 
  * as normal user: `npm install`

# Quick start

While in project directory, 

* open a terminal and type:

        npm start

* open another terminal and type:

        python test_message_sending/keypad_simulator.py

Then open [http://localhost:4000](http://localhost:4000) and see if the button clicks are sent to python process and analog display is changing.


# Optional 

optional: in order to see server.ls logs:

    npm run show-logs


optional: In order to build production code:

    make production


