# And-AdMob-Core-V-201712.0.1
And AdMob Core V-201712.0.1

### GIT Commit
```git_commit
git init
git remote add origin https://github.com/rzrasel/And-AdMob-Core.git
git remote -v
git fetch && git checkout master
git add .
git commit -m "Add Library Project File"
git pull
git push --all
```

[![](https://jitpack.io/v/rzrasel/And-AdMob-Core.svg)](https://jitpack.io/#rzrasel/And-AdMob-Core)

### Installation
Maven Repositories Installation

```maven_repositories
allprojects {
    repositories {
        maven { url 'https://jitpack.io' }
    }
}
```
```maven_dependencies
dependencies {
    compile 'com.github.rzrasel:And-AdMob-Core:V-201712.0.1'
}
```