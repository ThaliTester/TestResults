#### Test 635253937ae73fc_thali01_samsung-SM-A500FU Logs


```
--------- beginning of system
03-21 08:36:09.515  1018  2853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aL.onChange:-1 com.android.server.ssrm.aL.<init>:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 
03-21 08:36:09.525  1018  2853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.aJ.cP:-1 com.android.server.ssrm.aJ.<init>:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 
03-21 08:36:09.525  1018  2853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 com.android.server.ssrm.ad.b:-1 com.android.server.ssrm.ad.onBootCompleted:-1 com.android.server.ssrm.ad.c:-1 com.android.server.ssrm.ae.handleMessage:-1 
03-21 08:36:09.545  1018  1314 D ActivityManager: getContentProviderImpl callerProcessName:com.android.bluetooth, calleePkgName: com.android.email
03-21 08:36:09.545  1018  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:09.545  1018  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:09.545  1018  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:09.545  1018  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
--------- beginning of main
03-21 08:36:09.555  2900  2900 E Zygote  : MountEmulatedStorage()
03-21 08:36:09.555  2900  2900 E Zygote  : v2
03-21 08:36:09.555  2900  2900 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-21 08:36:09.555  2900  2900 I libpersona: KNOX_SDCARD checking this for 10145
03-21 08:36:09.555  2900  2900 I libpersona: KNOX_SDCARD not a persona
03-21 08:36:09.565  2900  2900 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 08:36:09.565  2900  2900 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 08:36:09.565  1018  1314 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=2900 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
03-21 08:36:09.575  1018  2853 I i       : No model
03-21 08:36:09.585  1018  2853 D FactoryTest: Not factory mode
03-21 08:36:09.585  1018  2853 D w       : isUserBuild = true
03-21 08:36:09.585  1018  2853 D FactoryTest: Not factory mode. isFactoryMode() returend false
03-21 08:36:09.595  1018  2853 D SSRM:aZ : Alarm set to refresh battery stats
03-21 08:36:09.595  1018  2853 D SSRM:aZ : Updating Threshold Value.. isSystemReady: true
03-21 08:36:09.605  1018  2853 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,03-21 08:36:09.605  2900  2900 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 08:36:09.605  2900  2900 D ActivityThread: Added TimaKeyStore provider
03-21 08:36:09.645  2900  2900 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-21 08:36:09.645  2900  2900 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-21 08:36:09.645  2900  2900 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-21 08:36:09.645  2900  2900 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-21 08:36:09.645  2900  2900 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-21 08:36:09.705  1018  1095 E SmartFaceService: onReceive: android.intent.action.BOOT_COMPLETED
03-21 08:36:09.705  1018  1095 D SmartFaceIndicator: no icon
03-21 08:36:09.705  1018  1095 E SmartFaceService: mActiveServiceType: 0
03-21 08:36:09.705  1018  1095 E SmartFaceService: mLightIntensityEnough: true mLux: 0.0
03-21 08:36:09.705  1018  1095 D Stay/Rotation Worker: updateClientsDone. def. do nothing.
03-21 08:36:09.705  1018  1095 E SmartFaceService: Service Type to Worker: 0
03-21 08:36:09.705  1018  1095 E SmartFaceService: Last Active clients:0 Current Active clients: 0
03-21 08:36:09.705  1018  1095 E SmartFaceService: Last Smart Pause clients: 0 Current Smart Pause clients: 0
03-21 08:36:09.705  1018  2853 D SSRM:n  : SIOP:: AP = 360
03-21 08:36:09.715  1018  1018 D CrashAnrDetector: Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
03-21 08:36:09.715  1018  1018 D CrashAnrDetector: Hardware: MSM8916
03-21 08:36:09.715  1018  1018 D CrashAnrDetector: Revision: 2
03-21 08:36:09.715  1018  1018 D CrashAnrDetector: Bootloader: A500FUXXU1BOH2
03-21 08:36:09.715  1018  1018 D CrashAnrDetector: Radio: unknown
03-21 08:36:09.715  1018  1018 D CrashAnrDetector: Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
03-21 08:36:09.715  1018  1018 D CrashAnrDetector: 
03-21 08:36:09.715  1018  1018 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-21 08:36:09.715  1018  1018 D CrashAnrDetector: Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys'
03-21 08:36:09.715  1018  1018 D CrashAnrDetector: Revision: '2'
03-21 08:36:09.715  1018  1018 D CrashAnrDetector: ABI: 'arm'
03-21 08:36:09.715  1018  1018 D CrashAnrDetector: pid: 4101, tid: 4302, name: Thread-633  >>> com.test.thalitest <<<
03-21 08:36:09.715  1018  1018 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:     r0 00000000  r1 9d60e7dc  r2 00000002  r3 00000000
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:     r4 b7919d00  r5 00000000  r6 b7919590  r7 bafd6340
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:     r8 b73dfedc  r9 b7919d00  sl b7919568  fp 9d60e7d4
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:     ip ffffffff  sp 9d60e7c4  lr 9b43bb30  pc 9b43ba34  cpsr 60000010
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:     d0  0000000000000000  d1  0000000000000000
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:     d2  0000000000000000  d3  0000000000000000
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:     d4  0000000000000000  d5  0000000000000000
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:     d6  0000000000000000  d7  0000000000000000
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:     d16 000027ab000027ab  d17 000027ab00000000
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:     d20 0000000100010001  d21 0000000000000000
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:     d26 0002000100010001  d27 0002000200020002
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:     scr 20000017
03-21 08:36:09.715  1018  1018 D CrashAnrDetector: 
03-21 08:36:09.715  1018  1018 D CrashAnrDetector: backtrace:
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:     #00 pc 003d1a34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:     #01 pc 003d1b2c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:     #02 pc e5943000  <unknown>
03-21 08:36:09.715  1018  1018 D CrashAnrDetector: 
03-21 08:36:09.715  1018  1018 D CrashAnrDetector: stack:
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e744  00000000  
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e748  98afc0a0  [anon:js-gc-heap]
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e74c  b7919d00  [heap]
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e750  00000001  
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e754  98a6e1a8  [anon:js-gc-heap]
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e758  9d60e774  [stack:4302]
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e75c  9b43b12c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e760  00000001  
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e764  00000000  
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e768  b791a830  [heap]
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e76c  00000000  
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e770  00000000  
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e774  b7919d00  [heap]
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e778  b791a830  [heap]
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e77c  9bac7b60  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e780  9d60e7ec  [stack:4302]
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e784  9b442514  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markConservativeStackRoots(JSTracer*, bool)+1308)
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e788  b7919d00  [heap]
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e78c  b7919568  [heap]
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e790  9d616000  /dev/ashmem/dalvik-indirect ref table slots (deleted)
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e794  9d60e7b8  [stack:4302]
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e798  9d60e7b0  [stack:4302]
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e79c  9d60e7bc  [stack:4302]
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e7a0  9b9ee6d4  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e7a4  9d60e7c0  [stack:4302]
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e7a8  00000011  
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e7ac  00000000  
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e7b0  00000001  
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e7b4  b7919d00  [heap]
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e7b8  9811eb50  [anon:js-gc-heap]
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e7bc  b7919590  [heap]
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e7c0  9d60e7d4  [stack:4302]
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:     #00  9d60e7c4  9d60e7d4  [stack:4302]
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e7c8  9d615838  [stack:4302]
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e7cc  bafcdfa0  [heap]
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e7d0  9d60e7ec  [stack:4302]
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e7d4  9b43f06c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::MarkValueRoot(JSTracer*, JS::Value*, char const*)+80)
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:     #01  9d60e7d8  b73dfedc  [heap]
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e7dc  00000000  
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e7e0  b791958c  [heap]
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e7e4  9b96fcd8  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e7e8  9d60e844  [stack:4302]
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d60e7ec  9b443dcc  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markRuntime(JSTracer*, js::gc::GCRuntime::TraceOrMarkRuntime, js::gc::GCRuntime::TraceRootsOrUsedSaved)+1452)
03-21 08:36:09.715  1018  1018 D CrashAnrDetector:          9d6
03-21 08:36:09.715  1018  1018 D CrashAnrDetector: processName:com.test.thalitest
03-21 08:36:09.715  1018  1018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-21 08:36:09.715  1018  1018 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-21 08:36:09.725  1018  1018 D CrashAnrDetector: Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
03-21 08:36:09.725  1018  1018 D CrashAnrDetector: Hardware: MSM8916
03-21 08:36:09.725  1018  1018 D CrashAnrDetector: Revision: 2
03-21 08:36:09.725  1018  1018 D CrashAnrDetector: Bootloader: A500FUXXU1BOH2
03-21 08:36:09.725  1018  1018 D CrashAnrDetector: Radio: unknown
03-21 08:36:09.725  1018  1018 D CrashAnrDetector: Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
03-21 08:36:09.725  1018  1018 D CrashAnrDetector: 
03-21 08:36:09.725  1018  1018 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-21 08:36:09.725  1018  1018 D CrashAnrDetector: Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys'
03-21 08:36:09.725  1018  1018 D CrashAnrDetector: Revision: '2'
03-21 08:36:09.725  1018  1018 D CrashAnrDetector: ABI: 'arm'
03-21 08:36:09.725  1018  1018 D CrashAnrDetector: pid: 3806, tid: 4128, name: Thread-569  >>> com.test.thalitest <<<
03-21 08:36:09.725  1018  1018 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:     r0 00000000  r1 9c296904  r2 00000002  r3 00000000
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:     r4 b885cc98  r5 00000000  r6 b885c528  r7 bb480a28
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:     r8 b8861ad4  r9 b885cc98  sl b885c500  fp 9c2968fc
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:     ip ffffffff  sp 9c2968ec  lr 9d0c1b30  pc 9d0c1a34  cpsr 600f0010
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:     d0  0000000000000000  d1  0000000000000000
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:     d2  0000000000000000  d3  0000000000000000
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:     d4  0000000000000000  d5  0000000000000000
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:     d6  0000000000000000  d7  0000000000000000
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:     d16 0000000000000000  d17 000027ab00000000
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:     d20 0000000100010001  d21 0000000000000000
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:     d26 0002000100010001  d27 0002000200020002
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:     scr 20000013
03-21 08:36:09.725  1018  1018 D CrashAnrDetector: 
03-21 08:36:09.725  1018  1018 D CrashAnrDetector: backtrace:
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:     #00 pc 003d1a34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:     #01 pc 003d1b2c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:     #02 pc e5943000  <unknown>
03-21 08:36:09.725  1018  1018 D CrashAnrDetector: 
03-21 08:36:09.725  1018  1018 D CrashAnrDetector: stack:
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c29686c  00000000  
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c296870  9a1fc0a0  [anon:js-gc-heap]
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c296874  b885cc98  [heap]
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c296878  00000001  
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c29687c  9a119fa0  [anon:js-gc-heap]
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c296880  9c29689c  [stack:4128]
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c296884  9d0c112c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c296888  00000001  
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c29688c  00000000  
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c296890  b885d7c8  [heap]
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c296894  00000000  
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c296898  00000000  
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c29689c  b885cc98  [heap]
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c2968a0  b885d7c8  [heap]
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c2968a4  9d74db60  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c2968a8  9c296914  [stack:4128]
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c2968ac  9d0c8514  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markConservativeStackRoots(JSTracer*, bool)+1308)
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c2968b0  b885cc98  [heap]
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c2968b4  b885c500  [heap]
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c2968b8  9c2aa000  
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c2968bc  9c2968e0  [stack:4128]
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c2968c0  9c2968d8  [stack:4128]
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c2968c4  9c2968e4  [stack:4128]
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c2968c8  9d6746d4  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c2968cc  9c2968e8  [stack:4128]
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c2968d0  00000004  
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c2968d4  00000000  
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c2968d8  00000001  
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c2968dc  b885cc98  [heap]
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c2968e0  99800520  [anon:js-gc-heap]
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c2968e4  b885c528  [heap]
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c2968e8  9c2968fc  [stack:4128]
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:     #00  9c2968ec  9c2968fc  [stack:4128]
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c2968f0  9c2a9838  [stack:4128]
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c2968f4  bb475298  [heap]
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c2968f8  9c296914  [stack:4128]
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c2968fc  9d0c506c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::MarkValueRoot(JSTracer*, JS::Value*, char const*)+80)
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:     #01  9c296900  b8861ad4  [heap]
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c296904  00000000  
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c296908  b885c524  [heap]
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c29690c  9d5f5cd8  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c296910  9c29696c  [stack:4128]
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c296914  9d0c9dcc  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markRuntime(JSTracer*, js::gc::GCRuntime::TraceOrMarkRuntime, js::gc::GCRuntime::TraceRootsOrUsedSaved)+1452)
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c296918  00000000  
03-21 08:36:09.725  1018  1018 D CrashAnrDetector:          9c29691c  9c296934  [stack
03-21 08:36:09.725  1018  1018 D CrashAnrDetector: processName:com.test.thalitest
03-21 08:36:09.725  1018  1018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-21 08:36:09.725  1018  1018 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-21 08:36:09.735  1018  2853 D SSRM:a  : DeviceInfo:: 000000000000
03-21 08:36:09.735  1018  2853 D SSRM:a  : SettingsAirViewInfo:: 000000000
03-21 08:36:09.775  1018  1018 D CrashAnrDetector: Build: samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
03-21 08:36:09.775  1018  1018 D CrashAnrDetector: Hardware: MSM8916
03-21 08:36:09.775  1018  1018 D CrashAnrDetector: Revision: 2
03-21 08:36:09.775  1018  1018 D CrashAnrDetector: Bootloader: A500FUXXU1BOH2
03-21 08:36:09.775  1018  1018 D CrashAnrDetector: Radio: unknown
03-21 08:36:09.775  1018  1018 D CrashAnrDetector: Kernel: Linux version 3.10.49-5583861 (dpi@SWHD7301) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Mon Aug 10 19:50:12 KST 2015
03-21 08:36:09.775  1018  1018 D CrashAnrDetector: 
03-21 08:36:09.775  1018  1018 D CrashAnrDetector: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
03-21 08:36:09.775  1018  1018 D CrashAnrDetector: Build fingerprint: 'samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys'
03-21 08:36:09.775  1018  1018 D CrashAnrDetector: Revision: '2'
03-21 08:36:09.775  1018  1018 D CrashAnrDetector: ABI: 'arm'
03-21 08:36:09.775  1018  1018 D CrashAnrDetector: pid: 4169, tid: 4392, name: Thread-644  >>> com.test.thalitest <<<
03-21 08:36:09.775  1018  1018 D CrashAnrDetector: signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:     r0 00000000  r1 9cc59044  r2 00000002  r3 00000000
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:     r4 b7bd9c50  r5 00000000  r6 b7bd94e0  r7 ba09d638
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:     r8 b778a6ac  r9 b7bd9c50  sl b7bd94b8  fp 9cc5903c
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:     ip ffffffff  sp 9cc5902c  lr 9d032b30  pc 9d032a34  cpsr 60070010
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:     d0  0000000000000000  d1  0000000000000000
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:     d2  0000000000000000  d3  0000000000000000
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:     d4  0000000000000000  d5  0000000000000000
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:     d6  0000000000000000  d7  0000000000000000
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:     d8  0000000000000000  d9  0000000000000000
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:     d10 0000000000000000  d11 0000000000000000
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:     d12 0000000000000000  d13 0000000000000000
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:     d14 0000000000000000  d15 0000000000000000
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:     d16 61426e6f69746163  d17 7065526e4f646573
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:     d18 0001000100010001  d19 0001000100010001
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:     d20 0000000100010001  d21 0000000000000000
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:     d22 0000000000000000  d23 0000000000000000
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:     d24 0000000000000000  d25 0000000000000000
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:     d26 0002000100010001  d27 0002000200020002
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:     d28 0080008000800080  d29 0080008000800080
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:     d30 0800080008000800  d31 0800080008000800
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:     scr 30000013
03-21 08:36:09.775  1018  1018 D CrashAnrDetector: 
03-21 08:36:09.775  1018  1018 D CrashAnrDetector: backtrace:
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:     #00 pc 003d1a34  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (bool ThingIsPermanentAtom<JS::Symbol>(JS::Symbol*)+4)
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:     #01 pc 003d1b2c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:     #02 pc e5943000  <unknown>
03-21 08:36:09.775  1018  1018 D CrashAnrDetector: 
03-21 08:36:09.775  1018  1018 D CrashAnrDetector: stack:
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc58fac  00000000  
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc58fb0  9a1fc0a0  [anon:js-gc-heap]
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc58fb4  b7bd9c50  [heap]
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc58fb8  b7bd9c50  [heap]
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc58fbc  00000001  
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc58fc0  9cc58fdc  [stack:4392]
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc58fc4  9d032150  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc58fc8  00000001  
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc58fcc  00000000  
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc58fd0  b7bda780  [heap]
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc58fd4  00000000  
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc58fd8  00000000  
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc58fdc  b7bd9c50  [heap]
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc58fe0  b7bda780  [heap]
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc58fe4  9d6beb60  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc58fe8  9cc59054  [stack:4392]
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc58fec  9d039514  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markConservativeStackRoots(JSTracer*, bool)+1308)
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc58ff0  b7bd9c50  [heap]
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc58ff4  b7bd94b8  [heap]
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc58ff8  9cc61000  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc58ffc  9cc59020  [stack:4392]
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc59000  9cc59018  [stack:4392]
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc59004  9cc59024  [stack:4392]
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc59008  9d5e56d4  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc5900c  9cc59028  [stack:4392]
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc59010  00000004  
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc59014  00000000  
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc59018  00000001  
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc5901c  b7bd9c50  [heap]
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc59020  99eed730  [anon:js-gc-heap]
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc59024  b7bd94e0  [heap]
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc59028  9cc5903c  [stack:4392]
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:     #00  9cc5902c  9cc5903c  [stack:4392]
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc59030  9cc60838  [stack:4392]
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc59034  ba0950e8  [heap]
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc59038  9cc59054  [stack:4392]
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc5903c  9d03606c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::MarkValueRoot(JSTracer*, JS::Value*, char const*)+80)
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:     #01  9cc59040  b778a6ac  [heap]
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc59044  00000000  
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc59048  b7bd94dc  [heap]
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc5904c  9d566cd8  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc59050  9cc590ac  [stack:4392]
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc59054  9d03adcc  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (js::gc::GCRuntime::markRuntime(JSTracer*, js::gc::GCRuntime::TraceOrMarkRuntime, js::gc::GCRuntime::TraceRootsOrUsedSaved)+1452)
03-21 08:36:09.775  1018  1018 D CrashAnrDetector:          9cc59058  000000
03-21 08:36:09.775  1018  1018 D CrashAnrDetector: processName:com.test.thalitest
03-21 08:36:09.775  1018  1018 D CrashAnrDetector: broadcastEvent : com.test.thalitest SYSTEM_TOMBSTONE
03-21 08:36:09.775  1018  1018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
03-21 08:36:09.775  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
03-21 08:36:09.775  1018  1018 I InputMethodManagerService: [BT Setting State] State =11
03-21 08:36:09.785  1018  1050 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
03-21 08:36:09.835  1018  1334 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-21 08:36:09.835  1018  1334 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
03-21 08:36:09.835  1018  1334 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
03-21 08:36:09.835  2063  2843 W DriveInitializer: Awaiting to be initialized
03-21 08:36:09.835  2063  2925 W DriveInitializer: Background init thread started
03-21 08:36:09.875  1018  1018 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-21 08:36:09.885  1018  1060 D PackageManager: [MSG] MCS_UNBIND
03-21 08:36:09.885  1018  1018 D BluetoothA2dp: Proxy object connected
03-21 08:36:09.885  1018  1018 V AlarmManagerEXT: mGmsLocationBundling: false
03-21 08:36:09.885  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
03-21 08:36:09.895  1018  1018 D SensorService: [SO] activate (ident=0xb8540470, enabled=0)
03-21 08:36:09.895  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
03-21 08:36:09.895  2921  2921 D AndroidRuntime: 
03-21 08:36:09.895  2921  2921 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-21 08:36:09.895  2921  2921 D AndroidRuntime: CheckJNI is OFF
03-21 08:36:09.895  2921  2921 D AndroidRuntime: readGMSProperty: start
03-21 08:36:09.895  2921  2921 D AndroidRuntime: readGMSProperty: already setted!!
03-21 08:36:09.895  2921  2921 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-21 08:36:09.895  2921  2921 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-21 08:36:09.895  2921  2921 D AndroidRuntime: readGMSProperty: end
03-21 08:36:09.895  2921  2921 D AndroidRuntime: addProductProperty: start
03-21 08:36:09.905  1018  1018 D SensorManager: unregisterListener ::   
03-21 08:36:09.905  1894  1894 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
03-21 08:36:09.905  1018  1018 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
03-21 08:36:09.905  1018  1018 D SensorService: [SO] changed settle time [0]
03-21 08:36:09.915  1018  1018 D SensorService: [SO] setDelay [200000000]
03-21 08:36:09.915  1018  1018 D SensorService: [SO] activate (ident=0xb8540470, enabled=1)
03-21 08:36:09.915  1018  1018 D SensorService: [SO] AR_init
03-21 08:36:09.915  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
03-21 08:36:09.915  1018  1018 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
03-21 08:36:09.915  1018  1018 D BluetoothPan: BluetoothPAN Proxy object connected
03-21 08:36:09.925  1018  1018 I ActivityManager: Killing 1560:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
03-21 08:36:09.925  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-21 08:36:09.935  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-21 08:36:09.935  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
03-21 08:36:09.935   298   298 E USB_UICC: Timeout! No signal received. Retry num = 29
03-21 08:36:09.935  1428  1428 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-21 08:36:09.935  1428  1428 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-21 08:36:09.945  1189  1189 D PowerUI : Cable  true --> true mBootCompleted : false
03-21 08:36:09.945  1189  1189 D PowerUI : Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
03-21 08:36:09.955  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 08:36:09.955  1018  1018 D RCPManagerService: ACTION_BOOT_COMPLETED
03-21 08:36:09.955  1018  1018 I MotionRecognitionService: Plugged
03-21 08:36:09.955  1018  1018 E RCPManagerService:  BootReceiver : calling scanAndStartRCPProxy ACTION_BOOT_COMPLETED 
03-21 08:36:09.955  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
03-21 08:36:09.965  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 08:36:09.965  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-21 08:36:09.965  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
03-21 08:36:09.965  1018  1018 D RCPManagerService: BootReceiver.onReceive(): Starting RCP Proxy for user = null
03-21 08:36:09.965  1018  1144 I ActivityManager: Killing 1785:com.sec.android.widgetapp.samsungapps/u0a138 (adj 15): empty #31
03-21 08:36:09.965  1018  1018 E RCPManagerService:  BootReceiver : Exception while scanAndStartRCPProxy() Attempt to get length of null array
03-21 08:36:09.975   316   316 I ServiceManager: Waiting for service AtCmdFwd...
03-21 08:36:09.975  1018  1018 D MotionRecognitionService:   mReceiver.onReceive : ACTION_BOOT_COMPLETED
03-21 08:36:09.985  1018  1334 I ActivityManager: Killing 1509:com.android.printspooler/u0a136 (adj 15): empty #31
03-21 08:36:10.015  1018  1045 D LocationProviderProxy: applying state to connected service
03-21 08:36:10.035  1018  1030 D RCPManagerService: exchangeData() failure , invalid userId
03-21 08:36:10.045  1018  1018 D EnterpriseDeviceManagerService: android.intent.action.BOOT_COMPLETED
03-21 08:36:10.045  1018  1018 V ApplicationPolicy: boot completed - refreshWidgetStatus
03-21 08:36:10.045  1018  1018 V ApplicationPolicy: refresh widget status for user 0
03-21 08:36:10.055  1018  1165 D EnterpriseDeviceManagerService: runAdminUpdate
03-21 08:36:10.055  1018  1165 D EnterpriseUtils: File Not Found : /data/system/selfUpdateAdmin.conf
03-21 08:36:10.055  1018  1165 D EnterpriseDeviceManagerService: nothing to selfUpdate
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.apps.books
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.dualclockdigital
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclockeasy
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.music
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.apps.magazines
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.tapandpay
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.email
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclock
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.music
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.fm
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.clockpackage
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gm
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.samsungapps
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.mms
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.app.memo
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.easymodecontactswidget
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.vending
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.vending
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.vending
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.activeapplicationwidget
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.sbrowser
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.talk
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname flipboard.app
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.chrome
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.music
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
03-21 08:36:10.055  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
03-21 08:36:10.055  2921  2921 E AffinityControl: AffinityControl: registerfunction enter
03-21 08:36:10.085  2921  2921 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-21 08:36:10.085  1018  1507 D RCPManagerService: exchangeData() failure , invalid userId
03-21 08:36:10.095  1018  1030 E PersonaManagerService: inState():  stateMachine is null !!
03-21 08:36:10.095  1018  1030 I PersonaManagerService: PersonaId don't exist
03-21 08:36:10.095  1018  1030 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-21 08:36:10.105  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-21 08:36:10.115  1018  1043 D SensorService: [SO] Reset Rotation Old [100], Init [1]
03-21 08:36:10.115  1018  1030 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-21 08:36:10.115  1018  1030 W ActivityManager: mDVFSHelper.acquire()
03-21 08:36:10.115  1018  1030 D FocusedStackFrame: Set to : 0
03-21 08:36:10.125  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-21 08:36:10.125  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-21 08:36:10.125  1018  1030 D InputDispatcher: Focused application set to: xxxx
03-21 08:36:10.125  1018  1030 D InputDispatcher: Focus left window: 1490
03-21 08:36:10.125  1490  1490 D Launcher.HomeView: onPause
03-21 08:36:10.125  2921  2921 D AndroidRuntime: Shutting down VM
03-21 08:36:10.125  1018  1045 W libprocessgroup: failed to open /acct/uid_10057/pid_1560/cgroup.procs: No such file or directory
03-21 08:36:10.125  1490  1490 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-21 08:36:10.125  1018  1045 W libprocessgroup: failed to open /acct/uid_10136/pid_1509/cgroup.procs: No such file or directory
03-21 08:36:10.135  1018  1045 W libprocessgroup: failed to open /acct/uid_10138/pid_1785/cgroup.procs: No such file or directory
03-21 08:36:10.135  1018  1363 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:10.135  1018  1363 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:10.135  1018  1363 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:10.135  1018  1363 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:10.135  1018  1051 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-21 08:36:10.135  1018  1051 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-21 08:36:10.145  1018  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-21 08:36:10.145  1018  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
03-21 08:36:10.145  2949  2949 E Zygote  : MountEmulatedStorage()
03-21 08:36:10.145  1018  1051 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-21 08:36:10.145  2949  2949 I libpersona: KNOX_SDCARD checking this for 10155
03-21 08:36:10.145  2949  2949 E Zygote  : v2
03-21 08:36:10.145  2949  2949 I libpersona: KNOX_SDCARD not a persona
03-21 08:36:10.145  1018  1051 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-21 08:36:10.155   258   258 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-21 08:36:10.155  2949  2949 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-21 08:36:10.155  2949  2949 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 08:36:10.155  1018  1363 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2949 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-21 08:36:10.155  2949  2949 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-21 08:36:10.175  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-21 08:36:10.175  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-21 08:36:10.175  1189  1189 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-21 08:36:10.175  1189  1189 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-21 08:36:10.175  1189  1189 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-21 08:36:10.175  1189  1189 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-21 08:36:10.185  1018  1018 W PhoneRestrictionPolicy: Message received - msg { when=-4ms what=2 target=com.android.server.enterprise.restriction.PhoneRestrictionPolicy$SmsMmsDeliveryHandler }
03-21 08:36:10.185  1018  1030 D RCPManagerService: exchangeData() failure , invalid userId
03-21 08:36:10.185   257   534 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
03-21 08:36:10.185   257   534 W Vold    : Returning OperationFailed - no handler for errno 0
03-21 08:36:10.185  2063  2925 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
03-21 08:36:10.205  1490  1490 V ActivityThread: updateVisibility : ActivityRecord{3d35c5ed token=android.os.BinderProxy@254aae7f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-21 08:36:10.205  1018  1018 D KnoxMUMContainerPolicy: mContainerReceiver : action - android.intent.action.BOOT_COMPLETED
03-21 08:36:10.205  1018  1018 I KnoxMUMContainerPolicy: MSG_REMOVE_ORPHANED_CONTAINERS received
03-21 08:36:10.205  2949  2949 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 08:36:10.205  2949  2949 D ActivityThread: Added TimaKeyStore provider
03-21 08:36:10.215  1018  2966 W PhoneRestrictionPolicy:  >>>> deliveryBlockedMsgs
03-21 08:36:10.215  1018  1314 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-21 08:36:10.215  1018  1314 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-21 08:36:10.215  1018  1314 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-21 08:36:10.225  1490  1490 D Launcher.HomeView: onStop
03-21 08:36:10.225  1018  2966 W PhoneRestrictionPolicy: cvList size 0
03-21 08:36:10.225  1018  2966 W PhoneRestrictionPolicy:  >>>> deliveryBlockedMsgs
03-21 08:36:10.225  1018  2966 W PhoneRestrictionPolicy: cvList size 0
03-21 08:36:10.225  1490  1490 V ActivityThread: updateVisibility : ActivityRecord{3d35c5ed token=android.os.BinderProxy@254aae7f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-21 08:36:10.225  2768  2768 E BluetoothAdapterService(154684346): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
03-21 08:36:10.225  2768  2768 E BluetoothAdapterService(154684346): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
03-21 08:36:10.225  2768  2768 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-21 08:36:10.225  2768  2852 D HeadsetStateMachine: Disconnected process message: 10
03-21 08:36:10.235  1018  1049 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-21 08:36:10.235  1018  1314 D PersonaManager: isKioskContainerExistOnDevice
03-21 08:36:10.245  1018  1031 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
03-21 08:36:10.255  1018  1134 D WifiP2pService: InactiveState{ what=143415 }
03-21 08:36:10.255  1018  1134 D WifiP2pService: P2pEnabledState{ what=143415 }
03-21 08:36:10.255  1018  1134 D WifiP2pService: DefaultState{ what=143415 }
03-21 08:36:10.255  1018  1147 D ConnectivityService: Got NetworkFactory Messenger for WIFI_P2P
03-21 08:36:10.255  1018  1134 D WIFI_P2P: got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
03-21 08:36:10.255  1018  1134 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
03-21 08:36:10.255  1018  1508 D RCPManagerService: exchangeData() failure , invalid userId
03-21 08:36:10.255  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:10.255  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:10.255  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:10.255  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:10.275  2970  2970 E Zygote  : MountEmulatedStorage()
03-21 08:36:10.275  2970  2970 E Zygote  : v2
03-21 08:36:10.275  2970  2970 I libpersona: KNOX_SDCARD checking this for 10072
03-21 08:36:10.275  2970  2970 I libpersona: KNOX_SDCARD not a persona
03-21 08:36:10.275  2970  2970 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-21 08:36:10.275  1018  1031 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=2970 uid=10072 gids={50072, 9997} abi=armeabi-v7a
03-21 08:36:10.275  2970  2970 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 08:36:10.285  2970  2970 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-21 08:36:10.285  2768  2836 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
03-21 08:36:10.285  2768  2836 I bluedroid: enable
03-21 08:36:10.295  1018  1147 D ConnectivityService: Got NetworkFactory Messenger for WIFI
03-21 08:36:10.295  2768  2836 I bt_hci_bdroid: init
03-21 08:36:10.295  1018  1145 E WifiStateMachine: Blacklist file delete
03-21 08:36:10.295  2768  2979 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
03-21 08:36:10.295  2768  2836 I bt_vendor: bt-vendor : init
03-21 08:36:10.295  2768  2836 I bt_vendor: bt-vendor : get_bt_soc_type
03-21 08:36:10.295  2768  2836 E bt_vendor: get_bt_soc_type: Failed to get soc type
03-21 08:36:10.295  2768  2836 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
03-21 08:36:10.295  2768  2836 D bt_userial_mct: userial_init
03-21 08:36:10.295  2768  2836 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
03-21 08:36:10.295  2768  2836 I bt_vendor: Starting hciattach daemon
03-21 08:36:10.295  2768  2836 I bt_vendor: try to set false
03-21 08:36:10.305  2768  2836 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
03-21 08:36:10.305  2768  2836 I bt_vendor: Starting hciattach daemon
03-21 08:36:10.305  2768  2836 I bt_vendor: try to set true
03-21 08:36:10.325  1490  1490 D Launcher: onTrimMemory. Level: 20
03-21 08:36:10.325  1018  1043 D SensorService: [SO] currT = 36200117276, prevT = 35760091547, diff = 440025729, [0.077 0.421 10.113]
03-21 08:36:10.325  1018  1043 D SensorService: [SO] 0.077 0.421 10.113
03-21 08:36:10.325  1018  1043 D SensorService: [SO] [100 -> 255]
03-21 08:36:10.335  1018  1018 D Tethering: Boot complete.
03-21 08:36:10.335  2992  2992 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
03-21 08:36:10.335  2921  2921 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-21 08:36:10.375  2970  2970 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 08:36:10.375  2970  2970 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:10.395  1018  1018 D SensorService: [SO] activate (ident=0xb8540470, enabled=0),
03-21 08:36:10.395  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-21 08:36:10.395  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-21 08:36:10.395  1018  1145 D WIFI    : got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
,03-21 08:36:10.395  1018  1145 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,03-21 08:36:10.395  1018  1504 I ActivityManager: Killing 1639:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,03-21 08:36:10.405  3004  3004 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,03-21 08:36:10.415  1018  1018 D SensorManager: unregisterListener ::   
,03-21 08:36:10.415  1018  1018 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
,03-21 08:36:10.415  1018  1018 D SensorService: [SO] changed settle time [1]
03-21 08:36:10.415  1018  1018 D SensorService: [SO] setDelay [66000000]
03-21 08:36:10.415  1018  1018 D SensorService: [SO] activate (ident=0xb8540470, enabled=1)
03-21 08:36:10.415  1018  1018 D SensorService: [SO] AR_init
03-21 08:36:10.415  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-21 08:36:10.415  3005  3005 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,03-21 08:36:10.425  1018  1018 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
03-21 08:36:10.425  1018  1018 V EnterpriseBillingEngine: ACTION_BOOT_COMPLETED
03-21 08:36:10.425  1018  1018 V EnterpriseBillingEngine: handleAllprofiles - start
03-21 08:36:10.425  1018  1018 V EnterpriseBillingPolicyStorage: getCurrentActiveProfiles - start - 
,03-21 08:36:10.425  1018  1018 V EnterpriseBillingPolicyStorage: getCurrentActiveProfiles - end - null
03-21 08:36:10.425  1018  1018 V EnterpriseBillingEngine: handleAllprofiles - end
,03-21 08:36:10.435  1018  1018 D UsbHostNotification: boot completed,
,03-21 08:36:10.445  3008  3008 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,03-21 08:36:10.445  1018  1018 D UsbHostRestrictor: mBootCompletedReceiver onReceive
03-21 08:36:10.445  1018  1018 D UsbHostRestrictor: initSetUsbBlock STARTED
,03-21 08:36:10.455  1018  1334 D RCPManagerService: exchangeData() failure , invalid userId
,03-21 08:36:10.455  3009  3009 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,03-21 08:36:10.465  3013  3013 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,03-21 08:36:10.475  1018  1508 D RCPManagerService: exchangeData() failure , invalid userId
,03-21 08:36:10.475  3015  3015 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,03-21 08:36:10.475  1018  1018 D UsbHostRestrictor: SIM was never inserted
,03-21 08:36:10.475  1018  1018 D UsbHostRestrictor: writableHostSysNode[false]
03-21 08:36:10.475  1018  1018 D UsbHostRestrictor: Can NOT Write Disable Sys Node to [ON]
,03-21 08:36:10.485  1018  2853 D SSRM:a  : DeviceInfo:: 000000000000
,03-21 08:36:10.485  1018  2853 D SSRM:a  : SettingsAirViewInfo:: 000000000
,03-21 08:36:10.485  2949  2949 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-21 08:36:10.495  1018  1043 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-21 08:36:10.495  2970  2970 D BadgeProvider: onCreate
,03-21 08:36:10.495  2970  2970 D BadgeProvider: DatabaseHelper
,03-21 08:36:10.515  2949  2949 I LibraryLoader: Time to load native libraries: 10 ms (timestamps 6397-6407)
03-21 08:36:10.515  2949  2949 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-21 08:36:10.535  2970  2993 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-21 08:36:10.555  2949  2949 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9384bba}
,03-21 08:36:10.555  2949  2949 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-21 08:36:10.555  2949  2949 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,03-21 08:36:10.555  1018  1018 D PersonaManagerService: ACTION_BOOT_COMPLETED
,03-21 08:36:10.555  1018  1065 E PersonaManagerServiceHandler:  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
,03-21 08:36:10.555  1018  1065 D KnoxKeyguardUpdateMonitor: onBootComplete
,03-21 08:36:10.565  1018  1043 D SensorService: [SO] 0.077 0.421 10.113
03-21 08:36:10.565  1018  1043 D SensorService: [SO] [100 -> 255]
,03-21 08:36:10.565  2063  2925 W DriveInitializer: Background init thread ended
,03-21 08:36:10.565  1018  1018 I KnoxKeyguardUpdateMonitor: onTrustManagedChanged user 0, managed:false
03-21 08:36:10.565  1018  1018 I KnoxKeyguardUpdateMonitor: onTrustChanged user:0, enable:false
,03-21 08:36:10.565  1189  1189 D KeyguardViewMediator: onTrustChanged( Showing = false , userId = 0 )
03-21 08:36:10.565  1018  1018 D UsbStorageNotification: boot completed
,03-21 08:36:10.575  2970  2993 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-21 08:36:10.575  1490  1490 D Launcher.Model: reloadBadges entered.
03-21 08:36:10.575  2970  2993 D BadgeProvider: sendNotify, [notify] : null
03-21 08:36:10.575  2970  2993 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-21 08:36:10.575  2970  2993 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-21 08:36:10.575  2970  2993 D BadgeProvider: update, [UpdateCount] : 1
,03-21 08:36:10.575  1018  1065 D PersonaManagerService: getPersonasForUser(): returning null!
,03-21 08:36:10.595  2949  2949 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-21 08:36:10.595  2949  2949 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 08:36:10.595  2949  2949 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-21 08:36:10.625  2949  2949 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,03-21 08:36:10.625  2949  2949 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
03-21 08:36:10.625  2949  2949 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,03-21 08:36:10.625  1018  1314 I ActivityManager: Killing 2133:com.android.vending/u0a28 (adj 15): empty #31
,03-21 08:36:10.625  2949  2949 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-21 08:36:10.625  2949  2949 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-21 08:36:10.625  2949  2949 I Adreno-EGL: Build Date: 04/06/15 Mon
03-21 08:36:10.625  2949  2949 I Adreno-EGL: Local Branch: 
03-21 08:36:10.625  2949  2949 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-21 08:36:10.625  2949  2949 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-21 08:36:10.625  2949  2949 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-21 08:36:10.645  1018  2994 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-21 08:36:10.645  1018  2994 W ActivityManager: userId = 0, bbcId = -10000
03-21 08:36:10.645  1018  2994 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 08:36:10.645  1018  2994 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-21 08:36:10.645  1018  1045 E libprocessgroup: failed to kill 1 processes for processgroup 1639
,03-21 08:36:10.665  3034  3034 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab 
,03-21 08:36:10.675  1018  1363 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-21 08:36:10.675  3035  3035 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
03-21 08:36:10.685  1018  1363 W ActivityManager: userId = 0, bbcId = -10000
03-21 08:36:10.685  1018  1363 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 08:36:10.685  1018  1363 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-21 08:36:10.685   258   444 I SurfaceFlinger: id=8 Removed Mauncher (5/8)
03-21 08:36:10.685   258  1042 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
03-21 08:36:10.695  1018  1363 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-21 08:36:10.695  1018  1363 W ActivityManager: userId = 0, bbcId = -10000
03-21 08:36:10.695  1018  1363 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 08:36:10.695  1018  1363 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-21 08:36:10.705  2768  2836 I bt_vendor: bluetooth satus is on
03-21 08:36:10.705  2768  2981 D bt_userial_mct: userial_open(port:0)
03-21 08:36:10.705  2768  2981 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,03-21 08:36:10.715  2768  2981 I bt_vendor: Done intiailizing UART
,03-21 08:36:10.715  2768  2981 I bt_vendor: Done intiailizing UART
03-21 08:36:10.715  2768  2981 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
03-21 08:36:10.715  2768  2981 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,03-21 08:36:10.725  2768  3049 D bt_userial_mct: Entering userial_read_thread()
,03-21 08:36:10.755  1018  1045 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.BOOT_COMPLETED
03-21 08:36:10.755  1018  1045 D GpsLocationProvider_ex: BOOT_COMPLETED native_init 
03-21 08:36:10.755  1018  1045 D GpsLocationProvider: set_capabilities_callback: 55u
,03-21 08:36:10.755  1018  1045 I libmdmdetect: ESOC framework not supported
,03-21 08:36:10.755  1018  1045 I libmdmdetect: Found internal modem: modem
03-21 08:36:10.755  1018  1545 D qmi_secgps_clnt: qmi_secgps_client_init()
,03-21 08:36:10.755  2768  2979 I         : BTE_InitTraceLevels -- TRC_HCI
,03-21 08:36:10.755  1018  1045 E PerMgrLib: Peripheral manager is not supported on this device
03-21 08:36:10.755  2768  2979 I         : BTE_InitTraceLevels -- TRC_L2CAP
03-21 08:36:10.755  1018  1045 E Geofence_Adapter: I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
03-21 08:36:10.755  1018  1045 E Geofence_Adapter: I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
03-21 08:36:10.755  1018  1045 D GpsLocationProvider_ex: BOOT_COMPLETED native_cleanup 
,03-21 08:36:10.755  2768  2979 I         : BTE_InitTraceLevels -- TRC_RFCOMM
03-21 08:36:10.755  2768  2979 I         : BTE_InitTraceLevels -- TRC_AVDT
03-21 08:36:10.755  2768  2979 I         : BTE_InitTraceLevels -- TRC_AVRC
03-21 08:36:10.755  2768  2979 I         : BTE_InitTraceLevels -- TRC_A2D
,03-21 08:36:10.755  2768  2979 I         : BTE_InitTraceLevels -- TRC_BNEP
03-21 08:36:10.755  2768  2979 I         : BTE_InitTraceLevels -- TRC_BTM
03-21 08:36:10.755  2768  2979 I         : BTE_InitTraceLevels -- TRC_GAP
,03-21 08:36:10.755  2768  2979 I         : BTE_InitTraceLevels -- TRC_PAN
03-21 08:36:10.755  2768  2979 I         : BTE_InitTraceLevels -- TRC_SAP
,03-21 08:36:10.755  2768  2979 I         : BTE_InitTraceLevels -- TRC_SDP
03-21 08:36:10.755  2768  2979 I         : BTE_InitTraceLevels -- TRC_GATT
03-21 08:36:10.755  2768  2979 I         : BTE_InitTraceLevels -- TRC_SMP
03-21 08:36:10.755  2768  2979 I         : BTE_InitTraceLevels -- TRC_BTAPP
,03-21 08:36:10.755  2768  2979 I         : BTE_InitTraceLevels -- TRC_BTIF
03-21 08:36:10.755  2768  2979 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,03-21 08:36:10.765  1189  1189 D StorageNotification: boot completed
,03-21 08:36:10.775  1018  1545 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
,03-21 08:36:10.775  1018  1545 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
,03-21 08:36:10.785  1018  1545 D qmi_secgps_clnt: SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
,03-21 08:36:10.785  1018  1363 D StatusBarManagerService: setIcon slot=volume index=23 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,03-21 08:36:10.795  1189  1189 D PhoneStatusBar: updateIcon slot=volume index=23 viewIndex=5 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02042a level=0 visible=true num=0 )
,03-21 08:36:10.795  1018  1030 D ActivityManager: startProcessLocked calleePkgName: flipboard.boxer.app, hostingType: broadcast
,03-21 08:36:10.795  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:10.795  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:10.795  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:10.795  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:10.825  3059  3059 E Zygote  : MountEmulatedStorage()
03-21 08:36:10.825  3059  3059 E Zygote  : v2
03-21 08:36:10.825  3059  3059 I libpersona: KNOX_SDCARD checking this for 10099
03-21 08:36:10.825  3059  3059 I libpersona: KNOX_SDCARD not a persona
,03-21 08:36:10.825  3059  3059 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 08:36:10.825  3059  3059 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 08:36:10.835  3059  3059 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-21 08:36:10.835  1018  1030 I ActivityManager: Start proc flipboard.boxer.app for broadcast flipboard.boxer.app/flipboard.boxer.receiver.BootCompleted: pid=3059 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-21 08:36:10.855  3059  3059 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 08:36:10.855  3059  3059 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:10.865  1018  1508 I art     : Explicit concurrent mark sweep GC freed 202969(12MB) AllocSpace objects, 105(8MB) LOS objects, 33% free, 26MB/39MB, paused 2.830ms total 230.261ms
,03-21 08:36:10.865  2949  3042 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,03-21 08:36:10.865  2768  2979 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,03-21 08:36:10.865  2768  2979 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3f326e9 
03-21 08:36:10.865  2768  2979 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3f326e9 
,03-21 08:36:10.875  1018  1045 W libprocessgroup: failed to open /acct/uid_10028/pid_2133/cgroup.procs: No such file or directory
,03-21 08:36:10.895  1018  1545 E LocSvc_utils_cfg: W/loc_read_sec_gps_conf: no secgps conf file, using defaults
,03-21 08:36:10.895  2768  2839 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,03-21 08:36:10.905  1018  1556 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,03-21 08:36:10.905  2768  2839 E bt-btif : L2CAP - L2CA_Registe
,03-21 08:36:10.905  2768  2839 E bt-btif :                : sec: 0x1086, service name [] (up to 213
,03-21 08:36:10.905  2768  2839 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
03-21 08:36:10.905  2768  2839 E BluetoothServiceJni: populateRssiValuesNative
03-21 08:36:10.905  2768  2839 I bluedroid: getModelRssiValues
03-21 08:36:10.905  2768  2839 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
03-21 08:36:10.905  2768  2839 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,03-21 08:36:10.905  1018  1556 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_ENGINE_LOCK_REQ_V02
,03-21 08:36:10.905  2768  2839 D BluetoothAdapterProperties: Name is: A5-1
,03-21 08:36:10.905  1018  1018 D SettingsProvider: name = bluetooth_name
,03-21 08:36:10.915  1018  1556 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
,03-21 08:36:10.915  1018  1545 I qmi_secgps_clnt: SECGPS: Set AGPS Mode : 7
,03-21 08:36:10.915  1018  1545 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
,03-21 08:36:10.915  2768  2839 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-21 08:36:10.915  2768  2839 D BluetoothAdapterProperties: Scan Mode:20
03-21 08:36:10.915  2768  2839 D BluetoothAdapterProperties: Discoverable Timeout:120
03-21 08:36:10.915  2768  2839 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
03-21 08:36:10.915  2768  2839 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
03-21 08:36:10.915  2768  2839 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,03-21 08:36:10.915  2768  2839 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,03-21 08:36:10.915  2768  2839 E bt-btif : BTA got event 0x1a00
03-21 08:36:10.915  2768  2839 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
03-21 08:36:10.915  1018  1556 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-21 08:36:10.915  1018  1545 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1558]: supl version = 131072
,03-21 08:36:10.925  1018  1314 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
03-21 08:36:10.925  1018  1314 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-21 08:36:10.925  2768  2839 D IOP_DB_BT: db_open: db_open : handle 3027820560l, read 13894 bytes onto local cache
,03-21 08:36:10.925  2768  2839 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
03-21 08:36:10.925  2768  2839 D IOP_DB_BT: db_query: result 1
03-21 08:36:10.925  2768  2839 I         : iop_db_open: iop_db_open status 0
,03-21 08:36:10.925  2768  3049 E bt_mct  : hci lib postload completed
,03-21 08:36:10.925  2768  2839 D bte_conf: Device ID record 1 : primary
03-21 08:36:10.925  2768  2839 D bte_conf:   vendorId            = 0075
03-21 08:36:10.925  2768  2839 D bte_conf:   vendorIdSource      = 0001
03-21 08:36:10.925  2768  2839 D bte_conf:   product             = 0100
03-21 08:36:10.925  2768  2839 D bte_conf:   version             = 0200
03-21 08:36:10.925  2768  2839 D bte_conf:   clientExecutableURL = 
03-21 08:36:10.925  2768  2839 D bte_conf:   serviceDescription  = 
03-21 08:36:10.925  2768  2839 D bte_conf:   documentationURL    = 
03-21 08:36:10.925  2768  2839 D bte_conf: bte_load_did_conf no section named DID2.
03-21 08:36:10.925  2768  2839 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,03-21 08:36:10.925  1018  1556 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-21 08:36:10.925  1018  1545 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1881]: aGlonassProtocolMask = 0x0
,03-21 08:36:10.935  2768  2836 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
03-21 08:36:10.935  2768  2836 D BluetoothAdapterProperties: ScanMode =  20
03-21 08:36:10.935  2768  2836 D BluetoothAdapterProperties: State =  11
,03-21 08:36:10.935  1018  1334 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-21 08:36:10.935  1018  1030 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
03-21 08:36:10.935  2768  2836 D BluetoothAdapterProperties: Setting state to 12
,03-21 08:36:10.935  2768  2836 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,03-21 08:36:10.935  1018  1363 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-21 08:36:10.935  2768  2839 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
03-21 08:36:10.935  2768  2839 D BluetoothAdapterProperties: Scan Mode:21
,03-21 08:36:10.935   298   298 E USB_UICC: Timeout! No signal received. Retry num = 30
03-21 08:36:10.935  2768  2839 D BluetoothAdapterProperties: Discoverable Timeout:120
,03-21 08:36:10.935  1018  1144 D SettingsProvider: name = bluetooth_a2dp_sink_mode
03-21 08:36:10.935  1018  1144 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 08:36:10.935  1018  1144 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 08:36:10.935  1018  1144 D SettingsProvider: selectionArgs: false
03-21 08:36:10.935  1018  1144 D SettingsProvider: selectionArgs: 1002
03-21 08:36:10.935  1018  1144 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 08:36:10.935  1018  1144 D SettingsProvider: ret = -1
,03-21 08:36:10.945  1018  1556 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,03-21 08:36:10.945  1018  1545 I qmi_secgps_clnt: SECGPS: Set XTRA enable : 1
,03-21 08:36:10.945  2949  2949 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 08:36:10.945  1018  1545 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-21 08:36:10.945  1018  1545 I qmi_secgps_clnt: SECGPS: Set GNSS RF CONFIG : 1
03-21 08:36:10.945  1018  1545 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-21 08:36:10.945  1018  1545 I qmi_secgps_clnt: SECGPS: Set CERT TYPE : 15
,03-21 08:36:10.945  1018  1545 D qmi_secgps_clnt: SECGPS: send a qmi message to secgps_server OK
03-21 08:36:10.945  1018  1545 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1605]: lpp profile = 0
,03-21 08:36:10.975  2949  2949 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-21 08:36:10.975   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-21 08:36:10.985  2949  2949 D PhoneWindow: *FMB* installDecor mIsFloating : false
,03-21 08:36:10.985  2949  2949 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-21 08:36:10.995  2949  2949 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-21 08:36:10.995  1018  1144 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,03-21 08:36:10.995  2768  2836 D BluetoothAdapterService: Bluetooth PBAP supproted is true
03-21 08:36:10.995  2768  2836 D BluetoothAdapterService: updateAdapterState state is 12
,03-21 08:36:10.995  1018  1314 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,03-21 08:36:10.995  1018  1314 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,03-21 08:36:11.005  1018  1556 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
03-21 08:36:11.005  1018  1545 E LocSvc_ApiV02: I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1644]: sensors disabled = 1
,03-21 08:36:11.005  1018  1314 W ActivityManager: userId = 0, bbcId = -10000
03-21 08:36:11.005  1018  1314 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 08:36:11.005  1018  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,03-21 08:36:11.005  1018  1556 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
,03-21 08:36:11.005  1018  1556 E LocSvc_ApiV02: I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
,03-21 08:36:11.005  2768  2836 D BluetoothAdapterService: Autoconnection is available 
03-21 08:36:11.005  2768  2836 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
03-21 08:36:11.005  2768  2836 D BluetoothAdapterService: starting service from this receiver
03-21 08:36:11.005  1018  1545 E LocSvc_ApiV02: E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3316]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
,03-21 08:36:11.005  1018  1558 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,03-21 08:36:11.005  1018  1558 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,03-21 08:36:11.005  1018  1558 W ActivityManager: userId = 0, bbcId = -10000
03-21 08:36:11.005  1018  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 08:36:11.005  1018  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,03-21 08:36:11.015  1894  2111 D BluetoothAdapter: onBluetoothStateChange: up=true
,03-21 08:36:11.015  1894  2111 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,03-21 08:36:11.015  2768  2836 I BluetoothAdapterState: Entering On State from state = 11
,03-21 08:36:11.015  1454  1468 D BluetoothAdapter: onBluetoothStateChange: up=true
03-21 08:36:11.015  1454  1468 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,03-21 08:36:11.015  2768  2787 D BluetoothAdapter: onBluetoothStateChange: up=true
,03-21 08:36:11.015  2768  2787 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,03-21 08:36:11.015  2949  2949 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 08:36:11.015  2949  2949 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 08:36:11.015  1189  1189 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-21 08:36:11.025  2214  2226 D BluetoothAdapter: onBluetoothStateChange: up=true
03-21 08:36:11.025  2214  2226 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,03-21 08:36:11.025  2949  2957 D BluetoothAdapter: onBluetoothStateChange: up=true
03-21 08:36:11.025  2949  2957 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-21 08:36:11.025  1018  1050 D BluetoothAdapter: onBluetoothStateChange: up=true
03-21 08:36:11.025  1018  1050 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,03-21 08:36:11.025  1189  1202 D BluetoothAdapter: onBluetoothStateChange: up=true
,03-21 08:36:11.025  1189  1202 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
03-21 08:36:11.025  1018  1050 D BluetoothA2dp: onBluetoothStateChange: up=true
,03-21 08:36:11.025  1469  1637 D BluetoothAdapter: onBluetoothStateChange: up=true
,03-21 08:36:11.025  1469  1637 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,03-21 08:36:11.025  1445  1460 D BluetoothAdapter: onBluetoothStateChange: up=true
03-21 08:36:11.025  1445  1460 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,03-21 08:36:11.025  2768  2781 D BluetoothA2dp: onBluetoothStateChange: up=true
,03-21 08:36:11.025  1018  1050 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,03-21 08:36:11.025  1018  1050 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,03-21 08:36:11.025  1018  1018 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,03-21 08:36:11.035  1018  1018 I InputMethodManagerService: [BT Setting State] State =12
03-21 08:36:11.035  1018  1018 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,03-21 08:36:11.035  1445  1445 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@18b5bc7d, true
,03-21 08:36:11.035  1445  1445 D BluetoothHeadset: registerMessageListener
,03-21 08:36:11.035  1189  1189 D BluetoothTile:  onBluetoothStateChange:
,03-21 08:36:11.045  1189  1189 D BluetoothTile:  onBluetoothPairedDevicesChanged:
03-21 08:36:11.045  1189  1189 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
03-21 08:36:11.045  1189  1189 D BluetoothTile:  getBluetoothState : 12
,03-21 08:36:11.045  1018  1508 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.cache.DataUpdateListenerCacheService; callingUser = 0; userId(target) = 0
03-21 08:36:11.045  1876  1876 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,03-21 08:36:11.045  2768  2787 D HeadsetService: registerMessageListener
,03-21 08:36:11.045  2768  2787 D HeadsetService: registerMessageListener
03-21 08:36:11.045  1189  1755 D BluetoothTile:  handleUpdatestate:false name:null
,03-21 08:36:11.055  2768  2852 D HeadsetStateMachine: Disconnected process message: 70
,03-21 08:36:11.055  2768  2852 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1b37986c
,03-21 08:36:11.055  1445  1445 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
03-21 08:36:11.055  1445  1445 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,03-21 08:36:11.055  1189  1755 D BluetoothTile:  handleUpdatestate:false name:null
,03-21 08:36:11.055  1445  1445 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
03-21 08:36:11.055  1445  1445 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,03-21 08:36:11.055  1445  1445 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,03-21 08:36:11.055  1189  1755 D BluetoothTile:  handleUpdatestate:false name:null
,03-21 08:36:11.065   298   298 E USB_UICC: Timeout! No signal received. Reach maximum retries!
03-21 08:36:11.065   298   298 E USB_UICC: usb_uicc_init_qmi failed ! 
03-21 08:36:11.065   298   298 I USB_UICC: usb_uicc_cleanup, signal received: 0x3 
03-21 08:36:11.065   298   298 I USB_UICC: usb_uicc_cleanup, Issuing QMI deinit ... 
,03-21 08:36:11.065  2768  2852 D HeadsetStateMachine: Disconnected process message: 9
03-21 08:36:11.065  2768  2852 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,03-21 08:36:11.065  1018  1031 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,03-21 08:36:11.075  1018  1030 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,03-21 08:36:11.075  1189  1189 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,03-21 08:36:11.085   284   284 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
03-21 08:36:11.085   284   284 V voice   : voice_set_parameters: enter: A2dpSuspended=false
03-21 08:36:11.085   284   284 V voice   : voice_set_parameters: exit with code(-2)
03-21 08:36:11.085   284   284 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
03-21 08:36:11.085   284   284 V msm8974_platform: platform_set_parameters: exit with code(-2)
03-21 08:36:11.085   284   284 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
03-21 08:36:11.085   284   284 V audio_hw_primary: adev_set_parameters: exit
,03-21 08:36:11.095  2768  2852 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,03-21 08:36:11.125  2949  3092 D OpenGLRenderer: Render dirty regions requested: true
,03-21 08:36:11.135  1018  1031 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false,
03-21 08:36:11.135  1018  1031 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-21 08:36:11.135  1018  1031 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-21 08:36:11.135  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-21 08:36:11.135  1018  1030 I ActivityManager: Killing 2214:com.vlingo.midas/u0a31 (adj 15): empty #31
03-21 08:36:11.135  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,03-21 08:36:11.145  2949  2949 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-21 08:36:11.145  2949  2949 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-21 08:36:11.145  2768  2768 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,03-21 08:36:11.155   258   258 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
,03-21 08:36:11.165  2768  2768 I BluetoothPbapService: Handler(): got msg=1
,03-21 08:36:11.165  1018  1031 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,03-21 08:36:11.175  2768  3094 V BluetoothPbapService: PBAP Service initSocket try: 0
,03-21 08:36:11.175  2768  3095 D BluetoothMapMasInstance: set MAP SDP message type : 1
,03-21 08:36:11.175  2768  3094 D BluetoothSocket: bindListen(): myUserId = 0
03-21 08:36:11.175  2768  3094 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 08:36:11.175  1018  1508 D InputDispatcher: Focus entered window: 2949
,03-21 08:36:11.185  2768  3094 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
03-21 08:36:11.185  2768  3094 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 08:36:11.185  2768  3094 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 08:36:11.185  2768  3094 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@264a8904
03-21 08:36:11.185  2768  3094 D BluetoothSocket: channel: 19
03-21 08:36:11.185  2768  3094 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,03-21 08:36:11.185  1018  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-21 08:36:11.185  2949  2949 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-21 08:36:11.185  2949  3092 I OpenGLRenderer: Initialized EGL, version 1.4
03-21 08:36:11.185  2768  3095 D BluetoothSocket: bindListen(): myUserId = 0
,03-21 08:36:11.185  2768  3095 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,03-21 08:36:11.185  1018  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-21 08:36:11.185  2768  3095 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
03-21 08:36:11.185  2768  3095 D BluetoothSocket: bindListen(), new LocalSocket 
03-21 08:36:11.185  2768  3095 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
03-21 08:36:11.185  2768  3095 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@93beed
,03-21 08:36:11.185  2768  3095 D BluetoothSocket: channel: 5
,03-21 08:36:11.195  2949  3092 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,03-21 08:36:11.195  2949  3092 D OpenGLRenderer: Enabling debug mode 0,
,03-21 08:36:11.225  1018  1314 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-21 08:36:11.225  1018  3097 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 08:36:11.235  1189  1189 I StatusBar: Icon Only
03-21 08:36:11.235  1189  1189 D PanelView: There is/are notification(s) 
,03-21 08:36:11.235  1018  1051 I ActivityManager: Displayed Component not be shown by security: +1s104ms
,03-21 08:36:11.235  1018  1051 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,03-21 08:36:11.235  1018  1051 W ActivityManager: mDVFSHelper.release()
03-21 08:36:11.235  1018  1051 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{875814e u0 com.test.thalitest/.MainActivity t16} time:37125
,03-21 08:36:11.235  1018  1046 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-21 08:36:11.255  2949  2949 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3f5efb37 time:37140
,03-21 08:36:11.255  1876  1876 I SamsungIME: getCurrentCandidateView
,03-21 08:36:11.345  2949  2949 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 2949
,03-21 08:36:11.355  1018  1045 W libprocessgroup: failed to open /acct/uid_10031/pid_2214/cgroup.procs: No such file or directory
,03-21 08:36:11.365  1018  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.sec.android.gallery3d, action: android.content.SyncAdapter
03-21 08:36:11.365  1018  1045 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
,03-21 08:36:11.385  1876  1876 D SamsungIME: Dismiss ExpandCandiate
,03-21 08:36:11.425  2507  3106 D PicasaService: start picasa sync
,03-21 08:36:11.435   258  1042 I SurfaceFlinger: id=10 Removed uhalitest (7/8)
,03-21 08:36:11.435   258   448 I SurfaceFlinger: id=10 Removed uhalitest (-2/8)
,03-21 08:36:11.455  2507  3106 D PicasaService: end picasa sync
,03-21 08:36:11.475  1018  1030 D ActivityManager: bindService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.gms, action: null
03-21 08:36:11.475  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-21 08:36:11.475  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-21 08:36:11.475  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 08:36:11.475  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-21 08:36:11.515  1018  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
03-21 08:36:11.515  1018  1045 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
,03-21 08:36:11.535  3059  3059 E ActivityThread: Failed to find provider info for flipboard.auth.internal.debug
,03-21 08:36:11.535  1018  1018 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,03-21 08:36:11.535  3059  3059 E ActivityThread: Failed to find provider info for flipboard.auth.internal
,03-21 08:36:11.545  1018  1144 I splitIntent: Split this intent : android.intent.action.BOOT_COMPLETED, mSplitNum[0]=91, mSplitNum[1]=131, mSplitNum[2]=170, mBgSplitQueueNum=3 divideNum= 38 r.nextReceiver= 53 receivers.size=208
,03-21 08:36:11.545  1018  1144 I splitIntent: finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
,03-21 08:36:11.555  1018  1018 I DrmEventReceiver: DrmEventReceiver : onReceive
03-21 08:36:11.555  1018  1018 I DrmEventReceiver: DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
,03-21 08:36:11.555  1018  1018 I DrmEventReceiver: DrmEventReceiver : beginStartingService
03-21 08:36:11.555  1018  1018 I System.out: start Service
,03-21 08:36:11.555  1018  1018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
,03-21 08:36:11.555  2949  2949 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-21 08:36:11.565  1018  1046 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.bluetoothtest, hostingType: broadcast
,03-21 08:36:11.565  1018  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:11.565  1018  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:11.565  1018  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:11.565  1018  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:11.575  1239  1239 V DownloadManager: onReceive intent + android.intent.action.BOOT_COMPLETED
,03-21 08:36:11.575  3115  3115 E Zygote  : MountEmulatedStorage()
03-21 08:36:11.575  3115  3115 I libpersona: KNOX_SDCARD checking this for 1000
03-21 08:36:11.575  3115  3115 E Zygote  : v2
03-21 08:36:11.575  3115  3115 I libpersona: KNOX_SDCARD not a persona
,03-21 08:36:11.585  3115  3115 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 08:36:11.585  3115  3115 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-21 08:36:11.585  1018  1046 I ActivityManager: Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3115 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-21 08:36:11.585  3115  3115 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-21 08:36:11.585  1018  1046 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,03-21 08:36:11.585  1018  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:11.585  1018  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:11.585  1018  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:11.585  1018  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:11.605  3130  3130 E Zygote  : MountEmulatedStorage()
03-21 08:36:11.605  3130  3130 E Zygote  : v2
,03-21 08:36:11.605  3130  3130 I libpersona: KNOX_SDCARD checking this for 10152
03-21 08:36:11.605  3130  3130 I libpersona: KNOX_SDCARD not a persona
,03-21 08:36:11.605  3130  3130 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 08:36:11.605  1876  1876 I SamsungIME: getDebugLevel  : 0x4f4c,
03-21 08:36:11.605  1018  1046 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=3130 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
03-21 08:36:11.605  1018  1018 D ActivityManager: startService callerProcessName:android, calleePkgName: android
03-21 08:36:11.605  1018  1018 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.DrmEventService; callingUser = 0; userId(target) = 0
03-21 08:36:11.615  3130  3130 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 08:36:11.615  1018  1558 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
03-21 08:36:11.615  1018  1558 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,03-21 08:36:11.615  1018  1558 W ActivityManager: userId = 0, bbcId = -10000
,03-21 08:36:11.615  1018  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 08:36:11.615  1018  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-21 08:36:11.615  3130  3130 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 08:36:11.615  3115  3115 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 08:36:11.625  3115  3115 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:11.655  3130  3130 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 08:36:11.655   283   522 D WVMDrmPlugIn: WVMDrmPlugin::onInitialize : 423
03-21 08:36:11.655   283   522 D WVMDrmPlugIn: WVMDrmPlugin::onSetOnInfoListener : add 423
,03-21 08:36:11.655  3130  3130 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:11.665  1018  3148 I DrmEventService: action event :android.intent.action.BOOT_COMPLETED
,03-21 08:36:11.665  1018  1363 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
03-21 08:36:11.665  1018  1363 D SecContentProvider2: mCursor = null
,03-21 08:36:11.675  1018  1018 I TimaServiceEventReceiver: TimaServiceEventReceiver : onReceive
,03-21 08:36:11.685   283   283 I ANDROID_DRM_FRWORKS_DrmManager: DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
,03-21 08:36:11.685  1239  1239 D MediaScannerReceiver: action: android.intent.action.BOOT_COMPLETED
,03-21 08:36:11.695  3115  3115 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-21 08:36:11.695  1018  1031 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
,03-21 08:36:11.695  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,03-21 08:36:11.695  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-21 08:36:11.695  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 08:36:11.695  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-21 08:36:11.715  1469  1469 E CscReceiver: onReceive android.intent.action.BOOT_COMPLETED
,03-21 08:36:11.715  1018  1030 D ActivityManager: startService callerProcessName:com.android.phone, calleePkgName: com.samsung.sec.android.application.csc
03-21 08:36:11.715  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.sec.android.application.csc/com.samsung.sec.android.application.csc.CscUpdateService; callingUser = 0; userId(target) = 0
,03-21 08:36:11.725  3115  3115 D BluetoothBDAdrressReceiver: onReceive(), action: android.intent.action.BOOT_COMPLETED
,03-21 08:36:11.735  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-21 08:36:11.735  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 08:36:11.735  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,03-21 08:36:11.735  3115  3115 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,03-21 08:36:11.735  1018  1363 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
03-21 08:36:11.735  1018  1363 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MediaScannerService; callingUser = 0; userId(target) = 0
,03-21 08:36:11.735  1018  1363 W ActivityManager: userId = 0, bbcId = -10000
,03-21 08:36:11.735  1018  1363 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 08:36:11.735  1018  1363 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-21 08:36:11.735  1018  1508 D ActivityManager: startService callerProcessName:com.sec.android.app.bluetoothtest, calleePkgName: com.sec.android.app.bluetoothtest
03-21 08:36:11.735  1018  1508 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
,03-21 08:36:11.735  1018  1508 W ActivityManager: userId = 0, bbcId = -10000
,03-21 08:36:11.745  1018  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 08:36:11.745  1018  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,03-21 08:36:11.745  1018  1504 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.providers.context, hostingType: broadcast
,03-21 08:36:11.745  1876  1876 I SamsungIME: getDebugLevel  : 0x4f4c
03-21 08:36:11.745  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:11.745  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:11.745  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:11.745  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:11.755  1469  1469 D CscUpdateService: onStart
,03-21 08:36:11.755  1469  1469 E CscUpdateService: costomer file is exists : it has been preconfiged.
03-21 08:36:11.755  1469  1469 I CscUpdateService: set_CSC_version
03-21 08:36:11.755  1469  1469 E CscParser: update(): xml file exist
,03-21 08:36:11.755  3130  3130 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,03-21 08:36:11.755  3151  3151 E Zygote  : MountEmulatedStorage()
03-21 08:36:11.765  3151  3151 I libpersona: KNOX_SDCARD checking this for 10003
03-21 08:36:11.765  3151  3151 E Zygote  : v2
03-21 08:36:11.765  3151  3151 I libpersona: KNOX_SDCARD not a persona
03-21 08:36:11.765  3151  3151 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 08:36:11.765  1018  1504 I ActivityManager: Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=3151 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,03-21 08:36:11.765  1876  1876 I SamsungIME: KeybaordView init() : load resources
,03-21 08:36:11.765  3151  3151 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 08:36:11.765  3151  3151 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 08:36:11.785  1018  1504 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,03-21 08:36:11.795  1469  1469 I CscUtil : isWifiOnly = false,
03-21 08:36:11.795  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:11.795  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:11.795  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:11.795  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:11.795  1469  1469 I System.out: HandDataNode = null
,03-21 08:36:11.795  1469  1469 I CscUpdateService: PATH_CSCNAME =CustomerDataSet.CSCName
03-21 08:36:11.805  2856  3052 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 08:36:11.805  1469  1469 I CscUpdateService: This is normal boot : CSC not updated
03-21 08:36:11.805  3165  3165 I libpersona: KNOX_SDCARD checking this for 1000
03-21 08:36:11.805  3165  3165 E Zygote  : MountEmulatedStorage()
03-21 08:36:11.805  3165  3165 I libpersona: KNOX_SDCARD not a persona
03-21 08:36:11.805  3165  3165 E Zygote  : v2
03-21 08:36:11.815  1018  1504 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=3165 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-21 08:36:11.805  3165  3165 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 08:36:11.815  1018  1504 I ActivityManager: Killing 2238:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
03-21 08:36:11.805  3165  3165 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 08:36:11.815  3151  3151 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 08:36:11.815  3151  3151 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:11.815  3165  3165 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 08:36:11.835  1018  1334 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
03-21 08:36:11.835  1018  1334 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,03-21 08:36:11.835  1018  1334 W ActivityManager: userId = 0, bbcId = -10000
03-21 08:36:11.835  1018  1334 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-21 08:36:11.835  1018  1334 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,03-21 08:36:11.845  1469  3171 E CscParser: update(): xml file exist
,03-21 08:36:11.865  1469  1469 I CscUpdateService: same CSC Version
,03-21 08:36:11.865  1469  1469 D CscUtil : Set Build Fingerprint to samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
,03-21 08:36:11.865  1239  3150 D MediaScannerService: !@start scanning volume internal: [/system/media, /oem/media]
,03-21 08:36:11.865  1018  1504 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
03-21 08:36:11.865  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,03-21 08:36:11.865  1469  3171 D CscGPS  : CSCGPS.updateParameters
03-21 08:36:11.865  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
03-21 08:36:11.865  1018  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 08:36:11.865  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-21 08:36:11.865  1469  3171 D CscGPS  : supl host : null
03-21 08:36:11.865  1469  3171 D CscGPS  : SUPL Host is null or invalid
03-21 08:36:11.865  1469  3171 D CscGPS  : supl_ver : null
03-21 08:36:11.865  1469  3171 D CscGPS  : SUPL Ver is null or invalid
03-21 08:36:11.865  1469  3171 D CscGPS  : supl port : null
03-21 08:36:11.865  1469  3171 D CscGPS  : SUPL PORT is null or invalid
03-21 08:36:11.865  1469  3171 D CscGPS  : LPP : null
03-21 08:36:11.865  1469  3171 D CscGPS  : LPP is null or invalid
03-21 08:36:11.865  1469  3171 D CscGPS  : CSC don't have any AGPS value.
,03-21 08:36:11.875  1018  2994 D ActivityManager: startProcessLocked calleePkgName: org.simalliance.openmobileapi.service, hostingType: broadcast
,03-21 08:36:11.875  1469  1469 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-21 08:36:11.875  1018  2994 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:11.875  1018  2994 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:11.875  1018  2994 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:11.875  1018  2994 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:11.885  1469  1469 D BluetoothBDTestService: onCreate()
,03-21 08:36:11.885  1469  1469 E BluetoothBDTestService: onStart(), extra_type: BOOT_COMPLETED
03-21 08:36:11.885  1469  1469 E BluetoothBDTestService: bd_address_path: /efs/bluetooth/bt_addr
,03-21 08:36:11.885  1469  1469 E BluetoothBDTestService: already exist!( /efs/bluetooth/bt_addr ), file length: 17
,03-21 08:36:11.885  3165  3165 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 08:36:11.895  3165  3165 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:11.895  3191  3191 E Zygote  : MountEmulatedStorage()
,03-21 08:36:11.895  3191  3191 E Zygote  : v2
03-21 08:36:11.895  3191  3191 I libpersona: KNOX_SDCARD checking this for 1101
03-21 08:36:11.895  3191  3191 I libpersona: KNOX_SDCARD not a persona
,03-21 08:36:11.895  3191  3191 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 08:36:11.895  3191  3191 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 08:36:11.895  1018  2994 I ActivityManager: Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=3191 uid=1101 gids={41101, 9997} abi=armeabi-v7a
,03-21 08:36:11.905  3191  3191 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 08:36:11.905  1876  1876 I SamsungIME: getCurrentKeyboard
03-21 08:36:11.905  1876  1876 I SamsungIME: getTextKeyboard
,03-21 08:36:11.905  1239  1239 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
,03-21 08:36:11.915   289   289 E SMD     : DCD OFF,
,03-21 08:36:11.925  1018  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
,03-21 08:36:11.925  2949  3101 D jxcore_app_log: JniHelper::setJavaVM(0xb7dfd450), pthread_self() = -1204406640
,03-21 08:36:11.925  1018  1045 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.libraries.social.autobackup.AutoBackupSyncService; callingUser = 0; userId(target) = 0
,03-21 08:36:11.925  3165  3165 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-21 08:36:11.935  1876  1876 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-21 08:36:11.935  2949  3101 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-21 08:36:11.935  2949  3101 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-21 08:36:11.935  2949  3101 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-21 08:36:11.935  2949  3101 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-21 08:36:11.935  2949  3101 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-21 08:36:11.935  2949  3101 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a7d8772 added. We now have 1 listener(s)
,03-21 08:36:11.945  3191  3191 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 08:36:11.945  3191  3191 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:11.955  1018  1045 I ActivityManager: Killing 2294:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
,03-21 08:36:11.975  2949  3101 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,03-21 08:36:11.975  2949  3101 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,03-21 08:36:11.975  2949  3101 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-21 08:36:11.975   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-21 08:36:11.975  2949  3101 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-21 08:36:11.985  1018  1045 W libprocessgroup: failed to open /acct/uid_10050/pid_2238/cgroup.procs: No such file or directory
,03-21 08:36:12.005  2949  3101 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-21 08:36:12.005  2949  3101 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-21 08:36:12.005  2949  3101 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-21 08:36:12.005  2949  3101 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
03-21 08:36:12.005  2949  3101 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-21 08:36:12.005  2949  3101 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-21 08:36:12.005  2949  3101 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-21 08:36:12.005  2949  3101 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-21 08:36:12.005  2949  3101 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-21 08:36:12.005  2949  3101 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-21 08:36:12.005  2949  3101 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-21 08:36:12.005  2949  3101 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e6a379 added. We now have 1 listener(s)
,03-21 08:36:12.005  2949  3101 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-21 08:36:12.005  1469  1637 D TP/MmsProvider: Update uri=content://mms, match=0
,03-21 08:36:12.005  1469  1637 D TP/MmsProvider: update , handleReadChangedBroadcast
,03-21 08:36:12.005  1469  1637 D TP/MmsSmsProvider: need read changed broadcast:false
,03-21 08:36:12.015  2949  3101 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-21 08:36:12.025  2949  3101 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-21 08:36:12.025  2949  3101 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,03-21 08:36:12.025  3191  3191 W ResourcesManager: Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,03-21 08:36:12.025  2949  3101 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,03-21 08:36:12.025  2949  3101 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-21 08:36:12.025  1018  1314 D PersonaManagerService: getPersonasForUser(): returning null!
,03-21 08:36:12.035  2949  3101 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-21 08:36:12.035  2378  2378 I Mms:transaction: [MmsSystemEventReceiver] restorePduNotificationStatus count=0
,03-21 08:36:12.035  2378  2378 D Mms/MessagingNotification: [start]    nonBlockingUpdateMessageIndicator() consume time = 5234.65031
,03-21 08:36:12.035  2378  2378 I Mms/ReservationManager: resetAfterConnected()
03-21 08:36:12.035  2949  3101 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,03-21 08:36:12.045  2378  3213 D Mms/MessagingNotification: sDisableVibrateForCamera = false
,03-21 08:36:12.045  2378  3213 D Mms/TelephonyPermission: isDefault true
,03-21 08:36:12.055  1469  1483 D TP/MmsSmsProvider: query,matched:7, calling pid = 2378
,03-21 08:36:12.055  1469  1757 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2378
03-21 08:36:12.055  3191  3191 V SmartcardService: main Received broadcast
03-21 08:36:12.055  3191  3191 V SmartcardService: Starting smartcard service after boot completed
,03-21 08:36:12.055  1469  1483 D TP/MmsSmsProvider: match 7:Elapsed time : 4.014 ms
,03-21 08:36:12.055  1018  1031 D ActivityManager: startService callerProcessName:org.simalliance.openmobileapi.service, calleePkgName: org.simalliance.openmobileapi.service
03-21 08:36:12.055  1018  1031 D ActivityManager: retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
,03-21 08:36:12.055  2949  3101 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 08:36:12.055  2949  3101 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 08:36:12.055  2949  3101 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-21 08:36:12.055  2949  3101 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 08:36:12.055  2949  3101 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 08:36:12.055  2949  3101 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 08:36:12.055  2949  3101 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 08:36:12.055  2949  3101 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-21 08:36:12.055  2949  3101 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-21 08:36:12.055  2949  3101 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-21 08:36:12.055  2949  3101 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-21 08:36:12.065  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-21 08:36:12.065  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 08:36:12.065  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
,03-21 08:36:12.065   278   870 D EnterpriseController: uids 10120
03-21 08:36:12.065   278   870 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0,
03-21 08:36:12.065   278   870 D Netd    : getNetworkForDns: using netid 502 for uid 10120
,03-21 08:36:12.065  2949  2949 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-21 08:36:12.075  2949  2949 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-21 08:36:12.085  3165  3165 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,03-21 08:36:12.085  1018  2994 D ActivityManager: startService callerProcessName:com.android.phone, calleePkgName: com.android.stk
,03-21 08:36:12.085  1018  2994 D ActivityManager: retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
,03-21 08:36:12.085  1018  2994 W ActivityManager: userId = 0, bbcId = -10000
,03-21 08:36:12.085  1018  2994 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 08:36:12.085  1018  2994 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,03-21 08:36:12.095  3165  3217 I KnoxUsageLogPro: savePreference: key = previous_sys_time value = 1458545772104
,03-21 08:36:12.105  3165  3165 I KnoxUsageLogPro: premStatus:2
,03-21 08:36:12.105  1018  1508 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,03-21 08:36:12.105  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-21 08:36:12.105  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:12.105  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:12.105  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:12.105  3165  3165 I KnoxUsageLogPro: isEulaShown : false
,03-21 08:36:12.105  3165  3165 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,03-21 08:36:12.115  1239  3150 E SQLiteLog: (283) recovered 345 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
,03-21 08:36:12.125  3220  3220 E Zygote  : MountEmulatedStorage()
,03-21 08:36:12.125  3220  3220 E Zygote  : v2
03-21 08:36:12.125  3220  3220 I libpersona: KNOX_SDCARD checking this for 10157
03-21 08:36:12.125  3220  3220 I libpersona: KNOX_SDCARD not a persona
03-21 08:36:12.125  1018  1508 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=3220 uid=10157 gids={50157, 9997} abi=armeabi-v7a
03-21 08:36:12.125  3220  3220 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-21 08:36:12.135  3220  3220 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 08:36:12.135  1018  1508 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
03-21 08:36:12.135  3220  3220 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 08:36:12.135  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:12.135  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:12.135  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:12.135  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:12.145  3165  3217 I KnoxUsageLogPro: savePreference: key = previous_elapsed_time value = 37985
03-21 08:36:12.145  2949  2949 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-21 08:36:12.155  3233  3233 E Zygote  : MountEmulatedStorage()
,03-21 08:36:12.155  3233  3233 E Zygote  : v2
03-21 08:36:12.155  3233  3233 I libpersona: KNOX_SDCARD checking this for 10085
03-21 08:36:12.155  3233  3233 I libpersona: KNOX_SDCARD not a persona
03-21 08:36:12.155  3220  3220 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 08:36:12.155  3220  3220 D ActivityThread: Added TimaKeyStore provider
03-21 08:36:12.155  3233  3233 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 08:36:12.155  3233  3233 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 08:36:12.165  1018  1508 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=3233 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-21 08:36:12.165  3233  3233 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 08:36:12.165  1018  1508 I ActivityManager: Killing 1673:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,03-21 08:36:12.175  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-21 08:36:12.175  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-21 08:36:12.175  1189  1189 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-21 08:36:12.175  1189  1189 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-21 08:36:12.175  1189  1189 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-21 08:36:12.175  1189  1189 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-21 08:36:12.195  1469  1487 D TP/MmsSmsProvider: query,matched:200, calling pid = 2378
,03-21 08:36:12.195   306   306 I art     : Explicit concurrent mark sweep GC freed 8700(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.528ms total 43.044ms
,03-21 08:36:12.195  1469  1487 D TP/MmsSmsProvider: match 200:Elapsed time : 3.695 ms
,03-21 08:36:12.215  2378  2378 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0,
,03-21 08:36:12.215  3233  3233 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-21 08:36:12.215  3233  3233 D ActivityThread: Added TimaKeyStore provider,
,03-21 08:36:12.225  1469  1757 D TP/SmsProvider: query,matched:0, calling pid = 2378,
,03-21 08:36:12.225  1469  1757 D TP/SmsProvider: match 0:Elapsed time : 1.750 ms,
,03-21 08:36:12.225   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 2.281ms total 26.666ms
,03-21 08:36:12.255   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 18.844ms,
,03-21 08:36:12.265  1018  1031 D ActivityManager: startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
03-21 08:36:12.265  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,03-21 08:36:12.265  1018  1045 W libprocessgroup: failed to open /acct/uid_10113/pid_2294/cgroup.procs: No such file or directory
,03-21 08:36:12.265  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-21 08:36:12.265  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 08:36:12.265  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,03-21 08:36:12.265  1469  1487 D TP/SmsProvider: query,matched:51, calling pid = 2378
,03-21 08:36:12.265  1469  1487 D TP/SmsProvider: match 51:Elapsed time : 1.709 ms
,03-21 08:36:12.275  1018  2994 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
03-21 08:36:12.275  1018  2994 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
,03-21 08:36:12.275  3220  3220 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-21 08:36:12.275  1018  2994 W ActivityManager: userId = 0, bbcId = -10000
,03-21 08:36:12.275  1018  2994 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-21 08:36:12.275  1018  2994 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,03-21 08:36:12.285  3151  3251 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,03-21 08:36:12.285  1018  1504 D ActivityManager: startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
03-21 08:36:12.285  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
,03-21 08:36:12.285  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
03-21 08:36:12.285  1018  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 08:36:12.285  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
,03-21 08:36:12.295  1018  1045 W libprocessgroup: failed to open /acct/uid_10015/pid_1673/cgroup.procs: No such file or directory
,03-21 08:36:12.295  1018  1558 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.safetyassurance, hostingType: broadcast
,03-21 08:36:12.295  1018  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:12.295  3233  3233 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-21 08:36:12.295  3233  3233 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-21 08:36:12.295  1018  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:12.295  3233  3233 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-21 08:36:12.295  3233  3233 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-21 08:36:12.295  3233  3233 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-21 08:36:12.295  3233  3233 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
03-21 08:36:12.295  1018  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:12.295  1018  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:12.315  3256  3256 E Zygote  : MountEmulatedStorage()
03-21 08:36:12.315  3256  3256 E Zygote  : v2
03-21 08:36:12.315  3256  3256 I libpersona: KNOX_SDCARD checking this for 10048
03-21 08:36:12.315  3256  3256 I libpersona: KNOX_SDCARD not a persona
,03-21 08:36:12.315  3256  3256 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 08:36:12.315  3256  3256 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-21 08:36:12.315  3256  3256 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 08:36:12.315  1018  1558 I ActivityManager: Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3256 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-21 08:36:12.325  2378  3213 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
03-21 08:36:12.325  1018  1558 D ActivityManager: startProcessLocked calleePkgName: com.sec.dsm.system, hostingType: broadcast
,03-21 08:36:12.325  1239  3150 D MediaScanner: Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,03-21 08:36:12.325  2121  2121 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
03-21 08:36:12.325  1018  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:12.325  2121  2121 I dhcpcd  : wlan0: no IPv6 Routers available
,03-21 08:36:12.325  1018  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:12.325  1018  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-21 08:36:12.325  1018  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:12.345  3268  3268 E Zygote  : MountEmulatedStorage()
03-21 08:36:12.345  3268  3268 I libpersona: KNOX_SDCARD checking this for 1000
03-21 08:36:12.345  3268  3268 E Zygote  : v2
03-21 08:36:12.345  3268  3268 I libpersona: KNOX_SDCARD not a persona
03-21 08:36:12.345  3268  3268 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 08:36:12.345  3268  3268 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 08:36:12.345  1018  1558 I ActivityManager: Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3268 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-21 08:36:12.345  3268  3268 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 08:36:12.355  1018  1558 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,03-21 08:36:12.355  1018  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:12.355  1018  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:12.355  1018  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:12.355  1018  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:12.375  3281  3281 E Zygote  : MountEmulatedStorage(),
03-21 08:36:12.375  3281  3281 E Zygote  : v2
03-21 08:36:12.375  3281  3281 I libpersona: KNOX_SDCARD checking this for 10159
,03-21 08:36:12.375  3281  3281 I libpersona: KNOX_SDCARD not a persona
03-21 08:36:12.375  3281  3281 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 08:36:12.375  1018  1558 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=3281 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-21 08:36:12.375  1018  1558 I ActivityManager: Killing 2359:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31,
,03-21 08:36:12.375  3281  3281 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 08:36:12.375  3281  3281 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
,03-21 08:36:12.385  3256  3256 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 08:36:12.385  3256  3256 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:12.395  3268  3268 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 08:36:12.395  3268  3268 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:12.415  2949  2964 I art     : Background partial concurrent mark sweep GC freed 10552(707KB) AllocSpace objects, 6(261KB) LOS objects, 39% free, 10MB/17MB, paused 5.162ms total 97.580ms
,03-21 08:36:12.415  2378  2378 D Mms/SmsReceiverService: onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
,03-21 08:36:12.425  2378  3294 D Mms/TelephonyPermission: isDefault true
03-21 08:36:12.425  2378  3294 D Mms/SmsReceiverService: [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
,03-21 08:36:12.425  2378  3294 D Mms/SmsReceiverService: [start]    handleBootCompleted() consume time = 386.34599
,03-21 08:36:12.435  3151  3251 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,03-21 08:36:12.435   345   345 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 3151
03-21 08:36:12.435   345   345 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,03-21 08:36:12.435  2970  2993 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,03-21 08:36:12.445  3151  3251 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
,03-21 08:36:12.455  3256  3256 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-21 08:36:12.455  3256  3256 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-21 08:36:12.455  3256  3256 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,03-21 08:36:12.455  3151  3251 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,03-21 08:36:12.465   345   345 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 3151
03-21 08:36:12.465   345   345 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,03-21 08:36:12.465  3281  3281 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 08:36:12.465  3281  3281 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:12.495  1018  1314 I ActivityManager: Killing 2396:com.sec.android.omc/1000 (adj 15): empty #31
,03-21 08:36:12.525  2970  2993 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-21 08:36:12.525  2970  2993 D BadgeProvider: sendNotify, [notify] : null
03-21 08:36:12.525  2970  2993 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-21 08:36:12.525  2970  2993 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-21 08:36:12.525  2970  2993 D BadgeProvider: update, [UpdateCount] : 1
03-21 08:36:12.525  1490  1490 D Launcher.Model: reloadBadges entered.
,03-21 08:36:12.525  2378  3213 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-21 08:36:12.525  1018  1507 D SettingsProvider: name = next_alarm_formatted
03-21 08:36:12.525  1018  1507 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 08:36:12.525  1018  1507 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 08:36:12.525  1018  1507 D SettingsProvider: selectionArgs: false
03-21 08:36:12.525  1018  1507 D SettingsProvider: selectionArgs: 10085
03-21 08:36:12.525  1018  1507 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 08:36:12.525  1018  1507 D SettingsProvider: ret = -1
,03-21 08:36:12.535  1018  1507 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10085
,03-21 08:36:12.545  2378  3213 D Mms/MessagingNotification: remove alarm
,03-21 08:36:12.565  1018  1099 V AlarmManager: waitForAlarm result :8
,03-21 08:36:12.565  1018  1099 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-21 08:36:12.575  1189  1189 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-21 08:36:12.625  2378  3303 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-21 08:36:12.645  1469  1637 I art     : Explicit concurrent mark sweep GC freed 39920(2MB) AllocSpace objects, 11(176KB) LOS objects, 39% free, 7MB/13MB, paused 933us total 88.743ms
,03-21 08:36:12.645  1469  1637 D TP/SmsProvider: query,matched:0, calling pid = 2378
,03-21 08:36:12.645  1469  1637 D TP/SmsProvider: match 0:Elapsed time : 1.888 ms
,03-21 08:36:12.695  1018  1144 I art     : Explicit concurrent mark sweep GC freed 25498(1279KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 26MB/39MB, paused 2.472ms total 230.241ms
,03-21 08:36:12.695  1018  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2359/cgroup.procs: No such file or directory
,03-21 08:36:12.715  2378  3213 D Mms/MessagingNotification: [end]    nonBlockingUpdateMessageIndicator() consume time = 289.701354
,03-21 08:36:12.715  1018  1504 D SettingsProvider: name = block_emergency_message
,03-21 08:36:12.715  1018  1504 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-21 08:36:12.715  1018  1504 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-21 08:36:12.715  1018  1504 D SettingsProvider: selectionArgs: false
,03-21 08:36:12.715  1018  1504 D SettingsProvider: selectionArgs: 10048
,03-21 08:36:12.725  1018  1504 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 08:36:12.725  1018  1504 D SettingsProvider: ret = -1
,03-21 08:36:12.735  1018  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2396/cgroup.procs: No such file or directory,
,03-21 08:36:12.735  1018  1507 W ActivityManager: getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
,03-21 08:36:12.755  1469  1487 D TP/MmsSmsProvider: getThreadUnReadCount unreadCount=0 imUnreadCount=0
,03-21 08:36:12.765  1469  1487 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775806
,03-21 08:36:12.765  3268  3268 E SQLiteLog: (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
,03-21 08:36:12.765  1018  1507 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,03-21 08:36:12.765  1018  1507 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
,03-21 08:36:12.765  1018  1507 W ActivityManager: userId = 0, bbcId = -10000
,03-21 08:36:12.765  1018  1507 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 08:36:12.765  1018  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,03-21 08:36:12.775  3281  3281 I Intent to TravelDirActivity: inside TravelBroadcastReceiver
,03-21 08:36:12.785  1469  1487 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-21 08:36:12.785  1469  1487 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775806
,03-21 08:36:12.785  1469  1487 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,03-21 08:36:12.785  1239  3150 V MediaScanner: processDirectory :  /system/media
,03-21 08:36:12.785  1469  1487 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-21 08:36:12.785  1469  1487 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-21 08:36:12.785  1469  1487 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-21 08:36:12.785  1469  1487 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-21 08:36:12.785  1469  1487 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-21 08:36:12.785  1469  1487 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-21 08:36:12.795  1311  1311 I WifiCredService: onCreate
,03-21 08:36:12.805  1018  1334 D ActivityManager: startProcessLocked calleePkgName: com.sec.usbsettings, hostingType: broadcast
,03-21 08:36:12.805  1018  1334 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:12.805  1018  1334 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:12.805  1018  1334 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:12.805  1018  1334 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:12.815  3268  3268 D DSM     : [Lines:107] Normal booted
03-21 08:36:12.815  3268  3268 D DSM     : [Lines:114] Boot completed
03-21 08:36:12.825  3311  3311 E Zygote  : MountEmulatedStorage()
03-21 08:36:12.825  3311  3311 I libpersona: KNOX_SDCARD checking this for 1000
03-21 08:36:12.825  3311  3311 E Zygote  : v2
03-21 08:36:12.825  3311  3311 I libpersona: KNOX_SDCARD not a persona
03-21 08:36:12.825  3311  3311 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-21 08:36:12.825  1018  1334 I ActivityManager: Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=3311 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-21 08:36:12.825  1018  1334 I ActivityManager: Killing 2426:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,03-21 08:36:12.825  3311  3311 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 08:36:12.825  3311  3311 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 08:36:12.835  1311  1311 D WifiTimerReceiver: action: android.intent.action.BOOT_COMPLETED
03-21 08:36:12.835  1311  1311 D WifiTimerReceiver: extra: Bundle[mParcelledData.dataSize=84]
03-21 08:36:12.835  1311  1311 D MY_TAG  : Action boot completed received
,03-21 08:36:12.835  1018  1334 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.factorykeystring, hostingType: broadcast
,03-21 08:36:12.835  1311  1311 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
03-21 08:36:12.835  1018  1334 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:12.835  1018  1334 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:12.835  1018  1334 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:12.835  1018  1334 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:12.835  1018  1145 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,03-21 08:36:12.835  1018  1145 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-21 08:36:12.835  1018  1145 E WifiNative-wlan0: invaild command id : 215
,03-21 08:36:12.845  3321  3321 E Zygote  : MountEmulatedStorage()
03-21 08:36:12.845  3321  3321 E Zygote  : v2
03-21 08:36:12.845  3321  3321 I libpersona: KNOX_SDCARD checking this for 1000
03-21 08:36:12.845  3321  3321 I libpersona: KNOX_SDCARD not a persona
,03-21 08:36:12.845  3321  3321 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 08:36:12.855  3321  3321 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-21 08:36:12.855  3321  3321 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-21 08:36:12.855  3311  3311 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 08:36:12.865  3311  3311 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:12.865  1018  1334 I ActivityManager: Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3321 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-21 08:36:12.865  1018  1334 I ActivityManager: Killing 2436:com.sec.tcpdumpservice/1000 (adj 15): empty #31
,03-21 08:36:12.885  1311  1311 D NearbySettings: MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,03-21 08:36:12.885  1311  2640 V NearbySettings: MountReceiver.mPrefHandler - 7002
,03-21 08:36:12.885  1018  1031 D SettingsProvider: name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
,03-21 08:36:12.885  3321  3321 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 08:36:12.885  3321  3321 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:12.905  1311  1311 I NearbySettings: MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
03-21 08:36:12.905  1311  1311 I NearbySettings: MountReceiver.onReceive - Internal Path
,03-21 08:36:12.905  1189  1189 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-21 08:36:12.915  1018  1030 D SettingsProvider: name = personal_mode_enabled
,03-21 08:36:12.925  3321  3321 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-21 08:36:12.955  1018  1363 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,03-21 08:36:12.965  1018  1363 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:12.965  1018  1363 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:12.965  1018  1363 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:12.965  1018  1363 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:12.965  1469  1487 D TP/MmsSmsProvider: delete threadId: 9223372036854775806
,03-21 08:36:12.965  1469  1487 D TP/MmsSmsProvider: need read changed broadcast:false
03-21 08:36:12.965  1239  3150 V MediaScanner:  prescan time: 860ms (DB items: 141)
03-21 08:36:12.965  1239  3150 V MediaScanner:     scan time: 188ms (Caching mode: true), (makeEntry time: 71ms ~37%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-21 08:36:12.965  1239  3150 V MediaScanner: postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-21 08:36:12.965  1239  3150 V MediaScanner:    total time: 1048ms
03-21 08:36:12.965  1239  3150 V MediaScanner: checked files: 133  directories : 6  (I: 0, U: 0)
,03-21 08:36:12.975   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-21 08:36:12.975  1469  1469 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-21 08:36:12.975  1469  1469 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-21 08:36:12.975  1469  1469 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-21 08:36:12.975  1469  1469 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-21 08:36:12.975  1469  1469 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-21 08:36:12.975  1469  1469 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-21 08:36:12.975  1018  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2436/cgroup.procs: No such file or directory
,03-21 08:36:12.985  1239  3150 D MediaScanner: checkDefaultSounds,
03-21 08:36:12.985  1239  3150 D MediaScanner: system alarm_alert  : Vwiurug_etwofi5wgg
,03-21 08:36:12.995  3345  3345 E Zygote  : MountEmulatedStorage()
03-21 08:36:12.995  3345  3345 E Zygote  : v2
03-21 08:36:12.995  3345  3345 I libpersona: KNOX_SDCARD checking this for 10160
03-21 08:36:12.995  3345  3345 I libpersona: KNOX_SDCARD not a persona
,03-21 08:36:12.995  3345  3345 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 08:36:12.995  3345  3345 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 08:36:12.995  3345  3345 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 08:36:13.005  1018  1363 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=3345 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a,
03-21 08:36:13.005  1018  1363 I ActivityManager: Killing 2348:com.sec.android.app.mt/1000 (adj 15): empty #31
03-21 08:36:13.005  3321  3321 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-21 08:36:13.015  2378  3294 D Mms/Conversation: deleteTempConversation(),deleted=0
,03-21 08:36:13.025  1311  1311 I SmartcardBootCompleteReceiver: SmartcardBootCompleteReceiver - onReceive() 
03-21 08:36:13.025  1311  1311 I SmartcardBootCompleteReceiver: Received intent with action - android.intent.action.BOOT_COMPLETED
,03-21 08:36:13.025  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
03-21 08:36:13.025  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
,03-21 08:36:13.035  3345  3345 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 08:36:13.035  1239  3150 D MediaScanner: OK. alarm_alert is already exist in setting DB.
,03-21 08:36:13.035  3321  3321 I LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
,03-21 08:36:13.045  3345  3345 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:13.045  1311  1311 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
,03-21 08:36:13.045  2949  3216 W jxcore-log: Initializing JXcore engine
,03-21 08:36:13.055  2949  3216 W jxcore-log: JXcore engine is ready
,03-21 08:36:13.055  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,03-21 08:36:13.065  1239  3150 D MediaScanner: system notification_sound  : K_Oprkltf5wgg
,03-21 08:36:13.065  1469  1483 D SmsProvider: Update uri=content://sms/outbox, match=8
,03-21 08:36:13.065  1311  1311 I SmartcardBootCompleteReceiver: Broadcast sent with current lockscreen type
,03-21 08:36:13.075  3345  3345 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-21 08:36:13.085  1018  1045 W libprocessgroup: failed to open /acct/uid_10131/pid_2426/cgroup.procs: No such file or directory
03-21 08:36:13.085  1018  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2348/cgroup.procs: No such file or directory
,03-21 08:36:13.095  1239  3150 D MediaScanner: OK. notification_sound is already exist in setting DB.
,03-21 08:36:13.095  3233  3233 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 510.556ms
,03-21 08:36:13.095  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
03-21 08:36:13.095  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
03-21 08:36:13.095  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
03-21 08:36:13.095  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
03-21 08:36:13.095  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
03-21 08:36:13.095  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
03-21 08:36:13.095  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
03-21 08:36:13.095  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
03-21 08:36:13.095  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
,03-21 08:36:13.095  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
03-21 08:36:13.095  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
03-21 08:36:13.095  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
03-21 08:36:13.095  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
,03-21 08:36:13.095  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
03-21 08:36:13.095  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
,03-21 08:36:13.095  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
03-21 08:36:13.095  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
03-21 08:36:13.095  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
,03-21 08:36:13.095  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
,03-21 08:36:13.095  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
,03-21 08:36:13.095  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
,03-21 08:36:13.105  1239  3150 D MediaScanner: system ringtone  : Wmfi_lpf_pwirywu5wgg
03-21 08:36:13.105  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
,03-21 08:36:13.105  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
,03-21 08:36:13.105  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
03-21 08:36:13.105  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
,03-21 08:36:13.105  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
,03-21 08:36:13.105  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
03-21 08:36:13.105  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
,03-21 08:36:13.105  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
,03-21 08:36:13.105  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
,03-21 08:36:13.105  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
03-21 08:36:13.105  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
,03-21 08:36:13.105  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
,03-21 08:36:13.105  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
,03-21 08:36:13.105  3321  3321 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
,03-21 08:36:13.105  3321  3321 I LcdtestApp: [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
,03-21 08:36:13.115  1469  1483 D TP/MmsSmsProvider: need read changed broadcast:false
,03-21 08:36:13.115  1951  1951 E audit   : type=1400 msg=audit(1458545773.115:205): avc:  denied  { ioctl } for  pid=3216 comm="Thread-370" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-21 08:36:13.115  1951  1951 E audit   :  SEPF_SM-A500FU_5.0.2-1_0038
,03-21 08:36:13.115  1951  1951 E audit   : type=1300 msg=audit(1458545773.115:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9b0c68f8 items=0 ppid=306 ppcomm=main pid=3216 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-370" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-21 08:36:13.115  1951  1951 E audit   : type=1320 msg=audit(1458545773.115:205): 
,03-21 08:36:13.125  1239  3150 D MediaScanner: OK. ringtone is already exist in setting DB.
,03-21 08:36:13.125  2949  3216 W jxcore-log: Starting JXcore engine
,03-21 08:36:13.125  1018  1508 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,03-21 08:36:13.135  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:13.135  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:13.135  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:13.135  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:13.155  3363  3363 E Zygote  : MountEmulatedStorage()
03-21 08:36:13.155  3363  3363 E Zygote  : v2
,03-21 08:36:13.155  3363  3363 I libpersona: KNOX_SDCARD checking this for 1000
03-21 08:36:13.155  3363  3363 I libpersona: KNOX_SDCARD not a persona
,03-21 08:36:13.155  1018  1508 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3363 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-21 08:36:13.155  1018  1508 I ActivityManager: Killing 2486:com.wsomacp/u0a25 (adj 15): empty #31
,03-21 08:36:13.165  3363  3363 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 08:36:13.175  2378  3294 D Mms/SmsReceiverService: moveOutboxMessagesToFailedBox messageCount: 0
03-21 08:36:13.175  2378  3294 D Mms/SmsReceiverService: handle boot completed, sendFirstQueuedMessage()
03-21 08:36:13.175  3363  3363 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 08:36:13.175  2378  3294 D Mms/SmsReceiverService: [SIM-1]sendFirstQueuedMessage()
,03-21 08:36:13.175  3363  3363 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 08:36:13.245   345   345 W SecureStorage: [WARN]: SPID(0x00000002)counter 0, error: #11, Try again
,03-21 08:36:13.255  2742  2742 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2742) action= = android.intent.action.MEDIA_SCANNER_FINISHED
,03-21 08:36:13.255  2742  2742 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2742) ACTION_MEDIA_SCANNER_FINISHED = /system/media
,03-21 08:36:13.255  2742  2742 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2742) ACTION_MEDIA_SCANNER_FINISHED = Ignored
,03-21 08:36:13.255  1311  1311 D [SBeam] : SBeamEnabler.initPreferenceForSbeam : 0
,03-21 08:36:13.255  1239  3150 D MediaScannerService: !@done scanning volume internal
,03-21 08:36:13.255  2949  3216 W jxcore-log: Platform android
03-21 08:36:13.255  2949  3216 W jxcore-log: 
,03-21 08:36:13.255  2949  3216 W jxcore-log: Process ARCH arm
03-21 08:36:13.255  2949  3216 W jxcore-log: 
,03-21 08:36:13.275  3363  3363 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 08:36:13.285  3363  3363 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:13.295  1239  3150 D MediaScannerService: !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
,03-21 08:36:13.295  1311  1311 I SettingSearch/SearchIntentReceiver: action : android.intent.action.BOOT_COMPLETED
,03-21 08:36:13.295  1311  1311 I SettingSearch/SearchIntentReceiver: search setting db init!!
,03-21 08:36:13.295  1311  1311 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,03-21 08:36:13.305  3345  3345 D [0]UMC:UMCContentProvider: @onCreate
,03-21 08:36:13.325  1469  1637 D TP/SmsProvider: query,matched:26, calling pid = 2378
,03-21 08:36:13.335  1311  3379 I SettingSearch/SearchIntentReceiver: BOOT_COMPLETED call InitSerachDBThread thread start!
03-21 08:36:13.335  1469  1637 D TP/SmsProvider: match 26:Elapsed time : 9.061 ms
,03-21 08:36:13.335  3345  3345 D [0]UMC:Core: onCreate(): 
03-21 08:36:13.335  3345  3345 D [0]UMC:Core: @isManagedProfileUser
03-21 08:36:13.335  3345  3345 D [0]UMC:Core: userId: 0
,03-21 08:36:13.345  1876  3203 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-21 08:36:13.355  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.wssyncmldm, hostingType: broadcast
,03-21 08:36:13.355  3345  3345 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
03-21 08:36:13.355  3345  3345 D [0]UMC:Core: userInfo.isManagedProfile() : false
,03-21 08:36:13.365  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:13.365  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:13.365  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:13.365  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:13.375  1239  3150 D MediaProvider: savePlaylistTableInBulkDeleter started
,03-21 08:36:13.385  3380  3380 E Zygote  : MountEmulatedStorage(),
03-21 08:36:13.385  3380  3380 E Zygote  : v2
,03-21 08:36:13.385  3380  3380 I libpersona: KNOX_SDCARD checking this for 1000
03-21 08:36:13.385  3380  3380 I libpersona: KNOX_SDCARD not a persona,
,03-21 08:36:13.385  3380  3380 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-21 08:36:13.385  1018  1031 I ActivityManager: Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3380 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-21 08:36:13.405  3380  3380 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 08:36:13.405  3380  3380 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 08:36:13.405  1018  1045 W libprocessgroup: failed to open /acct/uid_10025/pid_2486/cgroup.procs: No such file or directory
,03-21 08:36:13.405  1239  3150 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,03-21 08:36:13.425  3380  3380 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 08:36:13.425  3380  3380 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:13.445  1018  2994 D ActivityManager: getContentProviderImpl callerProcessName:com.android.settings, calleePkgName: com.sec.providers.settingsearch
,03-21 08:36:13.445  1239  3150 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,03-21 08:36:13.445  1018  2994 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:13.445  1018  2994 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:13.445  1018  2994 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:13.445  1018  2994 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:13.445  1239  3150 D MediaProvider: savePlaylistTableInBulkDeleter finished
,03-21 08:36:13.445  1239  3150 D MediaProvider: savePlaylistTableInBulkDeleter started
,03-21 08:36:13.445  1239  3150 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
03-21 08:36:13.445  1239  3150 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,03-21 08:36:13.445  1239  3150 D MediaProvider: savePlaylistTableInBulkDeleter finished
,03-21 08:36:13.455  3395  3395 E Zygote  : MountEmulatedStorage()
,03-21 08:36:13.455  3395  3395 E Zygote  : v2
03-21 08:36:13.455  3395  3395 I libpersona: KNOX_SDCARD checking this for 10150
03-21 08:36:13.455  3395  3395 I libpersona: KNOX_SDCARD not a persona
,03-21 08:36:13.455  3395  3395 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 08:36:13.465  3395  3395 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-21 08:36:13.465  1018  2994 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3395 uid=10150 gids={50150, 9997} abi=armeabi-v7a
03-21 08:36:13.465  3395  3395 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-21 08:36:13.465  1239  3150 D MediaScanner: Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,03-21 08:36:13.465  1018  1507 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-21 08:36:13.465  1018  1507 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,03-21 08:36:13.475  1018  1507 W ActivityManager: userId = 0, bbcId = -10000
03-21 08:36:13.475  1018  1507 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 08:36:13.475  1018  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-21 08:36:13.475  2378  3294 D Mms/SmsReceiver: unregisterForServiceStateChanges, already unregistered
03-21 08:36:13.475  2378  3294 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-21 08:36:13.475  2378  3294 D Mms/TelephonyPermission: isDefault true
,03-21 08:36:13.485  3380  3380 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-21 08:36:13.495  3395  3395 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 08:36:13.495  3395  3395 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:13.505  3363  3363 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-21 08:36:13.515  2949  3216 I jxcore-log: JXcore Cordova bridge is ready!
03-21 08:36:13.515  2949  3216 I jxcore-log: 
,03-21 08:36:13.515  2949  3216 W jxcore-log: JXcore engine is started
,03-21 08:36:13.525  2949  3101 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-21 08:36:13.525  2949  2949 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
03-21 08:36:13.525  1469  1487 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2378
,03-21 08:36:13.535  2949  3216 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-21 08:36:13.535  2949  3216 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-21 08:36:13.545  3345  3345 D [0]UMC:DeviceInfo: USA==US==
,03-21 08:36:13.545  2949  2949 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,03-21 08:36:13.555  1239  3150 V MediaScanner: processDirectory :  /storage/emulated/0
,03-21 08:36:13.555  2949  2949 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,03-21 08:36:13.555  1018  1363 D FocusedStackFrame: Set to : 0
03-21 08:36:13.555  1018  1363 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-21 08:36:13.555  1018  1363 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-21 08:36:13.555  1018  1363 D InputDispatcher: Focused application set to: xxxx
03-21 08:36:13.555  1018  1363 D InputDispatcher: Focus left window: 2949
03-21 08:36:13.555  1239  3150 D MediaScanner: Skipping:
03-21 08:36:13.555  1239  3150 D MediaScanner: 7klwibgf7fvntblfd7(75ebcf7
03-21 08:36:13.565  1018  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-21 08:36:13.565  1018  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
03-21 08:36:13.565   258  1949 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (462 us)
03-21 08:36:13.565  1239  3150 D MediaScanner: Skipping:
03-21 08:36:13.565  1239  3150 D MediaScanner: 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,03-21 08:36:13.575  1239  3150 V MediaScanner: processDirectory :  /storage/extSdCard
03-21 08:36:13.575  1239  3150 W MediaScanner: Error opening directory, reason : Permission denied.
03-21 08:36:13.575  1239  3150 W MediaScanner: 7klwibgf7fxlKdCbid7
,03-21 08:36:13.575  1239  3150 V MediaScanner:  prescan time: 103ms (DB items: 27)
03-21 08:36:13.575  1239  3150 V MediaScanner:     scan time: 25ms (Caching mode: true), (makeEntry time: 18ms ~72%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 1ms ~4%)
03-21 08:36:13.575  1239  3150 V MediaScanner: postscan time: 3ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-21 08:36:13.575  1239  3150 V MediaScanner:    total time: 131ms
03-21 08:36:13.575  1239  3150 V MediaScanner: checked files: 10  directories : 17  (I: 0, U: 0)
,03-21 08:36:13.585  2949  2949 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,03-21 08:36:13.585  2949  2949 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
03-21 08:36:13.585  2949  3101 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 37ms. Plugin should use CordovaInterface.getThreadPool().
,03-21 08:36:13.595  1018  1144 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-21 08:36:13.595  1239  3150 D MediaScannerService: !@done scanning volume external
,03-21 08:36:13.595  1018  1144 W ActivityManager: mDVFSHelper.acquire()
,03-21 08:36:13.605  1018  1144 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-21 08:36:13.605  1018  1144 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-21 08:36:13.605  1018  1144 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-21 08:36:13.605  3380  3380 I FOTA    : [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,03-21 08:36:13.615  2742  2742 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2742) action= = android.intent.action.MEDIA_SCANNER_FINISHED
,03-21 08:36:13.615  2742  2742 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2742) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
03-21 08:36:13.615  2742  2742 D FactoryTestApp: [DummyFtClient$sendBootCompletedAndFinish](2742) ...
03-21 08:36:13.615  2742  2742 D FactoryTestApp: [Support$Values.getString](2742) id=MODEL_COMMUNICATION_MODE, value=gsm
03-21 08:36:13.615  2742  2742 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2742) mConnectionMode = gsm
,03-21 08:36:13.615  2742  2742 D FactoryTestApp: [IPCWriterToSecPhoneService$ResponseWriter](2742) Create IPCWriterToSecPhoneService
03-21 08:36:13.615  2742  2742 I FactoryTestApp: [IPCWriterToSecPhoneService$connectToSecPhoneService](2742)  
,03-21 08:36:13.615  2742  2742 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
,03-21 08:36:13.615  1018  1334 D ActivityManager: bindService callerProcessName:com.sec.factory, calleePkgName: com.sec.phone, action: null
03-21 08:36:13.615  1018  1334 D ActivityManager: retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,03-21 08:36:13.615  1018  1334 W ActivityManager: userId = 0, bbcId = -10000
,03-21 08:36:13.615  1018  1334 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 08:36:13.615  1018  1334 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
,03-21 08:36:13.625  1490  1490 D Launcher: onRestart, Launcher: 319777158
,03-21 08:36:13.635  1490  1490 D Launcher: onStart, Launcher: 319777158
,03-21 08:36:13.635  1490  1490 D Launcher.HomeView: onStart
03-21 08:36:13.635  1490  1490 D Launcher: onResume, Launcher: 319777158
,03-21 08:36:13.635  1018  1144 D SettingsProvider: name = kids_home_mode
03-21 08:36:13.635  1018  1144 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 08:36:13.635  1018  1144 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 08:36:13.635  1018  1144 D SettingsProvider: selectionArgs: false
03-21 08:36:13.635  1018  1144 D SettingsProvider: selectionArgs: 10007
03-21 08:36:13.635  1018  1144 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 08:36:13.635  1018  1144 D SettingsProvider: ret = -1
,03-21 08:36:13.635  1490  1490 D Launcher.HomeView: onResume
03-21 08:36:13.635  1018  1504 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.colorblind, hostingType: broadcast
,03-21 08:36:13.635  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:13.635  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:13.635  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:13.635  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:13.655  1018  1504 I ActivityManager: Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3416 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-21 08:36:13.655  3416  3416 E Zygote  : MountEmulatedStorage()
03-21 08:36:13.655  3416  3416 E Zygote  : v2
03-21 08:36:13.655  3416  3416 I libpersona: KNOX_SDCARD checking this for 1000
03-21 08:36:13.655  3416  3416 I libpersona: KNOX_SDCARD not a persona
03-21 08:36:13.655  3416  3416 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 08:36:13.665  3416  3416 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 08:36:13.665  3416  3416 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 08:36:13.675  1469  1757 D TP/MmsSmsProvider: query,matched:200, calling pid = 2378
,03-21 08:36:13.675  1469  1757 D TP/MmsSmsProvider: match 200:Elapsed time : 2.807 ms
,03-21 08:36:13.675  1018  1018 D SensorService: [SO] activate (ident=0xb8540470, enabled=0)
03-21 08:36:13.675  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
03-21 08:36:13.675  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-21 08:36:13.685  1490  1490 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-21 08:36:13.695  1018  1018 D SensorManager: unregisterListener ::   
,03-21 08:36:13.695  1018  1018 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-21 08:36:13.705  1490  1490 D MenuAppsGridFragment: onResume,
03-21 08:36:13.705  1018  1144 D ActivityManager: handle home activity for 0
03-21 08:36:13.705  1018  1144 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,03-21 08:36:13.705  1018  1144 D KnoxTimeoutHandler: post home show event for user 0
03-21 08:36:13.705  1018  1144 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-21 08:36:13.705  1018  1144 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-21 08:36:13.705  1018  1144 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-21 08:36:13.705  1018  1018 D SensorService: [SO] changed settle time [0],
03-21 08:36:13.705  1018  1018 D SensorService: [SO] setDelay [200000000]
03-21 08:36:13.705  1018  1018 D SensorService: [SO] activate (ident=0xb8540470, enabled=1)
,03-21 08:36:13.705  1018  1018 D SensorService: [SO] AR_init,
03-21 08:36:13.705  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-21 08:36:13.725  3416  3416 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 08:36:13.725  3416  3416 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:13.735  1018  1018 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
03-21 08:36:13.735  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
03-21 08:36:13.735  1018  1018 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-21 08:36:13.735  1018  1018 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-21 08:36:13.735  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-21 08:36:13.755   258   258 I SurfaceFlinger: id=12 createSurf (720x1280),1 flag=4, Mauncher
,03-21 08:36:13.755  1018  1049 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-21 08:36:13.765  2742  2742 I FactoryTestApp: [IPCWriterToSecPhoneService$onServiceConnected](2742) connected done
03-21 08:36:13.765  2742  2742 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2742) Send Response Message to SecPhone
03-21 08:36:13.765  2742  2742 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2742) Response ��
,03-21 08:36:13.765  1018  1049 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-21 08:36:13.775  1018  2994 D InputDispatcher: Focus entered window: 1490
,03-21 08:36:13.775  1018  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-21 08:36:13.775  1018  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
03-21 08:36:13.775  1490  1490 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-21 08:36:13.805  3363  3363 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-21 08:36:13.805  3416  3416 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-21 08:36:13.815  3363  3363 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-21 08:36:13.825  2768  2854 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,03-21 08:36:13.825  3380  3380 I DBG_DM  : [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,03-21 08:36:13.835  1490  1490 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-21 08:36:13.845  1018  1558 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-21 08:36:13.845  1189  1189 I StatusBar: Icon Only
03-21 08:36:13.845  3414  3414 D AndroidRuntime: 
03-21 08:36:13.845  3414  3414 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-21 08:36:13.845  1189  1189 D PanelView: There is/are notification(s) 
,03-21 08:36:13.855  3414  3414 D AndroidRuntime: CheckJNI is OFF
03-21 08:36:13.855  3414  3414 D AndroidRuntime: readGMSProperty: start
03-21 08:36:13.855  3414  3414 D AndroidRuntime: readGMSProperty: already setted!!
03-21 08:36:13.855  3414  3414 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-21 08:36:13.855  3414  3414 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-21 08:36:13.855  3414  3414 D AndroidRuntime: readGMSProperty: end
03-21 08:36:13.855  3414  3414 D AndroidRuntime: addProductProperty: start
,03-21 08:36:13.855  1018  3438 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-21 08:36:13.865  3363  3363 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,03-21 08:36:13.865  3363  3363 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
,03-21 08:36:13.865   312  1076 D AT_Distributor: Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,03-21 08:36:13.875  3363  3363 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
,03-21 08:36:13.875  3363  3363 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-21 08:36:13.875  2063  3404 I iu.UploadsManager: #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,03-21 08:36:13.875  3380  3380 I DBG_DM  : [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,03-21 08:36:13.885  3380  3380 I DBG_DM  : [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,03-21 08:36:13.885  2768  2854 D BluetoothMediaBrowser: no now playing list
03-21 08:36:13.885  2768  2854 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,03-21 08:36:13.905  2742  2742 D FactoryTestApp: [IPCWriterToSecPhoneService$handleMessage](2742) Send BOOTING COMPLETED done
03-21 08:36:13.905  2949  2949 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-21 08:36:13.905  1876  1876 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false,
,03-21 08:36:13.935  1018  1043 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-21 08:36:13.975   312  1076 D AT_Distributor: SetAtdStatus(), 1_1_0
03-21 08:36:13.975   312  1076 D AT_Distributor: Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,03-21 08:36:13.985  1018  1314 D ActivityManager: startProcessLocked calleePkgName: com.google.android.configupdater, hostingType: broadcast
,03-21 08:36:13.985  1018  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:13.985  1018  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:13.985  1018  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:13.985  1018  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:13.995  3448  3448 E Zygote  : MountEmulatedStorage()
,03-21 08:36:13.995  3448  3448 E Zygote  : v2
03-21 08:36:14.005  3448  3448 I libpersona: KNOX_SDCARD checking this for 10086
03-21 08:36:14.005  3448  3448 I libpersona: KNOX_SDCARD not a persona
03-21 08:36:14.005  3448  3448 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-21 08:36:14.005  3448  3448 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 08:36:14.005  3448  3448 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-21 08:36:14.005  1018  1314 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3448 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
,03-21 08:36:14.015  3414  3414 E AffinityControl: AffinityControl: registerfunction enter
,03-21 08:36:14.025   306   306 I art     : Explicit concurrent mark sweep GC freed 8761(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 623us total 26.008ms
,03-21 08:36:14.035  3448  3448 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 08:36:14.035  3448  3448 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:14.045  3414  3414 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-21 08:36:14.055   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 20.541ms
,03-21 08:36:14.055  1018  1558 D PackageManager: START PACKAGE DELETE: observer{6348616}
03-21 08:36:14.055  1018  1558 D PackageManager: pkg{<packageName>}
03-21 08:36:14.055  1018  1558 D PackageManager: user{0}
03-21 08:36:14.055  1018  1558 D PackageManager: caller{2000}
03-21 08:36:14.055  1018  1558 D PackageManager: flags{2}
,03-21 08:36:14.055  1018  1558 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-21 08:36:14.055  1018  1558 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-21 08:36:14.055  1018  1558 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-21 08:36:14.055  1018  1558 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-21 08:36:14.055  1018  1558 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,03-21 08:36:14.055  1018  1060 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-21 08:36:14.055  1018  1060 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-21 08:36:14.055  1018  1060 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-21 08:36:14.055  1018  1060 D ApplicationPolicy: getApplicationUninstallationEnabled
,03-21 08:36:14.055  1018  1060 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
03-21 08:36:14.055  1018  1060 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
03-21 08:36:14.065  1018  1046 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
03-21 08:36:14.065  1018  1046 I ActivityManager: Killing 2949:com.test.thalitest/u0a155 (adj 1): stop com.test.thalitest cause uninstall pkg
,03-21 08:36:14.065   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 18.356ms
,03-21 08:36:14.085  1018  1334 I ActivityManager: Killing 2515:com.sec.android.widgetapp.digitalclock/u0a88 (adj 15): empty #31
,03-21 08:36:14.105  1469  1483 D TP/SmsProvider: query,matched:0, calling pid = 2378
,03-21 08:36:14.105  1018  1046 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7,
03-21 08:36:14.105  1018  1046 W ActivityManager: mDVFSHelper.release()
03-21 08:36:14.105  1018  1046 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-21 08:36:14.115  1469  1483 D TP/SmsProvider: match 0:Elapsed time : 10.135 ms
,03-21 08:36:14.135  1490  1490 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@254aae7f time:40027
,03-21 08:36:14.135  1018  1051 D PersonaManager: isKioskContainerExistOnDevice
,03-21 08:36:14.145  1018  1043 D SensorService: [SO] currT = 40030110191, prevT = 39550078264, diff = 480031927, [0.077 0.421 10.132]
,03-21 08:36:14.145  1018  1043 D SensorService: [SO] 0.077 0.421 10.132
,03-21 08:36:14.145  1018  1043 D SensorService: [SO] [100 -> 255]
,03-21 08:36:14.145   258  1949 I SurfaceFlinger: id=11 Removed NainActivit (7/8),
,03-21 08:36:14.145   258   444 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-21 08:36:14.155   345   345 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
03-21 08:36:14.155   258  1949 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-21 08:36:14.185  3345  3345 D USER_AGENT: UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,03-21 08:36:14.205  3151  3251 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,03-21 08:36:14.205  3151  3251 I SecureStorage: [INFO]: SPID(0x00000002)Skip using SecureStorageExceptionJNI
,03-21 08:36:14.225  3345  3345 D [0]UMC:AdminManager: init - start
,03-21 08:36:14.245  3345  3345 D [0]UMC:AdminManager: loadAdmins
,03-21 08:36:14.295  1018  1051 I ActivityManager: Displayed Component not be shown by security: +698ms
,03-21 08:36:14.305  1018  1030 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.policydm
,03-21 08:36:14.305  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:14.305  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:14.305  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:14.305  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:14.305  1469  1757 D TP/SmsProvider: query,matched:51, calling pid = 2378
,03-21 08:36:14.325  3469  3469 E Zygote  : MountEmulatedStorage()
03-21 08:36:14.325  3469  3469 E Zygote  : v2
03-21 08:36:14.325  3469  3469 I libpersona: KNOX_SDCARD checking this for 1000
03-21 08:36:14.325  3469  3469 I libpersona: KNOX_SDCARD not a persona
,03-21 08:36:14.325  3469  3469 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 08:36:14.325  3345  3345 D [0]UMC:AdminManager: init - end
03-21 08:36:14.325  1469  1757 D TP/SmsProvider: match 51:Elapsed time : 13.666 ms
,03-21 08:36:14.325  3345  3345 D GSLBManager: migrateStoredUrlFromOldPref,
,03-21 08:36:14.325  3469  3469 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 08:36:14.325  3469  3469 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 08:36:14.335  3380  3380 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220,
03-21 08:36:14.335  3380  3380 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,03-21 08:36:14.335  3380  3380 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
03-21 08:36:14.335  1018  1030 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3469 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-21 08:36:14.345  1018  1363 E Tethering: No numeric data
,03-21 08:36:14.345  1018  1314 D ActivityManager: startService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm
03-21 08:36:14.345  1018  1314 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
03-21 08:36:14.345  1018  1314 W ActivityManager: userId = 0, bbcId = -10000
03-21 08:36:14.345  1018  1314 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 08:36:14.345  1018  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-21 08:36:14.345  1018  3466 E Tethering: No numeric data
,03-21 08:36:14.345  3345  3345 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
,03-21 08:36:14.355  1018  1060 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,03-21 08:36:14.355  3345  3345 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,03-21 08:36:14.355  1018  1508 E Tethering: No numeric data
03-21 08:36:14.355  3345  3345 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-21 08:36:14.355  3345  3345 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-21 08:36:14.355  3345  3345 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-21 08:36:14.355  3345  3345 D [0]UMC:UMCAdmin: isContainer : 0
,03-21 08:36:14.355  3380  3380 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,03-21 08:36:14.355  1018  1507 E Tethering: No numeric data
03-21 08:36:14.355  3380  3380 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,03-21 08:36:14.355  3380  3380 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,03-21 08:36:14.365  1018  1504 E Tethering: No numeric data
,03-21 08:36:14.365  1018  1507 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
03-21 08:36:14.365  1018  1508 E Tethering: No numeric data
03-21 08:36:14.365  3469  3469 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 08:36:14.365  3345  3345 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
03-21 08:36:14.365  3345  3345 D [0]UMC:UMCAdmin: isContainer : 0
03-21 08:36:14.365  3380  3380 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,03-21 08:36:14.375  3380  3380 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,03-21 08:36:14.375  3469  3469 D ActivityThread: Added TimaKeyStore provider
03-21 08:36:14.375  3345  3345 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
03-21 08:36:14.375  3380  3380 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,03-21 08:36:14.375  1018  1060 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
03-21 08:36:14.375  3380  3380 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,03-21 08:36:14.385  3380  3380 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,03-21 08:36:14.385  3380  3380 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
03-21 08:36:14.385  3380  3380 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
03-21 08:36:14.385  1018  2994 D ActivityManager: startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
03-21 08:36:14.385  1018  2994 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
03-21 08:36:14.385  3380  3380 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,03-21 08:36:14.385  1018  2994 W ActivityManager: userId = 0, bbcId = -10000
03-21 08:36:14.385  1018  2994 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-21 08:36:14.385  1018  2994 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,03-21 08:36:14.385  3380  3380 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
03-21 08:36:14.385  3380  3434 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,03-21 08:36:14.395  3345  3345 D [0]UMC:GuardService: @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
,03-21 08:36:14.395  3345  3345 D [0]UMC:CoreReceiver: Intent : android.intent.action.BOOT_COMPLETED
03-21 08:36:14.395  3345  3345 D [0]UMC:CoreReceiver:  check PreETag 
,03-21 08:36:14.425  3380  3434 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
03-21 08:36:14.425  3380  3434 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,03-21 08:36:14.435  3345  3345 D [0]UMC:CoreReceiver: bulk enrolled package: null
,03-21 08:36:14.435  3345  3345 V [0]UMC:ProfileStorage: Enter loadList
,03-21 08:36:14.445  3345  3345 D [0]UMC:CoreReceiver: handleAutoEnrollmentAndUMCAdminDeactivation
03-21 08:36:14.445  3345  3345 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,03-21 08:36:14.445  1018  1045 W libprocessgroup: failed to open /acct/uid_10088/pid_2515/cgroup.procs: No such file or directory
,03-21 08:36:14.445  1018  1018 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,03-21 08:36:14.455  3380  3380 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,03-21 08:36:14.455  1018  1508 D ActivityManager: bindService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm, action: null
03-21 08:36:14.455  1018  1508 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,03-21 08:36:14.455  1018  1508 W ActivityManager: userId = 0, bbcId = -10000
03-21 08:36:14.455  1018  1508 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 08:36:14.455  1018  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-21 08:36:14.465  3380  3380 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,03-21 08:36:14.465  3380  3380 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,03-21 08:36:14.465  3345  3345 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-21 08:36:14.465  1189  1189 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
,03-21 08:36:14.465  3380  3380 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
03-21 08:36:14.465  1189  1189 D OverheatReceiver: into the SAFE_MODE_ACTION
,03-21 08:36:14.465  1189  1189 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
,03-21 08:36:14.465  3380  3380 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,03-21 08:36:14.475  3345  3345 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-21 08:36:14.475  3345  3345 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-21 08:36:14.475  3345  3345 D [0]UMC:UMCAdmin: isContainer : 0
,03-21 08:36:14.475  1189  1189 D OverheatReceiver: isSafeMode = false
,03-21 08:36:14.475  3380  3380 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
,03-21 08:36:14.485  1018  1504 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,03-21 08:36:14.485  3345  3345 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
03-21 08:36:14.485  3345  3345 D [0]UMC:UMCAdmin: isContainer : 0
,03-21 08:36:14.485  3345  3345 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,03-21 08:36:14.505  3345  3345 D [0]UMC:ByodSetupStarter: Container ID : 0
,03-21 08:36:14.525  1876  1876 E SamsungIME: mOCRHelper is null
,03-21 08:36:14.535  1469  1469 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-21 08:36:14.545  1894  2106 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-21 08:36:14.545  1018  2853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.cB:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,03-21 08:36:14.555  1018  1105 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-21 08:36:14.565  3380  3434 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,03-21 08:36:14.565  1018  1132 V NetworkStats: removeUidsLocked() for UIDs [10155]
03-21 08:36:14.565  1018  1132 V NetworkStats: performPollLocked(flags=0x3)
,03-21 08:36:14.565  1018  1132 D NetworkStatsFactory: UpdateStatsForKnox updated
,03-21 08:36:14.565  1018  1132 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-21 08:36:14.575  1018  1132 V NetworkStats: performPollLocked() took 5ms
,03-21 08:36:14.575  1018  1314 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-21 08:36:14.575  1018  1314 W ActivityManager: userId = 0, bbcId = -10000
,03-21 08:36:14.575  1018  1314 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-21 08:36:14.585  1018  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-21 08:36:14.605  3345  3345 V [0]UMC:Utils: checkAppScreen() : com.sec.android.app.launcher
03-21 08:36:14.605  3345  3345 I [0]UMC:Core: shutdown
,03-21 08:36:14.605  1454  1454 D RegisteredComponentCache: Collect Tech packages for Knox
,03-21 08:36:14.605  2378  3294 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
,03-21 08:36:14.615  1469  1469 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED
,03-21 08:36:14.615  1018  1363 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,03-21 08:36:14.615  1018  1031 D SettingsProvider: name = internet_call_settings_visibility
,03-21 08:36:14.615  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 08:36:14.615  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-21 08:36:14.615  1018  1031 D SettingsProvider: selectionArgs: false
,03-21 08:36:14.615  1018  1363 W ActivityManager: userId = 0, bbcId = -10000
03-21 08:36:14.615  1018  1363 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 08:36:14.615  1018  1363 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,03-21 08:36:14.615  1018  1031 D SettingsProvider: selectionArgs: 1001
03-21 08:36:14.615  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-21 08:36:14.615  1018  1031 D SettingsProvider: ret = -1
,03-21 08:36:14.615  1469  1469 D PhoneUtilsCommon: isSupportVoLTE is false.
,03-21 08:36:14.625  1454  1454 D PersonaManager: isKioskContainerExistOnDevice
,03-21 08:36:14.625  3345  3345 D [0]UMC:GuardService: @GuardService - stopService Result = true
,03-21 08:36:14.625  3345  3345 I art     : System.exit called, status: 0
,03-21 08:36:14.635  3345  3345 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,03-21 08:36:14.655  1445  1445 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,03-21 08:36:14.655  1018  1504 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: android.telecom.InCallService
03-21 08:36:14.655  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,03-21 08:36:14.655  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
03-21 08:36:14.655  1018  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 08:36:14.655  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-21 08:36:14.655  1018  3492 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: com.samsung.incallui.SEC_IN_CALL_SERVICE
,03-21 08:36:14.655  1018  3492 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
,03-21 08:36:14.655  1018  3492 W ActivityManager: userId = 0, bbcId = -10000
,03-21 08:36:14.655  1018  3492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 08:36:14.655  1018  3492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-21 08:36:14.665  1018  1508 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,03-21 08:36:14.675  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:14.675  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:14.675  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:14.675  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:14.675  3448  3448 E UpdateRequestReceiver: ignoring update request
,03-21 08:36:14.685  1018  1508 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3497 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,03-21 08:36:14.685  3497  3497 E Zygote  : MountEmulatedStorage()
,03-21 08:36:14.685  3497  3497 E Zygote  : v2
03-21 08:36:14.685  3497  3497 I libpersona: KNOX_SDCARD checking this for 10057
03-21 08:36:14.685  3497  3497 I libpersona: KNOX_SDCARD not a persona,
,03-21 08:36:14.695  3497  3497 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 08:36:14.695  3497  3497 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-21 08:36:14.695  3497  3497 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-21 08:36:14.715  1445  1445 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,03-21 08:36:14.735  2970  2993 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,03-21 08:36:14.735  1018  1133 D NtpTrustedTime: forceRefresh() from cache miss
,03-21 08:36:14.735   278   870 D EnterpriseController: uids 1000
03-21 08:36:14.735   278   870 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-21 08:36:14.735   278   870 D Netd    : getNetworkForDns: using netid 502 for uid 1000
,03-21 08:36:14.735  1018  1363 I ActivityManager: Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3345)(adj 0) has died(187,1079),
,03-21 08:36:14.745  3380  3380 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,03-21 08:36:14.755  3448  3448 E UpdateRequestReceiver: ignoring update request
,03-21 08:36:14.765  1018  2994 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-21 08:36:14.765  1018  2994 D SecContentProvider2: mCursor = null
,03-21 08:36:14.765  1018  1018 D RCPManagerService: PackageReceiver onReceive()
,03-21 08:36:14.765  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-21 08:36:14.765  3380  3434 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,03-21 08:36:14.765  3380  3380 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
03-21 08:36:14.765  3380  3380 I DBG_DM  : [com.wssyncmldm.llllIIIllIlIIIIllllI(230/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
,03-21 08:36:14.775  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,03-21 08:36:14.775  3497  3497 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 08:36:14.775  3497  3497 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:14.785  3380  3434 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-21 08:36:14.785  1018  1018 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,03-21 08:36:14.795  1311  3379 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
,03-21 08:36:14.795  1311  3379 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
,03-21 08:36:14.795  1018  1018 D OTPFW   : OtpDbHelper::getInstance New instance created
,03-21 08:36:14.795  1335  1335 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-21 08:36:14.795  1335  1335 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-21 08:36:14.795  1335  1335 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-21 08:36:14.795  1018  1018 D OTPFW   : DBIntegrity::getInstance - New instance created
,03-21 08:36:14.805  1335  1335 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-21 08:36:14.815  1335  1335 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-21 08:36:14.815  1018  1018 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,03-21 08:36:14.815  1018  1018 I OTPFW   : ProvisionData::getAllEntries Enter
,03-21 08:36:14.815  1018  1018 E OTPFW   : ProvisionData::getAllEntries Table is empty
,03-21 08:36:14.825  3380  3434 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,03-21 08:36:14.825  3380  3434 I DBG_DM  : [IlIIlIIlIllllIlllIII(205/llIIIIlllllIIllIIllI)] Initialized
,03-21 08:36:14.825  3380  3434 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,03-21 08:36:14.825  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-21 08:36:14.825  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-21 08:36:14.825  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-21 08:36:14.825  1018  1018 V EnterpriseBillingPolicy: uID is 10155
03-21 08:36:14.825  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
03-21 08:36:14.825  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-21 08:36:14.825  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-21 08:36:14.825  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-21 08:36:14.825  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-21 08:36:14.825  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-21 08:36:14.825  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-21 08:36:14.825  1018  1051 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1d92c64d u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t15} time:40717
,03-21 08:36:14.835  1018  3491 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-21 08:36:14.835  1018  1060 I art     : Explicit concurrent mark sweep GC freed 33967(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 30MB/45MB, paused 10.130ms total 450.216ms
,03-21 08:36:14.835  1018  3492 E Tethering: No numeric data
,03-21 08:36:14.835  1018  3491 W ActivityManager: userId = 0, bbcId = -10000
03-21 08:36:14.835  1018  3491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-21 08:36:14.835  1018  3491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-21 08:36:14.845  1335  1335 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
,03-21 08:36:14.845  1018  1558 E Tethering: No numeric data
,03-21 08:36:14.845  1335  1335 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,03-21 08:36:14.845  1335  1335 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,03-21 08:36:14.855  1335  1335 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-21 08:36:14.855  1335  1335 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,03-21 08:36:14.855  1335  1335 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,03-21 08:36:14.855  1335  1335 D daemonapp: [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,03-21 08:36:14.855  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-21 08:36:14.855  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-21 08:36:14.855  1018  1018 V EnterpriseBillingPolicy: uID is 10155
03-21 08:36:14.855  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
03-21 08:36:14.855  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-21 08:36:14.855  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-21 08:36:14.855  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-21 08:36:14.855  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-21 08:36:14.855  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-21 08:36:14.855  1018  2853 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
,03-21 08:36:14.855  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-21 08:36:14.855  1018  1018 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,03-21 08:36:14.865  1454  1454 D PersonaManager: isKioskContainerExistOnDevice
,03-21 08:36:14.865  1018  1060 D PackageManager: delete codoeFile: 
,03-21 08:36:14.865  1454  1454 D RegisteredServicesCache: empty dynamic service
,03-21 08:36:14.875  1018  2994 E Tethering: No numeric data
,03-21 08:36:14.875  3448  3448 E UpdateRequestReceiver: ignoring update request
,03-21 08:36:14.875  1018  1133 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1458545774868 mCachedNtpElapsedRealtime : 40768 mCachedNtpCertainty : 27
,03-21 08:36:14.875  1018  1133 D NtpTrustedTime: currentTimeMillis() cache hit
,03-21 08:36:14.875  1018  1133 D NtpTrustedTime: currentTimeMillis() cache hit
,03-21 08:36:14.885  1018  1508 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
03-21 08:36:14.885  3151  3151 E BluetoothHeadset: BTStateChangeCB is registed
,03-21 08:36:14.895  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:14.895  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:14.895  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:14.895  1018  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:14.905  3151  3151 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,03-21 08:36:14.915  3528  3528 E Zygote  : MountEmulatedStorage()
,03-21 08:36:14.915  3528  3528 E Zygote  : v2
03-21 08:36:14.915  3528  3528 I libpersona: KNOX_SDCARD checking this for 10009
03-21 08:36:14.915  3528  3528 I libpersona: KNOX_SDCARD not a persona
,03-21 08:36:14.915  3528  3528 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-21 08:36:14.915   289   289 E SMD     : DCD OFF,
03-21 08:36:14.915  3528  3528 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 08:36:14.915  3528  3528 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-21 08:36:14.925  1018  1508 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3528 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-21 08:36:14.925  1018  1314 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
03-21 08:36:14.925  1018  1314 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,03-21 08:36:14.925  1018  1314 W ActivityManager: userId = 0, bbcId = -10000
,03-21 08:36:14.925  1018  1314 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 08:36:14.925  1018  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,03-21 08:36:14.935  3151  3151 E BluetoothHeadset: BluetoothHeadset service is binded
,03-21 08:36:14.935   284   843 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
,03-21 08:36:14.935   284   843 D audio_hw_extn: audio_extn_get_parameters: returns 
03-21 08:36:14.935   284   843 V msm8974_platform: platform_get_parameters: exit: returns - 
03-21 08:36:14.935   284   843 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-21 08:36:14.935   284   843 I str_params: key: 'call_forwarding' value: ''
03-21 08:36:14.935  1989  1989 V InCall  : ProximitySensor -  - screenonImmediately: false
03-21 08:36:14.935  1989  1989 V InCall  : ProximitySensor -  - mFromRcsShare: false
,03-21 08:36:14.945  1989  1989 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,03-21 08:36:14.945  2063  3404 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 1067 ms
03-21 08:36:14.945  1989  1989 D ScoverManager: serviceVersion : 16908288
,03-21 08:36:14.955  1018  1031 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-21 08:36:14.955  1989  1989 D InCall  : InCallUtils - isCoverClosed false
,03-21 08:36:14.955  1445  1445 I Telecom : ProximitySensorManager: Proximity wake lock already released
,03-21 08:36:14.955  1018  1030 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-21 08:36:14.955  1989  1989 D InCall  : InCallUtils - isCoverClosed false
03-21 08:36:14.955  1989  1989 I InCall  : InCallPresenter -  - InCallState = NO_CALLS
,03-21 08:36:14.955  1989  1989 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
03-21 08:36:14.955  1989  1989 D InCall  : InCallPresenter -  - dismissCoverDialog()...
,03-21 08:36:14.965  3151  3151 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,03-21 08:36:14.965  1018  2994 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,03-21 08:36:14.965  1018  2994 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
03-21 08:36:14.965  1989  1989 I InCall  : CallSContextMotion - stopPutDownListening
,03-21 08:36:14.965  1989  1989 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,03-21 08:36:14.965  1018  2994 W ActivityManager: userId = 0, bbcId = -10000
,03-21 08:36:14.965  1018  2994 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-21 08:36:14.965  1018  2994 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,03-21 08:36:14.975  1189  1189 D PhoneStatusBarView: setCallBackground:0
,03-21 08:36:14.985  3528  3528 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 08:36:14.985  3528  3528 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:15.005  1018  1558 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-21 08:36:15.005  1989  1989 D InCall  : InCallUtils - isCoverClosed false
,03-21 08:36:15.085  3469  3469 I DBG_POLICYDM: [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,03-21 08:36:15.085  3469  3469 I DBG_POLICYDM: [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-21 08:36:15.085  1018  3492 D SettingsProvider: name = aw_daemon_service_key_version_check
,03-21 08:36:15.085  1018  3492 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-21 08:36:15.085  1018  3492 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-21 08:36:15.085  1018  3492 D SettingsProvider: selectionArgs: false
,03-21 08:36:15.085  1018  3492 D SettingsProvider: selectionArgs: 10162
,03-21 08:36:15.085  1018  3492 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,03-21 08:36:15.085  1018  3492 D SettingsProvider: ret = -1
,03-21 08:36:15.095  3151  3151 D BluetoothA2dp: Proxy object connected
,03-21 08:36:15.095  1018  3466 E Tethering: No numeric data
,03-21 08:36:15.115  1018  1060 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
,03-21 08:36:15.115  1335  1335 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
03-21 08:36:15.115  1018  3492 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10162
,03-21 08:36:15.115  1018  1060 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,03-21 08:36:15.125  1018  1174 D TaskPersister: removeObsoleteFile: deleting file=16_task.xml
03-21 08:36:15.125  1018  1174 D TaskPersister: removeObsoleteFile: deleting file=16_task_thumbnail.png
03-21 08:36:15.125  3448  3448 E UpdateRequestReceiver: ignoring update request
,03-21 08:36:15.135  1989  1989 D VideoCallManager: Instantiating VideoCallManager,
,03-21 08:36:15.135  1989  1989 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-21 08:36:15.135  1989  1989 I GFX construct_block_size_descriptor_2d second part: took 2.483750ms for 0*0 texture 0
,03-21 08:36:15.145  1989  1989 I GFX generate_partition_tables: took 5.186771ms for 0*0 texture 0,
,03-21 08:36:15.145  1989  1989 I GFX raster: took 11.509479ms for 176*144 texture 0
,03-21 08:36:15.145  1989  1989 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb81c7330 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb81df540 counterpartCT=4 counterpartW=176 counterparth=144
,03-21 08:36:15.155  1018  1060 D PackageManager: result of delete: 1{6348616}
,03-21 08:36:15.155  1335  1335 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-21 08:36:15.155  1018  1045 D EnterpriseDeviceManagerService: Package has changed for user 0
03-21 08:36:15.155  1989  1989 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,03-21 08:36:15.155  1018  1045 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,03-21 08:36:15.155  1335  1335 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-21 08:36:15.155  1018  1045 W TextServicesManagerService: no available spell checker services found
03-21 08:36:15.155  1989  1989 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-21 08:36:15.155  1989  1989 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-21 08:36:15.155  1989  1989 I Adreno-EGL: Build Date: 04/06/15 Mon
03-21 08:36:15.155  1989  1989 I Adreno-EGL: Local Branch: 
03-21 08:36:15.155  1989  1989 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-21 08:36:15.155  1989  1989 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-21 08:36:15.155  1989  1989 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
03-21 08:36:15.155  1335  1335 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-21 08:36:15.155  1335  1335 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-21 08:36:15.165  1335  1335 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-21 08:36:15.165  1189  1189 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-21 08:36:15.175  1335  1335 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-21 08:36:15.175  1989  1989 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-21 08:36:15.185  1018  1030 V VibratorService: hasVibrator - useVibetonz: true
,03-21 08:36:15.185  3448  3448 E UpdateRequestReceiver: ignoring update request
,03-21 08:36:15.185  3414  3414 D AndroidRuntime: Shutting down VM
,03-21 08:36:15.185  1989  1989 I glCompressedTexImage2D: took 0.274688ms for 320*61440 texture 37809
,03-21 08:36:15.185  1335  1335 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-21 08:36:15.195  2970  2993 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
,03-21 08:36:15.195  2970  2993 D BadgeProvider: sendNotify, [notify] : null
,03-21 08:36:15.195  3469  3524 I DBG_POLICYDM: [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,03-21 08:36:15.195  2970  2993 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
,03-21 08:36:15.195  2970  2993 D BadgeProvider: update, [BadgeCount] : badgecount=0
,03-21 08:36:15.195  2970  2993 D BadgeProvider: update, [UpdateCount] : 1
,03-21 08:36:15.205  1311  3379 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,03-21 08:36:15.205  1989  1989 I draw setup: took 11.689741ms for 320*240 texture 37809
03-21 08:36:15.205  1989  1989 E GFX GPU raster: drawn
,03-21 08:36:15.205  3469  3469 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,03-21 08:36:15.205  2378  3294 D Mms/MessagingNotification: setBadgeCount(), count=0
03-21 08:36:15.205  1989  1989 I GFX GPU raster ASTC: took 42.239323ms for 320*240 texture 12
03-21 08:36:15.205  1989  1989 I GFX raster: took 42.315886ms for 320*240 texture 0
03-21 08:36:15.205  1989  1989 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb81df540 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb81e1880 counterpartCT=4 counterpartW=320 counterparth=240
,03-21 08:36:15.205  1018  3467 V VibratorService: hasVibrator - useVibetonz: true
,03-21 08:36:15.205  1018  1060 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-21 08:36:15.205  1018  1060 D PackageManager: userId{-1}
03-21 08:36:15.205  1018  1060 D PackageManager: andCode{true}
,03-21 08:36:15.205  1018  1060 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,03-21 08:36:15.215  1018  1314 V VibratorService: hasVibrator - useVibetonz: true
,03-21 08:36:15.215  1989  1989 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-21 08:36:15.215  1989  1989 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-21 08:36:15.225  2378  3294 D Mms/MessagingNotification: remove alarm
,03-21 08:36:15.225  1989  1989 I glCompressedTexImage2D: took 0.364427ms for 480*122880 texture 37813
,03-21 08:36:15.225  1989  1989 I draw setup: took 0.762552ms for 480*640 texture 37813
03-21 08:36:15.225  1989  1989 E GFX GPU raster: drawn
,03-21 08:36:15.225  1018  2968 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-21 08:36:15.225  1989  1989 I GFX GPU raster ASTC: took 7.529636ms for 480*640 texture 12,
03-21 08:36:15.225  1989  1989 I GFX raster: took 7.609688ms for 480*640 texture 0
03-21 08:36:15.225  1989  1989 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb81e1880 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb840fd10 counterpartCT=4 counterpartW=480 counterparth=640
,03-21 08:36:15.235  1311  3379 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-21 08:36:15.235  2378  3552 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-21 08:36:15.235  3448  3448 E UpdateRequestReceiver: ignoring update request
,03-21 08:36:15.245  1018  1314 D ActivityManager: startProcessLocked calleePkgName: com.dropbox.android, hostingType: broadcast
,03-21 08:36:15.245  1018  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:15.245  1018  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:15.245  1018  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:15.245  1018  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:15.255  1335  1335 D daemonapp: [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1458545775198
03-21 08:36:15.255  1335  1335 D daemonapp: [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1458567360000
03-21 08:36:15.255  1335  1335 D daemonapp: [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
03-21 08:36:15.255  1335  1335 D daemonapp: [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,03-21 08:36:15.265  3556  3556 E Zygote  : MountEmulatedStorage(),
03-21 08:36:15.265  3556  3556 E Zygote  : v2
03-21 08:36:15.265  3556  3556 I libpersona: KNOX_SDCARD checking this for 10092,
,03-21 08:36:15.265  3556  3556 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-21 08:36:15.265  3556  3556 I libpersona: KNOX_SDCARD not a persona
03-21 08:36:15.265  1989  1989 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
03-21 08:36:15.265  1018  1314 I ActivityManager: Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3556 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-21 08:36:15.265  1989  1989 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-21 08:36:15.275  3556  3556 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 08:36:15.275  3556  3556 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-21 08:36:15.275  1018  1314 I ActivityManager: Killing 2531:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31,
03-21 08:36:15.275  1989  1989 I glCompressedTexImage2D: took 0.415209ms for 440*116864 texture 37809
,03-21 08:36:15.275  1989  1989 I draw setup: took 0.895885ms for 440*330 texture 37809
03-21 08:36:15.275  1989  1989 E GFX GPU raster: drawn,
,03-21 08:36:15.275  1989  1989 I GFX GPU raster ASTC: took 4.461458ms for 440*330 texture 12
03-21 08:36:15.275  1989  1989 I GFX raster: took 4.526145ms for 440*330 texture 0
03-21 08:36:15.275  1989  1989 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb840fd10 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb8424100 counterpartCT=4 counterpartW=440 counterparth=330
,03-21 08:36:15.285  3469  3524 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,03-21 08:36:15.295  3469  3469 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-21 08:36:15.305  1989  1989 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-21 08:36:15.305  1989  1989 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-21 08:36:15.305  1989  1989 I glCompressedTexImage2D: took 0.427136ms for 480*163840 texture 37811
03-21 08:36:15.305  1989  1989 I draw setup: took 0.834791ms for 480*640 texture 37811
03-21 08:36:15.305  1989  1989 E GFX GPU raster: drawn
,03-21 08:36:15.315  3556  3556 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-21 08:36:15.315  3556  3556 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:15.315  1018  2994 I ActivityManager: Killing 2568:com.sec.android.app.camera/u0a139 (adj 15): empty #31,
03-21 08:36:15.315  1469  1637 D TP/SmsProvider: query,matched:0, calling pid = 2378
,03-21 08:36:15.325  1989  1989 I GFX GPU raster ASTC: took 6.174636ms for 480*640 texture 12
03-21 08:36:15.325  1989  1989 I GFX raster: took 6.255625ms for 480*640 texture 0
03-21 08:36:15.325  1989  1989 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8413f10 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb8423c38 counterpartCT=4 counterpartW=480 counterparth=640
,03-21 08:36:15.335  1335  1335 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458567360000
,03-21 08:36:15.345  1335  1335 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
,03-21 08:36:15.345  1335  1335 D daemonapp: [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1458567360000
,03-21 08:36:15.365  1469  1637 D TP/SmsProvider: match 0:Elapsed time : 32.228 ms
,03-21 08:36:15.375  1989  1989 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-21 08:36:15.375  1989  1989 I GFX construct_block_size_descriptor_2d second part: took 2.314114ms for 0*0 texture 0
,03-21 08:36:15.385  1989  1989 I GFX generate_partition_tables: took 7.525937ms for 0*0 texture 0
,03-21 08:36:15.385  3469  3469 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-21 08:36:15.395  1989  1989 I GFX raster: took 11.938488ms for 176*144 texture 0
,03-21 08:36:15.395  1989  1989 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb840d5d0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb840d6f0 counterpartCT=4 counterpartW=176 counterparth=144
,03-21 08:36:15.395  1335  1335 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
03-21 08:36:15.395  3469  3524 I DBG_POLICYDM: [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
03-21 08:36:15.395  1335  1335 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-21 08:36:15.405  3469  3469 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-21 08:36:15.405  1018  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 08:36:15.405  1989  1989 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-21 08:36:15.405  1989  1989 I GFX construct_block_size_descriptor_2d second part: took 2.309323ms for 0*0 texture 0
,03-21 08:36:15.405  2378  3294 D Mms/SmsReceiverService: [end]    handleBootCompleted() consume time = 2698.562134
,03-21 08:36:15.415  1989  1989 I GFX generate_partition_tables: took 6.203803ms for 0*0 texture 0
,03-21 08:36:15.415  1989  1989 I GFX raster: took 10.621668ms for 176*144 texture 0
03-21 08:36:15.415  1989  1989 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb840d910 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb840d8b0 counterpartCT=4 counterpartW=176 counterparth=144
,03-21 08:36:15.415  3469  3469 I DBG_POLICYDM: [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,03-21 08:36:15.415  1989  1989 D ScoverManager: registerListener
,03-21 08:36:15.425  1018  3491 D ActivityManager: startProcessLocked calleePkgName: com.google.android.youtube, hostingType: broadcast
,03-21 08:36:15.425  1018  1031 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-21 08:36:15.425  1018  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 08:36:15.425  1018  1508 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-21 08:36:15.425  1018  1508 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@1af2eb27, pid : 1989, uid : 1001, type : 1
,03-21 08:36:15.435  3469  3469 I DBG_POLICYDM: [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,03-21 08:36:15.435  1018  3491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:15.435  1018  3491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:15.435  3469  3469 I DBG_POLICYDM: [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,03-21 08:36:15.435  1018  3491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:15.435  1018  3491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:15.435  1311  3379 D ScoverManager: serviceVersion : 16908288
,03-21 08:36:15.445  3577  3577 E Zygote  : MountEmulatedStorage(),
03-21 08:36:15.445  3577  3577 I libpersona: KNOX_SDCARD checking this for 10166,
03-21 08:36:15.445  3577  3577 E Zygote  : v2
,03-21 08:36:15.445  3577  3577 I libpersona: KNOX_SDCARD not a persona
03-21 08:36:15.445  3577  3577 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-21 08:36:15.455  1018  3491 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3577 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-21 08:36:15.455  3414  3414 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
03-21 08:36:15.455  3577  3577 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 08:36:15.455  3577  3577 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-21 08:36:15.475  3577  3577 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 08:36:15.475  3577  3577 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:15.485  1018  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 08:36:15.485  1018  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 08:36:15.525  1018  1031 I ActivityManager: Killing 2624:com.example.hello/u0a174 (adj 15): empty #31
,03-21 08:36:15.535  1989  1989 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
,03-21 08:36:15.545  1490  1490 D Launcher.Model: reloadBadges entered.
,03-21 08:36:15.555  1490  1490 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-21 08:36:15.555  1490  1490 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-21 08:36:15.555  1490  1490 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-21 08:36:15.585  1018  1363 D ActivityManager: startProcessLocked calleePkgName: com.fmm.dm, hostingType: broadcast
,03-21 08:36:15.595  1018  1363 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:15.595  1018  1363 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:15.595  1018  1363 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:15.595  1018  1363 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:15.605  1018  3467 D LocationManagerService: getProviders()=[passive]
,03-21 08:36:15.605  3596  3596 E Zygote  : MountEmulatedStorage()
03-21 08:36:15.605  3596  3596 I libpersona: KNOX_SDCARD checking this for 1000
03-21 08:36:15.605  3596  3596 E Zygote  : v2
03-21 08:36:15.605  3596  3596 I libpersona: KNOX_SDCARD not a persona
03-21 08:36:15.615  1018  1363 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3596 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-21 08:36:15.615  1018  1363 I ActivityManager: Killing 2607:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,03-21 08:36:15.615  1018  1363 I ActivityManager: Killing 2657:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #32
,03-21 08:36:15.615  3596  3596 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 08:36:15.615  3596  3596 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 08:36:15.615  3596  3596 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 08:36:15.625  1018  1363 I ActivityManager: Killing 2642:com.samsung.android.app.FileShareClient/u0a68 (adj 15): empty #33
,03-21 08:36:15.625  1018  2994 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,03-21 08:36:15.625  1018  2994 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:15.625  1018  2994 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:15.625  1018  2994 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:15.625  1018  2994 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:15.645  3611  3611 E Zygote  : MountEmulatedStorage()
03-21 08:36:15.645  3611  3611 E Zygote  : v2
03-21 08:36:15.645  3611  3611 I libpersona: KNOX_SDCARD checking this for 10015
03-21 08:36:15.645  3611  3611 I libpersona: KNOX_SDCARD not a persona
,03-21 08:36:15.645  3611  3611 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 08:36:15.645  3611  3611 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 08:36:15.655  3611  3611 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-21 08:36:15.655  1018  2994 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3611 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,03-21 08:36:15.665  3596  3596 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 08:36:15.665  3596  3596 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:15.665  3469  3524 I DBG_POLICYDM: [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,03-21 08:36:15.675  3469  3524 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-21 08:36:15.695  3611  3611 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 08:36:15.695  3611  3611 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:15.725  3469  3524 I DBG_POLICYDM: [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,03-21 08:36:15.725  3469  3524 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,03-21 08:36:15.725  3469  3524 I DBG_POLICYDM: [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,03-21 08:36:15.725  1018  1045 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-21 08:36:15.735  1018  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 08:36:15.735  1018  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 08:36:15.745  1018  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 08:36:15.755  1018  1045 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-21 08:36:15.755  1018  1045 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-21 08:36:15.755  1018  1045 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-21 08:36:15.755  1018  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 08:36:15.765  1018  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 08:36:15.765  1018  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 08:36:15.765  1018  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-21 08:36:15.765  1018  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-21 08:36:15.775  1018  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 08:36:15.775  1018  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-21 08:36:15.775  1018  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-21 08:36:15.785  1018  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-21 08:36:15.785  1018  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-21 08:36:15.785  1018  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-21 08:36:15.785  1018  1045 D UsbSettingsManager: clearDefaults: com.test.thalitest
03-21 08:36:15.785  1018  1045 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,03-21 08:36:15.805  3469  3524 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,03-21 08:36:15.805  1311  3379 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-21 08:36:15.805  1018  1507 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
03-21 08:36:15.805  1018  1507 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,03-21 08:36:15.805  1018  1507 W ActivityManager: userId = 0, bbcId = -10000
03-21 08:36:15.815  1018  1507 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 08:36:15.815  1018  1507 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-21 08:36:15.815  3469  3524 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-21 08:36:15.825  1018  2994 I ActivityManager: Killing 2682:com.android.calendar/u0a135 (adj 15): empty #31
,03-21 08:36:15.835  3469  3524 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-21 08:36:15.835  1311  3379 D Settings_Utils: isSupportVNFestival SM-A500FU XEO
,03-21 08:36:15.845  3469  3525 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,03-21 08:36:15.845  3469  3525 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-21 08:36:15.855  3469  3524 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,03-21 08:36:15.855  3469  3524 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,03-21 08:36:15.855  3469  3525 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-21 08:36:15.855  3469  3525 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-21 08:36:15.865  1018  1045 W libprocessgroup: failed to open /acct/uid_10142/pid_2531/cgroup.procs: No such file or directory
03-21 08:36:15.865  1018  1045 W libprocessgroup: failed to open /acct/uid_10139/pid_2568/cgroup.procs: No such file or directory
,03-21 08:36:15.865  3469  3525 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
03-21 08:36:15.865  1018  1045 W libprocessgroup: failed to open /acct/uid_10174/pid_2624/cgroup.procs: No such file or directory
03-21 08:36:15.865  1018  1045 W libprocessgroup: failed to open /acct/uid_10068/pid_2642/cgroup.procs: No such file or directory
03-21 08:36:15.865  1018  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2607/cgroup.procs: No such file or directory
03-21 08:36:15.865  1018  1045 W libprocessgroup: failed to open /acct/uid_10069/pid_2657/cgroup.procs: No such file or directory
,03-21 08:36:15.865  3469  3525 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-21 08:36:15.865  1018  1144 I ActivityManager: Killing 2788:com.android.keychain/1000 (adj 15): empty #31
,03-21 08:36:15.865  3469  3525 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-21 08:36:15.865  3469  3525 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,03-21 08:36:15.865  3469  3525 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,03-21 08:36:15.875  3469  3525 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-21 08:36:15.875  3469  3524 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/03/25/14:07:31
,03-21 08:36:15.875  3469  3524 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/03/21/08:36:15
,03-21 08:36:15.885  3469  3524 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,03-21 08:36:15.885  3469  3524 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,03-21 08:36:15.895  3596  3596 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,03-21 08:36:15.905  1018  1334 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
03-21 08:36:15.905  1018  1334 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0
,03-21 08:36:15.905  1018  1334 W ActivityManager: userId = 0, bbcId = -10000
03-21 08:36:15.905  1018  1334 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-21 08:36:15.905  1018  1334 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-21 08:36:15.915  3596  3596 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,03-21 08:36:15.915  3596  3596 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,03-21 08:36:15.915  3596  3596 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,03-21 08:36:15.915  3497  3639 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[refresh_search_history]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-21 08:36:15.925  3497  3639 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[refresh_search_domain_and_cookies]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-21 08:36:15.925  3577  3638 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-21 08:36:15.925  3577  3638 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-21 08:36:15.925  3497  3640 I SearchServiceFactory: refreshing search history.
,03-21 08:36:15.925  1018  1504 D ActivityManager: getContentProviderImpl callerProcessName:com.fmm.dm, calleePkgName: com.sec.pcw.device
,03-21 08:36:15.925  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:15.925  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:15.925  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:15.925  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:15.935  3642  3642 E Zygote  : MountEmulatedStorage()
,03-21 08:36:15.945  3642  3642 E Zygote  : v2
03-21 08:36:15.945  3642  3642 I libpersona: KNOX_SDCARD checking this for 1000
03-21 08:36:15.945  3642  3642 I libpersona: KNOX_SDCARD not a persona
,03-21 08:36:15.945  3642  3642 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 08:36:15.945  3642  3642 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 08:36:15.945  3642  3642 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 08:36:15.945  1018  1504 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3642 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-21 08:36:15.965  1018  1045 W libprocessgroup: failed to open /acct/uid_10135/pid_2682/cgroup.procs: No such file or directory
03-21 08:36:15.965  1018  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2788/cgroup.procs: No such file or directory
,03-21 08:36:15.965  3642  3642 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 08:36:15.965  3380  3434 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
03-21 08:36:15.965  3642  3642 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:15.975  3497  3641 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-21 08:36:15.975  1018  3491 D ActivityManager: startService callerProcessName:com.dropbox.android, calleePkgName: com.dropbox.android
,03-21 08:36:15.975  1018  3491 D ActivityManager: retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,03-21 08:36:15.975  1018  3491 W ActivityManager: userId = 0, bbcId = -10000
03-21 08:36:15.975  1018  3491 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,03-21 08:36:15.975  1018  3491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,03-21 08:36:15.975  1018  3491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:15.975  1018  3491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:15.975  1018  3491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:15.975  1018  3491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:15.995  3659  3659 E Zygote  : MountEmulatedStorage()
03-21 08:36:15.995  3659  3659 E Zygote  : v2
03-21 08:36:15.995  3659  3659 I libpersona: KNOX_SDCARD checking this for 10092
03-21 08:36:15.995  3659  3659 I libpersona: KNOX_SDCARD not a persona
,03-21 08:36:15.995  1018  3491 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3659 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-21 08:36:16.005  3577  3638 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-21 08:36:16.015  3497  3641 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 1901-1902)
03-21 08:36:16.015  3659  3659 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-21 08:36:16.015  3497  3641 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-21 08:36:16.015  3659  3659 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 08:36:16.015  3659  3659 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-21 08:36:16.015  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,03-21 08:36:16.025  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:16.025  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:16.025  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:16.025  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:16.035  3642  3642 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,03-21 08:36:16.035  3671  3671 E Zygote  : MountEmulatedStorage()
03-21 08:36:16.035  3671  3671 E Zygote  : v2
03-21 08:36:16.035  3671  3671 I libpersona: KNOX_SDCARD checking this for 10003
03-21 08:36:16.035  3671  3671 I libpersona: KNOX_SDCARD not a persona,
,03-21 08:36:16.045  3642  3642 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
03-21 08:36:16.045  3671  3671 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 08:36:16.045  3497  3641 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 08:36:16.045  3671  3671 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-21 08:36:16.045  3671  3671 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-21 08:36:16.045  3497  3641 W TRThreadPoolExecutor: Task "b[Get cookie call]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
03-21 08:36:16.055  1018  1018 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3671 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,03-21 08:36:16.055  3642  3642 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-21 08:36:16.055  3659  3659 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 08:36:16.055  3659  3659 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:16.065  3642  3657 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-21 08:36:16.075  3577  3638 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-21 08:36:16.075  3577  3638 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1b62b122: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-21 08:36:16.075  3577  3638 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-21 08:36:16.085  3671  3671 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-21 08:36:16.085  3671  3671 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:16.095  3596  3596 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,03-21 08:36:16.095  3596  3596 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,03-21 08:36:16.095  3596  3596 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-21 08:36:16.095  1018  3492 D ActivityManager: startProcessLocked calleePkgName: com.fmm.ds, hostingType: broadcast
,03-21 08:36:16.095  1018  3492 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:16.095  1018  3492 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:16.095  1018  3492 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:16.095  1018  3492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-21 08:36:16.115  3469  3524 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] ,
,03-21 08:36:16.115  3695  3695 E Zygote  : MountEmulatedStorage()
03-21 08:36:16.115  3695  3695 E Zygote  : v2
03-21 08:36:16.115  3695  3695 I libpersona: KNOX_SDCARD checking this for 1000
03-21 08:36:16.115  3695  3695 I libpersona: KNOX_SDCARD not a persona
,03-21 08:36:16.125  3695  3695 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-21 08:36:16.125  3695  3695 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 08:36:16.125  1018  3492 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3695 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-21 08:36:16.125  3695  3695 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 08:36:16.125  1018  3492 I ActivityManager: Killing 2867:com.samsung.android.sm/1000 (adj 15): empty #31
03-21 08:36:16.125  1018  3492 I ActivityManager: Killing 2900:com.android.email/u0a145 (adj 15): empty #32
,03-21 08:36:16.145  3695  3695 D TimaKeyStoreProvider: TimaSignature is unavailable,
,03-21 08:36:16.145  3695  3695 D ActivityThread: Added TimaKeyStore provider
,03-21 08:36:16.155   306   306 I art     : Explicit concurrent mark sweep GC freed 8743(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 648us total 24.481ms
,03-21 08:36:16.155  3469  3525 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-21 08:36:16.175   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 673us total 17.763ms
,03-21 08:36:16.185  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-21 08:36:16.185  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-21 08:36:16.185  1189  1189 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-21 08:36:16.185  1189  1189 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-21 08:36:16.185  1189  1189 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-21 08:36:16.185  1189  1189 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-21 08:36:16.185  1660  1671 I art     : Explicit concurrent mark sweep GC freed 2921(119KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 1.364ms total 43.167ms
,03-21 08:36:16.185   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 760us total 17.750ms
,03-21 08:36:16.195  1018  1144 I ActivityManager: Killing 3059:flipboard.boxer.app/u0a99 (adj 15): empty #31
,03-21 08:36:16.195  3671  3671 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-21 08:36:16.235  3469  3524 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,03-21 08:36:16.245  1018  1045 W libprocessgroup: failed to open /acct/uid_10145/pid_2900/cgroup.procs: No such file or directory
,03-21 08:36:16.245  3469  3524 I DBG_POLICYDM: [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-21 08:36:16.245  3497  3640 W TRThreadPoolExecutor: Task "b[Get cookie call]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-21 08:36:16.255  3469  3525 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,03-21 08:36:16.255  3469  3525 E SQLiteLog: (3850) statement aborts at 36: [UPDATE fumo SET serverport=?,downloadResultcode=?,objectdownloadurl=?,statusnotifyport=?,processid=?,pkgsize=?,reporturl=?,objectdownloadprotocol=?,resultcode=?,serverurl=?,pkgname=?,s
,03-21 08:36:16.255  3469  3525 E DBG_POLICYDM: [com.policydm.db.XDBSqlQuery(1065/xdmDbUpdateFUMORow)] android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
,03-21 08:36:16.265  1018  1045 W libprocessgroup: failed to open /acct/uid_1000/pid_2867/cgroup.procs: No such file or directory
03-21 08:36:16.265  1018  1045 W libprocessgroup: failed to open /acct/uid_10099/pid_3059/cgroup.procs: No such file or directory
,03-21 08:36:16.285  3497  3641 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 08:36:16.325  3695  3695 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-21 08:36:16.325  3695  3695 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-21 08:36:16.405  3671  3671 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-21 08:36:16.415  3671  3671 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-21 08:36:16.415  3671  3671 D UserAnalysis: Create SecureDbHelper
,03-21 08:36:16.415  3469  3525 E SQLiteLog: (10) unixWrite() File Descriptor : 37 gets errno : 30
,03-21 08:36:16.415  3469  3525 E DBG_POLICYDM: [com.policydm.db.XDBSqlQuery(730/xdmDbUpdateProfileListRow)] android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
,03-21 08:36:16.425  2725  3310 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-21 08:36:16.425  3642  3650 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-21 08:36:16.425  3469  3525 I DBG_POLICYDM: [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,03-21 08:36:16.425  3556  3556 W FileUtils: Failed to chmod(/data/data/com.dropbox.android/databases/prefs.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,03-21 08:36:16.435  3469  3525 E SQLiteLog: (28) failed to open "/data/user/0/com.policydm/databases/policydmdb.db" with flag (131138) and mode_t (0) due to error (30)
,03-21 08:36:16.435  3695  3695 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-21 08:36:16.435  2725  3310 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:36:16.435  3556  3556 E File    : fail readDirectory() errno=2
03-21 08:36:16.435  3556  3556 W FileUtils: Failed to chmod(/data/data/com.dropbox.android/app_bromo): android.system.ErrnoException: chmod failed: ENOENT (No such file or directory)
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: Failed to open database '/data/user/0/com.policydm/databases/policydmdb.db'.
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.435  3469  3525 E, SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: 	at com.policydm.XDMApplication.xdmDbGetReadableDatabase(XDMApplication.java:241)
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDBSqlQuery.xdmDbFetchProfileListRow(XDBSqlQuery.java:771)
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDBSqlAdapter.xdmDbSqlRead(XDBSqlAdapter.java:249)
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDB.xdbRead(XDB.java:724)
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDBProfileAdp.xdbGetProfileInfo(XDBProfileAdp.java:13)
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDB.xdbSetBackUpServerUrl(XDB.java:1826)
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpClearSessionStatus(XNOTIAdapter.java:276)
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpExcuteResumeNoti(XNOTIAdapter.java:442)
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpResumeNotiAction(XNOTIAdapter.java:512)
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: 	at com.policydm.agent.XDMUITask.xdmUIEvent(XDMUITask.java:194)
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: 	at com.policydm.agent.XDMUITask$1.handleMessage(XDMUITask.java:46)
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: 	at com.policydm.agent.XDMUITask.run(XDMUITask.java:50)
03-21 08:36:16.435  3469  3525 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:36:16.435  2725  3310 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: Couldn't open policydmdb.db for writing (will try read-only):
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at com.policydm.XDMApplication.xdmDbGetReadableDatabase(XDMApplication.java:241)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at com.policydm.db.XDBSqlQuery.xdmDbFetchProfileListRow(XDBSqlQuery.java:771)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at com.policydm.db.XDBSqlAdapter.xdmDbSqlRead(XDBSqlAdapter.java:249)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at com.policydm.db.XDB.xdbRead(XDB.java:724)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at com.policydm.db.XDBProfileAdp.xdbGetProfileInfo(XDBProfileAdp.java:13)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at com.policydm.db.XDB.xdbSetBackUpServerUrl(XDB.java:1826)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpClearSessionStatus(XNOTIAdapter.java:276)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpExcuteResumeNoti(XNOTIAdapter.java:442)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpResumeNotiAction(XNOTIAdapter.java:512)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at com.policydm.agent.XDMUITask.xdmUIEvent(XDMUITask.java:194)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at com.policydm.agent.XDMUITask$1.handleMessage(XDMUITask.java:46)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at com.policydm.agent.XDMUITask.run(XDMUITask.java:50)
03-21 08:36:16.435  3469  3525 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 08:36:16.435  2725  3310 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:36:16.435  3469  3525 W SQLiteOpenHelper: Opened policydmdb.db in read-only mode
03-21 08:36:16.445  3469  3525 E SQLiteLog: (28) failed to open "/data/user/0/com.policydm/databases/policydmdb.db" with flag (131138) and mode_t (0) due to error (30)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: Failed to open database '/data/user/0/com.policydm/databases/policydmdb.db'.
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at com.policydm.XDMApplication.xdmDbGetReadableDatabase(XDMApplication.java:241)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDBSqlQuery.xdmDbFetchProfileRow(XDBSqlQuery.java:232)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDBSqlAdapter.xdmDbSqlRead(XDBSqlAdapter.java:259)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDB.xdbRead(XDB.java:743)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDBProfileAdp.xdbGetProfileInfo(XDBProfileAdp.java:13)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDB.xdbSetBackUpServerUrl(XDB.java:1826)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpClearSessionStatus(XNOTIAdapter.java:276)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpExcuteResumeNoti(XNOTIAdapter.java:442)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpResumeNotiAction(XNOTIAdapter.java:512)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at com.policydm.agent.XDMUITask.xdmUIEvent(XDMUITask.java:194)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at com.policydm.agent.XDMUITask$1.handleMessage(XDMUITask.java:46)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at com.policydm.agent.XDMUITask.run(XDMUITask.java:50)
03-21 08:36:16.445  3469  3525 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: Couldn't open policydmdb.db for writing (will try read-only):
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at com.policydm.XDMApplication.xdmDbGetReadableDatabase(XDMApplication.java:241)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at com.policydm.db.XDBSqlQuery.xdmDbFetchProfileRow(XDBSqlQuery.java:232)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at com.policydm.db.XDBSqlAdapter.xdmDbSqlRead(XDBSqlAdapter.java:259)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at com.policydm.db.XDB.xdbRead(XDB.java:743)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at com.policydm.db.XDBProfileAdp.xdbGetProfileInfo(XDBProfileAdp.java:13)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at com.policydm.db.XDB.xdbSetBackUpServerUrl(XDB.java:1826)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpClearSessionStatus(XNOTIAdapter.java:276)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpExcuteResumeNoti(XNOTIAdapter.java:442)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpResumeNotiAction(XNOTIAdapter.java:512)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at com.policydm.agent.XDMUITask.xdmUIEvent(XDMUITask.java:194)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at com.policydm.agent.XDMUITask$1.handleMessage(XDMUITask.java:46)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at com.policydm.agent.XDMUITask.run(XDMUITask.java:50)
03-21 08:36:16.445  3469  3525 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:36:16.445  3695  3695 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
03-21 08:36:16.445  3469  3525 W SQLiteOpenHelper: Opened policydmdb.db in read-only mode
03-21 08:36:16.445  3695  3695 E SQLiteLog: (28) failed to open "/data/data/com.fmm.ds/databases/fmmds.db" with flag (131138) and mode_t (0) due to error (30)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: Failed to open database '/data/data/com.fmm.ds/databases/fmmds.db'.
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at com.fmm.ds.XDSApplication.xdsGetReadableDatabase(XDSApplication.java:255)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at com.fmm.ds.db.XDBProfileQuery.xdbProfileExistsRow(XDBProfileQuery.java:269)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at com.fmm.ds.db.XDB.xdbDBInit(XDB.java:49)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at com.fmm.ds.XDSApplication.onCreate(XDSApplication.java:61)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-21 08:36:16.445  3695  3695 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: Couldn't open fmmds.db for writing (will try read-only):
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at com.fmm.ds.XDSApplication.xdsGetReadableDatabase(XDSApplication.java:255)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at com.fmm.ds.db.XDBProfileQuery.xdbProfileExistsRow(XDBProfileQuery.java:269)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at com.fmm.ds.db.XDB.xdbDBInit(XDB.java:49)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at com.fmm.ds.XDSApplication.onCreate(XDSApplication.java:61)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-21 08:36:16.445  3695  3695 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-21 08:36:16.445  3695  3695 W SQLiteOpenHelper: Opened fmmds.db in read-only mode
03-21 08:36:16.455  3695  3695 E SQLiteLog: (28) failed to open "/data/data/com.fmm.ds/databases/fmmds.db" with flag (131138) and mode_t (0) due to error (30)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: Failed to open database '/data/data/com.fmm.ds/databases/fmmds.db'.
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at com.fmm.ds.XDSApplication.xdsGetReadableDatabase(XDSApplication.java:255)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at com.fmm.ds.db.XDBProfileQuery.xdbProfileFetchRow(XDBProfileQuery.java:178)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at com.fmm.ds.db.XDB.xdbDBInit(XDB.java:56)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at com.fmm.ds.XDSApplication.onCreate(XDSApplication.java:61)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-21 08:36:16.455  3695  3695 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: Couldn't open fmmds.db for writing (will try read-only):
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at com.fmm.ds.XDSApplication.xdsGetReadableDatabase(XDSApplication.java:255)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at com.fmm.ds.db.XDBProfileQuery.xdbProfileFetchRow(XDBProfileQuery.java:178)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at com.fmm.ds.db.XDB.xdbDBInit(XDB.java:56)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at com.fmm.ds.XDSApplication.onCreate(XDSApplication.java:61)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-21 08:36:16.455  3695  3695 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-21 08:36:16.455  3469  3525 E SQLiteLog: (28) failed to open "/data/user/0/com.policydm/databases/policydmdb.db" with flag (131138) and mode_t (0) due to error (30)
03-21 08:36:16.455  3695  3695 W SQLiteOpenHelper: Opened fmmds.db in read-only mode
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: Failed to open database '/data/user/0/com.policydm/databases/policydmdb.db'.
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at com.policydm.XDMApplication.xdmDbGetReadableDatabase(XDMApplication.java:241)
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDBSqlQuery.xdmDbFetchProfileListRow(XDBSqlQuery.java:771)
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDBSqlAdapter.xdmDbSqlRead(XDBSqlAdapter.java:249)
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDB.xdbWrite(XDB.java:1080)
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDBProfileAdp.xdbSetServerUrl(XDBProfileAdp.java:66)
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDB.xdbSetBackUpServerUrl(XDB.java:1832)
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpClearSessionStatus(XNOTIAdapter.java:276)
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpExcuteResumeNoti(XNOTIAdapter.java:442)
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpResumeNotiAction(XNOTIAdapter.java:512)
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at com.policydm.agent.XDMUITask.xdmUIEvent(XDMUITask.java:194)
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at com.policydm.agent.XDMUITask$1.handleMessage(XDMUITask.java:46)
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at com.policydm.agent.XDMUITask.run(XDMUITask.java:50)
03-21 08:36:16.455  3469  3525 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: Couldn't open policydmdb.db for writing (will try read-only):
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at com.policydm.XDMApplication.xdmDbGetReadableDatabase(XDMApplication.java:241)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at com.policydm.db.XDBSqlQuery.xdmDbFetchProfileListRow(XDBSqlQuery.java:771)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at com.policydm.db.XDBSqlAdapter.xdmDbSqlRead(XDBSqlAdapter.java:249)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at com.policydm.db.XDB.xdbWrite(XDB.java:1080)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at com.policydm.db.XDBProfileAdp.xdbSetServerUrl(XDBProfileAdp.java:66)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at com.policydm.db.XDB.xdbSetBackUpServerUrl(XDB.java:1832)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpClearSessionStatus(XNOTIAdapter.java:276)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpExcuteResumeNoti(XNOTIAdapter.java:442)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpResumeNotiAction(XNOTIAdapter.java:512)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at com.policydm.agent.XDMUITask.xdmUIEvent(XDMUITask.java:194)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at com.policydm.agent.XDMUITask$1.handleMessage(XDMUITask.java:46)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at com.policydm.agent.XDMUITask.run(XDMUITask.java:50)
03-21 08:36:16.455  3469  3525 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:36:16.455  3469  3525 W SQLiteOpenHelper: Opened policydmdb.db in read-only mode
03-21 08:36:16.465  2725  3310 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 08:36:16.465  2725  3310 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 08:36:16.465  2725  3310 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.465  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.465  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.465  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.465  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.465  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.465  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.465  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.465  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.465  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.465  2725  3310 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.465  2725  3310 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.465  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.465  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 08:36:16.465  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 08:36:16.465  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 08:36:16.465  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 08:36:16.465  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.465  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.465  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 08:36:16.465  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 08:36:16.465  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 08:36:16.465  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 08:36:16.465  2725  3310 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:36:16.465  3469  3525 E SQLiteLog: (28) failed to open "/data/user/0/com.policydm/databases/policydmdb.db" with flag (131138) and mode_t (0) due to error (30)
03-21 08:36:16.465  3671  3671 D IntelligenceServiceApplication: onCreate()
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: Failed to open database '/data/user/0/com.policydm/databases/policydmdb.db'.
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at com.policydm.XDMApplication.xdmDbGetWritableDatabase(XDMApplication.java:258)
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDBSqlQuery.xdmDbUpdateProfileRow(XDBSqlQuery.java:150)
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDBSqlAdapter.xdmDbSqlUpdate(XDBSqlAdapter.java:82)
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDB.xdbWrite(XDB.java:1105)
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDBProfileAdp.xdbSetServerUrl(XDBProfileAdp.java:66)
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDB.xdbSetBackUpServerUrl(XDB.java:1832)
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpClearSessionStatus(XNOTIAdapter.java:276)
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpExcuteResumeNoti(XNOTIAdapter.java:442)
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpResumeNotiAction(XNOTIAdapter.java:512)
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at com.policydm.agent.XDMUITask.xdmUIEvent(XDMUITask.java:194)
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at com.policydm.agent.XDMUITask$1.handleMessage(XDMUITask.java:46)
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at com.policydm.agent.XDMUITask.run(XDMUITask.java:50)
03-21 08:36:16.465  3469  3525 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:36:16.465  3469  3525 E DBG_POLICYDM: [com.policydm.XDMApplication(262/xdmDbGetWritableDatabase)] android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.465  3671  3671 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
03-21 08:36:16.465  1018  1558 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
03-21 08:36:16.465  1018  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:16.465  1018  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:16.465  1018  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:16.465  1018  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-21 08:36:16.465  2725  3310 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-21 08:36:16.475  2725  3310 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:36:16.475  3469  3525 E DBG_POLICYDM: [com.policydm.db.XDBSqlQuery(187/xdmDbUpdateProfileRow)] java.lang.NullPointerException: Attempt to invoke virtual method 'int android.database.sqlite.SQLiteDatabase.update(java.lang.String, android.content.ContentValues, java.lang.String, java.lang.String[])' on a null object reference
03-21 08:36:16.475  2725  3310 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 08:36:16.475  3671  3671 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
03-21 08:36:16.475  3469  3525 E SQLiteLog: (28) failed to open "/data/user/0/com.policydm/databases/policydmdb.db" with flag (131138) and mode_t (0) due to error (30)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:36:16.475  2725  3310 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: Failed to open database '/data/user/0/com.policydm/databases/policydmdb.db'.
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at com.policydm.XDMApplication.xdmDbGetReadableDatabase(XDMApplication.java:241)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDBSqlQuery.xdmDbFetchProfileListRow(XDBSqlQuery.java:771)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDBSqlAdapter.xdmDbSqlRead(XDBSqlAdapter.java:249)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDB.xdbWrite(XDB.java:1080)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDBProfileAdp.xdbSetServerAddress(XDBProfileAdp.java:78)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDB.xdbSetBackUpServerUrl(XDB.java:1833)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpClearSessionStatus(XNOTIAdapter.java:276)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpExcuteResumeNoti(XNOTIAdapter.java:442)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpResumeNotiAction(XNOTIAdapter.java:512)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at com.policydm.agent.XDMUITask.xdmUIEvent(XDMUITask.java:194)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at com.policydm.agent.XDMUITask$1.handleMessage(XDMUITask.java:46)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at com.policydm.agent.XDMUITask.run(XDMUITask.java:50)
03-21 08:36:16.475  3469  3525 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: Couldn't open policydmdb.db for writing (will try read-only):
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at com.policydm.XDMApplication.xdmDbGetReadableDatabase(XDMApplication.java:241)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at com.policydm.db.XDBSqlQuery.xdmDbFetchProfileListRow(XDBSqlQuery.java:771)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at com.policydm.db.XDBSqlAdapter.xdmDbSqlRead(XDBSqlAdapter.java:249)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at com.policydm.db.XDB.xdbWrite(XDB.java:1080)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at com.policydm.db.XDBProfileAdp.xdbSetServerAddress(XDBProfileAdp.java:78)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at com.policydm.db.XDB.xdbSetBackUpServerUrl(XDB.java:1833)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpClearSessionStatus(XNOTIAdapter.java:276)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpExcuteResumeNoti(XNOTIAdapter.java:442)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpResumeNotiAction(XNOTIAdapter.java:512)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at com.policydm.agent.XDMUITask.xdmUIEvent(XDMUITask.java:194)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at com.policydm.agent.XDMUITask$1.handleMessage(XDMUITask.java:46)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at com.policydm.agent.XDMUITask.run(XDMUITask.java:50)
03-21 08:36:16.475  3469  3525 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:36:16.475  2725  3310 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 08:36:16.485  3727  3727 I libpersona: KNOX_SDCARD checking this for 10060
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:36:16.485  3727  3727 I libpersona: KNOX_SDCARD not a persona
03-21 08:36:16.475  3469  3525 W SQLiteOpenHelper: Opened policydmdb.db in read-only mode
03-21 08:36:16.475  2725  3310 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 08:36:16.495  1018  1558 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3727 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:36:16.475  2725  3310 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 08:36:16.475  2725  3310 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:36:16.485  3556  3556 E SQLiteLog: (28) failed to open "/data/data/com.dropbox.android/databases/prefs.db" with flag (131138) and mode_t (0) due to error (30)
03-21 08:36:16.485  3727  3727 E Zygote  : MountEmulatedStorage()
03-21 08:36:16.485  3727  3727 E Zygote  : v2
03-21 08:36:16.485  3671  3671 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
03-21 08:36:16.485  3671  3671 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.485  3671  3671 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.485  3671  3671 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.485  3671  3671 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.485  3671  3671 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.485  3671  3671 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.485  3671  3671 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.485  3671  3671 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.485  3671  3671 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.485  3671  3671 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.485  3671  3671 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.485  3671  3671 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.485  3671  3671 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.485  3671  3671 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-21 08:36:16.485  3671  3671 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
03-21 08:36:16.485  3671  3671 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
03-21 08:36:16.485  3671  3671 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 08:36:16.485  3671  3671 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 08:36:16.485  3671  3671 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 08:36:16.485  3671  3671 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-21 08:36:16.485  3671  3671 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 08:36:16.485  3671  3671 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 08:36:16.485  3671  3671 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-21 08:36:16.485  3671  3671 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: Failed to open database '/data/data/com.dropbox.android/databases/prefs.db'.
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at com.dropbox.android.provider.a.a(panda.py:145)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at dbxyzptlk.db240408.w.w.a(panda.py:128)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at dbxyzptlk.db240408.w.w.g(panda.py:121)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at dbxyzptlk.db240408.w.a.<init>(panda.py:63)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at dbxyzptlk.db240408.w.m.r(panda.py:186)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at dbxyzptlk.db240408.w.m.a(panda.py:43)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at dbxyzptlk.db240408.w.n.a(panda.py:200)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at dbxyzptlk.db240408.w.C.c(panda.py:111)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at dbxyzptlk.db240408.w.K.d(panda.py:199)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at dbxyzptlk.db240408.w.m.l(panda.py:496)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at com.dropbox.android.exception.g.a(panda.py:165)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at com.dropbox.android.exception.c.a(panda.py:182)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at com.dropbox.android.b.c(panda.py:344)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at com.dropbox.android.b.<init>(panda.py:275)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at com.dropbox.android.DropboxApplication.onCreate(panda.py:135)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-21 08:36:16.485  3556  3556 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-21 08:36:16.485  3671  3671 E SQLiteOpenHelper: Couldn't open privacy for writing (will try read-only):
03-21 08:36:16.485  3671  3671 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.485  3671  3671 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.485  3671  3671 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.485  3671  3671 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.485  3671  3671 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.485  3671  3671 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.485  3671  3671 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.485  3671  3671 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.485  3671  3671 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.485  3671  3671 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.485  3671  3671 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.485  3671  3671 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.485  3671  3671 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.485  3671  3671 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-21 08:36:16.485  3671  3671 E SQLiteOpenHelper: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
03-21 08:36:16.485  3671  3671 E SQLiteOpenHelper: 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
03-21 08:36:16.485  3671  3671 E SQLiteOpenHelper: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 08:36:16.485  3671  3671 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 08:36:16.485  3671  3671 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
03-21 08:36:16.485  3671  3671 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-21 08:36:16.485  3671  3671 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 08:36:16.485  3671  3671 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 08:36:16.485  3671  3671 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-21 08:36:16.485  3671  3671 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: Couldn't open prefs.db for writing (will try read-only):
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at com.dropbox.android.provider.a.a(panda.py:145)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at dbxyzptlk.db240408.w.w.a(panda.py:128)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at dbxyzptlk.db240408.w.w.g(panda.py:121)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at dbxyzptlk.db240408.w.a.<init>(panda.py:63)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at dbxyzptlk.db240408.w.m.r(panda.py:186)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at dbxyzptlk.db240408.w.m.a(panda.py:43)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at dbxyzptlk.db240408.w.n.a(panda.py:200)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at dbxyzptlk.db240408.w.C.c(panda.py:111)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at dbxyzptlk.db240408.w.K.d(panda.py:199)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at dbxyzptlk.db240408.w.m.l(panda.py:496)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at com.dropbox.android.exception.g.a(panda.py:165)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at com.dropbox.android.exception.c.a(panda.py:182)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at com.dropbox.android.b.c(panda.py:344)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at com.dropbox.android.b.<init>(panda.py:275)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at com.dropbox.android.DropboxApplication.onCreate(panda.py:135)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-21 08:36:16.485  3556  3556 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-21 08:36:16.485  3556  3556 W SQLiteOpenHelper: Opened prefs.db in read-only mode
03-21 08:36:16.485  3469  3525 E SQLiteLog: (28) failed to open "/data/user/0/com.policydm/databases/policydmdb.db" with flag (131138) and mode_t (0) due to error (30)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: Failed to open database '/data/user/0/com.policydm/databases/policydmdb.db'.
03-21 08:36:16.485  3469  3525 E, SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at com.policydm.XDMApplication.xdmDbGetWritableDatabase(XDMApplication.java:258)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDBSqlQuery.xdmDbUpdateProfileRow(XDBSqlQuery.java:150)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDBSqlAdapter.xdmDbSqlUpdate(XDBSqlAdapter.java:82)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDB.xdbWrite(XDB.java:1105)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDBProfileAdp.xdbSetServerAddress(XDBProfileAdp.java:78)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDB.xdbSetBackUpServerUrl(XDB.java:1833)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpClearSessionStatus(XNOTIAdapter.java:276)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpExcuteResumeNoti(XNOTIAdapter.java:442)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpResumeNotiAction(XNOTIAdapter.java:512)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at com.policydm.agent.XDMUITask.xdmUIEvent(XDMUITask.java:194)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at com.policydm.agent.XDMUITask$1.handleMessage(XDMUITask.java:46)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at com.policydm.agent.XDMUITask.run(XDMUITask.java:50)
03-21 08:36:16.485  3469  3525 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:36:16.485  3469  3525 E DBG_POLICYDM: [com.policydm.XDMApplication(262/xdmDbGetWritableDatabase)] android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.495  3727  3727 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-21 08:36:16.495  2725  3310 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with ,flag (131138) and mode_t (0) due to error (30)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:36:16.495  2725  3310 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 08:36:16.495  3727  3727 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.495  2725  331,0 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:36:16.495  2725  3310 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 08:36:16.495  3727  3727 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908),
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:36:16.495  2725  3310 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpen,Helper.java:163)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:36:16.495  2725  3310 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 08:36:16.495  2725  3310 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:36:16.505   278   870 D EnterpriseController: uids 10057
03-21 08:36:16.505   278   870 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-21 08:36:16.505   278   870 D Netd    : getNetworkForDns: using netid 502 for uid 10057
03-21 08:36:16.515  3727  3727 D TimaKeyStoreProvider: TimaSignature is unavailable
03-21 08:36:16.515  3727  3727 D ActivityThread: Added TimaKeyStore provider
03-21 08:36:16.525  3469  3525 E DBG_POLICYDM: [com.policydm.db.XDBSqlQuery(187/xdmDbUpdateProfileRow)] java.lang.NullPointerException: Attempt to invoke virtual method 'int android.database.sqlite.SQLiteDatabase.update(java.lang.String, android.content.ContentValues, java.lang.String, java.lang.String[])' on a null object reference
03-21 08:36:16.525  3469  3525 E SQLiteLog: (28) failed to open "/data/user/0/com.policydm/databases/policydmdb.db" with flag (131138) and mode_t (0) due to error (30)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: Failed to open database '/data/user/0/com.policydm/databases/policydmdb.db'.
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at com.policydm.XDMApplication.xdmDbGetReadableDatabase(XDMApplication.java:241)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDBSqlQuery.xdmDbFetchProfileListRow(XDBSqlQuery.java:771)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDBSqlAdapter.xdmDbSqlRead(XDBSqlAdapter.java:249)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDB.xdbWrite(XDB.java:1080)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDBProfileAdp.xdbSetServerPort(XDBProfileAdp.java:116)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at com.policydm.db.XDB.xdbSetBackUpServerUrl(XDB.java:1834)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpClearSessionStatus(XNOTIAdapter.java:276)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpExcuteResumeNoti(XNOTIAdapter.java:442)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpResumeNotiAction(XNOTIAdapter.java:512)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at com.policydm.agent.XDMUITask.xdmUIEvent(XDMUITask.java:194)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at com.policydm.agent.XDMUITask$1.handleMessage(XDMUITask.java:46)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at com.policydm.agent.XDMUITask.run(XDMUITask.java:50)
03-21 08:36:16.525  3469  3525 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: Couldn't open policydmdb.db for writing (will try read-only):
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at com.policydm.XDMApplication.xdmDbGetReadableDatabase(XDMApplication.java:241)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at com.policydm.db.XDBSqlQuery.xdmDbFetchProfileListRow(XDBSqlQuery.java:771)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at com.policydm.db.XDBSqlAdapter.xdmDbSqlRead(XDBSqlAdapter.java:249)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at com.policydm.db.XDB.xdbWrite(XDB.java:1080)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at com.policydm.db.XDBProfileAdp.xdbSetServerPort(XDBProfileAdp.java:116)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at com.policydm.db.XDB.xdbSetBackUpServerUrl(XDB.java:1834)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpClearSessionStatus(XNOTIAdapter.java:276)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpExcuteResumeNoti(XNOTIAdapter.java:442)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at com.policydm.noti.XNOTIAdapter.xnotiPushAdpResumeNotiAction(XNOTIAdapter.java:512)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at com.policydm.agent.XDMUITask.xdmUIEvent(XDMUITask.java:194)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at com.policydm.agent.XDMUITask$1.handleMessage(XDMUITask.java:46)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at com.policydm.agent.XDMUITask.run(XDMUITask.java:50)
03-21 08:36:16.525  3469  3525 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:36:16.525  3469  3525 W SQLiteOpenHelper: Opened policydmdb.db in read-only mode
03-21 08:36:16.535  3469  3525 E SQLiteLog: (28) failed to open "/data/user/0/com.policydm/databases/policydmdb.db" with flag (131138) and mode_t (0) due to error (30)
03-21 08:36:16.535  3671  3671 W SQLiteOpenHelper: Opened privacy in read-only mode
03-21 08:36:16.535  2725  3310 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-21 08:36:16.535  2725  3310 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-21 08:36:16.535  2725  3310 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:36:16.535  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:36:16.535  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-21 08:36:16.535  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-21 08:36:16.535  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-21 08:36:16.535  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-21 08:36:16.535  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 08:36:16.535  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-21 08:36:16.535  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-21 08:36:16.535  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-21 08:36:16.535  2725  3310 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-21 08:36:16.535  2725  3310 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-21 08:36:16.535  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:36:16.535  2725  3310 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 08:36:16.535  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-21 08:36:16.535  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-21 08:36:16.535  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-21 08:36:16.535  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.535  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-21 08:36:16.535  2725  3310 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-21 08:36:16.535  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 08:36:16.535  2725  3310 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecuto
```
