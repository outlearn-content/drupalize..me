<!--
name: drupal-dependency-injection
version : "0.1"
title : "Dependency Injection and the Art of Services and Containers"
description: "Get your object-oriented skills sharp by exploring the ideas and reasons behind dependency injection. "
homepage : "https://drupalize.me/videos/introduction-dependency-injection?p=1780"
author : "Leanna Pelham "
-->


<!-- @section -->

## Introduction to Dependency Injection

Get your object-oriented skills sharp by exploring the ideas and reasons behind dependency injection. This simple principle separates developers who write functional code from those that are able to build great, and maintanable applications. In this series, we'll see dependency injection in action, why it's important, and how it relates to services and service-oriented architecture. We'll also refactor our demo application to use a dependency injection container, using a fantastic - but simple - container called Pimple.

In this tutorial, we’ll be coding with a real example where we create a simple app to help people give their money away, we’re calling it SendMoneyToStrangers.com. We’ve already bootstrapped a small app, which you can download and use if you want to follow along. It uses an SQLite database, so if you don't have that set up, you can grab the database and find installation instructions on the [SQLite site](http://www.sqlite.org/quickstart.html). Once you SQLite, you will install the app from the demo code we are providing. We will also be using Composer to make it easier to get Pimple when we need it. If you are not familiar with Composer, you can watch the short tutorial [The Wonderful World of Composer](https://drupalize.me/videos/wonderful-world-composer) to get up and running.

</br>
<iframe src="http://drupalize.me/ajax/dmeembed/OBXNV3JEMW85EPCMJSZET7TXZCWYDZOK" width="720" height="405" frameborder="0" scrolling="no" allowfullscreen></iframe>
</br>

**Downloads:**
[Sign in](https://drupalize.me/user/login?destination=node/1779%3Fp%3D1780) or [sign up](https://drupalize.me/pricing) to download companion files.

**Additional resources:**

* [SQLite site](http://www.sqlite.org/quickstart.html)
* [The Wonderful World of Composer tutorial](https://drupalize.me/videos/wonderful-world-composer)



<!-- @section -->

## Services and Dependency Injection

Our app is small now, but as it grows, the app.php file will get harder and harder to read. The best way to fix this is to separate each different chunk of functionality into different PHP classes and methods. Each of these classes is called a “service” and the whole idea is sometimes called Service-Oriented Architecture. In this tutorial you're going to create a new service, and learn about different ways to access external objects from a service. Then, we'll set up our app to use dependency injection to get the job done right.

</br>
<iframe src="http://drupalize.me/ajax/dmeembed/IDE5AUB8CVYEACER3BQXTFWDJCUK8TCB" width="720" height="405" frameborder="0" scrolling="no" allowfullscreen></iframe>
</br>

**Downloads:**

[Sign in](https://drupalize.me/user/login?destination=node/1781%3Fp%3D1780) or [sign up](https://drupalize.me/pricing) to download companion files.

**Additional resources:**

* [Service-Oriented Architecture](http://en.wikipedia.org/wiki/Service-oriented_architecture)



<!-- @section -->

## Injecting Configuration and Services, and Using Interfaces

We’ve already created our first service and used dependency injection, but one problem with the FriendHarvester is that we’ve hardcoded the SMTP configuration inside of it. What if we wanted to re-use this class with a different configuration? Or what if our beta and production setups use different SMTP servers? Right now, both are impossible! In this tutorial we're going to see how we can also inject configuration or an entire service. In the end we're going to inject the entire SmtpMailer object and build an interface for it. Through this process we'll make our code more flexible, since it will be able to accept any object that implements MailerInterface.

</br>
<iframe src="http://drupalize.me/ajax/dmeembed/7X6YT6KTAOYXHYQSCVTZ6STGDADZMJAR" width="720" height="405" frameborder="0" scrolling="no" allowfullscreen></iframe>
</br>

**Downloads:**

[Sign in](https://drupalize.me/user/login?destination=node/1782%3Fp%3D1780) or [sign up](https://drupalize.me/pricing) to download companion files.

<!-- @section -->

## Dependency Injection Container

Our project now has services, an interface, and is fully using dependency injection. Nice work! One of the downsides of DI is that all the complexity of creating and configuring objects is now your job. This isn’t so bad since it all happens in one place and gives you so much control, but it is something we can improve! If you want to make this easier, the tool you need is called a dependency injection container. A lot of DI containers exist in PHP, but we're going to use Composer to grab the simplest one of all, called Pimple. (If you are unfamiliar with Composer, you should watch [The Wonderful World of Composer tutorial](https://drupalize.me/videos/wonderful-world-composer).)

</br>
<iframe src="http://drupalize.me/ajax/dmeembed/4GNFQJLG5TNKXL889ZA7HPU75DE7T2ZS" width="720" height="405" frameborder="0" scrolling="no" allowfullscreen></iframe>
</br>

**Downloads:**

[Sign in](https://drupalize.me/user/login?destination=node/1783%3Fp%3D1780) or [sign up](https://drupalize.me/pricing) to download companion files.

**Additional resources:**

[The Wonderful World of Composer](https://drupalize.me/videos/wonderful-world-composer)
[Composer download](http://getcomposer.org/download/)
[Pimple](http://pimple.sensiolabs.org/)

<!-- @section -->

## A Dependency Injector Container in Your Project

Now it's time for you to use dependency injection containers in your own projects. In this tutorial we talk briefly about some other containers out there you might want to check out.

</br>
<iframe src="http://drupalize.me/ajax/dmeembed/C8YNBDN8LPSXMXWAWSYQUFGUAYAZFUM9" width="720" height="405" frameborder="0" scrolling="no" allowfullscreen></iframe>
</br>
