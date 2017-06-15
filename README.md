# Hot Topic

CF Serverless done right.

# What is this?

PaaS is about just pushing code. Serverless is about just pushing functions. Really they're both about abstractions to let you write stateless pieces of code that a platform can manage, scale and orchestrate for you. Apps are just stateless containers triggered by routes and scaled by `cf scale`. Functions are the same thing, but triggered by events in a shared message queue and being auto-scaled by message queue length. Hot Topic is a proof of concept that uses a `cf map-event` command, similar to `cf map-route` to make FaaS and PaaS work together in a _really_ nice, simple and orthogonal way.

# Demo!

<iframe width="560" height="315" src="https://www.youtube.com/embed/vJsmE88ROa8" frameborder="0" allowfullscreen></iframe>

## Repos

* [hottopic](https://github.com/teddyking/hottopic)
* [hackdayfunction](https://github.com/Samze/hackdayfunction)
* [cfevents](https://github.com/Samze/cfevents)
* [mapevent](https://github.com/Samze/mapevent)
