We’ve already created our first service and used dependency injection, but one problem with the FriendHarvester is that we’ve hardcoded the SMTP configuration inside of it. What if we wanted to re-use this class with a different configuration? Or what if our beta and production setups use different SMTP servers? Right now, both are impossible! In this tutorial we're going to see how we can also inject configuration or an entire service. In the end we're going to inject the entire SmtpMailer object and build an interface for it. Through this process we'll make our code more flexible, since it will be able to accept any object that implements MailerInterface.

</br>
<iframe src="http://drupalize.me/ajax/dmeembed/7X6YT6KTAOYXHYQSCVTZ6STGDADZMJAR" width="720" height="405" frameborder="0" scrolling="no" allowfullscreen></iframe>
</br>

**Downloads:**

[Sign in](https://drupalize.me/user/login?destination=node/1782%3Fp%3D1780) or [sign up](https://drupalize.me/pricing) to download companion files.
