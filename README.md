README
==============

to use this as template for developing third party library:

clone this repository on your lib/YourLibraryName

```
git clone git@github.com:monstrum/symfony-lib-template.git --depth=1 lib/library && rm -rf lib/library/.git

or

other branch

git clone git@github.com:monstrum/symfony-lib-template.git --depth=1 --branch=standard lib/Bundle && rm -rf lib/Bundle/.git

```

and then add this line on your main composer autoload

```
    ...
    "YourLibraryNameSpace\\": "lib/YourLibraryName/"
    ...
```

Resources
---------
