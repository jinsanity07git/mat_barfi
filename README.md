# Streamlit Barfi

**Block and Link based graphical programming environment for performing simulations in Python using Streamlit.**

Streamlit component for a graphical programming environment to perform simulations.

## Development notes

Following are the notes for working on the development of the component.

### Quickstart for development

- In terminal 1
```
$ cd st_barfi/frontend
$ npm run serve
```

- In terminal 2
```
$ streamlit run st_barfi/__init__.py 
```

### Requirements

- Ensure you have [Python 3.6+](https://www.python.org/downloads/), [Node.js](https://nodejs.org), and [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) installed.
- Clone this repo to a local folder.

#### Python virtual environment

Create a new Python virtual environment:

```
$ python3 -m venv venv  # create venv
$ . venv/bin/activate   # activate venv
$ pip install streamlit # install streamlit
```

Run the components's Streamlit app:

```
$ . venv/bin/activate  # activate the venv you created earlier
$ streamlit run st_barfi/__init__.py  # run the root test
```

#### Node environment

Install and initialize the component's frontend:

```
$ cd st_barfi/frontend
$ npm install    # Install npm dependencies
$ npm run serve  # Start the dev server
```

