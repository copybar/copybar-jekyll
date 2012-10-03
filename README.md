# Copybar-Jekyll

Jekyll Bootstrap preconfigured with Copybar.  Put your username in _includes/JB/setup.  New pages and posts come loaded with Copybar elements, ready for editing, right in your browser.  

## Quickstart Guide

1. Download or clone this repository
2. In the terminal, cd *the root directory of what you downloaded*
3. With a text editor, edit '_includes/JB/setup' to include your Copybar username
4. Generate your first post with the command 'rake post title='Hello World'
5. Run your new blog with the command 'jekyll --server'
6. Visit your blog at <http://localhost:4000>
7. Begin editing with Copybar

## Copybar Configuration

Enter your Copybar account name in:
_includes/JB/setup

Every new page or blog post will be generated with Copybar elements containing your username and page title.  Main pages come with 3 copybar elements: main content, secondary content, and sidebar right.

To create additional Copybar elements, you need to modify some layout files:
_includes/themes/twitter/post.html
_includes/themes/twitter/page.html

Use the Copybar elements you find as examples.  You can create any number of these elements, and put them almost anywhere on this site.

It's best to study how Jekyll renders template files if you want to customize this way.  See this [documentation](http://jekyllbootstrap.com/lessons/jekyll-introduction.html#initial_setup).

## Running Locally

Jekyll is a Ruby gem.  You will need ruby on your machine to run it.

Enter this command in your terminal, when you are in the root directory your blog:
jekyll --server

If it runs, you can visit <http://localhost:4000> and begin editing your Copybar elements

## Deploying to Github pages

You can deploy this blog just like any other Jekyll blog, using git and github pages.

<https://help.github.com/articles/using-jekyll-with-pages>


## Usage for Jekyll Bootstrap

This version of Jekyll is specifically wired with Twitter Bootstrap and jQuery.  The entire Jekyll workflow is available via the command line and your text editor.

For all usage and documentation please see: <http://jekyllbootstrap.com>

## Version of Jekyll

0.2.13 - stable and versioned using [semantic versioning](http://semver.org/).


## License

[Creative Commons](http://creativecommons.org/licenses/by-nc-sa/3.0/)



<script src="//copybar.io/mhurwi/readme-test.js">

</script>

