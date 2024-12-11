# devcontainer.json 

The devcontainer.json file tells Codespaces how to set up development environment and it contains basic configuration: 
"image": Specifies the base container image with Python.

"features": Installs the required Python version.

"customizations": Installs VS Code extensions for Python and Jupyter.

"postCreateCommand": Runs after the container setup, installing necessary libraries.

Explanation of Placement
Root Level: The "build" key goes directly under the root object of devcontainer.json.
This ensures the Dockerfile is used to build the container.
Other Configurations:
The "features" and "customizations" sections work alongside the "build" block.
The "postCreateCommand" ensures required libraries are installed after the container is set up.
If this devcontainer.json file exists in the .devcontainer folder, it will be automatically detected and applied by GitHub Codespaces when creating a new instance. Let me know if you need further clarification or examples!

# DockerFile

This defines a custom environment{Docker}
