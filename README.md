# My awesome app 🔥🔥🔥🔥🔥


![](assets/icons/png/web-development.png)

It is a realy realy big secret... stay tuned...


---

## Existing opensource tools

### Edit code

- [Theia](https://theia-ide.org/): Cloud & Desktop IDE Platform

### Run code

- []()
- []()
- []()

### Generate template code


--- 

## Hold on!!! 🛑🛑🛑

You need max node 11!

---

### Building

Using this the workflow above, GitHub will build your app every time you push a commit.


### Releasing

When you want to create a new release, follow these steps:

- Update the version in your project's package.json file (e.g. 1.2.3)
- Commit that change (git commit -am v1.2.3)
- Tag your commit (git tag v1.2.3). Make sure your tag name's format is v*.*.*. Your workflow will use this tag to detect when to create a release 
- Push your changes to GitHub (git push && git push --tags)

After building successfully, the action will publish your release artifacts. By default, a new release draft will be created on GitHub with download links for your app. If you want to change this behavior, have a look at the electron-builder docs.

---
