---
description: >-
  This page will give you some tips and tricks you can do with your profile on
  TTGit
---

# Customizing your profile

When you create your TTGit account for the first time, you'll notice that you have a blank bio, along with a overview of your profile. In fact, you can add any profile overview to your account, and treat it as a repository.

### How it works

This feature is hidden from most people that use Forgejo or Gitea, especially those that GitHub's about you feature. This time around, you have that same feature on TTGit, with the same way you use it on other providers. It functions like a readme file in Markdown while acting on your profile to help others understand who you are.

### Getting started

To start off, you should have a TTGit account. After you created your account, you can change a few things which we will go over.

#### Adding a bio

Adding bio is easy to do, and does not require you to have a repository on your account. You can do this by going into your account settings and go to the profile section. Here, you can change your username, full name, your website, and location. For this, we will choose the "Biography" text box. Type in anything that describes you, who you are, or a simple greeting.

<figure><img src="../.gitbook/assets/Screenshot 2024-03-03 160512.png" alt=""><figcaption><p>Figure 1: Example</p></figcaption></figure>

Here, you can write anything about yourself. The catch however is that there is no markdown as it is just a simple textbox but written to use a bio on your profile. Once you have that, you can save your changes by clicking the "Update Profile" button. When you go back to your profile, you will see what you wrote. Your text will also be shown publicly, so keep that in mind.

<figure><img src="../.gitbook/assets/Screenshot 2024-03-03 160826.png" alt=""><figcaption><p>Figure 2: The output of the text.</p></figcaption></figure>

#### Adding a overview

Many people want to add a overview to their profile as a way to figure out what things you like, languages you write in, or anything else that describes you. To get this feature, follow the steps below.

1. Create a repository named `.profile`. Make sure that you have a README preloaded.
2. Edit the README file inside of the repository. You can write in Markdown for better writing.
3. Commit your changes. If needed, you can signoff the commit. Changes you made will be seen publicly.
4. Go back to your profile and check if the overview tab is visible.  You should see your changes that you put in to the README file.

<figure><img src="../.gitbook/assets/Screenshot 2024-03-03 161553.png" alt=""><figcaption><p>Figure 3: Overview example</p></figcaption></figure>

You can always change your file at any time you wish.

### Sources

* [Profile readme](https://docs.gitea.com/usage/profile-readme)
