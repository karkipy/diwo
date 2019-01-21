## diwo - Do it when online

A simple shell script that records your commands when you are offline, and you can run it once you get the internet connecction or simple call the recorded commands


## Installation

Manual

```bash
  git clone {this-repo}
```

Give the permission to the script

```bash
  chmod +x diwo
```

Move the script to /usr/local/bin for global access

```bash
 mv diwo  /usr/local/bin
```

### or

This does all the things above

```bash
curl https://raw.githubusercontent.com/karkipy/diwo/master/diwo -o /usr/local/bin/diwo && chmod +x /usr/local/bin/diwo
```


## Usage

- stack : add commands so that you can run it at once
- pop: run save commands , show is a param to show the log

Restart the terminal


## TODO

- automation : add a callback to internet connection
- globalSave: the commands are being saved in a txt file and will show up in the folder need to make it a globalStore


## Output

<img width="568" alt="screen shot 2019-01-21 at 5 49 24 pm" src="https://user-images.githubusercontent.com/12614476/51473626-0019a200-1da5-11e9-8387-c5da6dc4c7eb.png">



<img width="571" alt="screen shot 2019-01-21 at 5 49 42 pm" src="https://user-images.githubusercontent.com/12614476/51473627-0019a200-1da5-11e9-84be-29e8c3bff196.png">

