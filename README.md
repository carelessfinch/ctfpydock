# ctfpydock
Docker files for hosting all python challenges.

# Usage
Add challenge files to files directory.

Add necessary modules to ``requirements.txt``.

Run ``docker build -t pydock .`` to build the container.

Run ``docker run -d -it -p 1337:1337 pydock`` to run the container.
