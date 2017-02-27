#### Test (Fail) 108111683 Build Logs


```


```

```
Updating 12428f5..70df915
Fast-forward
 .../ThaliCore/ThaliCore.xcodeproj/project.pbxproj  |   13 -
 .../NSRunLoop+NSStreamEventsThread.swift           |   17 --
 .../SocketConnection/NSStreamEventsThread.swift    |   70 -----
 .../ThaliCore/SocketConnection/VirtualSocket.swift |  282 +++++++++-----------
 4 files changed, 127 insertions(+), 255 deletions(-)
 delete mode 100644 lib/ios/ThaliCore/ThaliCore/SocketConnection/NSRunLoop+NSStreamEventsThread.swift
 delete mode 100644 lib/ios/ThaliCore/ThaliCore/SocketConnection/NSStreamEventsThread.swift

From https://github.com/thaliproject/Thali_CordovaPlugin
   12428f5..70df915  master     -> origin/master
 * [new branch]      iOS_swift3_migration_build -> origin/iOS_swift3_migration_build
 * [new branch]      iOS_swift3_migration_build_1 -> origin/iOS_swift3_migration_build_1
 * [new branch]      master_BUILD_iOS -> origin/master_BUILD_iOS
   668086c..e404086  master_jareksl_tmp -> origin/master_jareksl_tmp

```

```
Your branch is up-to-date with 'origin/master'.
git checkout iOS CI FAILED - clone.sh failure[0m

Already on 'master'
error: The following untracked working tree files would be overwritten by checkout:
	lib/ios/ThaliCore/ThaliCore/SocketConnection/NSRunLoop+NSStreamEventsThread.swift
	lib/ios/ThaliCore/ThaliCore/SocketConnection/NSStreamEventsThread.swift
Please move or remove them before you switch branches.
Aborting

```

Error: Command failed: Already on 'master'
error: The following untracked working tree files would be overwritten by checkout:
	lib/ios/ThaliCore/ThaliCore/SocketConnection/NSRunLoop+NSStreamEventsThread.swift
	lib/ios/ThaliCore/ThaliCore/SocketConnection/NSStreamEventsThread.swift
Please move or remove them before you switch branches.
Aborting
