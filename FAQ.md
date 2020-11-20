---
sidebar: true
order: 5
---

# FAQ

### What can I say?  
Checkout the [common commands](/getting_started/#list-of-common-commands-to-get-started-with-talon-if-using-the-knausj-repo) to get started using Talon.

### How can I code with Talon
Checkout the [introductory guide to coding with Talon](https://talon.wiki/working_with_code/).

### What hardware should I have?
Check out the [hardware](/hardware) page for microphone and eye tracker recommendations.  

### Are languages other than English supported?

They're being worked on, join talonvoice.slack.com and find a channel for your language to see how it's going.

### How can I make talon recognise me better?

See the page [Improving Recognition Accuracy](/improving_recognition_accuracy).

### How can I contribute?

While Talon is closed source, there's plenty you can do to help:

* https://speech.talonvoice.com/ Extend the voice data set used for speech recognition training.
* Publish your talon commands on Github for others to use like https://github.com/knausj85/knausj_talon or https://github.com/lunixbochs/talon_starter_pack.
* Report issues in the beta https://github.com/talonvoice/beta/issues
* Add more to these docs :)

### How do I enable verbose talon debugging?

Open your talon user directory, for example `~/.talon/user` on Linux. Open the `engines.py` file in an editor and change the line containing `W2lEngine()` to include the parameter `debug=True`. If a `debug=False` parameter already exists, in the `False` should be changed to `True`.

For example:
```
w2l = W2lEngine(model="en_US", debug=True)
```

### Troubleshooting
Checkout the [troubleshooting](https://talon.wiki/troubleshooting/) for solutions to common problems.
