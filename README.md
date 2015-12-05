# Node-install-problems
I am not very familiar with these areas of programming, but need to use Node and nam. Who can help me sorting this out?

AirMeToo:~ gerritbosch$ sudo npm install esp8266 -g
Password:
/usr/local/bin/bin/esp -> /usr/local/bin/lib/node_modules/esp8266/bin/cli.js

> serialport@1.7.4 install /usr/local/bin/lib/node_modules/esp8266/node_modules/serialport
> node-pre-gyp install --fallback-to-build

gyp WARN install got an error, rolling back install
gyp ERR! configure error 
gyp ERR! stack Error: EPERM: operation not permitted, utime '/Users/gerritbosch/.node-gyp/5.1.1'
gyp ERR! stack     at Error (native)
gyp ERR! System Darwin 15.0.0
gyp ERR! command "/usr/local/bin/node" "/usr/local/lib/node_modules/npm/node_modules/node-gyp/bin/node-gyp.js" "configure" "--fallback-to-build" "--module=/usr/local/bin/lib/node_modules/esp8266/node_modules/serialport/build/serialport/v1.7.4/Release/node-v47-darwin-x64/serialport.node" "--module_name=serialport" "--module_path=/usr/local/bin/lib/node_modules/esp8266/node_modules/serialport/build/serialport/v1.7.4/Release/node-v47-darwin-x64"
gyp ERR! cwd /usr/local/bin/lib/node_modules/esp8266/node_modules/serialport
gyp ERR! node -v v5.1.1
gyp ERR! node-gyp -v v3.0.3
gyp ERR! not ok 
node-pre-gyp ERR! build error 
node-pre-gyp ERR! stack Error: Failed to execute '/usr/local/bin/node /usr/local/lib/node_modules/npm/node_modules/node-gyp/bin/node-gyp.js configure --fallback-to-build --module=/usr/local/bin/lib/node_modules/esp8266/node_modules/serialport/build/serialport/v1.7.4/Release/node-v47-darwin-x64/serialport.node --module_name=serialport --module_path=/usr/local/bin/lib/node_modules/esp8266/node_modules/serialport/build/serialport/v1.7.4/Release/node-v47-darwin-x64' (1)
node-pre-gyp ERR! stack     at ChildProcess.<anonymous> (/usr/local/bin/lib/node_modules/esp8266/node_modules/serialport/node_modules/node-pre-gyp/lib/util/compile.js:83:29)
node-pre-gyp ERR! stack     at emitTwo (events.js:87:13)
node-pre-gyp ERR! stack     at ChildProcess.emit (events.js:172:7)
node-pre-gyp ERR! stack     at maybeClose (internal/child_process.js:818:16)
node-pre-gyp ERR! stack     at Process.ChildProcess._handle.onexit (internal/child_process.js:211:5)
node-pre-gyp ERR! System Darwin 15.0.0
node-pre-gyp ERR! command "/usr/local/bin/node" "/usr/local/bin/lib/node_modules/esp8266/node_modules/serialport/node_modules/.bin/node-pre-gyp" "install" "--fallback-to-build"
node-pre-gyp ERR! cwd /usr/local/bin/lib/node_modules/esp8266/node_modules/serialport
node-pre-gyp ERR! node -v v5.1.1
node-pre-gyp ERR! node-pre-gyp -v v0.6.7
node-pre-gyp ERR! not ok 
Failed to execute '/usr/local/bin/node /usr/local/lib/node_modules/npm/node_modules/node-gyp/bin/node-gyp.js configure --fallback-to-build --module=/usr/local/bin/lib/node_modules/esp8266/node_modules/serialport/build/serialport/v1.7.4/Release/node-v47-darwin-x64/serialport.node --module_name=serialport --module_path=/usr/local/bin/lib/node_modules/esp8266/node_modules/serialport/build/serialport/v1.7.4/Release/node-v47-darwin-x64' (1)
npm WARN install:serialport@1.7.4 serialport@1.7.4 install: `node-pre-gyp install --fallback-to-build`
npm WARN install:serialport@1.7.4 Exit status 1
/usr/local/bin/lib
└── (empty)

npm ERR! code 1
