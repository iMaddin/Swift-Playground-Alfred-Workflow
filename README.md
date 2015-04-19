# Swift Playground Alfred Workflow

Create or open a Swift Playground through Alfred. 

Launch Alfred and enter one of the following:
- *play osx fileName*
-- creates an OS X Playground
- *play ios fileName*
-- creates an iOS Playground
- *play prototype fileName* 
-- creates an iOS Playground with a template that allows you to prototype UIViews (based on [this](http://possiblemobile.com/2015/03/prototyping-uiview-animations-swift-playground/))

Example: swift ios Batman

This will create a folder **~/Playgrounds** and then open a playground named *fileName.playground* in Xcode. If a playground with that filename already exists then it will open the existing one instead.

Additional Info:
- You can change the default folder by editing main.sh inside the **.workflow** file.
- The .playground template files are stored inside the workflow.	