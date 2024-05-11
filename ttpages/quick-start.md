---
description: A quick start guide for setting up TTPages
---

# Quick start

### Requirements

To set up TTPages on TTGit, please be sure to have the following checked:

* Having a non-private repo
* Static-only files
* Password and email (if using Git-scm)

### Creating the repo

To start off, create a simple and easy-to-name repository that can be reached by others when accessing your site. If you want to use your username with the TTPages domain, it should look like this:

```
owner.ttnrtsite.io
```

Make sure that there are no spaces in between your repo name. To make our site easier, set the default branch name as `gh-pages` to add your static files to that branch only.&#x20;

### Adding your code

Once you created your repository, you can either:

* Add your code manually using the "New file" option.
* Using Git-scm (if making bigger changes)

In this case, we will add our index html file to the repo using the "New file" option. This allows us to use the built-in editor for easier edits. Once you added your index file, commit your changes to push your changes.

### Locating your site

{% hint style="warning" %}
Your code that you push to your repository will be public to anyone on the internet. Make sure you have no personal information to any of your HTML pages you added.
{% endhint %}

You can go to your website by using this URL below.

```
owner.ttnrtsite.io/REPO_NAME
```

Or if your repo name is the pages domain with owner name

```
owner.ttnrtsite.io
```

Our site we made is using your username to access it. You can see it works as any other page's provider.
