<h1>Flask Template With Bootstrap</h1>
<p>This is a simple scaffhold template so people can get started with Flask applications as fast as possible<p>
<b>Note</b>
<p>This isn't suited for beginneers as they must have good knowledge of flask before using this template.</p>

## Getting Started

To get started using this template in your project, first click "Use This Template" and click create a new repository

Then on the create new repo page Enter a name for your project and create it

next copy the url of your new created github repository and head over to vscode assuming you already created a foler for your project and opened it

then run
```
  git clone <repository_url>
```
After you have cloned your repo locally
You must now create a virtual environment
to do so
**Windows**
```
  python -m venv venv

```
**Mac**
```
  python3 -m venv venv
```

after you created the venv and see a venv folder in your repo
you should now activate it
**Windows**
```
  venv\Scripts\activate
```
**MAC**
```
  enter command here for mac
```

now with your virtual env activated

we must now install the dependencies for the current project
```
  pip install -r requirements.txt
```

Once Installed successfully 
make sure that your active interpreter is ('venv':venv) 
You can do that by opening a .py file and in the bottom right corner of VSCODE 
Just make sure that it is what that is stated above

Now since everything should be alright
```
  flask --debug run
```
OR
```
  flask --debug run -p 8080
```
To change the default port

Thanks for using my template!
Happy FlaskStrapping!!

