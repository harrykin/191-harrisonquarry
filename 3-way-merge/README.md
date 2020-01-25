# README
## INF191A assignment using Git Kata: 3-Way Merge
This Readme file would contain all the useful information on the Repo

8. What is the output of `git log --oneline --graph --all`
```
* d6bf1d2 Added Readme file
| * 67154c5 Added favorite greeting
|/  
* 1b50551 Add content to greeting.txt
* 1d7d925 Add file greeting.txt
```

9. Output of "Diff"
```
diff --git a/README.md b/README.md
deleted file mode 100644
index faf5fce..0000000
--- a/README.md
+++ /dev/null
@@ -1,3 +0,0 @@
-# README
-## INF191A assignment using Git Kata: 3-Way Merge
-This Readme file would contain all the useful information on the Repo
diff --git a/greeting.txt b/greeting.txt
index ce01362..42c3097 100644
--- a/greeting.txt
+++ b/greeting.txt
@@ -1 +1 @@
-hello
+Greetings Earthlings, we come in peace
```
