#### Test 5133502860beea6_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
E/dalvikvm( 1292): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1292): VFY: unable to resolve new-instance 2320 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
D/dalvikvm( 1292): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1292): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1292): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
D/dalvikvm( 1292): DexOpt: unable to opt direct call 0x3207 at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
D/dalvikvm( 1130): GC_FOR_ALLOC freed 228K, 4% free 18156K/18744K, paused 16ms, total 16ms
D/dalvikvm( 2398): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42758898
D/dalvikvm( 2398): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x42758898
D/dalvikvm( 2398): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42758898
D/dalvikvm( 2398): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42758898
D/dalvikvm( 2398): GC_CONCURRENT freed 477K, 3% free 18011K/18524K, paused 2ms+3ms, total 23ms
D/dalvikvm( 2398): GC_FOR_ALLOC freed 5K, 3% free 18048K/18524K, paused 13ms, total 14ms
I/dalvikvm-heap( 2398): Grow heap (frag case) to 17.730MB for 79892-byte allocation
D/ChimeraCfgMgr( 1292): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1292): Module APK com.google.android.play.games already loaded
D/dalvikvm( 2398): GC_FOR_ALLOC freed 0K, 3% free 18126K/18604K, paused 19ms, total 19ms
D/ChimeraCfgMgr( 1292): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/AsyncTaskServiceImpl( 1292): Submit a task: h
D/ChimeraCfgMgr( 1292): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 1292): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/h       ( 1292): Processing package: com.test.thalitest
I/PeopleContactsSync( 1292): CP2 sync disabled
D/GassUtils( 1292): Found app info for package com.test.thalitest:18. Hash: 01e4d8ac61718f1dcdc950940ea39ae21caf015e512d4d8080feb7f016346367
D/h       ( 1292): Found info for package com.test.thalitest in db.
I/dalvikvm( 1292): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1292): VFY: unable to resolve virtual method 34: Landroid/app/Activity;.finishAfterTransition ()V
,D/dalvikvm( 1292): VFY: replacing opcode 0x6e at 0x000e
--------- beginning of /dev/log/system
I/ActivityManager(  759): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2452 uid=10065 gids={50065, 3003, 1028, 1015}
W/BaseAppContext( 1292): Using Auth Proxy for data requests.
W/BaseAppContext( 1292): Using Auth Proxy for data requests.
W/BaseAppContext( 1292): Using Auth Proxy for data requests.
W/BaseAppContext( 1292): Using Auth Proxy for data requests.
W/BaseAppContext( 1292): Using Auth Proxy for data requests.
W/BaseAppContext( 1292): Using Auth Proxy for data requests.
I/ProviderInstaller( 2398): Installed default security provider GmsCore_OpenSSL
D/dalvikvm( 1292): GC_CONCURRENT freed 326K, 2% free 18453K/18820K, paused 2ms+5ms, total 20ms
W/Quickoffice( 2452): Cleanup of storage: done
D/com.google.android.apps.docs.quickoffice.X( 2452): Loading recent documents list
D/Quickoffice( 2452): The number of lines present in  /proc/mount 21
D/Quickoffice( 2452): Parsing the storagedefinition.xml.
D/Quickoffice( 2452): # of Storagedefinitions - 35
D/Quickoffice( 2452): The # of storage definitions available - 35
D/Quickoffice( 2452): Processing mountline rootfs / rootfs ro,relatime 0 0
D/Quickoffice( 2452): Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
D/Quickoffice( 2452): Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
D/Quickoffice( 2452): Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
D/Quickoffice( 2452): Processing mountline proc /proc proc rw,relatime 0 0
D/Quickoffice( 2452): Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
D/Quickoffice( 2452): Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
D/Quickoffice( 2452): Processing mountline debugfs /sys/kernel/debug debugfs rw,relatime 0 0
D/Quickoffice( 2452): Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
D/Quickoffice( 2452): Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
D/Quickoffice( 2452): Processing mountline tmpfs /mnt/asec tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2452): Processing mountline tmpfs /mnt/obb tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2452): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,nosuid,nodev,relatime,data=ordered 0 0
D/Quickoffice( 2452): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2452): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2452): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2452): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
D/Quickoffice( 2452): Processing mountline /dev/fuse /mnt/shell/emulated fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2452): Processing mountline tmpfs /storage/emulated tmpfs rw,seclabel,nosuid,nodev,relatime,mode=751,gid=1028 0 0
D/Quickoffice( 2452): Processing mountline /dev/fuse /storage/emulated/0 fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2452): Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2452): Build properties are not configured for this storage definition.
D/dalvikvm( 2452): GC_CONCURRENT freed 166K, 2% free 16916K/17116K, paused 3ms+1ms, total 12ms
D/Quickoffice( 2452): Adding the mount informaiton for listing in file manager MountedDeviceInformation [device=/dev/fuse, mountPath=/storage/emulated/legacy, fileSystemType=fuse, options=rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other, bootPriority1=0, bootPriority2=0, storageInfo=StorageDefinition [id=2010, matchPatterns=[/storage/emulated/legacy, fuse], skipPatterns=[obb], buildPatterns=[], type=INTERNAL, resourceString=2131231627, resourceStringItemized=2131231630, resourceIcon=2130838373, enabled=true], userFriendlyName=null]
D/Quickoffice( 2452): The # of mounts identified -  1
D/com.google.android.apps.docs.quickoffice.X( 2452): Checking validity of 0 items
D/ContentResolverUtil( 2452): There are 0 persisted uri permissions.
D/com.google.android.apps.docs.quickoffice.X( 2452): 0 items were valid
W/ActivityManager(  759): No permission grants found for com.quickoffice.android
D/AndroidRuntime( 2463): 
D/AndroidRuntime( 2463): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/dalvikvm( 1292): GC_CONCURRENT freed 295K, 2% free 18650K/18980K, paused 1ms+3ms, total 18ms
D/AndroidRuntime( 2463): CheckJNI is OFF
D/dalvikvm( 2463): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2463): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2463): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2463): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2463): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
W/Quickoffice( 2452): Could not load clipboard.
I/ActivityManager(  759): Killing 1943:com.google.android.apps.maps/u0a57 (adj 15): empty #17
D/dalvikvm( 2463): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
W/Quickoffice( 2452): Could not store clipboard.
D/ChimeraCfgMgr( 1292): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1292): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 2463): Calling main entry com.android.commands.am.Am
I/ActivityManager(  759): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2463
D/PermissionCache(  183): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (106 us)
I/Icing   ( 1292): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
D/AndroidRuntime( 2463): Shutting down VM
D/dalvikvm( 2463): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 0ms+1ms, total 2ms
I/SearchController( 1180): #onHotwordDetectorStopped(false)
I/MicrophoneInputStream( 1180): mic_close
I/ActivityManager(  759): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2494 uid=10108 gids={50108, 3003, 3001, 3002, 1028, 1015}
I/MicroHotwordRecognitionRunner( 1180): Hotword detection finished
I/MicroHotwordRecognitionRunner( 1180): Stopping hotword detection.
I/ActivityManager(  759): Killing 1974:com.google.android.youtube/u0a71 (adj 15): empty #17
F/ActivityManager(  759): Service ServiceRecord{42d378c8 u0 com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService} in process ProcessRecord{42d76a80 1974:com.google.android.youtube/u0a71} not same as in map: null
V/WebViewChromiumFactoryProvider( 2494): Binding Chromium to main looper Looper (main, tid 1) {425f7bb0}
I/LibraryLoader( 2494): Expected native library version number "",actual native library version number ""
I/chromium( 2494): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2494): Initializing chromium process, renderers=0
D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4422d7c8:true
D/BluetoothAdapter( 2494): 1113641592: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 2494): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
I/Icing   ( 1292): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
W/chromium( 2494): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 2494): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2494): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2494): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2494): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2494): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 2494): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 2494): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2494): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2494): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2494): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2494): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 2494): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2494): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2494): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2494): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2494): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2494): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2494): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 2494): CordovaWebView is running on device made by: LGE
,D/OpenGLRenderer( 2494): Enabling debug mode 0
,W/AwContents( 2494): nativeOnDraw failed; clearing to background color.
,W/AwContents( 2494): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  759): Displayed com.test.thalitest/.MainActivity: +304ms
,I/ActivityManager(  759): Killing 1708:com.google.android.deskclock/u0a33 (adj 15): empty #17
,D/JsMessageQueue( 2494): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 2494): GC_CONCURRENT freed 237K, 2% free 16887K/17156K, paused 3ms+2ms, total 17ms
,D/dalvikvm( 2494): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x425fc158
,D/dalvikvm( 2494): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x425fc158
,D/jxcore_app_log( 2494): JniHelper::setJavaVM(0x414e4f00), pthread_self() = 1982418536
,D/JX-Cordova( 2494): jxcore cordova android initializing
I/dalvikvm( 2494): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
W/dalvikvm( 2494): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 2494): VFY: replacing opcode 0x6e at 0x0045
,I/chromium( 2494): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/dalvikvm( 2494): GC_CONCURRENT freed 214K, 2% free 17172K/17420K, paused 1ms+2ms, total 11ms
,D/dalvikvm( 2494): GC_CONCURRENT freed 159K, 2% free 17515K/17716K, paused 1ms+1ms, total 9ms
,D/dalvikvm( 2494): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 2494): GC_CONCURRENT freed 157K, 2% free 17859K/18060K, paused 1ms+1ms, total 12ms
,D/dalvikvm( 2494): WAIT_FOR_CONCURRENT_GC blocked 5ms
,D/dalvikvm( 2494): GC_CONCURRENT freed 154K, 2% free 18204K/18404K, paused 1ms+1ms, total 12ms
D/dalvikvm( 2494): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 2494): WAIT_FOR_CONCURRENT_GC blocked 5ms
,D/dalvikvm( 2494): GC_CONCURRENT freed 159K, 2% free 18539K/18748K, paused 1ms+1ms, total 15ms
D/dalvikvm( 2494): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 2494): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 2494): GC_CONCURRENT freed 179K, 2% free 18954K/19188K, paused 2ms+2ms, total 23ms
D/dalvikvm( 2494): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 2494): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 2494): GC_CONCURRENT freed 221K, 2% free 19459K/19740K, paused 1ms+2ms, total 25ms
D/dalvikvm( 2494): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 2494): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 2494): GC_CONCURRENT freed 281K, 2% free 20069K/20416K, paused 1ms+2ms, total 24ms
,D/dalvikvm( 2494): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 2494): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 2494): GC_CONCURRENT freed 329K, 2% free 20826K/21228K, paused 2ms+1ms, total 19ms
D/dalvikvm( 2494): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 2494): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/dalvikvm( 2494): GC_CONCURRENT freed 402K, 3% free 21752K/22236K, paused 2ms+1ms, total 20ms
D/dalvikvm( 2494): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 2494): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/dalvikvm( 2494): GC_CONCURRENT freed 1210K, 6% free 22147K/23424K, paused 2ms+2ms, total 35ms
,D/dalvikvm( 2494): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/dalvikvm( 2494): GC_CONCURRENT freed 1450K, 7% free 22419K/24000K, paused 2ms+1ms, total 26ms
,D/dalvikvm( 2494): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 2494): GC_FOR_ALLOC freed 69K, 7% free 22397K/24000K, paused 22ms, total 22ms
,I/dalvikvm-heap( 2494): Grow heap (frag case) to 22.610MB for 744140-byte allocation
,D/dalvikvm( 2494): GC_FOR_ALLOC freed 537K, 9% free 22586K/24728K, paused 20ms, total 20ms
,D/dalvikvm( 2494): GC_FOR_ALLOC freed 776K, 9% free 22649K/24728K, paused 19ms, total 20ms
,I/dalvikvm-heap( 2494): Grow heap (frag case) to 23.211MB for 1116206-byte allocation
,D/dalvikvm( 2494): GC_FOR_ALLOC freed 735K, 11% free 23004K/25820K, paused 32ms, total 32ms
,D/dalvikvm( 2494): GC_FOR_ALLOC freed 1269K, 11% free 23067K/25820K, paused 21ms, total 21ms
,I/dalvikvm-heap( 2494): Grow heap (frag case) to 24.151MB for 1674304-byte allocation
,D/dalvikvm( 2494): GC_FOR_ALLOC freed 1120K, 15% free 23582K/27456K, paused 25ms, total 25ms
,D/dalvikvm( 2494): GC_FOR_ALLOC freed 1998K, 14% free 23712K/27456K, paused 22ms, total 24ms
,I/dalvikvm-heap( 2494): Grow heap (frag case) to 25.580MB for 2511452-byte allocation
,D/dalvikvm( 2494): GC_FOR_ALLOC freed 1652K, 19% free 24512K/29912K, paused 23ms, total 23ms
,D/dalvikvm( 2494): GC_CONCURRENT freed 214K, 19% free 24429K/29912K, paused 2ms+4ms, total 29ms
,D/dalvikvm( 2494): GC_CONCURRENT freed 2424K, 18% free 24585K/29912K, paused 2ms+3ms, total 34ms
,D/dalvikvm( 2494): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 2494): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 2494): GC_FOR_ALLOC freed 693K, 19% free 24393K/29912K, paused 21ms, total 21ms
,I/dalvikvm-heap( 2494): Grow heap (frag case) to 27.442MB for 3767174-byte allocation
,D/dalvikvm( 2494): GC_FOR_ALLOC freed 36K, 17% free 28035K/33592K, paused 23ms, total 23ms
,D/dalvikvm( 2494): GC_CONCURRENT freed 2717K, 24% free 25594K/33592K, paused 6ms+3ms, total 33ms
,W/jxcore-log( 2494): Initializing JXcore engine
,W/jxcore-log( 2494): JXcore engine is ready
,D/dalvikvm( 2494): GC_CONCURRENT freed 339K, 17% free 28190K/33592K, paused 4ms+11ms, total 32ms
,W/jxcore-log( 2494): Starting JXcore engine
,W/jxcore-log( 2494): Platform android
W/jxcore-log( 2494): 
,W/jxcore-log( 2494): Process ARCH arm
W/jxcore-log( 2494): 
,I/jxcore-log( 2494): JXcore Cordova bridge is ready!
I/jxcore-log( 2494): 
,W/jxcore-log( 2494): JXcore engine is started
I/Choreographer( 2494): Skipped 154 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 2494): Toggling radios to true
I/jxcore-log( 2494): 
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  759): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  759): Message: 1
,D/BluetoothManagerService(  759): MESSAGE_ENABLE: mBluetooth = null
,I/ActivityManager(  759): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=2545 uid=1002 gids={41002, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008}
,D/AdapterServiceConfig( 2545): Adding HeadsetService
,D/AdapterServiceConfig( 2545): Adding A2dpService
D/AdapterServiceConfig( 2545): Adding HidService
D/AdapterServiceConfig( 2545): Adding HealthService
D/AdapterServiceConfig( 2545): Adding PanService
D/AdapterServiceConfig( 2545): Adding GattService
,D/AdapterServiceConfig( 2545): Adding BluetoothMapService
,D/BluetoothAdapterService( 2545): REFCOUNT: CREATED. INSTANCE_COUNT1
,D/BluetoothManagerService(  759): Message: 20
,D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44204838:true
,D/BluetoothAdapterState( 2545): make
,I/bluedroid( 2545): init
,I/BluetoothAdapterState( 2545): Entering OffState
,I/bte_conf( 2545): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bluedroid( 2545): get_profile_interface socket
,D/BluetoothManagerService(  759): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  759): Message: 40
,D/BluetoothManagerService(  759): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 2545): config_hci_snoop_log
D/BluetoothManagerService(  759): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  759): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/BluetoothAdapterState( 2545): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 2545): Setting state to 11
I/BluetoothAdapterState( 2545): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 2545): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  759): Message: 60
D/BluetoothManagerService(  759): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  759): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 2545): make
,I/BluetoothBondStateMachine( 2545): StableState(): Entering Off State
,I/GKI_LINUX( 2545): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
,I/BluetoothAdapterProperties( 2545): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 2545): Address is:34:FC:EF:11:B1:66
,I/BluetoothAdapterProperties( 2545): adapterPropertyChangedCallback with type:1 len:7
,D/BluetoothHeadset(  759): Proxy object connected
D/BluetoothHeadset( 1004): Proxy object connected
D/BluetoothHeadset( 1004): Proxy object connected
,D/BluetoothHeadset( 1004): Proxy object connected
I/ActivityManager(  759): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=2560 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
,I/BluetoothAdapterState( 2545): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothAdapterProperties( 2545): Name is: Nexus 5
D/BluetoothManagerService(  759): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  759): Stored Bluetooth name: Nexus 5
D/HeadsetService( 2545): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 2545): classInitNative: succeeds
,D/HeadsetStateMachine( 2545): make
,I/bluedroid( 2545): get_profile_interface handsfree
,D/BluetoothA2dp(  759): Proxy object connected
,D/A2dpService( 2545): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 2545): classInitNative: succeeds
V/Avrcp   ( 2545): make
,I/bluedroid( 2545): get_profile_interface avrcp
,I/BluetoothA2dpServiceJni( 2545): classInitNative: succeeds
,D/A2dpStateMachine( 2545): make
,I/bluedroid( 2545): get_profile_interface a2dp
,I/GKI_LINUX( 2545): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,I/BluetoothHidServiceJni( 2545): classInitNative: succeeds
,D/A2dpStateMachine( 2545): Enter Disconnected: -2
D/HidService( 2545): Received start request. Starting profile...
,I/bluedroid( 2545): get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 2545): classInitNative: succeeds
,D/HealthService( 2545): Received start request. Starting profile...
,I/bluedroid( 2545): get_profile_interface health
,I/BluetoothPanServiceJni( 2545): classInitNative(L105): succeeds
,D/BluetoothPan(  759): BluetoothPAN Proxy object connected
D/PanService( 2545): Received start request. Starting profile...
D/BluetoothPanServiceJni( 2545): initializeNative(L110): pan
,I/bluedroid( 2545): get_profile_interface pan
,D/BluetoothTethering(  759): got CMD_CHANNEL_HALF_CONNECTED
,I/BtGatt.JNI( 2545): classInitNative(L684): classInitNative: Success!
,D/BtGatt.DebugUtils( 2545): handleDebugAction() action=null
D/BtGatt.GattService( 2545): Received start request. Starting profile...
D/BtGatt.GattService( 2545): start()
,I/bluedroid( 2545): get_profile_interface gatt
,D/BluetoothMapService( 2545): Received start request. Starting profile...
,D/BluetoothMapService( 2545): start()
,D/BluetoothAdapterService( 2545): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 2545): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 2545): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/BluetoothAdapterService( 2545): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/HeadsetPhoneState( 2545): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterService( 2545): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2545): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterState( 2545): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 2545): enable
,I/bt_hci_bdroid( 2545): init
,I/bt_vendor( 2545): init
I/bt_vnd_conf( 2545): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,I/bt_vnd_conf( 2545): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,I/bt_hci_bdroid( 2545): bt_hc_worker_thread started
,I/ActivityManager(  759): Killing 1828:com.google.android.email/u0a36 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1130): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/BroadcastQueue(  759): Permission Denial: receiving Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 (has extras) } to com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver requires android.permission.BLUETOOTH due to sender android (uid 1000)
,I/bt_userial_vendor( 2545): userial vendor open: opening /dev/ttyHS99
I/GKI_LINUX( 2545): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
,I/bt-btu  ( 2545): btu_task pending for preload complete event
,I/bt_userial_vendor( 2545): device fd = 65 open
,I/bt_hwcfg( 2545): bt vendor lib: set UART baud 4000000
,D/bt_hwcfg( 2545): Chipset BCM4335C0
D/bt_hwcfg( 2545): Target name = [BCM4335C0]
,I/bt_hwcfg( 2545): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,I/bt_hwcfg( 2545): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 2545): Settlement delay -- 100 ms
,I/bt_hwcfg( 2545): bt vendor lib: set UART baud 4000000
,I/bt_hwcfg( 2545): Setting local bd addr to 34:FC:EF:11:B1:66
,I/bt_hwcfg( 2545): vendor lib fwcfg completed
,I/bt-btu  ( 2545): btu_task received preload complete event
,I/        ( 2545): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 2545): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 2545): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 2545): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 2545): BTE_InitTraceLevels -- TRC_AVRC
,I/        ( 2545): BTE_InitTraceLevels -- TRC_A2D
I/        ( 2545): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 2545): BTE_InitTraceLevels -- TRC_BTM
I/        ( 2545): BTE_InitTraceLevels -- TRC_GAP
,I/        ( 2545): BTE_InitTraceLevels -- TRC_PAN
I/        ( 2545): BTE_InitTraceLevels -- TRC_SDP
I/        ( 2545): BTE_InitTraceLevels -- TRC_GATT
I/        ( 2545): BTE_InitTraceLevels -- TRC_SMP
I/        ( 2545): BTE_InitTraceLevels -- TRC_BTAPP
,I/        ( 2545): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 2545): BTM_SecRegister:p_cb_info->p_le_callback == 0x75098f8d 
,E/bt-btm  ( 2545): BTM_SecRegister: btm_cb.api.p_le_callback = 0x75098f8d 
,E/bt-btif ( 2545): Calling BTA_HhEnable
,E/bt-btif ( 2545): btif_storage_get_adapter_property service_mask:0x140040
,I/BluetoothAdapterProperties( 2545): adapterPropertyChangedCallback with type:2 len:6
,D/BluetoothAdapterProperties( 2545): Address is:34:FC:EF:11:B1:66
,I/BluetoothAdapterProperties( 2545): adapterPropertyChangedCallback with type:1 len:7
,D/BluetoothManagerService(  759): Bluetooth Adapter name changed to Nexus 5
,D/BluetoothManagerService(  759): Stored Bluetooth name: Nexus 5
D/BluetoothAdapterProperties( 2545): Name is: Nexus 5
,I/BluetoothAdapterProperties( 2545): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothAdapterProperties( 2545): Scan Mode:20
I/BluetoothAdapterProperties( 2545): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 2545): Discoverable Timeout:120
,I/BluetoothAdapterProperties( 2545): adapterPropertyChangedCallback with type:8 len:24
,D/BluetoothAdapterProperties( 2545): Adding bonded device:F4:F1:E1:5C:3B:E2
,D/BluetoothAdapterProperties( 2545): Adding bonded device:F8:95:C7:87:85:54
,D/BluetoothAdapterProperties( 2545): Adding bonded device:E0:DB:10:1F:C9:5E
,D/BluetoothAdapterProperties( 2545): Adding bonded device:F8:95:C7:87:3C:51
,I/BluetoothAdapterProperties( 2545): adapterPropertyChangedCallback with type:3 len:48
,E/BluetoothRemoteDevices( 2545): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,E/BluetoothRemoteDevices( 2545): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
,E/BluetoothRemoteDevices( 2545): devicePropertyChangedCallback: bdDevice: E0:DB:10:1F:C9:5E, value is empty for type: 10
,E/BluetoothRemoteDevices( 2545): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
,I/bt_hwcfg( 2545): SCO PCM configure {0, 4, 0, 0, 0}
,I/bte_conf( 2545): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 2545): [1] primary_record=1 vendor_id=0x000F vendor_id_source=0x0001 product_id=0x1200 version=0x1436
I/bte_conf( 2545): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 2545): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,D/BluetoothPanServiceJni( 2545): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
D/BluetoothAdapterState( 2545): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 2545): ScanMode =  20
D/BluetoothAdapterProperties( 2545): State =  11
D/BluetoothAdapterProperties( 2545): Setting state to 12
,I/BluetoothAdapterState( 2545): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterService( 2545): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  759): Message: 60
,D/BluetoothManagerService(  759): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  759): Broadcasting onBluetoothStateChange(true) to 6 receivers.
,D/BluetoothHeadset(  759): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1004): onBluetoothStateChange: up=true
D/BluetoothPan(  759): onBluetoothStateChange(on) call bindService
,I/BluetoothAdapterState( 2545): Entering On State
D/BluetoothAdapterService(1113622824)( 2545): Get Bonded Devices being called
D/BluetoothAdapterProperties( 2545): getBondedDevices: length=4
,I/BluetoothAdapterProperties( 2545): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothHeadset( 1004): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1004): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 2545): Scan Mode:21
D/BluetoothA2dp(  759): onBluetoothStateChange: up=true
I/BluetoothAdapterProperties( 2545): adapterPropertyChangedCallback with type:9 len:4
,D/BluetoothManagerService(  759): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothAdapterProperties( 2545): Discoverable Timeout:120
,D/BluetoothManagerService(  759): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  759): Message: 40
D/BluetoothManagerService(  759): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapService( 2545): onReceive
D/BluetoothMapService( 2545): STATE_ON
,W/ContextImpl(  759): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:192 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:484 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1129 
D/BluetoothMapService( 2545): Map Service startRfcommSocketListener
D/BluetoothAdapterService(1113622824)( 2545): Get Bonded Devices being called
D/BluetoothAdapterProperties( 2545): getBondedDevices: length=4
E/bt_h4   ( 2545): vendor lib postload completed
D/BluetoothAdapterService(1113622824)( 2545): Get Bonded Devices being called
D/BluetoothAdapterProperties( 2545): getBondedDevices: length=4
D/BluetoothMapService( 2545): Map Service initSocket
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 2545): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 2545): SOCK FLAG = 1 ***********************
D/BluetoothMapService( 2545): Accepting socket connection...
D/BluetoothAdapterService(1113622824)( 2545): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2545): getBondedDevices: length=4
W/ContextImpl( 2560): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  759): Message: 20
,D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@441cb360:true
W/BluetoothAdapter( 2545): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 2545): SOCK FLAG = 1 ***********************
D/LocalBluetoothProfileManager( 2560): Adding local A2DP profile
,D/BluetoothManagerService(  759): Message: 30
,D/LocalBluetoothProfileManager( 2560): Adding local HEADSET profile
,D/BluetoothManagerService(  759): Message: 30
W/ContextImpl( 2560): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
,W/ContextImpl( 2560): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
,D/BluetoothManagerService(  759): Message: 30
,D/BluetoothManagerService(  759): Message: 30
W/ContextImpl( 2560): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
W/ContextImpl( 2560): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
,D/BluetoothAdapterService(1113622824)( 2545): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2545): getBondedDevices: length=4
,D/dalvikvm(  759): GC_EXPLICIT freed 22019K, 53% free 26175K/55312K, paused 2ms+5ms, total 89ms
,D/LocalBluetoothProfileManager( 2560): Adding local MAP profile
,D/BluetoothMap( 2560): Create BluetoothMap proxy object
,D/BluetoothManagerService(  759): Message: 30
,W/ContextImpl( 2560): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1376 
,D/BluetoothManagerService(  759): Message: 30
,D/LocalBluetoothProfileManager( 2560): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 2560): finishStartingService: stopping service
W/ContextImpl( 2560): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/BluetoothAdapterService(1113622824)( 2545): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2545): getBondedDevices: length=4
,D/dalvikvm( 2560): GC_CONCURRENT freed 308K, 2% free 16870K/17212K, paused 4ms+3ms, total 24ms
,D/BluetoothA2dp( 2560): Proxy object connected
,D/A2dpProfile( 2560): Bluetooth service connected
,D/BluetoothHeadset( 2560): Proxy object connected
,D/HeadsetProfile( 2560): Bluetooth service connected
,D/BluetoothInputDevice( 2560): Proxy object connected
,D/HidProfile( 2560): Bluetooth service connected
,D/BluetoothPan( 2560): BluetoothPAN Proxy object connected
D/PanProfile( 2560): Bluetooth service connected
D/BluetoothMap( 2560): Proxy object connected
D/MapProfile( 2560): Bluetooth service connected
,D/BluetoothMap( 2560): getConnectedDevices()
,D/BluetoothPbap( 2560): Proxy object connected
,D/PbapServerProfile( 2560): Bluetooth service connected
,D/dalvikvm( 2545): GC_CONCURRENT freed 296K, 2% free 16850K/17180K, paused 1ms+2ms, total 16ms
,D/AuthorizationBluetoothService( 1130): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1130): Proximity feature is not enabled.
W/BroadcastQueue(  759): Permission Denial: receiving Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 (has extras) } to com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver requires android.permission.BLUETOOTH due to sender android (uid 1000)
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2545): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 2545): SOCK FLAG = 0 ***********************
,I/BtOppRfcommListener( 2545): Accept thread started.
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 2494): Got Device Bluetooth address: 34:FC:EF:11:B1:66
I/jxcore-log( 2494): 
I/jxcore-log( 2494): my name is : LGE-Nexus 5_PT6772
I/jxcore-log( 2494): 
I/jxcore-log( 2494): attempting to connect to test coordinator
I/jxcore-log( 2494): 
I/jxcore-log( 2494): check test folder
I/jxcore-log( 2494): 
I/jxcore-log( 2494): found test : ./testFindPeers.js
I/jxcore-log( 2494): 
I/jxcore-log( 2494): found test : ./testReConnect.js
I/jxcore-log( 2494): 
I/jxcore-log( 2494): found test : ./testSendData.js
I/jxcore-log( 2494): 
I/jxcore-log( 2494): Test app app.js loaded
I/jxcore-log( 2494): 
I/Choreographer( 2494): Skipped 117 frames!  The application may be doing too much work on its main thread.
I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
I/chromium( 2494): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): BLE advertisement not supported: Build version is 19
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,D/ConnectivityService(  759): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  759): Done.
,D/ConnectivityService(  759): Setting timer for 720seconds
,D/ConnectivityService(  759): handleInetConditionChange: no active default network - ignore
,W/EventLoggerService( 1180): Unable to send logs Error code: 262146 | Unable to resolve host "www.google.com": No address associated with hostname
,D/dalvikvm( 1616): GC_CONCURRENT freed 406K, 3% free 17425K/17868K, paused 2ms+1ms, total 13ms
,D/Finsky  ( 1616): [1] 5.onFinished: Installation state replication succeeded.
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/PowerManagerService(  759): Going to sleep due to screen timeout...
,I/Adreno-EGL(  759): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/SurfaceFlinger(  183): Screen released, type=0 flinger=0xb7710450
,D/qdhwcomposer(  183): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  183): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  759): Excessive delay in blankDisplay() while turning screen off: 293ms
,V/KeyguardServiceDelegate(  759): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@43b8cec8)
,V/KeyguardServiceDelegate(  759): **** SHOWN CALLED ****
I/WindowManager(  759): No lock screen! windowToken=null
,D/NfcService( 1027): NFC-C OFF
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,D/ConnectivityService(  759): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,D/ConnectivityService(  759): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,D/ConnectivityService(  759): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,D/ConnectivityService(  759): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  759): Done.
,D/ConnectivityService(  759): Setting timer for 720seconds
,D/ConnectivityService(  759): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/ActivityManager(  759): Killing 1518:com.android.providers.calendar/u0a1 (adj 15): empty for 1812s
,I/ActivityManager(  759): Killing 1657:com.google.android.calendar/u0a28 (adj 15): empty for 1837s
,I/ActivityManager(  759): Killing 1751:com.google.android.gm/u0a41 (adj 15): empty for 1837s
,I/ActivityManager(  759): Killing 2077:com.google.android.music:main/u0a58 (adj 15): empty for 1837s
,I/ProcessStatsService(  759): Prepared write state in 42ms
,I/ProcessStatsService(  759): Prepared write state in 5ms
,F/ActivityManager(  759): Service ServiceRecord{42e44ca0 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{42e84ef8 2077:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  759): Service ServiceRecord{42e3d778 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{42e84ef8 2077:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  759): Service ServiceRecord{42d855a8 u0 com.google.android.music/.download.artwork.ArtDownloadService} in process ProcessRecord{42e84ef8 2077:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  759): Service ServiceRecord{42d7f210 u0 com.google.android.music/.download.ArtDownloadQueueService} in process ProcessRecord{42e84ef8 2077:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  759): Service ServiceRecord{42d4bca0 u0 com.google.android.music/.download.cache.ArtCacheService} in process ProcessRecord{42e84ef8 2077:com.google.android.music:main/u0a58} not same as in map: null
,I/ProcessStatsService(  759): Pruning old procstats: /data/system/procstats/state-2015-11-23-17-38-14.bin
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
,TIME-OUT KILL (timeout was 1800000ms),I/jxcore-log( 2494): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2494): 
D/AndroidRuntime( 2787): 
D/AndroidRuntime( 2787): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2787): CheckJNI is OFF
D/dalvikvm( 2787): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2787): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2787): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2787): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2787): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 2787): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/AndroidRuntime( 2787): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  759): Force stopping com.test.thalitest appid=10108 user=-1: uninstall pkg
I/ActivityManager(  759): Killing 2494:com.test.thalitest/u0a108 (adj 0): stop com.test.thalitest
I/ActivityManager(  759): Killing 2351:com.google.android.partnersetup/u0a11 (adj 15): empty for 1820s
I/ActivityManager(  759): Killing 953:android.process.acore/u0a3 (adj 15): empty for 1820s
I/ActivityManager(  759): Killing 2326:com.android.defcontainer/u0a4 (adj 15): empty for 1820s
I/ActivityManager(  759):   Force finishing activity ActivityRecord{42c02888 u0 com.test.thalitest/.MainActivity t2}
I/WindowState(  759): WIN DEATH: Window{44821d10 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  759): Skipping PackageSetting{42751818 com.example.hello/10115} due to missing metadata
I/ActivityManager(  759): Force stopping com.test.thalitest appid=10108 user=0: pkg removed
I/InputReader(  759): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine(  980): Ignoring removeGeofence because network location is disabled.
I/ActivityManager(  759): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=2811 uid=10003 gids={50003, 3003, 1028, 1015}
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "sms"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
D/dalvikvm( 1046): GC_EXPLICIT freed 1248K, 7% free 26141K/27916K, paused 1ms+2ms, total 41ms
I/Launcher( 1046): Deferring update until onResume
D/dalvikvm( 1180): GC_EXPLICIT freed 1183K, 7% free 17783K/19064K, paused 1ms+1ms, total 53ms
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "smsto"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/LatinIME:LogUtils(  967): Dictionary info: dictionary = main:en_us ; version = 44 ; date = 1393228158
D/dalvikvm(  759): GC_EXPLICIT freed 1548K, 53% free 26203K/55312K, paused 3ms+8ms, total 80ms
D/dalvikvm(  759): WAIT_FOR_CONCURRENT_GC blocked 47ms
D/dalvikvm(  967): GC_CONCURRENT freed 286K, 2% free 17003K/17320K, paused 2ms+1ms, total 13ms
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "mms"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/Launcher( 1046): Deferring update until onResume
W/Binder  (  967): Caught a RuntimeException from the binder stub implementation.
W/Binder  (  967): java.lang.NullPointerException
W/Binder  (  967): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  (  967): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  (  967): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  (  967): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  759): Got RemoteException sending setActive(false) notification to pid 2494 uid 10108
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "mmsto"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
D/dalvikvm(  759): GC_EXPLICIT freed 259K, 53% free 26104K/55312K, paused 2ms+5ms, total 72ms
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "sms"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
D/dalvikvm( 1004): GC_CONCURRENT freed 347K, 3% free 17055K/17432K, paused 1ms+1ms, total 9ms
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "smsto"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
D/BackupManagerService(  759): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  759): removePackageParticipantsLocked: uid=10108 #1
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "mms"
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
D/dalvikvm( 2811): GC_CONCURRENT freed 260K, 2% free 16949K/17240K, paused 1ms+1ms, total 13ms
D/dalvikvm( 2811): WAIT_FOR_CONCURRENT_GC blocked 4ms
D/dalvikvm( 2811): WAIT_FOR_CONCURRENT_GC blocked 3ms
I/PackageManager(  759):   Action: "android.intent.action.SENDTO"
I/PackageManager(  759):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  759):   Scheme: "mmsto"
D/VoicemailCleanupService( 2811): Cleaning up data for package: com.test.thalitest
I/PackageManager(  759): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
D/AndroidRuntime( 2787): Shutting down VM
D/dalvikvm( 2787): GC_CONCURRENT freed 94K, 15% free 558K/656K, paused 0ms+0ms, total 1ms
I/Icing.InternalIcingCorporaProvider( 1180): Updating corpora: A: com.test.thalitest, C: MAYBE
I/ActivityManager(  759): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/ActivityManager(  759): Resuming delayed broadcast
W/Launcher( 1046): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@42605aa0 new=com.google.android.velvet.VelvetApplication@42605aa0
I/ActivityManager(  759): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2840 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
W/ContextImpl( 2840): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2407 
I/ActivityManager(  759): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
I/ContactLocale( 2811): AddressBook Labels [en_US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/Icing.InternalIcingCorporaProvider( 1180): UpdateCorporaTask done [took 60 ms] updated apps [took 60 ms] 
D/dalvikvm( 1292): GC_CONCURRENT freed 440K, 3% free 18748K/19224K, paused 2ms+2ms, total 20ms
D/PackageBroadcastService( 1292): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1292): Clearing selected account for com.test.thalitest
I/ActivityManager(  759): Resuming delayed broadcast
I/ActivityManager(  759): Killing 2452:com.quickoffice.android/u0a65 (adj 15): empty for 1820s
I/ActivityManager(  759): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/LocationSettingsChecker( 1292): Removing dialog suppression flag for package com.test.thalitest
D/gH_CompatibleDatabase( 1292): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1292): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1292): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1292): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1292): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1292): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1292): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1292): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1292): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1292): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
W/BaseAppContext( 1292): Using Auth Proxy for data requests.
D/gH_CompatibleDatabase( 1292): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1292): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1292): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
W/BaseAppContext( 1292): Using Auth Proxy for data requests.
I/GMPM-SVC( 1292): App measurement is starting up
I/Icing   ( 1292): doRemovePackageData com.test.thalitest
I/PeopleContactsSync( 1292): CP2 sync disabled
D/dalvikvm( 1292): GC_CONCURRENT freed 494K, 3% free 18940K/19460K, paused 3ms+3ms, total 25ms
W/DriveInitializer( 1292): Awaiting to be initialized
W/DriveInitializer( 1292): Background init thread started
E/SQLiteLog( 1292): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock154] disk I/O error
E/DocListDatabase( 1292): Failed to delete from ContentFileDeletionLock154 table
E/DocListDatabase( 1292): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1292): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1292): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1292): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1292): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1292): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/DocListDatabase( 1292): 	at com.google.android.gms.drive.database.k.a(SourceFile:329)
E/DocListDatabase( 1292): 	at com.google.android.gms.drive.database.f.h(SourceFile:1062)
E/DocListDatabase( 1292): 	at com.google.android.gms.drive.s.run(SourceFile:62)
W/DriveInitializer( 1292): Background init thread ended
W/dalvikvm( 1292): threadid=26: thread exiting with uncaught exception (group=0x415abba8)
E/SQLiteLog( 1292): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1292): disk I/O error (code 3850)
E/DriveAsyncService( 1292): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1292): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1292): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1292): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1292): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1292): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1292): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1292): 	at com.google.android.gms.drive.database.k.k(SourceFile:485)
E/DriveAsyncService( 1292): 	at com.google.android.gms.drive.database.k.b(SourceFile:460)
E/DriveAsyncService( 1292): 	at com.google.android.gms.drive.database.f.i(SourceFile:1516)
E/DriveAsyncService( 1292): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1292): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/DriveAsyncService( 1292): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1292): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1292): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1292): 	at java.lang.Thread.run(Thread.java:841)
I/Process ( 1292): Sending signal. PID: 1292 SIG: 9
E/AndroidRuntime( 1292): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 1292): Process: com.google.android.gms, PID: 1292
E/AndroidRuntime( 1292): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1292): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1292): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1292): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1292): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1292): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1292): 	at com.google.android.gms.drive.database.k.a(SourceFile:329)
E/AndroidRuntime( 1292): 	at com.google.android.gms.drive.database.f.h(SourceFile:1062)
E/AndroidRuntime( 1292): 	at com.google.android.gms.drive.s.run(SourceFile:62)
E/DropBoxManagerService(  759): Can't write: system_app_crash
E/DropBoxManagerService(  759): java.io.FileNotFoundException: /data/system/dropbox/drop82.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  759): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  759): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  759): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  759): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  759): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  759): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10018)
E/DropBoxManagerService(  759): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  759): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  759): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  759): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  759): 	... 5 more
I/ActivityManager(  759): Process com.google.android.gms (pid 1292) has died.
W/ActivityManager(  759): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  759): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/ActivityManager(  759): Resuming delayed broadcast
W/ActivityManager(  759): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  759): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
I/ActivityManager(  759): Start proc com.google.android.gms for broadcast com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy: pid=2872 uid=10007 gids={50007, 3003, 1007, 1028, 1015, 3002, 3001, 3007, 2001, 3006}
W/dalvikvm( 2872): VFY: unable to resolve static field 529 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
D/dalvikvm( 2872): VFY: replacing opcode 0x60 at 0x000b
I/dalvikvm( 2872): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 2872): VFY: unable to resolve virtual method 10979: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
D/dalvikvm( 2872): VFY: replacing opcode 0x6e at 0x00ca

```
