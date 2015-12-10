#### Test 506502784dae475_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
I/dalvikvm( 1284): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1284): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 1284): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 1284): VFY: unable to resolve new-instance 2320 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
D/dalvikvm( 1284): VFY: replacing opcode 0x22 at 0x001a
I/dalvikvm( 1284): Failed resolving Lcom/google/android/gms/common/permission/PermissionUtils$1; interface 96 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
W/dalvikvm( 1284): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
D/dalvikvm( 1284): DexOpt: unable to opt direct call 0x3207 at 0x1c in Lcom/google/android/gms/chimera/GmsModuleInitializer;.initializeModuleV0
D/dalvikvm( 2447): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42915890
D/dalvikvm( 2447): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42915890
D/dalvikvm( 2447): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42915890
D/dalvikvm( 2447): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42915890
D/dalvikvm( 2447): GC_CONCURRENT freed 461K, 3% free 18007K/18500K, paused 1ms+1ms, total 18ms
D/dalvikvm( 2447): WAIT_FOR_CONCURRENT_GC blocked 1ms
D/ChimeraCfgMgr( 1284): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1284): Module APK com.google.android.play.games already loaded
I/ProviderInstaller( 2447): Installed default security provider GmsCore_OpenSSL
D/ChimeraCfgMgr( 1284): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/AsyncTaskServiceImpl( 1284): Submit a task: k
D/ChimeraCfgMgr( 1284): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 1284): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 1284): Processing package: com.test.thalitest
D/GassUtils( 1284): Found app info for package com.test.thalitest:18. Hash: 01e4d8ac61718f1dcdc950940ea39ae21caf015e512d4d8080feb7f016346367
D/k       ( 1284): Found info for package com.test.thalitest in db.
D/dalvikvm( 1284): GC_CONCURRENT freed 498K, 3% free 18628K/19156K, paused 2ms+2ms, total 26ms
--------- beginning of /dev/log/system
I/ActivityManager(  757): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2504 uid=10065 gids={50065, 3003, 1028, 1015}
W/BaseAppContext( 1284): Using Auth Proxy for data requests.
W/BaseAppContext( 1284): Using Auth Proxy for data requests.
W/BaseAppContext( 1284): Using Auth Proxy for data requests.
W/BaseAppContext( 1284): Using Auth Proxy for data requests.
W/BaseAppContext( 1284): Using Auth Proxy for data requests.
W/BaseAppContext( 1284): Using Auth Proxy for data requests.
W/dalvikvm( 1284): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1284): Could not find method android.app.Activity.setEnterSharedElementCallback, referenced from method android.support.v4.app.w.setEnterSharedElementCallback
W/dalvikvm( 1284): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1284): VFY: replacing opcode 0x6e at 0x000e
W/dalvikvm( 1284): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
I/dalvikvm( 1284): Could not find method android.app.Activity.setExitSharedElementCallback, referenced from method android.support.v4.app.w.setExitSharedElementCallback
W/dalvikvm( 1284): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
D/dalvikvm( 1284): VFY: replacing opcode 0x6e at 0x000e
I/dalvikvm( 1284): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.w.supportFinishAfterTransition
W/dalvikvm( 1284): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1284): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1284): Could not find method android.app.Activity.postponeEnterTransition, referenced from method android.support.v4.app.w.supportPostponeEnterTransition
W/dalvikvm( 1284): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
D/dalvikvm( 1284): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 1284): Could not find method android.app.Activity.startPostponedEnterTransition, referenced from method android.support.v4.app.w.supportStartPostponedEnterTransition
W/dalvikvm( 1284): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
D/dalvikvm( 1284): VFY: replacing opcode 0x6e at 0x0006
I/PeopleDatabaseHelper( 1284): cleanUpNonGplusAccounts done.
W/Quickoffice( 2504): Cleanup of storage: done
D/com.google.android.apps.docs.quickoffice.X( 2504): Loading recent documents list
D/Quickoffice( 2504): The number of lines present in  /proc/mount 21
D/Quickoffice( 2504): Parsing the storagedefinition.xml.
D/Quickoffice( 2504): # of Storagedefinitions - 35
D/Quickoffice( 2504): The # of storage definitions available - 35
D/Quickoffice( 2504): Processing mountline rootfs / rootfs ro,relatime 0 0
D/Quickoffice( 2504): Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
D/Quickoffice( 2504): Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
D/Quickoffice( 2504): Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
D/Quickoffice( 2504): Processing mountline proc /proc proc rw,relatime 0 0
D/Quickoffice( 2504): Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
D/Quickoffice( 2504): Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
D/Quickoffice( 2504): Processing mountline debugfs /sys/kernel/debug debugfs rw,relatime 0 0
D/Quickoffice( 2504): Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
D/Quickoffice( 2504): Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
D/Quickoffice( 2504): Processing mountline tmpfs /mnt/asec tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2504): Processing mountline tmpfs /mnt/obb tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2504): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,nosuid,nodev,relatime,data=ordered 0 0
D/Quickoffice( 2504): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2504): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2504): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2504): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
D/Quickoffice( 2504): Processing mountline /dev/fuse /mnt/shell/emulated fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2504): Processing mountline tmpfs /storage/emulated tmpfs rw,seclabel,nosuid,nodev,relatime,mode=751,gid=1028 0 0
D/Quickoffice( 2504): Processing mountline /dev/fuse /storage/emulated/0 fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2504): Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2504): Build properties are not configured for this storage definition.
D/Quickoffice( 2504): Adding the mount informaiton for listing in file manager MountedDeviceInformation [device=/dev/fuse, mountPath=/storage/emulated/legacy, fileSystemType=fuse, options=rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other, bootPriority1=0, bootPriority2=0, storageInfo=StorageDefinition [id=2010, matchPatterns=[/storage/emulated/legacy, fuse], skipPatterns=[obb], buildPatterns=[], type=INTERNAL, resourceString=2131231627, resourceStringItemized=2131231630, resourceIcon=2130838373, enabled=true], userFriendlyName=null]
D/Quickoffice( 2504): The # of mounts identified -  1
D/dalvikvm( 1284): GC_CONCURRENT freed 360K, 2% free 18876K/19244K, paused 3ms+3ms, total 32ms
D/dalvikvm( 2504): GC_CONCURRENT freed 177K, 2% free 16922K/17128K, paused 2ms+2ms, total 14ms
D/com.google.android.apps.docs.quickoffice.X( 2504): Checking validity of 0 items
D/ContentResolverUtil( 2504): There are 0 persisted uri permissions.
D/com.google.android.apps.docs.quickoffice.X( 2504): 0 items were valid
W/ActivityManager(  757): No permission grants found for com.quickoffice.android
D/AndroidRuntime( 2522): 
D/AndroidRuntime( 2522): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2522): CheckJNI is OFF
D/dalvikvm( 2522): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2522): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2522): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2522): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2522): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/ConnectivityService(  757): Sampling interval elapsed, updating statistics ..
I/ActivityManager(  757): Killing 1956:com.google.android.apps.maps/u0a57 (adj 15): empty #17
W/Quickoffice( 2504): Could not load clipboard.
D/ConnectivityService(  757): Done.
D/ConnectivityService(  757): Setting timer for 720seconds
W/Quickoffice( 2504): Could not store clipboard.
D/dalvikvm( 2522): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/ChimeraCfgMgr( 1284): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1284): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 2522): Calling main entry com.android.commands.am.Am
I/ActivityManager(  757): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2522
D/PermissionCache(  187): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (101 us)
I/Icing   ( 1284): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
D/AndroidRuntime( 2522): Shutting down VM
D/dalvikvm( 2522): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 0ms+0ms, total 2ms
I/ActivityManager(  757): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2548 uid=10108 gids={50108, 3003, 3001, 3002, 1028, 1015}
I/SearchController( 1167): #onHotwordDetectorStopped(false)
I/MicrophoneInputStream( 1167): mic_close
I/ActivityManager(  757): Killing 1983:com.google.android.youtube/u0a71 (adj 15): empty #17
I/MicroHotwordRecognitionRunner( 1167): Hotword detection finished
I/MicroHotwordRecognitionRunner( 1167): Stopping hotword detection.
V/WebViewChromiumFactoryProvider( 2548): Binding Chromium to main looper Looper (main, tid 1) {42795bb0}
I/LibraryLoader( 2548): Expected native library version number "",actual native library version number ""
I/chromium( 2548): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2548): Initializing chromium process, renderers=0
F/ActivityManager(  757): Service ServiceRecord{42fc8638 u0 com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService} in process ProcessRecord{42d98010 1983:com.google.android.youtube/u0a71} not same as in map: null
D/BluetoothManagerService(  757): Message: 20
D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@445011d0:true
D/BluetoothAdapter( 2548): 1115337456: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 2548): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
I/Icing   ( 1284): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
W/chromium( 2548): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 2548): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2548): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2548): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2548): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2548): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 2548): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 2548): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2548): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2548): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2548): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2548): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 2548): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2548): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2548): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2548): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2548): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2548): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2548): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 2548): CordovaWebView is running on device made by: LGE
,D/OpenGLRenderer( 2548): Enabling debug mode 0
,W/AwContents( 2548): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  757): Displayed com.test.thalitest/.MainActivity: +293ms
,D/JsMessageQueue( 2548): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 2548): GC_CONCURRENT freed 253K, 2% free 16906K/17192K, paused 3ms+2ms, total 19ms
,I/Icing   ( 1284): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
,D/dalvikvm( 1284): GC_CONCURRENT freed 525K, 3% free 18969K/19528K, paused 11ms+1ms, total 29ms
,D/dalvikvm( 2548): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x4279a1d0
,D/dalvikvm( 2548): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x4279a1d0
,D/jxcore_app_log( 2548): JniHelper::setJavaVM(0x41736ed0), pthread_self() = 1982635160
,D/JX-Cordova( 2548): jxcore cordova android initializing
,I/dalvikvm( 2548): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
,W/dalvikvm( 2548): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 2548): VFY: replacing opcode 0x6e at 0x0045
,I/Icing   ( 1284): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,I/ActivityManager(  757): Killing 1688:com.google.android.deskclock/u0a33 (adj 15): empty #17
,D/dalvikvm( 2548): GC_CONCURRENT freed 206K, 2% free 17194K/17432K, paused 1ms+2ms, total 11ms
,D/dalvikvm( 2548): GC_CONCURRENT freed 159K, 2% free 17536K/17736K, paused 1ms+1ms, total 11ms
,D/dalvikvm( 2548): WAIT_FOR_CONCURRENT_GC blocked 3ms
,D/dalvikvm( 2548): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 2548): GC_CONCURRENT freed 157K, 2% free 17881K/18080K, paused 1ms+2ms, total 13ms
D/dalvikvm( 2548): WAIT_FOR_CONCURRENT_GC blocked 7ms
,D/dalvikvm( 2548): WAIT_FOR_CONCURRENT_GC blocked 3ms
,D/dalvikvm( 2548): GC_CONCURRENT freed 154K, 2% free 18225K/18424K, paused 1ms+1ms, total 13ms
,D/dalvikvm( 2548): WAIT_FOR_CONCURRENT_GC blocked 2ms
,D/dalvikvm( 2548): WAIT_FOR_CONCURRENT_GC blocked 5ms
,D/dalvikvm( 2548): GC_CONCURRENT freed 159K, 2% free 18561K/18768K, paused 1ms+1ms, total 15ms
,D/dalvikvm( 2548): WAIT_FOR_CONCURRENT_GC blocked 3ms
,D/dalvikvm( 2548): WAIT_FOR_CONCURRENT_GC blocked 7ms
,D/dalvikvm( 2548): GC_CONCURRENT freed 182K, 2% free 18981K/19216K, paused 1ms+2ms, total 17ms
,D/dalvikvm( 2548): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 2548): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 2548): GC_CONCURRENT freed 224K, 2% free 19493K/19776K, paused 1ms+3ms, total 25ms
D/dalvikvm( 2548): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 2548): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 2548): GC_CONCURRENT freed 284K, 2% free 20109K/20456K, paused 3ms+1ms, total 22ms
D/dalvikvm( 2548): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 2548): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 2548): GC_CONCURRENT freed 334K, 2% free 20874K/21280K, paused 1ms+1ms, total 27ms
,D/dalvikvm( 2548): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/dalvikvm( 2548): WAIT_FOR_CONCURRENT_GC blocked 7ms
,D/dalvikvm( 2548): GC_CONCURRENT freed 408K, 3% free 21812K/22300K, paused 2ms+1ms, total 22ms
,D/dalvikvm( 2548): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 2548): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 2548): GC_CONCURRENT freed 1203K, 6% free 22278K/23548K, paused 2ms+2ms, total 27ms
D/dalvikvm( 2548): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 2548): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 2548): GC_CONCURRENT freed 1504K, 7% free 22552K/24172K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 2548): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 2548): GC_FOR_ALLOC freed 46K, 7% free 22515K/24172K, paused 21ms, total 22ms
,I/dalvikvm-heap( 2548): Grow heap (frag case) to 22.708MB for 728606-byte allocation
,D/dalvikvm( 2548): GC_FOR_ALLOC freed 494K, 9% free 22732K/24884K, paused 23ms, total 23ms
,D/dalvikvm( 2548): GC_FOR_ALLOC freed 784K, 9% free 22773K/24884K, paused 23ms, total 23ms
,I/dalvikvm-heap( 2548): Grow heap (frag case) to 23.307MB for 1092904-byte allocation
,D/dalvikvm( 2548): GC_FOR_ALLOC freed 0K, 9% free 23840K/25952K, paused 21ms, total 21ms
,D/dalvikvm( 2548): GC_FOR_ALLOC freed 1956K, 11% free 23179K/25952K, paused 22ms, total 22ms
,I/dalvikvm-heap( 2548): Grow heap (frag case) to 24.225MB for 1639352-byte allocation
,D/dalvikvm( 2548): GC_FOR_ALLOC freed 1070K, 14% free 23709K/27556K, paused 21ms, total 21ms
,D/dalvikvm( 2548): GC_FOR_ALLOC freed 1980K, 14% free 23810K/27556K, paused 25ms, total 25ms
,I/dalvikvm-heap( 2548): Grow heap (frag case) to 25.624MB for 2459024-byte allocation
,D/dalvikvm( 2548): GC_CONCURRENT freed 1624K, 18% free 24587K/29960K, paused 5ms+1ms, total 26ms
D/dalvikvm( 2548): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 2548): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 2548): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 2548): GC_CONCURRENT freed 2547K, 18% free 24673K/29960K, paused 2ms+4ms, total 32ms
,D/dalvikvm( 2548): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 2548): GC_FOR_ALLOC freed 677K, 19% free 24529K/29960K, paused 22ms, total 22ms
,I/dalvikvm-heap( 2548): Grow heap (frag case) to 27.498MB for 3688532-byte allocation
,D/dalvikvm( 2548): GC_FOR_ALLOC freed <1K, 17% free 28130K/33564K, paused 21ms, total 21ms
,D/dalvikvm( 2548): GC_CONCURRENT freed 2623K, 24% free 25824K/33564K, paused 4ms+3ms, total 48ms
,D/dalvikvm( 2548): GC_FOR_ALLOC freed 735K, 24% free 25664K/33564K, paused 20ms, total 20ms
,W/jxcore-log( 2548): Initializing JXcore engine
,W/jxcore-log( 2548): JXcore engine is ready
,D/dalvikvm( 2548): GC_CONCURRENT freed 5418K, 31% free 23222K/33564K, paused 2ms+1ms, total 21ms
,D/dalvikvm( 2548): WAIT_FOR_CONCURRENT_GC blocked 17ms
,W/jxcore-log( 2548): Starting JXcore engine
,W/jxcore-log( 2548): Platform android
W/jxcore-log( 2548): 
,W/jxcore-log( 2548): Process ARCH arm
W/jxcore-log( 2548): 
,I/jxcore-log( 2548): JXcore Cordova bridge is ready!
I/jxcore-log( 2548): 
W/jxcore-log( 2548): JXcore engine is started
I/chromium( 2548): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Choreographer( 2548): Skipped 158 frames!  The application may be doing too much work on its main thread.
I/jxcore-log( 2548): Toggling radios to true
I/jxcore-log( 2548): 
D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  757): enable():  mBluetooth =null mBinding = false
D/BluetoothManagerService(  757): Message: 1
D/BluetoothManagerService(  757): MESSAGE_ENABLE: mBluetooth = null
I/ActivityManager(  757): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=2610 uid=1002 gids={41002, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008}
D/WifiService(  757): setWifiEnabled: true pid=2548, uid=10108
D/SoftapController(  184): Softap fwReload - Ok
I/jxcore-log( 2548): Radios toggled
I/jxcore-log( 2548): 
D/CommandListener(  184): Setting iface cfg
D/CommandListener(  184): Trying to bring down wlan0
D/WifiMonitor(  757): startMonitoring(wlan0) with mConnected = false
I/ActivityManager(  757): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=2625 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
I/wpa_supplicant( 2624): Successfully initialized wpa_supplicant
D/AdapterServiceConfig( 2610): Adding HeadsetService
D/AdapterServiceConfig( 2610): Adding A2dpService
D/AdapterServiceConfig( 2610): Adding HidService
D/AdapterServiceConfig( 2610): Adding HealthService
I/wpa_supplicant( 2624): rfkill: Cannot open RFKILL control device
D/AdapterServiceConfig( 2610): Adding PanService
D/AdapterServiceConfig( 2610): Adding GattService
D/AdapterServiceConfig( 2610): Adding BluetoothMapService
D/BluetoothAdapterService( 2610): REFCOUNT: CREATED. INSTANCE_COUNT1
D/BluetoothManagerService(  757): Message: 20
D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@441b2b58:true
D/BluetoothAdapterState( 2610): make
I/bluedroid( 2610): init
I/BluetoothAdapterState( 2610): Entering OffState
I/bte_conf( 2610): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bluedroid( 2610): get_profile_interface socket
I/GKI_LINUX( 2610): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
I/BluetoothAdapterProperties( 2610): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 2610): Address is:34:FC:EF:11:B1:66
I/BluetoothAdapterProperties( 2610): adapterPropertyChangedCallback with type:1 len:7
D/BluetoothManagerService(  757): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  757): Stored Bluetooth name: Nexus 5
D/BluetoothManagerService(  757): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  757): Message: 40
D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bluedroid( 2610): config_hci_snoop_log
D/BluetoothManagerService(  757): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  757): Broadcasting onBluetoothServiceUp() to 7 receivers.
D/BluetoothAdapterProperties( 2610): Name is: Nexus 5
D/BluetoothAdapterState( 2610): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 2610): Setting state to 11
I/BluetoothAdapterState( 2610): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 2610): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  757): Message: 60
D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothBondStateMachine( 2610): make
D/BluetoothManagerService(  757): Bluetooth State Change Intent: 10 -> 11
I/BluetoothBondStateMachine( 2610): StableState(): Entering Off State
D/BluetoothHeadset(  757): Proxy object connected
D/BluetoothHeadset(  996): Proxy object connected
D/BluetoothHeadset(  996): Proxy object connected
D/BluetoothHeadset(  996): Proxy object connected
D/HeadsetService( 2610): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 2610): classInitNative: succeeds
D/HeadsetStateMachine( 2610): make
I/bluedroid( 2610): get_profile_interface handsfree
I/BluetoothAdapterState( 2610): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/BluetoothA2dp(  757): Proxy object connected
D/A2dpService( 2610): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 2610): classInitNative: succeeds
V/Avrcp   ( 2610): make
I/bluedroid( 2610): get_profile_interface avrcp
I/BluetoothA2dpServiceJni( 2610): classInitNative: succeeds
D/A2dpStateMachine( 2610): make
I/bluedroid( 2610): get_profile_interface a2dp
I/GKI_LINUX( 2610): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
D/BluetoothManagerService(  757): Message: 20
D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4413d2c8:true
D/A2dpStateMachine( 2610): Enter Disconnected: -2
I/BluetoothHidServiceJni( 2610): classInitNative: succeeds
D/HidService( 2610): Received start request. Starting profile...
I/bluedroid( 2610): get_profile_interface hidhost
I/BluetoothHealthServiceJni( 2610): classInitNative: succeeds
D/HealthService( 2610): Received start request. Starting profile...
I/bluedroid( 2610): get_profile_interface health
I/BluetoothPanServiceJni( 2610): classInitNative(L105): succeeds
D/BluetoothPan(  757): BluetoothPAN Proxy object connected
D/PanService( 2610): Received start request. Starting profile...
D/BluetoothPanServiceJni( 2610): initializeNative(L110): pan
I/bluedroid( 2610): get_profile_interface pan
D/BluetoothManagerService(  757): Message: 30
D/BluetoothTethering(  757): got CMD_CHANNEL_HALF_CONNECTED
I/BtGatt.JNI( 2610): classInitNative(L684): classInitNative: Success!
D/BtGatt.DebugUtils( 2610): handleDebugAction() action=null
D/BtGatt.GattService( 2610): Received start request. Starting profile...
D/BtGatt.GattService( 2610): start()
I/bluedroid( 2610): get_profile_interface gatt
D/BluetoothManagerService(  757): Message: 30
D/LocalBluetoothProfileManager( 2625): Adding local MAP profile
D/BluetoothMap( 2625): Create BluetoothMap proxy object
D/BluetoothManagerService(  757): Message: 30
D/BluetoothMapService( 2610): Received start request. Starting profile...
D/BluetoothMapService( 2610): start()
D/BluetoothAdapterService( 2610): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 2610): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 2610): Profile still not running:com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 2610): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2610): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/HeadsetPhoneState( 2610): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
W/ContextImpl( 2625): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1367 
W/ContextImpl( 2625): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1370 
W/ContextImpl( 2625): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1376 
D/BluetoothAdapterService( 2610): Profile still not running:com.android.bluetooth.map.BluetoothMapService
D/BluetoothManagerService(  757): Message: 30
D/BluetoothAdapterState( 2610): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 2610): enable
D/LocalBluetoothProfileManager( 2625): LocalBluetoothProfileManager construction complete
I/bt_hci_bdroid( 2610): init
I/bt_vendor( 2610): init
I/bt_vnd_conf( 2610): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 2610): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
I/bt_hci_bdroid( 2610): bt_hc_worker_thread started
W/ContextImpl( 2625): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
D/BluetoothPan( 2625): BluetoothPAN Proxy object connected
D/PanProfile( 2625): Bluetooth service connected
D/BluetoothInputDevice( 2625): Proxy object connected
D/HidProfile( 2625): Bluetooth service connected
D/BluetoothMap( 2625): Proxy object connected
D/MapProfile( 2625): Bluetooth service connected
D/BluetoothMap( 2625): getConnectedDevices()
D/BluetoothMap( 2625): Bluetooth is Not enabled
I/ActivityManager(  757): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=2662 uid=10052 gids={50052, 3003, 1028, 1015}
I/ActivityManager(  757): Killing 1872:com.google.android.email/u0a36 (adj 15): empty #17
I/bt_userial_vendor( 2610): userial vendor open: opening /dev/ttyHS99
I/GKI_LINUX( 2610): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 2610): btu_task pending for preload complete event
I/bt_userial_vendor( 2610): device fd = 65 open
D/dalvikvm(  757): GC_EXPLICIT freed 22562K, 54% free 26502K/56432K, paused 2ms+5ms, total 94ms
I/bt_hwcfg( 2610): bt vendor lib: set UART baud 4000000
D/bt_hwcfg( 2610): Chipset BCM4335C0
D/bt_hwcfg( 2610): Target name = [BCM4335C0]
I/bt_hwcfg( 2610): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,D/dalvikvm( 2662): GC_CONCURRENT freed 202K, 2% free 16926K/17160K, paused 2ms+2ms, total 20ms
,D/AuthorizationBluetoothService( 1123): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/BroadcastQueue(  757): Permission Denial: receiving Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 (has extras) } to com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver requires android.permission.BLUETOOTH due to sender android (uid 1000)
I/ActivityManager(  757): Killing 2076:com.google.android.music:main/u0a58 (adj 15): empty #17
,F/ActivityManager(  757): Service ServiceRecord{42e017b8 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{42e40b48 2076:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  757): Service ServiceRecord{42e00e58 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{42e40b48 2076:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  757): Service ServiceRecord{42db8778 u0 com.google.android.music/.download.artwork.ArtDownloadService} in process ProcessRecord{42e40b48 2076:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  757): Service ServiceRecord{42d93c98 u0 com.google.android.music/.download.ArtDownloadQueueService} in process ProcessRecord{42e40b48 2076:com.google.android.music:main/u0a58} not same as in map: null
,F/ActivityManager(  757): Service ServiceRecord{42d6a068 u0 com.google.android.music/.download.cache.ArtCacheService} in process ProcessRecord{42e40b48 2076:com.google.android.music:main/u0a58} not same as in map: null
,I/bt_hwcfg( 2610): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 2610): Settlement delay -- 100 ms
,I/bt_hwcfg( 2610): bt vendor lib: set UART baud 4000000
,I/bt_hwcfg( 2610): Setting local bd addr to 34:FC:EF:11:B1:66
,I/bt_hwcfg( 2610): vendor lib fwcfg completed
,I/bt-btu  ( 2610): btu_task received preload complete event
,I/        ( 2610): BTE_InitTraceLevels -- TRC_HCI
I/        ( 2610): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 2610): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 2610): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 2610): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 2610): BTE_InitTraceLevels -- TRC_A2D
,I/        ( 2610): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 2610): BTE_InitTraceLevels -- TRC_BTM
I/        ( 2610): BTE_InitTraceLevels -- TRC_GAP
I/        ( 2610): BTE_InitTraceLevels -- TRC_PAN
I/        ( 2610): BTE_InitTraceLevels -- TRC_SDP
I/        ( 2610): BTE_InitTraceLevels -- TRC_GATT
,I/        ( 2610): BTE_InitTraceLevels -- TRC_SMP
I/        ( 2610): BTE_InitTraceLevels -- TRC_BTAPP
,I/        ( 2610): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 2610): BTM_SecRegister:p_cb_info->p_le_callback == 0x75075f8d 
,E/bt-btm  ( 2610): BTM_SecRegister: btm_cb.api.p_le_callback = 0x75075f8d 
,E/bt-btif ( 2610): Calling BTA_HhEnable
E/bt-btif ( 2610): btif_storage_get_adapter_property service_mask:0x140040
I/BluetoothAdapterProperties( 2610): adapterPropertyChangedCallback with type:2 len:6
D/BluetoothAdapterProperties( 2610): Address is:34:FC:EF:11:B1:66
,I/BluetoothAdapterProperties( 2610): adapterPropertyChangedCallback with type:1 len:7
D/BluetoothAdapterProperties( 2610): Name is: Nexus 5
,I/BluetoothAdapterProperties( 2610): adapterPropertyChangedCallback with type:7 len:4
,D/BluetoothAdapterProperties( 2610): Scan Mode:20
I/BluetoothAdapterProperties( 2610): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 2610): Discoverable Timeout:120
,I/BluetoothAdapterProperties( 2610): adapterPropertyChangedCallback with type:8 len:36
,D/BluetoothAdapterProperties( 2610): Adding bonded device:F4:F1:E1:5C:3B:E2
,D/BluetoothAdapterProperties( 2610): Adding bonded device:F8:95:C7:87:85:54
,D/BluetoothAdapterProperties( 2610): Adding bonded device:E0:DB:10:1F:C9:5E
,D/BluetoothAdapterProperties( 2610): Adding bonded device:08:EC:A9:50:76:27
,D/BluetoothAdapterProperties( 2610): Adding bonded device:F8:95:C7:87:3C:51
,D/BluetoothAdapterProperties( 2610): Adding bonded device:58:2A:F7:ED:96:BE
D/BluetoothManagerService(  757): Bluetooth Adapter name changed to Nexus 5
,D/BluetoothManagerService(  757): Stored Bluetooth name: Nexus 5
,I/BluetoothAdapterProperties( 2610): adapterPropertyChangedCallback with type:3 len:48
,E/BluetoothRemoteDevices( 2610): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,E/BluetoothRemoteDevices( 2610): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
E/BluetoothRemoteDevices( 2610): devicePropertyChangedCallback: bdDevice: E0:DB:10:1F:C9:5E, value is empty for type: 10
E/BluetoothRemoteDevices( 2610): devicePropertyChangedCallback: bdDevice: 08:EC:A9:50:76:27, value is empty for type: 10
,E/BluetoothRemoteDevices( 2610): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
,E/BluetoothRemoteDevices( 2610): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,I/bt_hwcfg( 2610): SCO PCM configure {0, 4, 0, 0, 0}
I/bte_conf( 2610): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 2610): [1] primary_record=1 vendor_id=0x000F vendor_id_source=0x0001 product_id=0x1200 version=0x1436
I/bte_conf( 2610): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 2610): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,D/BluetoothPanServiceJni( 2610): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
D/BluetoothAdapterState( 2610): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 2610): ScanMode =  20
D/BluetoothAdapterProperties( 2610): State =  11
,D/BluetoothAdapterProperties( 2610): Setting state to 12
I/BluetoothAdapterState( 2610): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 2610): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  757): Message: 60
D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  757): Broadcasting onBluetoothStateChange(true) to 10 receivers.
D/BluetoothPan(  757): onBluetoothStateChange(on) call bindService
I/BluetoothAdapterProperties( 2610): adapterPropertyChangedCallback with type:7 len:4
I/BluetoothAdapterState( 2610): Entering On State
D/BluetoothAdapterService(1115318688)( 2610): Get Bonded Devices being called
D/BluetoothAdapterProperties( 2610): Scan Mode:21
I/BluetoothAdapterProperties( 2610): adapterPropertyChangedCallback with type:9 len:4
D/BluetoothAdapterProperties( 2610): Discoverable Timeout:120
,W/ContextImpl(  757): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:192 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:484 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1129 
D/BluetoothA2dp(  757): onBluetoothStateChange: up=true
D/BluetoothHeadset(  757): onBluetoothStateChange: up=true
D/BluetoothHeadset(  996): onBluetoothStateChange: up=true
D/BluetoothHeadset(  996): onBluetoothStateChange: up=true
D/BluetoothHeadset(  996): onBluetoothStateChange: up=true
,D/BluetoothPbap( 2625): onBluetoothStateChange: up=true
,D/BluetoothMap( 2625): onBluetoothStateChange: up=true
,D/BluetoothPan( 2625): onBluetoothStateChange(on) call bindService
,D/BluetoothInputDevice( 2625): onBluetoothStateChange: up=true
,D/BluetoothAdapterProperties( 2610): getBondedDevices: length=6
W/ContextImpl( 2625): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap$1.onBluetoothStateChange:132 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,W/ContextImpl( 2625): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:192 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
D/BluetoothManagerService(  757): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  757): Bluetooth State Change Intent: 11 -> 12
D/BluetoothAdapterService(1115318688)( 2610): Get Bonded Devices being called
D/BluetoothAdapterProperties( 2610): getBondedDevices: length=6
,E/bt_h4   ( 2610): vendor lib postload completed
,D/BluetoothManagerService(  757): Message: 40
,D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapService( 2610): onReceive
,D/BluetoothMapService( 2610): STATE_ON
,D/BluetoothMapService( 2610): Map Service startRfcommSocketListener
,D/BluetoothAdapterService(1115318688)( 2610): Get Bonded Devices being called
D/BluetoothAdapterProperties( 2610): getBondedDevices: length=6
,D/Tethering(  757): sendTetherStateChangedBroadcast 1, 0, 0
,D/dalvikvm( 2610): GC_CONCURRENT freed 253K, 2% free 16832K/17116K, paused 6ms+1ms, total 22ms
,D/BluetoothMapService( 2610): Map Service initSocket
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2610): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 2610): SOCK FLAG = 1 ***********************
,D/BluetoothMapService( 2610): Accepting socket connection...
,D/LocalBluetoothProfileManager( 2625): Adding local A2DP profile
,D/BluetoothManagerService(  757): Message: 30
,D/LocalBluetoothProfileManager( 2625): Adding local HEADSET profile
,W/ContextImpl( 2625): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1364 
,D/BluetoothManagerService(  757): Message: 30
,D/BluetoothAdapterService(1115318688)( 2610): Get Bonded Devices being called
,D/BluetoothAdapterProperties( 2610): getBondedDevices: length=6
W/ContextImpl( 2625): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1551 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1361 
,D/BluetoothMap( 2625): getConnectedDevices()
,D/BluetoothMap( 2625): getConnectionState(58:2A:F7:ED:96:BE)
,D/MapProfile( 2625): getConnectionStatus: status is: 0
,I/wpa_supplicant( 2624): rfkill: Cannot open RFKILL control device
,D/dalvikvm( 2625): GC_CONCURRENT freed 264K, 2% free 16826K/17128K, paused 3ms+0ms, total 13ms
,D/BluetoothMap( 2625): getConnectedDevices()
,D/BluetoothMap( 2625): getConnectionState(F8:95:C7:87:3C:51)
,D/MapProfile( 2625): getConnectionStatus: status is: 0
,D/BluetoothMap( 2625): getConnectedDevices()
,D/BluetoothMap( 2625): getConnectionState(E0:DB:10:1F:C9:5E)
,D/MapProfile( 2625): getConnectionStatus: status is: 0
,D/BluetoothMap( 2625): getConnectedDevices()
,D/BluetoothMap( 2625): getConnectionState(F8:95:C7:87:85:54)
,D/MapProfile( 2625): getConnectionStatus: status is: 0
,D/BluetoothMap( 2625): getConnectedDevices()
,D/BluetoothMap( 2625): getConnectionState(F4:F1:E1:5C:3B:E2)
,D/MapProfile( 2625): getConnectionStatus: status is: 0
,D/BluetoothMap( 2625): getConnectedDevices()
,D/BluetoothMap( 2625): getConnectionState(08:EC:A9:50:76:27)
,D/MapProfile( 2625): getConnectionStatus: status is: 0
,D/BluetoothA2dp( 2625): Proxy object connected
,D/A2dpProfile( 2625): Bluetooth service connected
,W/ContextImpl( 2625): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/BluetoothHeadset( 2625): Proxy object connected
D/HeadsetProfile( 2625): Bluetooth service connected
D/DockEventReceiver( 2625): finishStartingService: stopping service
D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 2610): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 2610): SOCK FLAG = 1 ***********************
,D/BluetoothPbap( 2625): Proxy object connected
,D/PbapServerProfile( 2625): Bluetooth service connected
,D/WifiConfigStore(  757): Loading config and enabling all networks
,D/AuthorizationBluetoothService( 1123): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1123): Proximity feature is not enabled.
,W/BroadcastQueue(  757): Permission Denial: receiving Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 (has extras) } to com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver requires android.permission.BLUETOOTH due to sender android (uid 1000)
W/Settings( 1910): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 2610): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 2610): SOCK FLAG = 0 ***********************
I/BtOppRfcommListener( 2610): Accept thread started.
D/CommandListener(  184): Setting iface cfg
D/CommandListener(  184): Trying to bring up p2p0
D/WifiMonitor(  757): startMonitoring(p2p0) with mConnected = true
,I/wpa_supplicant( 2624): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant( 2624): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 2624): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 2624): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  757): scanCount==0 - aborting
,D/WifiStateMachine(  757): VerifyingLinkState enter
D/WifiStateMachine(  757): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  757): CaptivePortalCheckState enter
D/ConnectivityService(  757): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  757): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  757): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  757): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  757): Unexpected mtu value: android.net.wifi.WifiStateTracker@42cf9fc8
,D/Nat464Xlat(  757): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  757): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  757):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  757): requiresClat: netType=1, hasIPv4Address=true
,I/jxcore-log( 2548): Test app app.js loaded
I/jxcore-log( 2548): 
,I/Choreographer( 2548): Skipped 382 frames!  The application may be doing too much work on its main thread.
,I/chromium( 2548): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/dalvikvm( 1167): GC_CONCURRENT freed 912K, 6% free 17812K/18764K, paused 2ms+2ms, total 21ms
,D/Tethering(  757): MasterInitialState.processMessage what=3
,W/        (  757): Unable to set rtc to 1449751009: Invalid argument
,D/        (  757): Setting time of day to sec=1449751009
,D/CaptivePortalTracker(  757): NoActiveNetworkState{ when=-11ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/iu.SyncManager( 1284): SYNC; picasa accounts
,D/NetworkLogImpl( 1284): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1284): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1284): num queued entries: 0
,I/iu.UploadsManager( 1284): num updated entries: 0
,I/iu.SyncManager( 1284): NEXT; no task
,I/ActivityManager(  757): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=2805 uid=10031 gids={50031, 3003, 1028, 1015}
,D/GpsLocationProvider(  757): NTP server returned: 1449751006733 (Thu Dec 10 13:36:46 CET 2015) reference: 86600 certainty: 9 system time offset: -3102
E/ActivityThread( 1284): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  757): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 20750, reason: UserStart, SyncResult: databaseError: true stats []
,I/dalvikvm( 1284): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1284): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1284): VFY: replacing opcode 0x6e at 0x003d
,D/SyncManager(  757): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 89713, reason: UserStart
,I/Babel   ( 1910): connection state changed from UNKNOWN to CONNECTED
,E/Auth.Api.Credentials( 1284): [CredentialSyncAdapter] Unknown sync event.
,D/dalvikvm( 1284): GC_CONCURRENT freed 544K, 3% free 19058K/19644K, paused 3ms+2ms, total 19ms
,D/dalvikvm( 1123): GC_FOR_ALLOC freed 316K, 3% free 17985K/18500K, paused 12ms, total 12ms
,D/dalvikvm( 1123): GC_FOR_ALLOC freed <1K, 3% free 18001K/18520K, paused 12ms, total 12ms
,I/GCM     ( 1123): GCM config loaded
,D/dalvikvm( 2805): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,W/dalvikvm( 2805): VFY: unable to resolve instance field 68
D/dalvikvm( 2805): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 2805): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2805): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 2805): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 2805): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/dalvikvm( 1123): GC_FOR_ALLOC freed 120K, 4% free 17932K/18540K, paused 11ms, total 11ms
,D/dalvikvm( 2805): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 2805): VFY: unable to resolve instance field 68
,D/dalvikvm( 2805): VFY: replacing opcode 0x54 at 0x0011
D/dalvikvm( 2805): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2805): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 2805): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2805): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 2805): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 2805): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,I/ActivityManager(  757): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=2843 uid=10033 gids={50033, 1028}
,V/AlarmClock( 2843): AlarmInitReceiver android.intent.action.TIME_SET
,D/dalvikvm( 1655): GC_CONCURRENT freed 292K, 2% free 16793K/17116K, paused 3ms+1ms, total 13ms
,D/dalvikvm( 2240): GC_CONCURRENT freed 319K, 2% free 17466K/17812K, paused 2ms+12ms, total 32ms
,I/AlarmClock( 2843): Displaying next alarm time: ''
,V/AlarmClock( 2843): AlarmInitReceiver finished
,I/ActivityManager(  757): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=2862 uid=10068 gids={50068}
,I/ActivityManager(  757): Killing 1720:com.google.android.gm/u0a41 (adj 15): empty #17
,D/dalvikvm( 2862): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x4279fcf8, skipping init
D/TimeService( 2862): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449751010226
D/        ( 2862): TimeServiceNative: User Time to be set is 1449751010226
D/QC-time-services( 2862): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 2862): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 2862): Lib:time_genoff_operation: pargs->ts_val = 1449751010226
D/QC-time-services(  203): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 2862): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  203): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449751010226
D/QC-time-services(  203): Daemon:genoff_opr: Base = 2, val = 1449751010226, operation = 0
D/QC-time-services(  203): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS0/30/71 6:42:1
D/QC-time-services(  203): Daemon:Value read from RTC seconds = 34065721000
D/QC-time-services(  203): Daemon:new time 1449751010226 
D/QC-time-services(  203): Daemon: delta 1415685289226 genoff 1415685289226 
D/QC-time-services(  203): Daemon:genoff_persistent_update: Writing genoff = 1415685289226 to memory
D/QC-time-services(  203): Daemon:Opening File: /data/system/time/ats_2
,D/QC-time-services(  203): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  203): Updating the TOD offset
D/QC-time-services(  203): Daemon:genoff_persistent_update: Writing genoff = 1415685289226 to memory
D/QC-time-services(  203): Daemon:Opening File: /data/system/time/ats_1
,D/QC-time-services(  203): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  203): Daemon:Update to modem bit set
D/QC-time-services(  203): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  203): Daemon: Base = 2, Value being sent to MODEM = 1133786210226
,E/QC-time-services( 2862): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  203): Daemon: Time-services: Waiting to acceptconnection
,D/QC-time-services(  203): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/CheckinService( 1284): Checkin interval check for package: unspecified last checkin: 1449746249579 min interval config: 0 actual interval: 4760670
,I/ActivityManager(  757): Killing 1511:com.android.providers.calendar/u0a1 (adj 15): empty #17
,I/dalvikvm(  977): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm(  977): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm(  977): VFY: replacing opcode 0x6e at 0x003d
,V/GLSActivity( 1123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 2240): GC_CONCURRENT freed 273K, 2% free 17647K/17948K, paused 2ms+2ms, total 16ms
,D/dalvikvm(  757): GC_EXPLICIT freed 1576K, 53% free 26656K/56432K, paused 3ms+4ms, total 54ms
,W/dalvikvm( 1123): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 1123): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 1123): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/dalvikvm( 1123): VFY: replacing opcode 0x1f at 0x0011
I/dalvikvm( 1123): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 1123): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 1123): VFY: replacing opcode 0x6e at 0x003d
,D/dalvikvm(  977): GC_CONCURRENT freed 400K, 3% free 18743K/19244K, paused 3ms+2ms, total 19ms
,D/ConnectivityService(  757): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/dalvikvm( 1123): GC_CONCURRENT freed 375K, 3% free 18018K/18540K, paused 2ms+2ms, total 21ms
,D/dalvikvm( 2240): Trying to load lib /data/app-lib/com.google.android.apps.plus-2/libcronet.so 0x427a3858
,D/dalvikvm( 2240): Added shared lib /data/app-lib/com.google.android.apps.plus-2/libcronet.so 0x427a3858
,D/dalvikvm( 2240): GC_CONCURRENT freed 195K, 2% free 17878K/18104K, paused 3ms+2ms, total 14ms
,D/dalvikvm( 2240): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 2240): VFY: unable to resolve instance field 58
,D/dalvikvm( 2240): VFY: replacing opcode 0x54 at 0x000d
D/dalvikvm( 2240): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 2240): DexOpt: unable to optimize instance field ref 0x003a at 0x12 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 2240): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 2240): DexOpt: unable to optimize instance field ref 0x003a at 0x17 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/dalvikvm( 2240): GC_CONCURRENT freed 291K, 2% free 18030K/18352K, paused 3ms+2ms, total 14ms
,D/dalvikvm( 2240): DexOpt: couldn't find field Landroid/app/Notification;.color
,W/dalvikvm( 2240): VFY: unable to resolve instance field 2708
,D/dalvikvm( 2240): VFY: replacing opcode 0x59 at 0x008b
,D/dalvikvm( 2240): DexOpt: couldn't find field Landroid/app/Notification;.color
W/dalvikvm( 2240): VFY: unable to resolve instance field 2708
,D/dalvikvm( 2240): VFY: replacing opcode 0x59 at 0x00c7
,D/dalvikvm( 2240): GC_CONCURRENT freed 380K, 3% free 18042K/18452K, paused 1ms+2ms, total 26ms
,I/ActivityManager(  757): Killing 2387:com.android.defcontainer/u0a4 (adj 15): empty #17
,D/dalvikvm( 1123): GC_CONCURRENT freed 401K, 3% free 18075K/18540K, paused 4ms+3ms, total 39ms
,D/PerfProfileCollectorService( 1284): User is not opt-in to Usage & Diagnostics.
,D/PerfProfileCollectorService( 1284): removeStateFiles() called
,D/PerfProfileCollectorService( 1284): User is not opt-in to Usage & Diagnostics.
,D/dalvikvm( 1123): GC_CONCURRENT freed 468K, 3% free 18009K/18540K, paused 3ms+1ms, total 19ms
,I/VacuumService(  977): Vacuum at: now=1449751012767 tag=VacuumService
,D/dalvikvm( 1123): GC_CONCURRENT freed 396K, 3% free 18016K/18540K, paused 2ms+1ms, total 14ms
,D/dalvikvm( 1616): GC_CONCURRENT freed 441K, 3% free 17355K/17864K, paused 2ms+1ms, total 11ms
,D/dalvikvm( 1616): WAIT_FOR_CONCURRENT_GC blocked 3ms
,D/Finsky  ( 1616): [1] 5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  757): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=2971 uid=10001 gids={50001, 3003, 1028, 1015}
,I/CalendarProvider2( 2971): Created com.android.providers.calendar.CalendarAlarmManager@427b6370(com.android.providers.calendar.CalendarProvider2@427ae040)
,I/CalendarProvider2( 2971): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 2971): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlertReceiver( 1655): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.google.android.calendar/com.android.calendar.alerts.AlertReceiver }
,D/AlertService( 1655): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/CaptivePortalTracker(  757): DelayedCaptiveCheckState{ when=-6ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  757): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  757): Checking http://216.58.209.46/generate_204
W/ActivityThread(  757): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/CaptivePortalTracker(  757): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  757): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  757): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  757): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  757): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/AlertService( 1655): Beginning updateAlertNotification
,D/AlertService( 1655): No fired or scheduled alerts
,D/AlertService( 1655): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 1655): No events found starting within 1 week.
I/ActivityManager(  757): Killing 2142:android.process.acore/u0a3 (adj 15): empty #17
,I/PowerManagerService(  757): Going to sleep due to screen timeout...
,I/Adreno-EGL(  757): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/SurfaceFlinger(  187): Screen released, type=0 flinger=0xb881c450
,D/qdhwcomposer(  187): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  187): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  757): Excessive delay in blankDisplay() while turning screen off: 293ms
,V/KeyguardServiceDelegate(  757): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@4405efd8)
,V/KeyguardServiceDelegate(  757): **** SHOWN CALLED ****
I/WindowManager(  757): No lock screen! windowToken=null
,D/dalvikvm(  996): GC_CONCURRENT freed 335K, 3% free 17064K/17428K, paused 1ms+1ms, total 21ms
,D/NfcService( 1023): NFC-C OFF
,D/SyncManager(  757): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 20748, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  757): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, latestRunTime 149760, reason: UserStart
E/ActivityThread( 1284): Failed to find provider info for com.android.contacts.metadata
,I/PhenotypeConfigurator(  977): Scheduling Phenotype for one-off execution 5527 seconds from now (1449751094127)
,D/GetConfigurationSnapshotOperation(  977): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/dalvikvm(  977): GC_CONCURRENT freed 589K, 4% free 18755K/19440K, paused 3ms+2ms, total 20ms
,I/PhenotypeFlagCommitter(  977): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm(  977): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  977): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  977): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm(  977): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm(  977): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm(  977): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory(  977): Using platform SSLCertificateSocketFactory
,D/dalvikvm(  977): GC_CONCURRENT freed 535K, 4% free 18931K/19560K, paused 2ms+4ms, total 27ms
,D/dalvikvm(  977): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/dalvikvm(  977): GC_CONCURRENT freed 549K, 4% free 19051K/19696K, paused 3ms+2ms, total 20ms
,D/dalvikvm(  977): GC_CONCURRENT freed 614K, 4% free 19197K/19908K, paused 2ms+4ms, total 25ms
,D/dalvikvm(  977): GC_CONCURRENT freed 803K, 5% free 19215K/20112K, paused 1ms+7ms, total 29ms
,V/GLSActivity( 1123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1123): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 1123): GC_CONCURRENT freed 473K, 3% free 18049K/18556K, paused 2ms+3ms, total 27ms
,D/dalvikvm( 1123): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm(  977): GC_FOR_ALLOC freed 702K, 6% free 19021K/20168K, paused 32ms, total 33ms
,I/rmt_storage(  183): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb75aa160
I/rmt_storage(  183): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  183): wakelock acquired: 1, error no: 2
,I/rmt_storage(  183): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1218797872)
,I/rmt_storage(  183): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  183): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  183): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1218797872) wakelock released: 1, error no: 0
I/rmt_storage(  183): 
,I/rmt_storage(  183): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb75aa160

```
