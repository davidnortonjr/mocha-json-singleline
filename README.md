# mocha-json-singleline-shorterline
Single-line JSON output for mocha, with less data (stats and failure messages only) so that the log line will not balloon out of control.

## Installation

```
sudo npm -g install mocha-json-singleline-shorterline
```

## Usage

```
mocha -R mocha-json-singleline-shorterline
```

Output will be sent to STDOUT, but in a single line for each run. 
This is needed to have the output parsable by fluentd, who does not approve of newlines in your output.
