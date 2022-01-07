# style_dictionary

style dictionary test repository

## Getting Started

Styling
We are using the amazon style dictionary, to use it is necessary to install the CLI using the command:

```$ npm install -g style-dictionary```

done that the folder structure should look like this:

```
├── lib
├── config.json
├── style/
│   ├── brand-tokens.json
│   ├── global-tokens.json
```

To generate the classes run the command:

Generate separated:

```style-dictionary build -p flutter-separate```

Generate unified

```style-dictionary build -p flutter```

Github: https://github.com/amzn/style-dictionary
