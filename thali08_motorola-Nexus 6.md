#### Test 797510157282e1a_thali08_motorola-Nexus 6 Logs


```
TIME-OUT KILL (timeout was 1400000ms),--------- beginning of main
08-03 09:52:53.306  3421  3421 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-03 09:52:53.311  3421  3421 D AndroidRuntime: CheckJNI is OFF
08-03 09:52:53.346  3421  3421 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-03 09:52:53.387  3421  3421 I Radio-JNI: register_android_hardware_Radio DONE
08-03 09:52:53.407  3421  3421 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
--------- beginning of system
08-03 09:52:53.421   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-03 09:52:53.606   873   896 W PackageSettings: Skipping PackageSetting{dedfc31 com.example.hello/10273} due to missing metadata
08-03 09:52:53.667   873   896 I art     : Starting a blocking GC Explicit
08-03 09:52:53.716   873   896 I art     : Explicit concurrent mark sweep GC freed 22288(1598KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/42MB, paused 575us total 48.297ms
08-03 09:52:53.741   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-03 09:52:53.748  3421  3421 I art     : System.exit called, status: 0
08-03 09:52:53.748  3421  3421 I AndroidRuntime: VM exiting with result code 0.
08-03 09:52:53.759   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-03 09:52:53.789   873  1306 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-03 09:52:53.791  1696  2019 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-03 09:52:53.793  1662  1662 I Keyboard.Facilitator: resetDictionaries() : en_US
08-03 09:52:53.794  3275  3275 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-03 09:52:53.811  1662  3433 I Keyboard.Facilitator.DecoderInitializer: run()
08-03 09:52:53.813  1662  3433 I Decoder : createOrResetDecoder
08-03 09:52:53.837  1765  1765 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-03 09:52:53.869  2727  2743 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
08-03 09:52:53.870  2727  2743 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
08-03 09:52:53.870  2727  2743 E AndroidRuntime: Process: android.process.acore, PID: 2727
08-03 09:52:53.870  2727  2743 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-03 09:52:53.870  2727  2743 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-03 09:52:53.870  2727  2743 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-03 09:52:53.870  2727  2743 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-03 09:52:53.870  2727  2743 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-03 09:52:53.870  2727  2743 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-03 09:52:53.870  2727  2743 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-03 09:52:53.870  2727  2743 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:391)
08-03 09:52:53.870  2727  2743 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
08-03 09:52:53.870  2727  2743 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
08-03 09:52:53.870  2727  2743 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-03 09:52:53.870  2727  2743 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 09:52:53.870  2727  2743 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-03 09:52:53.870  2727  2743 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 09:52:53.888  2727  3438 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-03 09:52:53.890   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-03 09:52:53.892  1506  1506 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-03 09:52:53.892  1506  1506 D AndroidRuntime: Shutting down VM
08-03 09:52:53.894  1506  1506 E AndroidRuntime: FATAL EXCEPTION: main
08-03 09:52:53.894  1506  1506 E AndroidRuntime: Process: com.google.process.gapps, PID: 1506
08-03 09:52:53.894  1506  1506 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-03 09:52:53.894  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-03 09:52:53.894  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-03 09:52:53.894  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-03 09:52:53.894  1506  1506 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 09:52:53.894  1506  1506 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-03 09:52:53.894  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 09:52:53.894  1506  1506 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 09:52:53.894  1506  1506 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 09:52:53.894  1506  1506 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 09:52:53.894  1506  1506 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-03 09:52:53.894  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-03 09:52:53.894  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-03 09:52:53.894  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-03 09:52:53.894  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-03 09:52:53.894  1506  1506 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-03 09:52:53.894  1506  1506 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-03 09:52:53.894  1506  1506 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-03 09:52:53.894  1506  1506 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-03 09:52:53.894  1506  1506 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-03 09:52:53.894  1506  1506 E AndroidRuntime: 	... 8 more
08-03 09:52:53.898  1506  1506 I Process : Sending signal. PID: 1506 SIG: 9
08-03 09:52:53.899   873  3441 E DropBoxManagerService: Can't write: system_app_crash
08-03 09:52:53.899   873  3441 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
08-03 09:52:53.899   873  3441 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 09:52:53.899   873  3441 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 09:52:53.899   873  3441 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 09:52:53.899   873  3441 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 09:52:53.899   873  3441 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 09:52:53.899   873  3441 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 09:52:53.899   873  3441 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 09:52:53.899   873  3441 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 09:52:53.899   873  3441 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 09:52:53.899   873  3441 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 09:52:53.899   873  3441 E DropBoxManagerService: 	... 5 more
08-03 09:52:53.903  2727  2743 I Process : Sending signal. PID: 2727 SIG: 9
08-03 09:52:53.911  1782  1863 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-03 09:52:53.911   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-03 09:52:53.912   873   885 E PackageManager: Failed to write settings, restoring backup
08-03 09:52:53.912   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-03 09:52:53.912   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-03 09:52:53.912   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-03 09:52:53.912   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-03 09:52:53.912   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-03 09:52:53.912   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 09:52:53.912   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-03 09:52:53.912   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 09:52:53.916   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-03 09:52:53.916   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-03 09:52:53.916   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 09:52:53.916   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 09:52:53.916   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 09:52:53.916   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 09:52:53.916   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 09:52:53.916   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 09:52:53.916   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-03 09:52:53.916   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-03 09:52:53.916   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-03 09:52:53.916   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 09:52:53.916   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 09:52:53.916   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-03 09:52:53.916   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 09:52:53.916   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-03 09:52:53.916   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 09:52:53.916   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 09:52:53.916   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 09:52:53.916   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 09:52:53.916   873   886 E DropBoxManagerService: 	... 13 more
08-03 09:52:53.924   873  1711 I ActivityManager: Start proc 3442:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-03 09:52:53.924  1782  1863 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-03 09:52:53.924  1782  1863 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1782
08-03 09:52:53.924  1782  1863 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-03 09:52:53.924  1782  1863 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-03 09:52:53.924  1782  1863 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-03 09:52:53.924  1782  1863 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-03 09:52:53.924  1782  1863 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-03 09:52:53.924  1782  1863 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-03 09:52:53.924  1782  1863 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-03 09:52:53.924  1782  1863 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-03 09:52:53.924  1782  1863 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 09:52:53.924  1782  1863 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 09:52:53.924  1782  1863 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-03 09:52:53.924  1782  1863 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 09:52:53.925   873  1780 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-03 09:52:53.927   873  3451 E DropBoxManagerService: Can't write: system_app_crash
08-03 09:52:53.927   873  3451 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop103.tmp: open failed: EROFS (Read-only file system)
08-03 09:52:53.927   873  3451 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 09:52:53.927   873  3451 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 09:52:53.927   873  3451 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 09:52:53.927   873  3451 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 09:52:53.927   873  3451 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 09:52:53.927   873  3451 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 09:52:53.927   873  3451 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 09:52:53.927   873  3451 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 09:52:53.927   873  3451 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 09:52:53.927   873  3451 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 09:52:53.927   873  3451 E DropBoxManagerService: 	... 5 more
08-03 09:52:53.930  1782  1863 I Process : Sending signal. PID: 1782 SIG: 9
08-03 09:52:53.947   873  1315 D WifiService: Client connection lost with reason: 4
08-03 09:52:53.952   873  1397 I ActivityManager: Process android.process.acore (pid 2727) has died
08-03 09:52:53.952   873  1397 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
08-03 09:52:53.953   873  1780 I ActivityManager: Process com.google.process.gapps (pid 1506) has died
08-03 09:52:53.954   873  1780 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
08-03 09:52:53.954   873  1780 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
08-03 09:52:53.954   873  1780 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
08-03 09:52:53.954   873  1780 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.http.GoogleHttpService in 31000ms
08-03 09:52:53.954   873  1780 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 41000ms
08-03 09:52:53.956   873   884 D GraphicsStats: Buffer count: 1
08-03 09:52:53.956   873  1607 I WindowState: WIN DEATH: Window{20f8be3 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-03 09:52:53.966   873  1605 I ActivityManager: Start proc 3455:com.google.process.gapps/u0a11 for service com.google.android.gms/.gcm.http.GoogleHttpService
08-03 09:52:53.993   873  1718 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1782) has died
08-03 09:52:53.993   873  1718 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 50961ms
08-03 09:52:53.995   873  1718 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-03 09:52:54.017   873   884 I ActivityManager: Start proc 3467:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-03 09:52:54.057  3455  3455 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
08-03 09:52:54.068  3455  3455 I MultiDex: VM with version 2.1.0 has multidex support
08-03 09:52:54.068  3455  3455 I MultiDex: install
08-03 09:52:54.068  3455  3455 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-03 09:52:54.074  1799  1799 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-03 09:52:54.074  1799  1799 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 09:52:54.076  3467  3467 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 09:52:54.076  3467  3467 D AndroidRuntime: Shutting down VM
08-03 09:52:54.081  3467  3467 E AndroidRuntime: FATAL EXCEPTION: main
08-03 09:52:54.081  3467  3467 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3467
08-03 09:52:54.081  3467  3467 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-03 09:52:54.081  3467  3467 E AndroidRuntime: 	... 10 more
08-03 09:52:54.083   873  1763 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-03 09:52:54.084  3467  3467 I Process : Sending signal. PID: 3467 SIG: 9
08-03 09:52:54.084   873  3483 E DropBoxManagerService: Can't write: system_app_crash
08-03 09:52:54.084   873  3483 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop104.tmp: open failed: EROFS (Read-only file system)
08-03 09:52:54.084   873  3483 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 09:52:54.084   873  3483 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 09:52:54.084   873  3483 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 09:52:54.084   873  3483 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 09:52:54.084   873  3483 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 09:52:54.084   873  3483 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 09:52:54.084   873  3483 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 09:52:54.084   873  3483 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 09:52:54.084   873  3483 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 09:52:54.084   873  3483 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 09:52:54.084   873  3483 E DropBoxManagerService: 	... 5 more
08-03 09:52:54.093  1799  1799 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-03 09:52:54.094  1799  1799 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-03 09:52:54.112  3455  3455 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
08-03 09:52:54.115   873  1397 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3467) has died
08-03 09:52:54.116   873  1397 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-03 09:52:54.119  1799  3485 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-03 09:52:54.134   873  1780 I ActivityManager: Start proc 3488:com.google.android.googlequicksearchbox/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
08-03 09:52:54.136  1836  3484 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-03 09:52:54.161  1799  3485 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-03 09:52:54.161  1799  3485 E AndroidRuntime: Process: com.google.android.gms, PID: 1799
08-03 09:52:54.161  1799  3485 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-03 09:52:54.161  1799  3485 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-03 09:52:54.161  1799  3485 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-03 09:52:54.161  1799  3485 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-03 09:52:54.161  1799  3485 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-03 09:52:54.161  1799  3485 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-03 09:52:54.161  1799  3485 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-03 09:52:54.161  1799  3485 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-03 09:52:54.161  1799  3485 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-03 09:52:54.161  1799  3485 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-03 09:52:54.161  1799  3485 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-03 09:52:54.161  1799  3485 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-03 09:52:54.161  1799  3485 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-03 09:52:54.161  1799  3485 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-03 09:52:54.161  1799  3485 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-03 09:52:54.161  1799  3485 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-03 09:52:54.161  1799  3485 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-03 09:52:54.161  1799  3485 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-03 09:52:54.161  1799  3485 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
08-03 09:52:54.164   873  3500 E DropBoxManagerService: Can't write: system_app_crash
08-03 09:52:54.164   873  3500 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop105.tmp: open failed: EROFS (Read-only file system)
08-03 09:52:54.164   873  3500 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 09:52:54.164   873  3500 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 09:52:54.164   873  3500 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 09:52:54.164   873  3500 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 09:52:54.164   873  3500 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 09:52:54.164   873  3500 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 09:52:54.164   873  3500 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 09:52:54.164   873  3500 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 09:52:54.164   873  3500 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 09:52:54.164   873  3500 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 09:52:54.164   873  3500 E DropBoxManagerService: 	... 5 more
08-03 09:52:54.171  1799  3485 I Process : Sending signal. PID: 1799 SIG: 9
08-03 09:52:54.181  3455  3455 I GservicesProvider: Gservices pushing to system: true; secure/global: true
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 09:52:54.183  3455  3455 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 09:52:54.184  3455  3455 D AndroidRuntime: Shutting down VM
08-03 09:52:54.189  1836  3484 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-03 09:52:54.192   279   279 E lowmemorykiller: Error writing /proc/1799/oom_score_adj; errno=22
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 09:52:54.195  3488  3488 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 09:52:54.195  3488  3488 D AndroidRuntime: Shutting down VM
08-03 09:52:54.197  3455  3455 E AndroidRuntime: FATAL EXCEPTION: main
08-03 09:52:54.197  3455  3455 E AndroidRuntime: Process: com.google.process.gapps, PID: 3455
08-03 09:52:54.197  3455  3455 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-03 09:52:54.197  3455  3455 E AndroidRuntime: 	... 10 more
08-03 09:52:54.200  3488  3488 E AndroidRuntime: FATAL EXCEPTION: main
08-03 09:52:54.200  3488  3488 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3488
08-03 09:52:54.200  3488  3488 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-03 09:52:54.200  3488  3488 E AndroidRuntime: 	... 10 more
08-03 09:52:54.202   873  1781 W ActivityManager: Process com.google.android.gms has crashed too many times: killing!
08-03 09:52:54.202   873  3501 E DropBoxManagerService: Can't write: system_app_crash
08-03 09:52:54.202   873  3501 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop106.tmp: open failed: EROFS (Read-only file system)
08-03 09:52:54.202   873  3501 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 09:52:54.202   873  3501 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 09:52:54.202   873  3501 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 09:52:54.202   873  3501 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 09:52:54.202   873  3501 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 09:52:54.202   873  3501 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 09:52:54.202   873  3501 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 09:52:54.202   873  3501 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 09:52:54.202   873  3501 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 09:52:54.202   873  3501 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 09:52:54.202   873  3501 E DropBoxManagerService: 	... 5 more
08-03 09:52:54.202   873  1781 I ActivityManager: Killing 3455:com.google.process.gapps/u0a11 (adj 0): crash
08-03 09:52:54.205   873  3502 E DropBoxManagerService: Can't write: system_app_crash
08-03 09:52:54.205   873  3502 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop107.tmp: open failed: EROFS (Read-only file system)
08-03 09:52:54.205   873  3502 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 09:52:54.205   873  3502 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 09:52:54.205   873  3502 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 09:52:54.205   873  3502 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 09:52:54.205   873  3502 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 09:52:54.205   873  3502 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 09:52:54.205   873  3502 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 09:52:54.205   873  3502 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 09:52:54.205   873  3502 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 09:52:54.205   873  3502 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 09:52:54.205   873  3502 E DropBoxManagerService: 	... 5 more
08-03 09:52:54.213  1836  3484 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
08-03 09:52:54.213  1836  3484 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-03 09:52:54.213  1836  3484 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 1836
08-03 09:52:54.213  1836  3484 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-03 09:52:54.213  1836  3484 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-03 09:52:54.213  1836  3484 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-03 09:52:54.213  1836  3484 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-03 09:52:54.213  1836  3484 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-03 09:52:54.213  1836  3484 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-03 09:52:54.213  1836  3484 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-03 09:52:54.213  1836  3484 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-03 09:52:54.213  1836  3484 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-03 09:52:54.213  1836  3484 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-03 09:52:54.213  1836  3484 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-03 09:52:54.213  1836  3484 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-03 09:52:54.213  1836  3484 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-03 09:52:54.213  1836  3484 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-03 09:52:54.213  1836  3484 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-03 09:52:54.213  1836  3484 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-03 09:52:54.213  1836  3484 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 09:52:54.213  1836  3484 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-03 09:52:54.213  1836  3484 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-03 09:52:54.241  3442  3473 W GmsClient: service died
08-03 09:52:54.242  3442  3482 W GmsClient: service died
08-03 09:52:54.243  3442  3442 E SilentFeedbackService: GoogleApiClient silent feedback connection failed with result: 8
08-03 09:52:54.243  3442  3442 E SilentFeedbackService: GoogleApiClient silent feedback connection failed with result: 8
08-03 09:52:54.247   873  1781 W ActivityManager: Failure disconnecting service ComponentInfo{com.google.android.gms/com.google.android.gms.clearcut.service.ClearcutLoggerService} to connection android.os.BinderProxy@3d96f82 (in com.google.android.gms)
08-03 09:52:54.247   873  1781 W ActivityManager: android.os.DeadObjectException
08-03 09:52:54.247   873  1781 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-03 09:52:54.247   873  1781 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
08-03 09:52:54.247   873  1781 W ActivityManager: 	at android.app.IServiceConnection$Stub$Proxy.connected(IServiceConnection.java:92)
08-03 09:52:54.247   873  1781 W ActivityManager: 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1704)
08-03 09:52:54.247   873  1781 W ActivityManager: 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2336)
08-03 09:52:54.247   873  1781 W ActivityManager: 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15543)
08-03 09:52:54.247   873  1781 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4567)
08-03 09:52:54.247   873  1781 W ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-03 09:52:54.247   873  1781 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppCrashLocked(ActivityManagerService.java:12031)
08-03 09:52:54.247   873  1781 W ActivityManager: 	at com.android.server.am.ActivityManagerService.makeAppCrashingLocked(ActivityManagerService.java:11933)
08-03 09:52:54.247   873  1781 W ActivityManager: 	at com.android.server.am.ActivityManagerService.crashApplication(ActivityManagerService.java:12622)
08-03 09:52:54.247   873  1781 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12129)
08-03 09:52:54.247   873  1781 W ActivityManager: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12111)
08-03 09:52:54.247   873  1781 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1458)
08-03 09:52:54.247   873  1781 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
08-03 09:52:54.247   873  1781 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:453)
08-03 09:52:54.249   873  1780 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-03 09:52:54.249  3488  3488 I Process : Sending signal. PID: 3488 SIG: 9
08-03 09:52:54.250   873  1763 W ActivityManager: Spurious death for ProcessRecord{2581294 0:com.google.process.gapps/u0a11}, curProc for 3455: null
08-03 09:52:54.250   873  1711 I ActivityManager: Process com.google.android.gms (pid 1799) has died
08-03 09:52:54.250   873  1711 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
08-03 09:52:54.251   873  1711 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackService in 1000ms
08-03 09:52:54.251   873  1711 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackAsyncService in 11000ms
08-03 09:52:54.258   873  3503 E DropBoxManagerService: Can't write: system_app_crash
08-03 09:52:54.258   873  3503 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop108.tmp: open failed: EROFS (Read-only file system)
08-03 09:52:54.258   873  3503 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-03 09:52:54.258   873  3503 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-03 09:52:54.258   873  3503 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-03 09:52:54.258   873  3503 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-03 09:52:54.258   873  3503 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-03 09:52:54.258   873  3503 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-03 09:52:54.258   873  3503 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-03 09:52:54.258   873  3503 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-03 09:52:54.258   873  3503 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-03 09:52:54.258   873  3503 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-03 09:52:54.258   873  3503 E DropBoxManagerService: 	... 5 more

```
