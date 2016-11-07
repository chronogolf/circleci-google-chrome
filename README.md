# Circleci Use Chrome Stable Version

To force the use of the latest stable version of Chrome on Circle CI, define those lines in your circle.yml configuration file

```
dependencies:
  pre:
    - curl -s https://raw.githubusercontent.com/chronogolf/circleci-update-google-chrome/master/use_chrome_stable_version.sh | bash
```

