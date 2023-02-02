# SSE-API

- npm install
- node server.js
- (terminal 1) curl -H Accept:text/event-stream http://localhost:3001/events 
- (terminal 2) curl -X POST \
 -H "Content-Type: application/json" \
 -d '{"info": "Shark teeth are embedded in the gums rather than directly affixed to the jaw, and are constantly replaced throughout life.", "source": "https://en.wikipedia.org/wiki/Shark"}'\
 -s http://localhost:3001/fact
Reference:

https://www.digitalocean.com/community/tutorials/nodejs-server-sent-events-build-realtime-app
