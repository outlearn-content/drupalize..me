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
