## cuXfilter library - serverside crossfilter library for the browser

### To build using Docker:

while in the directory, run the following commands:


<pre>
docker build -t user_name/viz .
docker run --runtime=nvidia  -d -p 3000:3000 --name rapids_viz -v /folder/with/data:/usr/src/app/node_server/uploads user_name/viz

</pre>

### Javascript (es6) client - [cuXfilter](client_side)

