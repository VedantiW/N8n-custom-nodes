## Run N8n local instance and open .n8n folder in your laptop.
Inside that create a custom folder, and then place this zipped-extracted code inside the custom/n8n-nodes-nasapics folder.


You can test your node as you build it by running it in a local n8n instance.

# Install n8n using npm:

# npm install n8n -g
When you are ready to test your node, publish it locally:

## In your node directory
# npm run build
# npm link
Install the node into your local n8n instance:


## In the nodes directory within your n8n installation
## node-package-name is the name from the package.json
# npm link <node-package-name>
Check your directory

Make sure you run npm link <node-name> in the nodes directory within your n8n installation. This can be:

~/.n8n/custom/n8n-nodes-nasapics

## Start n8n:

# n8n start
