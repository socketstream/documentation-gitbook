# Quick Start

Install SocketStream as a global package:

```bash
npm install -g socketstream
```

Create a new app in your workspace (`socketstream -h` for options):

```bash
socketstream new my-app
```

You should see something like the following:

```bash
Success! Created app 'my-app' with:
 ✓ Basic chat demo (-m for minimal install)
 ✓ Javascript example code (-c if you prefer CoffeeScript)
 ✓ Plain HTML for views (-j if you prefer Jade)
 ✓ Plain CSS (-s if you prefer Stylus, -l for Less)
Next, run the following commands:
   cd my-app
   [sudo] npm install
To start your app:
   node app.js
```

To install the app and start it:

```bash
cd my-app
npm install
npm start
```

Open your favorite development browser at [http://localhost:3000/](http://localhost:3000/) and start hacking!

For a more comprehensive guide, [continue with our documentation →](client-side-development/README.md)
