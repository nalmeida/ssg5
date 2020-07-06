# ssg5

This is a copy of the original `ssg5` shell script made by Roman Zolotarev. Check out his post with the full documentation at: https://rgz.ee/bin/ssg5

# Install

One ease way to install it in your project is as a `git submodule`. In your project add it as:

```
$ git submodule add https://github.com/nalmeida/ssg5 ssg5
```

As the `ssg5` submodule file is configured as `chmod +x`, now you are able use locally:

```
$ ./ssg5/ssg5 src dst "Your Title" ./
```

It is very useful to have it as a submodule in order to deploy it to some sort of static site platform like **Netlify**.

# Updating

In order to update the `ssg5` submodule, rund:

```
$ git submodule update --recursive --remote
```

## Sample project

Sample project: https://github.com/nalmeida/ssg5-test

