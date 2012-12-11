# Intro

**Drupal YASnippet** is a collection of snippets for use with [YASnippet](https://github.com/capitaomorte/yasnippet/ "YASnippet") templating system for Emacs. These are not snippets for general PHP, CSS or SASS use. They are only bits that make your life in Drupal eaiser.

# Installation

Follow the instructions to install YASnippet: https://github.com/capitaomorte/yasnippet/blob/master/README.mdown

Clone this repository into your ~/.emacs.d directory:
````
cd ~/.emacs.d
git clone https://github.com/vml-msmith/drupal-yasnippet.git
````

Add this line to your `.emacs` file *AFTER* the YASnippet bits:
````
(setq yas/root-directory "~/.emacs.d/drupal-yasnippet")
(yas/load-directory yas/root-directory)
````

Restart Emacs or reload your .emacs file:
````
M-x load-file
<RETURN>
~/.emacs.d/.emacs
````

You should now have Drupal YASnippets.

# Usage

## Invocation

From within a PHP-mode file (module, inc, install, php) just type the name of a hook that is defined, and press tab.
````
hook_init<TAB>
````

The default template will be spit out for you ready for input.


## Standards

These snippets try to follow Drupal's coding standards where appropriate.
Every snippet that creates a function will be prepended with /** **/
documentation, for example. hook_form wil

<More Comming Soon!>

## List of Snippets

<Comming Soon!>
