#### Test 52445159d291820_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
D/dalvikvm( 2499): GC_CONCURRENT freed 397K, 3% free 17844K/18272K, paused 2ms+1ms, total 13ms
I/dalvikvm( 1295): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1295): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1295): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1295): VFY: unable to resolve new-instance 2320 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
D/dalvikvm( 1295): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1295): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1295): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
D/dalvikvm( 1295): DexOpt: unable to opt direct call 0x3207 at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
D/dalvikvm( 2499): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2499): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2499): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2499): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2499): VFY: unable to resolve instance field 46
D/dalvikvm( 2499): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2499): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2499): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2499): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2499): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 2499): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
D/dalvikvm( 2499): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42656320
D/dalvikvm( 2499): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42656320
D/dalvikvm( 2499): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42656320, skipping init
D/dalvikvm( 2499): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42656320
D/dalvikvm( 2499): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42656320
V/JNIHelp ( 2499): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
D/dalvikvm( 2499): GC_CONCURRENT freed 412K, 3% free 17940K/18384K, paused 5ms+2ms, total 30ms
D/dalvikvm( 2499): WAIT_FOR_CONCURRENT_GC blocked 10ms
D/dalvikvm( 2499): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42656320
D/dalvikvm( 2499): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x42656320
D/dalvikvm( 2499): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42656320
D/dalvikvm( 2499): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42656320
D/ChimeraCfgMgr( 1295): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1295): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1295): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/AsyncTaskServiceImpl( 1295): Submit a task: h
,D/ChimeraCfgMgr( 1295): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 1295): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/h       ( 1295): Processing package: com.test.thalitest
D/GassUtils( 1295): Found app info for package com.test.thalitest:18. Hash: 01e4d8ac61718f1dcdc950940ea39ae21caf015e512d4d8080feb7f016346367
D/h       ( 1295): Found info for package com.test.thalitest in db.
--------- beginning of /dev/log/system
I/ActivityManager(  796): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2547 uid=10065 gids={50065, 3003, 1028, 1015}
D/dalvikvm( 1295): GC_CONCURRENT freed 376K, 3% free 18488K/18924K, paused 2ms+3ms, total 24ms
I/PeopleContactsSync( 1295): CP2 sync disabled
I/dalvikvm( 1295): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/BaseAppContext( 1295): Using Auth Proxy for data requests.
W/BaseAppContext( 1295): Using Auth Proxy for data requests.
W/dalvikvm( 1295): VFY: unable to resolve virtual method 34: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1295): VFY: replacing opcode 0x6e at 0x000e
D/dalvikvm( 2499): GC_FOR_ALLOC freed 40K, 3% free 18000K/18424K, paused 20ms, total 21ms
W/BaseAppContext( 1295): Using Auth Proxy for data requests.
W/BaseAppContext( 1295): Using Auth Proxy for data requests.
W/BaseAppContext( 1295): Using Auth Proxy for data requests.
W/BaseAppContext( 1295): Using Auth Proxy for data requests.
I/ProviderInstaller( 2499): Installed default security provider GmsCore_OpenSSL
W/Quickoffice( 2547): Cleanup of storage: done
D/com.google.android.apps.docs.quickoffice.X( 2547): Loading recent documents list
D/Quickoffice( 2547): The number of lines present in  /proc/mount 21
D/Quickoffice( 2547): Parsing the storagedefinition.xml.
D/Quickoffice( 2547): # of Storagedefinitions - 35
D/Quickoffice( 2547): The # of storage definitions available - 35
D/Quickoffice( 2547): Processing mountline rootfs / rootfs ro,relatime 0 0
D/Quickoffice( 2547): Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
D/Quickoffice( 2547): Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
D/Quickoffice( 2547): Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
D/Quickoffice( 2547): Processing mountline proc /proc proc rw,relatime 0 0
D/Quickoffice( 2547): Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
D/Quickoffice( 2547): Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
D/Quickoffice( 2547): Processing mountline debugfs /sys/kernel/debug debugfs rw,relatime 0 0
D/Quickoffice( 2547): Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
D/Quickoffice( 2547): Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
D/Quickoffice( 2547): Processing mountline tmpfs /mnt/asec tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2547): Processing mountline tmpfs /mnt/obb tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2547): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,nosuid,nodev,relatime,data=ordered 0 0
D/Quickoffice( 2547): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2547): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2547): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2547): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
D/Quickoffice( 2547): Processing mountline /dev/fuse /mnt/shell/emulated fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2547): Processing mountline tmpfs /storage/emulated tmpfs rw,seclabel,nosuid,nodev,relatime,mode=751,gid=1028 0 0
D/Quickoffice( 2547): Processing mountline /dev/fuse /storage/emulated/0 fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/dalvikvm( 1295): GC_CONCURRENT freed 279K, 2% free 18701K/19012K, paused 3ms+2ms, total 28ms
D/Quickoffice( 2547): Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2547): Build properties are not configured for this storage definition.
D/dalvikvm( 2547): GC_CONCURRENT freed 172K, 2% free 16913K/17116K, paused 3ms+1ms, total 13ms
D/Quickoffice( 2547): Adding the mount informaiton for listing in file manager MountedDeviceInformation [device=/dev/fuse, mountPath=/storage/emulated/legacy, fileSystemType=fuse, options=rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other, bootPriority1=0, bootPriority2=0, storageInfo=StorageDefinition [id=2010, matchPatterns=[/storage/emulated/legacy, fuse], skipPatterns=[obb], buildPatterns=[], type=INTERNAL, resourceString=2131231627, resourceStringItemized=2131231630, resourceIcon=2130838373, enabled=true], userFriendlyName=null]
D/Quickoffice( 2547): The # of mounts identified -  1
D/com.google.android.apps.docs.quickoffice.X( 2547): Checking validity of 0 items
D/ContentResolverUtil( 2547): There are 0 persisted uri permissions.
D/com.google.android.apps.docs.quickoffice.X( 2547): 0 items were valid
W/ActivityManager(  796): No permission grants found for com.quickoffice.android
D/AndroidRuntime( 2559): 
D/AndroidRuntime( 2559): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2559): CheckJNI is OFF
D/dalvikvm( 2559): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2559): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2559): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2559): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2559): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/ActivityManager(  796): Killing 1938:com.google.android.apps.maps/u0a57 (adj 15): empty #17
W/Quickoffice( 2547): Could not load clipboard.
D/dalvikvm( 2559): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
W/Quickoffice( 2547): Could not store clipboard.
D/ChimeraCfgMgr( 1295): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1295): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 2559): Calling main entry com.android.commands.am.Am
I/ActivityManager(  796): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2559
D/PermissionCache(  185): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (199 us)
I/Icing   ( 1295): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
D/AndroidRuntime( 2559): Shutting down VM
D/dalvikvm( 2559): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 0ms+0ms, total 2ms
I/ActivityManager(  796): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2590 uid=10108 gids={50108, 3003, 3001, 3002, 1028, 1015}
I/SearchController( 1172): #onHotwordDetectorStopped(false)
I/MicrophoneInputStream( 1172): mic_close
D/dalvikvm( 1295): GC_CONCURRENT freed 441K, 3% free 18808K/19280K, paused 1ms+1ms, total 20ms
I/ActivityManager(  796): Killing 1971:com.google.android.youtube/u0a71 (adj 15): empty #17
V/WebViewChromiumFactoryProvider( 2590): Binding Chromium to main looper Looper (main, tid 1) {425fc9f8}
I/LibraryLoader( 2590): Expected native library version number "",actual native library version number ""
I/chromium( 2590): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2590): Initializing chromium process, renderers=0
I/MicroHotwordRecognitionRunner( 1172): Hotword detection finished
I/MicroHotwordRecognitionRunner( 1172): Stopping hotword detection.
F/ActivityManager(  796): Service ServiceRecord{42d37f88 u0 com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService} in process ProcessRecord{42c15340 1971:com.google.android.youtube/u0a71} not same as in map: null
D/dalvikvm(  978): GC_CONCURRENT freed 374K, 3% free 17882K/18376K, paused 1ms+3ms, total 24ms
D/BluetoothManagerService(  796): Message: 20
D/BluetoothManagerService(  796): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4427c5a8:true
D/BluetoothAdapter( 2590): 1113661576: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 2590): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
D/dalvikvm( 1172): GC_CONCURRENT freed 691K, 4% free 18485K/19200K, paused 2ms+1ms, total 21ms
W/chromium( 2590): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/Icing   ( 1295): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
I/dalvikvm( 2590): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2590): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2590): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2590): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2590): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 2590): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 2590): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2590): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2590): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2590): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2590): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 2590): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2590): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2590): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2590): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2590): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2590): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2590): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 2590): CordovaWebView is running on device made by: LGE
,D/OpenGLRenderer( 2590): Enabling debug mode 0
,W/AwContents( 2590): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  796): Displayed com.test.thalitest/.MainActivity: +282ms
,I/ActivityManager(  796): Killing 1700:com.google.android.deskclock/u0a33 (adj 15): empty #17
,D/JsMessageQueue( 2590): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 2590): GC_CONCURRENT freed 230K, 2% free 16877K/17136K, paused 2ms+2ms, total 17ms
,D/dalvikvm( 2590): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42600f68
,D/dalvikvm( 2590): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42600f68
,D/jxcore_app_log( 2590): JniHelper::setJavaVM(0x4159ced0), pthread_self() = 1983834328
,D/JX-Cordova( 2590): jxcore cordova android initializing
,I/dalvikvm( 2590): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
W/dalvikvm( 2590): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 2590): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 2590): GC_CONCURRENT freed 193K, 2% free 17104K/17328K, paused 2ms+1ms, total 10ms
,D/dalvikvm( 2590): GC_CONCURRENT freed 157K, 2% free 17448K/17644K, paused 1ms+1ms, total 10ms
,D/dalvikvm( 2590): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 2590): GC_CONCURRENT freed 156K, 2% free 17794K/17992K, paused 0ms+1ms, total 9ms
,D/dalvikvm( 2590): WAIT_FOR_CONCURRENT_GC blocked 5ms
,D/dalvikvm( 2590): GC_CONCURRENT freed 151K, 2% free 18137K/18336K, paused 2ms+1ms, total 12ms
,D/dalvikvm( 2590): WAIT_FOR_CONCURRENT_GC blocked 5ms
,D/dalvikvm( 2590): GC_CONCURRENT freed 156K, 2% free 18472K/18680K, paused 0ms+1ms, total 11ms
,D/dalvikvm( 2590): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 2590): GC_CONCURRENT freed 171K, 2% free 18871K/19096K, paused 1ms+2ms, total 15ms
,D/dalvikvm( 2590): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/dalvikvm( 2590): GC_FOR_ALLOC freed 209K, 2% free 19359K/19628K, paused 13ms, total 13ms
,D/dalvikvm( 2590): GC_CONCURRENT freed 58K, 1% free 19497K/19680K, paused 2ms+2ms, total 15ms
,D/dalvikvm( 2590): GC_CONCURRENT freed 282K, 2% free 20117K/20464K, paused 1ms+3ms, total 26ms
,D/dalvikvm( 2590): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 2590): GC_CONCURRENT freed 327K, 2% free 20885K/21288K, paused 1ms+3ms, total 30ms
,D/dalvikvm( 2590): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm( 2590): GC_CONCURRENT freed 403K, 3% free 21826K/22312K, paused 1ms+1ms, total 22ms
,D/dalvikvm( 2590): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 2590): GC_CONCURRENT freed 1240K, 6% free 22259K/23568K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 2590): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 2590): GC_FOR_ALLOC freed 1424K, 7% free 22526K/24144K, paused 20ms, total 20ms
,D/dalvikvm( 2590): GC_FOR_ALLOC freed 148K, 7% free 22459K/24144K, paused 18ms, total 18ms
,I/dalvikvm-heap( 2590): Grow heap (frag case) to 22.668MB for 744140-byte allocation
,D/dalvikvm( 2590): GC_FOR_ALLOC freed 5K, 7% free 23180K/24872K, paused 20ms, total 20ms
,D/dalvikvm( 2590): GC_FOR_ALLOC freed 1253K, 9% free 22761K/24872K, paused 19ms, total 20ms
,I/dalvikvm-heap( 2590): Grow heap (frag case) to 23.319MB for 1116206-byte allocation
,D/dalvikvm( 2590): GC_FOR_ALLOC freed 753K, 12% free 23097K/25964K, paused 23ms, total 23ms
,D/dalvikvm( 2590): GC_FOR_ALLOC freed 1235K, 11% free 23177K/25964K, paused 21ms, total 21ms
,I/dalvikvm-heap( 2590): Grow heap (frag case) to 24.256MB for 1674304-byte allocation
,D/dalvikvm( 2590): GC_FOR_ALLOC freed 1090K, 15% free 23722K/27600K, paused 20ms, total 20ms
,D/dalvikvm( 2590): GC_FOR_ALLOC freed 2011K, 14% free 23825K/27600K, paused 23ms, total 23ms
,I/dalvikvm-heap( 2590): Grow heap (frag case) to 25.688MB for 2511452-byte allocation
,D/dalvikvm( 2590): GC_CONCURRENT freed 60K, 13% free 26217K/30056K, paused 4ms+2ms, total 23ms
,D/dalvikvm( 2590): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 2590): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 2590): GC_CONCURRENT freed 4638K, 18% free 24754K/30056K, paused 1ms+6ms, total 41ms
,D/dalvikvm( 2590): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/dalvikvm( 2590): GC_FOR_ALLOC freed 195K, 19% free 24567K/30056K, paused 19ms, total 19ms
,I/dalvikvm-heap( 2590): Grow heap (frag case) to 27.610MB for 3767174-byte allocation
,D/dalvikvm( 2590): GC_FOR_ALLOC freed 2453K, 24% free 25792K/33736K, paused 21ms, total 21ms
,D/dalvikvm( 2590): GC_CONCURRENT freed 160K, 24% free 25796K/33736K, paused 2ms+1ms, total 22ms
,D/dalvikvm( 2590): GC_FOR_ALLOC freed 580K, 24% free 25697K/33736K, paused 20ms, total 20ms
,W/jxcore-log( 2590): Initializing JXcore engine
,W/jxcore-log( 2590): JXcore engine is ready
,D/dalvikvm( 2590): GC_CONCURRENT freed 5372K, 31% free 23310K/33736K, paused 2ms+0ms, total 17ms
,D/dalvikvm( 2590): WAIT_FOR_CONCURRENT_GC blocked 13ms
,W/jxcore-log( 2590): Starting JXcore engine
,W/jxcore-log( 2590): Platform android
W/jxcore-log( 2590): 
,W/jxcore-log( 2590): Process ARCH arm
W/jxcore-log( 2590): 
,I/jxcore-log( 2590): JXcore Cordova bridge is ready!
I/jxcore-log( 2590): 
,W/jxcore-log( 2590): JXcore engine is started
,I/chromium( 2590): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 2590): Toggling radios to true
I/jxcore-log( 2590): 
,D/BluetoothManagerService(  796): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  796): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  796): Message: 1
,D/BluetoothManagerService(  796): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  796): setWifiEnabled: true pid=2590, uid=10108
,I/ActivityManager(  796): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=2643 uid=1002 gids={41002, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008}
,I/jxcore-log( 2590): Radios toggled
I/jxcore-log( 2590): 
,D/SoftapController(  182): Softap fwReload - Ok
D/CommandListener(  182): Setting iface cfg
,D/CommandListener(  182): Trying to bring down wlan0
,D/WifiMonitor(  796): startMonitoring(wlan0) with mConnected = false
,I/ActivityManager(  796): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=2657 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
,I/wpa_supplicant( 2656): Successfully initialized wpa_supplicant
,D/AdapterServiceConfig( 2643): Adding HeadsetService
D/AdapterServiceConfig( 2643): Adding A2dpService
D/AdapterServiceConfig( 2643): Adding HidService
,D/AdapterServiceConfig( 2643): Adding HealthService
D/AdapterServiceConfig( 2643): Adding PanService
D/AdapterServiceConfig( 2643): Adding GattService
,D/AdapterServiceConfig( 2643): Adding BluetoothMapService
,D/BluetoothManagerService(  796): Message: 20
,D/BluetoothManagerService(  796): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44257d68:true
,D/BluetoothAdapterService( 2643): REFCOUNT: CREATED. INSTANCE_COUNT1
,D/BluetoothAdapter( 2657): 1113641368: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  796): Message: 20
D/BluetoothManagerService(  796): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44257030:true
,D/BluetoothManagerService(  796): Message: 30
,D/BluetoothAdapterState( 2643): make
,I/bluedroid( 2643): init
,W/ContextImpl( 2657): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
I/BluetoothAdapterState( 2643): Entering OffState
,D/BluetoothManagerService(  796): Message: 30
,I/bte_conf( 2643): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
D/LocalBluetoothProfileManager( 2657): Adding local MAP profile
,D/BluetoothMap( 2657): Create BluetoothMap proxy object
D/BluetoothManagerService(  796): Message: 30
,I/bluedroid( 2643): get_profile_interface socket
D/BluetoothManagerService(  796): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  796): Message: 40
,D/BluetoothManagerService(  796): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/GKI_LINUX( 2643): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
I/BluetoothAdapterProperties( 2643): adapterPropertyChangedCallback with type:2 len:6
I/bluedroid( 2643): config_hci_snoop_log
D/BluetoothAdapterProperties( 2643): Address is:34:FC:EF:11:B1:66
I/BluetoothAdapterProperties( 2643): adapterPropertyChangedCallback with type:1 len:7
D/BluetoothManagerService(  796): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  796): Broadcasting onBluetoothServiceUp() to 9 receivers.
D/BluetoothManagerService(  796): Bluetooth Adapter name changed to Nexus 5
,D/BluetoothAdapterProperties( 2643): Name is: Nexus 5
,D/BluetoothManagerService(  796): Stored Bluetooth name: Nexus 5
W/ContextImpl( 2657): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
W/ContextImpl( 2657): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1376 
,D/LocalBluetoothProfileManager( 2657): LocalBluetoothProfileManager construction complete
,D/BluetoothAdapterState( 2643): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 2643): Setting state to 11
D/BluetoothManagerService(  796): Message: 30
I/BluetoothAdapterState( 2643): Bluetooth adapter state changed: 10-> 11
I/wpa_supplicant( 2656): rfkill: Cannot open RFKILL control device
,D/BluetoothAdapterService( 2643): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  796): Message: 60
D/BluetoothManagerService(  796): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  796): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 2643): make
,I/BluetoothBondStateMachine( 2643): StableState(): Entering Off State
W/ContextImpl( 2657): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/BluetoothHeadset( 1001): Proxy object connected
,D/HeadsetService( 2643): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 2643): classInitNative: succeeds
,D/HeadsetStateMachine( 2643): make
,D/BluetoothHeadset(  796): Proxy object connected
D/BluetoothHeadset( 1001): Proxy object connected
,D/BluetoothHeadset( 1001): Proxy object connected
,I/BluetoothAdapterState( 2643): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/bluedroid( 2643): get_profile_interface handsfree
,I/ActivityManager(  796): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=2688 uid=10052 gids={50052, 3003, 1028, 1015}
,D/BluetoothA2dp(  796): Proxy object connected
D/A2dpService( 2643): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 2643): classInitNative: succeeds
V/Avrcp   ( 2643): make
,I/bluedroid( 2643): get_profile_interface avrcp
I/ActivityManager(  796): Killing 1815:com.google.android.email/u0a36 (adj 15): empty #17
,I/BluetoothA2dpServiceJni( 2643): classInitNative: succeeds
,D/A2dpStateMachine( 2643): make
,I/bluedroid( 2643): get_profile_interface a2dp
,I/GKI_LINUX( 2643): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
D/A2dpStateMachine( 2643): Enter Disconnected: -2
I/BluetoothHidServiceJni( 2643): classInitNative: succeeds
D/HidService( 2643): Received start request. Starting profile...
I/bluedroid( 2643): get_profile_interface hidhost
I/BluetoothHealthServiceJni( 2643): classInitNative: succeeds
D/HealthService( 2643): Received start request. Starting profile...
I/bluedroid( 2643): get_profile_interface health
I/BluetoothPanServiceJni( 2643): classInitNative(L105): succeeds
D/BluetoothPan(  796): BluetoothPAN Proxy object connected
D/PanService( 2643): Received start request. Starting profile...
D/BluetoothPanServiceJni( 2643): initializeNative(L110): pan
,I/bluedroid( 2643): get_profile_interface pan
,D/BluetoothTethering(  796): got CMD_CHANNEL_HALF_CONNECTED
I/BtGatt.JNI( 2643): classInitNative(L684): classInitNative: Success!
D/BtGatt.DebugUtils( 2643): handleDebugAction() action=null
D/BtGatt.GattService( 2643): Received start request. Starting profile...
D/BtGatt.GattService( 2643): start()
,I/bluedroid( 2643): get_profile_interface gatt
,D/BluetoothMapService( 2643): Received start request. Starting profile...
,D/BluetoothMapService( 2643): start()
D/BluetoothAdapterService( 2643): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/HeadsetPhoneState( 2643): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterService( 2643): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 2643): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 2643): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2643): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2643): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterState( 2643): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 2643): enable
D/BluetoothInputDevice( 2657): Proxy object connected
D/HidProfile( 2657): Bluetooth service connected
I/bt_hci_bdroid( 2643): init
D/BluetoothPan( 2657): BluetoothPAN Proxy object connected
D/PanProfile( 2657): Bluetooth service connected
D/BluetoothMap( 2657): Proxy object connected
D/MapProfile( 2657): Bluetooth service connected
D/BluetoothMap( 2657): getConnectedDevices()
I/bt_vendor( 2643): init
I/bt_vnd_conf( 2643): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 2643): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,D/BluetoothMap( 2657): Bluetooth is Not enabled
,I/bt_hci_bdroid( 2643): bt_hc_worker_thread started
,I/bt_userial_vendor( 2643): userial vendor open: opening /dev/ttyHS99
I/GKI_LINUX( 2643): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
,I/bt-btu  ( 2643): btu_task pending for preload complete event
,I/bt_userial_vendor( 2643): device fd = 65 open
,D/dalvikvm(  796): GC_EXPLICIT freed 22482K, 53% free 26172K/55504K, paused 2ms+5ms, total 93ms
,I/bt_hwcfg( 2643): bt vendor lib: set UART baud 4000000
,D/bt_hwcfg( 2643): Chipset BCM4335C0
D/bt_hwcfg( 2643): Target name = [BCM4335C0]
,I/bt_hwcfg( 2643): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,D/dalvikvm( 2688): GC_CONCURRENT freed 194K, 2% free 16926K/17152K, paused 3ms+4ms, total 22ms
,D/AuthorizationBluetoothService( 1112): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/BroadcastQueue(  796): Permission Denial: receiving Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 (has extras) } to com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver requires android.permission.BLUETOOTH due to sender android (uid 1000)
,I/ActivityManager(  796): Killing 2073:com.google.android.music:main/u0a58 (adj 15): empty #17
,F/ActivityManager(  796): Service ServiceRecord{42d5c098 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{42d162e8 2073:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  796): Service ServiceRecord{42d32b18 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{42d162e8 2073:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  796): Service ServiceRecord{42cab380 u0 com.google.android.music/.download.cache.ArtCacheService} in process ProcessRecord{42d162e8 2073:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  796): Service ServiceRecord{42c9abc0 u0 com.google.android.music/.download.artwork.ArtDownloadService} in process ProcessRecord{42d162e8 2073:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  796): Service ServiceRecord{42bf6928 u0 com.google.android.music/.download.ArtDownloadQueueService} in process ProcessRecord{42d162e8 2073:com.google.android.music:main/u0a58} not same as in map: null
,I/bt_hwcfg( 2643): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 2643): Settlement delay -- 100 ms
,I/bt_hwcfg( 2643): bt vendor lib: set UART baud 4000000
,I/bt_hwcfg( 2643): Setting local bd addr to 34:FC:EF:11:B1:66
,I/bt_hwcfg( 2643): vendor lib fwcfg completed
,I/bt-btu  ( 2643): btu_task received preload complete event
I/        ( 2643): BTE_InitTraceLevels -- TRC_HCI
I/        ( 2643): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 2643): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 2643): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 2643): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 2643): BTE_InitTraceLevels -- TRC_A2D
I/        ( 2643): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 2643): BTE_InitTraceLevels -- TRC_BTM
I/        ( 2643): BTE_InitTraceLevels -- TRC_GAP
I/        ( 2643): BTE_InitTraceLevels -- TRC_PAN
I/        ( 2643): BTE_InitTraceLevels -- TRC_SDP
I/        ( 2643): BTE_InitTraceLevels -- TRC_GATT
I/        ( 2643): BTE_InitTraceLevels -- TRC_SMP
I/        ( 2643): BTE_InitTraceLevels -- TRC_BTAPP
,I/        ( 2643): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 2643): BTM_SecRegister:p_cb_info->p_le_callback == 0x75082f8d 
E/bt-btm  ( 2643): BTM_SecRegister: btm_cb.api.p_le_callback = 0x75082f8d 
E/bt-btif ( 2643): Calling BTA_HhEnable
E/bt-btif ( 2643): btif_storage_get_adapter_property service_mask:0x140040
I/BluetoothAdapterProperties( 2643): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 2643): Address is:34:FC:EF:11:B1:66
I/BluetoothAdapterProperties( 2643): adapterPropertyChangedCallback with type:1 len:7
D/BluetoothAdapterProperties( 2643): Name is: Nexus 5
D/BluetoothManagerService(  796): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  796): Stored Bluetooth name: Nexus 5
I/BluetoothAdapterProperties( 2643): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 2643): Scan Mode:20
I/BluetoothAdapterProperties( 2643): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 2643): Discoverable Timeout:120
I/BluetoothAdapterProperties( 2643): adapterPropertyChangedCallback with type:8 len:36
D/BluetoothAdapterProperties( 2643): Adding bonded device:F4:F1:E1:5C:3B:E2
D/BluetoothAdapterProperties( 2643): Adding bonded device:F8:95:C7:87:85:54
D/BluetoothAdapterProperties( 2643): Adding bonded device:E0:DB:10:1F:C9:5E
D/BluetoothAdapterProperties( 2643): Adding bonded device:08:EC:A9:50:76:27
D/BluetoothAdapterProperties( 2643): Adding bonded device:F8:95:C7:87:3C:51
D/BluetoothAdapterProperties( 2643): Adding bonded device:58:2A:F7:ED:96:BE
I/BluetoothAdapterProperties( 2643): adapterPropertyChangedCallback with type:3 len:48
E/BluetoothRemoteDevices( 2643): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
E/BluetoothRemoteDevices( 2643): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
E/BluetoothRemoteDevices( 2643): devicePropertyChangedCallback: bdDevice: E0:DB:10:1F:C9:5E, value is empty for type: 10
E/BluetoothRemoteDevices( 2643): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
E/BluetoothRemoteDevices( 2643): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
E/BluetoothRemoteDevices( 2643): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
I/bt_hwcfg( 2643): SCO PCM configure {0, 4, 0, 0, 0}
I/bte_conf( 2643): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 2643): [1] primary_record=1 vendor_id=0x000F vendor_id_source=0x0001 product_id=0x1200 version=0x1436
I/bte_conf( 2643): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 2643): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/BluetoothAdapterState( 2643): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 2643): ScanMode =  20
D/BluetoothAdapterProperties( 2643): State =  11
D/BluetoothAdapterProperties( 2643): Setting state to 12
I/BluetoothAdapterState( 2643): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 2643): Broadcasting updateAdapterState() to 1 receivers.
I/BluetoothAdapterState( 2643): Entering On State
D/BluetoothManagerService(  796): Message: 60
D/BluetoothManagerService(  796): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  796): Broadcasting onBluetoothStateChange(true) to 10 receivers.
D/BluetoothPan(  796): onBluetoothStateChange(on) call bindService
D/BluetoothPanServiceJni( 2643): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
I/BluetoothAdapterProperties( 2643): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
D/BluetoothHeadset( 1001): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 2643): Scan Mode:21
I/BluetoothAdapterProperties( 2643): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 2643): Discoverable Timeout:120
D/BluetoothPbap( 2657): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
D/BluetoothHeadset(  796): onBluetoothStateChange: up=true
D/BluetoothA2dp(  796): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1001): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1001): onBluetoothStateChange: up=true
D/BluetoothMap( 2657): onBluetoothStateChange: up=true
D/BluetoothPan( 2657): onBluetoothStateChange(on) call bindService
W/ContextImpl(  796): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:192 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:484 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1129 
W/ContextImpl( 2657): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap$1.onBluetoothStateChange:132 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
W/ContextImpl( 2657): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:192 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
D/BluetoothInputDevice( 2657): onBluetoothStateChange: up=true
D/BluetoothManagerService(  796): Bluetooth State Change Intent: 11 -> 12
D/BluetoothMapService( 2643): onReceive
D/BluetoothManagerService(  796): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  796): Message: 40
D/BluetoothManagerService(  796): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
D/BluetoothMapService( 2643): STATE_ON
D/BluetoothMapService( 2643): Map Service startRfcommSocketListener
D/BluetoothMapService( 2643): Map Service initSocket
D/BluetoothManagerService(  796): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
W/BluetoothAdapter( 2643): getBluetoothService() called with no BluetoothManagerCallback
D/LocalBluetoothProfileManager( 2657): Adding local A2DP profile
E/BluetoothServiceJni( 2643): SOCK FLAG = 1 ***********************
D/BluetoothMapService( 2643): Accepting socket connection...
D/BluetoothManagerService(  796): Message: 30
D/LocalBluetoothProfileManager( 2657): Adding local HEADSET profile
D/BluetoothManagerService(  796): Message: 30
W/ContextImpl( 2657): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
D/dalvikvm( 2643): GC_CONCURRENT freed 261K, 2% free 16838K/17128K, paused 2ms+2ms, total 22ms
D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
E/bt_h4   ( 2643): vendor lib postload completed
W/ContextImpl( 2657): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
D/Tethering(  796): sendTetherStateChangedBroadcast 1, 0, 0
W/SocketClient(  182): write error (Broken pipe)
D/BluetoothMap( 2657): getConnectedDevices()
D/BluetoothMap( 2657): getConnectionState(58:2A:F7:ED:96:BE)
D/MapProfile( 2657): getConnectionStatus: status is: 0
D/dalvikvm( 2657): GC_CONCURRENT freed 251K, 2% free 16840K/17120K, paused 3ms+1ms, total 13ms
D/BluetoothMap( 2657): getConnectedDevices()
D/BluetoothMap( 2657): getConnectionState(F8:95:C7:87:3C:51)
D/MapProfile( 2657): getConnectionStatus: status is: 0
D/BluetoothMap( 2657): getConnectedDevices()
D/BluetoothMap( 2657): getConnectionState(E0:DB:10:1F:C9:5E)
D/MapProfile( 2657): getConnectionStatus: status is: 0
D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
D/BluetoothMap( 2657): getConnectedDevices()
D/BluetoothMap( 2657): getConnectionState(F8:95:C7:87:85:54)
D/MapProfile( 2657): getConnectionStatus: status is: 0
D/BluetoothMap( 2657): getConnectedDevices()
D/BluetoothMap( 2657): getConnectionState(F4:F1:E1:5C:3B:E2)
D/MapProfile( 2657): getConnectionStatus: status is: 0
I/wpa_supplicant( 2656): rfkill: Cannot open RFKILL control device
D/BluetoothMap( 2657): getConnectedDevices()
D/BluetoothMap( 2657): getConnectionState(08:EC:A9:50:76:27)
D/MapProfile( 2657): getConnectionStatus: status is: 0
W/ContextImpl( 2657): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/BluetoothA2dp( 2657): Proxy object connected
D/A2dpProfile( 2657): Bluetooth service connected
D/BluetoothHeadset( 2657): Proxy object connected
D/HeadsetProfile( 2657): Bluetooth service connected
D/DockEventReceiver( 2657): finishStartingService: stopping service
D/BluetoothManagerService(  796): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 2643): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 2643): SOCK FLAG = 1 ***********************
D/BluetoothPbap( 2657): Proxy object connected
D/PbapServerProfile( 2657): Bluetooth service connected
D/AuthorizationBluetoothService( 1112): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
E/AuthorizationBluetoothService( 1112): Proximity feature is not enabled.
W/BroadcastQueue(  796): Permission Denial: receiving Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 (has extras) } to com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver requires android.permission.BLUETOOTH due to sender android (uid 1000)
D/BluetoothManagerService(  796): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 2643): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 2643): SOCK FLAG = 0 ***********************
I/BtOppRfcommListener( 2643): Accept thread started.
D/WifiConfigStore(  796): Loading config and enabling all networks
W/Settings( 1854): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/CommandListener(  182): Setting iface cfg
D/CommandListener(  182): Trying to bring up p2p0
D/WifiMonitor(  796): startMonitoring(p2p0) with mConnected = true
,D/BluetoothManagerService(  796): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 2590): Got Device Bluetooth address: 34:FC:EF:11:B1:66
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): my name is : LGE-Nexus 5_PT680
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): attempting to connect to test coordinator
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): check test folder
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): found test : ./testFindPeers.js
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): found test : ./testReConnect.js
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): found test : ./testSendData.js
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Test app app.js loaded
I/jxcore-log( 2590): 
,I/Choreographer( 2590): Skipped 126 frames!  The application may be doing too much work on its main thread.
,I/chromium( 2590): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/wpa_supplicant( 2656): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 2656): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 2656): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 2656): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,D/ConnectivityService(  796): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  796): Done.
,D/ConnectivityService(  796): Setting timer for 720seconds
,E/WifiStateMachine(  796): scanCount==0 - aborting
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,D/ConnectivityService(  796): handleInetConditionChange: no active default network - ignore
,D/WifiStateMachine(  796): VerifyingLinkState enter
,D/WifiStateMachine(  796): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  796): CaptivePortalCheckState enter
D/ConnectivityService(  796): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  796): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  796): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  796): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  796): Unexpected mtu value: android.net.wifi.WifiStateTracker@42b7ddb0
,D/Nat464Xlat(  796): requiresClat: netType=1, hasIPv4Address=true
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,D/ConnectivityService(  796): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  796):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  796): requiresClat: netType=1, hasIPv4Address=true
,I/jxcore-log( 2590): BLE advertisement not supported: Build version is 19
I/jxcore-log( 2590): 
,D/dalvikvm( 1172): GC_CONCURRENT freed 1115K, 7% free 17899K/19196K, paused 5ms+1ms, total 25ms
,D/CaptivePortalTracker(  796): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  796): MasterInitialState.processMessage what=3
,D/        (  796): Setting time of day to sec=1449086820
,W/        (  796): Unable to set rtc to 1449086820: Invalid argument
,I/ActivityManager(  796): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=2820 uid=10031 gids={50031, 3003, 1028, 1015}
,D/GpsLocationProvider(  796): NTP server returned: 1449086817187 (Wed Dec 02 21:06:57 CET 2015) reference: 87450 certainty: 20 system time offset: -3116
,I/dalvikvm( 1295): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
,W/dalvikvm( 1295): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1295): VFY: replacing opcode 0x6e at 0x0033
,E/Auth.Api.Credentials( 1295): [CredentialSyncAdapter] Unknown sync event.
,D/dalvikvm( 2289): GC_CONCURRENT freed 383K, 3% free 17572K/17976K, paused 2ms+2ms, total 34ms
,D/dalvikvm( 2820): DexOpt: couldn't find static field Landroid/support/v4/e/a;.common_ic_googleplayservices
,W/dalvikvm( 2820): VFY: unable to resolve static field 811 (common_ic_googleplayservices) in Landroid/support/v4/e/a;
D/dalvikvm( 2820): VFY: replacing opcode 0x60 at 0x0051
,I/dalvikvm( 2820): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.e.a
W/dalvikvm( 2820): VFY: unable to resolve virtual method 323: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 2820): VFY: replacing opcode 0x6e at 0x018f
,I/dalvikvm( 2820): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.e.a
W/dalvikvm( 2820): VFY: unable to resolve virtual method 671: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 2820): VFY: replacing opcode 0x6e at 0x000b
,D/dalvikvm( 2820): DexOpt: couldn't find static field Landroid/support/v4/e/a;.common_full_open_on_phone
,I/dalvikvm( 2820): DexOpt: unable to optimize static field ref 0x032a at 0x85 in Lcom/google/android/gms/common/e;.a
,D/dalvikvm( 2820): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,W/dalvikvm( 2820): VFY: unable to resolve instance field 71
D/dalvikvm( 2820): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 2820): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2820): DexOpt: unable to optimize instance field ref 0x0047 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 2820): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 2820): DexOpt: unable to optimize instance field ref 0x0047 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/dalvikvm( 2820): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,W/dalvikvm( 2820): VFY: unable to resolve instance field 71
,D/dalvikvm( 2820): VFY: replacing opcode 0x54 at 0x0011
,D/dalvikvm( 2820): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2820): DexOpt: unable to optimize instance field ref 0x0047 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 2820): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2820): DexOpt: unable to optimize instance field ref 0x0047 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 2820): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 2820): DexOpt: unable to optimize instance field ref 0x003d at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,I/iu.SyncManager( 1295): SYNC; picasa accounts
,D/NetworkLogImpl( 1295): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1295): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SystemUpdateService( 1295): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1295): onCreate
,I/iu.UploadsManager( 1295): num queued entries: 0
,I/iu.UploadsManager( 1295): num updated entries: 0
I/iu.SyncManager( 1295): NEXT; no task
,D/SystemUpdateService( 1295): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1295): active receiver: enabled
,I/SystemUpdateService( 1295): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1295): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1295): now status is 0 (complete)
I/SystemUpdateService( 1295): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1295): file has been verified
,I/SystemUpdateService( 1295): OTA package size = 2571501
,I/SystemUpdateService( 1295): showing system update notification
,I/Babel   ( 1854): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  796): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=2869 uid=10033 gids={50033, 1028}
,D/SystemUpdateService( 1295): onDestroy
,V/AlarmClock( 2869): AlarmInitReceiver android.intent.action.TIME_SET
,I/dalvikvm(  978): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm(  978): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm(  978): VFY: replacing opcode 0x6e at 0x0033
,I/AlarmClock( 2869): Displaying next alarm time: ''
,V/AlarmClock( 2869): AlarmInitReceiver finished
,I/ActivityManager(  796): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=2905 uid=10068 gids={50068}
,D/dalvikvm( 1112): GC_CONCURRENT freed 396K, 3% free 18199K/18708K, paused 1ms+4ms, total 30ms
,I/ActivityManager(  796): Killing 1735:com.google.android.gm/u0a41 (adj 15): empty #17
D/dalvikvm( 2905): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x42606b80, skipping init
D/TimeService( 2905): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449086820739
D/        ( 2905): TimeServiceNative: User Time to be set is 1449086820739
D/QC-time-services( 2905): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 2905): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 2905): Lib:time_genoff_operation: pargs->ts_val = 1449086820739
D/QC-time-services( 2905): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  202): Daemon: Connection accepted:time_genoff
D/QC-time-services(  202): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449086820739
D/QC-time-services(  202): Daemon:genoff_opr: Base = 2, val = 1449086820739, operation = 0
D/QC-time-services(  202): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS0/22/71 14:12:15
D/QC-time-services(  202): Daemon:Value read from RTC seconds = 33401535000
D/QC-time-services(  202): Daemon:new time 1449086820739 
D/QC-time-services(  202): Daemon: delta 1415685285739 genoff 1415685285739 
D/QC-time-services(  202): Daemon:genoff_persistent_update: Writing genoff = 1415685285739 to memory
D/QC-time-services(  202): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  202): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  202): Updating the TOD offset
D/QC-time-services(  202): Daemon:genoff_persistent_update: Writing genoff = 1415685285739 to memory
D/QC-time-services(  202): Daemon:Opening File: /data/system/time/ats_1
,D/QC-time-services(  202): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  202): Daemon:Update to modem bit set
D/QC-time-services(  202): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  202): Daemon: Base = 2, Value being sent to MODEM = 1133122020739
,E/QC-time-services( 2905): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  202): Daemon: Time-services: Waiting to acceptconnection
,D/QC-time-services(  202): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
I/ActivityManager(  796): Killing 2119:com.android.providers.calendar/u0a1 (adj 15): empty #17
,D/dalvikvm( 1295): GC_CONCURRENT freed 540K, 3% free 18911K/19480K, paused 9ms+2ms, total 55ms
,I/dalvikvm( 1112): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1112): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1112): VFY: replacing opcode 0x6e at 0x0033
,I/CheckinService( 1295): Checkin interval check for package: unspecified last checkin: 1449052203979 min interval config: 0 actual interval: 34616805
,D/dalvikvm( 1112): GC_CONCURRENT freed 476K, 4% free 18233K/18812K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 1112): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 1112): WAIT_FOR_CONCURRENT_GC blocked 4ms
,I/GCM     ( 1112): GCM config loaded
,D/dalvikvm( 1112): GC_CONCURRENT freed 502K, 4% free 18213K/18856K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 1112): WAIT_FOR_CONCURRENT_GC blocked 11ms
,I/ActivityManager(  796): Killing 2435:com.android.defcontainer/u0a4 (adj 15): empty #17
,D/ConnectivityService(  796): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/dalvikvm( 2231): GC_CONCURRENT freed 439K, 4% free 17232K/17816K, paused 3ms+3ms, total 28ms
,D/Finsky  ( 2231): [1] 5.onFinished: Installation state replication succeeded.
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/ActivityManager(  796): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=2941 uid=10001 gids={50001, 3003, 1028, 1015}
,D/dalvikvm(  186): GC_EXPLICIT freed 42K, 1% free 16699K/16772K, paused 5ms+7ms, total 52ms
,D/dalvikvm(  186): GC_EXPLICIT freed <1K, 1% free 16699K/16772K, paused 1ms+1ms, total 12ms
,D/dalvikvm(  186): GC_EXPLICIT freed <1K, 1% free 16699K/16772K, paused 0ms+1ms, total 12ms
,D/dalvikvm(  796): GC_EXPLICIT freed 1708K, 53% free 26270K/55504K, paused 3ms+4ms, total 57ms
,I/CalendarProvider2( 2941): Created com.android.providers.calendar.CalendarAlarmManager@4261d110(com.android.providers.calendar.CalendarProvider2@42614de0)
,I/CalendarProvider2( 2941): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 2941): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlertReceiver( 1660): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.google.android.calendar/com.android.calendar.alerts.AlertReceiver }
,D/AlertService( 1660): 0 Action = android.intent.action.PROVIDER_CHANGED
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,D/CaptivePortalTracker(  796): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  796): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  796): Checking http://216.58.209.46/generate_204
W/ActivityThread(  796): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/CaptivePortalTracker(  796): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  796): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  796): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  796): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  796): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/AlertService( 1660): Beginning updateAlertNotification
,D/AlertService( 1660): No fired or scheduled alerts
,D/AlertService( 1660): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 1660): No events found starting within 1 week.
I/ActivityManager(  796): Killing 939:android.process.acore/u0a3 (adj 15): empty #17
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,D/dalvikvm( 1112): GC_CONCURRENT freed 404K, 3% free 18307K/18840K, paused 2ms+9ms, total 27ms
,I/VacuumService( 1112): Vacuum at: now=1449086850448 tag=VacuumService
,D/UdcCache:FPQuery( 1295): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1112): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1295): GC_CONCURRENT freed 260K, 2% free 19345K/19636K, paused 3ms+2ms, total 36ms
,W/SQLiteConnectionPool( 1295): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/dalvikvm( 1112): GC_CONCURRENT freed 538K, 4% free 18218K/18860K, paused 2ms+1ms, total 30ms
,D/GetConfigurationSnapshotOperation( 1112): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1112): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1112): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 1112): GC_CONCURRENT freed 343K, 3% free 18303K/18860K, paused 3ms+3ms, total 21ms
,D/GetCommittedConfigurationOperation( 1112): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 1112): GC_CONCURRENT freed 419K, 3% free 18350K/18900K, paused 2ms+1ms, total 16ms
,D/dalvikvm( 1112): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/dalvikvm( 1112): GC_CONCURRENT freed 353K, 3% free 18452K/18980K, paused 4ms+3ms, total 30ms
,D/GetCommittedConfigurationOperation( 1112): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 1112): GC_CONCURRENT freed 437K, 3% free 18503K/19040K, paused 3ms+2ms, total 19ms
,D/dalvikvm( 1112): GC_CONCURRENT freed 400K, 3% free 18657K/19152K, paused 1ms+3ms, total 17ms
,D/dalvikvm( 1112): GC_CONCURRENT freed 582K, 4% free 18677K/19356K, paused 2ms+2ms, total 18ms
,D/GetCommittedConfigurationOperation( 1112): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1112): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1112):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1112): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 1112): GC_CONCURRENT freed 675K, 5% free 18617K/19412K, paused 5ms+6ms, total 46ms
,D/dalvikvm( 1112): GC_CONCURRENT freed 529K, 5% free 18633K/19412K, paused 3ms+3ms, total 21ms
,D/GetCommittedConfigurationOperation( 1112): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 1112): GC_FOR_ALLOC freed 395K, 5% free 18471K/19412K, paused 25ms, total 26ms
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/PowerManagerService(  796): Going to sleep due to screen timeout...
,I/Adreno-EGL(  796): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/SurfaceFlinger(  185): Screen released, type=0 flinger=0xb8b16450
,D/qdhwcomposer(  185): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  185): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  796): Excessive delay in blankDisplay() while turning screen off: 292ms
,V/KeyguardServiceDelegate(  796): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@43da2510)
,V/KeyguardServiceDelegate(  796): **** SHOWN CALLED ****
I/WindowManager(  796): No lock screen! windowToken=null
,D/NfcService( 1029): NFC-C OFF
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/rmt_storage(  181): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb8ab2160
I/rmt_storage(  181): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  181): wakelock acquired: 1, error no: 2
,I/rmt_storage(  181): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1196744160)
,I/rmt_storage(  181): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  181): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  181): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1196744160) wakelock released: 1, error no: 0
I/rmt_storage(  181): 
,I/rmt_storage(  181): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb8ab2160
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Coordinator is now connected to the server!
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2590): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector command called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":18,"addressList":[{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"00:F4:6F:30:E0:6C","tryCount":0},{"address":"F4:F1:E1:5C:3B
,I/jxcore-log( 2590): Start now : testSendData.js
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 18
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): check server
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): serverPort is 43412
I/jxcore-log( 2590): 
,D/BluetoothManagerService(  796): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2590): Stoping All
I/        ( 2590): Stopping services
I/        ( 2590): Stop Bluetooth
,D/BluetoothManagerService(  796): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2590): Start-My BT: 34:FC:EF:11:B1:66
,D/BluetoothManagerService(  796): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2590):  mInstanceString : {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT680"}
,I/        ( 2590): All stuff available and enabled
I/        ( 2590): Stoping All
I/        ( 2590): Stopping services
I/        ( 2590): Stop Bluetooth
I/        ( 2590): Starting All
I/        ( 2590): Stopping services
,I/        ( 2590): Starting services address: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT680"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@4262a4f8
,I/        ( 2590): Stopping services
,I/        ( 2590): Starting services address: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT680"}
,I/        ( 2590): Add local service :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT680"}, length : 76
,I/        ( 2590): peerDiscoveryTimer timeout value:6800
,I/        ( 2590): Stop Bluetooth
I/        ( 2590): StartBluetooth listener
,I/        ( 2590): StartBluetooth listener
,D/BluetoothManagerService(  796): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2590): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 2643): SOCK FLAG = 0 ***********************
,I/jxcore-log( 2590): StartBroadcasting started ok
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): do fake peer & start
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Connect to fake peer: 7C:F9:0E:51:18:22
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:12:25.904Z SendDataConnector.js: Start called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2590): 
I/jxcore-log( 2590): 2015-12-02T20:12:25.905Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:12:25.905Z SendDataConnector.js: do connect now
I/jxcore-log( 2590): 
,I/        ( 2590): Selected device address: 7C:F9:0E:51:18:22, name: null
I/BTListenerThread( 2590): starting to listen
,I/BTListenerThread( 2590): waiting to accept incoming Connection
,I/        ( 2590): Connecting to null, at 7C:F9:0E:51:18:22
,I/jxcore-log( 2590): 2015-12-02T20:12:25.910Z SendDataTCPServer.js: TCP/IP server is bound to port: 43412
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 2590): We already were running, thus doing nothing
,I/        ( 2590): Added local service
I/        ( 2590): Cleared service requests
,I/        ( 2590): Stopped peer discovery
,I/        ( 2590): Started peer discovery
,I/        ( 2590): Discovery state changed to Started.
,I/BTConnectToThread( 2590): Starting to connect
,W/BluetoothAdapter( 2590): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2643): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 2590): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[250]}
,W/bt-sdp  ( 2643): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,E/bt-btif ( 2643): DISCOVERY_COMP_EVT slot id:5, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 2590): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 2643): invalid rfc slot id: 5
,I/CONNEC  ( 2590): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2590): 2015-12-02T20:12:31.070Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:12:31.071Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:12:31.074Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2590): 
,I/wpa_supplicant( 2656): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/ConnectivityService(  796): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  796): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  796): Attempting to switch to mobile
,D/ConnectivityService(  796): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  796): android_net_utils_resetConnections in env=0x76a3ef00 clazz=0x5d400001 iface=wlan0 mask=0x3
,D/ConnectivityService(  796): resetConnections(wlan0, 3)
V/NativeCrypto( 1112): Read error: ssl=0x78e84c90: I/O error during system call, Connection timed out
V/NativeCrypto( 1112): SSL shutdown failed: ssl=0x78e84c90: I/O error during system call, Broken pipe
,I/jxcore-log( 2590): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): The Coordinator has disconnected!
I/jxcore-log( 2590): 
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  796): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  796): handleInetConditionChange: no active default network - ignore
,W/wpa_supplicant( 2656): wlan0: Failed to initiate AP scan
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2590): 
,D/WifiService(  796): setWifiEnabled: false pid=2590, uid=10108
,E/WifiStateMachine(  796): scanCount==0 - aborting
,D/WifiService(  796): setWifiEnabled: true pid=2590, uid=10108
D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/WifiController(  796): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 475ms
,I/jxcore-log( 2590): Wifi toggled for connection repairment
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 2590): Wifi is DISABLED !!
I/        ( 2590): Stoping All
I/        ( 2590): Stopping services
,I/        ( 2590): Stopping services
,I/        ( 2590): Stop Bluetooth
I/        ( 2590): Stop Bluetooth
I/BTListenerThread( 2590): Stopped
,E/bt-btif ( 2643): bta_jv_rfcomm_stop_server
I/        ( 2590): Clearing local services failed, error code 2
,I/        ( 2590): Clearing service requests failed, error code 2
,I/        ( 2590): Stopping peer discovery failed, error code 2
,I/wpa_supplicant( 2656): P2P-FIND-STOPPED 
,D/WifiController(  796): DEFERRED_TOGGLE handled
,I/wpa_supplicant( 2656): p2p0: CTRL-EVENT-TERMINATING 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/Tethering(  796): InitialState.processMessage what=4
,D/Tethering(  796): sendTetherStateChangedBroadcast 0, 0, 0
,I/wpa_supplicant( 2656): wlan0: CTRL-EVENT-TERMINATING 
,W/Settings( 1854): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  978): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/SoftapController(  182): Softap fwReload - Ok
D/CommandListener(  182): Setting iface cfg
,D/CommandListener(  182): Trying to bring down wlan0
,D/WifiMonitor(  796): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 3139): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3139): rfkill: Cannot open RFKILL control device
,D/CaptivePortalTracker(  796): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/Tethering(  796): MasterInitialState.processMessage what=3
D/ConnectivityService(  796): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Babel   ( 1854): connection state changed from CONNECTED to DISCONNECTED
,I/iu.Environment( 1295): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/SystemUpdateService( 1295): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/iu.UploadsManager( 1295): num queued entries: 0
,I/iu.UploadsManager( 1295): num updated entries: 0
,D/SystemUpdateService( 1295): onCreate
,I/iu.SyncManager( 1295): NEXT; no task
,D/SystemUpdateService( 1295): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1295): active receiver: enabled
,I/SystemUpdateService( 1295): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1295): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1295): now status is 0 (complete)
I/SystemUpdateService( 1295): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1295): file has been verified
,I/SystemUpdateService( 1295): OTA package size = 2571501
,I/SystemUpdateService( 1295): showing system update notification
,D/SystemUpdateService( 1295): onDestroy
,D/Tethering(  796): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3139): rfkill: Cannot open RFKILL control device
,D/WifiConfigStore(  796): Loading config and enabling all networks
,W/Settings( 1854): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/CommandListener(  182): Setting iface cfg
,D/CommandListener(  182): Trying to bring up p2p0
,D/WifiMonitor(  796): startMonitoring(p2p0) with mConnected = true
I/WB      ( 2590): Wifi is now enabled !
I/        ( 2590): Stoping All
I/        ( 2590): Stopping services
,I/        ( 2590): Stop Bluetooth
I/        ( 2590): Starting All
I/        ( 2590): Stopping services
I/        ( 2590): Starting services address: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT680"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@4262a4f8
I/        ( 2590): Stopping services
,I/        ( 2590): Starting services address: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT680"}
I/        ( 2590): Add local service :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT680"}, length : 76
,I/        ( 2590): peerDiscoveryTimer timeout value:8876
,I/        ( 2590): Stop Bluetooth
I/        ( 2590): StartBluetooth listener
,I/        ( 2590): StartBluetooth listener
,D/BluetoothManagerService(  796): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2590): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 2643): SOCK FLAG = 0 ***********************
I/BTListenerThread( 2590): starting to listen
,I/BTListenerThread( 2590): waiting to accept incoming Connection
,I/        ( 2590): Discovery state changed to Started.
,I/        ( 2590): Added local service
,I/        ( 2590): Cleared service requests
,I/        ( 2590): Stopped peer discovery
,I/        ( 2590): Started peer discovery
,I/jxcore-log( 2590): 2015-12-02T20:12:36.077Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:12:36.079Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2590): 
,D/ConnectivityService(  796): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2590): Found 1 peers.
,I/SS      ( 2590): Peer(1): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 2590): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2590): Added service request
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,I/        ( 2590): Started service discovery
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,I/jxcore-log( 2590): 2015-12-02T20:12:41.086Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:12:41.088Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:12:41.091Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:12:41.092Z SendDataConnector.js: do connect now
I/jxcore-log( 2590): 
,I/        ( 2590): Selected device address: 7C:F9:0E:51:18:22, name: null
,I/        ( 2590): Connecting to null, at 7C:F9:0E:51:18:22
,I/BTConnectToThread( 2590): Starting to connect
,W/BluetoothAdapter( 2590): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2643): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 2590): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[251]}
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-sdp  ( 2643): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
,E/bt-btif ( 2643): DISCOVERY_COMP_EVT slot id:7, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 2590): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 2643): invalid rfc slot id: 7
,I/CONNEC  ( 2590): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2590): 2015-12-02T20:12:46.270Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:51:18:22 failed,
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:12:46.271Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:12:46.275Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/SocketClient(  182): write error (Broken pipe)
,D/ConnectivityService(  796): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant( 3139): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3139): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 3139): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3139): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,D/dalvikvm( 1001): GC_CONCURRENT freed 336K, 3% free 17064K/17428K, paused 2ms+1ms, total 22ms
,E/WifiStateMachine(  796): scanCount==0 - aborting
,I/wpa_supplicant( 3139): P2P-FIND-STOPPED 
,I/        ( 2590): Discovery state changed to Stopped.
,I/        ( 2590): Starting peer discovery failed, error code 2
,D/WifiStateMachine(  796): VerifyingLinkState enter
,D/WifiStateMachine(  796): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  796): CaptivePortalCheckState enter
,D/ConnectivityService(  796): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  796): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  796): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  796): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  796): Unexpected mtu value: android.net.wifi.WifiStateTracker@42b7ddb0
,D/Nat464Xlat(  796): requiresClat: netType=1, hasIPv4Address=true
,I/jxcore-log( 2590): 2015-12-02T20:12:51.297Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:12:51.297Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2590): 
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2590): Found 5 peers.
,I/SS      ( 2590): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 2590): Peer(2): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 2590): Peer(3): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 2590): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 2590): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 2590): Ignored { when=-5ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2590): Added service request
,I/        ( 2590): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT880","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 2590): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT880","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT880, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT880, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,D/ConnectivityService(  796): NetTransition Wakelock for ConnectedState released by timeout
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Coordinator is now connected to the server!
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,E/NetdConnector(  796): NDC Command {55 resolver setifdns wlan0  192.168.1.1} took too long (2316ms)
,D/ConnectivityService(  796): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  796):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  796): requiresClat: netType=1, hasIPv4Address=true
D/Tethering(  796): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  796): NoActiveNetworkState{ when=-6ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 2590): Started service discovery
I/        ( 2590): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT7267"}, typeCordovap2p._tcp.local.:
I/        ( 2590): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT7267"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT7267, peerAddress: B4:CE:F6:AB:A4:6A
I/        ( 2590): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT7267"}, typeCordovap2p._tcp.local.:
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT7267, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/iu.Environment( 1295): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1295): num queued entries: 0
,I/iu.UploadsManager( 1295): num updated entries: 0
I/iu.SyncManager( 1295): NEXT; no task
,I/SystemUpdateService( 1295): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1295): onCreate
,D/SystemUpdateService( 1295): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1295): active receiver: enabled
,I/SystemUpdateService( 1295): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1295): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1295): now status is 0 (complete)
,I/SystemUpdateService( 1295): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1295): file has been verified
,I/SystemUpdateService( 1295): OTA package size = 2571501
,I/SystemUpdateService( 1295): showing system update notification
,D/SystemUpdateService( 1295): onDestroy
,D/dalvikvm(  796): GC_CONCURRENT freed 2014K, 53% free 26529K/55504K, paused 4ms+4ms, total 80ms
,I/Babel   ( 1854): connection state changed from DISCONNECTED to CONNECTED
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 2590): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT880","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT880","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT880, peerAddress: 08:EC:A9:50:75:41
,I/        ( 2590): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT880","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT880, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41,
,I/        ( 2590): Found Service, :{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1479","ra":"7C:F9:0E:51:18:22"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1479","ra":"7C:F9:0E:51:18:22"} -- peerIdentifier:7C:F9:0E:51:18:22, peerName: samsung-SM-A500FU_PT1479, peerAddress: 7C:F9:0E:51:18:22
I/        ( 2590): Found Service, :{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1479","ra":"7C:F9:0E:51:18:22"}, typeCordovap2p._tcp.local.:
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : 7C:F9:0E:51:18:22, Name: samsung-SM-A500FU_PT1479, WifiDirectName: Thali Test (Galaxy A5), WifiDirect Address: 7e:f9:0e:51:18:23, peerId: 7C:F9:0E:51:18:22
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/ConnectivityService(  796): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/jxcore-log( 2590): 2015-12-02T20:12:56.319Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:12:56.320Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:12:56.322Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:12:56.324Z SendDataConnector.js: do connect now
I/jxcore-log( 2590): 
,I/        ( 2590): Selected device address: 7C:F9:0E:51:18:22, name: null
,I/        ( 2590): Connecting to null, at 7C:F9:0E:51:18:22
,I/BTConnectToThread( 2590): Starting to connect
,W/BluetoothAdapter( 2590): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2643): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 2590): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[253]}
,I/        ( 2590): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT785","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT785","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT785, peerAddress: E0:DB:10:14:E2:C0
,I/        ( 2590): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT785","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT785, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2643): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,I/BluetoothBondStateMachine( 2643): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2643): Entering PendingCommandState State
,W/BluetoothEventManager( 2657): CachedBluetoothDevice for device 7C:F9:0E:51:18:22 not found, calling readPairedDevices().
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,E/BluetoothEventManager( 2657): Got bonding state changed for 7C:F9:0E:51:18:22, but we have no record of that device.
,E/bt-btif ( 2643): services_to_search = 3fffffff
,E/bt-btif ( 2643): ****************search UUID = 1200***********
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,E/bt-btif ( 2643): services_to_search = 3ffffffe
,E/bt-btif ( 2643): ****************search UUID = 0100***********
,W/bt-btif ( 2643): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 2590): Starting to Handshake
W/bt-btif ( 2643): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2643): bta_dm_pm_ssr:2, lat:1200
,I/BTHandshakeSocketThread( 2590): Creating BTHandshakeSocketThread
I/BTConnectToThread( 2590): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread started
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/BTConnectToThread( 2590): got MESSAGE_READ 83 bytes.
,I/BTConnectToThread( 2590): Got JSON from encryption:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1479","ra":"7C:F9:0E:51:18:22"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 2590): HandshakeOk : samsung-SM-A500FU_PT1479
,I/HS      ( 2590): Hand Shake finished outgoing for : samsung-SM-A500FU_PT1479
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2590): Starting the connected thread incoming : false, samsung-SM-A500FU_PT1479
,I/BtToSocketBase( 2590): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2590): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2590): mHTTPPort  set to : 54520
,I/BtConnectorHelper( 2590): Request socket is using : 54520
,I/BtToRequestSocket( 2590): Now accepting connections
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,E/bt-btif ( 2643): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 9 uuid:0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BluetoothBondStateMachine( 2643): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
,D/BluetoothAdapterProperties( 2643): Failed to remove device: 7C:F9:0E:51:18:22
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,I/BluetoothBondStateMachine( 2643): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,I/BluetoothBondStateMachine( 2643): StableState(): Entering Off State
,I/BtConnectorHelper( 2590): Calling ConnectionStatusUpdate with port :54520
,I/jxcore-log( 2590): 2015-12-02T20:12:59.300Z SendDataConnector.js: CLIENT connected to 54520, error: null
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:12:59.300Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2590): 
,I/BtToRequestSocket( 2590): incoming data from: /127.0.0.1, port: 54520
,I/BtToRequestSocket( 2590): Set local streams
,I/jxcore-log( 2590): 2015-12-02T20:12:59.305Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2590): 
,I/BtToRequestSocket( 2590): rin ended ---------------------------;
,W/BluetoothEventManager( 2657): CachedBluetoothDevice for device 7C:F9:0E:51:18:22 not found, calling readPairedDevices().
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,E/BluetoothEventManager( 2657): Got bonding state changed for 7C:F9:0E:51:18:22, but we have no record of that device.
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,I/jxcore-log( 2590): 2015-12-02T20:13:00.070Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:13:00.250Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:13:00.530Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:13:00.815Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:13:00.948Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:13:01.565Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:13:01.608Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:13:01.715Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:13:02.054Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2590): 
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/CaptivePortalTracker(  796): DelayedCaptiveCheckState{ when=-8ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  796): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  796): Checking http://216.58.209.46/generate_204
,I/        ( 2590): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT7267"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT7267"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9856"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9856"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9856, peerAddress: 80:01:84:8A:B3:68
,I/        ( 2590): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9856"}, typeCordovap2p._tcp.local.:
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9856, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,W/bt-btif ( 2643): dm_pm_timer expires
,W/bt-btif ( 2643): dm_pm_timer expires 0
,W/bt-btif ( 2643): proc dm_pm_timer expires
,D/CaptivePortalTracker(  796): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  796): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  796): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  796): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  796): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 2590): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT1661"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT1661"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT1661, peerAddress: 00:F4:6F:30:E0:6C
,I/        ( 2590): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT1661"}, typeCordovap2p._tcp.local.:
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT1661, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C,
,I/jxcore-log( 2590): 2015-12-02T20:13:12.055Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:13:12.058Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:13:12.069Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:13:12.070Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:13:12.080Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2590): 
,I/BtToSocketBase( 2590): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 2590): Disconnect outgoing peer: samsung-SM-A500FU_PT1479
I/BtToSocketBase( 2590): Stop ReceivingThread
,I/BtToSocketBase( 2590): Stop SendingThread
,I/BtToSocketBase( 2590): Close local in
,I/BtToSocketBase( 2590): Close LocalOutputStream
I/BtToSocketBase( 2590): Close localHostSocket
,I/BtToSocketBase( 2590): Close bt in
,I/BtToSocketBase( 2590): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2590): Close bt out
,I/BtToSocketBase( 2590): Close bt socket
,I/BtToRequestSocket( 2590): Close server socket
,W/bt-btif ( 2643): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 2590): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5728"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5728"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5728, peerAddress: F4:F1:E1:5C:3B:E2
,I/        ( 2590): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5728"}, typeCordovap2p._tcp.local.:
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5728, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 2590): 2015-12-02T20:13:17.079Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:13:17.080Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2590): 
,I/        ( 2590): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT2788, peerAddress: F8:95:C7:87:3C:51
,I/        ( 2590): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT2788, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothManagerService(  796): Message: 20
,D/BluetoothManagerService(  796): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43621bd0:true
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: Thali Test (Galaxy A5)
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,D/dalvikvm(  978): GC_CONCURRENT freed 361K, 3% free 17915K/18376K, paused 2ms+1ms, total 24ms
,I/        ( 2590): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT7328, peerAddress: 34:FC:EF:9D:93:0B
,I/        ( 2590): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"}, typeCordovap2p._tcp.local.:
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT7328, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 2590): 2015-12-02T20:13:22.086Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:13:22.087Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:13:22.089Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:13:22.090Z SendDataConnector.js: do connect now
I/jxcore-log( 2590): 
,I/        ( 2590): Selected device address: 7C:F9:0E:51:18:22, name: Thali Test (Galaxy A5)
,I/        ( 2590): Connecting to Thali Test (Galaxy A5), at 7C:F9:0E:51:18:22
,I/BTConnectToThread( 2590): Starting to connect
,W/BluetoothAdapter( 2590): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2643): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 2590): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[254]}
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: Thali Test (Galaxy A5)
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,W/bt-btif ( 2643): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 2590): Starting to Handshake
W/bt-btif ( 2643): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2643): bta_dm_pm_ssr:2, lat:1200
,I/BTHandshakeSocketThread( 2590): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2590): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread started
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,I/BTConnectToThread( 2590): got MESSAGE_READ 83 bytes.
,I/BTConnectToThread( 2590): Got JSON from encryption:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1479","ra":"7C:F9:0E:51:18:22"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 2590): HandshakeOk : samsung-SM-A500FU_PT1479
I/HS      ( 2590): Hand Shake finished outgoing for : samsung-SM-A500FU_PT1479
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2590): Starting the connected thread incoming : false, samsung-SM-A500FU_PT1479
I/BtToSocketBase( 2590): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2590): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 2590): mHTTPPort  set to : 56105
I/BtConnectorHelper( 2590): Request socket is using : 56105
,I/BtToRequestSocket( 2590): Now accepting connections
,I/BtConnectorHelper( 2590): Calling ConnectionStatusUpdate with port :56105
,I/jxcore-log( 2590): 2015-12-02T20:13:23.571Z SendDataConnector.js: CLIENT connected to 56105, error: null
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:13:23.571Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2590): 
,I/BtToRequestSocket( 2590): incoming data from: /127.0.0.1, port: 56105
,I/BtToRequestSocket( 2590): Set local streams
,I/jxcore-log( 2590): 2015-12-02T20:13:23.574Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2590): 
,I/BtToRequestSocket( 2590): rin ended ---------------------------;
,I/dalvikvm(  796): Jit: resizing JitTable from 8192 to 16384
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751df7a0 rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 2590): Cleared service requests
,I/        ( 2590): Started peer discovery
,I/        ( 2590): Discovery state changed to Started.
,W/bt-btif ( 2643): dm_pm_timer expires
W/bt-btif ( 2643): dm_pm_timer expires 0
,W/bt-btif ( 2643): proc dm_pm_timer expires
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2590): Found 10 peers.
,I/SS      ( 2590): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2590): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2590): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2590): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2590): Peer(5): Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/SS      ( 2590): Peer(6): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2590): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 2590): Peer(8): A3-1 0a:ec:a9:50:75:42
I/SS      ( 2590): Peer(9): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 2590): Peer(10): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 2590): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2590): Added service request
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 2590): Started service discovery
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 2590): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1414","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1414","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT1414, peerAddress: B0:C5:59:3F:75:69
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT1414, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/jxcore-log( 2590): 2015-12-02T20:13:33.621Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:13:33.622Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:13:33.624Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:13:33.626Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:13:33.629Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2590): 
,I/BtToSocketBase( 2590): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2590): Disconnect outgoing peer: samsung-SM-A500FU_PT1479
,I/BtToSocketBase( 2590): Stop ReceivingThread
I/BtToSocketBase( 2590): Stop SendingThread
,I/BtToSocketBase( 2590): Close local in
,I/BtToSocketBase( 2590): Close LocalOutputStream
I/BtToSocketBase( 2590): Close localHostSocket
,I/BtToSocketBase( 2590): Close bt in
,I/BtToSocketBase( 2590): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2590): Close bt out
I/BtToSocketBase( 2590): Close bt socket
,I/BtToRequestSocket( 2590): Close server socket
,W/bt-btif ( 2643): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,I/jxcore-log( 2590): 2015-12-02T20:13:38.628Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:13:38.629Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2590): 
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: Thali Test (Galaxy A5)
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,I/wpa_supplicant( 3139): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,I/        ( 2590): Cleared service requests
,I/        ( 2590): Started peer discovery
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2590): Found 13 peers.
,I/SS      ( 2590): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 2590): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 2590): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2590): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 2590): Peer(5): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 2590): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 2590): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2590): Peer(8): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 2590): Peer(9): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 2590): Peer(10): Android_8ae2 52:55:27:f0:fd:0b
,I/SS      ( 2590): Peer(11): A3-1 0a:ec:a9:50:75:42
I/SS      ( 2590): Peer(12): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 2590): Peer(13): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 2590): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2590): Added service request
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/        ( 2590): Started service discovery
,I/jxcore-log( 2590): 2015-12-02T20:13:43.638Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:13:43.638Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:13:43.640Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:13:43.642Z SendDataConnector.js: do connect now
I/jxcore-log( 2590): 
,I/        ( 2590): Selected device address: 7C:F9:0E:51:18:22, name: Thali Test (Galaxy A5)
,I/        ( 2590): Connecting to Thali Test (Galaxy A5), at 7C:F9:0E:51:18:22
,I/BTConnectToThread( 2590): Starting to connect
,W/BluetoothAdapter( 2590): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2643): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 2590): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[255]}
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 2590): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5728"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5728"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5728, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5728, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 2590): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1414","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1414","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT1414, peerAddress: B0:C5:59:3F:75:69
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT1414, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 2590): Cleared service requests
,I/        ( 2590): Started peer discovery
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2590): Found 14 peers.
,I/SS      ( 2590): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2590): Peer(2): S5-1 ee:1f:72:63:11:86
,I/SS      ( 2590): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2590): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 2590): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 2590): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
,I/SS      ( 2590): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 2590): Peer(8): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 2590): Peer(9): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 2590): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2590): Peer(11): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 2590): Peer(12): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2590): Peer(13): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 2590): Peer(14): Note4-1 92:b6:86:43:73:1c,
,D/WifiP2pManager( 2590): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2590): Added service request
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 2590): Started service discovery
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: Thali Test (Galaxy A5)
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,D/dalvikvm( 2643): GC_CONCURRENT freed 323K, 3% free 16900K/17256K, paused 2ms+1ms, total 11ms
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751df7a0 rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2643): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 2590): Starting to Handshake
W/bt-btif ( 2643): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2643): bta_dm_pm_ssr:2, lat:1200
,I/BTHandshakeSocketThread( 2590): Creating BTHandshakeSocketThread
,I/        ( 2590): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1792","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1792","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT1792, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT1792, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2590): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread started
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2643): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
,I/BluetoothBondStateMachine( 2643): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2643): Entering PendingCommandState State
D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,W/BluetoothEventManager( 2657): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,E/BluetoothEventManager( 2657): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,E/bt-btif ( 2643): services_to_search = 3fffffff
,E/bt-btif ( 2643): ****************search UUID = 1200***********
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,E/bt-btif ( 2643): services_to_search = 3ffffffe
,E/bt-btif ( 2643): ****************search UUID = 0100***********
W/bt-btif ( 2643): new conn_srvc id:26, app_id:255
I/BTListenerThread( 2590): we got incoming connection
W/bt-btif ( 2643): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2643): bta_dm_pm_ssr:2, lat:1200
,I/BTHandshakeSocketThread( 2590): Creating BTHandshakeSocketThread
I/BTListenerThread( 2590): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread started
,I/BTListenerThread( 2590): got MESSAGE_READ 81 bytes.
,I/BTListenerThread( 2590): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5715","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2590): MESSAGE_WRITE 76 bytes.
,I/HS      ( 2590): Incoming connection Hand Shake finished for : motorola-XT1072_PT5715
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2590): Starting the connected thread incoming : true, motorola-XT1072_PT5715
,I/BtToSocketBase( 2590): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2590): Creating BTConnectedThread
,I/BtConnectorHelper( 2590): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2590): --DoOneRunRound started
,I/jxcore-log( 2590): 2015-12-02T20:14:07.490Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2590): 
,I/BtToRequestSocket( 2590): LocalHost address: localhost/127.0.0.1, port: 43412
,I/BtToRequestSocket( 2590): --DoOneRunRound ended
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,E/bt-btif ( 2643): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 2 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 3 uuid:0000110e-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 4 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 5 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 6 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 7 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 8 uuid:0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BluetoothBondStateMachine( 2643): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 2643): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 2643): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,I/BluetoothBondStateMachine( 2643): StableState(): Entering Off State
,W/BluetoothEventManager( 2657): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,E/BluetoothEventManager( 2657): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,I/        ( 2590): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT1661"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT1661"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT1661, peerAddress: 00:F4:6F:30:E0:6C
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT1661, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/jxcore-log( 2590): 2015-12-02T20:14:08.353Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:08.357Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:08.479Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:08.490Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:08.509Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:08.615Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:08.680Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:08.706Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:08.834Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:08.869Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:08.947Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:08.981Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:09.060Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:09.280Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:09.431Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:09.440Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:09.509Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:09.518Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:09.552Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:09.591Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:09.622Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:09.665Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:09.704Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:09.746Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:09.755Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:09.825Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:09.858Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:09.870Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:09.985Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:09.994Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:10.027Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:10.044Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:10.065Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:10.098Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:10.118Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:10.126Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:10.165Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:10.205Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:10.216Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:10.263Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:10.290Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:10.324Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:10.359Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:10.408Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:10.441Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:10.453Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:10.489Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:10.494Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:10.504Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:10.552Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2590): 
,I/wpa_supplicant( 3139): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,W/bt-btif ( 2643): dm_pm_timer expires
,W/bt-btif ( 2643): dm_pm_timer expires 0
,W/bt-btif ( 2643): proc dm_pm_timer expires
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 2643): invalid rfc slot id: 10
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BTConnectToThread( 2590): HandshakeFailed : SOCKET_DISCONNECTED
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread fully stopped
,I/CONNEC  ( 2590): Error: handshake: SOCKET_DISCONNECTED
,I/jxcore-log( 2590): 2015-12-02T20:14:12.994Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:12.995Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:13.031Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:13.032Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:13.033Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2590): 
I/jxcore-log( 2590): ---- round done--------
I/jxcore-log( 2590): 
I/jxcore-log( 2590): ---- gotta redo : 7C:F9:0E:51:18:22, try count now: 1
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): do fake peer & start
I/jxcore-log( 2590): 
I/jxcore-log( 2590): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 2590): 
I/jxcore-log( 2590): 2015-12-02T20:14:13.035Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2590): 
I/jxcore-log( 2590): 2015-12-02T20:14:13.035Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:13.035Z SendDataConnector.js: do connect now
I/jxcore-log( 2590): 
,I/        ( 2590): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/BTConnectToThread( 2590): Starting to connect
,W/BluetoothAdapter( 2590): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 2590): Connecting to null, at E0:DB:10:14:E2:C0
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:51:18:22 done with result: Connection to 7C:F9:0E:51:18:22 failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 2643): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 2590): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[259]}
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: Thali Test (Galaxy A5)
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751dfb18 rs_disc_pending=1
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,I/        ( 2590): Cleared service requests
,I/        ( 2590): Started peer discovery
,I/BluetoothBondStateMachine( 2643): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,I/BluetoothBondStateMachine( 2643): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,I/BluetoothBondStateMachine( 2643): Entering PendingCommandState State
,W/BluetoothEventManager( 2657): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,E/BluetoothEventManager( 2657): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,W/bt-btif ( 2643): dm_pm_timer expires
,W/bt-btif ( 2643): dm_pm_timer expires 1
,W/bt-btif ( 2643): proc dm_pm_timer expires
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2590): Found 13 peers.
,I/SS      ( 2590): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2590): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2590): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2590): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2590): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2590): Peer(6): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 2590): Peer(7): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2590): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2590): Peer(9): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2590): Peer(10): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 2590): Peer(11): A3-1 0a:ec:a9:50:75:42
I/SS      ( 2590): Peer(12): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 2590): Peer(13): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 2590): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2590): Added service request
,E/bt-btif ( 2643): services_to_search = 3fffffff
,E/bt-btif ( 2643): ****************search UUID = 1200***********
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,I/        ( 2590): Started service discovery
,E/bt-btif ( 2643): services_to_search = 3ffffffe
,E/bt-btif ( 2643): ****************search UUID = 0100***********
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751dfb18 rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2643): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2643): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2643): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2590): Starting to Handshake
,I/BTHandshakeSocketThread( 2590): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2590): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread started
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751dfb18 rs_disc_pending=1
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2590): got MESSAGE_READ 81 bytes.
,I/BTConnectToThread( 2590): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT785","ra":"E0:DB:10:14:E2:C0"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 2590): HandshakeOk : samsung-SM-N910C_PT785
,I/HS      ( 2590): Hand Shake finished outgoing for : samsung-SM-N910C_PT785
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2590): Starting the connected thread incoming : false, samsung-SM-N910C_PT785
,I/BtToSocketBase( 2590): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2590): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2590): mHTTPPort  set to : 52874
,I/BtConnectorHelper( 2590): Request socket is using : 52874
,I/BtToRequestSocket( 2590): Now accepting connections
,I/BtConnectorHelper( 2590): Calling ConnectionStatusUpdate with port :52874
,I/jxcore-log( 2590): 2015-12-02T20:14:20.753Z SendDataConnector.js: CLIENT connected to 52874, error: null
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:20.754Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2590): 
,I/BtToRequestSocket( 2590): incoming data from: /127.0.0.1, port: 52874
,I/BtToRequestSocket( 2590): Set local streams
,I/jxcore-log( 2590): 2015-12-02T20:14:20.773Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2590): 
,I/BtToRequestSocket( 2590): rin ended ---------------------------;
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2643): invalid rfc slot id: 6
I/BtToSocketBase( 2590): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2590): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2590): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT5715
I/BtToSocketBase( 2590): Stop ReceivingThread
I/BtToSocketBase( 2590): Stop SendingThread
I/BtToSocketBase( 2590): Close local in
I/BtToSocketBase( 2590): Close LocalOutputStream
I/BtToSocketBase( 2590): Close localHostSocket
I/BtToSocketBase( 2590): Close bt in
I/BtToSocketBase( 2590): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2590): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2590): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT5715
I/BtToSocketBase( 2590): Close bt in
I/BtToSocketBase( 2590): Close bt out
I/BtToSocketBase( 2590): Close bt socket
I/BtToSocketBase( 2590): Close bt out
,I/BtToSocketBase( 2590): Close bt socket
,I/jxcore-log( 2590): 2015-12-02T20:14:21.231Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:22.009Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2590): 
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,I/jxcore-log( 2590): 2015-12-02T20:14:22.282Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2590): 
,E/bt-btif ( 2643): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 9 uuid:0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BluetoothBondStateMachine( 2643): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 2643): Failed to remove device: E0:DB:10:14:E2:C0
,W/BluetoothEventManager( 2657): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,I/BluetoothBondStateMachine( 2643): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2643): StableState(): Entering Off State
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,E/BluetoothEventManager( 2657): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,I/jxcore-log( 2590): 2015-12-02T20:14:22.879Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:23.101Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:23.403Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2590): 
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-rfcomm( 2643): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
,W/bt-rfcomm( 2643): RFCOMM_DisconnectInd LCID:0x4c
,I/jxcore-log( 2590): 2015-12-02T20:14:24.085Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:24.802Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:25.302Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2590): 
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2590): 2015-12-02T20:14:25.626Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2590): 
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: XT1072
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,D/dalvikvm( 1172): GC_CONCURRENT freed 483K, 7% free 17901K/19188K, paused 9ms+1ms, total 26ms
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751dfb18 rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2643): dm_pm_timer expires
,W/bt-btif ( 2643): dm_pm_timer expires 0
,W/bt-btif ( 2643): proc dm_pm_timer expires
,I/jxcore-log( 2590): 2015-12-02T20:14:35.628Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:35.629Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:35.632Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:35.633Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:35.636Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2590): 
,I/BtToSocketBase( 2590): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 2590): Disconnect outgoing peer: samsung-SM-N910C_PT785
,I/BtToSocketBase( 2590): Stop ReceivingThread
,I/BtToSocketBase( 2590): Stop SendingThread
,I/BtToSocketBase( 2590): Close local in
,I/BtToSocketBase( 2590): Close LocalOutputStream
,I/BtToSocketBase( 2590): Close localHostSocket
,I/BtToSocketBase( 2590): Close bt in
,I/BtToSocketBase( 2590): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2590): Close bt out
,I/BtToSocketBase( 2590): Close bt socket
,I/BtToRequestSocket( 2590): Close server socket
,W/bt-btif ( 2643): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3139): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,I/wpa_supplicant( 3139): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/wpa_supplicant( 3139): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
I/wpa_supplicant( 3139): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 3139): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: Note4-1
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,I/jxcore-log( 2590): 2015-12-02T20:14:40.635Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:40.636Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2590): 
,I/wpa_supplicant( 3139): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2590): 2015-12-02T20:14:45.639Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:45.640Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:45.642Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:45.644Z SendDataConnector.js: do connect now
I/jxcore-log( 2590): 
,I/        ( 2590): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 2590): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 2590): Starting to connect
,W/BluetoothAdapter( 2590): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2643): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 2590): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[257]}
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: Note4-1
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,D/dalvikvm(  978): GC_CONCURRENT freed 406K, 3% free 17896K/18396K, paused 2ms+2ms, total 19ms
,I/        ( 2590): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT7328, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT7328, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,I/wpa_supplicant( 3139): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/ConnectivityService(  796): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  796): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  796): Attempting to switch to mobile
,D/ConnectivityService(  796): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  796): android_net_utils_resetConnections in env=0x76a3ef00 clazz=0x7c700001 iface=wlan0 mask=0x3
D/ConnectivityService(  796): resetConnections(wlan0, 3)
,I/jxcore-log( 2590): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): The Coordinator has disconnected!
I/jxcore-log( 2590): 
,V/NativeCrypto( 1112): Read error: ssl=0x79124520: I/O error during system call, Connection timed out
,V/NativeCrypto( 1112): SSL shutdown failed: ssl=0x79124520: I/O error during system call, Broken pipe
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,W/wpa_supplicant( 3139): wlan0: Failed to initiate AP scan
,D/Nat464Xlat(  796): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  796): handleInetConditionChange: no active default network - ignore
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2590): 
,D/WifiService(  796): setWifiEnabled: false pid=2590, uid=10108
,D/WifiService(  796): setWifiEnabled: true pid=2590, uid=10108
,E/WifiStateMachine(  796): scanCount==0 - aborting
,D/WifiController(  796): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 480ms
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,I/jxcore-log( 2590): Wifi toggled for connection repairment
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 2590): Wifi is DISABLED !!
I/        ( 2590): Stoping All
I/        ( 2590): Stopping services
,I/        ( 2590): Stopping services
,I/        ( 2590): Stop Bluetooth
I/        ( 2590): Stop Bluetooth
I/BTListenerThread( 2590): Stopped
E/bt-btif ( 2643): bta_jv_rfcomm_stop_server
I/BTConnectToThread( 2590): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btif ( 2643): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:13, channel:6
,W/bt-btif ( 2643): invalid rfc slot id: 13
,I/        ( 2590): Clearing local services failed, error code 2
I/        ( 2590): Clearing service requests failed, error code 2
I/        ( 2590): Stopping peer discovery failed, error code 2
I/CONNEC  ( 2590): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2590): 2015-12-02T20:14:51.010Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 2590): 
I/jxcore-log( 2590): 2015-12-02T20:14:51.011Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:51.011Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2590): 
,I/wpa_supplicant( 3139): P2P-FIND-STOPPED 
I/wpa_supplicant( 3139): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3139): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3139): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3139): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3139): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3139): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3139): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3139): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/wpa_supplicant( 3139): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/wpa_supplicant( 3139): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 3139): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  796): InitialState.processMessage what=4
,D/Tethering(  796): sendTetherStateChangedBroadcast 0, 0, 0
,W/Settings( 1854): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  978): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,D/WifiController(  796): DEFERRED_TOGGLE handled
,D/SoftapController(  182): Softap fwReload - Ok
D/CommandListener(  182): Setting iface cfg
,D/CommandListener(  182): Trying to bring down wlan0
,D/WifiMonitor(  796): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 3414): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3414): rfkill: Cannot open RFKILL control device
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751df428 rs_disc_pending=0
W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,D/Tethering(  796): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3414): rfkill: Cannot open RFKILL control device
,D/WifiConfigStore(  796): Loading config and enabling all networks
,W/Settings( 1854): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/CommandListener(  182): Setting iface cfg
,D/CommandListener(  182): Trying to bring up p2p0
,D/WifiMonitor(  796): startMonitoring(p2p0) with mConnected = true
I/WB      ( 2590): Wifi is now enabled !
I/        ( 2590): Stoping All
I/        ( 2590): Stopping services
I/        ( 2590): Stop Bluetooth
I/        ( 2590): Starting All
I/        ( 2590): Stopping services
I/        ( 2590): Starting services address: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT680"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@4262a4f8
I/        ( 2590): Stopping services
,I/        ( 2590): Starting services address: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT680"}
,I/        ( 2590): Add local service :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT680"}, length : 76
,I/        ( 2590): peerDiscoveryTimer timeout value:5001
I/        ( 2590): Stop Bluetooth
I/        ( 2590): StartBluetooth listener
,I/        ( 2590): StartBluetooth listener
,D/BluetoothManagerService(  796): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2590): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 2643): SOCK FLAG = 0 ***********************
I/BTListenerThread( 2590): starting to listen
,I/BTListenerThread( 2590): waiting to accept incoming Connection
,I/        ( 2590): Discovery state changed to Started.
,I/        ( 2590): Added local service
,I/        ( 2590): Cleared service requests
,I/        ( 2590): Stopped peer discovery
,I/        ( 2590): Started peer discovery
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/Tethering(  796): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  796): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  796): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/dalvikvm( 1188): GC_CONCURRENT freed 368K, 3% free 16741K/17140K, paused 30ms+1ms, total 58ms
,I/iu.Environment( 1295): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1295): num queued entries: 0
,I/Babel   ( 1854): connection state changed from CONNECTED to DISCONNECTED
,I/iu.UploadsManager( 1295): num updated entries: 0
,I/SystemUpdateService( 1295): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1295): onCreate
,D/SystemUpdateService( 1295): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.SyncManager( 1295): NEXT; no task
,I/SystemUpdateService( 1295): active receiver: enabled
,I/SystemUpdateService( 1295): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1295): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1295): now status is 0 (complete)
,I/SystemUpdateService( 1295): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1295): file has been verified
,I/SystemUpdateService( 1295): OTA package size = 2571501
,I/SystemUpdateService( 1295): showing system update notification
,D/SystemUpdateService( 1295): onDestroy
,D/ConnectivityService(  796): handleInetConditionChange: no active default network - ignore
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2590): 2015-12-02T20:14:56.012Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:14:56.013Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2590): 
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2590): Found 1 peers.
,I/SS      ( 2590): Peer(1): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2590): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2590): Added service request
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,D/dalvikvm( 2643): GC_CONCURRENT freed 417K, 3% free 16880K/17328K, paused 6ms+1ms, total 43ms
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: Note4-1
,D/dalvikvm( 1172): GC_CONCURRENT freed 413K, 7% free 17875K/19188K, paused 1ms+2ms, total 26ms
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 2590): Started service discovery
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService(  796): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2590): 2015-12-02T20:15:01.022Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:01.029Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:01.030Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:01.031Z SendDataConnector.js: do connect now
I/jxcore-log( 2590): 
,I/        ( 2590): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 2590): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 2590): Starting to connect
,W/BluetoothAdapter( 2590): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2643): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 2590): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[291]}
,I/wpa_supplicant( 3414): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [44:80:eb:7b:5a:05]: 7, f, 2205
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: XT1072
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,W/bt-btif ( 2643): new conn_srvc id:26, app_id:255
,I/BTListenerThread( 2590): we got incoming connection
W/bt-btif ( 2643): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2643): bta_dm_pm_ssr:2, lat:1200
,I/BTHandshakeSocketThread( 2590): Creating BTHandshakeSocketThread
I/BTListenerThread( 2590): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread started
,I/BTListenerThread( 2590): got MESSAGE_READ 81 bytes.
,I/BTListenerThread( 2590): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5715","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 2590): MESSAGE_WRITE 76 bytes.
,I/HS      ( 2590): Incoming connection Hand Shake finished for : motorola-XT1072_PT5715
I/BtConnectorHelper( 2590): Starting the connected thread incoming : true, motorola-XT1072_PT5715
I/BtToSocketBase( 2590): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2590): Creating BTConnectedThread
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 2590): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2590): --DoOneRunRound started
,I/jxcore-log( 2590): 2015-12-02T20:15:01.830Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2590): 
,I/BtToRequestSocket( 2590): LocalHost address: localhost/127.0.0.1, port: 43412
,I/BtToRequestSocket( 2590): --DoOneRunRound ended
,I/jxcore-log( 2590): 2015-12-02T20:15:02.279Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2590): 
,I/wpa_supplicant( 3414): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/jxcore-log( 2590): 2015-12-02T20:15:02.358Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:02.372Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:02.376Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:02.406Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:02.413Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2590): 
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [e0:db:10:14:e2:c0]: 7, f, 6109
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: Note4-1
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751dfb18 rs_disc_pending=1
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,I/        ( 2590): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT1028","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT1028","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT1028, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT1028, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751dfb18 rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2643): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 2590): Starting to Handshake
,W/bt-btif ( 2643): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2643): bta_dm_pm_ssr:2, lat:1200
,I/BTHandshakeSocketThread( 2590): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2590): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread started
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751dfb18 rs_disc_pending=1
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2643): dm_pm_timer expires
,W/bt-btif ( 2643): dm_pm_timer expires 0
,W/bt-btif ( 2643): proc dm_pm_timer expires
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751dfb18 rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,I/        ( 2590): Cleared service requests
,I/BTConnectToThread( 2590): got MESSAGE_READ 81 bytes.
,I/BTConnectToThread( 2590): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT785","ra":"E0:DB:10:14:E2:C0"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 2590): HandshakeOk : samsung-SM-N910C_PT785
,I/HS      ( 2590): Hand Shake finished outgoing for : samsung-SM-N910C_PT785
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2590): Starting the connected thread incoming : false, samsung-SM-N910C_PT785
,I/BtToSocketBase( 2590): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2590): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2590): mHTTPPort  set to : 38116
,I/BtConnectorHelper( 2590): Request socket is using : 38116
,I/BtToRequestSocket( 2590): Now accepting connections
,I/BtConnectorHelper( 2590): Calling ConnectionStatusUpdate with port :38116
,I/jxcore-log( 2590): 2015-12-02T20:15:09.849Z SendDataConnector.js: CLIENT connected to 38116, error: null
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:09.851Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2590): 
,I/BtToRequestSocket( 2590): incoming data from: /127.0.0.1, port: 38116
,I/BtToRequestSocket( 2590): Set local streams
,I/jxcore-log( 2590): 2015-12-02T20:15:09.867Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2590): 
,I/BtToRequestSocket( 2590): rin ended ---------------------------;
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 2590): Started peer discovery
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2590): Found 7 peers.
,I/SS      ( 2590): Peer(1): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 2590): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 2590): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 2590): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 2590): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 2590): Peer(6): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 2590): Peer(7): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 2590): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2590): Added service request
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3414): wlan0: Authentication with c0:ff:d4:d3:aa:48 timed out.
,I/wpa_supplicant( 3414): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/wpa_supplicant( 3414): wlan0: WPA: 4-Way Handshake failed - pre-shared key may be incorrect
,I/wpa_supplicant( 3414): wlan0: CTRL-EVENT-SSID-TEMP-DISABLED id=0 ssid="NG700" auth_failures=1 duration=10
,I/        ( 2590): Started service discovery
,W/bt-btif ( 2643): invalid rfc slot id: 14
,I/BtToSocketBase( 2590): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2590): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2590): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT5715
,I/BtToSocketBase( 2590): Stop ReceivingThread
,I/BtToSocketBase( 2590): Stop SendingThread
,I/BtToSocketBase( 2590): Close local in
,I/BtToSocketBase( 2590): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2590): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 2590): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT5715
,I/BtToSocketBase( 2590): Close LocalOutputStream
,I/BtToSocketBase( 2590): Close localHostSocket
,I/BtToSocketBase( 2590): Close bt in
I/BtToSocketBase( 2590): Close bt out
,I/BtToSocketBase( 2590): Close bt socket
,I/BtToSocketBase( 2590): Close bt in
,I/BtToSocketBase( 2590): Close bt out
,I/BtToSocketBase( 2590): Close bt socket
,I/jxcore-log( 2590): 2015-12-02T20:15:12.765Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2590): 
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751dfb18 rs_disc_pending=1
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2643): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
,W/bt-rfcomm( 2643): RFCOMM_DisconnectInd LCID:0x47
,D/ConnectivityService(  796): handleInetConditionChange: no active default network - ignore
,W/bt-btif ( 2643): dm_pm_timer expires
,W/bt-btif ( 2643): dm_pm_timer expires 0
,W/bt-btif ( 2643): proc dm_pm_timer expires
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 2590): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT7267"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT7267"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT7267, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT7267, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751df95c rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: XT1072
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,D/dalvikvm(  978): GC_CONCURRENT freed 394K, 3% free 17893K/18396K, paused 2ms+2ms, total 23ms
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751dfb18 rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2590): 2015-12-02T20:15:19.932Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:19.933Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:19.936Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:19.938Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:19.940Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2590): 
,I/BtToSocketBase( 2590): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2590): Disconnect outgoing peer: samsung-SM-N910C_PT785
,I/BtToSocketBase( 2590): Stop ReceivingThread
,I/BtToSocketBase( 2590): Stop SendingThread
,I/BtToSocketBase( 2590): Close local in
,I/BtToSocketBase( 2590): Close LocalOutputStream
I/BtToSocketBase( 2590): Close localHostSocket
,I/BtToSocketBase( 2590): Close bt in
,I/BtToSocketBase( 2590): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2590): Close bt out
I/BtToSocketBase( 2590): Close bt socket
,I/BtToRequestSocket( 2590): Close server socket
,W/bt-btif ( 2643): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,I/        ( 2590): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT2788, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT2788, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 2590): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1792","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1792","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT1792, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT1792, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: Note4-1
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,I/jxcore-log( 2590): 2015-12-02T20:15:24.969Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:24.970Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 2590): Cleared service requests
,I/        ( 2590): Started peer discovery
,I/jxcore-log( 2590): 2015-12-02T20:15:29.995Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:29.998Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:29.999Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:30.001Z SendDataConnector.js: do connect now
I/jxcore-log( 2590): 
,I/        ( 2590): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 2590): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 2590): Starting to connect
,W/BluetoothAdapter( 2590): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2643): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 2590): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[295]}
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2590): Found 11 peers.,
,I/SS      ( 2590): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 2590): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2590): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2590): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2590): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2590): Peer(6): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2590): Peer(7): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2590): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2590): Peer(9): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2590): Peer(10): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 2590): Peer(11): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 2590): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2590): Added service request
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [e0:db:10:14:e2:c0]: 6, 1d, 7d3
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: Note4-1
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,W/bt-btif ( 2643): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 2590): Starting to Handshake
,W/bt-btif ( 2643): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2643): bta_dm_pm_ssr:2, lat:1200
,I/BTHandshakeSocketThread( 2590): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2590): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread started
,I/BTConnectToThread( 2590): got MESSAGE_READ 81 bytes.
,I/BTConnectToThread( 2590): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT785","ra":"E0:DB:10:14:E2:C0"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 2590): HandshakeOk : samsung-SM-N910C_PT785
,I/HS      ( 2590): Hand Shake finished outgoing for : samsung-SM-N910C_PT785
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2590): Starting the connected thread incoming : false, samsung-SM-N910C_PT785
,I/BtToSocketBase( 2590): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2590): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2590): mHTTPPort  set to : 53438
,I/BtConnectorHelper( 2590): Request socket is using : 53438
,I/BtToRequestSocket( 2590): Now accepting connections
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,I/        ( 2590): Started service discovery
,I/BtConnectorHelper( 2590): Calling ConnectionStatusUpdate with port :53438
,I/jxcore-log( 2590): 2015-12-02T20:15:31.501Z SendDataConnector.js: CLIENT connected to 53438, error: null
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:31.503Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2590): 
,I/BtToRequestSocket( 2590): incoming data from: /127.0.0.1, port: 53438
,I/BtToRequestSocket( 2590): Set local streams
,I/jxcore-log( 2590): 2015-12-02T20:15:31.520Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2590): 
,I/BtToRequestSocket( 2590): rin ended ---------------------------;
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [44:80:eb:7b:5a:05]: 7, f, 2205
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: XT1072
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751dfb18 rs_disc_pending=1
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751df95c rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2643): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2643): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2643): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2590): we got incoming connection
,I/BTHandshakeSocketThread( 2590): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2590): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread started
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751df95c rs_disc_pending=1
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751df95c rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/BTListenerThread( 2590): got MESSAGE_READ 81 bytes.
,I/BTListenerThread( 2590): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5715","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2590): MESSAGE_WRITE 76 bytes.
,I/HS      ( 2590): Incoming connection Hand Shake finished for : motorola-XT1072_PT5715
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2590): Starting the connected thread incoming : true, motorola-XT1072_PT5715
,I/BtToSocketBase( 2590): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2590): Creating BTConnectedThread
,I/BtConnectorHelper( 2590): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2590): --DoOneRunRound started
,I/jxcore-log( 2590): 2015-12-02T20:15:33.899Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2590): 
,I/BtToRequestSocket( 2590): LocalHost address: localhost/127.0.0.1, port: 43412
,I/BtToRequestSocket( 2590): --DoOneRunRound ended
,I/jxcore-log( 2590): 2015-12-02T20:15:34.477Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:34.519Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:34.529Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:34.535Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:34.568Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2590): 
,I/wpa_supplicant( 3414): wlan0: CTRL-EVENT-SSID-REENABLED id=0 ssid="NG700"
,I/wpa_supplicant( 3414): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 2590): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT2788, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT2788, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,W/bt-btif ( 2643): dm_pm_timer expires
,W/bt-btif ( 2643): dm_pm_timer expires 0
,W/bt-btif ( 2643): proc dm_pm_timer expires
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751dfb18 rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [f8:95:c7:87:3c:51]: 0, 0, 0
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751df95c rs_disc_pending=1
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3414): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/        ( 2590): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT7328, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT7328, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2590): 
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 2643): dm_pm_timer expires
W/bt-btif ( 2643): dm_pm_timer expires 1
,W/bt-btif ( 2643): proc dm_pm_timer expires
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751df428 rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,D/ConnectivityService(  796): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2590): 2015-12-02T20:15:41.574Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:41.575Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:41.580Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:41.583Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:41.585Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2590): 
,I/BtToSocketBase( 2590): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 2590): Disconnect outgoing peer: samsung-SM-N910C_PT785
,I/BtToSocketBase( 2590): Stop ReceivingThread
,I/BtToSocketBase( 2590): Stop SendingThread
,I/BtToSocketBase( 2590): Close local in
,I/BtToSocketBase( 2590): Close LocalOutputStream
,I/BtToSocketBase( 2590): Close localHostSocket
,I/BtToSocketBase( 2590): Close bt in
,I/BtToSocketBase( 2590): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2590): Close bt out
,I/BtToSocketBase( 2590): Close bt socket
,I/BtToRequestSocket( 2590): Close server socket
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2643): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=6
,I/BluetoothBondStateMachine( 2643): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 12 NewState: 11
,I/BluetoothBondStateMachine( 2643): Entering PendingCommandState State
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751df428 rs_disc_pending=1
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,E/bt-btif ( 2643): services_to_search = 3fffffff
,E/bt-btif ( 2643): ****************search UUID = 1200***********
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,E/bt-btif ( 2643): services_to_search = 3ffffffe
,E/bt-btif ( 2643): ****************search UUID = 0100***********
,I/wpa_supplicant( 3414): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,E/bt-btif ( 2643): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 2 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 3 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 4 uuid:0000110e-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 9 uuid:0bbfc6ef-14cc-4ab2-af63-b92e887227ae
I/BluetoothBondStateMachine( 2643): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
D/BluetoothAdapterProperties( 2643): Removing bonded device:F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2643): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2643): StableState(): Entering Off State
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=5
,W/BluetoothEventManager( 2657): showUnbondMessage: Not displaying any message for reason: 0
,D/BluetoothMap( 2657): getConnectedDevices()
,D/BluetoothMap( 2657): getConnectionState(F8:95:C7:87:3C:51)
,D/MapProfile( 2657): getConnectionStatus: status is: 0
,W/bt-btif ( 2643): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,W/bt-btif ( 2643): invalid rfc slot id: 16
,I/BtToSocketBase( 2590): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2590): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2590): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT5715
,I/BtToSocketBase( 2590): Stop ReceivingThread
I/BtToSocketBase( 2590): Stop SendingThread
,I/BtToSocketBase( 2590): Close local in
,I/BtToSocketBase( 2590): Close LocalOutputStream
,I/BtToSocketBase( 2590): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2590): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 2590): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT5715
I/BtToSocketBase( 2590): Close localHostSocket
,I/BtToSocketBase( 2590): Close bt in
I/BtToSocketBase( 2590): Close bt in
,I/BtToSocketBase( 2590): Close bt out
I/BtToSocketBase( 2590): Close bt out
,I/BtToSocketBase( 2590): Close bt socket
,I/BtToSocketBase( 2590): Close bt socket
,I/jxcore-log( 2590): 2015-12-02T20:15:44.998Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2590): 
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751df95c rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2643): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
,W/bt-rfcomm( 2643): RFCOMM_DisconnectInd LCID:0x49
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2590): 
,W/bt-btif ( 2643): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2643): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2643): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2590): we got incoming connection
,I/BTHandshakeSocketThread( 2590): Creating BTHandshakeSocketThread
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTListenerThread( 2590): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread started
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: Note4-1
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=5
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=5
,I/BTListenerThread( 2590): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 2590): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 2590): MESSAGE_WRITE 76 bytes.
I/HS      ( 2590): Incoming connection Hand Shake finished for : LGE-LG-H815_PT2788
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 2590): Starting the connected thread incoming : true, LGE-LG-H815_PT2788
I/BtToSocketBase( 2590): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2590): Creating BTConnectedThread
I/BtConnectorHelper( 2590): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2590): --DoOneRunRound started
,I/jxcore-log( 2590): 2015-12-02T20:15:46.113Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2590): 
,I/BtToRequestSocket( 2590): LocalHost address: localhost/127.0.0.1, port: 43412
,I/BtToRequestSocket( 2590): --DoOneRunRound ended
,I/        ( 2590): Cleared service requests
,I/        ( 2590): Started peer discovery
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751df95c rs_disc_pending=1
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2590): 2015-12-02T20:15:46.612Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:46.613Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:46.878Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:46.917Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:46.922Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:46.930Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:46.975Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:46.986Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:46.990Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:47.019Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:47.047Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:47.052Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:47.090Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:47.128Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:47.200Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:47.204Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:47.218Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:47.248Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:47.269Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:47.273Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:47.282Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:47.318Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:47.353Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 2590): 
,W/wpa_supplicant( 3414): wlan0: WPA: Failed to set PTK to the driver (alg=3 keylen=16 bssid=c0:ff:d4:d3:aa:48)
,I/wpa_supplicant( 3414): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=1 locally_generated=1
,I/wpa_supplicant( 3414): wlan0: WPA: 4-Way Handshake failed - pre-shared key may be incorrect
,I/wpa_supplicant( 3414): wlan0: CTRL-EVENT-SSID-TEMP-DISABLED id=0 ssid="NG700" auth_failures=2 duration=20
,I/wpa_supplicant( 3414): wlan0: CTRL-EVENT-ASSOC-REJECT status_code=1
,E/wpa_supplicant( 3414): current_ssid == NULL
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/SupplicantStateTracker(  796): Failed to authenticate, disabling network 0
,I/jxcore-log( 2590): 2015-12-02T20:15:47.440Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 2590): 
,I/SS      ( 2590): Found 11 peers.
I/SS      ( 2590): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2590): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2590): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2590): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2590): Peer(5): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 2590): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2590): Peer(7): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2590): Peer(8): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2590): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2590): Peer(10): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 2590): Peer(11): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 2590): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2590): Added service request
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2590): 2015-12-02T20:15:47.533Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:47.583Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:47.800Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:47.858Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:47.893Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 2590): 
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2590): 2015-12-02T20:15:47.934Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:47.951Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:47.955Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:47.963Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:47.995Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:48.027Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:48.046Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:48.092Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 2590): 
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2590): 2015-12-02T20:15:48.466Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 2590): 
,I/        ( 2590): Started service discovery
,I/jxcore-log( 2590): 2015-12-02T20:15:48.734Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:48.738Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:49.151Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:49.470Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:49.509Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 2590): 
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: XT1072
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=5
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=5
,I/jxcore-log( 2590): 2015-12-02T20:15:49.809Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:49.813Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2590): 
,D/ConnectivityService(  796): NetTransition Wakelock for ConnectedState released by timeout
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3414): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2590): 2015-12-02T20:15:51.637Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:51.638Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:51.639Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:51.641Z SendDataConnector.js: do connect now
I/jxcore-log( 2590): 
,I/        ( 2590): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 2590): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 2590): Starting to connect
,W/BluetoothAdapter( 2590): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2643): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 2590): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[302]}
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751df428 rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: Note4-1
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=5
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=5
,D/dalvikvm(  978): GC_CONCURRENT freed 382K, 3% free 17897K/18396K, paused 2ms+1ms, total 15ms
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751dfb18 rs_disc_pending=1
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751df428 rs_disc_pending=1
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751dfb18 rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2643): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2643): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2643): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2590): Starting to Handshake
,I/BTHandshakeSocketThread( 2590): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2590): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread started
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751dfb18 rs_disc_pending=1
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2590): got MESSAGE_READ 81 bytes.
,I/BTConnectToThread( 2590): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT785","ra":"E0:DB:10:14:E2:C0"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 2590): HandshakeOk : samsung-SM-N910C_PT785
I/HS      ( 2590): Hand Shake finished outgoing for : samsung-SM-N910C_PT785
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread fully stopped
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2590): 
,D/WifiService(  796): setWifiEnabled: false pid=2590, uid=10108
,D/WifiService(  796): setWifiEnabled: true pid=2590, uid=10108
,D/WifiController(  796): WifiController msg { when=-1ms what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 470ms
,I/jxcore-log( 2590): Wifi toggled for connection repairment
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
I/BtConnectorHelper( 2590): Starting the connected thread incoming : false, samsung-SM-N910C_PT785
I/BtToSocketBase( 2590): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2590): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2590): mHTTPPort  set to : 46787
,I/BtConnectorHelper( 2590): Request socket is using : 46787
,I/BtToRequestSocket( 2590): Now accepting connections
,W/bt-btif ( 2643): dm_pm_timer expires
,W/bt-btif ( 2643): dm_pm_timer expires 0
,W/bt-btif ( 2643): proc dm_pm_timer expires
,I/BtConnectorHelper( 2590): Calling ConnectionStatusUpdate with port :46787
,I/jxcore-log( 2590): 2015-12-02T20:15:56.433Z SendDataConnector.js: CLIENT connected to 46787, error: null
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:56.435Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2590): 
,I/BtToRequestSocket( 2590): incoming data from: /127.0.0.1, port: 46787
,I/BtToRequestSocket( 2590): Set local streams
,I/jxcore-log( 2590): 2015-12-02T20:15:56.452Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2590): 
,I/BtToRequestSocket( 2590): rin ended ---------------------------;
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: XT1072
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=5
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=5
,D/WifiController(  796): DEFERRED_TOGGLE handled
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751dfb18 rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2643): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2643): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2643): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2590): we got incoming connection
,I/BTHandshakeSocketThread( 2590): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2590): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread started
,I/BTListenerThread( 2590): got MESSAGE_READ 81 bytes.
,I/BTListenerThread( 2590): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5715","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2590): MESSAGE_WRITE 76 bytes.
,I/HS      ( 2590): Incoming connection Hand Shake finished for : motorola-XT1072_PT5715
,I/BtConnectorHelper( 2590): Starting the connected thread incoming : true, motorola-XT1072_PT5715
I/BtToSocketBase( 2590): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2590): Creating BTConnectedThread
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2590): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2590): --DoOneRunRound started
,I/jxcore-log( 2590): 2015-12-02T20:15:57.242Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2590): 
,I/BtToRequestSocket( 2590): LocalHost address: localhost/127.0.0.1, port: 43412
,I/BtToRequestSocket( 2590): --DoOneRunRound ended
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751dfb18 rs_disc_pending=1
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,E/WifiStateMachine(  796): scanCount==0 - aborting
,I/WB      ( 2590): Wifi is DISABLED !!
,I/        ( 2590): Stoping All
I/        ( 2590): Stopping services
,I/        ( 2590): Stopping services
,I/        ( 2590): Stop Bluetooth
I/        ( 2590): Stop Bluetooth
,I/BTListenerThread( 2590): Stopped
,E/bt-btif ( 2643): bta_jv_rfcomm_stop_server
,I/        ( 2590): Clearing local services failed, error code 2
,I/        ( 2590): Clearing service requests failed, error code 2
,I/        ( 2590): Stopping peer discovery failed, error code 2
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,I/jxcore-log( 2590): 2015-12-02T20:15:57.737Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:57.743Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2590): 
,I/wpa_supplicant( 3414): P2P-FIND-STOPPED 
I/wpa_supplicant( 3414): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3414): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 3414): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3414): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 3414): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3414): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3414): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3414): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 3414): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3414): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3414): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/wpa_supplicant( 3414): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/jxcore-log( 2590): 2015-12-02T20:15:57.788Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2590): 
,D/dalvikvm(  796): GC_CONCURRENT freed 2124K, 52% free 26780K/55504K, paused 47ms+9ms, total 123ms
,I/jxcore-log( 2590): 2015-12-02T20:15:57.859Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:57.861Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:15:57.869Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2590): 
,I/wpa_supplicant( 3414): p2p0: CTRL-EVENT-TERMINATING 
,D/Tethering(  796): InitialState.processMessage what=4
,D/Tethering(  796): sendTetherStateChangedBroadcast 0, 0, 0
,I/wpa_supplicant( 3414): wlan0: CTRL-EVENT-TERMINATING 
,W/Settings( 1854): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  978): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/SoftapController(  182): Softap fwReload - Ok
D/CommandListener(  182): Setting iface cfg
,D/CommandListener(  182): Trying to bring down wlan0
,D/WifiMonitor(  796): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 3568): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3568): rfkill: Cannot open RFKILL control device
,D/Tethering(  796): sendTetherStateChangedBroadcast 1, 0, 0
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3568): rfkill: Cannot open RFKILL control device
,D/WifiConfigStore(  796): Loading config and enabling all networks
,W/Settings( 1854): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/CommandListener(  182): Setting iface cfg
,D/CommandListener(  182): Trying to bring up p2p0
,D/WifiMonitor(  796): startMonitoring(p2p0) with mConnected = true
I/WB      ( 2590): Wifi is now enabled !
I/        ( 2590): Stoping All
I/        ( 2590): Stopping services
I/        ( 2590): Stop Bluetooth
I/        ( 2590): Starting All
I/        ( 2590): Stopping services
I/        ( 2590): Starting services address: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT680"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@4262a4f8
I/        ( 2590): Stopping services
,I/        ( 2590): Starting services address: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT680"}
I/        ( 2590): Add local service :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT680"}, length : 76
,I/        ( 2590): peerDiscoveryTimer timeout value:5420
I/        ( 2590): Stop Bluetooth
I/        ( 2590): StartBluetooth listener
,I/        ( 2590): StartBluetooth listener
D/BluetoothManagerService(  796): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2590): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 2643): SOCK FLAG = 0 ***********************
I/BTListenerThread( 2590): starting to listen
I/BTListenerThread( 2590): waiting to accept incoming Connection
,I/        ( 2590): Discovery state changed to Started.
,W/wpa_supplicant( 3568): wlan0: Failed to initiate AP scan
,I/        ( 2590): Added local service
,I/        ( 2590): Cleared service requests
,I/        ( 2590): Stopped peer discovery
,I/        ( 2590): Starting peer discovery failed, error code 0
,W/bt-btif ( 2643): invalid rfc slot id: 18
,I/BtToSocketBase( 2590): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2590): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2590): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT2788
I/BtToSocketBase( 2590): Stop ReceivingThread
I/BtToSocketBase( 2590): Stop SendingThread
I/BtToSocketBase( 2590): Close local in
I/BtToSocketBase( 2590): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2590): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2590): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT2788
I/BtToSocketBase( 2590): Close localHostSocket
I/BtToSocketBase( 2590): Close bt in
I/BtToSocketBase( 2590): Close bt out
I/BtToSocketBase( 2590): Close LocalOutputStream
I/BtToSocketBase( 2590): Close bt in
I/BtToSocketBase( 2590): Close bt out
I/BtToSocketBase( 2590): Close bt socket
,I/BtToSocketBase( 2590): Close bt socket
,I/jxcore-log( 2590): 2015-12-02T20:16:00.670Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2590): 
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751dfb18 rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2643): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
,W/bt-rfcomm( 2643): RFCOMM_DisconnectInd LCID:0x4c
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/wpa_supplicant( 3568): wlan0: Failed to initiate AP scan
,W/bt-btif ( 2643): dm_pm_timer expires
,W/bt-btif ( 2643): dm_pm_timer expires 0,
,W/bt-btif ( 2643): proc dm_pm_timer expires
,W/bt-btif ( 2643): dm_pm_timer expires
,W/bt-btif ( 2643): dm_pm_timer expires 1
,W/bt-btif ( 2643): proc dm_pm_timer expires
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751df95c rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: G4-1
,D/dalvikvm( 2643): GC_CONCURRENT freed 388K, 3% free 16880K/17328K, paused 11ms+2ms, total 35ms
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=5
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=5
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751df95c rs_disc_pending=1
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751dfb18 rs_disc_pending=1
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2590): 2015-12-02T20:16:06.554Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:16:06.554Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:16:06.555Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:16:06.562Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:16:06.567Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:16:06.569Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2590): 
,I/BtConnectorHelper( 2590): Disconnect outgoing peer: E0:DB:10:14:E2:C0
,I/BtToSocketBase( 2590): Stop ReceivingThread
I/BtToSocketBase( 2590): Stop SendingThread
,I/BtToSocketBase( 2590): Close local in
,I/BtToSocketBase( 2590): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2590): Close LocalOutputStream
I/BtToSocketBase( 2590): Close localHostSocket
,I/BtToSocketBase( 2590): Close bt in
,I/BtToSocketBase( 2590): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2590): Close bt out
I/BtToSocketBase( 2590): Close bt socket
,I/BtToRequestSocket( 2590): Close server socket
,I/jxcore-log( 2590): 2015-12-02T20:16:06.590Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): ---- round done--------
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): ---- gotta redo : E0:DB:10:14:E2:C0, try count now: 1
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): do fake peer & start
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:16:06.597Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:16:06.598Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:16:06.599Z SendDataConnector.js: do connect now
I/jxcore-log( 2590): 
,I/        ( 2590): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 2590): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/jxcore-log( 2590): 2015-12-02T20:16:06.611Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:14:E2:C0 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
I/BTConnectToThread( 2590): Starting to connect
,W/BluetoothAdapter( 2590): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2643): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 2590): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[299]}
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751dfb18 rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0,
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2643): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=5
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=5
,W/bt-btif ( 2643): invalid rfc slot id: 19
,I/BtToSocketBase( 2590): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2590): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2590): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT5715
I/BtToSocketBase( 2590): Stop ReceivingThread
I/BtToSocketBase( 2590): Stop SendingThread
I/BtToSocketBase( 2590): Close local in
,I/BtToSocketBase( 2590): Close LocalOutputStream
I/BtToSocketBase( 2590): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2590): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2590): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT5715
I/BtToSocketBase( 2590): Close localHostSocket
I/BtToSocketBase( 2590): Close bt in
,I/BtToSocketBase( 2590): Close bt out
I/BtToSocketBase( 2590): Close bt in
I/BtToSocketBase( 2590): Close bt socket
I/BtToSocketBase( 2590): Close bt out
,I/BtToSocketBase( 2590): Close bt socket
,I/jxcore-log( 2590): 2015-12-02T20:16:08.165Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2590): 
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,W/bt-rfcomm( 2643): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
,W/bt-rfcomm( 2643): RFCOMM_DisconnectInd LCID:0x44
,I/BluetoothBondStateMachine( 2643): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=5
,I/BluetoothBondStateMachine( 2643): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 12 NewState: 11
,I/BluetoothBondStateMachine( 2643): Entering PendingCommandState State
,D/dalvikvm( 2657): GC_CONCURRENT freed 419K, 3% free 16808K/17256K, paused 45ms+0ms, total 53ms
,E/bt-btif ( 2643): services_to_search = 3fffffff
,E/bt-btif ( 2643): ****************search UUID = 1200***********
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751dfb18 rs_disc_pending=1
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751deef4 rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,E/bt-btif ( 2643): services_to_search = 3ffffffe
,E/bt-btif ( 2643): ****************search UUID = 0100***********
,W/bt-btif ( 2643): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2643): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2643): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2590): Starting to Handshake
,I/BTHandshakeSocketThread( 2590): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2590): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread started
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751deef4 rs_disc_pending=1
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: Note4-1
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=5
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=5
,I/BTConnectToThread( 2590): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 2590): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT7503","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2590): HandshakeOk : LGE-LG-D722_PT7503
I/HS      ( 2590): Hand Shake finished outgoing for : LGE-LG-D722_PT7503
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 2590): Starting the connected thread incoming : false, LGE-LG-D722_PT7503
I/BtToSocketBase( 2590): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2590): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 2590): mHTTPPort  set to : 59606
,I/BtConnectorHelper( 2590): Request socket is using : 59606
,I/BtToRequestSocket( 2590): Now accepting connections
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [f8:95:c7:87:3c:51]: 7, f, 2205
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=5
,E/bt-btif ( 2643): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 2 uuid:00001106-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 9 uuid:0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BluetoothBondStateMachine( 2643): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2643): Removing bonded device:F8:95:C7:87:85:54
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,I/BluetoothBondStateMachine( 2643): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2643): StableState(): Entering Off State
,W/BluetoothEventManager( 2657): showUnbondMessage: Not displaying any message for reason: 0
,D/BluetoothMap( 2657): getConnectedDevices()
,D/BluetoothMap( 2657): getConnectionState(F8:95:C7:87:85:54)
,D/MapProfile( 2657): getConnectionStatus: status is: 0
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtConnectorHelper( 2590): Calling ConnectionStatusUpdate with port :59606
,I/jxcore-log( 2590): 2015-12-02T20:16:11.267Z SendDataConnector.js: CLIENT connected to 59606, error: null
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:16:11.267Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2590): 
I/BtToRequestSocket( 2590): incoming data from: /127.0.0.1, port: 59606
,I/BtToRequestSocket( 2590): Set local streams
,I/BtToRequestSocket( 2590): rin ended ---------------------------;
,I/jxcore-log( 2590): 2015-12-02T20:16:11.270Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2590): 
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751df428 rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2590): 2015-12-02T20:16:12.037Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:16:12.209Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:16:12.505Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2590): 
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: XT1072
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,I/jxcore-log( 2590): 2015-12-02T20:16:12.743Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2590): 
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,I/jxcore-log( 2590): 2015-12-02T20:16:12.879Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:16:12.974Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2590): 
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751df428 rs_disc_pending=1
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2590): 2015-12-02T20:16:13.055Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:16:13.138Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:16:13.251Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2590): 
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751deef4 rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2643): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,I/BluetoothBondStateMachine( 2643): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,I/BluetoothBondStateMachine( 2643): Entering PendingCommandState State
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btif ( 2643): services_to_search = 3fffffff
,E/bt-btif ( 2643): ****************search UUID = 1200***********
,W/bt-btif ( 2643): dm_pm_timer expires
,W/bt-btif ( 2643): dm_pm_timer expires 0
,W/bt-btif ( 2643): proc dm_pm_timer expires
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,E/bt-btif ( 2643): services_to_search = 3ffffffe
,E/bt-btif ( 2643): ****************search UUID = 0100***********
,W/bt-btif ( 2643): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2643): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2643): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2590): we got incoming connection
,I/BTHandshakeSocketThread( 2590): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2590): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread started
,I/BTListenerThread( 2590): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 2590): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2590): MESSAGE_WRITE 76 bytes.
,I/HS      ( 2590): Incoming connection Hand Shake finished for : LGE-LG-H815_PT2788
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2590): Starting the connected thread incoming : true, LGE-LG-H815_PT2788
,I/BtToSocketBase( 2590): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2590): Creating BTConnectedThread
,I/BtConnectorHelper( 2590): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2590): --DoOneRunRound started
,I/BtToRequestSocket( 2590): LocalHost address: localhost/127.0.0.1, port: 43412
,I/jxcore-log( 2590): 2015-12-02T20:16:17.898Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2590): 
,I/BtToRequestSocket( 2590): --DoOneRunRound ended
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,E/bt-btif ( 2643): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 2 uuid:00001116-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 3 uuid:0000112d-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 4 uuid:0000110e-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 9 uuid:0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BluetoothBondStateMachine( 2643): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2643): Failed to remove device: F8:95:C7:87:3C:51
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,I/BluetoothBondStateMachine( 2643): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2643): StableState(): Entering Off State
,W/BluetoothEventManager( 2657): showUnbondMessage: Not displaying any message for reason: 0
,D/BluetoothMap( 2657): getConnectedDevices()
,D/BluetoothMap( 2657): getConnectionState(F8:95:C7:87:3C:51)
,D/MapProfile( 2657): getConnectionStatus: status is: 0
,I/jxcore-log( 2590): 2015-12-02T20:16:18.376Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:16:18.379Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:16:18.383Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:16:18.390Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:16:18.475Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2590): 
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751deef4 rs_disc_pending=1
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2590): 2015-12-02T20:16:18.576Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2590): 
,I/wpa_supplicant( 3568): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3568): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 3568): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3568): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  796): scanCount==0 - aborting
,D/WifiStateMachine(  796): VerifyingLinkState enter
,D/WifiStateMachine(  796): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  796): CaptivePortalCheckState enter
,D/WifiStateMachine(  796): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  796): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  796): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  796): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  796): Unexpected mtu value: android.net.wifi.WifiStateTracker@42b7ddb0
,D/Nat464Xlat(  796): requiresClat: netType=1, hasIPv4Address=true
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Coordinator is now connected to the server!
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService(  796): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  796):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  796): requiresClat: netType=1, hasIPv4Address=true
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751df428 rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2643): dm_pm_timer expires
,W/bt-btif ( 2643): dm_pm_timer expires 1
,W/bt-btif ( 2643): proc dm_pm_timer expires
,I/jxcore-log( 2590): 2015-12-02T20:16:23.252Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:16:23.252Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:16:23.258Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:16:23.259Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:16:23.262Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2590): 
,I/BtToSocketBase( 2590): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 2590): Disconnect outgoing peer: LGE-LG-D722_PT7503
,I/BtToSocketBase( 2590): Stop ReceivingThread
,I/BtToSocketBase( 2590): Stop SendingThread
,I/BtToSocketBase( 2590): Close local in
,I/BtToSocketBase( 2590): Close LocalOutputStream
,I/BtToSocketBase( 2590): Close localHostSocket
,I/BtToSocketBase( 2590): Close bt in
,I/BtToSocketBase( 2590): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2590): Close bt out
,I/BtToSocketBase( 2590): Close bt socket
,I/BtToRequestSocket( 2590): Close server socket
,D/Tethering(  796): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  796): NoActiveNetworkState{ when=-5ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/iu.Environment( 1295): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SystemUpdateService( 1295): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/iu.UploadsManager( 1295): num queued entries: 0
,I/iu.UploadsManager( 1295): num updated entries: 0
,I/iu.SyncManager( 1295): NEXT; no task
,D/SystemUpdateService( 1295): onCreate
,D/SystemUpdateService( 1295): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1295): active receiver: enabled
,I/SystemUpdateService( 1295): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1295): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1295): now status is 0 (complete)
I/SystemUpdateService( 1295): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1295): file has been verified
,I/SystemUpdateService( 1295): OTA package size = 2571501
,I/SystemUpdateService( 1295): showing system update notification
,D/SystemUpdateService( 1295): onDestroy
,W/bt-btif ( 2643): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2590): Found 3 peers.
,I/SS      ( 2590): Peer(1): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2590): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 2590): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 2590): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2590): Added service request
,W/bt-btif ( 2643): dm_pm_timer expires
,W/bt-btif ( 2643): dm_pm_timer expires 0
,W/bt-btif ( 2643): proc dm_pm_timer expires
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,I/        ( 2590): Started service discovery
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2590): 2015-12-02T20:16:28.262Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:16:28.263Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:16:33.273Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:16:33.274Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:16:33.275Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:16:33.277Z SendDataConnector.js: do connect now
I/jxcore-log( 2590): 
,I/        ( 2590): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 2590): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2590): Starting to connect
,W/BluetoothAdapter( 2590): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2643): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 2590): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[301]}
,I/        ( 2590): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT2788, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT2788, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,D/CaptivePortalTracker(  796): DelayedCaptiveCheckState{ when=-6ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  796): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  796): Checking http://216.58.209.46/generate_204
,I/        ( 2590): Cleared service requests
,I/        ( 2590): Started peer discovery
,I/ActivityManager(  796): Waited long enough for: ServiceRecord{437d7fd0 u0 com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService}
,W/Babel_NetworkConnectionCheckingService( 1854): IO exceptions, probably not a captive portal 
,W/Babel_NetworkConnectionCheckingService( 1854): java.net.SocketTimeoutException
W/Babel_NetworkConnectionCheckingService( 1854): 	at java.net.PlainSocketImpl.read(PlainSocketImpl.java:491)
W/Babel_NetworkConnectionCheckingService( 1854): 	at java.net.PlainSocketImpl.access$000(PlainSocketImpl.java:46)
W/Babel_NetworkConnectionCheckingService( 1854): 	at java.net.PlainSocketImpl$PlainSocketInputStream.read(PlainSocketImpl.java:240)
W/Babel_NetworkConnectionCheckingService( 1854): 	at java.io.InputStream.read(InputStream.java:162)
W/Babel_NetworkConnectionCheckingService( 1854): 	at java.io.BufferedInputStream.fillbuf(BufferedInputStream.java:142)
W/Babel_NetworkConnectionCheckingService( 1854): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:227)
W/Babel_NetworkConnectionCheckingService( 1854): 	at com.android.okhttp.internal.Util.readAsciiLine(Util.java:316)
W/Babel_NetworkConnectionCheckingService( 1854): 	at com.android.okhttp.internal.http.RawHeaders.fromBytes(RawHeaders.java:308)
W/Babel_NetworkConnectionCheckingService( 1854): 	at com.android.okhttp.internal.http.HttpTransport.readResponseHeaders(HttpTransport.java:135)
W/Babel_NetworkConnectionCheckingService( 1854): 	at com.android.okhttp.internal.http.HttpEngine.readResponse(HttpEngine.java:644)
W/Babel_NetworkConnectionCheckingService( 1854): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:347)
W/Babel_NetworkConnectionCheckingService( 1854): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:296)
W/Babel_NetworkConnectionCheckingService( 1854): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:179)
W/Babel_NetworkConnectionCheckingService( 1854): 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
W/Babel_NetworkConnectionCheckingService( 1854): 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
W/Babel_NetworkConnectionCheckingService( 1854): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/Babel_NetworkConnectionCheckingService( 1854): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel_NetworkConnectionCheckingService( 1854): 	at android.os.Looper.loop(Looper.java:136)
W/Babel_NetworkConnectionCheckingService( 1854): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Babel   ( 1854): connection state changed from DISCONNECTED to CONNECTED
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2590): Found 7 peers.
,I/SS      ( 2590): Peer(1): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2590): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2590): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2590): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2590): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2590): Peer(6): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 2590): Peer(7): A5-1 7e:f9:0e:37:96:ac
,D/WifiP2pManager( 2590): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2590): Added service request
,D/CaptivePortalTracker(  796): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  796): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  796): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  796): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  796): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/        ( 2590): Started service discovery
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751df428 rs_disc_pending=1
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 2643): invalid rfc slot id: 22
W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,I/BtToSocketBase( 2590): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2590): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2590): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT2788
I/BtToSocketBase( 2590): Stop ReceivingThread
,I/BtToSocketBase( 2590): Stop SendingThread
,I/BtToSocketBase( 2590): Close local in
,I/BtToSocketBase( 2590): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2590): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 2590): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT2788
,I/BtToSocketBase( 2590): Close LocalOutputStream
,I/BtToSocketBase( 2590): Close localHostSocket
I/BtToSocketBase( 2590): Close bt in
,I/BtToSocketBase( 2590): Close bt out
,I/BtToSocketBase( 2590): Close bt socket
,I/BtToSocketBase( 2590): Close bt in
,I/BtToSocketBase( 2590): Close bt out
,I/BtToSocketBase( 2590): Close bt socket
,I/jxcore-log( 2590): 2015-12-02T20:16:50.405Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2590): 
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,W/bt-l2cap( 2643): L2CAP - holding ACL for unknown handle:15 ls:0 cid:1 opcode:10 cur count:0
,W/bt-l2cap( 2643): L2CAP HOLD TIMEOUT
,W/bt-l2cap( 2643): L2CAP HOLD TIMEOUT
,E/bt-l2cap( 2643): L2CAP - rcvd ACL for unknown handle:15 ls:65535 cid:1 opcode:10 cur count:0
,W/bt-l2cap( 2643): L2CAP - holding ACL for unknown handle:15 ls:0 cid:1 opcode:2 cur count:0
,D/ConnectivityService(  796): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,W/bt-l2cap( 2643): L2CAP HOLD TIMEOUT
,W/bt-l2cap( 2643): L2CAP HOLD TIMEOUT
,E/bt-l2cap( 2643): L2CAP - rcvd ACL for unknown handle:15 ls:65535 cid:1 opcode:2 cur count:0
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3568): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,I/wpa_supplicant( 3568): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/bt-btif ( 2643): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:1, scn:0
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 2643): invalid rfc slot id: 25
,I/BTConnectToThread( 2590): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2590): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2590): 2015-12-02T20:17:21.180Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:17:21.182Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:17:21.184Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2590): 
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/dalvikvm(  978): GC_CONCURRENT freed 385K, 3% free 17900K/18380K, paused 3ms+3ms, total 25ms
,I/jxcore-log( 2590): 2015-12-02T20:17:26.191Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:17:26.192Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2590): 
,I/        ( 2590): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1792","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1792","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT1792, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT1792, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 2590): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5728"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5728"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5728, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5728, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3568): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/        ( 2590): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1414","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1414","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT1414, peerAddress: B0:C5:59:3F:75:69
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT1414, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/jxcore-log( 2590): 2015-12-02T20:17:31.198Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:17:31.199Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:17:31.200Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:17:31.202Z SendDataConnector.js: do connect now
I/jxcore-log( 2590): 
,I/        ( 2590): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 2590): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2590): Starting to connect
,W/BluetoothAdapter( 2590): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2643): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 2590): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[305]}
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [f8:95:c7:87:85:54]: 7, f, 6109
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,I/        ( 2590): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT7503","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT7503","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT7503, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT7503, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2643): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
,I/BluetoothBondStateMachine( 2643): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2643): Entering PendingCommandState State
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,E/bt-btif ( 2643): services_to_search = 3fffffff
,E/bt-btif ( 2643): ****************search UUID = 1200***********
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,E/bt-btif ( 2643): services_to_search = 3ffffffe
,E/bt-btif ( 2643): ****************search UUID = 0100***********
,W/bt-btif ( 2643): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2643): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2643): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2590): Starting to Handshake
,I/BTHandshakeSocketThread( 2590): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2590): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread started
,I/        ( 2590): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT7328, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT7328, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 2590): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 2590): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT7503","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 2590): HandshakeOk : LGE-LG-D722_PT7503
,I/HS      ( 2590): Hand Shake finished outgoing for : LGE-LG-D722_PT7503
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2590): Starting the connected thread incoming : false, LGE-LG-D722_PT7503
,I/BtToSocketBase( 2590): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2590): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2590): mHTTPPort  set to : 48573
,I/BtConnectorHelper( 2590): Request socket is using : 48573
,I/BtToRequestSocket( 2590): Now accepting connections
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,E/bt-btif ( 2643): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 2 uuid:00001106-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 9 uuid:0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BluetoothBondStateMachine( 2643): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2643): Failed to remove device: F8:95:C7:87:85:54
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,I/BluetoothBondStateMachine( 2643): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2643): StableState(): Entering Off State
,W/BluetoothEventManager( 2657): showUnbondMessage: Not displaying any message for reason: 0
,D/dalvikvm( 2643): GC_CONCURRENT freed 384K, 3% free 16880K/17296K, paused 2ms+1ms, total 12ms
,D/BluetoothMap( 2657): getConnectedDevices()
,D/BluetoothMap( 2657): getConnectionState(F8:95:C7:87:85:54)
D/MapProfile( 2657): getConnectionStatus: status is: 0
,I/BtConnectorHelper( 2590): Calling ConnectionStatusUpdate with port :48573
I/jxcore-log( 2590): 2015-12-02T20:17:38.414Z SendDataConnector.js: CLIENT connected to 48573, error: null
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:17:38.414Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2590): 
,I/BtToRequestSocket( 2590): incoming data from: /127.0.0.1, port: 48573
I/BtToRequestSocket( 2590): Set local streams
,I/jxcore-log( 2590): 2015-12-02T20:17:38.417Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2590): 
,I/BtToRequestSocket( 2590): rin ended ---------------------------;
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2590): Found Service, :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5777","ra":"34:FC:EF:11:AE:67"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5777","ra":"34:FC:EF:11:AE:67"} -- peerIdentifier:34:FC:EF:11:AE:67, peerName: LGE-Nexus 5_PT5777, peerAddress: 34:FC:EF:11:AE:67
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : 34:FC:EF:11:AE:67, Name: LGE-Nexus 5_PT5777, WifiDirectName: Android_8ae2, WifiDirect Address: 52:55:27:f0:fd:0b, peerId: 34:FC:EF:11:AE:67
,W/bt-btif ( 2643): dm_pm_timer expires
,W/bt-btif ( 2643): dm_pm_timer expires 0
,W/bt-btif ( 2643): proc dm_pm_timer expires
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2590): 2015-12-02T20:17:48.454Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:17:48.455Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:17:48.459Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:17:48.461Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:17:48.464Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2590): 
,I/BtToSocketBase( 2590): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 2590): Disconnect outgoing peer: LGE-LG-D722_PT7503
,I/BtToSocketBase( 2590): Stop ReceivingThread
,I/BtToSocketBase( 2590): Stop SendingThread
,I/BtToSocketBase( 2590): Close local in
,I/BtToSocketBase( 2590): Close LocalOutputStream
,I/BtToSocketBase( 2590): Close localHostSocket
,I/BtToSocketBase( 2590): Close bt in
,I/BtToSocketBase( 2590): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2590): Close bt out
,I/BtToSocketBase( 2590): Close bt socket
,I/BtToRequestSocket( 2590): Close server socket
,W/bt-btif ( 2643): bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND
,I/        ( 2590): Cleared service requests
,I/        ( 2590): Started peer discovery
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2590): Found 10 peers.
,I/SS      ( 2590): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2590): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2590): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2590): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2590): Peer(5): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2590): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2590): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2590): Peer(8): Android_8ae2 52:55:27:f0:fd:0b
I/SS      ( 2590): Peer(9): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 2590): Peer(10): Thali Test's G2 36:fc:ef:de:0a:e2
D/WifiP2pManager( 2590): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2590): Added service request
,I/        ( 2590): Started service discovery
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 2590): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT2788, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT2788, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 2590): 2015-12-02T20:17:53.464Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:17:53.465Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2590): 
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,I/        ( 2590): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT7267"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT7267"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT7267, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT7267, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2590): 2015-12-02T20:17:58.469Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:17:58.470Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:17:58.474Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:17:58.475Z SendDataConnector.js: do connect now
I/jxcore-log( 2590): 
,I/        ( 2590): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 2590): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2590): Starting to connect
,W/BluetoothAdapter( 2590): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2643): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 2590): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[308]}
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,I/BluetoothBondStateMachine( 2643): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
,I/BluetoothBondStateMachine( 2643): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2643): Entering PendingCommandState State
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,E/bt-btif ( 2643): services_to_search = 3fffffff
,E/bt-btif ( 2643): ****************search UUID = 1200***********
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,E/bt-btif ( 2643): services_to_search = 3ffffffe
,E/bt-btif ( 2643): ****************search UUID = 0100***********
,W/bt-btif ( 2643): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2643): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2643): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2590): Starting to Handshake
,I/BTHandshakeSocketThread( 2590): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2590): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread started
,I/BTConnectToThread( 2590): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 2590): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT7503","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 2590): HandshakeOk : LGE-LG-D722_PT7503
,I/HS      ( 2590): Hand Shake finished outgoing for : LGE-LG-D722_PT7503
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2590): Starting the connected thread incoming : false, LGE-LG-D722_PT7503
,I/BtToSocketBase( 2590): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2590): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2590): mHTTPPort  set to : 38595
,I/BtConnectorHelper( 2590): Request socket is using : 38595
,I/BtToRequestSocket( 2590): Now accepting connections
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,E/bt-btif ( 2643): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 2 uuid:00001106-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 2643): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 2643): Index: 9 uuid:0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BluetoothBondStateMachine( 2643): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2643): Failed to remove device: F8:95:C7:87:85:54
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,I/BluetoothBondStateMachine( 2643): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2643): StableState(): Entering Off State
,W/BluetoothEventManager( 2657): showUnbondMessage: Not displaying any message for reason: 0
,D/BluetoothMap( 2657): getConnectedDevices()
,D/BluetoothMap( 2657): getConnectionState(F8:95:C7:87:85:54)
,D/MapProfile( 2657): getConnectionStatus: status is: 0
,I/BtConnectorHelper( 2590): Calling ConnectionStatusUpdate with port :38595
,I/jxcore-log( 2590): 2015-12-02T20:18:00.830Z SendDataConnector.js: CLIENT connected to 38595, error: null
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:00.831Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2590): 
,I/BtToRequestSocket( 2590): incoming data from: /127.0.0.1, port: 38595
,I/BtToRequestSocket( 2590): Set local streams
,I/jxcore-log( 2590): 2015-12-02T20:18:00.833Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2590): 
,I/BtToRequestSocket( 2590): rin ended ---------------------------;
,I/        ( 2590): Cleared service requests
,I/        ( 2590): Started peer discovery
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2590): Found 13 peers.
,I/SS      ( 2590): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2590): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 2590): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2590): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 2590): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2590): Peer(6): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 2590): Peer(7): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 2590): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 2590): Peer(9): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2590): Peer(10): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 2590): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
,I/SS      ( 2590): Peer(12): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 2590): Peer(13): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 2590): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2590): Added service request
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,I/        ( 2590): Started service discovery
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [e0:db:10:14:e2:c0]: 6, 1d, 7d3
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: Note4-1
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751deef4 rs_disc_pending=1
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2643): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2643): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2643): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2590): we got incoming connection
,I/BTHandshakeSocketThread( 2590): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2590): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread started
,I/BTListenerThread( 2590): got MESSAGE_READ 81 bytes.
,I/BTListenerThread( 2590): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT785","ra":"E0:DB:10:14:E2:C0"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2590): MESSAGE_WRITE 76 bytes.
,I/HS      ( 2590): Incoming connection Hand Shake finished for : samsung-SM-N910C_PT785
,I/BTHandshakeSocketThread( 2590): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2590): Starting the connected thread incoming : true, samsung-SM-N910C_PT785
,I/BtToSocketBase( 2590): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2590): Creating BTConnectedThread
,I/BtConnectorHelper( 2590): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2590): --DoOneRunRound started
,I/BtToRequestSocket( 2590): LocalHost address: localhost/127.0.0.1, port: 43412
,I/jxcore-log( 2590): 2015-12-02T20:18:04.880Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2590): 
,I/BtToRequestSocket( 2590): --DoOneRunRound ended
,I/jxcore-log( 2590): 2015-12-02T20:18:05.662Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2590): 
,W/bt-btif ( 2643): dm_pm_timer expires
,W/bt-btif ( 2643): dm_pm_timer expires 0
,W/bt-btif ( 2643): proc dm_pm_timer expires
,I/jxcore-log( 2590): 2015-12-02T20:18:05.940Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:06.019Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:06.053Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:06.062Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:06.067Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:06.177Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:06.208Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:06.219Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:06.263Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:06.300Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:06.564Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:06.821Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:06.901Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 2590): 
,I/        ( 2590): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT7328, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT7328, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 2590): 2015-12-02T20:18:07.064Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:07.246Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:07.329Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:07.332Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 2590): 
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751deef4 rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2590): 2015-12-02T20:18:07.542Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:07.610Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:07.895Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:07.902Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:08.174Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:08.204Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:08.290Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:08.379Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:08.595Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:08.630Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:08.667Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:08.675Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:08.746Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 2590): 
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2590): 2015-12-02T20:18:08.834Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:08.838Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:08.869Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:08.872Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:08.917Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:08.920Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:08.959Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:09.031Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:09.034Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:09.068Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:09.084Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:09.122Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:09.211Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:09.239Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:09.284Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:09.315Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:09.320Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2590): 
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2590): 2015-12-02T20:18:10.876Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:10.877Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:10.880Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:10.881Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:10.884Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2590): 
,I/BtToSocketBase( 2590): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 2590): Disconnect outgoing peer: LGE-LG-D722_PT7503
,I/BtToSocketBase( 2590): Stop ReceivingThread
,I/BtToSocketBase( 2590): Stop SendingThread
,I/BtToSocketBase( 2590): Close local in
,I/BtToSocketBase( 2590): Close LocalOutputStream
,I/BtToSocketBase( 2590): Close localHostSocket
,I/BtToSocketBase( 2590): Close bt in
,I/BtToSocketBase( 2590): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2590): Close bt out
,I/BtToSocketBase( 2590): Close bt socket
,I/BtToRequestSocket( 2590): Close server socket
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751deef4 rs_disc_pending=1
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751deef4 rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2643): bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND
,I/        ( 2590): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT2788, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT2788, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 2590): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8756","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8756","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8756, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8756, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,I/jxcore-log( 2590): 2015-12-02T20:18:15.884Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:15.885Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2590): 
,W/bt-btif ( 2643): dm_pm_timer expires
,W/bt-btif ( 2643): dm_pm_timer expires 0
,W/bt-btif ( 2643): proc dm_pm_timer expires
,I/        ( 2590): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1414","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1414","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT1414, peerAddress: B0:C5:59:3F:75:69
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT1414, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 2590): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1792","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1792","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT1792, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT1792, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 2590): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9856"}, typeCordovap2p._tcp.local.:
,I/        ( 2590): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9856"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9856, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9856, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 2590): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5728"}, typeCordovap2p._tcp.local.:
I/        ( 2590): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5728"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5728, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 2590): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5728, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,W/bt-btif ( 2643): invalid rfc slot id: 24
,I/BtToSocketBase( 2590): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2590): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2590): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N910C_PT785
I/BtToSocketBase( 2590): Stop ReceivingThread
I/BtToSocketBase( 2590): Stop SendingThread
I/BtToSocketBase( 2590): Close local in
I/BtToSocketBase( 2590): Close LocalOutputStream
,I/BtToSocketBase( 2590): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2590): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2590): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N910C_PT785
I/BtToSocketBase( 2590): Close localHostSocket
I/BtToSocketBase( 2590): Close bt in
I/BtToSocketBase( 2590): Close bt out
I/BtToSocketBase( 2590): Close bt in
I/BtToSocketBase( 2590): Close bt socket
I/BtToSocketBase( 2590): Close bt out
,I/BtToSocketBase( 2590): Close bt socket
,I/jxcore-log( 2590): 2015-12-02T20:18:19.520Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2590): 
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751dfb18 rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2643): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
,W/bt-rfcomm( 2643): RFCOMM_DisconnectInd LCID:0x4e
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2590): 2015-12-02T20:18:20.889Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:20.890Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:20.892Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:20.893Z SendDataConnector.js: do connect now
I/jxcore-log( 2590): 
,I/        ( 2590): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 2590): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2590): Starting to connect
,W/BluetoothAdapter( 2590): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2643): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/BluetoothSocket( 2590): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[309]}
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751dfb18 rs_disc_pending=1
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751dfb18 rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751dfb18 rs_disc_pending=1
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2643): process_service_search_attr_rsp
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=7936, deviceClass=7936])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: Note4-1
,D/dalvikvm( 1172): GC_CONCURRENT freed 389K, 7% free 17875K/19188K, paused 19ms+2ms, total 53ms
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,I/wpa_supplicant( 3568): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2590): Cleared service requests
,I/        ( 2590): Started peer discovery
,W/bt-btif ( 2643): info:x10,
,D/        ( 2643): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2590): Found 12 peers.
,I/SS      ( 2590): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 2590): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 2590): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 2590): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2590): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2590): Peer(6): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2590): Peer(7): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2590): Peer(8): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2590): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2590): Peer(10): Android_8ae2 52:55:27:f0:fd:0b
,I/SS      ( 2590): Peer(11): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 2590): Peer(12): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 2590): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2590): Added service request
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751dfcd4 rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 2590): Started service discovery
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3568): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3568): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/ConnectivityService(  796): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  796): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  796): Attempting to switch to mobile
,D/ConnectivityService(  796): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  796): android_net_utils_resetConnections in env=0x76a3ef00 clazz=0x9d300001 iface=wlan0 mask=0x3
D/ConnectivityService(  796): resetConnections(wlan0, 3)
,V/NativeCrypto( 1112): Read error: ssl=0x79124520: I/O error during system call, Connection timed out
,V/NativeCrypto( 1112): SSL shutdown failed: ssl=0x79124520: I/O error during system call, Broken pipe
,I/jxcore-log( 2590): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): The Coordinator has disconnected!
I/jxcore-log( 2590): 
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  796): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  796): handleInetConditionChange: no active default network - ignore
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2590): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2590): 
,D/WifiService(  796): setWifiEnabled: false pid=2590, uid=10108
,D/WifiService(  796): setWifiEnabled: true pid=2590, uid=10108
E/WifiStateMachine(  796): scanCount==0 - aborting
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/WifiController(  796): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 469ms
,I/jxcore-log( 2590): Wifi toggled for connection repairment
I/jxcore-log( 2590): 
,I/chromium( 2590): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 2590): Wifi is DISABLED !!
,I/        ( 2590): Stoping All
I/        ( 2590): Stopping services
,I/        ( 2590): Stopping services
,I/        ( 2590): Stop Bluetooth
I/        ( 2590): Stop Bluetooth
,I/BTListenerThread( 2590): Stopped
,I/        ( 2590): Clearing local services failed, error code 2
I/BTConnectToThread( 2590): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btif ( 2643): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:29, channel:8
E/bt-btif ( 2643): bta_jv_rfcomm_stop_server
,W/bt-btif ( 2643): invalid rfc slot id: 29
I/        ( 2590): Clearing service requests failed, error code 2
I/        ( 2590): Stopping peer discovery failed, error code 2
,I/CONNEC  ( 2590): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2590): 2015-12-02T20:18:31.033Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:31.033Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:31.036Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:31.036Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2590): 
I/jxcore-log( 2590): 2015-12-02T20:18:31.037Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2590): 
I/jxcore-log( 2590): ---- round done--------
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): ---- gotta redo : F8:95:C7:87:85:54, try count now: 1
I/jxcore-log( 2590): 
I/jxcore-log( 2590): do fake peer & start
I/jxcore-log( 2590): 
I/jxcore-log( 2590): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 2590): 
I/jxcore-log( 2590): 2015-12-02T20:18:31.038Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2590): 
,I/jxcore-log( 2590): 2015-12-02T20:18:31.038Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2590): 
I/jxcore-log( 2590): 2015-12-02T20:18:31.038Z SendDataConnector.js: do connect now
I/jxcore-log( 2590): 
D/AndroidRuntime( 2590): Shutting down VM
,W/dalvikvm( 2590): threadid=1: thread exiting with uncaught exception (group=0x415aeba8)
,I/BtConnection( 2590): Got uncaughtException: java.lang.RuntimeException: Connector class is not initialized properly
,I/wpa_supplicant( 3568): P2P-FIND-STOPPED 
I/wpa_supplicant( 3568): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3568): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3568): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3568): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3568): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
I/wpa_supplicant( 3568): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 3568): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3568): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3568): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 3568): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 3568): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/wpa_supplicant( 3568): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,D/WifiController(  796): DEFERRED_TOGGLE handled
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/ConnectivityService(  796): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant( 3568): p2p0: CTRL-EVENT-TERMINATING 
,D/Tethering(  796): InitialState.processMessage what=4
,D/Tethering(  796): sendTetherStateChangedBroadcast 0, 0, 0
,I/wpa_supplicant( 3568): wlan0: CTRL-EVENT-TERMINATING 
,W/Settings( 1854): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  978): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/SoftapController(  182): Softap fwReload - Ok
D/CommandListener(  182): Setting iface cfg
,D/CommandListener(  182): Trying to bring down wlan0
,D/WifiMonitor(  796): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 3799): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3799): rfkill: Cannot open RFKILL control device
,D/Tethering(  796): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  796): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  796): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Babel   ( 1854): connection state changed from CONNECTED to DISCONNECTED
,D/Tethering(  796): sendTetherStateChangedBroadcast 1, 0, 0
,I/iu.Environment( 1295): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1295): num queued entries: 0
,I/SystemUpdateService( 1295): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/iu.UploadsManager( 1295): num updated entries: 0
,D/SystemUpdateService( 1295): onCreate
,D/SystemUpdateService( 1295): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1295): active receiver: enabled
,I/iu.SyncManager( 1295): NEXT; no task
,I/SystemUpdateService( 1295): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1295): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1295): now status is 0 (complete)
I/SystemUpdateService( 1295): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1295): file has been verified
,I/SystemUpdateService( 1295): OTA package size = 2571501
,I/SystemUpdateService( 1295): showing system update notification
,D/SystemUpdateService( 1295): onDestroy
,I/wpa_supplicant( 3799): rfkill: Cannot open RFKILL control device
,D/WifiConfigStore(  796): Loading config and enabling all networks
,W/Settings( 1854): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,D/CommandListener(  182): Setting iface cfg
,D/CommandListener(  182): Trying to bring up p2p0
,D/WifiMonitor(  796): startMonitoring(p2p0) with mConnected = true
,D/dalvikvm( 1112): GC_CONCURRENT freed 528K, 6% free 18433K/19412K, paused 3ms+2ms, total 19ms
,D/ConnectivityService(  796): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant( 3799): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,D/dalvikvm(  796): GC_CONCURRENT freed 2411K, 52% free 26786K/55504K, paused 12ms+4ms, total 69ms
,I/wpa_supplicant( 3799): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/ConnectivityService(  796): handleInetConditionChange: no active default network - ignore
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3799): wlan0: Authentication with c0:ff:d4:d3:aa:48 timed out.
,I/wpa_supplicant( 3799): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/wpa_supplicant( 3799): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3799): wlan0: Associated with c0:ff:d4:d3:aa:48
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,D/ConnectivityService(  796): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  796): Done.
,D/ConnectivityService(  796): Setting timer for 720seconds
,D/ConnectivityService(  796): handleInetConditionChange: no active default network - ignore
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3799): wlan0: Authentication with c0:ff:d4:d3:aa:48 timed out.
,I/wpa_supplicant( 3799): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/wpa_supplicant( 3799): wlan0: CTRL-EVENT-SSID-TEMP-DISABLED id=0 ssid="NG700" auth_failures=1 duration=10
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,D/dalvikvm( 2643): GC_CONCURRENT freed 395K, 3% free 16880K/17308K, paused 6ms+1ms, total 49ms
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3799): wlan0: CTRL-EVENT-SSID-REENABLED id=0 ssid="NG700"
,D/ConnectivityService(  796): handleInetConditionChange: no active default network - ignore
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2643): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,I/BluetoothBondStateMachine( 2643): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2643): Entering PendingCommandState State
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,D/ConnectivityService(  796): NetTransition Wakelock for ConnectedState released by timeout
,I/BluetoothBondStateMachine( 2643): bondStateChangeCallback: Status: 9 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2643): Failed to remove device: F8:95:C7:87:85:54
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,I/BluetoothBondStateMachine( 2643): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2643): StableState(): Entering Off State
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,E/bt-btif ( 2643): Do not find the bg connection mask for the remote device
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/ConnectivityService(  796): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant( 3799): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3799): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 3799): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3799): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  796): scanCount==0 - aborting
,D/WifiStateMachine(  796): VerifyingLinkState enter
,D/WifiStateMachine(  796): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  796): CaptivePortalCheckState enter
,D/WifiStateMachine(  796): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  796): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  796): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  796): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  796): Unexpected mtu value: android.net.wifi.WifiStateTracker@42b7ddb0
,D/Nat464Xlat(  796): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  796): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  796):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  796): requiresClat: netType=1, hasIPv4Address=true
,I/wpa_supplicant( 3799): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,I/wpa_supplicant( 3799): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3799): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00000600101c440032
,I/wpa_supplicant( 3799): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/Tethering(  796): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  796): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/iu.Environment( 1295): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1295): num queued entries: 0
,I/iu.UploadsManager( 1295): num updated entries: 0
I/iu.SyncManager( 1295): NEXT; no task
,I/SystemUpdateService( 1295): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1295): onCreate
,D/SystemUpdateService( 1295): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1295): active receiver: enabled
,I/SystemUpdateService( 1295): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1295): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1295): now status is 0 (complete)
I/SystemUpdateService( 1295): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1295): file has been verified
,I/SystemUpdateService( 1295): OTA package size = 2571501
,I/SystemUpdateService( 1295): showing system update notification
,D/SystemUpdateService( 1295): onDestroy
,D/dalvikvm( 2289): GC_CONCURRENT freed 253K, 2% free 17708K/17992K, paused 2ms+1ms, total 13ms
,I/wpa_supplicant( 3799): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/Babel   ( 1854): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  796): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/wpa_supplicant( 3799): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3799): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3799): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3799): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3799): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3799): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/CaptivePortalTracker(  796): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  796): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  796): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  796): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  796): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  796): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  796): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  796): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/wpa_supplicant( 3799): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3799): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3799): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/wpa_supplicant( 3799): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3799): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,I/wpa_supplicant( 3799): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3799): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/wpa_supplicant( 3799): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3799): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/ConnectivityService(  796): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  796): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  796): Attempting to switch to mobile
,D/ConnectivityService(  796): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  796): android_net_utils_resetConnections in env=0x76a3ef00 clazz=0xded00001 iface=wlan0 mask=0x3
D/ConnectivityService(  796): resetConnections(wlan0, 3)
,V/NativeCrypto( 1112): Read error: ssl=0x79124520: I/O error during system call, Connection timed out
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1112): SSL shutdown failed: ssl=0x79124520: I/O error during system call, Broken pipe
,D/Nat464Xlat(  796): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  796): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant( 3799): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3799): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 3799): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3799): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  796): scanCount==0 - aborting
,D/ConnectivityService(  796): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant( 3799): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/wpa_supplicant( 3799): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,D/Tethering(  796): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  796): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  796): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/iu.Environment( 1295): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1295): num queued entries: 0
,I/Babel   ( 1854): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1295): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/iu.UploadsManager( 1295): num updated entries: 0
,I/iu.SyncManager( 1295): NEXT; no task
,D/SystemUpdateService( 1295): onCreate
,D/dalvikvm( 2820): GC_CONCURRENT freed 281K, 2% free 16805K/17116K, paused 1ms+1ms, total 49ms
,D/SystemUpdateService( 1295): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1295): active receiver: enabled
,I/SystemUpdateService( 1295): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1295): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1295): now status is 0 (complete)
I/SystemUpdateService( 1295): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1295): file has been verified
,I/SystemUpdateService( 1295): OTA package size = 2571501
,I/SystemUpdateService( 1295): showing system update notification
,D/SystemUpdateService( 1295): onDestroy
,D/WifiStateMachine(  796): VerifyingLinkState enter
,D/WifiStateMachine(  796): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  796): CaptivePortalCheckState enter
,D/WifiStateMachine(  796): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  796): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  796): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  796): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  796): Unexpected mtu value: android.net.wifi.WifiStateTracker@42b7ddb0
,D/Nat464Xlat(  796): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  796): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  796): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  796):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  796): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  796): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/Tethering(  796): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  796): NoActiveNetworkState{ when=-4ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/iu.Environment( 1295): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1295): num queued entries: 0
,I/iu.UploadsManager( 1295): num updated entries: 0
,I/SystemUpdateService( 1295): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1295): onCreate
,D/SystemUpdateService( 1295): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1295): active receiver: enabled
,I/iu.SyncManager( 1295): NEXT; no task
,I/SystemUpdateService( 1295): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1295): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1295): now status is 0 (complete)
I/SystemUpdateService( 1295): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1295): file has been verified
,I/SystemUpdateService( 1295): OTA package size = 2571501
,I/SystemUpdateService( 1295): showing system update notification
,D/SystemUpdateService( 1295): onDestroy
,I/Babel   ( 1854): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  796): handleInetConditionHoldEnd: net=1, condition=0, published condition=100
,D/ConnectivityService(  796): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  796): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker(  796): Checking http://216.58.209.46/generate_204
D/ConnectivityService(  796): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  796): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  796): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  796): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  796): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  796): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/dalvikvm(  796): GC_CONCURRENT freed 2226K, 52% free 26996K/55504K, paused 22ms+5ms, total 90ms
,I/wpa_supplicant( 3799): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3799): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 3799): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
I/wpa_supplicant( 3799): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3799): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3799): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3799): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3799): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3799): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/wpa_supplicant( 3799): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 2643): l2cu_get_conn_role 1
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 2643): l2cu_get_conn_role 1
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 2643): l2cu_get_conn_role 1
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 2643): l2cu_get_conn_role 1
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,D/dalvikvm( 2643): GC_CONCURRENT freed 406K, 3% free 16880K/17316K, paused 17ms+6ms, total 63ms
,I/wpa_supplicant( 3799): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/ConnectivityService(  796): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  796): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  796): Attempting to switch to mobile
,D/ConnectivityService(  796): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  796): android_net_utils_resetConnections in env=0x76a3ef00 clazz=0x1f00001 iface=wlan0 mask=0x3
D/ConnectivityService(  796): resetConnections(wlan0, 3)
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1112): Read error: ssl=0x79124520: I/O error during system call, Connection timed out
,V/NativeCrypto( 1112): SSL shutdown failed: ssl=0x79124520: I/O error during system call, Broken pipe
,D/Nat464Xlat(  796): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  796): handleInetConditionChange: no active default network - ignore
,D/dalvikvm( 1112): GC_CONCURRENT freed 507K, 5% free 18402K/19344K, paused 2ms+2ms, total 16ms
,I/wpa_supplicant( 3799): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3799): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 3799): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3799): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  796): scanCount==0 - aborting
,D/Tethering(  796): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  796): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  796): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/iu.Environment( 1295): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1295): num queued entries: 0
,I/Babel   ( 1854): connection state changed from CONNECTED to DISCONNECTED
,I/iu.UploadsManager( 1295): num updated entries: 0
,I/SystemUpdateService( 1295): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1295): onCreate
,D/SystemUpdateService( 1295): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1295): active receiver: enabled
,I/iu.SyncManager( 1295): NEXT; no task
,D/dalvikvm( 1295): GC_CONCURRENT freed 1156K, 6% free 18968K/20152K, paused 3ms+9ms, total 40ms
,I/SystemUpdateService( 1295): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1295): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1295): now status is 0 (complete)
I/SystemUpdateService( 1295): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1295): file has been verified
,I/SystemUpdateService( 1295): OTA package size = 2571501
,I/SystemUpdateService( 1295): showing system update notification
,D/SystemUpdateService( 1295): onDestroy
,D/WifiStateMachine(  796): VerifyingLinkState enter
,D/WifiStateMachine(  796): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  796): CaptivePortalCheckState enter
,D/ConnectivityService(  796): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  796): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  796): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  796): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  796): Unexpected mtu value: android.net.wifi.WifiStateTracker@42b7ddb0
,D/Nat464Xlat(  796): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  796): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  796): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  796):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  796): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  796): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  796): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/iu.Environment( 1295): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1295): num queued entries: 0
,I/SystemUpdateService( 1295): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1295): onCreate
,D/SystemUpdateService( 1295): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.UploadsManager( 1295): num updated entries: 0
,I/SystemUpdateService( 1295): active receiver: enabled
,I/SystemUpdateService( 1295): Already downloaded, skipping offpeak checks.
,I/iu.SyncManager( 1295): NEXT; no task
,I/SystemUpdateService( 1295): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1295): now status is 0 (complete)
I/SystemUpdateService( 1295): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1295): file has been verified
,I/SystemUpdateService( 1295): OTA package size = 2571501
,V/NativeCrypto( 1112): SSL handshake aborted: ssl=0x79124520: SSL_ERROR_WANT_READ occurred. You should never see this.
,I/SystemUpdateService( 1295): showing system update notification
,I/ActivityManager(  796): Delay finish: com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,D/SystemUpdateService( 1295): onDestroy
I/ActivityManager(  796): Resuming delayed broadcast
,I/Babel   ( 1854): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  796): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  796): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/CaptivePortalTracker(  796): DelayedCaptiveCheckState{ when=-12ms what=2 arg1=6 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  796): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  796): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  796): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  796): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  796): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  796): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
D/CaptivePortalTracker(  796): isCaptivePortal: ret=false rspCode=204
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/dalvikvm(  978): GC_CONCURRENT freed 387K, 3% free 17902K/18384K, paused 2ms+1ms, total 16ms
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,W/bt-l2cap( 2643): l2cu_get_conn_role 1
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,W/bt-l2cap( 2643): l2cu_get_conn_role 1
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,W/bt-l2cap( 2643): l2cu_get_conn_role 1
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751df5e4 rs_disc_pending=1
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 2643): l2cu_get_conn_role 0
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1172): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1172): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,D/BluetoothAdapterService(1113642816)( 2643): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2643): getBondedDevices: length=4
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 2643): l2cu_get_conn_role 0
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [58:3f:54:73:64:c0]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2643): tBTM_SEC_DEV:0x751dfe90 rs_disc_pending=0
,W/bt-btif ( 2643): bta_dm_check_av:0
,W/bt-btif ( 2643): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3799): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/ConnectivityService(  796): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  796): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  796): Attempting to switch to mobile
,D/ConnectivityService(  796): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  796): android_net_utils_resetConnections in env=0x76a3ef00 clazz=0x21800001 iface=wlan0 mask=0x3
D/ConnectivityService(  796): resetConnections(wlan0, 3)
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1112): Read error: ssl=0x79124520: I/O error during system call, Connection timed out
,V/NativeCrypto( 1112): SSL shutdown failed: ssl=0x79124520: I/O error during system call, Broken pipe
,D/Nat464Xlat(  796): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  796): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant( 3799): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3799): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 3799): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3799): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  796): scanCount==0 - aborting
,D/Tethering(  796): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  796): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  796): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/iu.Environment( 1295): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1295): num queued entries: 0
,I/iu.UploadsManager( 1295): num updated entries: 0
,I/SystemUpdateService( 1295): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1295): onCreate
,D/SystemUpdateService( 1295): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/Babel   ( 1854): connection state changed from CONNECTED to DISCONNECTED
,I/iu.SyncManager( 1295): NEXT; no task
,I/SystemUpdateService( 1295): active receiver: enabled
,I/SystemUpdateService( 1295): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1295): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1295): now status is 0 (complete)
I/SystemUpdateService( 1295): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1295): file has been verified
,I/SystemUpdateService( 1295): OTA package size = 2571501
,I/SystemUpdateService( 1295): showing system update notification
,D/SystemUpdateService( 1295): onDestroy
,D/ConnectivityService(  796): handleInetConditionChange: no active default network - ignore
,D/WifiStateMachine(  796): VerifyingLinkState enter
,D/WifiStateMachine(  796): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  796): CaptivePortalCheckState enter
,D/WifiStateMachine(  796): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  796): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  796): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  796): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  796): Unexpected mtu value: android.net.wifi.WifiStateTracker@42b7ddb0
,D/Nat464Xlat(  796): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  796): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  796): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  796):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  796): requiresClat: netType=1, hasIPv4Address=true
,W/bt-l2cap( 2643): l2cu_get_conn_role 1
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,D/Tethering(  796): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  796): NoActiveNetworkState{ when=-4ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/iu.Environment( 1295): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1295): num queued entries: 0
,I/SystemUpdateService( 1295): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1295): onCreate
,D/SystemUpdateService( 1295): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.UploadsManager( 1295): num updated entries: 0
,I/iu.SyncManager( 1295): NEXT; no task
,I/SystemUpdateService( 1295): active receiver: enabled
,I/SystemUpdateService( 1295): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1295): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1295): now status is 0 (complete)
I/SystemUpdateService( 1295): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1295): file has been verified
,I/SystemUpdateService( 1295): OTA package size = 2571501
,I/SystemUpdateService( 1295): showing system update notification
,D/SystemUpdateService( 1295): onDestroy
,I/Babel   ( 1854): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  796): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,D/dalvikvm( 2643): GC_CONCURRENT freed 385K, 3% free 16880K/17300K, paused 7ms+5ms, total 56ms
,D/CaptivePortalTracker(  796): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=7 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  796): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  796): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  796): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  796): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  796): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  796): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  796): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,W/bt-l2cap( 2643): l2cu_get_conn_role 1
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [58:3f:54:73:64:c0]: 7, f, 6109
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 2643): l2cu_get_conn_role 1
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [34:fc:ef:11:ae:67]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 2643): l2cu_get_conn_role 1
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 2643): l2cu_get_conn_role 1
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 2643): l2cu_get_conn_role 1
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3799): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/ConnectivityService(  796): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  796): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  796): Attempting to switch to mobile
,D/ConnectivityService(  796): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  796): android_net_utils_resetConnections in env=0x76a3ef00 clazz=0x3f800001 iface=wlan0 mask=0x3
D/ConnectivityService(  796): resetConnections(wlan0, 3)
,V/NativeCrypto( 1112): Read error: ssl=0x79124520: I/O error during system call, Connection timed out
,V/NativeCrypto( 1112): SSL shutdown failed: ssl=0x79124520: I/O error during system call, Broken pipe
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  796): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  796): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  796): handleInetConditionChange: no active default network - ignore
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,D/Tethering(  796): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  796): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  796): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/iu.Environment( 1295): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1295): num queued entries: 0
,I/iu.UploadsManager( 1295): num updated entries: 0
,I/Babel   ( 1854): connection state changed from CONNECTED to DISCONNECTED
,I/iu.SyncManager( 1295): NEXT; no task
,I/SystemUpdateService( 1295): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1295): onCreate
,D/SystemUpdateService( 1295): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1295): active receiver: enabled
,I/SystemUpdateService( 1295): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1295): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1295): now status is 0 (complete)
,I/SystemUpdateService( 1295): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1295): file has been verified
,I/SystemUpdateService( 1295): OTA package size = 2571501
,I/SystemUpdateService( 1295): showing system update notification
,D/SystemUpdateService( 1295): onDestroy
,D/ConnectivityService(  796): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  796): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  796): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant( 3799): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3799): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 3799): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3799): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,E/WifiStateMachine(  796): scanCount==0 - aborting
,D/WifiStateMachine(  796): VerifyingLinkState enter
,D/WifiStateMachine(  796): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  796): CaptivePortalCheckState enter
,D/ConnectivityService(  796): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  796): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  796): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  796): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  796): Unexpected mtu value: android.net.wifi.WifiStateTracker@42b7ddb0
,D/Nat464Xlat(  796): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  796): NetTransition Wakelock for ConnectedState released by timeout
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/ConnectivityService(  796): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  796):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  796): requiresClat: netType=1, hasIPv4Address=true
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,D/Tethering(  796): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  796): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/dalvikvm(  796): GC_CONCURRENT freed 2720K, 52% free 26769K/55504K, paused 21ms+5ms, total 101ms
,I/iu.Environment( 1295): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*,
I/iu.UploadsManager( 1295): num queued entries: 0
I/SystemUpdateService( 1295): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/iu.UploadsManager( 1295): num updated entries: 0
,I/iu.SyncManager( 1295): NEXT; no task
,D/SystemUpdateService( 1295): onCreate
,D/SystemUpdateService( 1295): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1295): active receiver: enabled
,I/SystemUpdateService( 1295): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1295): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1295): now status is 0 (complete)
I/SystemUpdateService( 1295): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1295): file has been verified
,I/SystemUpdateService( 1295): OTA package size = 2571501
,I/SystemUpdateService( 1295): showing system update notification
,D/SystemUpdateService( 1295): onDestroy
,D/dalvikvm( 1854): GC_CONCURRENT freed 1790K, 8% free 22695K/24520K, paused 3ms+5ms, total 60ms
,D/dalvikvm( 1854): WAIT_FOR_CONCURRENT_GC blocked 30ms
,I/Babel   ( 1854): connection state changed from DISCONNECTED to CONNECTED
,D/dalvikvm( 1112): GC_CONCURRENT freed 466K, 5% free 18413K/19344K, paused 9ms+1ms, total 76ms
,D/ConnectivityService(  796): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,W/bt-l2cap( 2643): l2cu_get_conn_role 1
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,D/CaptivePortalTracker(  796): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=8 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  796): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  796): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  796): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  796): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  796): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  796): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  796): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,W/bt-l2cap( 2643): l2cu_get_conn_role 1
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 2643): l2cu_get_conn_role 1
,W/bt-btif ( 2643): info:x10
,D/        ( 2643): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2643): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2643): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2643): aclStateChangeCallback: Device is NULL
,D/dalvikvm( 2643): GC_CONCURRENT freed 390K, 3% free 16880K/17304K, paused 6ms+0ms, total 47ms
,I/wpa_supplicant( 3799): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,D/ConnectivityService(  796): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  796): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  796): Attempting to switch to mobile
,D/ConnectivityService(  796): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  796): android_net_utils_resetConnections in env=0x76a3ef00 clazz=0x5f000001 iface=wlan0 mask=0x3
D/ConnectivityService(  796): resetConnections(wlan0, 3)
,D/CommandListener(  182): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1112): Read error: ssl=0x79124520: I/O error during system call, Connection timed out
,V/NativeCrypto( 1112): SSL shutdown failed: ssl=0x79124520: I/O error during system call, Broken pipe
,D/Nat464Xlat(  796): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  796): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant( 3799): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,D/dalvikvm(  978): GC_CONCURRENT freed 395K, 3% free 17898K/18388K, paused 12ms+2ms, total 34ms
,I/wpa_supplicant( 3799): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 3799): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3799): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  796): scanCount==0 - aborting
,D/Tethering(  796): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  796): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  796): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/iu.Environment( 1295): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1295): num queued entries: 0
,I/iu.UploadsManager( 1295): num updated entries: 0
,I/Babel   ( 1854): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1295): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1295): onCreate
,D/SystemUpdateService( 1295): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1295): active receiver: enabled
I/iu.SyncManager( 1295): NEXT; no task
,I/SystemUpdateService( 1295): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1295): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1295): now status is 0 (complete)
I/SystemUpdateService( 1295): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1295): file has been verified
,I/SystemUpdateService( 1295): OTA package size = 2571501
,I/SystemUpdateService( 1295): showing system update notification
,D/SystemUpdateService( 1295): onDestroy
,D/WifiStateMachine(  796): VerifyingLinkState enter
,D/WifiStateMachine(  796): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  796): CaptivePortalCheckState enter
,D/WifiStateMachine(  796): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  796): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  796): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  796): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  796): Unexpected mtu value: android.net.wifi.WifiStateTracker@42b7ddb0
,D/Nat464Xlat(  796): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  796): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  796): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  796):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  796): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  796): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/Tethering(  796): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  796): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/iu.Environment( 1295): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1295): num queued entries: 0
,I/SystemUpdateService( 1295): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1295): onCreate
,D/SystemUpdateService( 1295): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1295): active receiver: enabled
,I/iu.UploadsManager( 1295): num updated entries: 0
,I/SystemUpdateService( 1295): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1295): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/iu.SyncManager( 1295): NEXT; no task
,I/SystemUpdateService( 1295): now status is 0 (complete)
I/SystemUpdateService( 1295): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1295): file has been verified
,I/SystemUpdateService( 1295): OTA package size = 2571501
,I/SystemUpdateService( 1295): showing system update notification
,D/dalvikvm( 1295): GC_CONCURRENT freed 671K, 6% free 18973K/20152K, paused 2ms+2ms, total 29ms
,D/SystemUpdateService( 1295): onDestroy
,I/Babel   ( 1854): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  796): handleInetConditionHoldEnd: net=1, condition=0, published condition=100
,D/CaptivePortalTracker(  796): DelayedCaptiveCheckState{ when=-3ms what=2 arg1=9 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  796): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  796): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  796): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  796): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  796): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  796): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  796): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/ConnectivityService(  796): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  796): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  796): Done.
,D/ConnectivityService(  796): Setting timer for 720seconds
,I/ProcessStatsService(  796): Prepared write state in 43ms
,I/ProcessStatsService(  796): Prepared write state in 4ms
,I/ProcessStatsService(  796): Pruning old procstats: /data/system/procstats/state-2015-12-02-05-17-00.bin
,I/ActivityManager(  796): Killing 2547:com.quickoffice.android/u0a65 (adj 15): empty for 1811s
,I/ActivityManager(  796): Killing 2499:com.google.android.apps.docs/u0a35 (adj 15): empty for 1811s
,I/ActivityManager(  796): Killing 2481:com.android.musicfx/u0a13 (adj 15): empty for 1811s
,I/ActivityManager(  796): Killing 2452:com.google.android.partnersetup/u0a11 (adj 15): empty for 1811s
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4564): 
D/AndroidRuntime( 4564): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4564): CheckJNI is OFF
D/dalvikvm( 4564): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4564): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4564): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4564): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4564): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4564): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/AndroidRuntime( 4564): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  796): Force stopping com.test.thalitest appid=10108 user=-1: uninstall pkg
I/ActivityManager(  796): Killing 2590:com.test.thalitest/u0a108 (adj 0): stop com.test.thalitest
I/ActivityManager(  796): Killing 2231:com.android.vending/u0a14 (adj 15): empty for 1801s
I/ActivityManager(  796): Killing 2905:com.qualcomm.timeservice/u0a68 (adj 15): empty for 1803s
I/ActivityManager(  796):   Force finishing activity ActivityRecord{43d2e000 u0 com.test.thalitest/.MainActivity t2}
I/WindowState(  796): WIN DEATH: Window{447984a0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  796): Skipping PackageSetting{42738e98 com.example.hello/10115} due to missing metadata
I/ActivityManager(  796): Force stopping com.test.thalitest appid=10108 user=0: pkg removed
D/dalvikvm( 1172): GC_EXPLICIT freed 344K, 8% free 17798K/19188K, paused 1ms+2ms, total 19ms
I/InputReader(  796): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  796):   Action: "android.intent.action.SENDTO"
I/PackageManager(  796):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  796):   Scheme: "sms"
I/PackageManager(  796): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/ActivityManager(  796): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4583 uid=10003 gids={50003, 3003, 1028, 1015}
I/LatinIME:LogUtils(  964): Dictionary info: dictionary = main:en_us ; version = 44 ; date = 1393228158
I/PackageManager(  796):   Action: "android.intent.action.SENDTO"
I/PackageManager(  796):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  796):   Scheme: "smsto"
I/PackageManager(  796): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
D/dalvikvm( 1042): GC_EXPLICIT freed 1053K, 7% free 26147K/27844K, paused 1ms+2ms, total 64ms
I/PackageManager(  796):   Action: "android.intent.action.SENDTO"
I/PackageManager(  796):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  796):   Scheme: "mms"
I/PackageManager(  796): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/Launcher( 1042): Deferring update until onResume
W/GeofencerStateMachine(  978): Ignoring removeGeofence because network location is disabled.
W/Binder  (  964): Caught a RuntimeException from the binder stub implementation.
W/Binder  (  964): java.lang.NullPointerException
W/Binder  (  964): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  (  964): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  (  964): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  (  964): 	at dalvik.system.NativeStart.run(Native Method)
D/dalvikvm(  796): GC_EXPLICIT freed 2233K, 52% free 26760K/55504K, paused 2ms+5ms, total 91ms
W/InputMethodManagerService(  796): Got RemoteException sending setActive(false) notification to pid 2590 uid 10108
I/PackageManager(  796):   Action: "android.intent.action.SENDTO"
I/PackageManager(  796):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  796):   Scheme: "mmsto"
I/PackageManager(  796): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/Launcher( 1042): Deferring update until onResume
I/PackageManager(  796):   Action: "android.intent.action.SENDTO"
I/PackageManager(  796):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  796):   Scheme: "sms"
I/PackageManager(  796): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  796):   Action: "android.intent.action.SENDTO"
I/PackageManager(  796):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  796):   Scheme: "smsto"
I/PackageManager(  796): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
D/BackupManagerService(  796): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  796): removePackageParticipantsLocked: uid=10108 #1
I/PackageManager(  796):   Action: "android.intent.action.SENDTO"
I/PackageManager(  796):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  796):   Scheme: "mms"
I/PackageManager(  796): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
D/dalvikvm(  796): GC_EXPLICIT freed 430K, 52% free 26678K/55504K, paused 3ms+17ms, total 98ms
I/PackageManager(  796):   Action: "android.intent.action.SENDTO"
I/PackageManager(  796):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  796):   Scheme: "mmsto"
I/PackageManager(  796): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
D/dalvikvm( 4583): GC_CONCURRENT freed 241K, 2% free 16938K/17208K, paused 2ms+2ms, total 15ms
D/VoicemailCleanupService( 4583): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  796): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=4614 uid=10013 gids={50013, 3003, 3002}
D/AndroidRuntime( 4564): Shutting down VM
D/dalvikvm( 4564): GC_CONCURRENT freed 94K, 15% free 558K/656K, paused 1ms+0ms, total 2ms
I/ActivityManager(  796): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4628 uid=10014 gids={50014, 3003, 1028, 1015}
I/ContactLocale( 4583): AddressBook Labels [en_US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
D/Finsky  ( 4628): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/dalvikvm( 4628): GC_CONCURRENT freed 258K, 2% free 16902K/17188K, paused 2ms+1ms, total 15ms
D/Finsky  ( 4628): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 4628): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4628): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/Finsky  ( 4628): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4628): [1] 2.run: Finished loading 1 libraries.
I/Icing.InternalIcingCorporaProvider( 1172): Updating corpora: A: com.test.thalitest, C: MAYBE
W/Launcher( 1042): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@42608c20 new=com.google.android.velvet.VelvetApplication@42608c20
D/dalvikvm( 4628): GC_CONCURRENT freed 276K, 2% free 17139K/17444K, paused 3ms+5ms, total 19ms
D/dalvikvm( 4628): WAIT_FOR_CONCURRENT_GC blocked 1ms
D/Finsky  ( 4628): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  796): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4662 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
D/Finsky  ( 4628): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
W/ContextImpl( 4662): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2407 
I/ActivityManager(  796): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4677 uid=10035 gids={50035, 1028, 3003, 1015}
I/Icing.InternalIcingCorporaProvider( 1172): UpdateCorporaTask done [took 71 ms] updated apps [took 71 ms] 
I/dalvikvm( 4677): Could not find method android.app.Activity.finishAfterTransition, referenced from method bx.onBackPressed
W/dalvikvm( 4677): VFY: unable to resolve virtual method 1145: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 4677): VFY: replacing opcode 0x6e at 0x0012
D/dalvikvm( 4677): GC_CONCURRENT freed 323K, 3% free 16888K/17240K, paused 3ms+2ms, total 22ms
D/dalvikvm( 4677): WAIT_FOR_CONCURRENT_GC blocked 8ms
D/dalvikvm( 4677): GC_CONCURRENT freed 337K, 3% free 17066K/17432K, paused 2ms+2ms, total 17ms
D/dalvikvm( 4677): WAIT_FOR_CONCURRENT_GC blocked 6ms
I/dalvikvm( 4677): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method gwe.a
W/dalvikvm( 4677): VFY: unable to resolve virtual method 1697: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 4677): VFY: replacing opcode 0x6e at 0x000f
I/dalvikvm( 4677): Could not find method android.content.Context.checkSelfPermission, referenced from method arg.a
W/dalvikvm( 4677): VFY: unable to resolve virtual method 1515: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
D/dalvikvm( 4677): VFY: replacing opcode 0x6e at 0x001b
I/GAv4    ( 4677): Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4677):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4677):   adb logcat -s GAv4
W/GAv4    ( 4677): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/dalvikvm( 4677): GC_CONCURRENT freed 311K, 2% free 17268K/17608K, paused 3ms+2ms, total 20ms
D/dalvikvm( 4677): WAIT_FOR_CONCURRENT_GC blocked 11ms
D/dalvikvm( 4677): WAIT_FOR_CONCURRENT_GC blocked 11ms
E/SharedPreferencesImpl( 4677): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4677): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4677): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4677): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4677): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4677): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4677): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4677): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4677): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4677): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4677): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4677): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4677): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4677): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4677): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4677): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4677): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:952)
E/SQLiteDatabase( 4677): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4677): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4677): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4677): 	at auq.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4677): 	at aug.a(PG:1552)
E/SQLiteDatabase( 4677): 	at jnh$a.a(PG:131)
E/SQLiteDatabase( 4677): 	at aui.run(PG:567)
W/dalvikvm( 4677): threadid=13: thread exiting with uncaught exception (group=0x415aeba8)
W/AnalyticsTrackerProxyImpl( 4677): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.453.15.35, sample rate 1.0
I/dalvikvm( 4677): Could not find method android.provider.DocumentsContract.getTreeDocumentId, referenced from method efh.a
W/dalvikvm( 4677): VFY: unable to resolve static method 2872: Landroid/provider/DocumentsContract;.getTreeDocumentId (Landroid/net/Uri;)Ljava/lang/String;
D/dalvikvm( 4677): VFY: replacing opcode 0x71 at 0x0075
E/SQLiteDatabase( 4677): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4677): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4677): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4677): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4677): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4677): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4677): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4677): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4677): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 4677): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 4677): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4677): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:952)
E/SQLiteDatabase( 4677): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4677): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4677): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4677): 	at gpk$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4677): 	at gpk.g(Unknown Source)
E/SQLiteDatabase( 4677): 	at gpk.a(Unknown Source)
E/SQLiteDatabase( 4677): 	at gpk.e(Unknown Source)
E/SQLiteDatabase( 4677): 	at gpm.b(Unknown Source)
E/SQLiteDatabase( 4677): 	at gpp.run(Unknown Source)
E/SQLiteDatabase( 4677): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4677): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4677): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4677): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4677): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 4677): 	at ijd$c.run(Unknown Source)
E/GAv4    ( 4677): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4677): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
D/dalvikvm( 4677): GC_CONCURRENT freed 243K, 2% free 17540K/17812K, paused 3ms+3ms, total 22ms
D/dalvikvm( 4677): WAIT_FOR_CONCURRENT_GC blocked 10ms
D/dalvikvm( 4677): WAIT_FOR_CONCURRENT_GC blocked 10ms

```
