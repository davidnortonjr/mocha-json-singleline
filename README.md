# mocha-json-singleline
Single-line JSON output for mocha

## Installation

```
sudo npm -g install mocha-json-singleline
```

## Usage

```
mocha -R mocha-json-singleline
```

Output will be sent to STDOUT, but in a single line for each run. 
This is needed to have the output parsable by fluentd, who does not approve of newlines in your output.
