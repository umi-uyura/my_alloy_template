My Alloy Template
=================

Titanium Alloy project template.

Feature
--------

* Alloy-base template
* Jade & Stylus
* Some changes in tiapp.xml

Usage
-----

```
$ git clone https://github.com/umi-uyura/my_alloy_template
$ titanium create --template ./my_alloy_template
```

or 

```
$ titanium create --template https://github.com/umi-uyura/my_alloy_template/raw/master/my_alloy_template.zip
```

Archive
------

```
$ git archive HEAD --format=zip --worktree-attributes > my_alloy_template.zip
```

Update template
----------------

```
$ mkdir -p template_tmp/Resources
$ cp template/tiapp.xml template_tmp
$ alloy new template_tmp
```

And, it will properly reflect the difference between *template* and *template_tmp*.
