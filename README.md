# nbdev template

Use this template to more easily create your [nbdev](https://nbdev.fast.ai/) project.

_If you are using an older version of this template, and want to upgrade to the theme-based version, see [this helper script](https://gist.github.com/hamelsmu/977e82a23dcd8dcff9058079cb4a8f18) (more explanation of what this means is contained in the link to the script)_.


# What I modified

Please modified the .gitmodules

```
[submodule "manuscript"]
	path = manuscript
	url = https://github.com/btrspg/latex-template.git

```

Change the url to a manuscript of the project that created from the [template](https://github.com/btrspg/latex-template.git). It will really help when you write something, and want to make it be a manuscript.

Whenever modified the url, you must update the submodule.

```
git submodule update --init
```

or maybe you can just 

```
git submodule add youownrepo.git manuscript
```
