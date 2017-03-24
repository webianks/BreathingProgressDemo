[![Android Arsenal](https://img.shields.io/badge/Android%20Arsenal-BreathingProgressDemo-brightgreen.svg?style=flat)](http://android-arsenal.com/details/3/4111)

# BreathingProgressDemo
Here comes a nice little breathing progress which you can show in your Android apps.
# Customisations
Customisations are under development. They will be here in near future.

# Preview
<img src="http://webianks.com/breathing_progress/breather.gif" height="700" width="400" >

# **Setup for Developers**

1.Make sure you have downloaded the latest version of Android Studio. It works on Linux, Windows and Mac. Download the correct version for your OS
2.Go to the project repo and fork it by clicking "Fork"
3.If you are working on Windows, download Git Bash for Windows to get a full Unix bash with Git functionality
4.Clone the repo to your desktop git clone git@github.com:your_name/BreathingProgressDemo.git
5.Open the project with Android Studio

# **Configure remotes**

When a repository is cloned, it has a default remote called origin that points to your fork on GitHub, not the original repository it was forked from. To keep track of the original repository, you should add another remote named upstream:

1.Open terminal or git bash in your local repository and type:

    git remote add upstream https://github.com/BreathingProgressDemo.git

    Run git remote -v to check the status, you should see something like the following:

        origin https://github.com/YOUR_USERNAME/BreathingProgressDemo.git (fetch)

        origin https://github.com/YOUR_USERNAME/BreathingProgressDemo.git (push)

        upstream https://github.com/BreathingProgressDemo.git (fetch)

        upstream https://github.com/BreathingProgressDemo.git (push)

2.To update your local copy with remote changes, run the following:

    git fetch upstream

    git merge upstream/master

    This will give you an exact copy of the current remote, make sure you don't have any local changes.

# **Contributing and developing a feature**

1.Make sure you are in the master branch git checkout master
2.Sync your copy git pull
3.Create a new branch with a meaningful name git checkout -b branch_name
4.Develop your feature on Android Studio and run it using the emulator or connecting your own Android device
5.Clean your project from Android Studio Build/Clean project
6.Add the files you changed git add file_name (avoid using git add .)
7.Commit your changes git commit -m "Message briefly explaining the feature"
8.Keep one commit per feature. If you forgot to add changes, you can edit the previous commit git commit --amend
9.Push to your repo git push origin branch-name
10.Go into the Github repo and create a pull request explaining your changes
11.If you are requested to make changes, edit your commit using git commit --amend, push again and the pull request will edit automatically
12.You will need to add a message on the pull request notifying your changes to your reviewer.

## License

```
BreathingProgress library for Android
Copyright (c) 2016 Ramankit Singh (http://github.com/webianks).

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
