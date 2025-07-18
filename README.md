# R
Started by an SCM change
Running as SYSTEM
[EnvInject] - Loading node environment variables.
Building on the built-in node in workspace /var/lib/jenkins/workspace/freerdp-nightly-source
[WS-CLEANUP] Deleting project workspace...
[WS-CLEANUP] Deferred wipeout is used...
[WS-CLEANUP] Done
The recommended git tool is: NONE
No credentials specified
Cloning the remote Git repository
Cloning repository https://github.com/FreeRDP/FreeRDP.git
 > git init /var/lib/jenkins/workspace/freerdp-nightly-source/source # timeout=10
Fetching upstream changes from https://github.com/FreeRDP/FreeRDP.git
 > git --version # timeout=10
 > git --version # 'git version 2.43.0'
 > git fetch --tags --force --progress -- https://github.com/FreeRDP/FreeRDP.git +refs/heads/*:refs/remotes/origin/* # timeout=10
 > git config remote.origin.url https://github.com/FreeRDP/FreeRDP.git # timeout=10
 > git config --add remote.origin.fetch +refs/heads/*:refs/remotes/origin/* # timeout=10
Avoid second fetch
 > git rev-parse origin/master^{commit} # timeout=10
Checking out Revision 1d098015aeb901b2924d8ffdca32794aa60f1f27 (origin/master)
 > git config core.sparsecheckout # timeout=10
 > git checkout -f 1d098015aeb901b2924d8ffdca32794aa60f1f27 # timeout=10
Commit message: "Merge pull request #11741 from rupran/andreas/fix-get-access-token-return-value"
 > git rev-list --no-walk ca553e927561dd1a73ea20ae9d9ab4abf19431c9 # timeout=10
Triggering freerdp-nightly-source Â» pkg-deb
freerdp-nightly-source Â» pkg-deb completed with result SUCCESS
Started calculate disk usage of build
Finished Calculation of disk usage of build in 0 seconds
Started calculate disk usage of workspace
Finished Calculation of disk usage of workspace in 0 seconds
Triggering a new build of freerdp-nightly-binaries
Finished: SUCCESS
