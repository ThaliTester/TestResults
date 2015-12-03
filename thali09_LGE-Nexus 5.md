#### Test 525393149f38b37_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
I/dalvikvm( 1317): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1317): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1317): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1317): VFY: unable to resolve new-instance 2320 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
D/dalvikvm( 1317): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1317): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1317): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
D/dalvikvm( 1317): DexOpt: unable to opt direct call 0x3207 at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
D/dalvikvm( 2438): Trying to load lib /data/app-lib/com.google.android.gms-2/libgmscore.so 0x42a5af10
D/dalvikvm( 2438): Shared lib '/data/app-lib/com.google.android.gms-2/libgmscore.so' already loaded in same CL 0x42a5af10
D/dalvikvm( 2438): Trying to load lib /data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so 0x42a5af10
D/dalvikvm( 2438): Shared lib '/data/app-lib/com.google.android.gms-2/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42a5af10
D/dalvikvm( 2438): GC_CONCURRENT freed 446K, 3% free 17943K/18424K, paused 2ms+3ms, total 16ms
D/dalvikvm( 2438): GC_FOR_ALLOC freed 31K, 3% free 18001K/18424K, paused 11ms, total 11ms
D/ChimeraCfgMgr( 1317): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1317): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1317): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/AsyncTaskServiceImpl( 1317): Submit a task: h
D/ChimeraCfgMgr( 1317): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 1317): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/h       ( 1317): Processing package: com.test.thalitest
D/GassUtils( 1317): Found app info for package com.test.thalitest:18. Hash: 01e4d8ac61718f1dcdc950940ea39ae21caf015e512d4d8080feb7f016346367
D/h       ( 1317): Found info for package com.test.thalitest in db.
,I/PeopleContactsSync( 1317): CP2 sync disabled
I/dalvikvm( 1317): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1317): VFY: unable to resolve virtual method 34: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1317): VFY: replacing opcode 0x6e at 0x000e
--------- beginning of /dev/log/system
I/ActivityManager(  771): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2490 uid=10065 gids={50065, 3003, 1028, 1015}
W/BaseAppContext( 1317): Using Auth Proxy for data requests.
W/BaseAppContext( 1317): Using Auth Proxy for data requests.
D/dalvikvm( 1317): GC_CONCURRENT freed 321K, 2% free 18432K/18804K, paused 3ms+6ms, total 25ms
D/dalvikvm( 1100): GC_CONCURRENT freed 347K, 3% free 18137K/18628K, paused 2ms+1ms, total 31ms
W/BaseAppContext( 1317): Using Auth Proxy for data requests.
W/BaseAppContext( 1317): Using Auth Proxy for data requests.
W/BaseAppContext( 1317): Using Auth Proxy for data requests.
W/BaseAppContext( 1317): Using Auth Proxy for data requests.
I/ProviderInstaller( 2438): Installed default security provider GmsCore_OpenSSL
W/Quickoffice( 2490): Cleanup of storage: done
D/com.google.android.apps.docs.quickoffice.X( 2490): Loading recent documents list
D/Quickoffice( 2490): The number of lines present in  /proc/mount 21
D/Quickoffice( 2490): Parsing the storagedefinition.xml.
D/Quickoffice( 2490): # of Storagedefinitions - 35
D/Quickoffice( 2490): The # of storage definitions available - 35
D/Quickoffice( 2490): Processing mountline rootfs / rootfs ro,relatime 0 0
D/Quickoffice( 2490): Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
D/Quickoffice( 2490): Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
D/Quickoffice( 2490): Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
D/Quickoffice( 2490): Processing mountline proc /proc proc rw,relatime 0 0
D/Quickoffice( 2490): Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
D/Quickoffice( 2490): Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
D/Quickoffice( 2490): Processing mountline debugfs /sys/kernel/debug debugfs rw,relatime 0 0
D/Quickoffice( 2490): Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
D/Quickoffice( 2490): Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
D/Quickoffice( 2490): Processing mountline tmpfs /mnt/asec tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2490): Processing mountline tmpfs /mnt/obb tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2490): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,nosuid,nodev,relatime,data=ordered 0 0
D/Quickoffice( 2490): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2490): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/dalvikvm( 1317): GC_CONCURRENT freed 278K, 2% free 18643K/18956K, paused 2ms+3ms, total 18ms
D/Quickoffice( 2490): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2490): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
D/Quickoffice( 2490): Processing mountline /dev/fuse /mnt/shell/emulated fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2490): Processing mountline tmpfs /storage/emulated tmpfs rw,seclabel,nosuid,nodev,relatime,mode=751,gid=1028 0 0
D/Quickoffice( 2490): Processing mountline /dev/fuse /storage/emulated/0 fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2490): Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2490): Build properties are not configured for this storage definition.
D/Quickoffice( 2490): Adding the mount informaiton for listing in file manager MountedDeviceInformation [device=/dev/fuse, mountPath=/storage/emulated/legacy, fileSystemType=fuse, options=rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other, bootPriority1=0, bootPriority2=0, storageInfo=StorageDefinition [id=2010, matchPatterns=[/storage/emulated/legacy, fuse], skipPatterns=[obb], buildPatterns=[], type=INTERNAL, resourceString=2131231627, resourceStringItemized=2131231630, resourceIcon=2130838373, enabled=true], userFriendlyName=null]
D/Quickoffice( 2490): The # of mounts identified -  1
D/dalvikvm( 2490): GC_CONCURRENT freed 178K, 2% free 16922K/17132K, paused 2ms+1ms, total 15ms
D/AndroidRuntime( 2511): 
D/AndroidRuntime( 2511): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2511): CheckJNI is OFF
D/com.google.android.apps.docs.quickoffice.X( 2490): Checking validity of 0 items
D/ContentResolverUtil( 2490): There are 0 persisted uri permissions.
D/com.google.android.apps.docs.quickoffice.X( 2490): 0 items were valid
D/dalvikvm( 2511): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2511): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2511): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2511): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2511): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
W/ActivityManager(  771): No permission grants found for com.quickoffice.android
I/ActivityManager(  771): Killing 1966:com.google.android.apps.maps/u0a57 (adj 15): empty #17
W/Quickoffice( 2490): Could not load clipboard.
D/dalvikvm( 2511): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
W/Quickoffice( 2490): Could not store clipboard.
D/ChimeraCfgMgr( 1317): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1317): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 2511): Calling main entry com.android.commands.am.Am
I/ActivityManager(  771): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2511
D/PermissionCache(  182): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (219 us)
I/Icing   ( 1317): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
D/AndroidRuntime( 2511): Shutting down VM
D/dalvikvm( 2511): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 0ms+0ms, total 2ms
I/ActivityManager(  771): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2539 uid=10108 gids={50108, 3003, 3001, 3002, 1028, 1015}
I/SearchController( 1193): #onHotwordDetectorStopped(false)
I/MicrophoneInputStream( 1193): mic_close
D/dalvikvm( 1193): GC_CONCURRENT freed 410K, 3% free 18250K/18768K, paused 1ms+4ms, total 16ms
D/dalvikvm(  980): GC_CONCURRENT freed 364K, 3% free 17905K/18372K, paused 2ms+2ms, total 19ms
V/WebViewChromiumFactoryProvider( 2539): Binding Chromium to main looper Looper (main, tid 1) {429e5510}
I/LibraryLoader( 2539): Expected native library version number "",actual native library version number ""
I/chromium( 2539): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2539): Initializing chromium process, renderers=0
I/ActivityManager(  771): Killing 2000:com.google.android.youtube/u0a71 (adj 15): empty #17
I/MicroHotwordRecognitionRunner( 1193): Stopping hotword detection.
I/MicroHotwordRecognitionRunner( 1193): Hotword detection finished
F/ActivityManager(  771): Service ServiceRecord{42ff6fd8 u0 com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService} in process ProcessRecord{42ff8e90 2000:com.google.android.youtube/u0a71} not same as in map: null
D/BluetoothManagerService(  771): Message: 20
D/BluetoothManagerService(  771): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4477cb48:true
D/BluetoothAdapter( 2539): 1117761984: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 2539): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
W/chromium( 2539): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/Icing   ( 1317): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
I/dalvikvm( 2539): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2539): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2539): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2539): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2539): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 2539): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 2539): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2539): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2539): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2539): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2539): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 2539): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
D/dalvikvm( 1317): GC_CONCURRENT freed 431K, 3% free 18741K/19208K, paused 1ms+1ms, total 20ms
I/dalvikvm( 2539): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2539): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2539): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2539): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2539): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2539): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 2539): CordovaWebView is running on device made by: LGE
,D/OpenGLRenderer( 2539): Enabling debug mode 0
,W/AwContents( 2539): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  771): Displayed com.test.thalitest/.MainActivity: +285ms
,I/ActivityManager(  771): Killing 1714:com.google.android.deskclock/u0a33 (adj 15): empty #17
,D/JsMessageQueue( 2539): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 2539): GC_CONCURRENT freed 243K, 2% free 16893K/17168K, paused 2ms+2ms, total 19ms
,D/dalvikvm( 2539): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x429ea0a0
,D/dalvikvm( 2539): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x429ea0a0
,D/jxcore_app_log( 2539): JniHelper::setJavaVM(0x41986ed0), pthread_self() = 1984208280
,D/JX-Cordova( 2539): jxcore cordova android initializing
I/dalvikvm( 2539): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
W/dalvikvm( 2539): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 2539): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 2539): GC_CONCURRENT freed 213K, 2% free 17192K/17436K, paused 2ms+1ms, total 11ms
,D/dalvikvm( 2539): GC_CONCURRENT freed 159K, 2% free 17536K/17736K, paused 1ms+1ms, total 10ms
,D/dalvikvm( 2539): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 2539): GC_CONCURRENT freed 154K, 2% free 17879K/18076K, paused 2ms+1ms, total 12ms
,D/dalvikvm( 2539): WAIT_FOR_CONCURRENT_GC blocked 3ms
,D/dalvikvm( 2539): GC_CONCURRENT freed 151K, 2% free 18222K/18420K, paused 2ms+1ms, total 13ms
,D/dalvikvm( 2539): WAIT_FOR_CONCURRENT_GC blocked 2ms
,D/dalvikvm( 2539): GC_CONCURRENT freed 157K, 2% free 18558K/18764K, paused 1ms+1ms, total 12ms
,D/dalvikvm( 2539): WAIT_FOR_CONCURRENT_GC blocked 5ms
,D/ConnectivityService(  771): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  771): Done.
,D/ConnectivityService(  771): Setting timer for 720seconds
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
D/dalvikvm( 2539): GC_CONCURRENT freed 179K, 2% free 18979K/19212K, paused 2ms+1ms, total 25ms
D/dalvikvm( 2539): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 2539): GC_CONCURRENT freed 221K, 2% free 19491K/19772K, paused 1ms+1ms, total 14ms
,D/dalvikvm( 2539): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 2539): GC_CONCURRENT freed 279K, 2% free 20107K/20452K, paused 1ms+2ms, total 23ms
,D/dalvikvm( 2539): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 2539): GC_CONCURRENT freed 327K, 2% free 20874K/21276K, paused 2ms+2ms, total 20ms
,D/dalvikvm( 2539): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 2539): GC_CONCURRENT freed 403K, 3% free 21815K/22300K, paused 1ms+1ms, total 29ms
,D/dalvikvm( 2539): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 2539): GC_CONCURRENT freed 1227K, 6% free 22256K/23552K, paused 1ms+2ms, total 26ms
,D/dalvikvm( 2539): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 2539): GC_CONCURRENT freed 1464K, 7% free 22530K/24140K, paused 2ms+1ms, total 22ms
,D/dalvikvm( 2539): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 2539): GC_FOR_ALLOC freed 129K, 7% free 22456K/24140K, paused 18ms, total 18ms
,I/dalvikvm-heap( 2539): Grow heap (frag case) to 22.666MB for 744140-byte allocation
,D/dalvikvm( 2539): GC_FOR_ALLOC freed 2K, 7% free 23180K/24868K, paused 19ms, total 19ms
,D/dalvikvm( 2539): GC_FOR_ALLOC freed 1254K, 9% free 22761K/24868K, paused 19ms, total 19ms
,I/dalvikvm-heap( 2539): Grow heap (frag case) to 23.318MB for 1116206-byte allocation
,D/dalvikvm( 2539): GC_FOR_ALLOC freed 5K, 9% free 23845K/25960K, paused 20ms, total 20ms
,D/dalvikvm( 2539): GC_FOR_ALLOC freed 1985K, 11% free 23177K/25960K, paused 20ms, total 20ms
,I/dalvikvm-heap( 2539): Grow heap (frag case) to 24.256MB for 1674304-byte allocation
,D/dalvikvm( 2539): GC_FOR_ALLOC freed 1096K, 15% free 23715K/27596K, paused 28ms, total 28ms
,D/dalvikvm( 2539): GC_FOR_ALLOC freed 2006K, 14% free 23824K/27596K, paused 22ms, total 22ms
,I/dalvikvm-heap( 2539): Grow heap (frag case) to 25.687MB for 2511452-byte allocation
,D/dalvikvm( 2539): GC_CONCURRENT freed 141K, 14% free 26136K/30052K, paused 4ms+1ms, total 24ms
D/dalvikvm( 2539): WAIT_FOR_CONCURRENT_GC blocked 10ms
D/dalvikvm( 2539): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 2539): GC_CONCURRENT freed 4531K, 18% free 24752K/30052K, paused 2ms+7ms, total 51ms
,D/dalvikvm( 2539): WAIT_FOR_CONCURRENT_GC blocked 41ms
,D/dalvikvm( 2539): GC_FOR_ALLOC freed 39K, 18% free 24746K/30052K, paused 19ms, total 19ms
,I/dalvikvm-heap( 2539): Grow heap (frag case) to 27.785MB for 3767174-byte allocation
,D/dalvikvm( 2539): GC_FOR_ALLOC freed 4K, 16% free 28421K/33732K, paused 22ms, total 22ms
,D/dalvikvm( 2539): GC_CONCURRENT freed 2742K, 23% free 26051K/33732K, paused 3ms+12ms, total 44ms
,W/jxcore-log( 2539): Initializing JXcore engine
,W/jxcore-log( 2539): JXcore engine is ready
,D/dalvikvm( 2539): GC_CONCURRENT freed 810K, 16% free 28361K/33732K, paused 2ms+12ms, total 26ms
,D/dalvikvm( 2539): WAIT_FOR_CONCURRENT_GC blocked 18ms
,W/jxcore-log( 2539): Starting JXcore engine
,W/jxcore-log( 2539): Platform android
W/jxcore-log( 2539): 
,W/jxcore-log( 2539): Process ARCH arm
W/jxcore-log( 2539): 
,I/jxcore-log( 2539): JXcore Cordova bridge is ready!
I/jxcore-log( 2539): 
,W/jxcore-log( 2539): JXcore engine is started
,I/chromium( 2539): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 2539): Toggling radios to true
I/jxcore-log( 2539): 
D/BluetoothManagerService(  771): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  771): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  771): Message: 1
,D/BluetoothManagerService(  771): MESSAGE_ENABLE: mBluetooth = null
D/WifiService(  771): setWifiEnabled: true pid=2539, uid=10108
,D/SoftapController(  179): Softap fwReload - Ok
,I/jxcore-log( 2539): Radios toggled
I/jxcore-log( 2539): 
D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring down wlan0
,I/ActivityManager(  771): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=2593 uid=1002 gids={41002, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008}
D/WifiMonitor(  771): startMonitoring(wlan0) with mConnected = false
,E/WifiHW  (  771): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,I/ActivityManager(  771): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=2604 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
,I/wpa_supplicant( 2599): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 2599): rfkill: Cannot open RFKILL control device
,D/AdapterServiceConfig( 2593): Adding HeadsetService
D/AdapterServiceConfig( 2593): Adding A2dpService
D/AdapterServiceConfig( 2593): Adding HidService
D/AdapterServiceConfig( 2593): Adding HealthService
D/AdapterServiceConfig( 2593): Adding PanService
,D/AdapterServiceConfig( 2593): Adding GattService
,D/AdapterServiceConfig( 2593): Adding BluetoothMapService
,D/BluetoothAdapterService( 2593): REFCOUNT: CREATED. INSTANCE_COUNT1
D/BluetoothManagerService(  771): Message: 20
,D/BluetoothManagerService(  771): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4472ade0:true
,D/BluetoothAdapterState( 2593): make
,I/bluedroid( 2593): init
,I/BluetoothAdapterState( 2593): Entering OffState
,I/bte_conf( 2593): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bluedroid( 2593): get_profile_interface socket
D/BluetoothManagerService(  771): Message: 20
I/GKI_LINUX( 2593): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
D/BluetoothManagerService(  771): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@447281d0:true
,I/BluetoothAdapterProperties( 2593): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 2593): Address is:34:FC:EF:11:B1:66
,I/BluetoothAdapterProperties( 2593): adapterPropertyChangedCallback with type:1 len:7
,D/BluetoothManagerService(  771): Bluetooth Adapter name changed to Nexus 5
,D/BluetoothManagerService(  771): Stored Bluetooth name: Nexus 5
D/BluetoothManagerService(  771): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  771): Message: 40
,D/BluetoothManagerService(  771): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 2593): config_hci_snoop_log
D/BluetoothManagerService(  771): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  771): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/BluetoothAdapterProperties( 2593): Name is: Nexus 5
D/BluetoothAdapterState( 2593): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 2593): Setting state to 11
,I/BluetoothAdapterState( 2593): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 2593): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  771): Message: 60
D/BluetoothManagerService(  771): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  771): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 2593): make
,I/BluetoothBondStateMachine( 2593): StableState(): Entering Off State
,D/BluetoothHeadset(  771): Proxy object connected
D/BluetoothHeadset( 1006): Proxy object connected
D/BluetoothHeadset( 1006): Proxy object connected
,D/BluetoothHeadset( 1006): Proxy object connected
I/BluetoothAdapterState( 2593): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/BluetoothManagerService(  771): Message: 30
,D/HeadsetService( 2593): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 2593): classInitNative: succeeds
,D/HeadsetStateMachine( 2593): make
,D/BluetoothManagerService(  771): Message: 30
,I/bluedroid( 2593): get_profile_interface handsfree
W/ContextImpl( 2604): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
,W/ContextImpl( 2604): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
D/LocalBluetoothProfileManager( 2604): Adding local MAP profile
D/BluetoothMap( 2604): Create BluetoothMap proxy object
D/BluetoothManagerService(  771): Message: 30
D/BluetoothA2dp(  771): Proxy object connected
D/A2dpService( 2593): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 2593): classInitNative: succeeds
V/Avrcp   ( 2593): make
,I/bluedroid( 2593): get_profile_interface avrcp
,I/BluetoothA2dpServiceJni( 2593): classInitNative: succeeds
D/A2dpStateMachine( 2593): make
I/bluedroid( 2593): get_profile_interface a2dp
,I/GKI_LINUX( 2593): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothManagerService(  771): Message: 30
W/ContextImpl( 2604): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1376 
,W/ContextImpl( 2604): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/LocalBluetoothProfileManager( 2604): LocalBluetoothProfileManager construction complete
D/A2dpStateMachine( 2593): Enter Disconnected: -2
I/BluetoothHidServiceJni( 2593): classInitNative: succeeds
D/HidService( 2593): Received start request. Starting profile...
I/bluedroid( 2593): get_profile_interface hidhost
I/BluetoothHealthServiceJni( 2593): classInitNative: succeeds
D/HealthService( 2593): Received start request. Starting profile...
I/bluedroid( 2593): get_profile_interface health
I/BluetoothPanServiceJni( 2593): classInitNative(L105): succeeds
D/BluetoothPan(  771): BluetoothPAN Proxy object connected
D/PanService( 2593): Received start request. Starting profile...
D/BluetoothPanServiceJni( 2593): initializeNative(L110): pan
I/bluedroid( 2593): get_profile_interface pan
D/BluetoothTethering(  771): got CMD_CHANNEL_HALF_CONNECTED
I/BtGatt.JNI( 2593): classInitNative(L684): classInitNative: Success!
D/BtGatt.DebugUtils( 2593): handleDebugAction() action=null
D/BtGatt.GattService( 2593): Received start request. Starting profile...
D/BtGatt.GattService( 2593): start()
I/bluedroid( 2593): get_profile_interface gatt
D/BluetoothPan( 2604): BluetoothPAN Proxy object connected
,D/BluetoothMapService( 2593): Received start request. Starting profile...
,D/BluetoothMapService( 2593): start()
,D/PanProfile( 2604): Bluetooth service connected
I/ActivityManager(  771): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=2643 uid=10052 gids={50052, 3003, 1028, 1015}
I/ActivityManager(  771): Killing 1844:com.google.android.email/u0a36 (adj 15): empty #17
,D/BluetoothAdapterService( 2593): Profile still not running:com.android.bluetooth.hdp.HealthService
,D/HeadsetPhoneState( 2593): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/BluetoothInputDevice( 2604): Proxy object connected
,D/HidProfile( 2604): Bluetooth service connected
,D/BluetoothAdapterService( 2593): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 2593): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 2593): Profile still not running:com.android.bluetooth.map.BluetoothMapService
,D/BluetoothAdapterService( 2593): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2593): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothMap( 2604): Proxy object connected
D/BluetoothAdapterState( 2593): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
D/MapProfile( 2604): Bluetooth service connected
D/BluetoothMap( 2604): getConnectedDevices()
I/bluedroid( 2593): enable
D/BluetoothMap( 2604): Bluetooth is Not enabled
I/bt_hci_bdroid( 2593): init
I/bt_vendor( 2593): init
I/bt_vnd_conf( 2593): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 2593): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
I/bt_hci_bdroid( 2593): bt_hc_worker_thread started
,I/bt_userial_vendor( 2593): userial vendor open: opening /dev/ttyHS99
,I/GKI_LINUX( 2593): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 2593): btu_task pending for preload complete event
,I/bt_userial_vendor( 2593): device fd = 65 open
,I/bt_hwcfg( 2593): bt vendor lib: set UART baud 4000000
,D/dalvikvm(  771): GC_EXPLICIT freed 22422K, 53% free 26223K/55588K, paused 2ms+5ms, total 105ms
,D/bt_hwcfg( 2593): Chipset BCM4335C0
,D/bt_hwcfg( 2593): Target name = [BCM4335C0]
,I/bt_hwcfg( 2593): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,D/AuthorizationBluetoothService( 1100): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/dalvikvm( 2643): GC_CONCURRENT freed 201K, 2% free 16927K/17160K, paused 3ms+3ms, total 24ms
W/BroadcastQueue(  771): Permission Denial: receiving Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 (has extras) } to com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver requires android.permission.BLUETOOTH due to sender android (uid 1000)
I/ActivityManager(  771): Killing 1673:com.google.android.calendar/u0a28 (adj 15): empty #17
,I/bt_hwcfg( 2593): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 2593): Settlement delay -- 100 ms
,I/bt_hwcfg( 2593): bt vendor lib: set UART baud 4000000
,I/bt_hwcfg( 2593): Setting local bd addr to 34:FC:EF:11:B1:66
,I/bt_hwcfg( 2593): vendor lib fwcfg completed
,I/bt-btu  ( 2593): btu_task received preload complete event
,I/        ( 2593): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 2593): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 2593): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 2593): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 2593): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 2593): BTE_InitTraceLevels -- TRC_A2D
I/        ( 2593): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 2593): BTE_InitTraceLevels -- TRC_BTM
,I/        ( 2593): BTE_InitTraceLevels -- TRC_GAP
I/        ( 2593): BTE_InitTraceLevels -- TRC_PAN
I/        ( 2593): BTE_InitTraceLevels -- TRC_SDP
I/        ( 2593): BTE_InitTraceLevels -- TRC_GATT
I/        ( 2593): BTE_InitTraceLevels -- TRC_SMP
I/        ( 2593): BTE_InitTraceLevels -- TRC_BTAPP
,I/        ( 2593): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 2593): BTM_SecRegister:p_cb_info->p_le_callback == 0x750a9f8d 
,E/bt-btm  ( 2593): BTM_SecRegister: btm_cb.api.p_le_callback = 0x750a9f8d 
,E/bt-btif ( 2593): Calling BTA_HhEnable
,E/bt-btif ( 2593): btif_storage_get_adapter_property service_mask:0x140040
I/BluetoothAdapterProperties( 2593): adapterPropertyChangedCallback with type:2 len:6
,D/BluetoothAdapterProperties( 2593): Address is:34:FC:EF:11:B1:66
,I/BluetoothAdapterProperties( 2593): adapterPropertyChangedCallback with type:1 len:7
,D/BluetoothManagerService(  771): Bluetooth Adapter name changed to Nexus 5
,D/BluetoothManagerService(  771): Stored Bluetooth name: Nexus 5
D/BluetoothAdapterProperties( 2593): Name is: Nexus 5
,I/BluetoothAdapterProperties( 2593): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothAdapterProperties( 2593): Scan Mode:20
I/BluetoothAdapterProperties( 2593): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 2593): Discoverable Timeout:120
,I/BluetoothAdapterProperties( 2593): adapterPropertyChangedCallback with type:8 len:36
,D/BluetoothAdapterProperties( 2593): Adding bonded device:F4:F1:E1:5C:3B:E2
,D/BluetoothAdapterProperties( 2593): Adding bonded device:F8:95:C7:87:85:54
,D/BluetoothAdapterProperties( 2593): Adding bonded device:E0:DB:10:1F:C9:5E
,D/BluetoothAdapterProperties( 2593): Adding bonded device:08:EC:A9:50:76:27
,D/BluetoothAdapterProperties( 2593): Adding bonded device:F8:95:C7:87:3C:51
,D/BluetoothAdapterProperties( 2593): Adding bonded device:58:2A:F7:ED:96:BE
,I/BluetoothAdapterProperties( 2593): adapterPropertyChangedCallback with type:3 len:48
,E/BluetoothRemoteDevices( 2593): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,E/BluetoothRemoteDevices( 2593): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
,E/BluetoothRemoteDevices( 2593): devicePropertyChangedCallback: bdDevice: E0:DB:10:1F:C9:5E, value is empty for type: 10
,E/BluetoothRemoteDevices( 2593): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
,E/BluetoothRemoteDevices( 2593): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
,E/BluetoothRemoteDevices( 2593): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,I/bt_hwcfg( 2593): SCO PCM configure {0, 4, 0, 0, 0}
,I/bte_conf( 2593): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 2593): [1] primary_record=1 vendor_id=0x000F vendor_id_source=0x0001 product_id=0x1200 version=0x1436
I/bte_conf( 2593): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 2593): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/BluetoothAdapterState( 2593): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 2593): ScanMode =  20
,D/BluetoothAdapterProperties( 2593): State =  11
D/BluetoothAdapterProperties( 2593): Setting state to 12
D/BluetoothPanServiceJni( 2593): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
I/BluetoothAdapterState( 2593): Bluetooth adapter state changed: 11-> 12
I/BluetoothAdapterProperties( 2593): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothAdapterService( 2593): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  771): Message: 60
D/BluetoothManagerService(  771): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  771): Broadcasting onBluetoothStateChange(true) to 10 receivers.
,D/BluetoothPan(  771): onBluetoothStateChange(on) call bindService
,I/BluetoothAdapterState( 2593): Entering On State
D/BluetoothAdapterProperties( 2593): Scan Mode:21
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
I/BluetoothAdapterProperties( 2593): adapterPropertyChangedCallback with type:9 len:4
,W/ContextImpl(  771): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:192 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:484 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1129 
D/BluetoothAdapterProperties( 2593): Discoverable Timeout:120
D/BluetoothHeadset(  771): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1006): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1006): onBluetoothStateChange: up=true
D/BluetoothA2dp(  771): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1006): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
D/BluetoothInputDevice( 2604): onBluetoothStateChange: up=true
,D/BluetoothPan( 2604): onBluetoothStateChange(on) call bindService
,W/ContextImpl( 2604): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:192 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
D/BluetoothMap( 2604): onBluetoothStateChange: up=true
D/BluetoothPbap( 2604): onBluetoothStateChange: up=true
,W/ContextImpl( 2604): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap$1.onBluetoothStateChange:132 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
E/bt_h4   ( 2593): vendor lib postload completed
,D/BluetoothManagerService(  771): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  771): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothMapService( 2593): onReceive
D/BluetoothMapService( 2593): STATE_ON
,D/BluetoothMapService( 2593): Map Service startRfcommSocketListener
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/Tethering(  771): sendTetherStateChangedBroadcast 1, 0, 0
,D/BluetoothManagerService(  771): Message: 40
,D/BluetoothManagerService(  771): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapService( 2593): Map Service initSocket
,D/BluetoothManagerService(  771): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/dalvikvm( 2593): GC_CONCURRENT freed 255K, 2% free 16838K/17120K, paused 13ms+1ms, total 55ms
,W/BluetoothAdapter( 2593): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 2593): SOCK FLAG = 1 ***********************
,D/BluetoothMapService( 2593): Accepting socket connection...
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/LocalBluetoothProfileManager( 2604): Adding local A2DP profile
,D/BluetoothManagerService(  771): Message: 30
,W/ContextImpl( 2604): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
D/LocalBluetoothProfileManager( 2604): Adding local HEADSET profile
,D/BluetoothManagerService(  771): Message: 30
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
I/wpa_supplicant( 2599): rfkill: Cannot open RFKILL control device
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/BluetoothMap( 2604): getConnectedDevices()
,W/ContextImpl( 2604): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
D/BluetoothMap( 2604): getConnectionState(58:2A:F7:ED:96:BE)
D/MapProfile( 2604): getConnectionStatus: status is: 0
,D/dalvikvm( 2604): GC_CONCURRENT freed 358K, 3% free 16830K/17224K, paused 3ms+1ms, total 13ms
,D/dalvikvm( 2604): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/BluetoothMap( 2604): getConnectedDevices()
,D/BluetoothMap( 2604): getConnectionState(F8:95:C7:87:3C:51)
,D/MapProfile( 2604): getConnectionStatus: status is: 0
,D/BluetoothMap( 2604): getConnectedDevices()
,D/BluetoothMap( 2604): getConnectionState(E0:DB:10:1F:C9:5E)
,D/MapProfile( 2604): getConnectionStatus: status is: 0
D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/BluetoothMap( 2604): getConnectedDevices()
,D/BluetoothMap( 2604): getConnectionState(F8:95:C7:87:85:54)
,D/MapProfile( 2604): getConnectionStatus: status is: 0
,D/BluetoothMap( 2604): getConnectedDevices()
,D/BluetoothMap( 2604): getConnectionState(F4:F1:E1:5C:3B:E2)
,D/MapProfile( 2604): getConnectionStatus: status is: 0
,D/BluetoothMap( 2604): getConnectedDevices()
,D/BluetoothMap( 2604): getConnectionState(08:EC:A9:50:76:27)
,D/MapProfile( 2604): getConnectionStatus: status is: 0
,D/BluetoothA2dp( 2604): Proxy object connected
,D/A2dpProfile( 2604): Bluetooth service connected
,D/BluetoothHeadset( 2604): Proxy object connected
,D/HeadsetProfile( 2604): Bluetooth service connected
,W/ContextImpl( 2604): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/BluetoothManagerService(  771): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 2593): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 2593): SOCK FLAG = 1 ***********************
D/DockEventReceiver( 2604): finishStartingService: stopping service
,D/BluetoothPbap( 2604): Proxy object connected
,D/PbapServerProfile( 2604): Bluetooth service connected
,D/AuthorizationBluetoothService( 1100): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1100): Proximity feature is not enabled.
W/BroadcastQueue(  771): Permission Denial: receiving Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 (has extras) } to com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver requires android.permission.BLUETOOTH due to sender android (uid 1000)
,D/BluetoothManagerService(  771): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2593): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 2593): SOCK FLAG = 0 ***********************
,I/BtOppRfcommListener( 2593): Accept thread started.
,D/WifiConfigStore(  771): Loading config and enabling all networks
,W/Settings( 1888): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring up p2p0
,D/WifiMonitor(  771): startMonitoring(p2p0) with mConnected = true
,D/BluetoothManagerService(  771): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 2539): Got Device Bluetooth address: 34:FC:EF:11:B1:66
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): my name is : LGE-Nexus 5_PT8412
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): attempting to connect to test coordinator
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): check test folder
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): found test : ./testFindPeers.js
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): found test : ./testReConnect.js
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): found test : ./testSendData.js
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Test app app.js loaded
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/Choreographer( 2539): Skipped 130 frames!  The application may be doing too much work on its main thread.
,I/chromium( 2539): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 2599): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 2599): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 2599): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 2599): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  771): scanCount==0 - aborting
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,D/WifiStateMachine(  771): VerifyingLinkState enter
D/WifiStateMachine(  771): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  771): CaptivePortalCheckState enter
,D/WifiStateMachine(  771): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  771): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  771): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  771): Unexpected mtu value: android.net.wifi.WifiStateTracker@42ec1430
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,D/ConnectivityService(  771): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  771):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/dalvikvm( 1193): GC_FOR_ALLOC freed 842K, 6% free 17736K/18768K, paused 15ms, total 15ms
,I/jxcore-log( 2539): BLE advertisement not supported: Build version is 19
I/jxcore-log( 2539): 
,D/dalvikvm( 1193): GC_CONCURRENT freed 280K, 5% free 17847K/18768K, paused 2ms+1ms, total 11ms
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/MusicLifecycle( 2096): com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@42a83b48 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,I/NetworkMonitor( 2096): type=WIFI subType= reason=null isConnected=true
,D/CaptivePortalTracker(  771): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/        (  771): Unable to set rtc to 1449156088: Invalid argument
,D/        (  771): Setting time of day to sec=1449156088
,I/iu.SyncManager( 1317): SYNC; picasa accounts
,D/dalvikvm( 2275): GC_CONCURRENT freed 315K, 2% free 17463K/17808K, paused 2ms+1ms, total 16ms
,D/NetworkLogImpl( 1317): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/GpsLocationProvider(  771): NTP server returned: 1449156088460 (Thu Dec 03 16:21:28 CET 2015) reference: 88462 certainty: 18 system time offset: -53
,I/iu.UploadsManager( 1317): num queued entries: 0
,I/iu.UploadsManager( 1317): num updated entries: 0
I/dalvikvm( 1317): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1317): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1317): VFY: replacing opcode 0x6e at 0x0033
,I/iu.SyncManager( 1317): NEXT; no task
,I/SystemUpdateService( 1317): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/Babel   ( 1888): connection state changed from UNKNOWN to CONNECTED
,D/SystemUpdateService( 1317): onCreate
,D/SystemUpdateService( 1317): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1317): active receiver: enabled
,I/SystemUpdateService( 1317): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1317): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1317): now status is 0 (complete)
I/SystemUpdateService( 1317): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1317): file has been verified
,I/SystemUpdateService( 1317): OTA package size = 2571501
,I/SystemUpdateService( 1317): showing system update notification
,I/ActivityManager(  771): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=2819 uid=10031 gids={50031, 3003, 1028, 1015}
,D/SystemUpdateService( 1317): onDestroy
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,E/Auth.Api.Credentials( 1317): [CredentialSyncAdapter] Unknown sync event.
,V/GLSActivity( 1100): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1100): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCM     ( 1100): GCM config loaded
,D/dalvikvm( 2275): Trying to load lib /data/app-lib/com.google.android.apps.plus-2/libcronet.so 0x429f3650
,D/dalvikvm( 2275): Added shared lib /data/app-lib/com.google.android.apps.plus-2/libcronet.so 0x429f3650
,D/dalvikvm( 1100): GC_CONCURRENT freed 400K, 3% free 18184K/18680K, paused 2ms+2ms, total 42ms
,D/dalvikvm( 2275): GC_CONCURRENT freed 266K, 2% free 17665K/17960K, paused 6ms+1ms, total 27ms
,D/dalvikvm( 2819): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,W/dalvikvm( 2819): VFY: unable to resolve instance field 68
D/dalvikvm( 2819): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 2819): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2819): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 2819): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 2819): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/dalvikvm( 2819): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 2819): VFY: unable to resolve instance field 68
,D/dalvikvm( 2819): VFY: replacing opcode 0x54 at 0x0011
D/dalvikvm( 2819): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2819): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 2819): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2819): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 2819): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 2819): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,I/ActivityManager(  771): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetService$CalendarFactory: pid=2852 uid=10028 gids={50028, 3003}
,I/ActivityManager(  771): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=2870 uid=10033 gids={50033, 1028}
,I/ActivityManager(  771): Killing 2096:com.google.android.music:main/u0a58 (adj 15): empty #17
,I/dalvikvm(  980): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
,W/dalvikvm(  980): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm(  980): VFY: replacing opcode 0x6e at 0x0033
F/ActivityManager(  771): Service ServiceRecord{4318c080 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{42d69458 2096:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  771): Service ServiceRecord{4317fd50 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{42d69458 2096:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  771): Service ServiceRecord{4314eeb8 u0 com.google.android.music/.download.artwork.ArtDownloadService} in process ProcessRecord{42d69458 2096:com.google.android.music:main/u0a58} not same as in map: null
,D/dalvikvm( 2275): GC_CONCURRENT freed 224K, 2% free 17855K/18120K, paused 2ms+1ms, total 13ms
F/ActivityManager(  771): Service ServiceRecord{4310b570 u0 com.google.android.music/.download.ArtDownloadQueueService} in process ProcessRecord{42d69458 2096:com.google.android.music:main/u0a58} not same as in map: null
F/ActivityManager(  771): Service ServiceRecord{430f0df0 u0 com.google.android.music/.download.cache.ArtCacheService} in process ProcessRecord{42d69458 2096:com.google.android.music:main/u0a58} not same as in map: null
,V/AlarmClock( 2870): AlarmInitReceiver android.intent.action.TIME_SET
,D/dalvikvm( 2275): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,W/dalvikvm( 2275): VFY: unable to resolve instance field 58
D/dalvikvm( 2275): VFY: replacing opcode 0x54 at 0x000d
D/dalvikvm( 2275): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2275): DexOpt: unable to optimize instance field ref 0x003a at 0x12 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 2275): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 2275): DexOpt: unable to optimize instance field ref 0x003a at 0x17 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,I/AlarmClock( 2870): Displaying next alarm time: ''
,V/AlarmClock( 2870): AlarmInitReceiver finished
,I/ActivityManager(  771): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=2889 uid=10068 gids={50068}
,I/ActivityManager(  771): Killing 1753:com.google.android.gm/u0a41 (adj 15): empty #17
,D/dalvikvm( 2889): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x429f0c80, skipping init
D/TimeService( 2889): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449156088960
D/        ( 2889): TimeServiceNative: User Time to be set is 1449156088960
D/QC-time-services( 2889): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 2889): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 2889): Lib:time_genoff_operation: pargs->ts_val = 1449156088960
,D/QC-time-services(  198): Daemon: Connection accepted:time_genoff
D/QC-time-services( 2889): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  198): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449156088960
D/QC-time-services(  198): Daemon:genoff_opr: Base = 2, val = 1449156088960, operation = 0
D/QC-time-services(  198): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS0/23/71 9:26:43
D/QC-time-services(  198): Daemon:Value read from RTC seconds = 33470803000
D/QC-time-services(  198): Daemon:new time 1449156088960 
D/QC-time-services(  198): Daemon: delta 1415685285960 genoff 1415685285960 
D/QC-time-services(  198): Daemon:genoff_persistent_update: Writing genoff = 1415685285960 to memory
D/QC-time-services(  198): Daemon:Opening File: /data/system/time/ats_2
,D/QC-time-services(  198): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  198): Updating the TOD offset
D/QC-time-services(  198): Daemon:genoff_persistent_update: Writing genoff = 1415685285960 to memory
D/QC-time-services(  198): Daemon:Opening File: /data/system/time/ats_1
,D/QC-time-services(  198): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  198): Daemon:Update to modem bit set
D/QC-time-services(  198): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  198): Daemon: Base = 2, Value being sent to MODEM = 1133191288960
,E/QC-time-services( 2889): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  198): Daemon: Time-services: Waiting to acceptconnection
,D/QC-time-services(  198): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/CheckinService( 1317): Checkin interval check for package: unspecified last checkin: 1449138604644 min interval config: 0 actual interval: 17484349
,D/dalvikvm( 2275): GC_CONCURRENT freed 278K, 2% free 18026K/18336K, paused 2ms+3ms, total 19ms
,I/ActivityManager(  771): Killing 2136:com.android.providers.calendar/u0a1 (adj 15): empty #17
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/ActivityManager(  771): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=2914 uid=10001 gids={50001, 3003, 1028, 1015}
,I/ActivityManager(  771): Killing 2383:com.android.defcontainer/u0a4 (adj 15): empty #17
,D/dalvikvm(  183): GC_EXPLICIT freed 42K, 1% free 16699K/16772K, paused 3ms+7ms, total 55ms
,D/dalvikvm(  183): GC_EXPLICIT freed <1K, 1% free 16699K/16772K, paused 2ms+1ms, total 21ms
,D/dalvikvm(  183): GC_EXPLICIT freed <1K, 1% free 16699K/16772K, paused 1ms+1ms, total 13ms
,I/CalendarProvider2( 2914): Created com.android.providers.calendar.CalendarAlarmManager@42a06980(com.android.providers.calendar.CalendarProvider2@429fe640)
,D/dalvikvm(  771): GC_EXPLICIT freed 1537K, 53% free 26239K/55588K, paused 3ms+4ms, total 58ms
,E/HttpOperation( 2275): [fetchnotificationscount] Unexpected exception
E/HttpOperation( 2275): kdg: 500: Internal Server Error
E/HttpOperation( 2275): 	at kec.a(PG:2406)
E/HttpOperation( 2275): 	at kdj.o(PG:7479)
E/HttpOperation( 2275): 	at kde.a(PG:1379)
E/HttpOperation( 2275): 	at kdj.i(PG:143)
E/HttpOperation( 2275): 	at bqs.a(PG:3937)
E/HttpOperation( 2275): 	at dlh.a(PG:16167)
E/HttpOperation( 2275): 	at dlh.a(PG:7064)
E/HttpOperation( 2275): 	at dli.run(PG:1679)
E/HttpOperation( 2275): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2275): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2275): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2275): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2275): 	at java.lang.Thread.run(Thread.java:841)
,E/HttpOperation( 2275): [kec{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2275): java.io.IOException: 1 of 3 operations in the batch failed
E/HttpOperation( 2275): 	at kec.a(PG:269)
E/HttpOperation( 2275): 	at kdj.o(PG:7479)
E/HttpOperation( 2275): 	at kde.a(PG:1379)
E/HttpOperation( 2275): 	at kdj.i(PG:143)
E/HttpOperation( 2275): 	at bqs.a(PG:3937)
E/HttpOperation( 2275): 	at dlh.a(PG:16167)
E/HttpOperation( 2275): 	at dlh.a(PG:7064)
E/HttpOperation( 2275): 	at dli.run(PG:1679)
E/HttpOperation( 2275): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2275): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2275): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2275): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2275): 	at java.lang.Thread.run(Thread.java:841)
,D/SyncManager(  771): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, latestRunTime 23686, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/CalendarProvider2( 2914): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 2914): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlertReceiver( 2852): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.google.android.calendar/com.android.calendar.alerts.AlertReceiver }
,D/AlertService( 2852): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/dalvikvm( 1621): GC_CONCURRENT freed 431K, 3% free 17353K/17832K, paused 2ms+1ms, total 18ms
,D/Finsky  ( 1621): [1] 5.onFinished: Installation state replication succeeded.
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,D/AlertService( 2852): Beginning updateAlertNotification
,D/AlertService( 2852): No fired or scheduled alerts
,D/AlertService( 2852): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 2852): No events found starting within 1 week.
I/ActivityManager(  771): Killing 951:android.process.acore/u0a3 (adj 15): empty #17
,D/dalvikvm( 1100): GC_CONCURRENT freed 427K, 3% free 18289K/18784K, paused 3ms+3ms, total 46ms
,I/VacuumService( 1100): Vacuum at: now=1449156097714 tag=VacuumService
,D/dalvikvm( 1317): GC_CONCURRENT freed 495K, 3% free 18829K/19360K, paused 2ms+3ms, total 22ms
,D/UdcCache:FPQuery( 1317): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1100): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1100): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1100): GC_CONCURRENT freed 582K, 4% free 18172K/18856K, paused 2ms+1ms, total 18ms
,D/GetConfigurationSnapshotOperation( 1100): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/dalvikvm( 1100): GC_CONCURRENT freed 354K, 4% free 18229K/18856K, paused 2ms+1ms, total 17ms
,I/PhenotypeFlagCommitter( 1100): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1100): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1100): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/dalvikvm( 1100): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.x.a
W/dalvikvm( 1100): VFY: unable to resolve virtual method 1099: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1100): VFY: replacing opcode 0x6e at 0x0033
,D/dalvikvm( 1100): GC_FOR_ALLOC freed 140K, 3% free 18331K/18856K, paused 20ms, total 20ms
,D/dalvikvm( 1100): GC_CONCURRENT freed 466K, 3% free 18421K/18988K, paused 4ms+4ms, total 31ms
,D/dalvikvm( 1100): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/CaptivePortalTracker(  771): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker(  771): Checking http://216.58.209.46/generate_204
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
W/ActivityThread(  771): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/CaptivePortalTracker(  771): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  771): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  771): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  771): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/dalvikvm( 1100): GC_CONCURRENT freed 379K, 3% free 18557K/19028K, paused 2ms+2ms, total 19ms
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,D/dalvikvm( 1100): GC_CONCURRENT freed 517K, 4% free 18625K/19236K, paused 3ms+2ms, total 21ms
,D/dalvikvm( 1100): GC_CONCURRENT freed 602K, 4% free 18624K/19320K, paused 1ms+2ms, total 17ms
,D/GetCommittedConfigurationOperation( 1100): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1100):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1100): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 1100): GC_CONCURRENT freed 641K, 5% free 18553K/19372K, paused 2ms+2ms, total 19ms
,D/GetCommittedConfigurationOperation( 1100): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1100): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/dalvikvm( 1100): GC_FOR_ALLOC freed 542K, 5% free 18521K/19372K, paused 26ms, total 27ms
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/PowerManagerService(  771): Going to sleep due to screen timeout...
,I/Adreno-EGL(  771): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/SurfaceFlinger(  182): Screen released, type=0 flinger=0xb7c70450
,D/qdhwcomposer(  182): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  182): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  771): Excessive delay in blankDisplay() while turning screen off: 284ms
,V/KeyguardServiceDelegate(  771): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@4307fee0)
,V/KeyguardServiceDelegate(  771): **** SHOWN CALLED ****
I/WindowManager(  771): No lock screen! windowToken=null
,D/NfcService( 1028): NFC-C OFF
,D/dalvikvm( 2275): GC_CONCURRENT freed 381K, 3% free 18034K/18444K, paused 4ms+1ms, total 16ms
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,D/dalvikvm( 2275): DexOpt: couldn't find field Landroid/app/Notification;.color
,W/dalvikvm( 2275): VFY: unable to resolve instance field 2708
,D/dalvikvm( 2275): VFY: replacing opcode 0x59 at 0x008b
,D/dalvikvm( 2275): DexOpt: couldn't find field Landroid/app/Notification;.color
W/dalvikvm( 2275): VFY: unable to resolve instance field 2708
,D/dalvikvm( 2275): VFY: replacing opcode 0x59 at 0x00c7
,D/dalvikvm( 1100): GC_FOR_ALLOC freed 277K, 5% free 18415K/19368K, paused 24ms, total 25ms
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/rmt_storage(  178): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb8bab160
I/rmt_storage(  178): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  178): wakelock acquired: 1, error no: 2
,I/rmt_storage(  178): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1195724256)
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/rmt_storage(  178): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  178): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  178): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1195724256) wakelock released: 1, error no: 0
I/rmt_storage(  178): 
,I/rmt_storage(  178): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb8bab160
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Coordinator is now connected to the server!
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,D/BluetoothManagerService(  771): Message: 20
,D/BluetoothManagerService(  771): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@430c9328:true
,I/BluetoothConnectionReceiver( 1193): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1193): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/dalvikvm(  980): GC_CONCURRENT freed 385K, 3% free 17921K/18400K, paused 9ms+2ms, total 36ms
,D/btif_config_util( 2593): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1193): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1193): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,I/wpa_supplicant( 2599): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  771): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  771): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  771): Attempting to switch to mobile
,D/ConnectivityService(  771): Attempting to switch to BLUETOOTH_TETHER
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/dalvikvm( 1006): GC_CONCURRENT freed 342K, 3% free 17064K/17432K, paused 1ms+2ms, total 29ms
,D/NetUtils(  771): android_net_utils_resetConnections in env=0x77ab8f90 clazz=0x5e600001 iface=wlan0 mask=0x3
,D/ConnectivityService(  771): resetConnections(wlan0, 3)
V/NativeCrypto( 1100): Read error: ssl=0x7599f2b0: I/O error during system call, Connection timed out
V/NativeCrypto( 1100): SSL shutdown failed: ssl=0x7599f2b0: I/O error during system call, Broken pipe
,I/jxcore-log( 2539): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): The Coordinator has disconnected!
I/jxcore-log( 2539): 
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,D/WifiService(  771): setWifiEnabled: false pid=2539, uid=10108
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,W/wpa_supplicant( 2599): wlan0: Failed to initiate AP scan
,E/WifiStateMachine(  771): scanCount==0 - aborting
D/WifiService(  771): setWifiEnabled: true pid=2539, uid=10108
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/WifiController(  771): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 468ms
,I/jxcore-log( 2539): Wifi toggled for connection repairment
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 2599): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 2599): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  771): InitialState.processMessage what=4
,D/Tethering(  771): sendTetherStateChangedBroadcast 0, 0, 0
,W/Settings( 1888): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  980): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  771): DEFERRED_TOGGLE handled
,D/SoftapController(  179): Softap fwReload - Ok
,D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring down wlan0
,I/wpa_supplicant( 3188): Successfully initialized wpa_supplicant
,D/WifiMonitor(  771): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 3188): rfkill: Cannot open RFKILL control device
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,D/Tethering(  771): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3188): rfkill: Cannot open RFKILL control device
,D/WifiConfigStore(  771): Loading config and enabling all networks
,W/Settings( 1888): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring up p2p0
,D/WifiMonitor(  771): startMonitoring(p2p0) with mConnected = true
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/iu.Environment( 1317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1317): num queued entries: 0
,I/Babel   ( 1888): connection state changed from CONNECTED to DISCONNECTED
,I/iu.UploadsManager( 1317): num updated entries: 0
,I/SystemUpdateService( 1317): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1317): onCreate
,D/SystemUpdateService( 1317): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.SyncManager( 1317): NEXT; no task
,I/SystemUpdateService( 1317): active receiver: enabled
I/SystemUpdateService( 1317): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1317): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1317): now status is 0 (complete)
I/SystemUpdateService( 1317): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1317): file has been verified
,I/SystemUpdateService( 1317): OTA package size = 2571501
,I/SystemUpdateService( 1317): showing system update notification
,D/dalvikvm( 1317): GC_CONCURRENT freed 604K, 4% free 18839K/19476K, paused 4ms+1ms, total 20ms
,W/SQLiteConnectionPool( 1317): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/SystemUpdateService( 1317): onDestroy
,I/wpa_supplicant( 3188): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3188): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 3188): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3188): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  771): scanCount==0 - aborting
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,D/WifiStateMachine(  771): VerifyingLinkState enter
,D/WifiStateMachine(  771): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  771): CaptivePortalCheckState enter
D/ConnectivityService(  771): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  771): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  771): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  771): Unexpected mtu value: android.net.wifi.WifiStateTracker@42ec1430
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,W/bt-l2cap( 2593): l2cu_get_conn_role 1
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BluetoothConnectionReceiver( 1193): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1193): Bluetooth Device Name: G3s-1
,D/dalvikvm(  771): GC_CONCURRENT freed 2047K, 53% free 26498K/55588K, paused 3ms+5ms, total 76ms
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/ConnectivityService(  771): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  771): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  771):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Coordinator is now connected to the server!
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): NoActiveNetworkState{ when=-13ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/btif_config_util( 2593): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/dalvikvm( 1209): GC_CONCURRENT freed 320K, 3% free 16765K/17124K, paused 10ms+1ms, total 21ms
,I/iu.Environment( 1317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1317): num queued entries: 0
,I/SystemUpdateService( 1317): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/iu.UploadsManager( 1317): num updated entries: 0
,I/iu.SyncManager( 1317): NEXT; no task
,D/SystemUpdateService( 1317): onCreate
,D/SystemUpdateService( 1317): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1317): active receiver: enabled
,I/SystemUpdateService( 1317): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1317): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1317): now status is 0 (complete)
I/SystemUpdateService( 1317): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1317): file has been verified
,I/SystemUpdateService( 1317): OTA package size = 2571501
,I/SystemUpdateService( 1317): showing system update notification
,D/SystemUpdateService( 1317): onDestroy
,I/Babel   ( 1888): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1193): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1193): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,W/bt-l2cap( 2593): l2cu_get_conn_role 1
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BluetoothConnectionReceiver( 1193): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1193): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/CaptivePortalTracker(  771): DelayedCaptiveCheckState{ when=-7ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  771): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  771): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  771): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  771): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  771): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/btif_config_util( 2593): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1193): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1193): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,W/bt-l2cap( 2593): l2cu_get_conn_role 1
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BluetoothConnectionReceiver( 1193): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1193): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/btif_config_util( 2593): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1193): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1193): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/dalvikvm( 2593): GC_CONCURRENT freed 327K, 3% free 16897K/17256K, paused 2ms+0ms, total 12ms
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/dalvikvm(  980): GC_CONCURRENT freed 425K, 3% free 17899K/18420K, paused 2ms+2ms, total 25ms
,W/bt-l2cap( 2593): l2cu_get_conn_role 1
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BluetoothConnectionReceiver( 1193): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1193): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/btif_config_util( 2593): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1193): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1193): Bluetooth Device Name: G3s-1
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,I/wpa_supplicant( 3188): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  771): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  771): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  771): Attempting to switch to mobile
,D/ConnectivityService(  771): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  771): android_net_utils_resetConnections in env=0x77ab8f90 clazz=0x7df00001 iface=wlan0 mask=0x3
,V/NativeCrypto( 1100): Read error: ssl=0x762ade68: I/O error during system call, Connection timed out
D/ConnectivityService(  771): resetConnections(wlan0, 3)
,V/NativeCrypto( 1100): SSL shutdown failed: ssl=0x762ade68: I/O error during system call, Broken pipe
,I/jxcore-log( 2539): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): The Coordinator has disconnected!
I/jxcore-log( 2539): 
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,D/WifiService(  771): setWifiEnabled: false pid=2539, uid=10108
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,D/WifiService(  771): setWifiEnabled: true pid=2539, uid=10108
,W/wpa_supplicant( 3188): wlan0: Failed to initiate AP scan
,E/WifiStateMachine(  771): scanCount==0 - aborting
,D/WifiController(  771): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 485ms
,I/jxcore-log( 2539): Wifi toggled for connection repairment
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/WifiController(  771): DEFERRED_TOGGLE handled
,I/wpa_supplicant( 3188): p2p0: CTRL-EVENT-TERMINATING 
,D/Tethering(  771): InitialState.processMessage what=4
,D/Tethering(  771): sendTetherStateChangedBroadcast 0, 0, 0
,I/wpa_supplicant( 3188): wlan0: CTRL-EVENT-TERMINATING 
,W/Settings( 1888): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  980): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/SoftapController(  179): Softap fwReload - Ok
D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring down wlan0
,D/WifiMonitor(  771): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 3474): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3474): rfkill: Cannot open RFKILL control device
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Babel   ( 1888): connection state changed from CONNECTED to DISCONNECTED
,I/iu.Environment( 1317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1317): num queued entries: 0
I/iu.UploadsManager( 1317): num updated entries: 0
,I/iu.SyncManager( 1317): NEXT; no task
,I/SystemUpdateService( 1317): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1317): onCreate
,D/SystemUpdateService( 1317): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1317): active receiver: enabled
,I/SystemUpdateService( 1317): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1317): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1317): now status is 0 (complete)
I/SystemUpdateService( 1317): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1317): file has been verified
,I/SystemUpdateService( 1317): OTA package size = 2571501
,I/SystemUpdateService( 1317): showing system update notification
,D/SystemUpdateService( 1317): onDestroy
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/Tethering(  771): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3474): rfkill: Cannot open RFKILL control device
,D/WifiConfigStore(  771): Loading config and enabling all networks
,W/Settings( 1888): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring up p2p0
,D/WifiMonitor(  771): startMonitoring(p2p0) with mConnected = true
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/dalvikvm(  771): Jit: resizing JitTable from 8192 to 16384
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3474): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3474): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 3474): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3474): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  771): scanCount==0 - aborting
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiStateMachine(  771): VerifyingLinkState enter
,D/WifiStateMachine(  771): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  771): CaptivePortalCheckState enter
,D/ConnectivityService(  771): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  771): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  771): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  771): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  771): Unexpected mtu value: android.net.wifi.WifiStateTracker@42ec1430
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  771): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  771): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  771):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/dalvikvm( 1100): GC_CONCURRENT freed 488K, 5% free 18399K/19368K, paused 19ms+1ms, total 34ms
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): NoActiveNetworkState{ when=-14ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/iu.Environment( 1317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1317): num queued entries: 0
,I/SystemUpdateService( 1317): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1317): onCreate
,I/iu.UploadsManager( 1317): num updated entries: 0
,I/iu.SyncManager( 1317): NEXT; no task
,D/SystemUpdateService( 1317): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1317): active receiver: enabled
,I/SystemUpdateService( 1317): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1317): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1317): now status is 0 (complete)
I/SystemUpdateService( 1317): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1317): file has been verified
,I/SystemUpdateService( 1317): OTA package size = 2571501
,I/SystemUpdateService( 1317): showing system update notification
,D/SystemUpdateService( 1317): onDestroy
,I/Babel   ( 1888): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=0, published condition=100
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Coordinator is now connected to the server!
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,D/CaptivePortalTracker(  771): DelayedCaptiveCheckState{ when=-2ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  771): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  771): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  771): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  771): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  771): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/wpa_supplicant( 3474): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  771): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  771): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  771): Attempting to switch to mobile
,D/ConnectivityService(  771): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  771): android_net_utils_resetConnections in env=0x77ab8f90 clazz=0xa2500001 iface=wlan0 mask=0x3
D/ConnectivityService(  771): resetConnections(wlan0, 3)
,V/NativeCrypto( 1100): Read error: ssl=0x78f10fd8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1100): SSL shutdown failed: ssl=0x78f10fd8: I/O error during system call, Broken pipe
,I/jxcore-log( 2539): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): The Coordinator has disconnected!
I/jxcore-log( 2539): 
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,D/WifiService(  771): setWifiEnabled: false pid=2539, uid=10108
,I/wpa_supplicant( 3474): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,E/WifiStateMachine(  771): scanCount==0 - aborting
D/WifiService(  771): setWifiEnabled: true pid=2539, uid=10108
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/WifiController(  771): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 480ms
,I/jxcore-log( 2539): Wifi toggled for connection repairment
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiController(  771): DEFERRED_TOGGLE handled
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant( 3474): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 3474): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/Tethering(  771): InitialState.processMessage what=4
,D/Tethering(  771): sendTetherStateChangedBroadcast 0, 0, 0
,I/wpa_supplicant( 3474): wlan0: CTRL-EVENT-TERMINATING 
,W/Settings( 1888): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  980): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/SoftapController(  179): Softap fwReload - Ok
D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring down wlan0
,D/WifiMonitor(  771): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 3632): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3632): rfkill: Cannot open RFKILL control device
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Babel   ( 1888): connection state changed from CONNECTED to DISCONNECTED
,I/iu.Environment( 1317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1317): num queued entries: 0
,I/iu.UploadsManager( 1317): num updated entries: 0
,I/SystemUpdateService( 1317): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/iu.SyncManager( 1317): NEXT; no task
,D/SystemUpdateService( 1317): onCreate
,D/SystemUpdateService( 1317): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1317): active receiver: enabled
,I/SystemUpdateService( 1317): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1317): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1317): now status is 0 (complete)
I/SystemUpdateService( 1317): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1317): file has been verified
,I/SystemUpdateService( 1317): OTA package size = 2571501
,I/SystemUpdateService( 1317): showing system update notification
,D/SystemUpdateService( 1317): onDestroy
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/Tethering(  771): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3632): rfkill: Cannot open RFKILL control device
,D/WifiConfigStore(  771): Loading config and enabling all networks
,W/Settings( 1888): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring up p2p0
,D/WifiMonitor(  771): startMonitoring(p2p0) with mConnected = true
,W/wpa_supplicant( 3632): wlan0: Failed to initiate AP scan
,D/dalvikvm(  771): GC_CONCURRENT freed 2360K, 53% free 26521K/55584K, paused 4ms+4ms, total 94ms
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,W/wpa_supplicant( 3632): wlan0: Failed to initiate AP scan
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3632): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3632): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 3632): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3632): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  771): scanCount==0 - aborting
,D/WifiStateMachine(  771): VerifyingLinkState enter
,D/WifiStateMachine(  771): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  771): CaptivePortalCheckState enter
,D/WifiStateMachine(  771): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  771): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  771): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  771): Unexpected mtu value: android.net.wifi.WifiStateTracker@42ec1430
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  771): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  771): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  771):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/iu.Environment( 1317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1317): num queued entries: 0
,I/SystemUpdateService( 1317): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/iu.UploadsManager( 1317): num updated entries: 0
,I/iu.SyncManager( 1317): NEXT; no task
,D/SystemUpdateService( 1317): onCreate
,D/SystemUpdateService( 1317): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1317): active receiver: enabled
,I/SystemUpdateService( 1317): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1317): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1317): now status is 0 (complete)
I/SystemUpdateService( 1317): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1317): file has been verified
,I/SystemUpdateService( 1317): OTA package size = 2571501
,I/SystemUpdateService( 1317): showing system update notification
,D/SystemUpdateService( 1317): onDestroy
,I/Babel   ( 1888): connection state changed from DISCONNECTED to CONNECTED
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Coordinator is now connected to the server!
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2593): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,D/CaptivePortalTracker(  771): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  771): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  771): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  771): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  771): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  771): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,W/bt-l2cap( 2593): l2cu_get_conn_role 1
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2593): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3632): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  771): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  771): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  771): Attempting to switch to mobile
,D/ConnectivityService(  771): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  771): android_net_utils_resetConnections in env=0x77ab8f90 clazz=0xc2100001 iface=wlan0 mask=0x3
D/ConnectivityService(  771): resetConnections(wlan0, 3)
,V/NativeCrypto( 1100): Read error: ssl=0x78eb13b0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1100): SSL shutdown failed: ssl=0x78eb13b0: I/O error during system call, Broken pipe
I/jxcore-log( 2539): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): The Coordinator has disconnected!
I/jxcore-log( 2539): 
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/iu.Environment( 1317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1317): num queued entries: 0
,I/iu.UploadsManager( 1317): num updated entries: 0
,I/SystemUpdateService( 1317): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1317): onCreate
,D/SystemUpdateService( 1317): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/Babel   ( 1888): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1317): active receiver: enabled
,I/iu.SyncManager( 1317): NEXT; no task
,I/SystemUpdateService( 1317): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1317): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1317): now status is 0 (complete)
I/SystemUpdateService( 1317): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1317): file has been verified
,I/SystemUpdateService( 1317): OTA package size = 2571501
,I/SystemUpdateService( 1317): showing system update notification
,D/SystemUpdateService( 1317): onDestroy
,W/bt-l2cap( 2593): l2cu_get_conn_role 1
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,D/btif_config_util( 2593): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,D/WifiService(  771): setWifiEnabled: false pid=2539, uid=10108
,D/WifiService(  771): setWifiEnabled: true pid=2539, uid=10108
,D/WifiController(  771): WifiController msg { when=-1ms what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 482ms
,I/jxcore-log( 2539): Wifi toggled for connection repairment
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,E/WifiStateMachine(  771): scanCount==0 - aborting
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/WifiController(  771): DEFERRED_TOGGLE handled
,I/wpa_supplicant( 3632): p2p0: CTRL-EVENT-TERMINATING 
,D/Tethering(  771): InitialState.processMessage what=4
,D/Tethering(  771): sendTetherStateChangedBroadcast 0, 0, 0
,I/wpa_supplicant( 3632): wlan0: CTRL-EVENT-TERMINATING 
,W/Settings( 1888): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  980): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/SoftapController(  179): Softap fwReload - Ok
D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring down wlan0
,D/WifiMonitor(  771): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 3805): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3805): rfkill: Cannot open RFKILL control device
,W/bt-l2cap( 2593): l2cu_get_conn_role 1
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,D/Tethering(  771): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3805): rfkill: Cannot open RFKILL control device
,D/WifiConfigStore(  771): Loading config and enabling all networks
,W/Settings( 1888): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring up p2p0
,D/WifiMonitor(  771): startMonitoring(p2p0) with mConnected = true
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant( 3805): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3805): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/btif_config_util( 2593): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3805): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3805): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  771): scanCount==0 - aborting
,D/WifiStateMachine(  771): VerifyingLinkState enter
,D/WifiStateMachine(  771): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  771): CaptivePortalCheckState enter
,D/WifiStateMachine(  771): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  771): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  771): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  771): Unexpected mtu value: android.net.wifi.WifiStateTracker@42ec1430
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  771): NetTransition Wakelock for ConnectedState released by timeout
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Coordinator is now connected to the server!
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService(  771): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  771):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): NoActiveNetworkState{ when=-4ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/iu.Environment( 1317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1317): num queued entries: 0
,I/iu.UploadsManager( 1317): num updated entries: 0
,I/SystemUpdateService( 1317): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1317): onCreate
,D/SystemUpdateService( 1317): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1317): active receiver: enabled
,I/SystemUpdateService( 1317): Already downloaded, skipping offpeak checks.
,I/iu.SyncManager( 1317): NEXT; no task
,D/dalvikvm( 1317): GC_CONCURRENT freed 593K, 4% free 18850K/19476K, paused 2ms+2ms, total 24ms
,I/SystemUpdateService( 1317): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1317): now status is 0 (complete)
I/SystemUpdateService( 1317): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1317): file has been verified
,I/SystemUpdateService( 1317): OTA package size = 2571501
,I/SystemUpdateService( 1317): showing system update notification
,D/SystemUpdateService( 1317): onDestroy
,D/dalvikvm( 2275): GC_CONCURRENT freed 314K, 2% free 18110K/18456K, paused 2ms+2ms, total 22ms
,I/Babel   ( 1888): connection state changed from DISCONNECTED to CONNECTED
,D/dalvikvm( 1888): GC_CONCURRENT freed 1555K, 7% free 22686K/24284K, paused 2ms+1ms, total 35ms
,D/dalvikvm( 1100): GC_CONCURRENT freed 540K, 5% free 18380K/19312K, paused 2ms+1ms, total 16ms
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,W/bt-l2cap( 2593): l2cu_get_conn_role 1
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2593): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,D/CaptivePortalTracker(  771): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=5 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  771): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  771): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker(  771): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  771): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  771): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/wpa_supplicant( 3805): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  771): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  771): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  771): Attempting to switch to mobile
,D/ConnectivityService(  771): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  771): android_net_utils_resetConnections in env=0x77ab8f90 clazz=0xe1900001 iface=wlan0 mask=0x3
D/ConnectivityService(  771): resetConnections(wlan0, 3)
,V/NativeCrypto( 1100): Read error: ssl=0x78eb13b0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1100): SSL shutdown failed: ssl=0x78eb13b0: I/O error during system call, Broken pipe
,I/jxcore-log( 2539): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): The Coordinator has disconnected!
I/jxcore-log( 2539): 
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,D/WifiService(  771): setWifiEnabled: false pid=2539, uid=10108
,D/WifiService(  771): setWifiEnabled: true pid=2539, uid=10108
,W/wpa_supplicant( 3805): wlan0: Failed to initiate AP scan
,E/WifiStateMachine(  771): scanCount==0 - aborting
,D/WifiController(  771): WifiController msg { when=-1ms what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 481ms
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,I/jxcore-log( 2539): Wifi toggled for connection repairment
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3805): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 3805): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  771): InitialState.processMessage what=4
,D/Tethering(  771): sendTetherStateChangedBroadcast 0, 0, 0
,W/Settings( 1888): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  980): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  771): DEFERRED_TOGGLE handled
,D/SoftapController(  179): Softap fwReload - Ok
D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring down wlan0
,D/WifiMonitor(  771): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 3952): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3952): rfkill: Cannot open RFKILL control device
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,D/Tethering(  771): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3952): rfkill: Cannot open RFKILL control device
,D/WifiConfigStore(  771): Loading config and enabling all networks
,W/Settings( 1888): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring up p2p0
,D/WifiMonitor(  771): startMonitoring(p2p0) with mConnected = true
,W/wpa_supplicant( 3952): wlan0: Failed to initiate AP scan
,D/dalvikvm(  771): GC_CONCURRENT freed 2343K, 53% free 26593K/55584K, paused 4ms+4ms, total 95ms
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Babel   ( 1888): connection state changed from CONNECTED to DISCONNECTED
,I/iu.Environment( 1317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1317): num queued entries: 0
,I/iu.UploadsManager( 1317): num updated entries: 0
,I/SystemUpdateService( 1317): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/iu.SyncManager( 1317): NEXT; no task
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/SystemUpdateService( 1317): onCreate
,D/SystemUpdateService( 1317): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1317): active receiver: enabled
,I/SystemUpdateService( 1317): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1317): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1317): now status is 0 (complete)
I/SystemUpdateService( 1317): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1317): file has been verified
,I/SystemUpdateService( 1317): OTA package size = 2571501
,I/SystemUpdateService( 1317): showing system update notification
,D/SystemUpdateService( 1317): onDestroy
,W/wpa_supplicant( 3952): wlan0: Failed to initiate AP scan
,I/wpa_supplicant( 3952): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 3952): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 3952): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3952): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  771): scanCount==0 - aborting
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,D/WifiStateMachine(  771): VerifyingLinkState enter
,D/WifiStateMachine(  771): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  771): CaptivePortalCheckState enter
,D/WifiStateMachine(  771): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  771): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  771): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  771): Unexpected mtu value: android.net.wifi.WifiStateTracker@42ec1430
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  771): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  771): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  771):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Coordinator is now connected to the server!
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/iu.Environment( 1317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1317): num queued entries: 0
,I/SystemUpdateService( 1317): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/iu.UploadsManager( 1317): num updated entries: 0
,D/SystemUpdateService( 1317): onCreate
,D/SystemUpdateService( 1317): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1317): active receiver: enabled
,I/SystemUpdateService( 1317): Already downloaded, skipping offpeak checks.
,I/iu.SyncManager( 1317): NEXT; no task
,I/SystemUpdateService( 1317): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1317): now status is 0 (complete)
,I/SystemUpdateService( 1317): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1317): file has been verified
,I/SystemUpdateService( 1317): OTA package size = 2571501
,I/SystemUpdateService( 1317): showing system update notification
,D/SystemUpdateService( 1317): onDestroy
,I/Babel   ( 1888): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  771): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker(  771): Checking http://216.58.209.46/generate_204
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  771): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  771): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  771): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  771): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/ConnectivityService(  771): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  771): Done.
,D/ConnectivityService(  771): Setting timer for 720seconds
,I/EventLogService( 1317): Aggregate from 1449154852469 (log), 1449154852469 (data)
,I/wpa_supplicant( 3952): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  771): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  771): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  771): Attempting to switch to mobile
,D/ConnectivityService(  771): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  771): android_net_utils_resetConnections in env=0x77ab8f90 clazz=0x20e00001 iface=wlan0 mask=0x3
D/ConnectivityService(  771): resetConnections(wlan0, 3)
,I/jxcore-log( 2539): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): The Coordinator has disconnected!
I/jxcore-log( 2539): 
,V/NativeCrypto( 1100): Read error: ssl=0x7a71dea0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1100): SSL shutdown failed: ssl=0x7a71dea0: I/O error during system call, Broken pipe
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,D/WifiService(  771): setWifiEnabled: false pid=2539, uid=10108
,W/wpa_supplicant( 3952): wlan0: Failed to initiate AP scan
,E/WifiStateMachine(  771): scanCount==0 - aborting
D/WifiService(  771): setWifiEnabled: true pid=2539, uid=10108
,D/WifiController(  771): WifiController msg { when=-1ms what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 484ms
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,I/jxcore-log( 2539): Wifi toggled for connection repairment
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3952): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 3952): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering(  771): InitialState.processMessage what=4
,D/Tethering(  771): sendTetherStateChangedBroadcast 0, 0, 0
,W/Settings( 1888): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  980): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  771): DEFERRED_TOGGLE handled
,D/SoftapController(  179): Softap fwReload - Ok
,D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring down wlan0
,D/WifiMonitor(  771): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 4109): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 4109): rfkill: Cannot open RFKILL control device
,D/Tethering(  771): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 4109): rfkill: Cannot open RFKILL control device
,D/WifiConfigStore(  771): Loading config and enabling all networks
,W/Settings( 1888): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring up p2p0
,D/WifiMonitor(  771): startMonitoring(p2p0) with mConnected = true
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/iu.Environment( 1317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1317): num queued entries: 0
,I/Babel   ( 1888): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1317): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1317): onCreate
,D/SystemUpdateService( 1317): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.UploadsManager( 1317): num updated entries: 0
,I/SystemUpdateService( 1317): active receiver: enabled
,I/SystemUpdateService( 1317): Already downloaded, skipping offpeak checks.
,I/iu.SyncManager( 1317): NEXT; no task
,I/SystemUpdateService( 1317): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1317): now status is 0 (complete)
I/SystemUpdateService( 1317): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1317): file has been verified
,I/SystemUpdateService( 1317): OTA package size = 2571501
,I/SystemUpdateService( 1317): showing system update notification
,D/SystemUpdateService( 1317): onDestroy
,D/dalvikvm( 1317): GC_CONCURRENT freed 482K, 3% free 18978K/19492K, paused 3ms+5ms, total 33ms
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 4109): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 4109): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 4109): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 4109): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  771): scanCount==0 - aborting
,D/WifiStateMachine(  771): VerifyingLinkState enter
,D/WifiStateMachine(  771): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  771): CaptivePortalCheckState enter
D/ConnectivityService(  771): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  771): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  771): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  771): Unexpected mtu value: android.net.wifi.WifiStateTracker@42ec1430
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  771): NetTransition Wakelock for ConnectedState released by timeout
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Coordinator is now connected to the server!
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService(  771): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  771):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/iu.Environment( 1317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SystemUpdateService( 1317): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1317): onCreate
,D/SystemUpdateService( 1317): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.UploadsManager( 1317): num queued entries: 0
,I/SystemUpdateService( 1317): active receiver: enabled
,I/iu.UploadsManager( 1317): num updated entries: 0
,I/SystemUpdateService( 1317): Already downloaded, skipping offpeak checks.
,I/iu.SyncManager( 1317): NEXT; no task
,I/SystemUpdateService( 1317): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1317): now status is 0 (complete)
I/SystemUpdateService( 1317): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1317): file has been verified
,I/SystemUpdateService( 1317): OTA package size = 2571501
,I/SystemUpdateService( 1317): showing system update notification
,D/SystemUpdateService( 1317): onDestroy
,I/Babel   ( 1888): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=0, published condition=0
,D/dalvikvm( 1100): GC_CONCURRENT freed 467K, 5% free 18379K/19312K, paused 10ms+1ms, total 45ms
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  771): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=7 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  771): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  771): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  771): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  771): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  771): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2593): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 4109): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  771): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  771): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  771): Attempting to switch to mobile
,D/ConnectivityService(  771): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  771): android_net_utils_resetConnections in env=0x77ab8f90 clazz=0x41800001 iface=wlan0 mask=0x3
D/ConnectivityService(  771): resetConnections(wlan0, 3)
,V/NativeCrypto( 1100): Read error: ssl=0x7a71dea0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1100): SSL shutdown failed: ssl=0x7a71dea0: I/O error during system call, Broken pipe
,I/jxcore-log( 2539): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): The Coordinator has disconnected!
I/jxcore-log( 2539): 
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant( 4109): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 4109): wlan0: CTRL-EVENT-ASSOC-REJECT bssid=c0:ff:d4:d3:aa:48 status_code=1
E/wpa_supplicant( 4109): Retrying assoc: 1 
,I/wpa_supplicant( 4109): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/CaptivePortalTracker(  771): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/Tethering(  771): MasterInitialState.processMessage what=3
,I/Babel   ( 1888): connection state changed from CONNECTED to DISCONNECTED
I/iu.Environment( 1317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1317): num queued entries: 0
,I/SystemUpdateService( 1317): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1317): onCreate
,I/iu.UploadsManager( 1317): num updated entries: 0
,I/iu.SyncManager( 1317): NEXT; no task
,D/SystemUpdateService( 1317): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1317): active receiver: enabled
,I/SystemUpdateService( 1317): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1317): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1317): now status is 0 (complete)
I/SystemUpdateService( 1317): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1317): file has been verified
,I/SystemUpdateService( 1317): OTA package size = 2571501
,I/SystemUpdateService( 1317): showing system update notification
,D/SystemUpdateService( 1317): onDestroy
,I/wpa_supplicant( 4109): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 4109): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/dalvikvm(  771): GC_CONCURRENT freed 2307K, 53% free 26652K/55584K, paused 33ms+5ms, total 93ms
,I/wpa_supplicant( 4109): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 4109): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,E/WifiStateMachine(  771): scanCount==0 - aborting
,D/WifiStateMachine(  771): VerifyingLinkState enter
,D/WifiStateMachine(  771): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  771): CaptivePortalCheckState enter
,D/ConnectivityService(  771): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  771): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  771): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  771): Unexpected mtu value: android.net.wifi.WifiStateTracker@42ec1430
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  771): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  771): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  771):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,W/bt-l2cap( 2593): l2cu_get_conn_role 1
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Coordinator is now connected to the server!
I/jxcore-log( 2539): 
,D/CaptivePortalTracker(  771): NoActiveNetworkState{ when=-16ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering(  771): MasterInitialState.processMessage what=3
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/iu.Environment( 1317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 1317): num queued entries: 0
,I/iu.UploadsManager( 1317): num updated entries: 0
I/iu.SyncManager( 1317): NEXT; no task
,I/SystemUpdateService( 1317): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1317): onCreate
,D/SystemUpdateService( 1317): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/SystemUpdateService( 1317): active receiver: enabled
,I/SystemUpdateService( 1317): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1317): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1317): now status is 0 (complete)
I/SystemUpdateService( 1317): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1317): file has been verified
,I/SystemUpdateService( 1317): OTA package size = 2571501
,I/SystemUpdateService( 1317): showing system update notification
,D/SystemUpdateService( 1317): onDestroy
,I/Babel   ( 1888): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/btif_config_util( 2593): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 2593): l2cu_get_conn_role 1
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,D/CaptivePortalTracker(  771): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=8 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  771): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  771): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  771): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  771): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  771): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/btif_config_util( 2593): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 2593): l2cu_get_conn_role 1
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BluetoothConnectionReceiver( 1193): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1193): Bluetooth Device Name: ALE-L21
,D/dalvikvm( 1193): GC_CONCURRENT freed 509K, 5% free 17831K/18768K, paused 2ms+1ms, total 18ms
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,E/bt-btm  ( 2593): tBTM_SEC_DEV:0x7520695c rs_disc_pending=1
,W/bt-btif ( 2593): bta_dm_check_av:0
,W/bt-btif ( 2593): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 4109): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  771): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  771): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  771): Attempting to switch to mobile
,D/ConnectivityService(  771): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  771): android_net_utils_resetConnections in env=0x77ab8f90 clazz=0x5ee00001 iface=wlan0 mask=0x3
D/ConnectivityService(  771): resetConnections(wlan0, 3)
,V/NativeCrypto( 1100): Read error: ssl=0x762ade68: I/O error during system call, Connection timed out
,V/NativeCrypto( 1100): SSL shutdown failed: ssl=0x762ade68: I/O error during system call, Broken pipe
,I/jxcore-log( 2539): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): The Coordinator has disconnected!
I/jxcore-log( 2539): 
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,D/WifiService(  771): setWifiEnabled: false pid=2539, uid=10108
,D/WifiService(  771): setWifiEnabled: true pid=2539, uid=10108
,W/wpa_supplicant( 4109): wlan0: Failed to initiate AP scan
,E/WifiStateMachine(  771): scanCount==0 - aborting
,D/WifiController(  771): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 480ms
,I/jxcore-log( 2539): Wifi toggled for connection repairment
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/WifiController(  771): DEFERRED_TOGGLE handled
,E/bt-btm  ( 2593): tBTM_SEC_DEV:0x7520695c rs_disc_pending=0
,W/bt-btif ( 2593): bta_dm_check_av:0
,W/bt-btif ( 2593): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 4109): p2p0: CTRL-EVENT-TERMINATING 
,D/Tethering(  771): InitialState.processMessage what=4
,D/Tethering(  771): sendTetherStateChangedBroadcast 0, 0, 0
,I/wpa_supplicant( 4109): wlan0: CTRL-EVENT-TERMINATING 
,W/Settings( 1888): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  980): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/SoftapController(  179): Softap fwReload - Ok
D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring down wlan0
,D/WifiMonitor(  771): startMonitoring(wlan0) with mConnected = false
,E/WifiHW  (  771): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,I/wpa_supplicant( 4426): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 4426): rfkill: Cannot open RFKILL control device
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1193): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1193): Bluetooth Device Name: ALE-L21
D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Babel   ( 1888): connection state changed from CONNECTED to DISCONNECTED
,I/iu.Environment( 1317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1317): num queued entries: 0
,I/iu.UploadsManager( 1317): num updated entries: 0
,I/iu.SyncManager( 1317): NEXT; no task
,I/SystemUpdateService( 1317): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1317): onCreate
,D/SystemUpdateService( 1317): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1317): active receiver: enabled
,I/SystemUpdateService( 1317): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1317): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1317): now status is 0 (complete)
I/SystemUpdateService( 1317): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1317): file has been verified
,I/SystemUpdateService( 1317): OTA package size = 2571501
,I/SystemUpdateService( 1317): showing system update notification
,D/SystemUpdateService( 1317): onDestroy
,D/Tethering(  771): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 4426): rfkill: Cannot open RFKILL control device
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiConfigStore(  771): Loading config and enabling all networks
,W/Settings( 1888): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring up p2p0
,D/WifiMonitor(  771): startMonitoring(p2p0) with mConnected = true
,W/wpa_supplicant( 4426): wlan0: Failed to initiate AP scan
,D/btif_config_util( 2593): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/wpa_supplicant( 4426): wlan0: Failed to initiate AP scan
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,W/bt-l2cap( 2593): l2cu_get_conn_role 0
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [58:2a:f7:ed:96:be]: 6, f, 4106
,I/BluetoothConnectionReceiver( 1193): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,D/dalvikvm( 2593): GC_CONCURRENT freed 409K, 3% free 16875K/17316K, paused 8ms+1ms, total 16ms
,I/BluetoothClassifier( 1193): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/btif_config_util( 2593): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1193): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1193): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/dalvikvm(  980): GC_CONCURRENT freed 381K, 3% free 17906K/18420K, paused 2ms+1ms, total 18ms
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-l2cap( 2593): l2cu_get_conn_role 0
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BluetoothConnectionReceiver( 1193): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1193): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 4426): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant( 4426): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 4426): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 4426): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  771): scanCount==0 - aborting
,D/WifiStateMachine(  771): VerifyingLinkState enter
,D/WifiStateMachine(  771): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  771): CaptivePortalCheckState enter
,D/WifiStateMachine(  771): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  771): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  771): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  771): Unexpected mtu value: android.net.wifi.WifiStateTracker@42ec1430
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/btif_config_util( 2593): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1193): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1193): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/ConnectivityService(  771): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  771): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  771):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Coordinator is now connected to the server!
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): NoActiveNetworkState{ when=-57ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/iu.Environment( 1317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1317): num queued entries: 0
,I/SystemUpdateService( 1317): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/iu.UploadsManager( 1317): num updated entries: 0
,D/SystemUpdateService( 1317): onCreate
,D/SystemUpdateService( 1317): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.SyncManager( 1317): NEXT; no task
,I/SystemUpdateService( 1317): active receiver: enabled
,I/SystemUpdateService( 1317): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1317): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1317): now status is 0 (complete)
,I/SystemUpdateService( 1317): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1317): file has been verified
,I/SystemUpdateService( 1317): OTA package size = 2571501
,I/SystemUpdateService( 1317): showing system update notification
,D/SystemUpdateService( 1317): onDestroy
,D/dalvikvm( 2819): GC_CONCURRENT freed 287K, 2% free 16803K/17120K, paused 4ms+1ms, total 27ms
,I/Babel   ( 1888): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,W/bt-l2cap( 2593): l2cu_get_conn_role 0
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BluetoothConnectionReceiver( 1193): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1193): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/btif_config_util( 2593): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1193): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1193): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/CaptivePortalTracker(  771): DelayedCaptiveCheckState{ when=-2ms what=2 arg1=9 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  771): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  771): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  771): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  771): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  771): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,W/bt-l2cap( 2593): l2cu_get_conn_role 0
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BluetoothConnectionReceiver( 1193): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1193): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,E/bt-btm  ( 2593): tBTM_SEC_DEV:0x752065e4 rs_disc_pending=0
,W/bt-btif ( 2593): bta_dm_check_av:0
,W/bt-btif ( 2593): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2593): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothConnectionReceiver( 1193): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 1193): Bluetooth Device Name: ALE-L21
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/BluetoothAdapterService(1117743376)( 2593): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2593): getBondedDevices: length=6
,D/dalvikvm(  980): GC_CONCURRENT freed 394K, 3% free 17904K/18420K, paused 2ms+1ms, total 19ms
,I/wpa_supplicant( 4426): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  771): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  771): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  771): Attempting to switch to mobile
,D/ConnectivityService(  771): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  771): android_net_utils_resetConnections in env=0x77ab8f90 clazz=0x7ea00001 iface=wlan0 mask=0x3
D/ConnectivityService(  771): resetConnections(wlan0, 3)
,I/jxcore-log( 2539): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): The Coordinator has disconnected!
I/jxcore-log( 2539): 
,V/NativeCrypto( 1100): Read error: ssl=0x78f10fd8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1100): SSL shutdown failed: ssl=0x78f10fd8: I/O error during system call, Broken pipe
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/dalvikvm( 1209): GC_CONCURRENT freed 395K, 3% free 16768K/17252K, paused 6ms+1ms, total 32ms
,D/dalvikvm(  965): GC_CONCURRENT freed 296K, 2% free 16996K/17320K, paused 5ms+1ms, total 54ms
,I/iu.Environment( 1317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1317): num queued entries: 0
,I/iu.UploadsManager( 1317): num updated entries: 0
,I/Babel   ( 1888): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1317): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1317): onCreate
,I/iu.SyncManager( 1317): NEXT; no task
,D/SystemUpdateService( 1317): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/SystemUpdateService( 1317): active receiver: enabled
,I/SystemUpdateService( 1317): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1317): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1317): now status is 0 (complete)
I/SystemUpdateService( 1317): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1317): file has been verified
,I/SystemUpdateService( 1317): OTA package size = 2571501
,I/SystemUpdateService( 1317): showing system update notification
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/SystemUpdateService( 1317): onDestroy
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,D/WifiService(  771): setWifiEnabled: false pid=2539, uid=10108
,D/WifiService(  771): setWifiEnabled: true pid=2539, uid=10108
,D/WifiController(  771): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 461ms
,I/jxcore-log( 2539): Wifi toggled for connection repairment
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,E/WifiStateMachine(  771): scanCount==0 - aborting
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/WifiController(  771): DEFERRED_TOGGLE handled
,I/wpa_supplicant( 4426): p2p0: CTRL-EVENT-TERMINATING 
,D/Tethering(  771): InitialState.processMessage what=4
,D/Tethering(  771): sendTetherStateChangedBroadcast 0, 0, 0
,I/wpa_supplicant( 4426): wlan0: CTRL-EVENT-TERMINATING 
,W/Settings( 1888): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  980): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/dalvikvm( 2643): GC_CONCURRENT freed 341K, 3% free 16974K/17344K, paused 2ms+3ms, total 19ms
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,D/dalvikvm(  771): GC_CONCURRENT freed 2324K, 52% free 26697K/55584K, paused 2ms+5ms, total 62ms
,D/SoftapController(  179): Softap fwReload - Ok
D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring down wlan0
,D/WifiMonitor(  771): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 4645): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 4645): rfkill: Cannot open RFKILL control device
,D/Tethering(  771): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 4645): rfkill: Cannot open RFKILL control device
,D/WifiConfigStore(  771): Loading config and enabling all networks
,W/Settings( 1888): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring up p2p0
,D/WifiMonitor(  771): startMonitoring(p2p0) with mConnected = true
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 4645): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 4645): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 4645): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 4645): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,D/dalvikvm( 1016): GC_CONCURRENT freed 333K, 3% free 16743K/17104K, paused 6ms+1ms, total 42ms
,E/WifiStateMachine(  771): scanCount==0 - aborting
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiStateMachine(  771): VerifyingLinkState enter
,D/WifiStateMachine(  771): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  771): CaptivePortalCheckState enter
,D/WifiStateMachine(  771): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  771): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  771): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  771): Unexpected mtu value: android.net.wifi.WifiStateTracker@42ec1430
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  771): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  771): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  771):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/iu.Environment( 1317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SystemUpdateService( 1317): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1317): onCreate
,D/SystemUpdateService( 1317): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1317): active receiver: enabled
,I/iu.UploadsManager( 1317): num queued entries: 0
,I/SystemUpdateService( 1317): Already downloaded, skipping offpeak checks.
,I/iu.UploadsManager( 1317): num updated entries: 0
,I/iu.SyncManager( 1317): NEXT; no task
,I/SystemUpdateService( 1317): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1317): now status is 0 (complete)
I/SystemUpdateService( 1317): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1317): file has been verified
,I/SystemUpdateService( 1317): OTA package size = 2571501
,I/SystemUpdateService( 1317): showing system update notification
,D/SystemUpdateService( 1317): onDestroy
,D/dalvikvm( 1317): GC_CONCURRENT freed 672K, 4% free 18949K/19652K, paused 8ms+4ms, total 36ms
,I/Babel   ( 1888): connection state changed from DISCONNECTED to CONNECTED
,D/dalvikvm( 1100): GC_CONCURRENT freed 506K, 5% free 18388K/19312K, paused 1ms+2ms, total 15ms
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Coordinator is now connected to the server!
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,D/CaptivePortalTracker(  771): DelayedCaptiveCheckState{ when=-2ms what=2 arg1=10 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  771): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  771): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  771): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  771): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  771): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/wpa_supplicant( 4645): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  771): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  771): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  771): Attempting to switch to mobile
,D/ConnectivityService(  771): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  771): android_net_utils_resetConnections in env=0x77ab8f90 clazz=0x9fc00001 iface=wlan0 mask=0x3
D/ConnectivityService(  771): resetConnections(wlan0, 3)
,I/jxcore-log( 2539): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): The Coordinator has disconnected!
I/jxcore-log( 2539): 
,V/NativeCrypto( 1100): Read error: ssl=0x7a82be20: I/O error during system call, Connection timed out
,V/NativeCrypto( 1100): SSL shutdown failed: ssl=0x7a82be20: I/O error during system call, Broken pipe
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant( 4645): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,D/WifiService(  771): setWifiEnabled: false pid=2539, uid=10108
,E/WifiStateMachine(  771): scanCount==0 - aborting
D/WifiService(  771): setWifiEnabled: true pid=2539, uid=10108
,D/WifiController(  771): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 483ms
,I/jxcore-log( 2539): Wifi toggled for connection repairment
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/dalvikvm( 2604): GC_CONCURRENT freed 415K, 3% free 16808K/17252K, paused 2ms+1ms, total 36ms
,D/WifiController(  771): DEFERRED_TOGGLE handled
,I/wpa_supplicant( 4645): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 4645): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/Tethering(  771): InitialState.processMessage what=4
,D/Tethering(  771): sendTetherStateChangedBroadcast 0, 0, 0
,I/wpa_supplicant( 4645): wlan0: CTRL-EVENT-TERMINATING 
,W/Settings( 1888): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  980): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Babel   ( 1888): connection state changed from CONNECTED to DISCONNECTED
,I/iu.Environment( 1317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1317): num queued entries: 0
D/SoftapController(  179): Softap fwReload - Ok
,I/iu.UploadsManager( 1317): num updated entries: 0
D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring down wlan0
,I/iu.SyncManager( 1317): NEXT; no task
,I/SystemUpdateService( 1317): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/WifiMonitor(  771): startMonitoring(wlan0) with mConnected = false
,D/SystemUpdateService( 1317): onCreate
,D/SystemUpdateService( 1317): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/wpa_supplicant( 4798): Successfully initialized wpa_supplicant
,I/SystemUpdateService( 1317): active receiver: enabled
,I/SystemUpdateService( 1317): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1317): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1317): now status is 0 (complete)
I/SystemUpdateService( 1317): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1317): file has been verified
,I/SystemUpdateService( 1317): OTA package size = 2571501
,I/SystemUpdateService( 1317): showing system update notification
,D/SystemUpdateService( 1317): onDestroy
,I/wpa_supplicant( 4798): rfkill: Cannot open RFKILL control device
,D/Tethering(  771): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 4798): rfkill: Cannot open RFKILL control device
,D/WifiConfigStore(  771): Loading config and enabling all networks
,W/Settings( 1888): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring up p2p0
,D/WifiMonitor(  771): startMonitoring(p2p0) with mConnected = true
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService(  771): NetTransition Wakelock for ConnectedState released by timeout
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,D/WifiService(  771): setWifiEnabled: false pid=2539, uid=10108
,D/WifiService(  771): setWifiEnabled: true pid=2539, uid=10108
,D/WifiController(  771): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 481ms
,I/jxcore-log( 2539): Wifi toggled for connection repairment
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,E/WifiStateMachine(  771): scanCount==0 - aborting
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,I/wpa_supplicant( 4798): p2p0: CTRL-EVENT-TERMINATING 
,D/Tethering(  771): InitialState.processMessage what=4
,D/Tethering(  771): sendTetherStateChangedBroadcast 0, 0, 0
,I/wpa_supplicant( 4798): wlan0: CTRL-EVENT-TERMINATING 
,W/Settings( 1888): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  980): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  771): DEFERRED_TOGGLE handled
,D/SoftapController(  179): Softap fwReload - Ok
,D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring down wlan0
,I/wpa_supplicant( 4830): Successfully initialized wpa_supplicant
,D/WifiMonitor(  771): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 4830): rfkill: Cannot open RFKILL control device
,D/Tethering(  771): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 4830): rfkill: Cannot open RFKILL control device
,D/WifiConfigStore(  771): Loading config and enabling all networks
,W/Settings( 1888): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring up p2p0
,D/WifiMonitor(  771): startMonitoring(p2p0) with mConnected = true
,W/wpa_supplicant( 4830): wlan0: Failed to initiate AP scan
,W/ProcessCpuTracker(  771): Skipping unknown process pid 4858
,W/ProcessCpuTracker(  771): Skipping unknown process pid 4859
W/ProcessCpuTracker(  771): Skipping unknown process pid 4861
W/ProcessCpuTracker(  771): Skipping unknown process pid 4862
,W/ProcessCpuTracker(  771): Skipping unknown process pid 4866
,W/wpa_supplicant( 4830): wlan0: Failed to initiate AP scan
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/btif_config_util( 2593): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 4830): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 4830): wlan0: Associated with c0:ff:d4:d3:aa:48
,W/bt-l2cap( 2593): l2cu_get_conn_role 1
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2593): tBTM_SEC_DEV:0x75206b18 rs_disc_pending=1
,W/bt-btif ( 2593): bta_dm_check_av:0
,W/bt-btif ( 2593): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2593): tBTM_SEC_DEV:0x75206cd4 rs_disc_pending=0
,W/bt-btif ( 2593): bta_dm_check_av:0
,W/bt-btif ( 2593): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2593): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 4830): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 4830): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  771): scanCount==0 - aborting
,D/WifiStateMachine(  771): VerifyingLinkState enter
,D/WifiStateMachine(  771): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  771): CaptivePortalCheckState enter
,D/ConnectivityService(  771): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  771): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  771): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  771): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  771): Unexpected mtu value: android.net.wifi.WifiStateTracker@42ec1430
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Coordinator is now connected to the server!
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-l2cap( 2593): l2cu_get_conn_role 0
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2593): tBTM_SEC_DEV:0x75206b18 rs_disc_pending=0
,W/bt-btif ( 2593): bta_dm_check_av:0
,W/bt-btif ( 2593): btif_dm_cback : unhandled event (14)
,D/ConnectivityService(  771): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  771):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): NoActiveNetworkState{ when=-5ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/iu.Environment( 1317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1317): num queued entries: 0
,I/SystemUpdateService( 1317): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/dalvikvm(  939): GC_CONCURRENT freed 342K, 3% free 17074K/17444K, paused 1ms+5ms, total 38ms
,I/iu.UploadsManager( 1317): num updated entries: 0
,D/SystemUpdateService( 1317): onCreate
,I/iu.SyncManager( 1317): NEXT; no task
,D/SystemUpdateService( 1317): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1317): active receiver: enabled
,I/SystemUpdateService( 1317): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1317): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1317): now status is 0 (complete)
I/SystemUpdateService( 1317): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1317): file has been verified
,I/SystemUpdateService( 1317): OTA package size = 2571501
,I/SystemUpdateService( 1317): showing system update notification
,D/SystemUpdateService( 1317): onDestroy
,D/dalvikvm(  771): GC_CONCURRENT freed 2370K, 52% free 26718K/55584K, paused 5ms+4ms, total 72ms
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2593): tBTM_SEC_DEV:0x75206b18 rs_disc_pending=1
,W/bt-btif ( 2593): bta_dm_check_av:0
,W/bt-btif ( 2593): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,I/Babel   ( 1888): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/btif_config_util( 2593): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 2593): l2cu_get_conn_role 0
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,D/CaptivePortalTracker(  771): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=11 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  771): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  771): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  771): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  771): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  771): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/btif_config_util( 2593): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2593): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 2593): l2cu_get_conn_role 1
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [34:fc:ef:11:ae:67]: 7, f, 610c
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2593): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,D/dalvikvm( 2593): GC_CONCURRENT freed 396K, 3% free 16875K/17316K, paused 18ms+1ms, total 62ms
,E/bt-btm  ( 2593): tBTM_SEC_DEV:0x75206b18 rs_disc_pending=1
,W/bt-btif ( 2593): bta_dm_check_av:0
W/bt-btif ( 2593): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2593): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 2593): l2cu_get_conn_role 0
,W/bt-btif ( 2593): info:x10
,D/        ( 2593): remote version info [b0:c5:59:3f:75:69]: 7, f, 6109
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2593): tBTM_SEC_DEV:0x75206cd4 rs_disc_pending=0
,W/bt-btif ( 2593): bta_dm_check_av:0
,W/bt-btif ( 2593): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 4830): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  771): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  771): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  771): Attempting to switch to mobile
,D/ConnectivityService(  771): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  771): android_net_utils_resetConnections in env=0x77ab8f90 clazz=0xbf300001 iface=wlan0 mask=0x3
D/ConnectivityService(  771): resetConnections(wlan0, 3)
,V/NativeCrypto( 1100): Read error: ssl=0x78f10fd8: I/O error during system call, Connection timed out
I/jxcore-log( 2539): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): The Coordinator has disconnected!
I/jxcore-log( 2539): 
,V/NativeCrypto( 1100): SSL shutdown failed: ssl=0x78f10fd8: I/O error during system call, Broken pipe
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,D/WifiService(  771): setWifiEnabled: false pid=2539, uid=10108
,W/wpa_supplicant( 4830): wlan0: Failed to initiate AP scan
,D/WifiService(  771): setWifiEnabled: true pid=2539, uid=10108
E/WifiStateMachine(  771): scanCount==0 - aborting
,D/WifiController(  771): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 483ms
,I/jxcore-log( 2539): Wifi toggled for connection repairment
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/btif_config_util( 2593): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/WifiController(  771): DEFERRED_TOGGLE handled
,E/bt-btm  ( 2593): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2593): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 4830): p2p0: CTRL-EVENT-TERMINATING 
,D/Tethering(  771): InitialState.processMessage what=4
,D/Tethering(  771): sendTetherStateChangedBroadcast 0, 0, 0
,I/wpa_supplicant( 4830): wlan0: CTRL-EVENT-TERMINATING 
,W/Settings( 1888): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  980): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/SoftapController(  179): Softap fwReload - Ok
D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring down wlan0
,D/WifiMonitor(  771): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 4988): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 4988): rfkill: Cannot open RFKILL control device
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/Babel   ( 1888): connection state changed from CONNECTED to DISCONNECTED
,I/iu.Environment( 1317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1317): num queued entries: 0
,I/iu.UploadsManager( 1317): num updated entries: 0
,I/iu.SyncManager( 1317): NEXT; no task
,I/SystemUpdateService( 1317): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1317): onCreate
,D/SystemUpdateService( 1317): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1317): active receiver: enabled
,I/SystemUpdateService( 1317): Already downloaded, skipping offpeak checks.
I/SystemUpdateService( 1317): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1317): now status is 0 (complete)
I/SystemUpdateService( 1317): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1317): file has been verified
,I/SystemUpdateService( 1317): OTA package size = 2571501
,I/SystemUpdateService( 1317): showing system update notification
,D/SystemUpdateService( 1317): onDestroy
,D/Tethering(  771): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 4988): rfkill: Cannot open RFKILL control device,
,D/WifiConfigStore(  771): Loading config and enabling all networks
,W/Settings( 1888): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring up p2p0
,D/WifiMonitor(  771): startMonitoring(p2p0) with mConnected = true
,W/wpa_supplicant( 4988): wlan0: Failed to initiate AP scan
,W/wpa_supplicant( 4988): wlan0: Failed to initiate AP scan
,I/wpa_supplicant( 4988): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/wpa_supplicant( 4988): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 4988): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 4988): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  771): scanCount==0 - aborting
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiStateMachine(  771): VerifyingLinkState enter
,D/WifiStateMachine(  771): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  771): CaptivePortalCheckState enter
D/ConnectivityService(  771): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  771): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  771): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  771): Unexpected mtu value: android.net.wifi.WifiStateTracker@42ec1430
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  771): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  771): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  771):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/iu.Environment( 1317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1317): num queued entries: 0
,I/SystemUpdateService( 1317): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/iu.UploadsManager( 1317): num updated entries: 0
,D/SystemUpdateService( 1317): onCreate
,D/SystemUpdateService( 1317): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1317): active receiver: enabled
,I/iu.SyncManager( 1317): NEXT; no task
,I/SystemUpdateService( 1317): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1317): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1317): now status is 0 (complete)
I/SystemUpdateService( 1317): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1317): file has been verified
,I/SystemUpdateService( 1317): OTA package size = 2571501
,I/SystemUpdateService( 1317): showing system update notification
,D/SystemUpdateService( 1317): onDestroy
,I/Babel   ( 1888): connection state changed from DISCONNECTED to CONNECTED
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Coordinator is now connected to the server!
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=0, published condition=100
,I/wpa_supplicant( 4988): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  771): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  771): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  771): Attempting to switch to mobile
,D/ConnectivityService(  771): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  771): android_net_utils_resetConnections in env=0x77ab8f90 clazz=0xdf100001 iface=wlan0 mask=0x3
D/ConnectivityService(  771): resetConnections(wlan0, 3)
,I/jxcore-log( 2539): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): The Coordinator has disconnected!
I/jxcore-log( 2539): 
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=false
,I/wpa_supplicant( 4988): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2462 MHz)
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Error type "connect_error" when connecting to the test server
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 4988): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 4988): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 4988): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,E/WifiStateMachine(  771): scanCount==0 - aborting
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): DelayedCaptiveCheckState{ when=-12ms what=1 obj=NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker(  771): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/iu.Environment( 1317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1317): num queued entries: 0
,I/iu.UploadsManager( 1317): num updated entries: 0
,I/Babel   ( 1888): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1317): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1317): onCreate
,D/SystemUpdateService( 1317): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.SyncManager( 1317): NEXT; no task
,I/SystemUpdateService( 1317): active receiver: enabled
,I/SystemUpdateService( 1317): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1317): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1317): now status is 0 (complete)
I/SystemUpdateService( 1317): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1317): file has been verified
,I/SystemUpdateService( 1317): OTA package size = 2571501
,I/SystemUpdateService( 1317): showing system update notification
,D/SystemUpdateService( 1317): onDestroy
,D/dalvikvm( 1006): GC_EXPLICIT freed 369K, 3% free 17073K/17468K, paused 12ms+3ms, total 60ms
,D/CaptivePortalTracker(  771): NoActiveNetworkState{ when=-1ms what=2 arg1=12 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker(  771): DefaultState{ when=-1ms what=2 arg1=12 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  771): VerifyingLinkState enter
,D/WifiStateMachine(  771): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  771): CaptivePortalCheckState enter
,D/ConnectivityService(  771): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  771): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  771): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  771): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  771): Unexpected mtu value: android.net.wifi.WifiStateTracker@42ec1430
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,I/jxcore-log( 2539): DBG, CoordinatorConnector connect called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): Coordinator is now connected to the server!
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,D/ConnectivityService(  771): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  771): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  771):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  771): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  771): NoActiveNetworkState{ when=-9ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/dalvikvm(  939): GC_EXPLICIT freed 188K, 3% free 16927K/17444K, paused 2ms+2ms, total 17ms
,I/iu.Environment( 1317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1317): num queued entries: 0
,I/iu.UploadsManager( 1317): num updated entries: 0
,I/iu.SyncManager( 1317): NEXT; no task
,I/SystemUpdateService( 1317): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1317): onCreate
,D/SystemUpdateService( 1317): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1317): active receiver: enabled
,I/SystemUpdateService( 1317): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1317): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1317): now status is 0 (complete)
I/SystemUpdateService( 1317): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1317): file has been verified
,I/SystemUpdateService( 1317): OTA package size = 2571501
,I/SystemUpdateService( 1317): showing system update notification
,D/SystemUpdateService( 1317): onDestroy
,D/dalvikvm( 1100): GC_CONCURRENT freed 476K, 5% free 18383K/19312K, paused 1ms+1ms, total 14ms
,I/Babel   ( 1888): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  771): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  771): DelayedCaptiveCheckState{ when=-2ms what=2 arg1=13 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  771): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  771): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  771): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  771): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  771): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  771): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  771): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/ConnectivityService(  771): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  771): Done.
,D/ConnectivityService(  771): Setting timer for 720seconds
,I/jxcore-log( 2539): DBG, CoordinatorConnector command called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): command received : {"command":"timeout","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): stop tests now !
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback stop-by-timeout", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2539): DBG, CoordinatorConnector command called
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): command received : {"command":"end","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): ****TEST TOOK:  ms ****
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): stop tests now !
I/jxcore-log( 2539): 
I/jxcore-log( 2539): end, event received
I/jxcore-log( 2539): 
I/jxcore-log( 2539): CoordinatorConnector close called
I/jxcore-log( 2539): 
I/jxcore-log( 2539): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2539): 
I/jxcore-log( 2539): The Coordinator has disconnected!
I/jxcore-log( 2539): 
I/jxcore-log( 2539): The Coordinator has closed!
I/jxcore-log( 2539): 
I/jxcore-log( 2539): stop tests now !
I/jxcore-log( 2539): 
,I/jxcore-log( 2539): turning Radios off
I/jxcore-log( 2539): 
I/jxcore-log( 2539): Toggling radios to false
I/jxcore-log( 2539): 
D/BluetoothManagerService(  771): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  771): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@44726cd8 mBinding = false
,D/BluetoothManagerService(  771): Message: 2
D/BluetoothManagerService(  771): Sending off request.
D/BluetoothAdapterState( 2593): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2593): Setting state to 13
I/BluetoothAdapterState( 2593): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 2593): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterProperties( 2593): onBluetoothDisable()
,I/BluetoothAdapterState( 2593): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/BluetoothAdapterProperties( 2593): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothAdapterProperties( 2593): Scan Mode:20
,D/BluetoothAdapterState( 2593): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 2593): bta_jv_rfcomm_stop_server
E/bt-btif ( 2593): bta_jv_rfcomm_stop_server
E/BtOppRfcommListener( 2593): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/BluetoothManagerService(  771): Message: 60
E/bt-btif ( 2593): bta_jv_rfcomm_stop_server
D/BluetoothManagerService(  771): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
W/bt-btif ( 2593): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
W/bt-l2cap( 2593): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 2593): L2CAP - PSM: 0x0017 not found for deregistration
D/btif_config_util( 2593): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/BluetoothManagerService(  771): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 2593): onReceive
,D/BluetoothMapService( 2593): STATE_TURNING_OFF
,D/BluetoothMapService( 2593): MAP Service closeService in
I/BtOppRfcommListener( 2593): stopping Accept Thread
,I/BtOppRfcommListener( 2593): BluetoothSocket listen thread finished
,D/CachedBluetoothDevice( 2604):  Clearing all connection state for dev:Thali Test (Galaxy A3)
D/WifiService(  771): setWifiEnabled: false pid=2539, uid=10108
,D/CachedBluetoothDevice( 2604):  Clearing all connection state for dev:XT1039
,D/CachedBluetoothDevice( 2604):  Clearing all connection state for dev:G3s-1
,D/CachedBluetoothDevice( 2604):  Clearing all connection state for dev:Note3-1
,I/jxcore-log( 2539): Radios toggled
I/jxcore-log( 2539): 
,I/chromium( 2539): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
,D/CachedBluetoothDevice( 2604):  Clearing all connection state for dev:G4-1
,D/CachedBluetoothDevice( 2604):  Clearing all connection state for dev:ALE-L21
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/bt_hwcfg( 2593): hw_epilog_process
W/bt-btif ( 2593): ag scb idx 1 not allocated
E/bt-btif ( 2593): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2593): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2593): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2593): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2593): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2593): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 2593): L2CAP - PSM: 0x0017 not found for deregistration
,E/WifiStateMachine(  771): scanCount==0 - aborting
W/ContextImpl( 2604): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 2604): finishStartingService: stopping service
D/ConnectivityService(  771): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService(  771): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  771): Attempting to switch to mobile
,D/ConnectivityService(  771): Attempting to switch to BLUETOOTH_TETHER
D/BluetoothPbap( 2604): Proxy object disconnected
D/PbapServerProfile( 2604): Bluetooth service disconnected
D/bt_hwcfg( 2593): hw_epilog_cback Opcode:0x0C03 Status: 0
I/bt_hci_bdroid( 2593): bt_hc_worker_thread exiting
W/bt_userial( 2593): select_read return size <=0:-1, exiting userial_read_thread
I/bt_userial_vendor( 2593): device fd = 65 close
D/BTSNOOP-DISP( 2593): btsnoop_close
I/GKI_LINUX( 2593): gki_task_entry: gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2593): GKI_exit_task: GKI_exit_task 0 done
I/GKI_LINUX( 2593): GKI_destroy_task: GKI_shutdown(): task [BTU] terminated
,D/AuthorizationBluetoothService( 1100): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothAdapterState( 2593): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 2593): Received stop request...Stopping profile...
,D/NetUtils(  771): android_net_utils_resetConnections in env=0x77ab8f90 clazz=0x1e000001 iface=wlan0 mask=0x3
W/BroadcastQueue(  771): Permission Denial: receiving Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 (has extras) } to com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver requires android.permission.BLUETOOTH due to sender android (uid 1000)
,D/ConnectivityService(  771): resetConnections(wlan0, 3)
D/CommandListener(  179): Clearing all IP addresses on wlan0
D/BluetoothHeadset(  771): Proxy object disconnected
D/BluetoothHeadset( 1006): Proxy object disconnected
D/BluetoothHeadset( 1006): Proxy object disconnected
D/BluetoothHeadset( 1006): Proxy object disconnected
D/BluetoothHeadset( 2604): Proxy object disconnected
D/HeadsetProfile( 2604): Bluetooth service disconnected
D/A2dpService( 2593): Received stop request...Stopping profile...
D/A2dpStateMachine( 2593): Exit Disconnected: -1
D/BluetoothA2dp(  771): Proxy object disconnected
D/HidService( 2593): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2593): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHeadsetServiceJni( 2593): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2593): Cleaning up Bluetooth Handsfree callback object
D/HealthService( 2593): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2593): Profile still running: com.android.bluetooth.hdp.HealthService
I/GKI_LINUX( 2593): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2593): GKI_exit_task: GKI_exit_task 2 done
I/GKI_LINUX( 2593): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BluetoothAdapterService( 2593): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 2593): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2593): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2593): Cleaning up Bluetooth GID callback object
D/PanService( 2593): Received stop request...Stopping profile...
D/BluetoothAdapterState( 2593): Stopping profile services that were post enabled
D/BluetoothA2dp( 2604): Proxy object disconnected
D/A2dpProfile( 2604): Bluetooth service disconnected
D/BluetoothPan(  771): BluetoothPAN Proxy object disconnected
D/BluetoothInputDevice( 2604): Proxy object disconnected
D/HidProfile( 2604): Bluetooth service disconnected
D/BluetoothPan( 2604): BluetoothPAN Proxy object disconnected
D/PanProfile( 2604): Bluetooth service disconnected
D/BluetoothAdapterService( 2593): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 2593): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2593): Cleaning up Bluetooth Health object
D/BtGatt.DebugUtils( 2593): handleDebugAction() action=null
D/BtGatt.GattService( 2593): Received stop request...Stopping profile...
D/BtGatt.GattService( 2593): stop()
D/BluetoothAdapterService( 2593): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/BluetoothMapService( 2593): Received stop request...Stopping profile...
D/BluetoothMapService( 2593): stop()
D/BluetoothMapService( 2593): MAP Service closeService in
D/BluetoothMap( 2604): Proxy object disconnected
D/MapProfile( 2604): Bluetooth service disconnected
W/BluetoothPanServiceJni( 2593): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2593): Cleaning up Bluetooth PAN callback object
,D/BluetoothAdapterService( 2593): Profile still running: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterState( 2593): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2593): Setting state to 10
I/BluetoothAdapterState( 2593): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 2593): Broadcasting updateAdapterState() to 1 receivers.
I/BluetoothAdapterState( 2593): Entering OffState
D/BluetoothMapService( 2593): cleanup()
D/BluetoothManagerService(  771): Message: 60
D/BluetoothManagerService(  771): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  771): Broadcasting onBluetoothStateChange(false) to 12 receivers.
D/BluetoothMapService( 2593): MAP Service closeService in
D/BluetoothHeadset(  771): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1006): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1006): onBluetoothStateChange: up=false
D/BluetoothA2dp(  771): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1006): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 2604): onBluetoothStateChange: up=false
D/BluetoothMap( 2604): onBluetoothStateChange: up=false
D/BluetoothPbap( 2604): onBluetoothStateChange: up=false
D/BluetoothA2dp( 2604): onBluetoothStateChange: up=false
D/BluetoothHeadset( 2604): onBluetoothStateChange: up=false
D/BluetoothManagerService(  771): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  771): Broadcasting onBluetoothServiceDown() to 10 receivers.
D/BluetoothManagerService(  771): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@44726cd8 mBinding = false
D/BluetoothManagerService(  771): Sending unbind request.
D/BluetoothAdapterService( 2593): Cleaning up adapter native....
I/GKI_LINUX( 2593): gki_task_entry: gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 2593): GKI_exit_task: GKI_exit_task 1 done
I/GKI_LINUX( 2593): GKI_destroy_task: GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 2593): cleanupNative: return from cleanup
D/BluetoothManagerService(  771): Bluetooth State Change Intent: 13 -> 10
D/BluetoothAdapterService( 2593): Done cleaning up adapter native....
D/BluetoothAdapterService(1117743376)( 2593): ****onDestroy()********
D/BtGatt.GattService( 2593): cleanup()
W/bt-btif ( 2593): GATTC Module not enabled/already disabled
W/bt-btif ( 2593): GATTS Module not enabled/already disabled
D/BluetoothAdapter(  865): 1118200024: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  980): 1118052968: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  980): 1118052968: getState() :  mService = null. Returning STATE_OFF
W/ContextImpl( 2604): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/DockEventReceiver( 2604): finishStartingService: stopping service
V/NativeCrypto( 1100): Read error: ssl=0x78f10fd8: I/O error during system call, Connection timed out
,D/BluetoothAdapter( 2604): 1117742080: getState() :  mService = null. Returning STATE_OFF
V/NativeCrypto( 1100): SSL shutdown failed: ssl=0x78f10fd8: I/O error during system call, Broken pipe
I/ActivityManager(  771): Killing 2401:com.google.android.partnersetup/u0a11 (adj 15): empty #17
D/AuthorizationBluetoothService( 1100): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/BroadcastQueue(  771): Permission Denial: receiving Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 (has extras) } to com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver requires android.permission.BLUETOOTH due to sender android (uid 1000)
D/BluetoothAdapter( 2604): 1117742080: getState() :  mService = null. Returning STATE_OFF
D/AndroidRuntime( 5200): 
D/AndroidRuntime( 5200): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5200): CheckJNI is OFF
D/dalvikvm( 5200): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 5200): Added shared lib libjavacore.so 0x0
D/dalvikvm( 5200): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5200): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5200): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/BluetoothTethering(  771): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering(  771): attempted to stop reverse tether with nothing tethered
D/Nat464Xlat(  771): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityService(  771): handleInetConditionChange: no active default network - ignore
,D/dalvikvm( 5200): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
,D/dalvikvm(  771): GC_CONCURRENT freed 2472K, 52% free 26718K/55584K, paused 2ms+4ms, total 60ms
,D/AndroidRuntime( 5200): Calling main entry com.android.commands.pm.Pm
,I/wpa_supplicant( 4988): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 4988): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/ActivityManager(  771): Force stopping com.test.thalitest appid=10108 user=-1: uninstall pkg
I/ActivityManager(  771): Killing 2539:com.test.thalitest/u0a108 (adj 0): stop com.test.thalitest
I/ActivityManager(  771):   Force finishing activity ActivityRecord{44b798b0 u0 com.test.thalitest/.MainActivity t2}
,I/WindowState(  771): WIN DEATH: Window{44b8d278 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings(  771): Skipping PackageSetting{42b470c8 com.example.hello/10115} due to missing metadata
,I/ActivityManager(  771): Force stopping com.test.thalitest appid=10108 user=0: pkg removed
,I/InputReader(  771): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  771):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  771):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  771):   Scheme: "sms"
I/PackageManager(  771): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/ActivityManager(  771): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5245 uid=10003 gids={50003, 3003, 1028, 1015}
,D/dalvikvm( 1050): GC_EXPLICIT freed 753K, 6% free 26142K/27756K, paused 7ms+2ms, total 50ms
,I/Launcher( 1050): Deferring update until onResume
,I/LatinIME:LogUtils(  965): Dictionary info: dictionary = main:en_us ; version = 44 ; date = 1393228158
,I/PackageManager(  771):   Action: "android.intent.action.SENDTO"
I/PackageManager(  771): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  771):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  771):   Scheme: "smsto"
,W/GeofencerStateMachine(  980): Ignoring removeGeofence because network location is disabled.
D/BackupManagerService(  771): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  771): removePackageParticipantsLocked: uid=10108 #1
,I/PackageManager(  771):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  771):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  771):   Scheme: "mms"
,D/Tethering(  771): InitialState.processMessage what=4
,I/wpa_supplicant( 4988): wlan0: CTRL-EVENT-TERMINATING 
I/PackageManager(  771): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm( 1193): GC_EXPLICIT freed 164K, 6% free 17745K/18768K, paused 1ms+3ms, total 120ms
,I/Launcher( 1050): Deferring update until onResume
I/PackageManager(  771):   Action: "android.intent.action.SENDTO"
I/PackageManager(  771):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  771):   Scheme: "mmsto"
I/PackageManager(  771): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  771):   Action: "android.intent.action.SENDTO"
I/PackageManager(  771):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  771):   Scheme: "sms"
I/PackageManager(  771): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,W/Binder  (  965): Caught a RuntimeException from the binder stub implementation.
W/Binder  (  965): java.lang.NullPointerException
W/Binder  (  965): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  (  965): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  (  965): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  (  965): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  771): Got RemoteException sending setActive(false) notification to pid 2539 uid 10108
,I/PackageManager(  771):   Action: "android.intent.action.SENDTO"
I/PackageManager(  771):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  771):   Scheme: "smsto"
I/PackageManager(  771): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  771):   Action: "android.intent.action.SENDTO"
I/PackageManager(  771):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  771):   Scheme: "mms"
I/PackageManager(  771): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/Tethering(  771): sendTetherStateChangedBroadcast 0, 0, 0
W/Settings( 1888): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  771):   Action: "android.intent.action.SENDTO"
I/PackageManager(  771):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  771):   Scheme: "mmsto"
I/PackageManager(  771): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,W/Settings(  980): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/dalvikvm( 5245): GC_CONCURRENT freed 190K, 2% free 16929K/17148K, paused 12ms+1ms, total 25ms
,D/VoicemailCleanupService( 5245): Cleaning up data for package: com.test.thalitest
,I/Icing.InternalIcingCorporaProvider( 1193): Updating corpora: A: com.test.thalitest, C: MAYBE
I/ActivityManager(  771): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/ActivityManager(  771): Resuming delayed broadcast
W/Launcher( 1050): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@429f2c20 new=com.google.android.velvet.VelvetApplication@429f2c20
,D/dalvikvm(  771): GC_EXPLICIT freed 1159K, 52% free 26745K/55584K, paused 5ms+10ms, total 111ms
,I/ActivityManager(  771): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5273 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
,D/AndroidRuntime( 5200): Shutting down VM
,D/dalvikvm( 5200): GC_CONCURRENT freed 94K, 15% free 558K/656K, paused 0ms+0ms, total 1ms
W/ContextImpl( 5273): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2407 
I/ActivityManager(  771): Delay finish: com.android.keychain/.KeyChainBroadcastReceiver
,I/ActivityManager(  771): Resuming delayed broadcast
,I/ActivityManager(  771): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 1317): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1317): Clearing selected account for com.test.thalitest
,I/Icing.InternalIcingCorporaProvider( 1193): UpdateCorporaTask done [took 77 ms] updated apps [took 77 ms] 
I/ActivityManager(  771): Killing 2490:com.quickoffice.android/u0a65 (adj 15): empty #17
,I/LocationSettingsChecker( 1317): Removing dialog suppression flag for package com.test.thalitest
,D/dalvikvm( 1317): GC_CONCURRENT freed 694K, 4% free 19011K/19732K, paused 1ms+4ms, total 31ms
,D/gH_CompatibleDatabase( 1317): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1317): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1317): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 1317): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,W/BaseAppContext( 1317): Using Auth Proxy for data requests.
,D/gH_CompatibleDatabase( 1317): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1317): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1317): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,W/BaseAppContext( 1317): Using Auth Proxy for data requests.
,D/gH_CompatibleDatabase( 1317): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1317): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1317): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1317): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1317): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1317): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ContactLocale( 5245): AddressBook Labels [en_US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Е, Є, Ж, З, И, І, Ї, Й, К, Л, М, Н, О, П, Р, С, Т, У, Ф, Х, Ц, Ч, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/GMPM-SVC( 1317): App measurement is starting up
,I/PeopleContactsSync( 1317): CP2 sync disabled
,I/Icing   ( 1317): doRemovePackageData com.test.thalitest
,D/dalvikvm( 1317): GC_CONCURRENT freed 570K, 4% free 19132K/19732K, paused 3ms+3ms, total 21ms
,W/DriveInitializer( 1317): Awaiting to be initialized
,W/DriveInitializer( 1317): Background init thread started
,W/DriveInitializer( 1317): Background init thread ended
,E/SQLiteLog( 1317): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DriveAsyncService( 1317): disk I/O error (code 3850)
E/DriveAsyncService( 1317): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1317): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1317): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1317): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1317): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1317): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1317): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1317): 	at com.google.android.gms.drive.database.k.k(SourceFile:485)
E/DriveAsyncService( 1317): 	at com.google.android.gms.drive.database.k.b(SourceFile:460)
E/DriveAsyncService( 1317): 	at com.google.android.gms.drive.database.f.i(SourceFile:1516)
E/DriveAsyncService( 1317): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1317): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/DriveAsyncService( 1317): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1317): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1317): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1317): 	at java.lang.Thread.run(Thread.java:841)
,E/SQLiteDatabase( 1100): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1100): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1100): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1100): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1100): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1100): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1100): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1100): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1100): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1100): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1100): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1100): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:952)
E/SQLiteDatabase( 1100): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1100): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1100): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1100): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 1100): 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:137)
E/SQLiteDatabase( 1100): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:550)
E/SQLiteDatabase( 1100): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:157)
E/SQLiteDatabase( 1100): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/SQLiteDatabase( 1100): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1100): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1100): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/SQLiteDatabase( 1100): 	at java.lang.Thread.run(Thread.java:841)
,E/SQLiteOpenHelper( 1100): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1100): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1100): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1100): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1100): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1100): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1100): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1100): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1100): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteOpenHelper( 1100): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteOpenHelper( 1100): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1100): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:952)
E/SQLiteOpenHelper( 1100): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1100): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteOpenHelper( 1100): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 1100): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 1100): 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:137)
E/SQLiteOpenHelper( 1100): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:550)
E/SQLiteOpenHelper( 1100): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:157)
E/SQLiteOpenHelper( 1100): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/SQLiteOpenHelper( 1100): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1100): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1100): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/SQLiteOpenHelper( 1100): 	at java.lang.Thread.run(Thread.java:841)
,W/SQLiteOpenHelper( 1100): Opened phenotype.db in read-only mode
,E/SQLiteLog( 1100): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1100): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1100): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1100): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1100): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1100): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1100): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1100): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1100): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1100): 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:138)
E/ClearcutLoggerIntentService( 1100): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:550)
E/ClearcutLoggerIntentService( 1100): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:157)
E/ClearcutLoggerIntentService( 1100): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1100): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1100): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1100): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearcutLoggerIntentService( 1100): 	at java.lang.Thread.run(Thread.java:841)
,E/SQLiteLog( 1100): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1100): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1100): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1100): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1100): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1100): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1100): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1100): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1100): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1100): 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:138)
E/ClearcutLoggerIntentService( 1100): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:550)
E/ClearcutLoggerIntentService( 1100): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:157)
E/ClearcutLoggerIntentService( 1100): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1100): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1100): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1100): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearcutLoggerIntentService( 1100): 	at java.lang.Thread.run(Thread.java:841)

```
