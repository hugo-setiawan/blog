+++
title = 'Hello World'
date = 2023-10-15T20:19:00+07:00
draft = false
+++

Still empty, hope i don't forget to fill this in soon.


Well, here's at least how i installed Hugo (the framework) on my machine.

{{< highlight powershell >}}
winget install Hugo.Hugo.Extended
{{< /highlight >}}

Then, I created a [repository on GitHub](github.com/hugo-setiawan/blog) (since i plan on hosting this blog using GitHub pages).

After cloning said repository onto my local machine, i initialized the Hugo site inside the folder, making sure the root of the site is at the root of the repository.

{{< highlight powershell >}}
# the --force flag is needed since the repository is non-empty thanks to the .git folder
hugo new site .\ --force
{{< /highlight >}}

After installing a theme (I used [Etch](https://github.com/LukasJoswiak/etch)), I proceeded to follow some basic examples, and managed to create this first page!

