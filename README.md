# octo-captcha-generator
Simple captcha generator written in java

### Require simpleCaptcha
Download [SimpleCaptcha](http://simplecaptcha.sourceforge.net) to the folder:

```
$ curl -O http://www.java2s.com/Code/JarDownload/simplecaptcha/simplecaptcha-1.2.1.jar.zip
```

Extract SimpleCaptcha:

```
$ jar xf simplecaptcha-1.2.1.jar.zip
```

Create directories for dataSet:
```
mkdir data && cd data && mkdir test_data valid_data train_data
```

Run SimpleCaptcha:

```
$ javac Main.java && java Main
```

By default it will generate:
```
50000 training captcha images
20000 validation captcha images
1000  test captcha images
```
