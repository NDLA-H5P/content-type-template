# Content-Type Template
Template repository for new content types.

## How to use this Template

This project is intended be used as a template for new H5P content types. Se the docs/ folder for suggested guidelines and workflows for your H5P content type.

## Building and Running

You can set up local development using the h5p-dev-root project following these steps:  
    * Clone the h5p-dev-root
    * Check out this content-type in a subfolder to h5p-de-root
    * If nessecary, modify the dev-root project to have a build target and dependencies file for the current content type.


When this is done, you can run an instance of h5p with this content type installed by running `make run_<THIS_CONTENT_TYPE>`.


## Creating Releases

Releases are created every time you check in the main or master branch of the content type by using github actions.

