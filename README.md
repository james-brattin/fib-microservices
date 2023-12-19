There is a nginx  server listening to:
1. a react dev server on port 3000, called client
2. a nodejs api on port 5000, called api

Routes:
- '/' goes to client:3000
- '/api' goes to api:5000

goes into default.conf