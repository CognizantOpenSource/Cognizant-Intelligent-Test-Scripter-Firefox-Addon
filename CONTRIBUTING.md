# Contributing to Cognizant Intelligent Test Scripter

These are just guidelines, not rules. Use your best judgment. Please feel free to propose changes to this document in a pull request.

## Code of Conduct

This project adheres to the Contributor Covenant [code of conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [CogCITS@cognizant.com](mailto:CogCITS@cognizant.com).

## Communication

For general queries and discussions, please use the Cognizant Intelligent Test Scripter Forum on [Google Groups](https://groups.google.com/forum/#!forum/cognizant-intelligent-test-scripter)

## How Can I Contribute?

### Sign the CLA

Before you contribute, we first ask people to sign a [Contributor License Agreement](https://www.clahub.com/agreements/CognizantQAHub/Cognizant-Intelligent-Test-Scripter-Firefox-Addon) (or CLA). We ask this so that we know that contributors have the right to donate the code.

When you open your pull request we ask that you indicate that you've signed the CLA. This will reduce the time it takes for us to integrate it.

### Reporting Bugs

* Please go through the Help section to see if the problem is already addressed. Most common problems are already addressed in Troubleshooting and FAQs sections.

* Perform a cursory search to see if the problem has already been reported. If it has, add a comment to the existing issue instead of opening a new one.

* Use a clear and descriptive title for the issue to identify the problem.

### Suggesting Enhancements

* Perform a cursory search to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.

* Use a clear and descriptive title for the issue to identify the suggestion

* Explain why this enhancement would be useful to most Cognizant Intelligent Test Scripter users and isn't something that can or should be implemented as a community package

### Code Contribution

#### Development

Clone the Repo and extract it.

[Firefox WebExtensions Getting Started](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/Your_first_WebExtension)

You can do it via two ways

 * Open "about:debugging" in Firefox, click "Load Temporary Add-on" and select *manifest.json* in the cloned directory:

 * Alternatively, you can run the WebExtension from the command line using the [web-ext](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Getting_started_with_web-ext) tool.

#### Using web-ext

[Getting Started with web-ext](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/Getting_started_with_web-ext)

web-ext is a node-based application that you can install with the nodejs/npm tool. Install web-ext using the following command:

`npm install --global web-ext`

You can test whether your installation worked by running the following command, which lists the installed web-ext version number:

`web-ext --version`

You can test an extension in Firefox by cd'ing into your extension's root directory and entering the following command:

`web-ext run`

This will start up Firefox and load the extension temporarily in the browser, 


#### Prerequsite

The extension uses WebSocket Protocol to connect to the server. The Server is started as soon as you Launch Spy/Heal/Recorder from the **Cognizant Intelligent Test Scripter**

So it is required that the server needs to be running to Test it .

By default the server runs on https://localhost:8887. The server runs with a self-signed certificate that needs to be installed. Check [Documentation]() for more info.

### Submiting Changes

Always write a clear log message for your commits. One-line messages are fine for small changes, but bigger changes should look like this:

```
$ git commit -m "A brief summary of the commit
> 
> A paragraph describing what changed and its impact."
```
