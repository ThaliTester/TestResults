#### Test 721454317367600_thali08_LGE-Nexus 5 Logs


```
TIME-OUT KILL (timeout was 1400000ms),--------- beginning of main
06-22 07:49:02.142  3025  3025 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-22 07:49:02.146  3025  3025 D AndroidRuntime: CheckJNI is OFF
06-22 07:49:02.180  3025  3025 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-22 07:49:02.213  3025  3025 I Radio-JNI: register_android_hardware_Radio DONE
06-22 07:49:02.233  3025  3025 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
--------- beginning of system
06-22 07:49:02.239   787   803 I ActivityManager: Force stopping com.test.thalitest appid=10026 user=-1: uninstall pkg
06-22 07:49:02.396   787   814 W PackageSettings: Skipping PackageSetting{887fce com.example.hello/10116} due to missing metadata
06-22 07:49:02.423   787   814 I art     : Starting a blocking GC Explicit
06-22 07:49:02.461   787   814 I art     : Explicit concurrent mark sweep GC freed 16800(1102KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 24MB/37MB, paused 620us total 36.145ms
06-22 07:49:02.478   787   814 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
06-22 07:49:02.480  3025  3025 I art     : System.exit called, status: 0
06-22 07:49:02.480  3025  3025 I AndroidRuntime: VM exiting with result code 0.
06-22 07:49:02.486   787   814 I ActivityManager: Force stopping com.test.thalitest appid=10026 user=0: pkg removed
06-22 07:49:02.514  1262  1575 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
06-22 07:49:02.533   787   883 I InputReader: Reconfiguring input devices.  changes=0x00000010
06-22 07:49:02.543  1308  1308 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
06-22 07:49:02.598  2119  2134 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
06-22 07:49:02.603  2119  2134 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
06-22 07:49:02.603  2119  2134 E AndroidRuntime: Process: android.process.acore, PID: 2119
06-22 07:49:02.603  2119  2134 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-22 07:49:02.603  2119  2134 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
06-22 07:49:02.603  2119  2134 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
06-22 07:49:02.603  2119  2134 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
06-22 07:49:02.603  2119  2134 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
06-22 07:49:02.603  2119  2134 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
06-22 07:49:02.603  2119  2134 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
06-22 07:49:02.603  2119  2134 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:391)
06-22 07:49:02.603  2119  2134 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
06-22 07:49:02.603  2119  2134 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
06-22 07:49:02.603  2119  2134 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
06-22 07:49:02.603  2119  2134 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-22 07:49:02.603  2119  2134 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
06-22 07:49:02.603  2119  2134 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-22 07:49:02.618  2119  3049 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
06-22 07:49:02.619   787   889 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
06-22 07:49:02.638   787  1063 I ActivityManager: Start proc 3063:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
06-22 07:49:02.645  2119  2134 I Process : Sending signal. PID: 2119 SIG: 9
06-22 07:49:02.654   787  3069 E DropBoxManagerService: Can't write: system_app_crash
06-22 07:49:02.654   787  3069 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
06-22 07:49:02.654   787  3069 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
06-22 07:49:02.654   787  3069 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-22 07:49:02.654   787  3069 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-22 07:49:02.654   787  3069 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
06-22 07:49:02.654   787  3069 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
06-22 07:49:02.654   787  3069 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
06-22 07:49:02.654   787  3069 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-22 07:49:02.654   787  3069 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
06-22 07:49:02.654   787  3069 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-22 07:49:02.654   787  3069 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
06-22 07:49:02.654   787  3069 E DropBoxManagerService: 	... 5 more
06-22 07:49:02.671   787   787 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED

```
