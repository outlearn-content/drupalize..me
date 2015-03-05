<!--
name: drupal-ladder
version : "0.1"
title : "The Learn Drupal Ladder"
description: "In this series we introduce the Drupal Ladder project, and walk through the lessons in the Drupal ladder."
homepage : "https://drupalize.me/videos/overview-learn-drupal-ladder?p=1176"
author : "Addison Berry"
-->


<!-- @section -->

## Overview of the Learn Drupal Ladder

In this series we introduce the [Drupal Ladder project](http://drupalladder.org/), and walk through the lessons in the [Drupal ladder](http://drupalladder.org/ladder/ee503327-50be-1904-8d04-9499098cad64). This community initiative was created to get more people to help with work on Drupal core. It achieves this by creating lessons that start with the very basic skills needed to help and working their way up the ladder into more skills and tasks. Our series begins with a short presentation about the project, and then the subsequent videos walk through the lessons from the ladder, starting with installing Drupal locally.

</br>
<iframe src="http://drupalize.me/ajax/dmeembed/SB3JHSB7DKKYR3BDKHKFQEYDGYVFITDQ" width="720" height="405" frameborder="0" scrolling="no" allowfullscreen></iframe>
</br>

**Additional resources:**

* [Drupal Ladder website](http://drupalladder.org/)
* [Drupal Ladder profile](http://drupal.org/project/learn)
* [Drupal Ladder coordination group](http://groups.drupal.org/drupal-ladder)
* [Drupal Ladder IRC channel: #drupal-ladder](http://http//drupalladder.org/chat)

<!-- @section -->

## Install Drupal Locally with Dev Desktop

In this first step of the Learn Drupal Ladder we will install Drupal on our computer. This follows the instructions to [Install Drupal locally](http://drupalladder.org/lesson/8daa1222-481d-fc54-a9bf-9d9ccc1ae702) on learndrupal.org. We start by getting and installing the [Dev Desktop](http://www.acquia.com/products-services/dev-desktop), which is an all-in-one web server which comes with Drupal 7. We then install our own Drupal 8 site in Dev Desktop.

</br>
<iframe src="http://drupalize.me/ajax/dmeembed/HFJJBHAJTYS4YHVWGTMSHE8EATEW784H" width="720" height="405" frameborder="0" scrolling="no" allowfullscreen></iframe>
</br>

**Additional resources:**

If you do not wish to use Dev Desktop as your local web server, we have videos for three other web servers, based on operating system:

* [Installing WampServer (for Windows)](https://drupalize.me/videos/installing-wampserver)
* [Installing MAMP web server (for Mac)](https://drupalize.me/videos/installing-mamp-web-server)
* [Installing a web server on Ubuntu](https://drupalize.me/videos/installing-web-server-ubuntu)


<!-- @section -->

## Install Git

In this video we walk through getting Git version control installed, and then show how to do a few basic things, including how to get a copy of the latest Drupal development code. This video follows the instructions found in the [Install Git](http://drupalladder.org/lesson/027b5839-7a74-af04-6905-fee2d01c7ef4) lesson on learndrupal.org.

This video is installing Git on Windows, because it has the most steps involved. Installation on Mac and Linux is very simple, in that they do not have a wizard to walk through, so they are not demonstrated. All commands used on the command line in the video work on Windows, Mac, and Linux, because Windows is using the Git Bash shell which is part of the Git installation.

</br>
<iframe src="http://drupalize.me/ajax/dmeembed/MYNRIM98KOHOQCSVSGM97XFHJA3SQHBI" width="720" height="405" frameborder="0" scrolling="no" allowfullscreen></iframe>
</br>

**Additional resources:**

* [Git download page](http://git-scm.com/downloads)


<!-- @section -->

## Getting Started in the Issue Queue

In this step we turn our attention to Drupal.org and the community issue queue. This is where all of the active work for Drupal core takes place. We will look at the queue and create our issue to see how it works. This video follows the instructions for the [Getting started in the issue queue lesson](http://drupalladder.org/lesson/1d498fa2-d3e4-5754-9160-757d219e8032) on learndrupal.org.

</br>
<iframe src="http://drupalize.me/ajax/dmeembed/PHLFFWAYFDEGAD2L2MR8A4CMT7JEI6ZL" width="720" height="405" frameborder="0" scrolling="no" allowfullscreen></iframe>
</br>


<!-- @section -->

## Test Patches

In this video we will walk through the process of testing existing patches in the Drupal.org issue queue. We will read an issue, download and apply the patch with Git, and then test it to see if it works. This video follows the instructions on the Test patches lesson on learndrupal.org.

The lines that I have in my .bash_profile (shown at the end of this video) to add the Git branch to my command line prompt is:

    function parse_git_branch { git branch --no-color 2> /dev/null | sed -e '/^[^*]/d' -e 's/* \(.*\)/(\1)/' } export PS1="\h:\W \u\$(parse_git_branch)\$ "

I'm using a Mac, so your mileage may vary on other systems.

</br>
<iframe src="http://drupalize.me/ajax/dmeembed/KKJB8K2B7FBOQZT3ALHGU2HXHVVQSRPA" width="720" height="405" frameborder="0" scrolling="no" allowfullscreen></iframe>
</br>

<!-- @section -->

## Write a Patch

In this video we will write our own patch to resolve an issue. We will take a screenshot of the issue before and after our patch, and upload the images and patch to the Drupal.org issue queue. This video follows the instructions in the [Write a patch lesson](http://drupalladder.org/lesson/72a836e6-b408-a7a4-1923-8788761b2608) on learndrupal.org.

</br>
<iframe src="http://drupalize.me/ajax/dmeembed/S6FNUYDNPHNUTEVOLBGNGQJ3V4HYKHVD" width="720" height="405" frameborder="0" scrolling="no" allowfullscreen></iframe>
</br>
