# Empty Hugo Theme

This is an empty theme for the [Hugo Static Site Generator](https://gohugo.io/).

## Description
 
I am a big fan of Hugo, but recently a change was made to the theme generator where instead of giving you a mostly empty file structure with only the minimum files needed to get a Hugo site to run, it now generates a bunch of dummy files and files all the files with boiler plate code. I think this change is for the best, as Hugo does have a bit of a learning curve to it, but I am a little annoyed that Hugo doesn't even provide an option to generate an old, mostly empty theme skeleton. As a result, I generated an empty theme with the last version with an older machine running Debian 12 using Hugo V0.111.3.

## Getting Started

### Installing

* [Install Hugo](https://gohugo.io/installation/)
* In a terminal, navigate to the directory where you would like to save your Hugo site and run the following command:
   ```hugo new site <enter site name here>```
* Navigate to the "themes" folder of your Hugo site and fetch this repo. The final path should look something like <your site>/themes/empty-hugo-theme/
* OPTIONAL - rename the folder something different from "empty-hugo-theme"
* Open your hugo.toml file and add a line under the title referencing either "empty-hugo-theme" or whatever you renamed the theme, like this:
    ```title = "empty-hugo-theme"```

## Help

If you are new to Hugo, I highly recommend looking through the ["Getting Started"](https://gohugo.io/getting-started/) section of the official docs. 

## Authors

[Sheldon Codling](https://www.sheldonc.ca)

## Acknowledgments

* [Hugo](https://gohugo.io/) for being an amazing static site generator and having the old version generate me this empty skeleton.
