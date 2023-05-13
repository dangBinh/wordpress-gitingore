# Why Exclude Most Files

I update plugins on the server using the built-in WordPress update functionality. When a plugin is updated on a server in this way, it becomes out of sync with the Git repo. The particular situation I want to avoid is pushing an outdated version of a plugin from my local machine to the live site.

This same argument applies to WordPress core and theme files.

# What I Include

I only include plugins and themes that are specific to the project. For example, if I’m creating a custom theme for the project, the theme gets included in the repo. If I write a plugin specific to this project, it gets included in the repo.

# What I Don’t Include

Any plugin or theme that lives somewhere else is not included in the repo. Some examples include:

a plugin available in the WordPress.org repo
a parent theme
a plugin that includes its own update routine
