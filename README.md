# Introduction
This repository aims to be the ultimate guide for how-tos and increasing productivity with developer tools

## Shell
* Z shell
  * [zsh](https://github.com/robbyrussell/oh-my-zsh/wiki/Installing-ZSH): An enhanced version of bourne shell
  * [Oh my zsh](https://github.com/robbyrussell/oh-my-zsh): Comes with many plugins to make the command line kick ass!
  * [zsh autosuggestion](https://github.com/zsh-users/zsh-autosuggestions): Cos no one got time to enter type in the full command all the time

## React
* [React with webpack 4 and babel 7](https://medium.freecodecamp.org/how-to-combine-webpack-4-and-babel-7-to-create-a-fantastic-react-app-845797e036ff)

## Nodejs
* [logging in express with morgan and bunyan](https://medium.com/@tobydigz/logging-in-a-node-express-app-with-morgan-and-bunyan-30d9bf2c07a)
* [To ORM or not, that is the question](https://blog.logrocket.com/why-you-should-avoid-orms-with-examples-in-node-js-e0baab73fa5)

## Kubernetes
[nginx ingress](https://www.digitalocean.com/community/tutorials/how-to-set-up-an-nginx-ingress-with-cert-manager-on-digitalocean-kubernetes)
[make yourself cluster admin on GKE](https://medium.com/@kevinsimper/make-yourself-cluster-admin-on-google-cloud-kubernetes-engine-a84e13dfe66d)

### Proxy
By default, pods are private and are not accessible fromm the external world.
Running `kubectl proxy` sets up a proxy from our local computer to the kubernetes API
Then, we can access the pod via `http://localhost:8001/api/v1/namespaces/default/pods/$POD_NAME/proxy`
