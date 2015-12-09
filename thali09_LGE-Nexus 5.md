#### Test 5065027873d6a28_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
I/dalvikvm( 1296): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1296): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1296): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1296): VFY: unable to resolve new-instance 2320 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
D/dalvikvm( 1296): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1296): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1296): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
D/dalvikvm( 1296): DexOpt: unable to opt direct call 0x3207 at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
D/dalvikvm( 2520): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42802ae8
D/dalvikvm( 2520): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x42802ae8
D/dalvikvm( 2520): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42802ae8
D/dalvikvm( 2520): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42802ae8
D/dalvikvm( 2520): GC_CONCURRENT freed 444K, 3% free 17943K/18424K, paused 3ms+1ms, total 16ms
D/dalvikvm( 2520): GC_FOR_ALLOC freed 30K, 3% free 18001K/18424K, paused 12ms, total 13ms
D/ChimeraCfgMgr( 1296): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1296): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1296): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/AsyncTaskServiceImpl( 1296): Submit a task: h
D/ChimeraCfgMgr( 1296): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 1296): Loading module com.google.android.gms.vision from APK com.google.android.gms
I/PeopleContactsSync( 1296): CP2 sync disabled
D/h       ( 1296): Processing package: com.test.thalitest
D/GassUtils( 1296): Found app info for package com.test.thalitest:18. Hash: 01e4d8ac61718f1dcdc950940ea39ae21caf015e512d4d8080feb7f016346367
D/h       ( 1296): Found info for package com.test.thalitest in db.
I/dalvikvm( 1296): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1296): VFY: unable to resolve virtual method 34: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1296): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1296): Using Auth Proxy for data requests.
W/BaseAppContext( 1296): Using Auth Proxy for data requests.
--------- beginning of /dev/log/system
I/ActivityManager(  767): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2565 uid=10065 gids={50065, 3003, 1028, 1015}
D/dalvikvm( 1296): GC_CONCURRENT freed 375K, 3% free 18418K/18824K, paused 2ms+3ms, total 35ms
I/ProviderInstaller( 2520): Installed default security provider GmsCore_OpenSSL
W/BaseAppContext( 1296): Using Auth Proxy for data requests.
W/BaseAppContext( 1296): Using Auth Proxy for data requests.
W/BaseAppContext( 1296): Using Auth Proxy for data requests.
W/BaseAppContext( 1296): Using Auth Proxy for data requests.
W/Quickoffice( 2565): Cleanup of storage: done
D/com.google.android.apps.docs.quickoffice.X( 2565): Loading recent documents list
D/Quickoffice( 2565): The number of lines present in  /proc/mount 21
D/dalvikvm( 1296): GC_CONCURRENT freed 268K, 2% free 18632K/18932K, paused 2ms+2ms, total 20ms
D/Quickoffice( 2565): Parsing the storagedefinition.xml.
D/Quickoffice( 2565): # of Storagedefinitions - 35
D/Quickoffice( 2565): The # of storage definitions available - 35
D/Quickoffice( 2565): Processing mountline rootfs / rootfs ro,relatime 0 0
D/Quickoffice( 2565): Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
D/Quickoffice( 2565): Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
D/Quickoffice( 2565): Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
D/Quickoffice( 2565): Processing mountline proc /proc proc rw,relatime 0 0
D/Quickoffice( 2565): Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
D/Quickoffice( 2565): Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
D/Quickoffice( 2565): Processing mountline debugfs /sys/kernel/debug debugfs rw,relatime 0 0
D/Quickoffice( 2565): Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
D/Quickoffice( 2565): Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
D/Quickoffice( 2565): Processing mountline tmpfs /mnt/asec tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2565): Processing mountline tmpfs /mnt/obb tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2565): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,nosuid,nodev,relatime,data=ordered 0 0
D/Quickoffice( 2565): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2565): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2565): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2565): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
D/Quickoffice( 2565): Processing mountline /dev/fuse /mnt/shell/emulated fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2565): Processing mountline tmpfs /storage/emulated tmpfs rw,seclabel,nosuid,nodev,relatime,mode=751,gid=1028 0 0
D/Quickoffice( 2565): Processing mountline /dev/fuse /storage/emulated/0 fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2565): Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2565): Build properties are not configured for this storage definition.
D/Quickoffice( 2565): Adding the mount informaiton for listing in file manager MountedDeviceInformation [device=/dev/fuse, mountPath=/storage/emulated/legacy, fileSystemType=fuse, options=rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other, bootPriority1=0, bootPriority2=0, storageInfo=StorageDefinition [id=2010, matchPatterns=[/storage/emulated/legacy, fuse], skipPatterns=[obb], buildPatterns=[], type=INTERNAL, resourceString=2131231627, resourceStringItemized=2131231630, resourceIcon=2130838373, enabled=true], userFriendlyName=null]
D/Quickoffice( 2565): The # of mounts identified -  1
D/dalvikvm( 2565): GC_CONCURRENT freed 194K, 2% free 16940K/17164K, paused 1ms+6ms, total 21ms
D/com.google.android.apps.docs.quickoffice.X( 2565): Checking validity of 0 items
D/ContentResolverUtil( 2565): There are 0 persisted uri permissions.
D/com.google.android.apps.docs.quickoffice.X( 2565): 0 items were valid
W/ActivityManager(  767): No permission grants found for com.quickoffice.android
D/dalvikvm( 2302): GC_CONCURRENT freed 245K, 2% free 17546K/17824K, paused 1ms+1ms, total 13ms
I/ActivityManager(  767): Killing 1963:com.google.android.apps.maps/u0a57 (adj 15): empty #17
W/Quickoffice( 2565): Could not load clipboard.
D/ChimeraCfgMgr( 1296): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1296): Module APK com.google.android.play.games already loaded
W/Quickoffice( 2565): Could not store clipboard.
I/Icing   ( 1296): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
D/dalvikvm( 1296): GC_CONCURRENT freed 420K, 3% free 18743K/19196K, paused 3ms+1ms, total 18ms
I/Icing   ( 1296): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
D/dalvikvm( 1175): GC_CONCURRENT freed 471K, 3% free 18475K/18976K, paused 1ms+1ms, total 11ms
,D/AndroidRuntime( 2608): 
D/AndroidRuntime( 2608): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2608): CheckJNI is OFF
D/dalvikvm( 2608): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2608): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2608): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2608): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2608): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 2608): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/AndroidRuntime( 2608): Calling main entry com.android.commands.am.Am
I/ActivityManager(  767): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2608
D/PermissionCache(  182): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (103 us)
D/AndroidRuntime( 2608): Shutting down VM
D/dalvikvm( 2608): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 0ms+0ms, total 2ms
I/ActivityManager(  767): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2627 uid=10108 gids={50108, 3003, 3001, 3002, 1028, 1015}
I/MicrophoneInputStream( 1175): mic_close
I/SearchController( 1175): #onHotwordDetectorStopped(false)
I/MicroHotwordRecognitionRunner( 1175): Hotword detection finished
I/MicroHotwordRecognitionRunner( 1175): Stopping hotword detection.
I/ActivityManager(  767): Killing 1719:com.google.android.deskclock/u0a33 (adj 15): empty #17
I/ActivityManager(  767): Killing 1991:com.google.android.youtube/u0a71 (adj 15): empty #18
V/WebViewChromiumFactoryProvider( 2627): Binding Chromium to main looper Looper (main, tid 1) {426822b0}
I/LibraryLoader( 2627): Expected native library version number "",actual native library version number ""
I/chromium( 2627): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2627): Initializing chromium process, renderers=0
D/BluetoothManagerService(  767): Message: 20
D/BluetoothManagerService(  767): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@443e3568:true
D/BluetoothAdapter( 2627): 1114210760: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 2627): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
W/chromium( 2627): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
F/ActivityManager(  767): Service ServiceRecord{42c4ce28 u0 com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService} in process ProcessRecord{42c93c98 1991:com.google.android.youtube/u0a71} not same as in map: null
I/dalvikvm( 2627): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2627): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2627): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2627): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2627): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 2627): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 2627): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2627): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2627): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2627): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2627): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 2627): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2627): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2627): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2627): VFY: replacing opcode 0x6e at 0x000d
D/dalvikvm(  987): GC_CONCURRENT freed 366K, 3% free 17882K/18344K, paused 4ms+2ms, total 20ms
I/dalvikvm( 2627): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2627): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2627): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 2627): CordovaWebView is running on device made by: LGE
,D/OpenGLRenderer( 2627): Enabling debug mode 0
,W/AwContents( 2627): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  767): Displayed com.test.thalitest/.MainActivity: +314ms
,D/JsMessageQueue( 2627): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 2627): GC_CONCURRENT freed 233K, 2% free 16888K/17152K, paused 2ms+3ms, total 18ms
,D/dalvikvm( 2627): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x426870a8
,D/dalvikvm( 2627): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x426870a8
D/jxcore_app_log( 2627): JniHelper::setJavaVM(0x41623ed0), pthread_self() = 1982499264
,D/JX-Cordova( 2627): jxcore cordova android initializing
I/dalvikvm( 2627): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 2627): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 2627): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 2627): GC_CONCURRENT freed 218K, 2% free 17181K/17428K, paused 2ms+2ms, total 11ms
,D/dalvikvm( 2627): GC_CONCURRENT freed 158K, 2% free 17525K/17724K, paused 1ms+0ms, total 10ms
,D/dalvikvm( 2627): WAIT_FOR_CONCURRENT_GC blocked 5ms
,D/dalvikvm( 2627): GC_CONCURRENT freed 155K, 2% free 17870K/18068K, paused 1ms+1ms, total 14ms
,D/dalvikvm( 2627): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/dalvikvm( 2627): GC_CONCURRENT freed 151K, 2% free 18215K/18412K, paused 1ms+2ms, total 16ms
,D/dalvikvm( 2627): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 2627): GC_CONCURRENT freed 157K, 2% free 18550K/18756K, paused 1ms+2ms, total 21ms
,D/dalvikvm( 2627): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 2627): GC_CONCURRENT freed 178K, 2% free 18968K/19200K, paused 1ms+1ms, total 12ms
,D/dalvikvm( 2627): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 2627): GC_CONCURRENT freed 220K, 2% free 19478K/19756K, paused 2ms+2ms, total 26ms
,D/dalvikvm( 2627): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 2627): GC_CONCURRENT freed 279K, 2% free 20094K/20436K, paused 1ms+3ms, total 27ms
,D/dalvikvm( 2627): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 2627): GC_CONCURRENT freed 326K, 2% free 20859K/21256K, paused 1ms+2ms, total 31ms
,D/dalvikvm( 2627): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 2627): GC_CONCURRENT freed 402K, 3% free 21796K/22276K, paused 2ms+3ms, total 36ms
,D/dalvikvm( 2627): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/dalvikvm( 2627): GC_CONCURRENT freed 1185K, 6% free 22275K/23528K, paused 2ms+3ms, total 38ms
,D/dalvikvm( 2627): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/dalvikvm( 2627): GC_CONCURRENT freed 1510K, 7% free 22552K/24164K, paused 2ms+3ms, total 39ms
,D/dalvikvm( 2627): WAIT_FOR_CONCURRENT_GC blocked 33ms
,D/dalvikvm( 2627): GC_FOR_ALLOC freed 9K, 7% free 22553K/24164K, paused 30ms, total 30ms
I/dalvikvm-heap( 2627): Grow heap (frag case) to 22.746MB for 728606-byte allocation
,D/dalvikvm( 2627): GC_FOR_ALLOC freed 15K, 7% free 23249K/24876K, paused 20ms, total 20ms
,D/dalvikvm( 2627): GC_FOR_ALLOC freed 1295K, 9% free 22772K/24876K, paused 22ms, total 23ms
,I/dalvikvm-heap( 2627): Grow heap (frag case) to 23.307MB for 1092904-byte allocation
,D/dalvikvm( 2627): GC_FOR_ALLOC freed 2K, 9% free 23836K/25944K, paused 21ms, total 21ms
,D/dalvikvm( 2627): GC_FOR_ALLOC freed 1944K, 11% free 23178K/25944K, paused 23ms, total 24ms
,I/dalvikvm-heap( 2627): Grow heap (frag case) to 24.224MB for 1639352-byte allocation
,D/dalvikvm( 2627): GC_FOR_ALLOC freed 1079K, 14% free 23700K/27548K, paused 25ms, total 25ms
,D/dalvikvm( 2627): GC_FOR_ALLOC freed 1953K, 14% free 23811K/27548K, paused 24ms, total 25ms
,I/dalvikvm-heap( 2627): Grow heap (frag case) to 25.625MB for 2459024-byte allocation
,D/dalvikvm( 2627): GC_CONCURRENT freed 83K, 13% free 26129K/29952K, paused 2ms+1ms, total 23ms
,D/dalvikvm( 2627): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 2627): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 2627): GC_CONCURRENT freed 4535K, 18% free 24730K/29952K, paused 2ms+3ms, total 30ms
,D/dalvikvm( 2627): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/dalvikvm-heap( 2627): Grow heap (frag case) to 27.694MB for 3688532-byte allocation
,D/dalvikvm( 2627): GC_FOR_ALLOC freed 2415K, 23% free 25917K/33556K, paused 36ms, total 36ms
,D/dalvikvm( 2627): GC_CONCURRENT freed 285K, 23% free 26133K/33556K, paused 2ms+18ms, total 61ms
,W/jxcore-log( 2627): Initializing JXcore engine
,W/jxcore-log( 2627): JXcore engine is ready
,D/dalvikvm( 2627): GC_CONCURRENT freed 859K, 16% free 28344K/33556K, paused 5ms+12ms, total 31ms
,W/jxcore-log( 2627): Starting JXcore engine
,W/jxcore-log( 2627): Platform android
W/jxcore-log( 2627): 
,W/jxcore-log( 2627): Process ARCH arm
W/jxcore-log( 2627): 
,I/jxcore-log( 2627): JXcore Cordova bridge is ready!
I/jxcore-log( 2627): 
,W/jxcore-log( 2627): JXcore engine is started
,I/chromium( 2627): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 2627): Error!: missing ) after argument list
E/jxcore  ( 2627): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 2627): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,W/PluginManager( 2627): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 32ms. Plugin should use CordovaInterface.getThreadPool().
,W/Sidekick_LocationOracleImpl( 1175): Best location was null
,W/GCoreFlp(  987): No location to return for getLastLocation()
,W/IInputConnectionWrapper( 2627): showStatusIcon on inactive InputConnection
,D/dalvikvm( 1175): GC_FOR_ALLOC freed 726K, 6% free 17845K/18976K, paused 16ms, total 17ms
,I/dalvikvm-heap( 1175): Grow heap (frag case) to 18.064MB for 640016-byte allocation
,W/GCoreFlp(  987): No location to return for getLastLocation()
,D/dalvikvm( 1175): GC_FOR_ALLOC freed <1K, 3% free 18470K/18976K, paused 25ms, total 25ms
,I/MicroHotwordRecognitionRunner( 1175): Starting hotword detection.
,D/dalvikvm( 1175): GC_CONCURRENT freed 3K, 3% free 18473K/18976K, paused 2ms+1ms, total 17ms
,W/GCoreFlp(  987): No location to return for getLastLocation()
,W/GCoreFlp(  987): No location to return for getLastLocation()
D/audio_hw_primary(  185): select_devices: out_snd_device(0: ) in_snd_device(35: voice-rec-mic)
D/        (  185): Failed to fetch the lookup information of the device 0000003E 
,E/ACDB-LOADER(  185): Error: ACDB AudProc vol returned = -19
,W/GCoreFlp(  987): No location to return for getLastLocation()
,W/GCoreFlp(  987): No location to return for getLastLocation()
,I/SearchController( 1175): #onHotwordDetectorStarted
,E/libEGL  ( 2627): call to OpenGL ES API with no current context (logged once per thread)
,D/dalvikvm( 1620): GC_CONCURRENT freed 391K, 3% free 17421K/17848K, paused 3ms+1ms, total 12ms
,D/Finsky  ( 1620): [1] 5.onFinished: Installation state replication succeeded.
,D/ConnectivityService(  767): handleInetConditionChange: no active default network - ignore
,I/PowerManagerService(  767): Going to sleep due to screen timeout...
,I/Adreno-EGL(  767): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/SurfaceFlinger(  182): Screen released, type=0 flinger=0xb89b2450
,D/qdhwcomposer(  182): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  182): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  767): Excessive delay in blankDisplay() while turning screen off: 291ms
,V/KeyguardServiceDelegate(  767): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@44bf76b8)
,V/KeyguardServiceDelegate(  767): **** SHOWN CALLED ****
,I/WindowManager(  767): No lock screen! windowToken=null
,I/SearchController( 1175): #onHotwordDetectorStopped(false)
,I/MicrophoneInputStream( 1175): mic_close
,I/ActivityManager(  767): Killing 1841:com.google.android.email/u0a36 (adj 15): empty #17
,D/NfcService( 1038): NFC-C OFF
,I/MicroHotwordRecognitionRunner( 1175): Stopping hotword detection.
,I/MicroHotwordRecognitionRunner( 1175): Hotword detection finished
,W/EventLoggerService( 1175): Unable to send logs Error code: 262146 | Unable to resolve host "www.google.com": No address associated with hostname
,W/SocketClient(  179): write error (Broken pipe)
,D/ConnectivityService(  767): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  179): write error (Broken pipe)
,D/ConnectivityService(  767): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  179): write error (Broken pipe)
,D/ConnectivityService(  767): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  767): Done.
,D/ConnectivityService(  767): Setting timer for 720seconds
,D/ConnectivityService(  767): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  179): write error (Broken pipe)
,D/ConnectivityService(  767): Sampling interval elapsed, updating statistics ..
,I/ProcessStatsService(  767): Prepared write state in 47ms
,I/ProcessStatsService(  767): Prepared write state in 3ms
,D/ConnectivityService(  767): Done.
,D/ConnectivityService(  767): Setting timer for 720seconds
,D/ConnectivityService(  767): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  179): write error (Broken pipe)
,I/ProcessStatsService(  767): Pruning old procstats: /data/system/procstats/state-2015-12-08-07-27-00.bin
,I/ActivityManager(  767): Delay finish: com.google.android.gms/.checkin.EventLogService$Receiver
,I/ActivityManager(  767): Resuming delayed broadcast
,D/dalvikvm(  767): GC_EXPLICIT freed 23920K, 52% free 27254K/56064K, paused 4ms+5ms, total 106ms
,V/GLSActivity( 1126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1126): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1296): Aggregate from 1449626468067 (log), 1449626468067 (data)
,W/SocketClient(  179): write error (Broken pipe)
,I/ActivityManager(  767): Killing 2100:com.google.android.music:main/u0a58 (adj 15): empty for 1800s
,F/ActivityManager(  767): Service ServiceRecord{42e02f28 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{42e0ce80 2100:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  767): Service ServiceRecord{42de4b88 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{42e0ce80 2100:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  767): Service ServiceRecord{42dd4ab0 u0 com.google.android.music/.download.artwork.ArtDownloadService} in process ProcessRecord{42e0ce80 2100:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  767): Service ServiceRecord{42d2cd50 u0 com.google.android.music/.download.ArtDownloadQueueService} in process ProcessRecord{42e0ce80 2100:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  767): Service ServiceRecord{42d05bd8 u0 com.google.android.music/.download.cache.ArtCacheService} in process ProcessRecord{42e0ce80 2100:com.google.android.music:main/u0a58} not same as in map: null
,I/ActivityManager(  767): Killing 1675:com.google.android.calendar/u0a28 (adj 15): empty for 1800s
,I/ActivityManager(  767): Killing 1763:com.google.android.gm/u0a41 (adj 15): empty for 1800s
,I/ActivityManager(  767): Killing 2148:com.android.providers.calendar/u0a1 (adj 15): empty for 1812s
,TIME-OUT KILL (timeout was 1800000ms)
```
