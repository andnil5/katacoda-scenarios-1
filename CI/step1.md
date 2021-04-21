If you want to follow along with the tutorial on your computer instead of in the Katacoda sandbox, you can find the code for the Express application [here](https://github.com/nwessman/katacoda-scenarios/tree/express-app). If you do this, make sure to fork the repo before cloning since step 8 requires you to have permission to push to the repository. The source code of the project resides in the branch `express-app`.

**Note:** You will not be able to do *step 8: Testing the GitHub Action* if you do not run this locally. However, you can proceed with the tutorial until *step 8* and fork the complete project at that point, including everything implemented in *step 1-7*.

#### Node installation (Locally only)

**Note:** This step is only required if you want to run the project locally; proceed to the next step if you continue on Katacoda.

Start by installing Node and NPM, if not already installed. You can check if you have them installed by running the following two commands in the terminal:
```
node -v
npm -v
```{{execute}}
If they are already installed, you will see the node and npm versions printed and can proceed to step 3.

#### 1. Install Node (Linux)
```
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
sudo apt-get install -y nodejs
```{{execute}}
#### 2. Test Node and npm
Node:
``` 
> node -v
```{{execute}} 
NPM:
```
> npm -v
```{{execute}}

**Note:** Some of these commands used above are Linux-specific. Consult the [official documentation](https://nodejs.org/en/download/) for other OS support.
