---
layout: default
title: 'wp user meta update'
---

`wp user meta update` - Update a meta field.

<hr />

&lt;user&gt;
: The user login, user email, or user ID of the user to update metadata for.

&lt;key&gt;
: The metadata key.

&lt;value&gt;
: The new metadata value.

[\--format=&lt;format&gt;]
: The serialization format for the value. Default is plaintext.

### GLOBAL PARAMETERS

  \--path=&lt;path&gt;
      Path to the WordPress files

  \--url=&lt;url&gt;
      Pretend request came from given URL. In multisite, this argument is how the target site is specified.

  \--user=&lt;id|login|email&gt;
      Set the WordPress user

  \--skip-plugins[=&lt;plugin&gt;]
      Skip loading all or some plugins

  \--skip-themes[=&lt;theme&gt;]
      Skip loading all or some themes

  \--require=&lt;path&gt;
      Load PHP file before running the command (may be used more than once)

  \--[no-]color
      Whether to colorize the output

  \--debug
      Show all PHP errors; add verbosity to WP-CLI bootstrap

  \--prompt
      Prompt the user to enter values for all command arguments

  \--quiet
      Suppress informational messages



