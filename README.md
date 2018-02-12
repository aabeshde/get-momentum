[Momentum]: https://momentumdash.com/
[Get Momentum]: https://github.com/chingubelugas/get-momentum
[Resolving Merge Conflicts]: https://help.github.com/articles/resolving-merge-conflicts-after-a-git-rebase/

# Reverb Momentum
reverse-engineering this chrome app: [Momentum][] 

##Description
Reverb Momentum will gently take over your default home screen on Google Chrome with a new inspirational photo each day. It will also assist you in making your days more productive with a daily reminder of your goal, a todo list, a place to save your favorite links, a pomodoro timer, and even a weather check. 

##Getting Started

To-do
- Clone the repo from your Github account to your machine. 
- CD into your Get Momentum directory and run the following commands:
  - npm install (installs all of the dependencies needed)
  - git remote add upstream https://github.com/chingubelugas/get-momentum (set a remote to the main repo so later you can pull down updates from other team members)
  - npm run start

##Wireframes
![alt tag](https://raw.githubusercontent.com/username/get-momentum/master/client/assets/wireframe1.png)

##Stack
1. jQuery
2. Node

##Roadmap
v1.0 Reverse engineer the front end of the [Momentum][] app, fetch random photos, random quotes and weather data, build a todo list and pomodoro timer.

###Updating the Project
1. Commit your changes or remove them from staging
2. Check your remotes by running git remote -v. You should see your origins and the upstreams.

```javascript
origin	https://github.com/vientang/get-momentum.git (fetch)
origin	https://github.com/vientang/get-momentum.git (push)
upstream	https://github.com/chingubelugas/get-momentum.git (fetch)
upstream	https://github.com/chingubelugas/get-momentum.git (push)
```

3. Run git pull --rebase upstream master
4. You now have the latest code! 
5. Do you see merge conflicts? This [Resolving Merge Conflicts][] article is pretty good for explaining what to do.

