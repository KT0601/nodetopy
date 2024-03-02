
This package help you to run python code in nodejs
If you want to run for python (not for python3) then use this package [nodetopy](https://www.npmjs.com/package/nodetopy)
 

```js
const runPythonCode = require('nodetopy3');
async function executePythonCode() {
    try {
        const stdout = await runPythonCode('demo.py');
        console.log(stdout);
    } catch (error) {
        console.error(error);
    }
}
executePythonCode();
```

## Installation

This is a [Node.js](https://nodejs.org/en/) module available through the
[npm registry](https://www.npmjs.com/).

Before installing, [download and install Node.js](https://nodejs.org/en/download/).
Node.js 0.10 or higher is required.

If this is a brand new project, make sure to create a `package.json` first with
the [`npm init` command](https://docs.npmjs.com/creating-a-package-json-file).

Installation is done using the
[`npm install` command](https://docs.npmjs.com/getting-started/installing-npm-packages-locally):

```console
$ npm install nodetopy3
```


## how to use Python Library
  First make a .txt file(for eg dependency.txt) and write library and it's version.
  dependepency.txt
```console
img2pdf==0.5.1
numpy==1.26.1
```


Then run following function 
```js

const libinstall =require('nodetopy3')
async function libinstall1() {
    try {
        const stdout = await libinstall('dependency.txt');
        console.log(stdout);
    } catch (error) {
        console.error(error);
    }
}
libinstall1()
```


### Running Tests

To run the test suite, first install the dependencies, then run `npm test`:

```console
$ npm install
$ npm test
```

## People

The original author of nodetopy3 is [Tanish Khandelwal](https://github.com/kt0601)
For any issue you can open issue at github repo[nodetopy](https://github.com/KT0601/nodetopy);



## License

  [License](https://github.com/KT0601/nodetopy/blob/main/LICE)

