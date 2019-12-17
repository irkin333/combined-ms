## Local development -- all at once
It is preferred to only run one app at a time. But if you need to run them all locally, you can do so with the following instructions

# First terminal tab
cd app-frame

npm install

npm start

Open http://localhost:4200 ;

# Second terminal tab (used port: 4201)
cd app1
npm install
ng serve

# Third terminal tab (used port: 4202)
cd app2
npm install
ng serve
