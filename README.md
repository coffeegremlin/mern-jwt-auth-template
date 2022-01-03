# MERN Stack with JWT Auth Template 
#
# DEPRECATION NOTICE:
This is a coupled application and will NOT work with the most current version of `react-scripts`.  The code in this repository functions, but if you're looking for a more current option, please refer to the decoupled version of this application:
- Front end can be found [here](https://github.com/SEI-Remote-WC/jwt-auth-mern-template-front-end).
- Back end can be found [here](https://github.com/SEI-Remote-WC/jwt-auth-mern-template-back-end).

This is a MERN Stack template that includes JWT Authentication.

Use this to go build things! 🚀

## To Use This Template

**Replace `<name-of-your-app-here>` in the commands below with the name of your app!**

```bash
git clone https://github.com/SEI-Remote-WC/jwt-auth-mern-template-coupled <name-of-your-app-here>
cd <name-of-your-app-here>
```

Once you are in the project directory:

```bash
rm -rf .git
```

Here's what your command line output should like after this step (note that the indicator that we are in a git repository is gone!)

<img src="https://i.imgur.com/L47kNOZ.png" alt="The command line before and after running the rm -rf .git command. Before git:(main) is visible indiating that the directory contains a git repository, after the command it is not.">

Re-initialize a git repository:

```bash
git init
```

Use the GitHub CLI to create a new project repository on GitHub:

```bash
gh repo create <name-of-your-app-here>
```

Run npm i to fetch the template's dependencies:

```bash
npm i
```

Then, make an initial commit:

```bash
git add .
git commit -m "initial commit"
git push -u origin main
```

touch a .env file:

```bash
touch .env
```

Fill it with the following:

```
DATABASE_URL=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
SECRET=XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
```

Replace the `DATABASE_URL` and `SECRET` with values that you provide.

Delete this README.md

You're done!
