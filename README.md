# Cozy-sdk shell

This is a tool to quickly start an application for tests within your cozy.

Install :

```bash
npm install -g cozy-sdk
```

Usage :

```bash
mkdir my-app
cd my-app
echo '<p>Hello World !</p>' > index.html
cozy-sdk . --remote https://yourcozy.cozycloud.cc
```
