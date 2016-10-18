NODE_ENV=production node_modules/.bin/webpack -p

node_modules/.bin/http-server src/static

NODE_ENV=production node_modules/.bin/babel-node --presets 'react,es2015' src/server.js