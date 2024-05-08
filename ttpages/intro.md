# Intro

{% hint style="warning" %}
We made changes to use Meli as our pages server! This documentation section is decrypted and will now use the Meli section for setting up TTPages! Other changes may occur later on!
{% endhint %}

On this page, we will cover on how our TTPages service works for TTGit, including a way to use it with your repo you may have. You should keep note on the following as well:

* This service is somewhat different from other providers
* This service does not render markdown files
* This service only uses static files

With that out of the way, let's begin on using TTPages.

### Repo configuration

We should have a repo created for TTPages. For this, we need to create the repo with this name:

`[USERNAME].ttnrtsite.io`

Alternatively, you can name your repo anything you want without the domain at the end. This is mostly different for those that want more than one site at a time. See more below.

Be sure to replace `[USERNAME]` with your account name. Once that is done, you can create the repo and send it to the database. It is also important to add the `gitea-pages` topic to the repo due to the program requiring it. You should also create a branch named `gitea-pages`, where the static files will go into, as the server will not use any other branch. This makes it easy for when you use a static site generator as a example. Once you have that, you can start adding your static files.

### Adding static files

{% hint style="info" %}
Make sure you use the gitea-pages branch. The server will only interact with this branch. Do not make a pull request, as that might mess something up.
{% endhint %}

You can start off with a simple HTML document. You should name the file as `index.html`. For the best editing experience, we recommend using Visual Studio Code, along with a Live Server that can read your HTML document. It is up to you on what editor you like using. Once you have your content saved to the file, you can either:

1. Upload the file
2. Copy contents to the built-in editor online

After that, you need a commit message. Think of a good one. Once you have that, you should review your changes before pushing them. If you messed something up, you can always change it. Otherwise, you can safely push your changes.

### Visiting your site

Once you have your file committed, it will be rendered to the system. To see your website, go to your address bar and type in this:

```
[USERNAME].ttnrtsite.io
```

Remember to change `[USERNAME]` with your account name. You should see your site in a few seconds. If you like to use a static site generator, please see our examples on our Organization.

### Quick notes

In case you want to have a site that is not in the same repository as your main one, you can make a repository with any name you like, while adding your default branch name as `gitea-pages` if only have already-generated static files. To access your website with the repo name, the URL might look like this:

```
[USERNAME].ttnrtsite.io/[YOUR_REPO_NAME]
```

Be sure to add a slash at the end of the URL to allow the server to find what repo your website is located on. The code only looks up your website if you add a slash at the end, otherwise you will get a 404 error message.
