TravisAndroidExample is a sample project demonstrating how to distribute an Android app to GitHub and Play Store releases using [Travis CI](https://travis-ci.com/).

You can find the accompanying blog [here](https://jfenn.me/blog/2018-11-14-Continuous-Integration).

Relevant files: 

- [.travis.yml](./.travis.yml)
- [build.gradle](./build.gradle)
- [app/build.gradle](./app/build.gradle)
- [key.jks](./key.jks) (a dummy file)
- [service.json](./service.json) (also a dummy file)
- [secrets.tar](./secrets.tar) (a dummy file composed of the two dummy files)
- [secrets.tar.enc](./secrets.tar.enc) (this shouldn't be a dummy file - since it is encrypted you will never know - but in this sample project it is)
