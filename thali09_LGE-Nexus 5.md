#### Test 50650278d0426ce_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
D/dalvikvm( 2517): GC_CONCURRENT freed 280K, 2% free 18012K/18324K, paused 2ms+2ms, total 19ms
D/dalvikvm( 2517): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2517): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2517): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2517): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2517): VFY: unable to resolve instance field 36
D/dalvikvm( 2517): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2517): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2517): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2517): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2517): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 2517): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 2517): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427429a8
D/dalvikvm( 2517): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427429a8
D/dalvikvm( 2517): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427429a8, skipping init
D/dalvikvm( 2517): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427429a8
D/dalvikvm( 2517): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427429a8
V/JNIHelp ( 2517): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/dalvikvm( 1290): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1290): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1290): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1290): VFY: unable to resolve new-instance 2320 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
D/dalvikvm( 1290): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1290): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1290): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
D/dalvikvm( 1290): DexOpt: unable to opt direct call 0x3207 at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
D/dalvikvm( 2517): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x427429a8
D/dalvikvm( 2517): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x427429a8
D/dalvikvm( 2517): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x427429a8
D/dalvikvm( 2517): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x427429a8
D/dalvikvm( 2517): GC_CONCURRENT freed 508K, 3% free 18001K/18544K, paused 2ms+1ms, total 16ms
D/dalvikvm( 2517): WAIT_FOR_CONCURRENT_GC blocked 1ms
I/dalvikvm-heap( 2517): Grow heap (frag case) to 17.682MB for 79892-byte allocation
D/dalvikvm( 2517): GC_FOR_ALLOC freed <1K, 3% free 18078K/18624K, paused 14ms, total 14ms
D/ChimeraCfgMgr( 1290): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1290): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1290): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/AsyncTaskServiceImpl( 1290): Submit a task: k
D/ChimeraCfgMgr( 1290): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 1290): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/k       ( 1290): Processing package: com.test.thalitest
W/BaseAppContext( 1290): Using Auth Proxy for data requests.
W/BaseAppContext( 1290): Using Auth Proxy for data requests.
D/GassUtils( 1290): Found app info for package com.test.thalitest:18. Hash: 01e4d8ac61718f1dcdc950940ea39ae21caf015e512d4d8080feb7f016346367
D/k       ( 1290): Found info for package com.test.thalitest in db.
--------- beginning of /dev/log/system
I/ActivityManager(  763): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2573 uid=10065 gids={50065, 3003, 1028, 1015}
I/ProviderInstaller( 2517): Installed default security provider GmsCore_OpenSSL
D/dalvikvm( 1290): GC_CONCURRENT freed 473K, 3% free 18762K/19248K, paused 3ms+4ms, total 40ms
W/BaseAppContext( 1290): Using Auth Proxy for data requests.
W/BaseAppContext( 1290): Using Auth Proxy for data requests.
W/BaseAppContext( 1290): Using Auth Proxy for data requests.
W/BaseAppContext( 1290): Using Auth Proxy for data requests.
W/dalvikvm( 1290): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1290): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1290): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1290): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 1290): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1290): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1290): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1290): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1290): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1290): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1290): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1290): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1290): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1290): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1290): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1290): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
D/dalvikvm( 1290): VFY: replacing opcode 0x6e at 0x0006
I/PeopleDatabaseHelper( 1290): cleanUpNonGplusAccounts done.
W/Quickoffice( 2573): Cleanup of storage: done
D/com.google.android.apps.docs.quickoffice.X( 2573): Loading recent documents list
D/Quickoffice( 2573): The number of lines present in  /proc/mount 21
D/Quickoffice( 2573): Parsing the storagedefinition.xml.
D/Quickoffice( 2573): # of Storagedefinitions - 35
D/Quickoffice( 2573): The # of storage definitions available - 35
D/Quickoffice( 2573): Processing mountline rootfs / rootfs ro,relatime 0 0
D/Quickoffice( 2573): Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
D/AndroidRuntime( 2584): 
D/AndroidRuntime( 2584): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/Quickoffice( 2573): Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
D/Quickoffice( 2573): Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
D/Quickoffice( 2573): Processing mountline proc /proc proc rw,relatime 0 0
D/Quickoffice( 2573): Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
D/AndroidRuntime( 2584): CheckJNI is OFF
D/Quickoffice( 2573): Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
D/Quickoffice( 2573): Processing mountline debugfs /sys/kernel/debug debugfs rw,relatime 0 0
D/Quickoffice( 2573): Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
D/Quickoffice( 2573): Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
D/Quickoffice( 2573): Processing mountline tmpfs /mnt/asec tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2573): Processing mountline tmpfs /mnt/obb tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2573): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,nosuid,nodev,relatime,data=ordered 0 0
D/Quickoffice( 2573): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2573): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2573): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2573): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
D/Quickoffice( 2573): Processing mountline /dev/fuse /mnt/shell/emulated fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2573): Processing mountline tmpfs /storage/emulated tmpfs rw,seclabel,nosuid,nodev,relatime,mode=751,gid=1028 0 0
D/Quickoffice( 2573): Processing mountline /dev/fuse /storage/emulated/0 fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/dalvikvm( 2584): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2584): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2584): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2584): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2584): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/Quickoffice( 2573): Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2573): Build properties are not configured for this storage definition.
D/dalvikvm( 1290): GC_CONCURRENT freed 393K, 3% free 18966K/19392K, paused 1ms+2ms, total 22ms
D/Quickoffice( 2573): Adding the mount informaiton for listing in file manager MountedDeviceInformation [device=/dev/fuse, mountPath=/storage/emulated/legacy, fileSystemType=fuse, options=rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other, bootPriority1=0, bootPriority2=0, storageInfo=StorageDefinition [id=2010, matchPatterns=[/storage/emulated/legacy, fuse], skipPatterns=[obb], buildPatterns=[], type=INTERNAL, resourceString=2131231627, resourceStringItemized=2131231630, resourceIcon=2130838373, enabled=true], userFriendlyName=null]
D/Quickoffice( 2573): The # of mounts identified -  1
D/com.google.android.apps.docs.quickoffice.X( 2573): Checking validity of 0 items
D/dalvikvm( 2573): GC_CONCURRENT freed 189K, 2% free 16971K/17172K, paused 4ms+2ms, total 31ms
D/ContentResolverUtil( 2573): There are 0 persisted uri permissions.
D/dalvikvm( 2584): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/com.google.android.apps.docs.quickoffice.X( 2573): 0 items were valid
W/ActivityManager(  763): No permission grants found for com.quickoffice.android
D/ConnectivityService(  763): Sampling interval elapsed, updating statistics ..
D/ConnectivityService(  763): Done.
D/ConnectivityService(  763): Setting timer for 720seconds
I/ActivityManager(  763): Killing 1991:com.google.android.apps.maps/u0a57 (adj 15): empty #17
W/Quickoffice( 2573): Could not load clipboard.
W/Quickoffice( 2573): Could not store clipboard.
D/ChimeraCfgMgr( 1290): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1290): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 2584): Calling main entry com.android.commands.am.Am
I/ActivityManager(  763): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2584
D/PermissionCache(  183): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (95 us)
I/Icing   ( 1290): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
D/AndroidRuntime( 2584): Shutting down VM
D/dalvikvm( 2584): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 1ms+0ms, total 2ms
I/ActivityManager(  763): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2616 uid=10108 gids={50108, 3003, 3001, 3002, 1028, 1015}
I/SearchController( 1178): #onHotwordDetectorStopped(false)
I/MicrophoneInputStream( 1178): mic_close
V/WebViewChromiumFactoryProvider( 2616): Binding Chromium to main looper Looper (main, tid 1) {425bc3f0}
I/LibraryLoader( 2616): Expected native library version number "",actual native library version number ""
I/chromium( 2616): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2616): Initializing chromium process, renderers=0
D/BluetoothManagerService(  763): Message: 20
D/BluetoothManagerService(  763): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44370490:true
D/BluetoothAdapter( 2616): 1113399424: getState() :  mService = null. Returning STATE_OFF
D/dalvikvm( 1178): GC_CONCURRENT freed 603K, 4% free 18291K/18924K, paused 2ms+9ms, total 50ms
I/MicroHotwordRecognitionRunner( 1178): Hotword detection finished
I/MicroHotwordRecognitionRunner( 1178): Stopping hotword detection.
I/ActivityManager(  763): Killing 2023:com.google.android.youtube/u0a71 (adj 15): empty #17
I/Adreno-EGL( 2616): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
F/ActivityManager(  763): Service ServiceRecord{42d2dc98 u0 com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService} in process ProcessRecord{42c16720 2023:com.google.android.youtube/u0a71} not same as in map: null
W/chromium( 2616): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 2616): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2616): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2616): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2616): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2616): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 2616): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 2616): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2616): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2616): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2616): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2616): VFY: replacing opcode 0x6f at 0x001a
I/Icing   ( 1290): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
W/dalvikvm( 2616): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2616): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2616): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2616): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2616): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2616): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2616): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 2616): CordovaWebView is running on device made by: LGE
,D/OpenGLRenderer( 2616): Enabling debug mode 0
W/AwContents( 2616): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  763): Displayed com.test.thalitest/.MainActivity: +272ms
D/JsMessageQueue( 2616): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 2616): GC_CONCURRENT freed 257K, 2% free 16906K/17192K, paused 3ms+2ms, total 18ms
D/dalvikvm( 2616): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x425c0f60
D/dalvikvm( 2616): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x425c0f60
D/jxcore_app_log( 2616): JniHelper::setJavaVM(0x414a7f00), pthread_self() = 1982519744
D/JX-Cordova( 2616): jxcore cordova android initializing
I/Icing   ( 1290): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
I/dalvikvm( 2616): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 2616): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 2616): VFY: replacing opcode 0x6e at 0x0045
D/dalvikvm( 1290): GC_CONCURRENT freed 486K, 3% free 19195K/19712K, paused 3ms+2ms, total 20ms
D/dalvikvm( 2616): GC_CONCURRENT freed 200K, 2% free 17185K/17416K, paused 1ms+2ms, total 10ms
I/Icing   ( 1290): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
I/ActivityManager(  763): Killing 1720:com.google.android.deskclock/u0a33 (adj 15): empty #17
D/dalvikvm( 2616): GC_CONCURRENT freed 158K, 2% free 17530K/17728K, paused 1ms+1ms, total 10ms
D/dalvikvm( 2616): WAIT_FOR_CONCURRENT_GC blocked 5ms
D/dalvikvm( 2616): GC_CONCURRENT freed 155K, 2% free 17875K/18072K, paused 1ms+1ms, total 10ms
D/dalvikvm( 2616): WAIT_FOR_CONCURRENT_GC blocked 5ms
D/dalvikvm( 2616): GC_CONCURRENT freed 152K, 2% free 18219K/18416K, paused 1ms+2ms, total 13ms
D/dalvikvm( 2616): WAIT_FOR_CONCURRENT_GC blocked 8ms
D/dalvikvm( 2616): GC_CONCURRENT freed 157K, 2% free 18555K/18760K, paused 1ms+1ms, total 12ms
D/dalvikvm( 2616): WAIT_FOR_CONCURRENT_GC blocked 5ms
D/dalvikvm( 2616): GC_CONCURRENT freed 179K, 2% free 18976K/19208K, paused 1ms+2ms, total 19ms
D/dalvikvm( 2616): WAIT_FOR_CONCURRENT_GC blocked 13ms
D/dalvikvm( 2616): GC_CONCURRENT freed 221K, 2% free 19488K/19768K, paused 2ms+1ms, total 16ms
D/dalvikvm( 2616): WAIT_FOR_CONCURRENT_GC blocked 10ms
D/dalvikvm( 2616): GC_CONCURRENT freed 280K, 2% free 20108K/20452K, paused 1ms+2ms, total 20ms
D/dalvikvm( 2616): WAIT_FOR_CONCURRENT_GC blocked 15ms
D/dalvikvm( 2616): GC_CONCURRENT freed 327K, 2% free 20876K/21276K, paused 1ms+2ms, total 27ms
D/dalvikvm( 2616): WAIT_FOR_CONCURRENT_GC blocked 22ms
D/dalvikvm( 2616): GC_CONCURRENT freed 403K, 3% free 21816K/22300K, paused 1ms+1ms, total 22ms
D/dalvikvm( 2616): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 2616): GC_CONCURRENT freed 1209K, 6% free 22279K/23556K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 2616): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 2616): GC_CONCURRENT freed 1488K, 7% free 22551K/24160K, paused 2ms+1ms, total 25ms
,D/dalvikvm( 2616): WAIT_FOR_CONCURRENT_GC blocked 14ms
,I/dalvikvm-heap( 2616): Grow heap (frag case) to 22.745MB for 728606-byte allocation
,D/dalvikvm( 2616): GC_FOR_ALLOC freed 475K, 9% free 22787K/24872K, paused 21ms, total 21ms
,D/dalvikvm( 2616): GC_FOR_ALLOC freed 833K, 9% free 22772K/24872K, paused 21ms, total 21ms
,I/dalvikvm-heap( 2616): Grow heap (frag case) to 23.307MB for 1092904-byte allocation
,D/dalvikvm( 2616): GC_FOR_ALLOC freed 1K, 9% free 23838K/25940K, paused 21ms, total 21ms
,D/dalvikvm( 2616): GC_FOR_ALLOC freed 1945K, 11% free 23178K/25940K, paused 21ms, total 23ms
,I/dalvikvm-heap( 2616): Grow heap (frag case) to 24.225MB for 1639352-byte allocation
,D/dalvikvm( 2616): GC_FOR_ALLOC freed 1075K, 14% free 23704K/27544K, paused 21ms, total 21ms
,D/dalvikvm( 2616): GC_FOR_ALLOC freed 1957K, 14% free 23812K/27544K, paused 23ms, total 23ms
,I/dalvikvm-heap( 2616): Grow heap (frag case) to 25.625MB for 2459024-byte allocation
,D/dalvikvm( 2616): GC_CONCURRENT freed 0K, 13% free 26213K/29948K, paused 4ms+1ms, total 25ms
,D/dalvikvm( 2616): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 2616): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 2616): GC_CONCURRENT freed 4610K, 18% free 24740K/29948K, paused 2ms+4ms, total 33ms
,D/dalvikvm( 2616): WAIT_FOR_CONCURRENT_GC blocked 4ms
,I/dalvikvm-heap( 2616): Grow heap (frag case) to 27.705MB for 3688532-byte allocation
,D/dalvikvm( 2616): GC_FOR_ALLOC freed 2418K, 23% free 25924K/33552K, paused 23ms, total 24ms
,D/dalvikvm( 2616): GC_CONCURRENT freed 176K, 23% free 25941K/33552K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 2616): GC_FOR_ALLOC freed 963K, 24% free 25667K/33552K, paused 20ms, total 20ms
,W/jxcore-log( 2616): Initializing JXcore engine
,W/jxcore-log( 2616): JXcore engine is ready
,D/dalvikvm( 2616): GC_CONCURRENT freed 5418K, 31% free 23220K/33552K, paused 2ms+2ms, total 28ms
,D/dalvikvm( 2616): WAIT_FOR_CONCURRENT_GC blocked 21ms
W/jxcore-log( 2616): Starting JXcore engine
,W/jxcore-log( 2616): Platform android
W/jxcore-log( 2616): 
,W/jxcore-log( 2616): Process ARCH arm
W/jxcore-log( 2616): 
,I/jxcore-log( 2616): JXcore Cordova bridge is ready!
I/jxcore-log( 2616): 
,W/jxcore-log( 2616): JXcore engine is started
,I/chromium( 2616): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 2616): Toggling radios to true
I/jxcore-log( 2616): 
,D/BluetoothManagerService(  763): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  763): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  763): Message: 1
,D/BluetoothManagerService(  763): MESSAGE_ENABLE: mBluetooth = null
D/WifiService(  763): setWifiEnabled: true pid=2616, uid=10108
I/ActivityManager(  763): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=2668 uid=1002 gids={41002, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008}
,I/jxcore-log( 2616): Radios toggled
I/jxcore-log( 2616): 
,D/SoftapController(  180): Softap fwReload - Ok
D/CommandListener(  180): Setting iface cfg
,D/CommandListener(  180): Trying to bring down wlan0
,I/wpa_supplicant( 2681): Successfully initialized wpa_supplicant
D/AdapterServiceConfig( 2668): Adding HeadsetService
D/AdapterServiceConfig( 2668): Adding A2dpService
D/AdapterServiceConfig( 2668): Adding HidService
D/AdapterServiceConfig( 2668): Adding HealthService
D/AdapterServiceConfig( 2668): Adding PanService
D/AdapterServiceConfig( 2668): Adding GattService
,D/AdapterServiceConfig( 2668): Adding BluetoothMapService
,D/BluetoothAdapterService( 2668): REFCOUNT: CREATED. INSTANCE_COUNT1
,D/BluetoothManagerService(  763): Message: 20
,D/BluetoothManagerService(  763): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@441f3320:true
D/BluetoothAdapterState( 2668): make
,I/wpa_supplicant( 2681): rfkill: Cannot open RFKILL control device
,I/bluedroid( 2668): init
,I/BluetoothAdapterState( 2668): Entering OffState
,I/bte_conf( 2668): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bluedroid( 2668): get_profile_interface socket
,D/BluetoothManagerService(  763): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  763): Message: 40
,D/BluetoothManagerService(  763): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 2668): config_hci_snoop_log
D/BluetoothManagerService(  763): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  763): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 2668): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 2668): Setting state to 11
I/BluetoothAdapterState( 2668): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 2668): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  763): Message: 60
D/BluetoothManagerService(  763): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  763): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 2668): make
,D/WifiMonitor(  763): startMonitoring(wlan0) with mConnected = false
I/ActivityManager(  763): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=2685 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
,D/BluetoothHeadset(  763): Proxy object connected
,D/BluetoothHeadset( 1008): Proxy object connected
D/BluetoothHeadset( 1008): Proxy object connected
,D/BluetoothHeadset( 1008): Proxy object connected
,D/HeadsetService( 2668): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 2668): classInitNative: succeeds
,D/HeadsetStateMachine( 2668): make
I/BluetoothBondStateMachine( 2668): StableState(): Entering Off State
,I/GKI_LINUX( 2668): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
I/BluetoothAdapterProperties( 2668): adapterPropertyChangedCallback with type:2 len:6
,D/BluetoothAdapterProperties( 2668): Address is:34:FC:EF:11:B1:66
,I/BluetoothAdapterProperties( 2668): adapterPropertyChangedCallback with type:1 len:7
,D/BluetoothAdapterProperties( 2668): Name is: Nexus 5
D/BluetoothManagerService(  763): Bluetooth Adapter name changed to Nexus 5
,D/BluetoothManagerService(  763): Stored Bluetooth name: Nexus 5
,I/BluetoothAdapterState( 2668): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/bluedroid( 2668): get_profile_interface handsfree
,D/BluetoothA2dp(  763): Proxy object connected
D/A2dpService( 2668): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 2668): classInitNative: succeeds
V/Avrcp   ( 2668): make
,I/bluedroid( 2668): get_profile_interface avrcp
,I/BluetoothA2dpServiceJni( 2668): classInitNative: succeeds
D/A2dpStateMachine( 2668): make
,I/bluedroid( 2668): get_profile_interface a2dp
,I/GKI_LINUX( 2668): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,I/BluetoothHidServiceJni( 2668): classInitNative: succeeds
,D/A2dpStateMachine( 2668): Enter Disconnected: -2
D/HidService( 2668): Received start request. Starting profile...
,I/bluedroid( 2668): get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 2668): classInitNative: succeeds
,D/HealthService( 2668): Received start request. Starting profile...
,I/bluedroid( 2668): get_profile_interface health
,I/BluetoothPanServiceJni( 2668): classInitNative(L105): succeeds
,D/BluetoothPan(  763): BluetoothPAN Proxy object connected
D/PanService( 2668): Received start request. Starting profile...
D/BluetoothPanServiceJni( 2668): initializeNative(L110): pan
,I/bluedroid( 2668): get_profile_interface pan
,D/BluetoothTethering(  763): got CMD_CHANNEL_HALF_CONNECTED
I/BtGatt.JNI( 2668): classInitNative(L684): classInitNative: Success!
D/BtGatt.DebugUtils( 2668): handleDebugAction() action=null
D/BtGatt.GattService( 2668): Received start request. Starting profile...
D/BtGatt.GattService( 2668): start()
I/bluedroid( 2668): get_profile_interface gatt
D/BluetoothMapService( 2668): Received start request. Starting profile...
D/BluetoothMapService( 2668): start()
D/HeadsetPhoneState( 2668): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterService( 2668): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 2668): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 2668): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 2668): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2668): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 2668): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterState( 2668): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 2668): enable
,I/bt_hci_bdroid( 2668): init
,I/bt_vendor( 2668): init
I/bt_vnd_conf( 2668): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 2668): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,I/bt_hci_bdroid( 2668): bt_hc_worker_thread started
I/ActivityManager(  763): Killing 1913:com.google.android.email/u0a36 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1120): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/BroadcastQueue(  763): Permission Denial: receiving Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 (has extras) } to com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver requires android.permission.BLUETOOTH due to sender android (uid 1000)
,I/ActivityManager(  763): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=2720 uid=10052 gids={50052, 3003, 1028, 1015}
I/bt_userial_vendor( 2668): userial vendor open: opening /dev/ttyHS99
I/GKI_LINUX( 2668): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 2668): btu_task pending for preload complete event
I/bt_userial_vendor( 2668): device fd = 65 open
,I/bt_hwcfg( 2668): bt vendor lib: set UART baud 4000000
,D/bt_hwcfg( 2668): Chipset BCM4335C0
,D/bt_hwcfg( 2668): Target name = [BCM4335C0]
,I/bt_hwcfg( 2668): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,D/dalvikvm( 2720): GC_CONCURRENT freed 194K, 2% free 16926K/17152K, paused 3ms+0ms, total 21ms
,I/ActivityManager(  763): Killing 2121:com.google.android.music:main/u0a58 (adj 15): empty #17
,F/ActivityManager(  763): Service ServiceRecord{42cd0510 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{42bd89b8 2121:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  763): Service ServiceRecord{42ccb130 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{42bd89b8 2121:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  763): Service ServiceRecord{42cc2ef0 u0 com.google.android.music/.download.artwork.ArtDownloadService} in process ProcessRecord{42bd89b8 2121:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  763): Service ServiceRecord{42cbfa08 u0 com.google.android.music/.download.ArtDownloadQueueService} in process ProcessRecord{42bd89b8 2121:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  763): Service ServiceRecord{42cb6e58 u0 com.google.android.music/.download.cache.ArtCacheService} in process ProcessRecord{42bd89b8 2121:com.google.android.music:main/u0a58} not same as in map: null
,I/bt_hwcfg( 2668): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 2668): Settlement delay -- 100 ms
,I/bt_hwcfg( 2668): bt vendor lib: set UART baud 4000000
,I/bt_hwcfg( 2668): Setting local bd addr to 34:FC:EF:11:B1:66
,I/bt_hwcfg( 2668): vendor lib fwcfg completed
,I/bt-btu  ( 2668): btu_task received preload complete event
I/        ( 2668): BTE_InitTraceLevels -- TRC_HCI
I/        ( 2668): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 2668): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 2668): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 2668): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 2668): BTE_InitTraceLevels -- TRC_A2D
I/        ( 2668): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 2668): BTE_InitTraceLevels -- TRC_BTM
I/        ( 2668): BTE_InitTraceLevels -- TRC_GAP
I/        ( 2668): BTE_InitTraceLevels -- TRC_PAN
I/        ( 2668): BTE_InitTraceLevels -- TRC_SDP
I/        ( 2668): BTE_InitTraceLevels -- TRC_GATT
I/        ( 2668): BTE_InitTraceLevels -- TRC_SMP
I/        ( 2668): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 2668): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 2668): BTM_SecRegister:p_cb_info->p_le_callback == 0x7505bf8d 
,E/bt-btm  ( 2668): BTM_SecRegister: btm_cb.api.p_le_callback = 0x7505bf8d 
,E/bt-btif ( 2668): Calling BTA_HhEnable
E/bt-btif ( 2668): btif_storage_get_adapter_property service_mask:0x140040
,I/BluetoothAdapterProperties( 2668): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 2668): Address is:34:FC:EF:11:B1:66
,I/BluetoothAdapterProperties( 2668): adapterPropertyChangedCallback with type:1 len:7
D/BluetoothAdapterProperties( 2668): Name is: Nexus 5
,I/BluetoothAdapterProperties( 2668): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothManagerService(  763): Bluetooth Adapter name changed to Nexus 5
,D/BluetoothManagerService(  763): Stored Bluetooth name: Nexus 5
D/BluetoothAdapterProperties( 2668): Scan Mode:20
,I/BluetoothAdapterProperties( 2668): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 2668): Discoverable Timeout:120
,I/BluetoothAdapterProperties( 2668): adapterPropertyChangedCallback with type:8 len:36
,D/BluetoothAdapterProperties( 2668): Adding bonded device:F4:F1:E1:5C:3B:E2
,D/BluetoothAdapterProperties( 2668): Adding bonded device:F8:95:C7:87:85:54
,D/BluetoothAdapterProperties( 2668): Adding bonded device:E0:DB:10:1F:C9:5E
,D/BluetoothAdapterProperties( 2668): Adding bonded device:08:EC:A9:50:76:27
,D/BluetoothAdapterProperties( 2668): Adding bonded device:F8:95:C7:87:3C:51
,D/BluetoothAdapterProperties( 2668): Adding bonded device:58:2A:F7:ED:96:BE
,I/BluetoothAdapterProperties( 2668): adapterPropertyChangedCallback with type:3 len:48
,E/BluetoothRemoteDevices( 2668): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,E/BluetoothRemoteDevices( 2668): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
,E/BluetoothRemoteDevices( 2668): devicePropertyChangedCallback: bdDevice: E0:DB:10:1F:C9:5E, value is empty for type: 10
,E/BluetoothRemoteDevices( 2668): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
,E/BluetoothRemoteDevices( 2668): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
,E/BluetoothRemoteDevices( 2668): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,I/bt_hwcfg( 2668): SCO PCM configure {0, 4, 0, 0, 0}
,I/bte_conf( 2668): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 2668): [1] primary_record=1 vendor_id=0x000F vendor_id_source=0x0001 product_id=0x1200 version=0x1436
I/bte_conf( 2668): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 2668): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,D/BluetoothAdapterState( 2668): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothAdapterProperties( 2668): ScanMode =  20
D/BluetoothAdapterProperties( 2668): State =  11
D/BluetoothAdapterProperties( 2668): Setting state to 12
I/BluetoothAdapterState( 2668): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterService( 2668): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  763): Message: 60
,D/BluetoothManagerService(  763): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  763): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothHeadset(  763): onBluetoothStateChange: up=true
D/BluetoothA2dp(  763): onBluetoothStateChange: up=true
,D/BluetoothPan(  763): onBluetoothStateChange(on) call bindService
,I/BluetoothAdapterState( 2668): Entering On State
,D/BluetoothAdapterService(1113380656)( 2668): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2668): getBondedDevices: length=6
,D/BluetoothHeadset( 1008): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1008): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1008): onBluetoothStateChange: up=true
W/ContextImpl(  763): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:192 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:484 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1129 
,D/BluetoothManagerService(  763): Bluetooth State Change Intent: 11 -> 12
,E/bt_h4   ( 2668): vendor lib postload completed
,D/BluetoothAdapterService(1113380656)( 2668): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2668): getBondedDevices: length=6
,D/Tethering(  763): sendTetherStateChangedBroadcast 1, 0, 0
,D/BluetoothPanServiceJni( 2668): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
,I/BluetoothAdapterProperties( 2668): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothAdapterService(1113380656)( 2668): Get Bonded Devices being called
,D/dalvikvm( 2668): GC_CONCURRENT freed 254K, 2% free 16831K/17116K, paused 2ms+2ms, total 19ms
,I/wpa_supplicant( 2681): rfkill: Cannot open RFKILL control device
,D/dalvikvm(  763): GC_EXPLICIT freed 22941K, 54% free 26476K/56384K, paused 3ms+6ms, total 155ms
,D/BluetoothMapService( 2668): onReceive
,D/BluetoothMapService( 2668): STATE_ON
,D/BluetoothAdapterProperties( 2668): Scan Mode:21
D/BluetoothManagerService(  763): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  763): Message: 40
D/BluetoothManagerService(  763): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
I/BluetoothAdapterProperties( 2668): adapterPropertyChangedCallback with type:9 len:4
,D/BluetoothAdapterProperties( 2668): Discoverable Timeout:120
,D/BluetoothMapService( 2668): Map Service startRfcommSocketListener
,D/BluetoothMapService( 2668): Map Service initSocket
,D/BluetoothManagerService(  763): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/WifiConfigStore(  763): Loading config and enabling all networks
,W/ContextImpl( 2685): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/BluetoothManagerService(  763): Message: 20
D/BluetoothManagerService(  763): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42d08568:true
W/BluetoothAdapter( 2668): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 2668): SOCK FLAG = 1 ***********************
D/BluetoothMapService( 2668): Accepting socket connection...
D/BluetoothManagerService(  763): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 2668): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 2668): SOCK FLAG = 1 ***********************
D/LocalBluetoothProfileManager( 2685): Adding local A2DP profile
D/BluetoothManagerService(  763): Message: 30
,W/Settings( 1950): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LocalBluetoothProfileManager( 2685): Adding local HEADSET profile
,D/BluetoothManagerService(  763): Message: 30
,D/BluetoothManagerService(  763): Message: 30
W/ContextImpl( 2685): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
W/ContextImpl( 2685): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
,W/ContextImpl( 2685): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
D/BluetoothAdapterProperties( 2668): getBondedDevices: length=6
,D/BluetoothManagerService(  763): Message: 30
,D/CommandListener(  180): Setting iface cfg
D/LocalBluetoothProfileManager( 2685): Adding local MAP profile
,D/BluetoothMap( 2685): Create BluetoothMap proxy object
,D/BluetoothManagerService(  763): Message: 30
W/ContextImpl( 2685): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
,W/ContextImpl( 2685): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1376 
,D/BluetoothManagerService(  763): Message: 30
,D/LocalBluetoothProfileManager( 2685): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 2685): finishStartingService: stopping service
,D/CommandListener(  180): Trying to bring up p2p0
W/ContextImpl( 2685): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/WifiMonitor(  763): startMonitoring(p2p0) with mConnected = true
D/BluetoothAdapterService(1113380656)( 2668): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2668): getBondedDevices: length=6
,D/dalvikvm( 2685): GC_CONCURRENT freed 307K, 3% free 16888K/17236K, paused 1ms+2ms, total 13ms
,D/BluetoothA2dp( 2685): Proxy object connected
,D/A2dpProfile( 2685): Bluetooth service connected
,D/BluetoothHeadset( 2685): Proxy object connected
,D/HeadsetProfile( 2685): Bluetooth service connected
,D/BluetoothInputDevice( 2685): Proxy object connected
,D/HidProfile( 2685): Bluetooth service connected
D/AuthorizationBluetoothService( 1120): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1120): Proximity feature is not enabled.
,D/BluetoothPan( 2685): BluetoothPAN Proxy object connected
D/PanProfile( 2685): Bluetooth service connected
D/BluetoothMap( 2685): Proxy object connected
D/MapProfile( 2685): Bluetooth service connected
,D/BluetoothMap( 2685): getConnectedDevices()
D/BluetoothPbap( 2685): Proxy object connected
,D/PbapServerProfile( 2685): Bluetooth service connected
W/BroadcastQueue(  763): Permission Denial: receiving Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 (has extras) } to com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver requires android.permission.BLUETOOTH due to sender android (uid 1000)
,D/BluetoothManagerService(  763): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2668): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 2668): SOCK FLAG = 0 ***********************
,I/BtOppRfcommListener( 2668): Accept thread started.
,I/wpa_supplicant( 2681): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant( 2681): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 2681): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 2681): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  763): scanCount==0 - aborting
,D/WifiStateMachine(  763): VerifyingLinkState enter
,D/WifiStateMachine(  763): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  763): CaptivePortalCheckState enter
D/ConnectivityService(  763): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  763): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  763): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  763): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  763): Unexpected mtu value: android.net.wifi.WifiStateTracker@42a412b0
,D/Nat464Xlat(  763): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  763): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  763):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  763): requiresClat: netType=1, hasIPv4Address=true
,I/jxcore-log( 2616): Test app app.js loaded
I/jxcore-log( 2616): 
,I/Choreographer( 2616): Skipped 382 frames!  The application may be doing too much work on its main thread.
,I/chromium( 2616): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Tethering(  763): MasterInitialState.processMessage what=3
,W/        (  763): Unable to set rtc to 1449681171: Invalid argument
,D/CaptivePortalTracker(  763): NoActiveNetworkState{ when=-4ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/        (  763): Setting time of day to sec=1449681171
,I/SystemUpdateService( 1290): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1290): onCreate
,D/SystemUpdateService( 1290): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1290): active receiver: enabled
,I/SystemUpdateService( 1290): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1290): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1290): now status is 0 (complete)
I/SystemUpdateService( 1290): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1290): file has been verified
,I/SystemUpdateService( 1290): OTA package size = 2571501
,I/SystemUpdateService( 1290): showing system update notification
,D/GpsLocationProvider(  763): NTP server returned: 1449681168407 (Wed Dec 09 18:12:48 CET 2015) reference: 86234 certainty: 9 system time offset: -3102
,I/dalvikvm( 1290): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm( 1290): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/dalvikvm( 1290): VFY: replacing opcode 0x6e at 0x003d
,I/iu.SyncManager( 1290): SYNC; picasa accounts
E/ActivityThread( 1290): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  763): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 21616, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  763): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 89357, reason: UserStart
,D/NetworkLogImpl( 1290): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1290): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/SystemUpdateService( 1290): onDestroy
,I/iu.UploadsManager( 1290): num queued entries: 0
,I/iu.UploadsManager( 1290): num updated entries: 0
,I/iu.SyncManager( 1290): NEXT; no task
,E/Auth.Api.Credentials( 1290): [CredentialSyncAdapter] Unknown sync event.
I/ActivityManager(  763): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=2878 uid=10031 gids={50031, 3003, 1028, 1015}
,D/dalvikvm( 1120): GC_EXPLICIT freed 293K, 4% free 17902K/18484K, paused 1ms+2ms, total 19ms
,D/dalvikvm( 1178): GC_CONCURRENT freed 882K, 6% free 17839K/18924K, paused 2ms+2ms, total 14ms
,I/Babel   ( 1950): connection state changed from UNKNOWN to CONNECTED
,I/GCM     ( 1120): GCM config loaded
,D/dalvikvm( 2878): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,W/dalvikvm( 2878): VFY: unable to resolve instance field 68
D/dalvikvm( 2878): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 2878): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2878): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 2878): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 2878): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/dalvikvm( 2878): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,W/dalvikvm( 2878): VFY: unable to resolve instance field 68
,D/dalvikvm( 2878): VFY: replacing opcode 0x54 at 0x0011
,D/dalvikvm( 2878): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2878): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 2878): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2878): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 2878): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 2878): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,D/dalvikvm( 2286): GC_CONCURRENT freed 320K, 2% free 17492K/17844K, paused 5ms+2ms, total 20ms
,I/ActivityManager(  763): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=2913 uid=10033 gids={50033, 1028}
,D/dalvikvm( 1178): GC_CONCURRENT freed 378K, 6% free 17886K/18924K, paused 2ms+1ms, total 18ms
,V/AlarmClock( 2913): AlarmInitReceiver android.intent.action.TIME_SET
,D/dalvikvm( 1290): GC_CONCURRENT freed 761K, 5% free 19168K/19968K, paused 7ms+2ms, total 39ms
,I/AlarmClock( 2913): Displaying next alarm time: ''
,V/AlarmClock( 2913): AlarmInitReceiver finished
,I/dalvikvm(  987): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm(  987): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm(  987): VFY: replacing opcode 0x6e at 0x003d
,I/ActivityManager(  763): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=2931 uid=10068 gids={50068}
,D/dalvikvm( 2931): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x425c6a80, skipping init
,D/TimeService( 2931): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449681171968
D/        ( 2931): TimeServiceNative: User Time to be set is 1449681171969
D/QC-time-services( 2931): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 2931): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 2931): Lib:time_genoff_operation: pargs->ts_val = 1449681171969
D/QC-time-services( 2931): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  200): Daemon: Connection accepted:time_genoff
D/QC-time-services(  200): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449681171969
D/QC-time-services(  200): Daemon:genoff_opr: Base = 2, val = 1449681171969, operation = 0
D/QC-time-services(  200): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS0/29/71 11:18:3
D/QC-time-services(  200): Daemon:Value read from RTC seconds = 33995883000
D/QC-time-services(  200): Daemon:new time 1449681171969 
D/QC-time-services(  200): Daemon: delta 1415685288969 genoff 1415685288969 
D/QC-time-services(  200): Daemon:genoff_persistent_update: Writing genoff = 1415685288969 to memory
D/QC-time-services(  200): Daemon:Opening File: /data/system/time/ats_2
,D/QC-time-services(  200): Daemon:time_persistent_memory_opr:Genoff write operation 
,V/GLSActivity( 1120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/QC-time-services(  200): Updating the TOD offset
D/QC-time-services(  200): Daemon:genoff_persistent_update: Writing genoff = 1415685288969 to memory
D/QC-time-services(  200): Daemon:Opening File: /data/system/time/ats_1
,D/QC-time-services(  200): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  200): Daemon:Update to modem bit set
D/QC-time-services(  200): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  200): Daemon: Base = 2, Value being sent to MODEM = 1133716371969
E/QC-time-services( 2931): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  200): Daemon: Time-services: Waiting to acceptconnection
,D/QC-time-services(  200): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/CheckinService( 1290): Checkin interval check for package: unspecified last checkin: 1449671257442 min interval config: 0 actual interval: 9914550
,D/dalvikvm( 2286): Trying to load lib /data/app-lib/com.google.android.apps.plus-2/libcronet.so 0x425ca670
,D/dalvikvm( 2286): Added shared lib /data/app-lib/com.google.android.apps.plus-2/libcronet.so 0x425ca670
,D/dalvikvm( 2286): GC_CONCURRENT freed 253K, 2% free 17663K/17948K, paused 3ms+1ms, total 17ms
,I/ActivityManager(  763): Killing 2163:com.android.providers.calendar/u0a1 (adj 15): empty #17
,I/ActivityManager(  763): Killing 1753:com.google.android.gm/u0a41 (adj 15): empty #18
,D/dalvikvm(  987): GC_CONCURRENT freed 424K, 3% free 18704K/19220K, paused 2ms+3ms, total 20ms
,D/dalvikvm( 2286): GC_CONCURRENT freed 215K, 2% free 17856K/18104K, paused 3ms+2ms, total 19ms
,D/dalvikvm( 2286): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 2286): VFY: unable to resolve instance field 58
,D/dalvikvm( 2286): VFY: replacing opcode 0x54 at 0x000d
D/dalvikvm( 2286): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2286): DexOpt: unable to optimize instance field ref 0x003a at 0x12 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 2286): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 2286): DexOpt: unable to optimize instance field ref 0x003a at 0x17 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/dalvikvm( 2286): GC_CONCURRENT freed 345K, 3% free 18023K/18400K, paused 2ms+2ms, total 18ms
,D/ConnectivityService(  763): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/dalvikvm( 2286): DexOpt: couldn't find field Landroid/app/Notification;.color
,W/dalvikvm( 2286): VFY: unable to resolve instance field 2708
,D/dalvikvm( 2286): VFY: replacing opcode 0x59 at 0x008b
,D/dalvikvm( 2286): DexOpt: couldn't find field Landroid/app/Notification;.color
,W/dalvikvm( 2286): VFY: unable to resolve instance field 2708
,D/dalvikvm( 2286): VFY: replacing opcode 0x59 at 0x00c7
,I/ActivityManager(  763): Killing 2446:com.android.defcontainer/u0a4 (adj 15): empty #17
,D/dalvikvm(  763): GC_EXPLICIT freed 1464K, 53% free 26508K/56384K, paused 4ms+6ms, total 81ms
,D/dalvikvm( 1638): GC_CONCURRENT freed 395K, 3% free 17426K/17856K, paused 3ms+2ms, total 15ms
,D/Finsky  ( 1638): [1] 5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  763): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=2988 uid=10001 gids={50001, 3003, 1028, 1015}
,D/dalvikvm(  184): GC_EXPLICIT freed 42K, 1% free 16698K/16772K, paused 4ms+7ms, total 60ms
,D/dalvikvm(  184): GC_EXPLICIT freed <1K, 1% free 16698K/16772K, paused 1ms+1ms, total 12ms
,D/dalvikvm(  184): GC_EXPLICIT freed <1K, 1% free 16698K/16772K, paused 0ms+2ms, total 12ms
,I/CalendarProvider2( 2988): Created com.android.providers.calendar.CalendarAlarmManager@425dd100(com.android.providers.calendar.CalendarProvider2@425d4dd0)
,D/dalvikvm( 1120): GC_CONCURRENT freed 381K, 3% free 18019K/18496K, paused 3ms+3ms, total 20ms
,I/VacuumService(  987): Vacuum at: now=1449681176800 tag=VacuumService
,D/dalvikvm( 1120): GC_CONCURRENT freed 541K, 4% free 17887K/18536K, paused 3ms+1ms, total 23ms
,I/CalendarProvider2( 2988): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 2988): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlertReceiver( 1685): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.google.android.calendar/com.android.calendar.alerts.AlertReceiver }
,D/AlertService( 1685): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/CaptivePortalTracker(  763): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  763): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  763): Checking http://216.58.209.46/generate_204
,W/ActivityThread(  763): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/CaptivePortalTracker(  763): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  763): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  763): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  763): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  763): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/AlertService( 1685): Beginning updateAlertNotification
,D/AlertService( 1685): No fired or scheduled alerts
,D/AlertService( 1685): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 1685): No events found starting within 1 week.
I/ActivityManager(  763): Killing 2195:android.process.acore/u0a3 (adj 15): empty #17
,I/PowerManagerService(  763): Going to sleep due to screen timeout...
,I/Adreno-EGL(  763): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/SurfaceFlinger(  183): Screen released, type=0 flinger=0xb85b0450
,D/qdhwcomposer(  183): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  183): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  763): Excessive delay in blankDisplay() while turning screen off: 294ms
,V/KeyguardServiceDelegate(  763): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@42d14f20)
,V/KeyguardServiceDelegate(  763): **** SHOWN CALLED ****
,I/WindowManager(  763): No lock screen! windowToken=null
,D/NfcService( 1034): NFC-C OFF
,D/SyncManager(  763): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 21614, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  763): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 149456, reason: UserStart
E/ActivityThread( 1290): Failed to find provider info for com.android.contacts.metadata
,D/dalvikvm( 1120): GC_CONCURRENT freed 393K, 4% free 17964K/18536K, paused 2ms+2ms, total 27ms
,I/PhenotypeConfigurator(  987): Scheduling Phenotype for one-off execution 3969 seconds from now (1449681257099)
,D/GetConfigurationSnapshotOperation(  987): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/dalvikvm(  987): GC_CONCURRENT freed 573K, 4% free 18761K/19428K, paused 4ms+3ms, total 29ms
,I/PhenotypeFlagCommitter(  987): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm(  987): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  987): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  987): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm(  987): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm(  987): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm(  987): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory(  987): Using platform SSLCertificateSocketFactory
,D/dalvikvm(  987): GC_CONCURRENT freed 521K, 4% free 18927K/19544K, paused 3ms+5ms, total 36ms
,D/dalvikvm(  987): GC_CONCURRENT freed 621K, 4% free 19053K/19768K, paused 4ms+5ms, total 36ms
,D/dalvikvm(  987): GC_CONCURRENT freed 604K, 4% free 19176K/19876K, paused 2ms+3ms, total 19ms
,D/dalvikvm(  987): GC_CONCURRENT freed 754K, 5% free 19178K/20028K, paused 3ms+3ms, total 21ms
,V/GLSActivity( 1120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1120): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm(  987): GC_FOR_ALLOC freed 767K, 6% free 19040K/20112K, paused 64ms, total 65ms
,I/rmt_storage(  179): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb8a53160
I/rmt_storage(  179): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  179): wakelock acquired: 1, error no: 2
,I/rmt_storage(  179): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1197133280)
,I/rmt_storage(  179): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  179): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  179): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1197133280) wakelock released: 1, error no: 0
I/rmt_storage(  179): 
,I/rmt_storage(  179): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb8a53160
,I/jxcore-log( 2616): Toggling radios to false
I/jxcore-log( 2616): 
,D/BluetoothManagerService(  763): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  763): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@449d4300 mBinding = false
,D/BluetoothManagerService(  763): Message: 2
D/BluetoothManagerService(  763): Sending off request.
D/BluetoothAdapterState( 2668): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2668): Setting state to 13
I/BluetoothAdapterState( 2668): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 2668): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterProperties( 2668): onBluetoothDisable()
I/BluetoothAdapterState( 2668): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,I/BluetoothAdapterProperties( 2668): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 2668): Scan Mode:20
,D/BluetoothAdapterState( 2668): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 2668): bta_jv_rfcomm_stop_server
,E/bt-btif ( 2668): bta_jv_rfcomm_stop_server
E/BtOppRfcommListener( 2668): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/BluetoothManagerService(  763): Message: 60
E/bt-btif ( 2668): bta_jv_rfcomm_stop_server
,W/bt-btif ( 2668): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
W/bt-l2cap( 2668): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2668): L2CAP - PSM: 0x0017 not found for deregistration
D/btif_config_util( 2668): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
D/BluetoothManagerService(  763): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,D/BluetoothManagerService(  763): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 2668): onReceive
D/BluetoothMapService( 2668): STATE_TURNING_OFF
,D/BluetoothMapService( 2668): MAP Service closeService in
,I/BtOppRfcommListener( 2668): stopping Accept Thread
,I/BtOppRfcommListener( 2668): BluetoothSocket listen thread finished
,D/CachedBluetoothDevice( 2685):  Clearing all connection state for dev:Thali Test (Galaxy A3)
,D/CachedBluetoothDevice( 2685):  Clearing all connection state for dev:XT1039
,D/WifiService(  763): setWifiEnabled: false pid=2616, uid=10108
D/CachedBluetoothDevice( 2685):  Clearing all connection state for dev:G3s-1
D/CachedBluetoothDevice( 2685):  Clearing all connection state for dev:Note3-1
D/CachedBluetoothDevice( 2685):  Clearing all connection state for dev:G4-1
,D/CachedBluetoothDevice( 2685):  Clearing all connection state for dev:ALE-L21
W/ContextImpl( 2685): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/jxcore-log( 2616): Radios toggled
I/jxcore-log( 2616): 
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/ConnectivityService(  763): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  763): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  763): Attempting to switch to mobile
,D/ConnectivityService(  763): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  763): android_net_utils_resetConnections in env=0x753dcdc8 clazz=0x5e300001 iface=wlan0 mask=0x3
D/ConnectivityService(  763): resetConnections(wlan0, 3)
,D/DockEventReceiver( 2685): finishStartingService: stopping service
D/BluetoothPbap( 2685): Proxy object disconnected
,D/PbapServerProfile( 2685): Bluetooth service disconnected
,D/AuthorizationBluetoothService( 1120): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/NativeCrypto( 1120): Read error: ssl=0x78c5ed08: I/O error during system call, Connection timed out
,V/NativeCrypto( 1120): SSL shutdown failed: ssl=0x78c5ed08: I/O error during system call, Broken pipe
W/BroadcastQueue(  763): Permission Denial: receiving Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 (has extras) } to com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver requires android.permission.BLUETOOTH due to sender android (uid 1000)
,W/bt-btif ( 2668): ag scb idx 1 not allocated
E/bt-btif ( 2668): BTA AG is already disabled, ignoring ...
,D/bt_hwcfg( 2668): hw_epilog_process
W/bt-l2cap( 2668): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2668): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2668): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2668): L2CAP - PSM: 0x0017 not found for deregistration
,W/bt-l2cap( 2668): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 2668): L2CAP - PSM: 0x0017 not found for deregistration
,E/WifiStateMachine(  763): scanCount==0 - aborting
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/bt_hwcfg( 2668): hw_epilog_cback Opcode:0x0C03 Status: 0
,I/bt_hci_bdroid( 2668): bt_hc_worker_thread exiting
W/bt_userial( 2668): select_read return size <=0:-1, exiting userial_read_thread
,I/bt_userial_vendor( 2668): device fd = 65 close
,D/BTSNOOP-DISP( 2668): btsnoop_close
,I/GKI_LINUX( 2668): gki_task_entry: gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2668): GKI_exit_task: GKI_exit_task 0 done
,I/GKI_LINUX( 2668): GKI_destroy_task: GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 2668): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 2668): Received stop request...Stopping profile...
,D/BluetoothHeadset( 1008): Proxy object disconnected
D/BluetoothHeadset(  763): Proxy object disconnected
,D/BluetoothAdapterService( 2668): Profile still running: com.android.bluetooth.hdp.HealthService
D/BluetoothHeadset( 1008): Proxy object disconnected
,D/BluetoothHeadset( 1008): Proxy object disconnected
W/BluetoothHeadsetServiceJni( 2668): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2668): Cleaning up Bluetooth Handsfree callback object
,D/BluetoothHeadset( 2685): Proxy object disconnected
D/HeadsetProfile( 2685): Bluetooth service disconnected
D/A2dpService( 2668): Received stop request...Stopping profile...
,D/A2dpStateMachine( 2668): Exit Disconnected: -1
D/BluetoothA2dp( 2685): Proxy object disconnected
,D/BluetoothA2dp(  763): Proxy object disconnected
,D/A2dpProfile( 2685): Bluetooth service disconnected
,D/HidService( 2668): Received stop request...Stopping profile...
D/BluetoothInputDevice( 2685): Proxy object disconnected
,D/BluetoothAdapterService( 2668): Profile still running: com.android.bluetooth.hdp.HealthService
D/HidProfile( 2685): Bluetooth service disconnected
,D/BluetoothAdapterState( 2668): Stopping profile services that were post enabled
I/GKI_LINUX( 2668): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2668): GKI_exit_task: GKI_exit_task 2 done
,I/GKI_LINUX( 2668): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
,D/HealthService( 2668): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2668): Profile still running: com.android.bluetooth.hdp.HealthService
,D/PanService( 2668): Received stop request...Stopping profile...
D/BluetoothPan(  763): BluetoothPAN Proxy object disconnected
D/BluetoothTethering(  763): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering(  763): attempted to stop reverse tether with nothing tethered
D/BtGatt.DebugUtils( 2668): handleDebugAction() action=null
D/BtGatt.GattService( 2668): Received stop request...Stopping profile...
D/BtGatt.GattService( 2668): stop()
D/BluetoothPan( 2685): BluetoothPAN Proxy object disconnected
,D/PanProfile( 2685): Bluetooth service disconnected
W/BluetoothHidServiceJni( 2668): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2668): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2668): Cleaning up Bluetooth GID callback object
D/BluetoothMapService( 2668): Received stop request...Stopping profile...
,D/BluetoothMapService( 2668): stop()
D/Nat464Xlat(  763): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  763): handleInetConditionChange: no active default network - ignore
D/BluetoothMapService( 2668): MAP Service closeService in
D/BluetoothAdapterService( 2668): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 2668): Cleaning up Bluetooth Health Interface...
D/BluetoothMap( 2685): Proxy object disconnected
D/MapProfile( 2685): Bluetooth service disconnected
W/BluetoothHealthServiceJni( 2668): Cleaning up Bluetooth Health object
D/BluetoothAdapterService( 2668): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 2668): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2668): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService( 2668): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/BluetoothMapService( 2668): cleanup()
D/BluetoothAdapterState( 2668): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2668): Setting state to 10
I/BluetoothAdapterState( 2668): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 2668): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothMapService( 2668): MAP Service closeService in
D/BluetoothManagerService(  763): Message: 60
D/BluetoothManagerService(  763): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  763): Broadcasting onBluetoothStateChange(false) to 12 receivers.
D/BluetoothHeadset(  763): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 2668): Entering OffState
D/BluetoothA2dp(  763): onBluetoothStateChange: up=false
D/BluetoothPbap( 2685): onBluetoothStateChange: up=false
D/BluetoothMap( 2685): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 2685): onBluetoothStateChange: up=false
D/BluetoothHeadset( 2685): onBluetoothStateChange: up=false
D/BluetoothA2dp( 2685): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1008): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1008): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1008): onBluetoothStateChange: up=false
D/BluetoothManagerService(  763): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  763): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/BluetoothManagerService(  763): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@449d4300 mBinding = false
D/BluetoothManagerService(  763): Sending unbind request.
D/BluetoothAdapterService( 2668): Cleaning up adapter native....
D/BluetoothManagerService(  763): Bluetooth State Change Intent: 13 -> 10
I/GKI_LINUX( 2668): gki_task_entry: gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 2668): GKI_exit_task: GKI_exit_task 1 done
I/GKI_LINUX( 2668): GKI_destroy_task: GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 2668): cleanupNative: return from cleanup
D/BluetoothAdapterService( 2668): Done cleaning up adapter native....
D/BluetoothAdapter(  866): 1113847568: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapterService(1113380656)( 2668): ****onDestroy()********
D/BtGatt.GattService( 2668): cleanup()
W/bt-btif ( 2668): GATTC Module not enabled/already disabled
W/bt-btif ( 2668): GATTS Module not enabled/already disabled
D/BluetoothAdapter(  987): 1114834176: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter(  987): 1114834176: getState() :  mService = null. Returning STATE_OFF
,D/DockEventReceiver( 2685): finishStartingService: stopping service
,W/ContextImpl( 2685): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothAdapter( 2685): 1113432720: getState() :  mService = null. Returning STATE_OFF
,D/AuthorizationBluetoothService( 1120): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  763): Killing 2473:com.google.android.partnersetup/u0a11 (adj 15): empty #17
,W/BroadcastQueue(  763): Permission Denial: receiving Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 (has extras) } to com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver requires android.permission.BLUETOOTH due to sender android (uid 1000)
I/wpa_supplicant( 2681): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 2681): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/Tethering(  763): InitialState.processMessage what=4
,I/wpa_supplicant( 2681): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering(  763): sendTetherStateChangedBroadcast 0, 0, 0
,W/Settings( 1950): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BluetoothAdapter( 2685): 1113432720: getState() :  mService = null. Returning STATE_OFF
,W/Settings(  987): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ConnectivityService(  763): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  763): handleInetConditionChange: no active default network - ignore
,D/Tethering(  763): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  763): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  763): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SystemUpdateService( 1290): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1290): onCreate
,D/SystemUpdateService( 1290): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1290): active receiver: enabled
,I/iu.Environment( 1290): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/SystemUpdateService( 1290): Already downloaded, skipping offpeak checks.
,I/iu.UploadsManager( 1290): num queued entries: 0
,I/Babel   ( 1950): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1290): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1290): now status is 0 (complete)
I/SystemUpdateService( 1290): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1290): file has been verified
,I/iu.UploadsManager( 1290): num updated entries: 0
,I/SystemUpdateService( 1290): OTA package size = 2571501
,I/iu.SyncManager( 1290): NEXT; no task
,I/SystemUpdateService( 1290): showing system update notification
,D/SystemUpdateService( 1290): onDestroy
,D/ConnectivityService(  763): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  763): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  763): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  763): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  763): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  763): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  763): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  763): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  763): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  763): Done.
,D/ConnectivityService(  763): Setting timer for 720seconds
,D/ConnectivityService(  763): handleInetConditionChange: no active default network - ignore
,D/dalvikvm( 1120): GC_CONCURRENT freed 413K, 4% free 17940K/18536K, paused 1ms+1ms, total 19ms
,D/ConnectivityService(  763): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  763): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  763): Done.
,D/ConnectivityService(  763): Setting timer for 720seconds
,I/ProcessStatsService(  763): Prepared write state in 35ms
,I/ProcessStatsService(  763): Prepared write state in 10ms
,I/dalvikvm(  763): Jit: resizing JitTable from 8192 to 16384
,I/ProcessStatsService(  763): Pruning old procstats: /data/system/procstats/state-2015-12-09-03-33-43.bin
,TIME-OUT KILL (timeout was 1800000ms)
```
