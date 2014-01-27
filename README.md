Storm-developer-setup
=======================
- A [NeverwinterDP](https://github.com/DemandCube/NeverwinterDP) and [DemandCube](https://github.com/DemandCube) Project

Setup a box to develop storm

Install
====
Step 1) Setup
----

- [DemandCube Developer Setup](https://github.com/DemandCube/developer-setup)

```
git clone https://github.com/DemandCube/developer-setup.git
cd developer-setup
./setup.sh
```
Step 2) Run
----

```
git clone https://github.com/DemandCube/Storm-developer-setup.git
cd Storm-developer-setup
vagrant up
vagrant ssh
```

Keep your fork updated
====
[Github Fork a Repo Help](https://help.github.com/articles/fork-a-repo)


- Add the remote, call it "upstream":

```
git remote add upstream git@github.com:DemandCube/Storm-developer-setup.git
```
- Fetch all the branches of that remote into remote-tracking branches,
- such as upstream/master:

```
git fetch upstream
```
- Make sure that you're on your master branch:

```
git checkout master
```
- Merge upstream changes to your master branch

```
git merge upstream/master
```
