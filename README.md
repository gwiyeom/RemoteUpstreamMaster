# RemoteUpstreamMaster

test
#1 내용을 수정

---
test1
## branch master에서 
## pull  (remoteUpsreamMaster에서 변경한 내용 받음 O)

remote: Enumerating objects: 8, done.
remote: Counting objects: 100% (8/8), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (4/4), 1.29 KiB | 8.00 KiB/s, done.
From https://github.com/gwiyeom/RemoteUpstreamMaster
   b768ece..70d9a82  main       -> upsream/main
Updating b768ece..70d9a82
Fast-forward
 README.md | 8 ++++++--
 1 file changed, 6 insertions(+), 2 deletions(-)
 
## pull upstream/master (remoteUpsreamMaster에서 변경한 내용 받음 O)

remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 737 bytes | 5.00 KiB/s, done.
From https://github.com/gwiyeom/RemoteUpstreamMaster
 * branch            main       -> FETCH_HEAD
   70d9a82..29130b1  main       -> upstream/main
Updating 70d9a82..29130b1
Fast-forward
 README.md | 6 +++---
 1 file changed, 3 insertions(+), 3 deletions(-)
 
 
 ## branch #2에서 
 ## pull  (remoteUpsreamMaster에서 변경한 내용 받음 X)
 
 here is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=<remote>/<branch> #2
## pull upstream/master (remoteUpsreamMaster에서 변경한 내용 받음 O)
 
From https://github.com/gwiyeom/RemoteUpstreamMaster
 * branch            main       -> FETCH_HEAD
Updating 29130b1..8381717
Fast-forward
 README.md | 35 +++++++++++++++++++++++++++++++++--
 1 file changed, 33 insertions(+), 2 deletions(-)
