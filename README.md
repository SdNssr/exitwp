# ExitWP

This is a fork of exitwp which cleans internal urls by removing the domain name and scheme, e.g:

`<a href="https://www.example.com/this/is/a/example"></a>`

Becomes:

`<a href="/this/is/a/example"></a>`

This is useful for locally testing your jekyll site.

To use this, you have to edit the `internal_domain` attribute in the [config.yaml](/config.yaml "config.yaml") file to your site's hostname.

For further documentation, read the [README.rst](/README.rst "README.rst") file.