#### Test 564496606be5677_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
D/dalvikvm( 2671): GC_FOR_ALLOC freed 56K, 3% free 17580K/18032K, paused 12ms, total 12ms
D/dalvikvm( 2671): GC_CONCURRENT freed 273K, 2% free 17822K/18124K, paused 1ms+3ms, total 19ms
D/dalvikvm( 2671): WAIT_FOR_CONCURRENT_GC blocked 9ms
D/dalvikvm( 2671): WAIT_FOR_CONCURRENT_GC blocked 10ms
--------- beginning of /dev/log/system
I/ActivityManager(  757): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2708 uid=10065 gids={50065, 3003, 1028, 1015}
I/ActivityManager(  757): Killing 1908:com.google.android.email/u0a36 (adj 15): empty #17
D/dalvikvm( 2671): GC_CONCURRENT freed 290K, 2% free 17987K/18308K, paused 3ms+1ms, total 17ms
D/dalvikvm( 2671): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2671): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2671): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2671): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2671): VFY: unable to resolve instance field 36
D/dalvikvm( 2671): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2671): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2671): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2671): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2671): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 2671): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 2671): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4276ebb8
D/dalvikvm( 2671): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4276ebb8
D/dalvikvm( 2671): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4276ebb8, skipping init
D/dalvikvm( 2671): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4276ebb8
D/dalvikvm( 2671): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4276ebb8
V/JNIHelp ( 2671): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/dalvikvm( 2671): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4276ebb8
D/dalvikvm( 2671): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4276ebb8
D/dalvikvm( 2671): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4276ebb8
D/dalvikvm( 2671): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4276ebb8
D/dalvikvm( 2671): GC_CONCURRENT freed 455K, 3% free 17949K/18440K, paused 3ms+2ms, total 18ms
W/Quickoffice( 2708): Cleanup of storage: done
D/com.google.android.apps.docs.quickoffice.X( 2708): Loading recent documents list
D/Quickoffice( 2708): The number of lines present in  /proc/mount 21
D/Quickoffice( 2708): Parsing the storagedefinition.xml.
D/Quickoffice( 2708): # of Storagedefinitions - 35
D/Quickoffice( 2708): The # of storage definitions available - 35
D/Quickoffice( 2708): Processing mountline rootfs / rootfs ro,relatime 0 0
D/Quickoffice( 2708): Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
D/Quickoffice( 2708): Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
D/Quickoffice( 2708): Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
D/Quickoffice( 2708): Processing mountline proc /proc proc rw,relatime 0 0
D/Quickoffice( 2708): Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
D/Quickoffice( 2708): Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
D/Quickoffice( 2708): Processing mountline debugfs /sys/kernel/debug debugfs rw,relatime 0 0
D/Quickoffice( 2708): Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
D/Quickoffice( 2708): Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
D/Quickoffice( 2708): Processing mountline tmpfs /mnt/asec tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2708): Processing mountline tmpfs /mnt/obb tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2708): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,nosuid,nodev,relatime,data=ordered 0 0
D/Quickoffice( 2708): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2708): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2708): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2708): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
D/Quickoffice( 2708): Processing mountline /dev/fuse /mnt/shell/emulated fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2708): Processing mountline tmpfs /storage/emulated tmpfs rw,seclabel,nosuid,nodev,relatime,mode=751,gid=1028 0 0
D/Quickoffice( 2708): Processing mountline /dev/fuse /storage/emulated/0 fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2708): Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2708): Build properties are not configured for this storage definition.
D/Quickoffice( 2708): Adding the mount informaiton for listing in file manager MountedDeviceInformation [device=/dev/fuse, mountPath=/storage/emulated/legacy, fileSystemType=fuse, options=rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other, bootPriority1=0, bootPriority2=0, storageInfo=StorageDefinition [id=2010, matchPatterns=[/storage/emulated/legacy, fuse], skipPatterns=[obb], buildPatterns=[], type=INTERNAL, resourceString=2131231627, resourceStringItemized=2131231630, resourceIcon=2130838373, enabled=true], userFriendlyName=null]
D/Quickoffice( 2708): The # of mounts identified -  1
I/ActivityManager(  757): Killing 2127:com.google.android.music:main/u0a58 (adj 15): empty #17
D/dalvikvm( 2708): GC_CONCURRENT freed 259K, 2% free 16952K/17240K, paused 3ms+2ms, total 23ms
D/dalvikvm( 2708): WAIT_FOR_CONCURRENT_GC blocked 3ms
D/com.google.android.apps.docs.quickoffice.X( 2708): Checking validity of 0 items
D/dalvikvm( 2708): WAIT_FOR_CONCURRENT_GC blocked 4ms
I/ProviderInstaller( 2671): Installed default security provider GmsCore_OpenSSL
F/ActivityManager(  757): Service ServiceRecord{42dafb18 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{42bcac00 2127:com.google.android.music:main/u0a58} not same as in map: null
F/ActivityManager(  757): Service ServiceRecord{42d8be18 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{42bcac00 2127:com.google.android.music:main/u0a58} not same as in map: null
W/Quickoffice( 2708): Could not load clipboard.
F/ActivityManager(  757): Service ServiceRecord{42d6a138 u0 com.google.android.music/.download.artwork.ArtDownloadService} in process ProcessRecord{42bcac00 2127:com.google.android.music:main/u0a58} not same as in map: null
F/ActivityManager(  757): Service ServiceRecord{42d540d0 u0 com.google.android.music/.download.ArtDownloadQueueService} in process ProcessRecord{42bcac00 2127:com.google.android.music:main/u0a58} not same as in map: null
F/ActivityManager(  757): Service ServiceRecord{42c25398 u0 com.google.android.music/.download.cache.ArtCacheService} in process ProcessRecord{42bcac00 2127:com.google.android.music:main/u0a58} not same as in map: null
D/ContentResolverUtil( 2708): There are 0 persisted uri permissions.
D/com.google.android.apps.docs.quickoffice.X( 2708): 0 items were valid
W/Quickoffice( 2708): Could not store clipboard.
W/ActivityManager(  757): No permission grants found for com.quickoffice.android
I/Icing   ( 1328): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
I/Icing   ( 1328): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
I/Icing   ( 1328): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
D/dalvikvm( 1328): GC_CONCURRENT freed 521K, 3% free 19054K/19608K, paused 2ms+2ms, total 18ms
I/Icing   ( 1328): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
,D/AndroidRuntime( 2734): 
D/AndroidRuntime( 2734): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2734): CheckJNI is OFF
D/dalvikvm( 2734): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2734): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2734): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2734): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2734): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 2734): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/AndroidRuntime( 2734): Calling main entry com.android.commands.am.Am
I/ActivityManager(  757): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2734
D/PermissionCache(  182): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (106 us)
D/dalvikvm(  757): GC_FOR_ALLOC freed 24806K, 57% free 24188K/55500K, paused 90ms, total 90ms
D/AndroidRuntime( 2734): Shutting down VM
D/dalvikvm( 2734): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 0ms+0ms, total 1ms
I/ActivityManager(  757): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2753 uid=10108 gids={50108, 3003, 3001, 3002, 1028, 1015}
I/SearchController( 1221): #onHotwordDetectorStopped(false)
I/MicrophoneInputStream( 1221): mic_close
I/ActivityManager(  757): Killing 2430:com.android.chrome/u0a31 (adj 15): empty #17
I/ActivityManager(  757): Killing 1806:com.google.android.gm/u0a41 (adj 15): empty #18
I/MicroHotwordRecognitionRunner( 1221): Hotword detection finished
I/MicroHotwordRecognitionRunner( 1221): Stopping hotword detection.
V/WebViewChromiumFactoryProvider( 2753): Binding Chromium to main looper Looper (main, tid 1) {4261c9b8}
I/LibraryLoader( 2753): Expected native library version number "",actual native library version number ""
I/chromium( 2753): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2753): Initializing chromium process, renderers=0
D/BluetoothManagerService(  757): Message: 20
D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42ce25e8:true
I/Adreno-EGL( 2753): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
W/chromium( 2753): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 2753): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2753): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2753): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2753): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2753): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 2753): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 2753): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2753): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2753): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2753): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2753): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 2753): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2753): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2753): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2753): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2753): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2753): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2753): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 2753): CordovaWebView is running on device made by: LGE
,D/OpenGLRenderer( 2753): Enabling debug mode 0
,W/AwContents( 2753): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  757): Displayed com.test.thalitest/.MainActivity: +283ms
,D/dalvikvm(  757): GC_CONCURRENT freed 205K, 54% free 25757K/55500K, paused 3ms+4ms, total 73ms
,D/JsMessageQueue( 2753): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 2753): GC_CONCURRENT freed 248K, 2% free 16879K/17156K, paused 1ms+2ms, total 14ms
,D/dalvikvm( 2753): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42620cd0
,D/dalvikvm( 2753): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42620cd0
,D/jxcore_app_log( 2753): JniHelper::setJavaVM(0x41504f00), pthread_self() = 1983437768
,I/chromium( 2753): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/dalvikvm( 2753): GC_CONCURRENT freed 189K, 2% free 17122K/17344K, paused 2ms+5ms, total 15ms
,D/dalvikvm( 2753): GC_CONCURRENT freed 160K, 2% free 17465K/17664K, paused 3ms+1ms, total 15ms
,D/dalvikvm( 2753): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 2753): GC_CONCURRENT freed 157K, 2% free 17808K/18008K, paused 2ms+2ms, total 17ms
,D/dalvikvm( 2753): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/dalvikvm( 2753): WAIT_FOR_CONCURRENT_GC blocked 3ms
,D/dalvikvm( 2753): GC_CONCURRENT freed 153K, 2% free 18147K/18348K, paused 1ms+1ms, total 15ms
D/dalvikvm( 2753): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/dalvikvm( 2753): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 2753): GC_CONCURRENT freed 157K, 2% free 18480K/18688K, paused 1ms+1ms, total 11ms
D/dalvikvm( 2753): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 2753): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 2753): GC_CONCURRENT freed 174K, 2% free 18879K/19108K, paused 2ms+1ms, total 13ms
,D/dalvikvm( 2753): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 2753): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 2753): GC_CONCURRENT freed 214K, 2% free 19366K/19640K, paused 2ms+1ms, total 16ms
,D/dalvikvm( 2753): WAIT_FOR_CONCURRENT_GC blocked 5ms
,D/dalvikvm( 2753): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/dalvikvm( 2753): GC_CONCURRENT freed 279K, 2% free 19941K/20288K, paused 1ms+2ms, total 16ms
,D/dalvikvm( 2753): WAIT_FOR_CONCURRENT_GC blocked 6ms
,D/dalvikvm( 2753): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 2753): GC_CONCURRENT freed 314K, 2% free 20669K/21056K, paused 1ms+2ms, total 27ms
D/dalvikvm( 2753): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 2753): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 2753): GC_CONCURRENT freed 385K, 3% free 21556K/22024K, paused 3ms+2ms, total 37ms
D/dalvikvm( 2753): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/dalvikvm( 2753): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/dalvikvm( 2753): GC_CONCURRENT freed 572K, 3% free 22550K/23208K, paused 1ms+3ms, total 28ms
,D/dalvikvm( 2753): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/dalvikvm( 2753): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 2753): GC_CONCURRENT freed 1512K, 7% free 22927K/24532K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 2753): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm( 2753): GC_FOR_ALLOC freed 1002K, 7% free 23052K/24532K, paused 22ms, total 22ms
,I/dalvikvm-heap( 2753): Grow heap (frag case) to 23.233MB for 728606-byte allocation
,D/dalvikvm( 2753): GC_FOR_ALLOC freed <1K, 6% free 23763K/25244K, paused 21ms, total 21ms
,D/dalvikvm( 2753): GC_FOR_ALLOC freed 1288K, 8% free 23300K/25244K, paused 22ms, total 23ms
,I/dalvikvm-heap( 2753): Grow heap (frag case) to 23.823MB for 1092904-byte allocation
,D/dalvikvm( 2753): GC_FOR_ALLOC freed 0K, 8% free 24368K/26312K, paused 21ms, total 21ms
,D/dalvikvm( 2753): GC_FOR_ALLOC freed 1953K, 10% free 23706K/26312K, paused 24ms, total 25ms
,I/dalvikvm-heap( 2753): Grow heap (frag case) to 24.740MB for 1639352-byte allocation
,D/dalvikvm( 2753): GC_FOR_ALLOC freed 22K, 10% free 25284K/27916K, paused 22ms, total 22ms
,D/dalvikvm( 2753): GC_FOR_ALLOC freed 2889K, 14% free 24284K/27916K, paused 23ms, total 24ms
,I/dalvikvm-heap( 2753): Grow heap (frag case) to 26.086MB for 2459024-byte allocation
,D/dalvikvm( 2753): GC_FOR_ALLOC freed 14K, 13% free 26671K/30320K, paused 24ms, total 24ms
,D/dalvikvm( 2753): GC_FOR_ALLOC freed 4548K, 17% free 25247K/30320K, paused 27ms, total 27ms
,I/dalvikvm-heap( 2753): Grow heap (frag case) to 28.200MB for 3688532-byte allocation
,D/dalvikvm( 2753): GC_FOR_ALLOC freed 43K, 16% free 28806K/33924K, paused 37ms, total 37ms
,D/dalvikvm( 2753): GC_CONCURRENT freed 2566K, 23% free 26285K/33924K, paused 2ms+3ms, total 28ms
,D/dalvikvm( 2753): GC_FOR_ALLOC freed 2146K, 23% free 26358K/33924K, paused 28ms, total 33ms
,W/jxcore-log( 2753): Initializing JXcore engine
,W/jxcore-log( 2753): JXcore engine is ready
,D/dalvikvm( 2753): GC_CONCURRENT freed 6016K, 31% free 23564K/33924K, paused 2ms+1ms, total 20ms
,D/dalvikvm( 2753): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 2753): WAIT_FOR_CONCURRENT_GC blocked 14ms
,W/jxcore-log( 2753): Starting JXcore engine
,W/jxcore-log( 2753): Platform android
W/jxcore-log( 2753): 
,W/jxcore-log( 2753): Process ARCH arm
W/jxcore-log( 2753): 
,I/jxcore-log( 2753): JXcore Cordova bridge is ready!
I/jxcore-log( 2753): 
,W/jxcore-log( 2753): JXcore engine is started
,E/jxcore  ( 2753): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 2753): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 2753): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,D/dalvikvm(  757): GC_FOR_ALLOC freed 30K, 53% free 26566K/55500K, paused 39ms, total 39ms
,I/dalvikvm-heap(  757): Grow heap (frag case) to 26.791MB for 856096-byte allocation
,D/dalvikvm(  757): GC_FOR_ALLOC freed 1K, 52% free 27400K/56340K, paused 39ms, total 39ms
,W/PluginManager( 2753): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 104ms. Plugin should use CordovaInterface.getThreadPool().
,W/Sidekick_LocationOracleImpl( 1221): Best location was null
,W/IInputConnectionWrapper( 2753): showStatusIcon on inactive InputConnection
,W/GCoreFlp(  985): No location to return for getLastLocation()
,W/GCoreFlp(  985): No location to return for getLastLocation()
,W/GCoreFlp(  985): No location to return for getLastLocation()
,W/GCoreFlp(  985): No location to return for getLastLocation()
,W/GCoreFlp(  985): No location to return for getLastLocation()
,W/GCoreFlp(  985): No location to return for getLastLocation()
,D/dalvikvm( 1221): GC_FOR_ALLOC freed 1061K, 8% free 17848K/19276K, paused 22ms, total 22ms
,I/dalvikvm-heap( 1221): Grow heap (frag case) to 18.066MB for 640016-byte allocation
,D/dalvikvm( 1221): GC_FOR_ALLOC freed <1K, 5% free 18472K/19276K, paused 25ms, total 25ms
,I/MicroHotwordRecognitionRunner( 1221): Starting hotword detection.
,D/dalvikvm( 1045): GC_CONCURRENT freed 2066K, 8% free 26296K/28388K, paused 1ms+2ms, total 23ms
,D/audio_hw_primary(  185): select_devices: out_snd_device(0: ) in_snd_device(35: voice-rec-mic)
,D/        (  185): Failed to fetch the lookup information of the device 0000003E 
,E/ACDB-LOADER(  185): Error: ACDB AudProc vol returned = -19
,D/dalvikvm( 1221): GC_CONCURRENT freed 12K, 5% free 18465K/19276K, paused 1ms+1ms, total 21ms
,I/SearchController( 1221): #onHotwordDetectorStarted
,E/libEGL  ( 2753): call to OpenGL ES API with no current context (logged once per thread)
,D/dalvikvm( 1125): GC_CONCURRENT freed 391K, 4% free 17910K/18576K, paused 3ms+1ms, total 15ms
,I/VacuumService(  985): Vacuum at: now=1453288517687 tag=VacuumService
,D/dalvikvm( 1665): GC_CONCURRENT freed 961K, 5% free 19823K/20824K, paused 2ms+1ms, total 25ms
,D/Finsky  ( 1665): [1] 5.onFinished: Installation state replication succeeded.
,D/dalvikvm( 1125): GC_CONCURRENT freed 365K, 4% free 17962K/18576K, paused 2ms+2ms, total 22ms
,D/dalvikvm(  985): GC_CONCURRENT freed 469K, 3% free 18788K/19352K, paused 3ms+3ms, total 20ms
,I/PhenotypeConfigurator(  985): Scheduling Phenotype for one-off execution 4038 seconds from now (1453288517927)
,D/GetConfigurationSnapshotOperation(  985): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter(  985): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm(  985): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  985): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm(  985): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm(  985): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm(  985): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm(  985): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory(  985): Using platform SSLCertificateSocketFactory
,D/dalvikvm(  985): GC_CONCURRENT freed 525K, 4% free 18944K/19564K, paused 5ms+4ms, total 37ms
,D/dalvikvm(  985): GC_CONCURRENT freed 611K, 4% free 19037K/19744K, paused 3ms+3ms, total 21ms
,D/dalvikvm(  985): GC_CONCURRENT freed 615K, 4% free 19169K/19876K, paused 1ms+4ms, total 20ms
,D/dalvikvm(  985): GC_CONCURRENT freed 759K, 5% free 19169K/20024K, paused 2ms+4ms, total 21ms
,D/dalvikvm(  985): GC_CONCURRENT freed 805K, 5% free 19192K/20092K, paused 2ms+7ms, total 31ms
,V/GLSActivity( 1125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1125): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm(  985): GC_FOR_ALLOC freed 787K, 6% free 19126K/20140K, paused 23ms, total 23ms
,D/dalvikvm(  985): GC_FOR_ALLOC freed 304K, 7% free 18875K/20140K, paused 28ms, total 28ms
,I/rmt_storage(  178): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb8087160
I/rmt_storage(  178): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  178): wakelock acquired: 1, error no: 2
,I/rmt_storage(  178): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1207406896)
,I/rmt_storage(  178): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  178): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  178): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1207406896) wakelock released: 1, error no: 0
I/rmt_storage(  178): 
,I/rmt_storage(  178): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb8087160
,I/PowerManagerService(  757): Going to sleep due to screen timeout...
,I/Adreno-EGL(  757): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/SurfaceFlinger(  182): Screen released, type=0 flinger=0xb8789450
,D/qdhwcomposer(  182): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  182): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  757): Excessive delay in blankDisplay() while turning screen off: 293ms
,V/KeyguardServiceDelegate(  757): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@4440eda8)
,V/KeyguardServiceDelegate(  757): **** SHOWN CALLED ****
I/WindowManager(  757): No lock screen! windowToken=null
,D/dalvikvm( 1125): GC_CONCURRENT freed 419K, 4% free 17927K/18576K, paused 1ms+2ms, total 18ms
,I/SearchController( 1221): #onHotwordDetectorStopped(false)
,I/MicrophoneInputStream( 1221): mic_close
,I/ActivityManager(  757): Killing 1702:com.google.android.calendar/u0a28 (adj 15): empty #17
,D/NfcService( 1027): NFC-C OFF
,I/MicroHotwordRecognitionRunner( 1221): Hotword detection finished
,I/MicroHotwordRecognitionRunner( 1221): Stopping hotword detection.
,D/dalvikvm( 1221): GC_CONCURRENT freed 1064K, 7% free 17921K/19144K, paused 2ms+5ms, total 20ms
,I/wpa_supplicant(  948): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  757): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  757): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  757): Attempting to switch to mobile
,D/ConnectivityService(  757): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  757): android_net_utils_resetConnections in env=0x753f12a8 clazz=0x5d500001 iface=wlan0 mask=0x3
D/ConnectivityService(  757): resetConnections(wlan0, 3)
,V/NativeCrypto( 1125): Read error: ssl=0x7749c3d0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1125): SSL shutdown failed: ssl=0x7749c3d0: I/O error during system call, Broken pipe
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  757): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  757): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  948): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  948): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  948): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  948): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  757): scanCount==0 - aborting
,D/Tethering(  757): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  757): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  757): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/dalvikvm( 1261): GC_CONCURRENT freed 329K, 3% free 16765K/17132K, paused 20ms+1ms, total 40ms
,I/SystemUpdateService( 1328): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1328): onCreate
,D/SystemUpdateService( 1328): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1328): active receiver: enabled
,I/iu.Environment( 1328): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1328): num queued entries: 0
,I/iu.UploadsManager( 1328): num updated entries: 0
I/iu.SyncManager( 1328): NEXT; no task
,I/SystemUpdateService( 1328): Already downloaded, skipping offpeak checks.
,I/SystemUpdateService( 1328): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1328): now status is 0 (complete)
I/SystemUpdateService( 1328): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1328): file has been verified
,I/SystemUpdateService( 1328): OTA package size = 2571501
,I/Babel   ( 1946): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1328): showing system update notification
I/ActivityManager(  757): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=3003 uid=10031 gids={50031, 3003, 1028, 1015}
,D/SystemUpdateService( 1328): onDestroy
,D/dalvikvm( 3003): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 3003): VFY: unable to resolve instance field 68
,D/dalvikvm( 3003): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 3003): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 3003): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 3003): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 3003): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/dalvikvm( 3003): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 3003): VFY: unable to resolve instance field 68
,D/dalvikvm( 3003): VFY: replacing opcode 0x54 at 0x0011
,I/ActivityManager(  757): Killing 1060:com.google.android.keep/u0a52 (adj 15): empty #17
D/dalvikvm( 3003): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 3003): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 3003): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 3003): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 3003): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 3003): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
,D/WifiStateMachine(  757): VerifyingLinkState enter
,D/WifiStateMachine(  757): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  757): CaptivePortalCheckState enter
D/ConnectivityService(  757): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  757): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine(  757): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  757): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  757): Unexpected mtu value: android.net.wifi.WifiStateTracker@429fef98
,D/Nat464Xlat(  757): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  757): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  757): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  757):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  757): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  757): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/Tethering(  757): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  757): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1328): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1328): onCreate
,D/SystemUpdateService( 1328): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1328): active receiver: enabled
,I/SystemUpdateService( 1328): Already downloaded, skipping offpeak checks.
,I/iu.Environment( 1328): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1328): num queued entries: 0
,I/iu.UploadsManager( 1328): num updated entries: 0
I/SystemUpdateService( 1328): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1328): now status is 0 (complete)
,I/SystemUpdateService( 1328): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1328): file has been verified
,I/SystemUpdateService( 1328): OTA package size = 2571501
,I/SystemUpdateService( 1328): showing system update notification
,I/iu.SyncManager( 1328): NEXT; no task
,D/SystemUpdateService( 1328): onDestroy
,I/Babel   ( 1946): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  757): handleInetConditionHoldEnd: net=1, condition=0, published condition=100
,D/ConnectivityService(  757): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  757): DelayedCaptiveCheckState{ when=-7ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  757): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  757): Checking http://216.58.209.78/generate_204
,D/CaptivePortalTracker(  757): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  757): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  757): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  757): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  757): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/ConnectivityService(  757): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  757): Done.
,D/ConnectivityService(  757): Setting timer for 720seconds
,I/wpa_supplicant(  948): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  757): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  757): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  757): Attempting to switch to mobile
,D/ConnectivityService(  757): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  757): android_net_utils_resetConnections in env=0x753f12a8 clazz=0x9fa00001 iface=wlan0 mask=0x3
D/ConnectivityService(  757): resetConnections(wlan0, 3)
,D/dalvikvm( 1006): GC_CONCURRENT freed 339K, 3% free 17066K/17432K, paused 1ms+1ms, total 35ms
,V/NativeCrypto( 1125): Read error: ssl=0x7749c3d0: I/O error during system call, Connection timed out
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1125): SSL shutdown failed: ssl=0x7749c3d0: I/O error during system call, Broken pipe
,D/Nat464Xlat(  757): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  757): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  948): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  948): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  948): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  948): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  757): scanCount==0 - aborting
,D/Tethering(  757): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  757): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  757): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SystemUpdateService( 1328): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1328): onCreate
,D/SystemUpdateService( 1328): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1328): active receiver: enabled
,I/iu.Environment( 1328): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/SystemUpdateService( 1328): Already downloaded, skipping offpeak checks.
,I/iu.UploadsManager( 1328): num queued entries: 0
,I/iu.UploadsManager( 1328): num updated entries: 0
,I/Babel   ( 1946): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1328): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1328): now status is 0 (complete)
I/SystemUpdateService( 1328): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1328): file has been verified
,I/SystemUpdateService( 1328): OTA package size = 2571501
,I/iu.SyncManager( 1328): NEXT; no task
,I/SystemUpdateService( 1328): showing system update notification
,D/SystemUpdateService( 1328): onDestroy
,D/ConnectivityService(  757): handleInetConditionChange: no active default network - ignore
,W/SocketClient(  179): write error (Broken pipe)
,D/WifiStateMachine(  757): VerifyingLinkState enter
,D/WifiStateMachine(  757): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  757): CaptivePortalCheckState enter
D/ConnectivityService(  757): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  757): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine(  757): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService(  757): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  757): Unexpected mtu value: android.net.wifi.WifiStateTracker@429fef98
,D/Nat464Xlat(  757): requiresClat: netType=1, hasIPv4Address=true
,I/dalvikvm(  757): Jit: resizing JitTable from 8192 to 16384
,D/ConnectivityService(  757): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  757): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  757):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  757): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  757): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  757): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1328): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1328): onCreate
,D/SystemUpdateService( 1328): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1328): active receiver: enabled
,I/SystemUpdateService( 1328): Already downloaded, skipping offpeak checks.
,I/iu.Environment( 1328): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1328): num queued entries: 0
,I/iu.UploadsManager( 1328): num updated entries: 0
,I/SystemUpdateService( 1328): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1328): now status is 0 (complete)
I/SystemUpdateService( 1328): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1328): file has been verified
I/iu.SyncManager( 1328): NEXT; no task
,I/SystemUpdateService( 1328): OTA package size = 2571501
,I/SystemUpdateService( 1328): showing system update notification
,D/SystemUpdateService( 1328): onDestroy
,D/dalvikvm( 1328): GC_CONCURRENT freed 657K, 4% free 19104K/19792K, paused 12ms+2ms, total 37ms
,D/dalvikvm(  757): GC_EXPLICIT freed 2859K, 52% free 26819K/55572K, paused 2ms+6ms, total 65ms
,I/Babel   ( 1946): connection state changed from DISCONNECTED to CONNECTED
,D/dalvikvm( 1125): GC_CONCURRENT freed 435K, 4% free 17914K/18576K, paused 1ms+1ms, total 13ms
,D/ConnectivityService(  757): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  757): DelayedCaptiveCheckState{ when=-9ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  757): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  757): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  757): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  757): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  757): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  757): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  757): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/EventLogService( 1328): Aggregate from 1453287527260 (log), 1453287527260 (data)
,I/wpa_supplicant(  948): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  757): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  757): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  757): Attempting to switch to mobile
,D/ConnectivityService(  757): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  757): android_net_utils_resetConnections in env=0x753f12a8 clazz=0xbe100001 iface=wlan0 mask=0x3
D/ConnectivityService(  757): resetConnections(wlan0, 3)
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1125): Read error: ssl=0x77552768: I/O error during system call, Connection timed out
,V/NativeCrypto( 1125): SSL shutdown failed: ssl=0x77552768: I/O error during system call, Broken pipe
D/Nat464Xlat(  757): requiresClat: netType=1, hasIPv4Address=false
D/ConnectivityService(  757): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  948): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  948): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  948): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  948): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  757): scanCount==0 - aborting
,D/Tethering(  757): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  757): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  757): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SystemUpdateService( 1328): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1328): onCreate
,D/SystemUpdateService( 1328): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1328): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1328): num queued entries: 0
,I/SystemUpdateService( 1328): active receiver: enabled
D/ConnectivityService(  757): handleInetConditionChange: no active default network - ignore
,I/Babel   ( 1946): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1328): Already downloaded, skipping offpeak checks.
,I/iu.UploadsManager( 1328): num updated entries: 0
I/SystemUpdateService( 1328): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1328): now status is 0 (complete)
,I/SystemUpdateService( 1328): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1328): file has been verified
,I/SystemUpdateService( 1328): OTA package size = 2571501
,I/iu.SyncManager( 1328): NEXT; no task
,I/SystemUpdateService( 1328): showing system update notification
,D/SystemUpdateService( 1328): onDestroy
,D/WifiStateMachine(  757): VerifyingLinkState enter
,D/WifiStateMachine(  757): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  757): CaptivePortalCheckState enter
,D/WifiStateMachine(  757): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  757): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  757): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  757): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService(  757): Unexpected mtu value: android.net.wifi.WifiStateTracker@429fef98
,D/Nat464Xlat(  757): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  757): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  757): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  757):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  757): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  757): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  757): NoActiveNetworkState{ when=-4ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1328): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1328): onCreate
,D/SystemUpdateService( 1328): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1328): active receiver: enabled
,I/iu.Environment( 1328): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1328): num queued entries: 0
,I/SystemUpdateService( 1328): Already downloaded, skipping offpeak checks.
,I/iu.UploadsManager( 1328): num updated entries: 0
,I/SystemUpdateService( 1328): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/SystemUpdateService( 1328): now status is 0 (complete)
,I/SystemUpdateService( 1328): processDownloadedFile /cache/update.zip
I/SystemUpdateService( 1328): file has been verified
,I/SystemUpdateService( 1328): OTA package size = 2571501
,I/iu.SyncManager( 1328): NEXT; no task
,I/SystemUpdateService( 1328): showing system update notification
,D/SystemUpdateService( 1328): onDestroy
,I/Babel   ( 1946): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  757): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/CaptivePortalTracker(  757): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  757): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  757): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  757): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  757): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker(  757): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  757): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  757): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/wpa_supplicant(  948): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  757): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  757): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
,D/ConnectivityService(  757): Attempting to switch to mobile
,D/ConnectivityService(  757): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  757): android_net_utils_resetConnections in env=0x753f12a8 clazz=0xdc000001 iface=wlan0 mask=0x3
D/ConnectivityService(  757): resetConnections(wlan0, 3)
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1125): Read error: ssl=0x7749c3d0: I/O error during system call, Connection timed out
,V/NativeCrypto( 1125): SSL shutdown failed: ssl=0x7749c3d0: I/O error during system call, Broken pipe
,D/Nat464Xlat(  757): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  757): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  948): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  948): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  948): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  948): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  757): scanCount==0 - aborting
,D/CaptivePortalTracker(  757): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/Tethering(  757): MasterInitialState.processMessage what=3
D/ConnectivityService(  757): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/SystemUpdateService( 1328): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1328): onCreate
,D/SystemUpdateService( 1328): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1328): active receiver: enabled
,I/iu.Environment( 1328): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1328): num queued entries: 0
,I/iu.UploadsManager( 1328): num updated entries: 0
I/Babel   ( 1946): connection state changed from CONNECTED to DISCONNECTED
I/SystemUpdateService( 1328): Already downloaded, skipping offpeak checks.
,I/iu.SyncManager( 1328): NEXT; no task
I/SystemUpdateService( 1328): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1328): now status is 0 (complete)
I/SystemUpdateService( 1328): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1328): file has been verified
,I/SystemUpdateService( 1328): OTA package size = 2571501
,I/SystemUpdateService( 1328): showing system update notification
,D/SystemUpdateService( 1328): onDestroy
,D/WifiStateMachine(  757): VerifyingLinkState enter
,D/WifiStateMachine(  757): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  757): CaptivePortalCheckState enter
,D/WifiStateMachine(  757): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  757): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  757): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  757): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  757): Unexpected mtu value: android.net.wifi.WifiStateTracker@429fef98
,D/Nat464Xlat(  757): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  757): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  757): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  757):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  757): requiresClat: netType=1, hasIPv4Address=true
,D/Tethering(  757): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  757): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1328): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1328): onCreate
,D/SystemUpdateService( 1328): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1328): active receiver: enabled
,I/iu.Environment( 1328): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1328): num queued entries: 0
,I/SystemUpdateService( 1328): Already downloaded, skipping offpeak checks.
,I/iu.UploadsManager( 1328): num updated entries: 0
,I/SystemUpdateService( 1328): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
,I/iu.SyncManager( 1328): NEXT; no task
I/SystemUpdateService( 1328): now status is 0 (complete)
I/SystemUpdateService( 1328): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1328): file has been verified
,I/SystemUpdateService( 1328): OTA package size = 2571501
,I/SystemUpdateService( 1328): showing system update notification
,D/SystemUpdateService( 1328): onDestroy
,I/Babel   ( 1946): connection state changed from DISCONNECTED to CONNECTED
,D/dalvikvm( 1946): GC_CONCURRENT freed 1496K, 7% free 22682K/24232K, paused 2ms+2ms, total 32ms
,D/ConnectivityService(  757): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,TIME-OUT KILL (timeout was 1200000ms),D/CaptivePortalTracker(  757): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=5 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  757): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  757): Checking http://216.58.209.78/generate_204
D/CaptivePortalTracker(  757): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker(  757): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  757): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/CaptivePortalTracker(  757): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  757): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
D/AndroidRuntime( 3489): 
D/AndroidRuntime( 3489): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3489): CheckJNI is OFF
D/dalvikvm( 3489): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 3489): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3489): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3489): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 3489): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 3489): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
D/AndroidRuntime( 3489): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  757): Force stopping com.test.thalitest appid=10108 user=-1: uninstall pkg
I/ActivityManager(  757): Killing 2753:com.test.thalitest/u0a108 (adj 9): stop com.test.thalitest
W/PackageSettings(  757): Skipping PackageSetting{42706440 com.example.hello/10116} due to missing metadata
I/ActivityManager(  757): Force stopping com.test.thalitest appid=10108 user=0: pkg removed
D/dalvikvm( 1045): GC_EXPLICIT freed 289K, 8% free 26140K/28388K, paused 1ms+2ms, total 20ms
D/dalvikvm( 1221): GC_EXPLICIT freed 196K, 8% free 17786K/19144K, paused 1ms+2ms, total 17ms
D/dalvikvm( 1328): GC_EXPLICIT freed 561K, 4% free 19166K/19824K, paused 1ms+3ms, total 27ms
I/Launcher( 1045): Deferring update until onResume
I/InputReader(  757): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine(  985): Ignoring removeGeofence because network location is disabled.
I/LatinIME:LogUtils(  968): Dictionary info: dictionary = main:en_us ; version = 44 ; date = 1393228158
I/PackageManager(  757):   Action: "android.intent.action.SENDTO"
I/PackageManager(  757):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  757):   Scheme: "sms"
I/PackageManager(  757): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/Launcher( 1045): Deferring update until onResume
D/VoicemailCleanupService( 2306): Cleaning up data for package: com.test.thalitest
D/dalvikvm(  757): GC_EXPLICIT freed 2457K, 52% free 26839K/55572K, paused 2ms+4ms, total 83ms
I/PackageManager(  757):   Action: "android.intent.action.SENDTO"
I/PackageManager(  757):   Category: "android.intent.category.DEFAULT"
D/dalvikvm(  757): WAIT_FOR_CONCURRENT_GC blocked 77ms
I/PackageManager(  757):   Scheme: "smsto"
I/PackageManager(  757): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  757): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  757):   Action: "android.intent.action.SENDTO"
I/PackageManager(  757):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  757):   Scheme: "mms"
I/PackageManager(  757):   Action: "android.intent.action.SENDTO"
I/PackageManager(  757):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  757):   Scheme: "mmsto"
I/PackageManager(  757): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  757):   Action: "android.intent.action.SENDTO"
I/PackageManager(  757):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  757):   Scheme: "sms"
D/dalvikvm(  757): GC_EXPLICIT freed 314K, 52% free 26786K/55572K, paused 4ms+5ms, total 73ms
I/PackageManager(  757): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  757):   Action: "android.intent.action.SENDTO"
I/PackageManager(  757):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  757):   Scheme: "smsto"
I/PackageManager(  757): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  757):   Action: "android.intent.action.SENDTO"
I/PackageManager(  757):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  757):   Scheme: "mms"
I/Icing.InternalIcingCorporaProvider( 1221): Updating corpora: A: com.test.thalitest, C: MAYBE
I/PackageManager(  757): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
D/BackupManagerService(  757): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  757): removePackageParticipantsLocked: uid=10108 #1
D/AndroidRuntime( 3489): Shutting down VM
I/PackageManager(  757):   Action: "android.intent.action.SENDTO"
I/PackageManager(  757):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  757):   Scheme: "mmsto"
D/dalvikvm( 3489): GC_CONCURRENT freed 94K, 15% free 558K/656K, paused 2ms+0ms, total 3ms
I/PackageManager(  757): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
W/Launcher( 1045): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@42625a38 new=com.google.android.velvet.VelvetApplication@42625a38
I/ActivityManager(  757): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3527 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
W/ContextImpl( 3527): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2407 
I/ActivityManager(  757): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
I/ActivityManager(  757): Resuming delayed broadcast
I/ActivityManager(  757): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
I/Icing.InternalIcingCorporaProvider( 1221): UpdateCorporaTask done [took 150 ms] updated apps [took 149 ms] 
I/ActivityManager(  757): Resuming delayed broadcast
D/PackageBroadcastService( 1328): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1328): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1328): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1328): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1328): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1328): Module APK com.google.android.play.games already loaded
I/ActivityManager(  757): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
I/LocationSettingsChecker( 1328): Removing dialog suppression flag for package com.test.thalitest
D/gH_CompatibleDatabase( 1328): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1328): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1328): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1328): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/BaseAppContext( 1328): Using Auth Proxy for data requests.
D/gH_CompatibleDatabase( 1328): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1328): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
W/BaseAppContext( 1328): Using Auth Proxy for data requests.
D/gH_CompatibleDatabase( 1328): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1328): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1328): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1328): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1328): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1328): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1328): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/GMPM-SVC( 1328): App measurement is starting up, version: 8489
I/GMPM-SVC( 1328): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
D/dalvikvm( 1328): GC_CONCURRENT freed 694K, 4% free 19295K/20084K, paused 2ms+7ms, total 28ms
I/Icing   ( 1328): doRemovePackageData com.test.thalitest
W/SharedPreferencesImpl( 1328): writeToFile: Got exception:
W/SharedPreferencesImpl( 1328): java.io.IOException: write failed: EBADF (Bad file number)
W/SharedPreferencesImpl( 1328): 	at libcore.io.IoBridge.write(IoBridge.java:455)
W/SharedPreferencesImpl( 1328): 	at java.io.FileOutputStream.write(FileOutputStream.java:187)
W/SharedPreferencesImpl( 1328): 	at com.android.internal.util.FastXmlSerializer.flushBytes(FastXmlSerializer.java:232)
W/SharedPreferencesImpl( 1328): 	at com.android.internal.util.FastXmlSerializer.flush(FastXmlSerializer.java:253)
W/SharedPreferencesImpl( 1328): 	at com.android.internal.util.FastXmlSerializer.endDocument(FastXmlSerializer.java:198)
W/SharedPreferencesImpl( 1328): 	at com.android.internal.util.XmlUtils.writeMapXml(XmlUtils.java:182)
W/SharedPreferencesImpl( 1328): 	at android.app.SharedPreferencesImpl.writeToFile(SharedPreferencesImpl.java:596)
W/SharedPreferencesImpl( 1328): 	at android.app.SharedPreferencesImpl.access$800(SharedPreferencesImpl.java:52)
W/SharedPreferencesImpl( 1328): 	at android.app.SharedPreferencesImpl$2.run(SharedPreferencesImpl.java:511)
W/SharedPreferencesImpl( 1328): 	at android.app.SharedPreferencesImpl.enqueueDiskWrite(SharedPreferencesImpl.java:532)
W/SharedPreferencesImpl( 1328): 	at android.app.SharedPreferencesImpl.access$100(SharedPreferencesImpl.java:52)
W/SharedPreferencesImpl( 1328): 	at android.app.SharedPreferencesImpl$EditorImpl.commit(SharedPreferencesImpl.java:454)
W/SharedPreferencesImpl( 1328): 	at com.google.android.gms.icing.proxy.f.a(SourceFile:365)
W/SharedPreferencesImpl( 1328): 	at com.google.android.gms.icing.proxy.f.a(SourceFile:213)
W/SharedPreferencesImpl( 1328): 	at com.google.android.gms.icing.proxy.f.a(SourceFile:31)
W/SharedPreferencesImpl( 1328): 	at com.google.android.gms.icing.proxy.h.run(SourceFile:132)
W/SharedPreferencesImpl( 1328): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/SharedPreferencesImpl( 1328): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/SharedPreferencesImpl( 1328): 	at java.lang.Thread.run(Thread.java:841)
W/SharedPreferencesImpl( 1328): Caused by: libcore.io.ErrnoException: write failed: EBADF (Bad file number)
W/SharedPreferencesImpl( 1328): 	at libcore.io.Posix.writeBytes(Native Method)
W/SharedPreferencesImpl( 1328): 	at libcore.io.Posix.write(Posix.java:202)
W/SharedPreferencesImpl( 1328): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:197)
W/SharedPreferencesImpl( 1328): 	at libcore.io.IoBridge.write(IoBridge.java:450)
W/SharedPreferencesImpl( 1328): 	... 18 more
E/SharedPreferencesImpl( 1328): Couldn't clean up partially-written file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml
E/SQLiteDatabase( 1328): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 1328): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1328): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:952)
E/SQLiteDatabase( 1328): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1328): 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2307)
E/SQLiteDatabase( 1328): 	at com.google.android.gms.measurement.internal.e.e(SourceFile:418)
E/SQLiteDatabase( 1328): 	at com.google.android.gms.measurement.internal.e.a(SourceFile:357)
E/SQLiteDatabase( 1328): 	at com.google.android.gms.measurement.internal.aq.s(SourceFile:1591)
E/SQLiteDatabase( 1328): 	at com.google.android.gms.measurement.internal.aq.p(SourceFile:1605)
E/SQLiteDatabase( 1328): 	at com.google.android.gms.measurement.internal.aq.c(SourceFile:306)
E/SQLiteDatabase( 1328): 	at com.google.android.gms.measurement.internal.ar.run(SourceFile:195)
E/SQLiteDatabase( 1328): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 1328): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 1328): 	at com.google.android.gms.measurement.internal.ap.run(SourceFile:294)
E/GMPM-SVC( 1328): Opening the database failed, dropping and recreating it
E/SQLiteDatabase( 1328): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 1328): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:804)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:789)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1328): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:952)
E/SQLiteDatabase( 1328): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1328): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1328): 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
E/SQLiteDatabase( 1328): 	at com.google.android.gms.measurement.internal.e.e(SourceFile:418)
E/SQLiteDatabase( 1328): 	at com.google.android.gms.measurement.internal.e.a(SourceFile:357)
E/SQLiteDatabase( 1328): 	at com.google.android.gms.measurement.internal.aq.s(SourceFile:1591)
E/SQLiteDatabase( 1328): 	at com.google.android.gms.measurement.internal.aq.p(SourceFile:1605)
E/SQLiteDatabase( 1328): 	at com.google.android.gms.measurement.internal.aq.c(SourceFile:306)
E/SQLiteDatabase( 1328): 	at com.google.android.gms.measurement.internal.ar.run(SourceFile:195)
E/SQLiteDatabase( 1328): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 1328): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 1328): 	at com.google.android.gms.measurement.internal.ap.run(SourceFile:294)
E/GMPM-SVC( 1328): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
W/GMPM-SVC( 1328): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
E/GMPM-SVC( 1328): Task exception on worker thread: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2319)
E/ConnectivityChangeReceiver( 1328): Ignoring connectivity change
W/FileUtils( 1328): Failed to chmod(/data/data/com.google.android.gms/databases/DocList.db): libcore.io.ErrnoException: chmod failed: EROFS (Read-only file system)
W/GMPM-SVC( 1328): Error opening database: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2303)
E/GMPM-SVC( 1328): Error querying app: com.test.thalitest, android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2303)
W/GMPM-SVC( 1328): Error opening database: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2303)
E/GMPM-SVC( 1328): Task exception on worker thread: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2303)
E/SharedPreferencesImpl( 1328): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 1328): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 1328): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 1328): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 1328): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 1328): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 1328): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
E/SharedPreferencesImpl( 1328): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak

```
