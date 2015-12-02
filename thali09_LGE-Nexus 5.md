#### Test 52383621d5a0cb8_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
D/dalvikvm( 1148): GC_CONCURRENT freed 401K, 3% free 18252K/18748K, paused 2ms+2ms, total 21ms
I/dalvikvm( 1328): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1328): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1328): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1328): VFY: unable to resolve new-instance 2320 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
D/dalvikvm( 1328): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1328): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1328): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
D/dalvikvm( 1328): DexOpt: unable to opt direct call 0x3207 at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
D/dalvikvm( 2744): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2744): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2744): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2744): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2744): VFY: unable to resolve instance field 46
D/dalvikvm( 2744): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2744): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2744): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2744): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2744): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 2744): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
D/dalvikvm( 2744): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4276d240
D/dalvikvm( 2744): Added shared lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4276d240
D/dalvikvm( 2744): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4276d240, skipping init
D/dalvikvm( 2744): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4276d240
D/dalvikvm( 2744): Added shared lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4276d240
V/JNIHelp ( 2744): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
D/dalvikvm( 2744): GC_CONCURRENT freed 436K, 3% free 17989K/18456K, paused 2ms+2ms, total 15ms
D/dalvikvm( 2744): WAIT_FOR_CONCURRENT_GC blocked 5ms
D/dalvikvm( 2744): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x4276d240
D/dalvikvm( 2744): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x4276d240
D/dalvikvm( 2744): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x4276d240
D/dalvikvm( 2744): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4276d240
,D/dalvikvm( 2744): GC_FOR_ALLOC freed 258K, 3% free 18066K/18496K, paused 13ms, total 13ms
D/ChimeraCfgMgr( 1328): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1328): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1328): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/AsyncTaskServiceImpl( 1328): Submit a task: h
D/ChimeraCfgMgr( 1328): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/PeopleContactsSync( 1328): CP2 sync disabled
D/ChimeraCfgMgr( 1328): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/h       ( 1328): Processing package: com.test.thalitest
I/dalvikvm( 1328): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1328): VFY: unable to resolve virtual method 34: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1328): VFY: replacing opcode 0x6e at 0x000e
D/GassUtils( 1328): Found app info for package com.test.thalitest:18. Hash: 01e4d8ac61718f1dcdc950940ea39ae21caf015e512d4d8080feb7f016346367
D/h       ( 1328): Found info for package com.test.thalitest in db.
--------- beginning of /dev/log/system
I/ActivityManager(  760): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2804 uid=10065 gids={50065, 3003, 1028, 1015}
D/dalvikvm( 1328): GC_CONCURRENT freed 383K, 3% free 18543K/19056K, paused 3ms+2ms, total 23ms
W/BaseAppContext( 1328): Using Auth Proxy for data requests.
W/BaseAppContext( 1328): Using Auth Proxy for data requests.
W/BaseAppContext( 1328): Using Auth Proxy for data requests.
I/ProviderInstaller( 2744): Installed default security provider GmsCore_OpenSSL
W/BaseAppContext( 1328): Using Auth Proxy for data requests.
W/BaseAppContext( 1328): Using Auth Proxy for data requests.
W/BaseAppContext( 1328): Using Auth Proxy for data requests.
W/Quickoffice( 2804): Cleanup of storage: done
D/com.google.android.apps.docs.quickoffice.X( 2804): Loading recent documents list
D/Quickoffice( 2804): The number of lines present in  /proc/mount 21
D/Quickoffice( 2804): Parsing the storagedefinition.xml.
D/Quickoffice( 2804): # of Storagedefinitions - 35
D/Quickoffice( 2804): The # of storage definitions available - 35
D/Quickoffice( 2804): Processing mountline rootfs / rootfs ro,relatime 0 0
D/Quickoffice( 2804): Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
D/Quickoffice( 2804): Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
D/Quickoffice( 2804): Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
D/Quickoffice( 2804): Processing mountline proc /proc proc rw,relatime 0 0
D/Quickoffice( 2804): Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
D/Quickoffice( 2804): Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
D/dalvikvm( 2804): GC_CONCURRENT freed 171K, 2% free 16913K/17116K, paused 3ms+1ms, total 12ms
D/Quickoffice( 2804): Processing mountline debugfs /sys/kernel/debug debugfs rw,relatime 0 0
D/Quickoffice( 2804): Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
D/Quickoffice( 2804): Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
D/Quickoffice( 2804): Processing mountline tmpfs /mnt/asec tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2804): Processing mountline tmpfs /mnt/obb tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2804): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,nosuid,nodev,relatime,data=ordered 0 0
D/Quickoffice( 2804): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2804): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2804): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2804): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
D/Quickoffice( 2804): Processing mountline /dev/fuse /mnt/shell/emulated fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2804): Processing mountline tmpfs /storage/emulated tmpfs rw,seclabel,nosuid,nodev,relatime,mode=751,gid=1028 0 0
D/Quickoffice( 2804): Processing mountline /dev/fuse /storage/emulated/0 fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2804): Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2804): Build properties are not configured for this storage definition.
D/Quickoffice( 2804): Adding the mount informaiton for listing in file manager MountedDeviceInformation [device=/dev/fuse, mountPath=/storage/emulated/legacy, fileSystemType=fuse, options=rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other, bootPriority1=0, bootPriority2=0, storageInfo=StorageDefinition [id=2010, matchPatterns=[/storage/emulated/legacy, fuse], skipPatterns=[obb], buildPatterns=[], type=INTERNAL, resourceString=2131231627, resourceStringItemized=2131231630, resourceIcon=2130838373, enabled=true], userFriendlyName=null]
D/Quickoffice( 2804): The # of mounts identified -  1
D/AndroidRuntime( 2815): 
D/AndroidRuntime( 2815): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2815): CheckJNI is OFF
D/dalvikvm( 2815): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2815): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2815): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2815): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2815): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/com.google.android.apps.docs.quickoffice.X( 2804): Checking validity of 0 items
W/ActivityManager(  760): No permission grants found for com.quickoffice.android
D/dalvikvm( 1328): GC_CONCURRENT freed 282K, 2% free 18776K/19092K, paused 2ms+2ms, total 27ms
D/dalvikvm( 2815): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
I/ActivityManager(  760): Killing 2329:com.android.chrome/u0a31 (adj 15): empty #17
D/dalvikvm( 2368): GC_CONCURRENT freed 239K, 2% free 17599K/17868K, paused 2ms+1ms, total 20ms
W/Quickoffice( 2804): Could not load clipboard.
D/ContentResolverUtil( 2804): There are 0 persisted uri permissions.
D/com.google.android.apps.docs.quickoffice.X( 2804): 0 items were valid
W/Quickoffice( 2804): Could not store clipboard.
D/ChimeraCfgMgr( 1328): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1328): Module APK com.google.android.play.games already loaded
I/Icing   ( 1328): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
D/AndroidRuntime( 2815): Calling main entry com.android.commands.am.Am
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2815
D/PermissionCache(  184): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (123 us)
D/AndroidRuntime( 2815): Shutting down VM
D/dalvikvm( 2815): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 0ms+0ms, total 2ms
I/SearchController( 1222): #onHotwordDetectorStopped(false)
I/MicrophoneInputStream( 1222): mic_close
I/ActivityManager(  760): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2842 uid=10108 gids={50108, 3003, 3001, 3002, 1028, 1015}
I/Icing   ( 1328): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
D/dalvikvm( 1222): GC_CONCURRENT freed 494K, 3% free 18541K/19088K, paused 2ms+1ms, total 22ms
I/ActivityManager(  760): Killing 1105:com.google.android.keep/u0a52 (adj 15): empty #17
I/MicroHotwordRecognitionRunner( 1222): Hotword detection finished
I/MicroHotwordRecognitionRunner( 1222): Stopping hotword detection.
V/WebViewChromiumFactoryProvider( 2842): Binding Chromium to main looper Looper (main, tid 1) {42615ae8}
I/LibraryLoader( 2842): Expected native library version number "",actual native library version number ""
I/chromium( 2842): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2842): Initializing chromium process, renderers=0
D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@442bba40:true
I/Adreno-EGL( 2842): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
W/chromium( 2842): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 2842): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2842): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2842): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2842): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2842): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 2842): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 2842): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2842): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2842): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2842): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2842): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 2842): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2842): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2842): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2842): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2842): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2842): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2842): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 2842): CordovaWebView is running on device made by: LGE
,D/OpenGLRenderer( 2842): Enabling debug mode 0
W/AwContents( 2842): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  760): Displayed com.test.thalitest/.MainActivity: +272ms
I/ActivityManager(  760): Killing 2401:com.qualcomm.timeservice/u0a68 (adj 15): empty #17
D/dalvikvm( 2842): GC_CONCURRENT freed 228K, 2% free 16855K/17116K, paused 2ms+0ms, total 16ms
D/JsMessageQueue( 2842): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 2842): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42619c20
D/dalvikvm( 2842): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42619c20
D/jxcore_app_log( 2842): JniHelper::setJavaVM(0x414fbf00), pthread_self() = 1982816360
D/JX-Cordova( 2842): jxcore cordova android initializing
I/dalvikvm( 2842): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
W/dalvikvm( 2842): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 2842): VFY: replacing opcode 0x6e at 0x0045
D/dalvikvm( 2842): GC_CONCURRENT freed 218K, 2% free 17116K/17364K, paused 1ms+2ms, total 14ms
D/dalvikvm( 2842): GC_CONCURRENT freed 158K, 2% free 17463K/17660K, paused 1ms+2ms, total 17ms
D/dalvikvm( 2842): WAIT_FOR_CONCURRENT_GC blocked 11ms
D/dalvikvm( 2842): GC_CONCURRENT freed 154K, 2% free 17807K/18004K, paused 2ms+2ms, total 19ms
D/dalvikvm( 2842): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/dalvikvm( 2842): GC_CONCURRENT freed 151K, 2% free 18150K/18348K, paused 2ms+2ms, total 20ms
D/dalvikvm( 2842): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/dalvikvm( 2842): GC_CONCURRENT freed 156K, 2% free 18484K/18692K, paused 2ms+3ms, total 24ms
D/dalvikvm( 2842): WAIT_FOR_CONCURRENT_GC blocked 16ms
D/dalvikvm( 2842): GC_CONCURRENT freed 172K, 2% free 18886K/19112K, paused 3ms+3ms, total 44ms
D/dalvikvm( 2842): WAIT_FOR_CONCURRENT_GC blocked 32ms
D/dalvikvm( 2842): GC_CONCURRENT freed 211K, 2% free 19378K/19648K, paused 2ms+2ms, total 25ms
D/dalvikvm( 2842): WAIT_FOR_CONCURRENT_GC blocked 18ms
D/dalvikvm( 2842): GC_CONCURRENT freed 270K, 2% free 19970K/20304K, paused 1ms+1ms, total 16ms
D/dalvikvm( 2842): WAIT_FOR_CONCURRENT_GC blocked 11ms
D/dalvikvm( 2842): GC_CONCURRENT freed 314K, 2% free 20707K/21092K, paused 1ms+3ms, total 22ms
D/dalvikvm( 2842): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 2842): GC_CONCURRENT freed 386K, 3% free 21612K/22076K, paused 1ms+3ms, total 27ms
,D/dalvikvm( 2842): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 2842): GC_CONCURRENT freed 987K, 5% free 22174K/23232K, paused 1ms+2ms, total 25ms
,D/dalvikvm( 2842): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm( 2842): GC_FOR_ALLOC freed 982K, 7% free 22339K/23772K, paused 20ms, total 20ms
,I/dalvikvm-heap( 2842): Grow heap (frag case) to 22.315MB for 496096-byte allocation
,D/dalvikvm( 2842): GC_FOR_ALLOC freed 6K, 6% free 22817K/24260K, paused 21ms, total 21ms
,D/dalvikvm( 2842): GC_FOR_ALLOC freed 887K, 8% free 22503K/24260K, paused 20ms, total 20ms
,I/dalvikvm-heap( 2842): Grow heap (frag case) to 22.711MB for 744140-byte allocation
,D/dalvikvm( 2842): GC_FOR_ALLOC freed 11K, 8% free 23218K/24988K, paused 21ms, total 21ms
,D/dalvikvm( 2842): GC_FOR_ALLOC freed 1289K, 9% free 22764K/24988K, paused 21ms, total 21ms
,I/dalvikvm-heap( 2842): Grow heap (frag case) to 23.321MB for 1116206-byte allocation
,D/dalvikvm( 2842): GC_FOR_ALLOC freed 6K, 9% free 23848K/26080K, paused 31ms, total 31ms
,D/dalvikvm( 2842): GC_FOR_ALLOC freed 1984K, 12% free 23180K/26080K, paused 23ms, total 23ms
,I/dalvikvm-heap( 2842): Grow heap (frag case) to 24.260MB for 1674304-byte allocation
,D/dalvikvm( 2842): GC_FOR_ALLOC freed 38K, 11% free 24777K/27716K, paused 21ms, total 21ms
,D/dalvikvm( 2842): GC_FOR_ALLOC freed 3063K, 15% free 23826K/27716K, paused 25ms, total 27ms
,I/dalvikvm-heap( 2842): Grow heap (frag case) to 25.689MB for 2511452-byte allocation
,D/dalvikvm( 2842): GC_FOR_ALLOC freed 36K, 14% free 26242K/30172K, paused 23ms, total 23ms
,D/dalvikvm( 2842): GC_CONCURRENT freed 1976K, 19% free 24642K/30172K, paused 5ms+4ms, total 53ms
,D/dalvikvm( 2842): GC_CONCURRENT freed 2587K, 19% free 24705K/30172K, paused 2ms+3ms, total 29ms
,D/dalvikvm( 2842): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 2842): GC_FOR_ALLOC freed 251K, 19% free 24614K/30172K, paused 26ms, total 26ms
,I/dalvikvm-heap( 2842): Grow heap (frag case) to 27.656MB for 3767174-byte allocation
,D/dalvikvm( 2842): GC_FOR_ALLOC freed 91K, 17% free 28201K/33852K, paused 22ms, total 22ms
,D/dalvikvm( 2842): GC_CONCURRENT freed 2662K, 24% free 25773K/33852K, paused 4ms+3ms, total 27ms
,D/dalvikvm( 2842): GC_FOR_ALLOC freed 492K, 25% free 25692K/33852K, paused 19ms, total 19ms
,W/jxcore-log( 2842): Initializing JXcore engine
,W/jxcore-log( 2842): JXcore engine is ready
,D/dalvikvm( 2842): GC_CONCURRENT freed 5365K, 32% free 23311K/33852K, paused 1ms+2ms, total 23ms
,D/dalvikvm( 2842): WAIT_FOR_CONCURRENT_GC blocked 21ms
,W/jxcore-log( 2842): Starting JXcore engine
,W/jxcore-log( 2842): Platform android
W/jxcore-log( 2842): 
,W/jxcore-log( 2842): Process ARCH arm
W/jxcore-log( 2842): 
,I/jxcore-log( 2842): JXcore Cordova bridge is ready!
I/jxcore-log( 2842): 
,W/jxcore-log( 2842): JXcore engine is started
,I/chromium( 2842): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 2842): Error!: Cannot find module '../server-address.js'
E/jxcore  ( 2842): Stack: [{"_fileName":"module.js","_functionName":"Module._oldRes","_lineNumber":"776","_columnNumber":"15","_msg":"    at Module._oldRes@module.js:776:15"},{"_fileName":"module.js","_functionName":"Module._resolveFilename","_lineNumber":"1608","_columnNumber":"1","_msg":"    at Module._resolveFilename@module.js:1608:1"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"337","_columnNumber":"18","_msg":"    at Module._load@module.js:337:18"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"11","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"}]
,I/chromium( 2842): [INFO:CONSOLE(37)] "App.js file failed to load : "Cannot find module '../server-address.js'\nError: Cannot find module '../server-address.js'\n    at Module._oldRes@module.js:776:15\n    at Module._resolveFilename@module.js:1608:1\n    at Module._load@module.js:337:18\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21\n    at Module.prototype._compile@module.js:597:10\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7"", source: file:///android_asset/www/js/thali_main.js (37)
,W/PluginManager( 2842): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 26ms. Plugin should use CordovaInterface.getThreadPool().
,W/Sidekick_LocationOracleImpl( 1222): Best location was null
,W/IInputConnectionWrapper( 2842): showStatusIcon on inactive InputConnection
,W/GCoreFlp(  986): No location to return for getLastLocation()
,W/GCoreFlp(  986): No location to return for getLastLocation()
,W/GCoreFlp(  986): No location to return for getLastLocation()
,D/dalvikvm( 1222): GC_FOR_ALLOC freed 721K, 7% free 17902K/19088K, paused 31ms, total 31ms
,I/dalvikvm-heap( 1222): Grow heap (frag case) to 18.120MB for 640016-byte allocation
,D/dalvikvm( 1222): GC_FOR_ALLOC freed <1K, 3% free 18527K/19088K, paused 18ms, total 18ms
,I/MicroHotwordRecognitionRunner( 1222): Starting hotword detection.
,W/GCoreFlp(  986): No location to return for getLastLocation()
,D/dalvikvm( 1222): GC_CONCURRENT freed 25K, 3% free 18536K/19088K, paused 3ms+5ms, total 20ms
,D/audio_hw_primary(  187): select_devices: out_snd_device(0: ) in_snd_device(35: voice-rec-mic)
D/        (  187): Failed to fetch the lookup information of the device 0000003E 
,E/ACDB-LOADER(  187): Error: ACDB AudProc vol returned = -19
,I/SearchController( 1222): #onHotwordDetectorStarted
,E/libEGL  ( 2842): call to OpenGL ES API with no current context (logged once per thread)
,D/dalvikvm( 1222): GC_CONCURRENT freed 464K, 3% free 18578K/19108K, paused 2ms+2ms, total 17ms
,I/GCM     ( 1148): GCM message com.google.android.gms 0:1449056471065614%136ddda6f9fd7ecd
,I/GCM     ( 1328): Message from 745476177629 null
,I/GCoreUlr(  986): GCM message received Intent { act=com.google.android.c2dm.intent.RECEIVE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.location.reporting.service.GcmBroadcastReceiver (has extras) }
,I/GCoreUlr(  986): Received GCM notification for account#2# timestamp:1449056471057
,I/GCoreUlr(  986): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_INSISTENT_SYNC cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{account=Account {name=thalitester@gmail.com, type=com.google}, label=GcmBroadcastReceiver}]
,I/GCoreUlr(  986): DispatchingService.onCreate()
,D/dalvikvm(  986): GC_CONCURRENT freed 406K, 3% free 17909K/18436K, paused 2ms+6ms, total 22ms
I/dalvikvm(  986): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.location.reporting.k.a
W/dalvikvm(  986): VFY: unable to resolve virtual method 1309: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm(  986): VFY: replacing opcode 0x6e at 0x030d
,W/BaseAppContext(  986): Using Auth Proxy for data requests.
,W/dalvikvm(  986): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  986): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  986): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm(  986): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm(  986): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm(  986): VFY: replacing opcode 0x6e at 0x00bb
,V/GLSActivity( 1148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1148): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm(  986): GC_CONCURRENT freed 342K, 3% free 18009K/18460K, paused 2ms+2ms, total 17ms
,I/dalvikvm(  986): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm(  986): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm(  986): VFY: replacing opcode 0x6e at 0x0033
,D/dalvikvm(  986): GC_CONCURRENT freed 386K, 3% free 18043K/18524K, paused 3ms+3ms, total 28ms
,D/ConnectivityService(  760): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/dalvikvm(  760): GC_EXPLICIT freed 23253K, 52% free 27247K/56164K, paused 3ms+4ms, total 92ms
,D/dalvikvm(  986): GC_CONCURRENT freed 377K, 3% free 18066K/18564K, paused 5ms+1ms, total 19ms
,I/GCoreUlr(  986): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/GCoreUlr(  986): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr(  986): Unbound from all location providers
,I/GCoreUlr(  986): DispatchingService.onDestroy()
I/GCoreUlr(  986): Stopping handler for UlrDispSvcFast
,I/GCoreUlr(  986): Stopping handler for UlrDispSvcSlow
,I/GCoreUlr(  986): Unbound from all location providers
,D/Finsky  ( 2488): [1] 5.onFinished: Installation state replication succeeded.
,D/dalvikvm( 1328): GC_CONCURRENT freed 482K, 3% free 18868K/19380K, paused 3ms+1ms, total 71ms
,D/dalvikvm( 1148): GC_CONCURRENT freed 399K, 3% free 18277K/18772K, paused 5ms+1ms, total 52ms
,I/VacuumService( 1148): Vacuum at: now=1449056474748 tag=VacuumService
,D/UdcCache:FPQuery( 1328): Bootstrapping UDC settings cache for all accounts
,D/dalvikvm( 1148): GC_CONCURRENT freed 477K, 4% free 18281K/18860K, paused 2ms+3ms, total 20ms
,D/GetConfigurationSnapshotOperation( 1148): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/dalvikvm( 1148): GC_CONCURRENT freed 441K, 4% free 18289K/18860K, paused 1ms+2ms, total 17ms
,I/PhenotypeFlagCommitter( 1148): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1148): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1148): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 1148): GC_CONCURRENT freed 371K, 3% free 18470K/18940K, paused 2ms+4ms, total 29ms
,D/dalvikvm( 1148): GC_CONCURRENT freed 471K, 3% free 18519K/19084K, paused 4ms+3ms, total 19ms
,D/dalvikvm( 1148): GC_CONCURRENT freed 429K, 3% free 18620K/19144K, paused 2ms+2ms, total 16ms
,D/dalvikvm( 1148): GC_CONCURRENT freed 581K, 4% free 18652K/19328K, paused 1ms+5ms, total 23ms
,W/Uploader( 1148):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1148): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 1148): GC_CONCURRENT freed 622K, 4% free 18601K/19356K, paused 3ms+4ms, total 19ms
,D/GetCommittedConfigurationOperation( 1148): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 1148): GC_FOR_ALLOC freed 533K, 5% free 18556K/19356K, paused 30ms, total 31ms
,D/dalvikvm( 1148): GC_FOR_ALLOC freed 184K, 5% free 18404K/19356K, paused 26ms, total 26ms
,D/dalvikvm( 1328): GC_CONCURRENT freed 591K, 4% free 18877K/19504K, paused 13ms+1ms, total 30ms
,I/rmt_storage(  180): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb89a5160
I/rmt_storage(  180): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  180): wakelock acquired: 1, error no: 2
,I/rmt_storage(  180): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1197845984)
,I/rmt_storage(  180): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  180): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  180): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1197845984) wakelock released: 1, error no: 0
I/rmt_storage(  180): 
,I/rmt_storage(  180): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb89a5160
,I/PowerManagerService(  760): Going to sleep due to screen timeout...
,I/Adreno-EGL(  760): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/SurfaceFlinger(  184): Screen released, type=0 flinger=0xb79cf450
,D/qdhwcomposer(  184): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  184): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  760): Excessive delay in blankDisplay() while turning screen off: 302ms
,V/KeyguardServiceDelegate(  760): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@42baf970)
,V/KeyguardServiceDelegate(  760): **** SHOWN CALLED ****
I/WindowManager(  760): No lock screen! windowToken=null
,I/SearchController( 1222): #onHotwordDetectorStopped(false)
,I/MicrophoneInputStream( 1222): mic_close
,I/ActivityManager(  760): Killing 2205:com.google.android.music:main/u0a58 (adj 15): empty #17
,D/NfcService( 1051): NFC-C OFF
F/ActivityManager(  760): Service ServiceRecord{42e2d1c0 u0 com.google.android.music/.download.ArtDownloadQueueService} in process ProcessRecord{42ccbca0 2205:com.google.android.music:main/u0a58} not same as in map: null
,I/MicroHotwordRecognitionRunner( 1222): Hotword detection finished
,I/MicroHotwordRecognitionRunner( 1222): Stopping hotword detection.
,F/ActivityManager(  760): Service ServiceRecord{42d5a338 u0 com.google.android.music/.download.cache.ArtCacheService} in process ProcessRecord{42ccbca0 2205:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  760): Service ServiceRecord{42c81240 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{42ccbca0 2205:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  760): Service ServiceRecord{42c2c6b8 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{42ccbca0 2205:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  760): Service ServiceRecord{42c0b7b0 u0 com.google.android.music/.download.artwork.ArtDownloadService} in process ProcessRecord{42ccbca0 2205:com.google.android.music:main/u0a58} not same as in map: null
,D/dalvikvm( 1222): GC_CONCURRENT freed 1109K, 6% free 17986K/19128K, paused 2ms+2ms, total 13ms
,D/ConnectivityService(  760): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  760): Done.
,D/ConnectivityService(  760): Setting timer for 720seconds
,D/ConnectivityService(  760): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,I/dalvikvm(  760): Jit: resizing JitTable from 8192 to 16384
I/ProcessStatsService(  760): Prepared write state in 44ms
,I/ProcessStatsService(  760): Prepared write state in 9ms
,I/ProcessStatsService(  760): Pruning old procstats: /data/system/procstats/state-2015-12-01-12-15-49.bin
,I/ActivityManager(  760): Killing 2700:com.google.android.partnersetup/u0a11 (adj 15): empty for 1801s
,I/ActivityManager(  760): Killing 953:android.process.acore/u0a3 (adj 15): empty for 1801s
,I/ActivityManager(  760): Killing 2677:com.android.defcontainer/u0a4 (adj 15): empty for 1801s
,I/ActivityManager(  760): Killing 2293:com.android.providers.calendar/u0a1 (adj 15): empty for 1821s
,I/ActivityManager(  760): Killing 1971:com.google.android.talk/u0a51 (adj 15): empty for 1841s
,I/ActivityManager(  760): Killing 1784:com.google.android.calendar/u0a28 (adj 15): empty for 1841s
,I/ActivityManager(  760): Killing 1867:com.google.android.gm/u0a41 (adj 15): empty for 1841s
,F/ActivityManager(  760): Service ServiceRecord{42db92a0 u0 com.google.android.talk/com.google.android.libraries.hangouts.video.CallService} in process ProcessRecord{42c289c0 1971:com.google.android.talk/u0a51} not same as in map: null
,TIME-OUT KILL (timeout was 1800000ms)
```
