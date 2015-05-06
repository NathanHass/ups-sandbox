A small starter kit for test environments

### Getting Started Started


**Navigate to your `Sites` directory**

```
cd ~/Sites
```

**Clone this directory**
```
git clone git@github.com:NathanHass/ups-sandbox.git && cd ups-sandbox && rm -rf .git
```

**If you want it to be called something other than `ups-sandbox`, you can change it like this**
```
mv ~/Sites/ups-sandbox3 ~/Sites/desired_directory_name
```


**Now it's time to build this thing out. First run a bower install**
```
bower install
```

**Next let's start watching for changes with a compass watch**
```
compass watch
```

**Finally let's get a simple server running**
```
python -m SimpleHTTPServer
```

Bam, you did it! Now visit [localhost:8000](http://localhost:8000/) and make a thing!
