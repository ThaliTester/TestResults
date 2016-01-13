#### Test 558877588826def_thali09_LGE-Nexus 5 Logs


```
--------- beginning of /dev/log/main
I/dalvikvm( 2803): Could not find method android.provider.DocumentsContract.getTreeDocumentId, referenced from method edw.a
W/dalvikvm( 2803): VFY: unable to resolve static method 2986: Landroid/provider/DocumentsContract;.getTreeDocumentId (Landroid/net/Uri;)Ljava/lang/String;
D/dalvikvm( 2803): VFY: replacing opcode 0x71 at 0x0075
D/dalvikvm( 2803): GC_CONCURRENT freed 440K, 3% free 17517K/17984K, paused 1ms+2ms, total 12ms
D/dalvikvm( 2803): GC_FOR_ALLOC freed 39K, 3% free 17579K/18024K, paused 14ms, total 14ms
,--------- beginning of /dev/log/system
I/ActivityManager(  757): Start proc com.quickoffice.android for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver: pid=2839 uid=10065 gids={50065, 3003, 1028, 1015}
I/ActivityManager(  757): Killing 1923:com.google.android.email/u0a36 (adj 15): empty #17
D/dalvikvm( 2803): GC_CONCURRENT freed 192K, 2% free 17783K/18104K, paused 2ms+1ms, total 13ms
D/dalvikvm( 2803): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2803): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2803): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 2803): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 2803): VFY: unable to resolve instance field 36
D/dalvikvm( 2803): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 2803): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 2803): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 2803): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 2803): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 2803): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 2803): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x426c75f8
D/dalvikvm( 2803): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x426c75f8
D/dalvikvm( 2803): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x426c75f8, skipping init
D/dalvikvm( 2803): GC_CONCURRENT freed 403K, 3% free 17843K/18276K, paused 1ms+3ms, total 14ms
D/dalvikvm( 2803): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x426c75f8
D/dalvikvm( 2803): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x426c75f8
V/JNIHelp ( 2803): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/dalvikvm( 2803): GC_CONCURRENT freed 391K, 3% free 17919K/18344K, paused 5ms+1ms, total 17ms
D/dalvikvm( 2803): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x426c75f8
D/dalvikvm( 2803): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x426c75f8
D/dalvikvm( 2803): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x426c75f8
D/dalvikvm( 2803): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x426c75f8
W/Quickoffice( 2839): Cleanup of storage: done
D/com.google.android.apps.docs.quickoffice.X( 2839): Loading recent documents list
D/Quickoffice( 2839): The number of lines present in  /proc/mount 21
D/dalvikvm( 2803): GC_FOR_ALLOC freed 179K, 2% free 18052K/18384K, paused 12ms, total 12ms
D/Quickoffice( 2839): Parsing the storagedefinition.xml.
D/dalvikvm(  994): GC_CONCURRENT freed 495K, 4% free 18668K/19272K, paused 2ms+3ms, total 19ms
D/Quickoffice( 2839): # of Storagedefinitions - 35
D/Quickoffice( 2839): The # of storage definitions available - 35
D/Quickoffice( 2839): Processing mountline rootfs / rootfs ro,relatime 0 0
D/Quickoffice( 2839): Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
D/Quickoffice( 2839): Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
D/Quickoffice( 2839): Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
D/dalvikvm( 2839): GC_CONCURRENT freed 171K, 2% free 16912K/17116K, paused 3ms+1ms, total 13ms
D/Quickoffice( 2839): Processing mountline proc /proc proc rw,relatime 0 0
D/Quickoffice( 2839): Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
D/Quickoffice( 2839): Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
D/Quickoffice( 2839): Processing mountline debugfs /sys/kernel/debug debugfs rw,relatime 0 0
D/Quickoffice( 2839): Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
D/Quickoffice( 2839): Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
D/Quickoffice( 2839): Processing mountline tmpfs /mnt/asec tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2839): Processing mountline tmpfs /mnt/obb tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
D/Quickoffice( 2839): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,nosuid,nodev,relatime,data=ordered 0 0
D/Quickoffice( 2839): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2839): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2839): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
D/Quickoffice( 2839): Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
D/Quickoffice( 2839): Processing mountline /dev/fuse /mnt/shell/emulated fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2839): Processing mountline tmpfs /storage/emulated tmpfs rw,seclabel,nosuid,nodev,relatime,mode=751,gid=1028 0 0
D/Quickoffice( 2839): Processing mountline /dev/fuse /storage/emulated/0 fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2839): Processing mountline /dev/fuse /storage/emulated/legacy fuse rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
D/Quickoffice( 2839): Build properties are not configured for this storage definition.
D/Quickoffice( 2839): Adding the mount informaiton for listing in file manager MountedDeviceInformation [device=/dev/fuse, mountPath=/storage/emulated/legacy, fileSystemType=fuse, options=rw,nosuid,nodev,relatime,user_id=1023,group_id=1023,default_permissions,allow_other, bootPriority1=0, bootPriority2=0, storageInfo=StorageDefinition [id=2010, matchPatterns=[/storage/emulated/legacy, fuse], skipPatterns=[obb], buildPatterns=[], type=INTERNAL, resourceString=2131231627, resourceStringItemized=2131231630, resourceIcon=2130838373, enabled=true], userFriendlyName=null]
D/AndroidRuntime( 2851): 
D/AndroidRuntime( 2851): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2851): CheckJNI is OFF
D/Quickoffice( 2839): The # of mounts identified -  1
I/ProviderInstaller( 2803): Installed default security provider GmsCore_OpenSSL
D/dalvikvm( 2851): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 2851): Added shared lib libjavacore.so 0x0
D/dalvikvm( 2851): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 2851): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 2851): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/ActivityManager(  757): Killing 2146:com.google.android.music:main/u0a58 (adj 15): empty #17
D/com.google.android.apps.docs.quickoffice.X( 2839): Checking validity of 0 items
F/ActivityManager(  757): Service ServiceRecord{42d6bec0 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{42c25848 2146:com.google.android.music:main/u0a58} not same as in map: null
F/ActivityManager(  757): Service ServiceRecord{42d08ec8 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{42c25848 2146:com.google.android.music:main/u0a58} not same as in map: null
W/Quickoffice( 2839): Could not load clipboard.
F/ActivityManager(  757): Service ServiceRecord{42ccfad8 u0 com.google.android.music/.download.artwork.ArtDownloadService} in process ProcessRecord{42c25848 2146:com.google.android.music:main/u0a58} not same as in map: null
D/dalvikvm( 2851): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
F/ActivityManager(  757): Service ServiceRecord{42ca3a50 u0 com.google.android.music/.download.ArtDownloadQueueService} in process ProcessRecord{42c25848 2146:com.google.android.music:main/u0a58} not same as in map: null
F/ActivityManager(  757): Service ServiceRecord{42c9d730 u0 com.google.android.music/.download.cache.ArtCacheService} in process ProcessRecord{42c25848 2146:com.google.android.music:main/u0a58} not same as in map: null
D/ContentResolverUtil( 2839): There are 0 persisted uri permissions.
D/com.google.android.apps.docs.quickoffice.X( 2839): 0 items were valid
W/ActivityManager(  757): No permission grants found for com.quickoffice.android
W/Quickoffice( 2839): Could not store clipboard.
D/AndroidRuntime( 2851): Calling main entry com.android.commands.am.Am
I/ActivityManager(  757): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 2851
D/PermissionCache(  180): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (150 us)
I/Icing   ( 1332): Indexing DAD01F3A9BA107296FD295581C27F6C1449145D9 from com.google.android.googlequicksearchbox
D/dalvikvm(  757): GC_FOR_ALLOC freed 22742K, 55% free 24032K/52836K, paused 111ms, total 111ms
D/AndroidRuntime( 2851): Shutting down VM
D/dalvikvm( 2851): GC_CONCURRENT freed 95K, 15% free 586K/684K, paused 0ms+0ms, total 1ms
I/ActivityManager(  757): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2890 uid=10108 gids={50108, 3003, 3001, 3002, 1028, 1015}
I/SearchController( 1205): #onHotwordDetectorStopped(false)
I/MicrophoneInputStream( 1205): mic_close
I/MicroHotwordRecognitionRunner( 1205): Hotword detection finished
I/MicroHotwordRecognitionRunner( 1205): Stopping hotword detection.
V/WebViewChromiumFactoryProvider( 2890): Binding Chromium to main looper Looper (main, tid 1) {4262b780}
I/LibraryLoader( 2890): Expected native library version number "",actual native library version number ""
I/chromium( 2890): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2890): Initializing chromium process, renderers=0
D/BluetoothManagerService(  757): Message: 20
D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42cda6e8:true
I/Adreno-EGL( 2890): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
I/ActivityManager(  757): Killing 1794:com.google.android.gm/u0a41 (adj 15): empty #17
W/chromium( 2890): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/dalvikvm( 2890): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 2890): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 2890): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 2890): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 2890): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 2890): VFY: replacing opcode 0x6e at 0x0008
I/Icing   ( 1332): Indexing done DAD01F3A9BA107296FD295581C27F6C1449145D9
I/Icing   ( 1332): Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
W/dalvikvm( 2890): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2890): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 2890): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 2890): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 2890): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 2890): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 2890): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 2890): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 2890): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 2890): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 2890): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 2890): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 2890): CordovaWebView is running on device made by: LGE
D/dalvikvm(  757): GC_CONCURRENT freed 162K, 52% free 25603K/52836K, paused 4ms+5ms, total 74ms
,I/Icing   ( 1332): Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
I/ActivityManager(  757): Killing 2631:com.android.chrome/u0a31 (adj 15): empty #17
D/OpenGLRenderer( 2890): Enabling debug mode 0
W/AwContents( 2890): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  757): Displayed com.test.thalitest/.MainActivity: +337ms
D/dalvikvm( 2890): GC_CONCURRENT freed 220K, 2% free 16867K/17120K, paused 2ms+2ms, total 18ms
D/JsMessageQueue( 2890): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 2890): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4262fa98
D/dalvikvm( 2890): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4262fa98
D/jxcore_app_log( 2890): JniHelper::setJavaVM(0x41510f00), pthread_self() = 1983873048
D/JX-Cordova( 2890): jxcore cordova android initializing
D/dalvikvm( 2890): GC_CONCURRENT freed 236K, 2% free 17142K/17408K, paused 1ms+1ms, total 10ms
D/dalvikvm( 2890): WAIT_FOR_CONCURRENT_GC blocked 3ms
D/dalvikvm( 2890): WAIT_FOR_CONCURRENT_GC blocked 3ms
D/dalvikvm( 2890): GC_CONCURRENT freed 159K, 2% free 17485K/17684K, paused 1ms+1ms, total 10ms
D/dalvikvm( 2890): WAIT_FOR_CONCURRENT_GC blocked 4ms
D/dalvikvm( 2890): WAIT_FOR_CONCURRENT_GC blocked 4ms
D/dalvikvm( 2890): GC_CONCURRENT freed 157K, 2% free 17828K/18028K, paused 1ms+0ms, total 12ms
D/dalvikvm( 2890): WAIT_FOR_CONCURRENT_GC blocked 7ms
D/dalvikvm( 2890): WAIT_FOR_CONCURRENT_GC blocked 6ms
D/dalvikvm( 2890): GC_CONCURRENT freed 154K, 2% free 18172K/18372K, paused 1ms+2ms, total 16ms
D/dalvikvm( 2890): WAIT_FOR_CONCURRENT_GC blocked 9ms
D/dalvikvm( 2890): WAIT_FOR_CONCURRENT_GC blocked 7ms
D/dalvikvm( 2890): GC_CONCURRENT freed 159K, 2% free 18508K/18716K, paused 1ms+1ms, total 13ms
D/dalvikvm( 2890): WAIT_FOR_CONCURRENT_GC blocked 1ms
D/dalvikvm( 2890): WAIT_FOR_CONCURRENT_GC blocked 7ms
D/dalvikvm( 2890): GC_CONCURRENT freed 176K, 2% free 18915K/19144K, paused 1ms+2ms, total 16ms
D/dalvikvm( 2890): WAIT_FOR_CONCURRENT_GC blocked 9ms
D/dalvikvm( 2890): WAIT_FOR_CONCURRENT_GC blocked 10ms
D/dalvikvm( 2890): GC_CONCURRENT freed 218K, 2% free 19413K/19688K, paused 1ms+1ms, total 15ms
D/dalvikvm( 2890): WAIT_FOR_CONCURRENT_GC blocked 6ms
D/dalvikvm( 2890): WAIT_FOR_CONCURRENT_GC blocked 10ms
D/dalvikvm( 2890): GC_CONCURRENT freed 277K, 2% free 20013K/20352K, paused 2ms+1ms, total 23ms
D/dalvikvm( 2890): WAIT_FOR_CONCURRENT_GC blocked 15ms
D/dalvikvm( 2890): WAIT_FOR_CONCURRENT_GC blocked 13ms
D/dalvikvm( 2890): GC_CONCURRENT freed 325K, 2% free 20758K/21152K, paused 1ms+2ms, total 24ms
D/dalvikvm( 2890): WAIT_FOR_CONCURRENT_GC blocked 16ms
D/dalvikvm( 2890): WAIT_FOR_CONCURRENT_GC blocked 15ms
D/dalvikvm( 2890): GC_CONCURRENT freed 396K, 3% free 21674K/22144K, paused 0ms+1ms, total 22ms
D/dalvikvm( 2890): WAIT_FOR_CONCURRENT_GC blocked 18ms
D/dalvikvm( 2890): WAIT_FOR_CONCURRENT_GC blocked 19ms
D/dalvikvm( 2890): GC_FOR_ALLOC freed 972K, 5% free 22221K/23260K, paused 20ms, total 20ms
,D/dalvikvm( 2890): GC_FOR_ALLOC freed 966K, 6% free 22384K/23792K, paused 33ms, total 34ms
,D/dalvikvm( 2890): GC_FOR_ALLOC freed 880K, 8% free 22544K/24268K, paused 20ms, total 21ms
,I/dalvikvm-heap( 2890): Grow heap (frag case) to 22.737MB for 728606-byte allocation
,D/dalvikvm( 2890): GC_FOR_ALLOC freed 2K, 7% free 23253K/24980K, paused 19ms, total 19ms
,D/dalvikvm( 2890): GC_FOR_ALLOC freed 1277K, 9% free 22799K/24980K, paused 19ms, total 19ms
,I/dalvikvm-heap( 2890): Grow heap (frag case) to 23.333MB for 1092904-byte allocation
,D/dalvikvm( 2890): GC_FOR_ALLOC freed 717K, 12% free 23149K/26048K, paused 20ms, total 20ms
,D/dalvikvm( 2890): GC_FOR_ALLOC freed 1244K, 11% free 23206K/26048K, paused 27ms, total 28ms
,I/dalvikvm-heap( 2890): Grow heap (frag case) to 24.252MB for 1639352-byte allocation
,D/dalvikvm( 2890): GC_FOR_ALLOC freed 24K, 11% free 24782K/27652K, paused 25ms, total 25ms
,D/dalvikvm( 2890): GC_FOR_ALLOC freed 2991K, 14% free 23823K/27652K, paused 24ms, total 24ms
,I/dalvikvm-heap( 2890): Grow heap (frag case) to 25.636MB for 2459024-byte allocation
,D/dalvikvm( 2890): GC_FOR_ALLOC freed 70K, 13% free 26155K/30056K, paused 21ms, total 21ms
,D/dalvikvm( 2890): GC_CONCURRENT freed 1860K, 19% free 24596K/30056K, paused 2ms+5ms, total 41ms
,D/dalvikvm( 2890): GC_CONCURRENT freed 2524K, 18% free 24707K/30056K, paused 1ms+3ms, total 36ms
D/dalvikvm( 2890): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/dalvikvm( 2890): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 2890): GC_FOR_ALLOC freed 367K, 19% free 24616K/30056K, paused 22ms, total 22ms
,I/dalvikvm-heap( 2890): Grow heap (frag case) to 27.583MB for 3688532-byte allocation
,D/dalvikvm( 2890): GC_FOR_ALLOC freed 5K, 17% free 28213K/33660K, paused 23ms, total 23ms
,D/dalvikvm( 2890): GC_CONCURRENT freed 2689K, 24% free 25859K/33660K, paused 5ms+3ms, total 40ms
,D/dalvikvm( 2890): GC_FOR_ALLOC freed 782K, 24% free 25690K/33660K, paused 20ms, total 21ms
,W/jxcore-log( 2890): Initializing JXcore engine
,W/jxcore-log( 2890): JXcore engine is ready
,D/dalvikvm( 2890): GC_CONCURRENT freed 5447K, 31% free 23232K/33660K, paused 2ms+0ms, total 20ms
,D/dalvikvm( 2890): WAIT_FOR_CONCURRENT_GC blocked 17ms
,W/jxcore-log( 2890): Starting JXcore engine
,W/jxcore-log( 2890): Platform android
W/jxcore-log( 2890): 
,W/jxcore-log( 2890): Process ARCH arm
W/jxcore-log( 2890): 
,I/jxcore-log( 2890): JXcore Cordova bridge is ready!
I/jxcore-log( 2890): 
,W/jxcore-log( 2890): JXcore engine is started
,I/chromium( 2890): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 2890): Skipped 157 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 2890): Toggling radios to true
I/jxcore-log( 2890): 
,D/BluetoothAdapter( 2890): enable(): BT is already enabled..!
,I/jxcore-log( 2890): Radios toggled
I/jxcore-log( 2890): 
,I/jxcore-log( 2890): My device name is: LGE-Nexus 5
I/jxcore-log( 2890): 
D/WifiService(  757): setWifiEnabled: true pid=2890, uid=10108
,I/wpa_supplicant(  924): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/CommandListener(  177): Clearing all IP addresses on wlan0
,D/ConnectivityService(  757): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityService(  757): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  757): Attempting to switch to mobile
,D/ConnectivityService(  757): Attempting to switch to BLUETOOTH_TETHER
,D/NetUtils(  757): android_net_utils_resetConnections in env=0x75f22f48 clazz=0x5d600001 iface=wlan0 mask=0x3
D/ConnectivityService(  757): resetConnections(wlan0, 3)
,V/NativeCrypto( 1078): Read error: ssl=0x79296f50: I/O error during system call, Connection timed out
,V/NativeCrypto( 1078): SSL shutdown failed: ssl=0x79296f50: I/O error during system call, Broken pipe
,D/CommandListener(  177): Clearing all IP addresses on wlan0
,D/Nat464Xlat(  757): requiresClat: netType=1, hasIPv4Address=false
,D/ConnectivityService(  757): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  757): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  757): handleInetConditionChange: no active default network - ignore
,D/ConnectivityService(  757): handleInetConditionChange: no active default network - ignore
,I/wpa_supplicant(  924): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/wpa_supplicant(  924): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant(  924): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  924): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
,E/WifiStateMachine(  757): scanCount==0 - aborting
,D/ConnectivityService(  757): handleInetConditionChange: no active default network - ignore
,D/Tethering(  757): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  757): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  757): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/dalvikvm( 1258): GC_CONCURRENT freed 355K, 3% free 16741K/17132K, paused 3ms+0ms, total 14ms
,I/SystemUpdateService( 1332): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1332): onCreate
,D/SystemUpdateService( 1332): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1332): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1332): num queued entries: 0
,I/SystemUpdateService( 1332): active receiver: enabled
,I/SystemUpdateService( 1332): Already downloaded, skipping offpeak checks.
,I/Babel   ( 1963): connection state changed from CONNECTED to DISCONNECTED
,I/iu.UploadsManager( 1332): num updated entries: 0
I/SystemUpdateService( 1332): network: null; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1332): now status is 0 (complete)
I/SystemUpdateService( 1332): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1332): file has been verified
,I/SystemUpdateService( 1332): OTA package size = 2571501
,I/iu.SyncManager( 1332): NEXT; no task
,D/dalvikvm(  181): GC_EXPLICIT freed 42K, 1% free 16698K/16772K, paused 1ms+1ms, total 16ms
I/ActivityManager(  757): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService$Receiver: pid=3015 uid=10031 gids={50031, 3003, 1028, 1015}
,I/SystemUpdateService( 1332): showing system update notification
,D/dalvikvm(  181): GC_EXPLICIT freed <1K, 1% free 16698K/16772K, paused 1ms+2ms, total 16ms
,D/SystemUpdateService( 1332): onDestroy
,D/WifiStateMachine(  757): VerifyingLinkState enter
D/WifiStateMachine(  757): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  757): CaptivePortalCheckState enter
,D/dalvikvm(  181): GC_EXPLICIT freed <1K, 1% free 16698K/16772K, paused 1ms+1ms, total 13ms
,D/WifiStateMachine(  757): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService(  757): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  757): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService(  757): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService(  757): Unexpected mtu value: android.net.wifi.WifiStateTracker@42ad96f8
,D/Nat464Xlat(  757): requiresClat: netType=1, hasIPv4Address=true
,D/dalvikvm( 3015): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 3015): VFY: unable to resolve instance field 68
D/dalvikvm( 3015): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 3015): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 3015): DexOpt: unable to optimize instance field ref 0x0044 at 0x11 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
D/dalvikvm( 3015): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
,I/dalvikvm( 3015): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/BuildInfo;.hasLanguageApkSplits
,D/dalvikvm( 3015): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
W/dalvikvm( 3015): VFY: unable to resolve instance field 68
,D/dalvikvm( 3015): VFY: replacing opcode 0x54 at 0x0011
,D/dalvikvm( 3015): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 3015): DexOpt: unable to optimize instance field ref 0x0044 at 0x16 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 3015): DexOpt: couldn't find field Landroid/content/pm/PackageInfo;.splitNames
I/dalvikvm( 3015): DexOpt: unable to optimize instance field ref 0x0044 at 0x1b in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
D/dalvikvm( 3015): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 3015): DexOpt: unable to optimize instance field ref 0x003b at 0x25 in Lorg/chromium/base/library_loader/LibraryLoader;.getLibraryApkPath
I/ActivityManager(  757): Killing 1706:com.google.android.calendar/u0a28 (adj 15): empty #17
,D/ConnectivityService(  757): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  757): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService(  757):    car=removed=[] added=[fe80::5255:27ff:fef0:fff0/64,]
,D/Nat464Xlat(  757): requiresClat: netType=1, hasIPv4Address=true
,D/ConnectivityService(  757): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/Tethering(  757): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  757): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SystemUpdateService( 1332): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1332): onCreate
,D/SystemUpdateService( 1332): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1332): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1332): num queued entries: 0
,I/jxcore-log( 2890): Test app app.js loaded
I/jxcore-log( 2890): 
,I/Choreographer( 2890): Skipped 382 frames!  The application may be doing too much work on its main thread.
,I/iu.UploadsManager( 1332): num updated entries: 0
,I/iu.SyncManager( 1332): NEXT; no task
,I/SystemUpdateService( 1332): active receiver: enabled
,I/SystemUpdateService( 1332): Already downloaded, skipping offpeak checks.
,I/chromium( 2890): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/SystemUpdateService( 1332): network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false; metered: false; mobile allowed: true; isAltModeWearable: false; isWifiNeededForAltModeWearableDevice: false
I/SystemUpdateService( 1332): now status is 0 (complete)
I/SystemUpdateService( 1332): processDownloadedFile /cache/update.zip
,I/SystemUpdateService( 1332): file has been verified
,I/SystemUpdateService( 1332): OTA package size = 2571501
,I/SystemUpdateService( 1332): showing system update notification
,D/SystemUpdateService( 1332): onDestroy
,I/dalvikvm(  994): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm(  994): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm(  994): VFY: replacing opcode 0x6e at 0x003d
,I/Babel   ( 1963): connection state changed from DISCONNECTED to CONNECTED
,D/dalvikvm( 2392): GC_CONCURRENT freed 356K, 3% free 17673K/18060K, paused 2ms+1ms, total 22ms
,D/ConnectivityService(  757): handleInetConditionHoldEnd: net=1, condition=0, published condition=100
,D/dalvikvm( 1205): GC_CONCURRENT freed 1255K, 7% free 17889K/19176K, paused 3ms+0ms, total 14ms
,D/dalvikvm( 1078): GC_CONCURRENT freed 366K, 4% free 17937K/18640K, paused 5ms+3ms, total 40ms
,D/dalvikvm( 2358): GC_CONCURRENT freed 160K, 3% free 17429K/17792K, paused 2ms+1ms, total 12ms
,D/Finsky  ( 2358): [1] 5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  757): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=3113 uid=10071 gids={50071, 3003, 1028, 1015}
,I/dalvikvm( 3113): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method epz.a
,W/dalvikvm( 3113): VFY: unable to resolve virtual method 2853: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 3113): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 3113): GC_CONCURRENT freed 361K, 3% free 16850K/17240K, paused 3ms+1ms, total 18ms
,D/dalvikvm( 3113): WAIT_FOR_CONCURRENT_GC blocked 4ms
D/dalvikvm( 3113): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 3113): WAIT_FOR_CONCURRENT_GC blocked 5ms
,D/dalvikvm( 3113): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3113): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3113): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 3113): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 3113): VFY: unable to resolve instance field 36
,D/dalvikvm( 3113): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 3113): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 3113): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 3113): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 3113): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 3113): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 3113): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42680968
D/dalvikvm( 3113): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42680968
,D/dalvikvm( 3113): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42680968, skipping init
,D/dalvikvm( 3113): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42680968
D/dalvikvm( 3113): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42680968
,V/JNIHelp ( 3113): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 3113): GC_CONCURRENT freed 283K, 2% free 17152K/17352K, paused 2ms+1ms, total 15ms
D/dalvikvm( 3113): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42680968
D/dalvikvm( 3113): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42680968
D/dalvikvm( 3113): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42680968
,D/dalvikvm( 3113): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42680968
,I/dalvikvm( 3113): Could not find method android.app.Activity.finishAfterTransition, referenced from method cf.onBackPressed
,W/dalvikvm( 3113): VFY: unable to resolve virtual method 2379: Landroid/app/Activity;.finishAfterTransition ()V
,D/dalvikvm( 3113): VFY: replacing opcode 0x6e at 0x0012
,D/dalvikvm( 3113): GC_CONCURRENT freed 240K, 2% free 17313K/17588K, paused 3ms+0ms, total 11ms
,I/ProviderInstaller( 3113): Installed default security provider GmsCore_OpenSSL
,E/YouTube MDX( 3113): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/dalvikvm( 3113): GC_CONCURRENT freed 347K, 3% free 17480K/17856K, paused 3ms+2ms, total 19ms
,D/dalvikvm( 3113): WAIT_FOR_CONCURRENT_GC blocked 7ms
,D/dalvikvm( 3113): WAIT_FOR_CONCURRENT_GC blocked 7ms
,D/dalvikvm( 3113): GC_CONCURRENT freed 236K, 2% free 17754K/18020K, paused 3ms+2ms, total 14ms
,D/dalvikvm( 3113): WAIT_FOR_CONCURRENT_GC blocked 3ms
,D/dalvikvm( 3113): WAIT_FOR_CONCURRENT_GC blocked 3ms
,D/dalvikvm( 3113): WAIT_FOR_CONCURRENT_GC blocked 5ms
D/ConnectivityService(  757): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/dalvikvm( 3113): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 3113): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 3113): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 3113): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
,W/dalvikvm( 3113): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 3113): VFY: replacing opcode 0x71 at 0x004e
,D/dalvikvm( 3113): GC_CONCURRENT freed 283K, 2% free 17981K/18292K, paused 2ms+2ms, total 22ms
,D/dalvikvm( 3113): WAIT_FOR_CONCURRENT_GC blocked 2ms
,D/dalvikvm( 3113): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/dalvikvm( 3113): DexOpt: --- BEGIN 'ads1029888369.jar' (bootstrap=0) ---
,W/InstanceID/Rpc( 3113): Found 10007
,I/dalvikvm( 3113): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method asf.getActivityBanner
W/dalvikvm( 3113): VFY: unable to resolve virtual method 2824: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 3113): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 3113): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method asf.getActivityBanner
W/dalvikvm( 3113): VFY: unable to resolve virtual method 2825: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 3113): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 3113): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method asf.getApplicationBanner
W/dalvikvm( 3113): VFY: unable to resolve virtual method 2832: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 3113): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 3113): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method asf.getApplicationBanner
W/dalvikvm( 3113): VFY: unable to resolve virtual method 2833: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 3113): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm( 3113): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method asf.getLeanbackLaunchIntentForPackage
,W/dalvikvm( 3113): VFY: unable to resolve virtual method 2849: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 3113): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 3113): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method asf.getPackageInstaller
W/dalvikvm( 3113): VFY: unable to resolve virtual method 2853: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 3113): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 3113): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method asf.getUserBadgedDrawableForDensity
W/dalvikvm( 3113): VFY: unable to resolve virtual method 2869: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 3113): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 3113): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method asf.getUserBadgedIcon
W/dalvikvm( 3113): VFY: unable to resolve virtual method 2870: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 3113): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm( 3113): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method asf.getUserBadgedLabel
W/dalvikvm( 3113): VFY: unable to resolve virtual method 2871: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
,D/dalvikvm( 3113): VFY: replacing opcode 0x6e at 0x0002
,D/dalvikvm( 3161): DexOpt: load 6ms, verify+opt 5ms, 188892 bytes
,D/dalvikvm( 3113): DexOpt: --- END 'ads1029888369.jar' (success) ---
,D/dalvikvm( 3113): DEX prep '/data/data/com.google.android.youtube/cache/ads1029888369.jar': unzip in 0ms, rewrite 58ms
,D/dalvikvm( 3113): GC_CONCURRENT freed 375K, 3% free 18119K/18524K, paused 4ms+1ms, total 30ms
,D/dalvikvm( 3113): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 3113): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/dalvikvm( 3113): Could not find method android.os.PowerManager.isDeviceIdleMode, referenced from method com.google.android.libraries.youtube.net.gcm.service.YouTubeGcmTaskService.a
W/dalvikvm( 3113): VFY: unable to resolve virtual method 4039: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
D/dalvikvm( 3113): VFY: replacing opcode 0x6e at 0x0008
I/dalvikvm( 3113): Could not find method android.content.Context.getSystemService, referenced from method com.google.android.libraries.youtube.net.gcm.service.YouTubeGcmTaskService.a
W/dalvikvm( 3113): VFY: unable to resolve virtual method 2688: Landroid/content/Context;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 3113): VFY: replacing opcode 0x6e at 0x0011
,D/dalvikvm( 3113): GC_CONCURRENT freed 329K, 2% free 18259K/18620K, paused 2ms+2ms, total 17ms
,D/dalvikvm( 3113): GC_CONCURRENT freed 488K, 3% free 18293K/18812K, paused 4ms+3ms, total 30ms
,D/dalvikvm( 3113): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 3113): GC_CONCURRENT freed 370K, 3% free 18371K/18812K, paused 2ms+3ms, total 21ms
,I/ActivityManager(  757): Killing 2662:com.google.android.keep/u0a52 (adj 15): empty #17
,D/dalvikvm( 1078): GC_CONCURRENT freed 438K, 4% free 17914K/18640K, paused 5ms+1ms, total 35ms
,D/PerfProfileCollectorService( 1332): User is not opt-in to Usage & Diagnostics.
,D/PerfProfileCollectorService( 1332): removeStateFiles() called
,D/PerfProfileCollectorService( 1332): User is not opt-in to Usage & Diagnostics.
,D/dalvikvm( 1332): GC_CONCURRENT freed 611K, 4% free 19098K/19740K, paused 3ms+2ms, total 22ms
,D/CaptivePortalTracker(  757): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
,D/ConnectivityService(  757): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker(  757): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker(  757): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  757): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  757): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  757): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService(  757): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/PowerManagerService(  757): Going to sleep due to screen timeout...
,I/Adreno-EGL(  757): <qeglDrvAPI_eglInitialize:320>: EGL 1.4 QUALCOMM Build: I0404c4692afb8623f95c43aeb6d5e13ed4b30ddbDate: 11/06/13
,D/SurfaceFlinger(  180): Screen released, type=0 flinger=0xb8d0a450
,D/qdhwcomposer(  180): hwc_blank: Blanking display: 0
,D/qdhwcomposer(  180): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  757): Excessive delay in blankDisplay() while turning screen off: 290ms
,V/KeyguardServiceDelegate(  757): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$17@42e49780)
,V/KeyguardServiceDelegate(  757): **** SHOWN CALLED ****
I/WindowManager(  757): No lock screen! windowToken=null
,D/NfcService( 1041): NFC-C OFF
,I/rmt_storage(  176): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb738c160
I/rmt_storage(  176): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  176): wakelock acquired: 1, error no: 2
,I/rmt_storage(  176): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1221017904)
,I/rmt_storage(  176): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  176): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  176): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1221017904) wakelock released: 1, error no: 0
I/rmt_storage(  176): 
,I/rmt_storage(  176): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb738c160
,D/dalvikvm( 1078): GC_CONCURRENT freed 406K, 4% free 17900K/18640K, paused 2ms+1ms, total 24ms
,D/dalvikvm(  757): GC_EXPLICIT freed 1605K, 51% free 25791K/52528K, paused 3ms+9ms, total 80ms
,I/VacuumService(  994): Vacuum at: now=1452688756424 tag=VacuumService
,D/dalvikvm( 1078): GC_CONCURRENT freed 401K, 4% free 17899K/18640K, paused 1ms+1ms, total 15ms
,I/jxcore-log( 2890): --= Surplus to requirements =--
I/jxcore-log( 2890): 
,I/jxcore-log( 2890): ****TEST TOOK:  ms ****
I/jxcore-log( 2890): 
,I/jxcore-log( 2890): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2890): 
,D/AndroidRuntime( 3308): 
D/AndroidRuntime( 3308): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3308): CheckJNI is OFF
,D/dalvikvm( 3308): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 3308): Added shared lib libjavacore.so 0x0
D/dalvikvm( 3308): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 3308): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 3308): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/dalvikvm( 3308): Note: class Landroid/app/ActivityManagerNative; has 179 unimplemented (abstract) methods
,D/AndroidRuntime( 3308): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  757): Force stopping com.test.thalitest appid=10108 user=-1: uninstall pkg
,I/ActivityManager(  757): Killing 2890:com.test.thalitest/u0a108 (adj 0): stop com.test.thalitest
,I/ActivityManager(  757):   Force finishing activity ActivityRecord{44838870 u0 com.test.thalitest/.MainActivity t2}
,I/WindowState(  757): WIN DEATH: Window{42bc7158 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings(  757): Skipping PackageSetting{426f6c30 com.example.hello/10116} due to missing metadata
,I/ActivityManager(  757): Force stopping com.test.thalitest appid=10108 user=0: pkg removed
,D/dalvikvm( 1332): GC_EXPLICIT freed 273K, 4% free 18991K/19740K, paused 1ms+2ms, total 24ms
,D/dalvikvm( 1205): GC_EXPLICIT freed 337K, 8% free 17796K/19176K, paused 1ms+2ms, total 26ms
,D/dalvikvm( 1059): GC_EXPLICIT freed 1280K, 7% free 26148K/27920K, paused 1ms+2ms, total 20ms
,I/InputReader(  757): Reconfiguring input devices.  changes=0x00000010
,I/Launcher( 1059): Deferring update until onResume
I/PackageManager(  757):   Action: "android.intent.action.SENDTO"
I/PackageManager(  757):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  757):   Scheme: "sms"
I/PackageManager(  757): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/Launcher( 1059): Deferring update until onResume
,I/PackageManager(  757):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  757):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  757):   Scheme: "smsto"
,W/GeofencerStateMachine(  994): Ignoring removeGeofence because network location is disabled.
,D/VoicemailCleanupService( 2338): Cleaning up data for package: com.test.thalitest
I/PackageManager(  757): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  757):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  757):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  757):   Scheme: "mms"
,D/dalvikvm(  757): GC_EXPLICIT freed 734K, 51% free 25770K/52528K, paused 3ms+5ms, total 84ms
,D/dalvikvm(  757): WAIT_FOR_CONCURRENT_GC blocked 79ms
I/PackageManager(  757): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/dalvikvm( 2338): GC_CONCURRENT freed 259K, 2% free 17036K/17328K, paused 6ms+1ms, total 15ms
,I/LatinIME:LogUtils(  979): Dictionary info: dictionary = main:en_us ; version = 44 ; date = 1393228158
,D/dalvikvm(  757): GC_EXPLICIT freed 101K, 52% free 25677K/52528K, paused 4ms+4ms, total 51ms
,I/PackageManager(  757):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  757):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  757):   Scheme: "mmsto"
I/PackageManager(  757): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/PackageManager(  757):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  757):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  757): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
I/PackageManager(  757):   Scheme: "sms"
,I/PackageManager(  757):   Action: "android.intent.action.SENDTO"
I/PackageManager(  757):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  757):   Scheme: "smsto"
I/PackageManager(  757): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,D/AndroidRuntime( 3308): Shutting down VM
,D/dalvikvm( 3308): GC_CONCURRENT freed 94K, 15% free 558K/656K, paused 0ms+0ms, total 1ms
,I/PackageManager(  757):   Action: "android.intent.action.SENDTO"
I/PackageManager(  757):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  757):   Scheme: "mms"
I/PackageManager(  757): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,I/Icing.InternalIcingCorporaProvider( 1205): Updating corpora: A: com.test.thalitest, C: MAYBE
D/BackupManagerService(  757): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  757): removePackageParticipantsLocked: uid=10108 #1
,I/PackageManager(  757):   Action: "android.intent.action.SENDTO"
I/PackageManager(  757):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  757):   Scheme: "mmsto"
I/PackageManager(  757): Adding preferred activity ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.phone.BabelHomeActivity} for user 0 :
,W/Launcher( 1059): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@42629ba8 new=com.google.android.velvet.VelvetApplication@42629ba8
,I/ActivityManager(  757): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3345 uid=1000 gids={41000, 1028, 1015, 3002, 3001, 3003}
,W/ContextImpl( 3345): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1487 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2407 
,I/ActivityManager(  757): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ActivityManager(  757): Resuming delayed broadcast
,I/ActivityManager(  757): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/ActivityManager(  757): Resuming delayed broadcast
,I/ActivityManager(  757): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 1332): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1332): Clearing selected account for com.test.thalitest
,W/Binder  (  979): Caught a RuntimeException from the binder stub implementation.
W/Binder  (  979): java.lang.NullPointerException
W/Binder  (  979): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  (  979): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  (  979): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  (  979): 	at dalvik.system.NativeStart.run(Native Method)
,W/InputMethodManagerService(  757): Got RemoteException sending setActive(false) notification to pid 2890 uid 10108
I/Icing.InternalIcingCorporaProvider( 1205): UpdateCorporaTask done [took 113 ms] updated apps [took 113 ms] 
I/LocationSettingsChecker( 1332): Removing dialog suppression flag for package com.test.thalitest
,D/gH_CompatibleDatabase( 1332): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1332): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1332): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 1332): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,W/BaseAppContext( 1332): Using Auth Proxy for data requests.
,W/BaseAppContext( 1332): Using Auth Proxy for data requests.
,D/gH_CompatibleDatabase( 1332): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1332): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1332): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/dalvikvm(  994): GC_CONCURRENT freed 510K, 4% free 18715K/19388K, paused 2ms+3ms, total 22ms
,D/gH_CompatibleDatabase( 1332): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1332): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1332): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1332): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1332): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1332): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/GMPM-SVC( 1332): App measurement is starting up, version: 8489
,I/GMPM-SVC( 1332): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,D/dalvikvm( 1332): GC_CONCURRENT freed 557K, 4% free 19212K/19860K, paused 3ms+3ms, total 25ms
,I/Icing   ( 1332): doRemovePackageData com.test.thalitest
,E/SQLiteLog( 1332): (3850) statement aborts at 26: [DELETE FROM user_attributes WHERE app_id=?] disk I/O error
,E/GMPM-SVC( 1332): Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.e(SourceFile:1776)
,E/SharedPreferencesImpl( 1332): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,W/DriveInitializer( 1332): Background init thread started
,W/DriveInitializer( 1332): Awaiting to be initialized
,E/SQLiteLog( 1332): (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock163] disk I/O error
,E/DocListDatabase( 1332): Failed to delete from ContentFileDeletionLock163 table
E/DocListDatabase( 1332): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1332): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1332): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1332): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1332): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1332): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/DocListDatabase( 1332): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 1332): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/DocListDatabase( 1332): 	at com.google.android.gms.drive.t.run(SourceFile:62)
W/DriveInitializer( 1332): Background init thread ended
W/dalvikvm( 1332): threadid=26: thread exiting with uncaught exception (group=0x415d7ba8)
,E/SQLiteLog( 1332): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DriveAsyncService( 1332): disk I/O error (code 3850)
E/DriveAsyncService( 1332): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1332): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1332): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1332): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1332): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1332): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1332): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1332): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1332): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1332): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1332): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1332): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1332): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1332): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1332): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1332): 	at java.lang.Thread.run(Thread.java:841)
,I/Process ( 1332): Sending signal. PID: 1332 SIG: 9
E/AndroidRuntime( 1332): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 1332): Process: com.google.android.gms, PID: 1332
E/AndroidRuntime( 1332): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1332): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1332): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1332): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1332): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1332): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1497)
E/AndroidRuntime( 1332): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/AndroidRuntime( 1332): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/AndroidRuntime( 1332): 	at com.google.android.gms.drive.t.run(SourceFile:62)
,E/DropBoxManagerService(  757): Can't write: system_app_crash
E/DropBoxManagerService(  757): java.io.FileNotFoundException: /data/system/dropbox/drop87.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  757): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  757): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  757): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  757): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  757): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  757): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10018)
E/DropBoxManagerService(  757): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  757): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  757): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  757): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  757): 	... 5 more
,I/ActivityManager(  757): Process com.google.android.gms (pid 1332) has died.
W/ActivityManager(  757): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
,I/ActivityManager(  757): Resuming delayed broadcast
W/ActivityManager(  757): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
W/ActivityManager(  757): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
W/ActivityManager(  757): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10999ms
,W/ActivityManager(  757): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 10999ms

```
