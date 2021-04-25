# Handle virtualenv for Python

## Objectives:
1. Installing virtualenv
2. Creating named environment
3. Activating the environment
4. Installing modules with pip
5. Create a module and import installed modules
6. Run module
7. Learn how to deactivate it

## Steps:
Check if you have virtualenv installed
            > virtualenv --version

If you don’t have it installed, do:
            > pip install virtualenv

Create new directory for project, something like:
            > mkdir virtualenv_demo

Navigate inside it:
            > cd virtualenv_demo

Create environment
            > virtualenv venv --python python3

FYI: 
venv  is the environment’s name
--python python3 defines python version to be used as interpreter 
This should create a new directory with the environment’s name
Installed pip and all python dependencies.

Activate environment
            > source venv/bin/activate
            
You should see:
            >(venv)  <your_awesome_username> >

Let’s install any package
           (venv) > pip install pandas


Create simple python module
          (venv) > main.pp


After creating python module, let’s run it:
          (venv) > python main.py

To deactivate virtualenv:
          (venv) > deactivate


> which python (where is python installed)
> ls venv
