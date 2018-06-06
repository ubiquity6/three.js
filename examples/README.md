Raw Three.js GLTF Testing Environment
========


#### Testing GLTF Assets ####

Goal: Provide a raw three.js environment for importing and testing gltf assets while we narrow in on a working pipeline.

Contains working example of applying lightmap (/examples/ubq_lightmap.html)


### Usage ###

1. Create an html scene
  - Name a scene in the following format : category_nameofscene.html
    - ex: ubq_lightmap.html

  -   Go to /examples/files.js and make sure to include your new scene.
    - ex: If you wanted to include ubq_mytest.html, files.js would look like this:
      - "ubq": [
        - "ubq_lightmap",
        - "ubq_mytest",
        - ],

2. Go to root directory and call 'python -m SimpleHTTPServer 8000' (or server/portnumber of your choice)

3. Open browser of choice (tested on safari and chrome) and visit localhost:8000

4. For more information, visit: https://threejs.org/docs/#manual/introduction/How-to-run-things-locally


### NOTES ###

1. If you find that your html scene is not updating, make sure to clear your cached data. This shouldn't happen too often https://stackoverflow.com/questions/25723801/file-not-updating-on-localhost
