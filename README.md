<!-- ghmig:moved -->
> **This repository has moved to [https://git.navicore.tech/navicore/mykc](https://git.navicore.tech/navicore/mykc).**
>
> The GitHub copy is archived and no longer maintained.

My GH
=========

A rust cli and tui created as a learning experience to explore meta programming
with openapi specs as input.


Repo Setup / Initialization
--------------

You don't need this info unless you are going to update the code generated from
the openapi spec.

Download the api spec and run the generator

```bash
curl -o api/api.github.com.yaml https://raw.githubusercontent.com/github/rest-api-description/main/descriptions/api.github.com/api.github.com.yaml
brew install openapi-generator
openapi-generator generate -i api/api.github.com.yaml -g rust 

#-o pkg/adminapi --package-name adminapi --git-host umc/pkg


```