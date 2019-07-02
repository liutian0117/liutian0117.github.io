---
layout: post
title: iOS系统通知(NSNotification.Name)一览

---

[`static let AVAudioEngineConfigurationChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1389078-avaudioengineconfigurationchange)
音频引擎配置更改时发布的通知。

**AVAudioSession相关：**(在Swift 5中调用：AVAudioSession.notificationName)

[`class let interruptionNotification: NSNotification.Name`](https://developer.apple.com/documentation/avfoundation/avaudiosession/1616596-interruptionnotification)
在发生音频中断时发布。

[`class let mediaServicesWereLostNotification: NSNotification.Name`](https://developer.apple.com/documentation/avfoundation/avaudiosession/1616457-mediaserviceswerelostnotificatio)
在媒体服务器终止时发布。

[`class let mediaServicesWereResetNotification: NSNotification.Name`](https://developer.apple.com/documentation/avfoundation/avaudiosession/1616540-mediaserviceswereresetnotificati)
在媒体服务器重新启动时发布。

[`class let routeChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/avfoundation/avaudiosession/1616493-routechangenotification)
当系统音频路由改变时发布。

[`class let silenceSecondaryAudioHintNotification: NSNotification.Name`](https://developer.apple.com/documentation/avfoundation/avaudiosession/1616622-silencesecondaryaudiohintnotific)
在其他应用程序的主音频启动和停止时发布。

[`static let AVAudioUnitComponentTagsDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1387538-avaudiounitcomponenttagsdidchang)
组件标记已更改。

[`static let CKAccountChanged: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1399172-ckaccountchanged)
已登录iCloud帐户的状态可能已更改时发布的通知。

[`static let CNContactStoreDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1403253-cncontactstoredidchange)
在联系人存储发生更改时发布。

[`static let EKEventStoreChanged: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1507525-ekeventstorechanged)
对日历数据库进行更改时发布的通知。

[`static let HKUserPreferencesDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1614169-hkuserpreferencesdidchange)
当使用者改变其或其优先单位时，通知观察员。(HealthKit)

[`let HMCharacteristicPropertySupportsEventNotification: String`](https://developer.apple.com/documentation/homekit/hmcharacteristicpropertysupportsevent)
该特性支持事件通知。(HomeKit)

[`static let NSBundleResourceRequestLowDiskSpace: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1614835-nsbundleresourcerequestlowdisksp)
在系统检测到可用磁盘空间不足后发布。通知将发布到默认通知中心。

[`static let NSCalendarDayChanged: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1408062-nscalendardaychanged)
由系统日历、区域设置和时区决定的系统日历日更改时发布的通知。

[`static let NSDidBecomeSingleThreaded: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1412246-nsdidbecomesinglethreaded)
未实现。

[`static let NSExtensionHostDidBecomeActive: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1616429-nsextensionhostdidbecomeactive)
当扩展的主机应用程序从非活动状态移动到活动状态时发布。

[`static let NSExtensionHostDidEnterBackground: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1616212-nsextensionhostdidenterbackgroun)
当扩展的主机应用程序开始在后台运行时发布。

[`static let NSExtensionHostWillEnterForeground: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1616748-nsextensionhostwillenterforegrou)
当扩展的主机应用程序在前台开始运行时发布。

[`static let NSExtensionHostWillResignActive: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1616519-nsextensionhostwillresignactive)
当扩展的主机应用程序从活动状态移动到非活动状态时发布。

[`static let NSFileHandleConnectionAccepted: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1417116-nsfilehandleconnectionaccepted)
当“nsfilehandle”对象在两个进程之间建立套接字连接，为连接的一端创建“nsfilehandle”对象，并通过将其放入“userinfo”字典使该对象对观察员可用时，将发布此通知。

[`static let NSFileHandleDataAvailable: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1415913-nsfilehandledataavailable)
当文件句柄确定当前可在文件或通信通道中读取数据时，将发布此通知。

[`static let NSFileHandleReadToEndOfFileCompletion: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1416927-nsfilehandlereadtoendoffilecompl)
当文件句柄读取文件中的所有数据时，或者如果是通信通道，则在另一个进程发出数据结束的信号之前，发布此通知。

[`static let NSHTTPCookieManagerAcceptPolicyChanged: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1415149-nshttpcookiemanageracceptpolicyc)
当cookie存储的接受策略更改时发布的通知。

[`static let NSHTTPCookieManagerCookiesChanged: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1409500-nshttpcookiemanagercookieschange)
当存储在cookie存储中的cookie发生更改时发布的通知。

[`static let NSManagedObjectContextDidSave: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1506380-nsmanagedobjectcontextdidsave)
上下文完成保存的通知。

[`static let NSManagedObjectContextObjectsDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1506884-nsmanagedobjectcontextobjectsdid)
对与此上下文关联的托管对象所做更改的通知。

[`static let NSManagedObjectContextWillSave: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1506816-nsmanagedobjectcontextwillsave)
上下文将要保存的通知。

[`static let NSMetadataQueryDidFinishGathering: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1414740-nsmetadataquerydidfinishgatherin)
当接收器完成查询的初始结果收集阶段时发布。

[`static let NSMetadataQueryDidStartGathering: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1416717-nsmetadataquerydidstartgathering)
当接收者开始查询的初始结果收集阶段时发布。

[`static let NSMetadataQueryDidUpdate: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1413406-nsmetadataquerydidupdate)
当接收者的结果在查询的实时更新阶段发生更改时发布。

[`static let NSMetadataQueryGatheringProgress: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1408041-nsmetadataquerygatheringprogress)
作为接收者发布的是在查询的初始结果收集阶段收集结果。

[`static let NSPersistentStoreCoordinatorStoresDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1468925-nspersistentstorecoordinatorstor)
无论何时将持久存储添加到持久存储协调器中或从持久存储协调器中删除，或存储UUID更改，都会发布。

[`static let NSPersistentStoreCoordinatorStoresWillChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1468800-nspersistentstorecoordinatorstor)
在打开的持久存储更改列表之前发布。

[`static let NSPersistentStoreCoordinatorWillRemoveStore: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1468876-nspersistentstorecoordinatorwill)
每当从持久性存储协调器中删除持久性存储时发布。

[`static let NSProcessInfoPowerStateDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1617322-nsprocessinfopowerstatedidchange)
当iOS设备的电源状态（低功耗模式启用或禁用）更改时发布。

[`static let NSSystemClockDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1414255-nssystemclockdidchange)
每当系统时钟改变时发出的通知。

[`static let NSSystemTimeZoneDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1387256-nssystemtimezonedidchange)
时区更改时发布的通知。

[`static let NSThreadWillExit: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1408204-nsthreadwillexit)
当一个`NSThread` 对象在线程退出之前收到 [`exit()`](https://developer.apple.com/documentation/foundation/thread/1409404-exit)消息时，它会发布此通知。为接收此通知而调用的观察器方法在退出线程之前在退出线程中执行。

[`static let NSURLCredentialStorageChanged: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1412767-nsurlcredentialstoragechanged)
存储的凭据集更改时发布的通知。

[`static let NSUbiquityIdentityDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1407629-nsubiquityidentitydidchange)
在iCloud (“ubiquity”)身份更改后发送。

[`static let NSUndoManagerCheckpoint: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1417262-nsundomanagercheckpoint)
每当 `NSUndoManager` 对象 打开或关闭撤销组（除了打开顶层组）和检查[`canRedo`](https://developer.apple.com/documentation/foundation/undomanager/1415212-canredo)中的重做堆栈。

[`static let NSUndoManagerDidCloseUndoGroup: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1408817-nsundomanagerdidcloseundogroup)
每当 `NSUndoManager` 对象关闭一个撤销组后发布, 该撤销组出现在 [`endUndoGrouping()`](https://developer.apple.com/documentation/foundation/undomanager/1416490-endundogrouping) 方法。

[`static let NSUndoManagerDidOpenUndoGroup: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1415906-nsundomanagerdidopenundogroup)
每当 `NSUndoManager` 对象打开一个撤销组时发布, 该撤销组出现在 [`beginUndoGrouping()`](https://developer.apple.com/documentation/foundation/undomanager/1409894-beginundogrouping) 方法。

[`static let NSUndoManagerDidRedoChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1413579-nsundomanagerdidredochange)
在 `NSUndoManager` 对象执行重做操作后发布。 ([`redo()`](https://developer.apple.com/documentation/foundation/undomanager/1417030-redo)).

[`static let NSUndoManagerDidUndoChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1410142-nsundomanagerdidundochange)
在 `NSUndoManager` 对象执行撤销操作后发布。

[`static let NSUndoManagerWillCloseUndoGroup: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1411493-nsundomanagerwillcloseundogroup)
在 `NSUndoManager` 对象关闭撤销组之前发布， 该撤销组出现在 [`endUndoGrouping()`](https://developer.apple.com/documentation/foundation/undomanager/1416490-endundogrouping) 方法。

[`static let NSUndoManagerWillRedoChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1416239-nsundomanagerwillredochange)
在 `NSUndoManager` 对象执行重做操作之前发布。 ([`redo()`](https://developer.apple.com/documentation/foundation/undomanager/1417030-redo))。

[`static let NSUndoManagerWillUndoChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1412921-nsundomanagerwillundochange)
在 `NSUndoManager` 对象执行撤销操作之前发布。

[`static let NSWillBecomeMultiThreaded: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1417567-nswillbecomemultithreaded)
在第一个线程与当前线程分离时发布。NSThread 类在第一次分离线程时最多发布一次此通知，使用 [`detachNewThreadSelector(_:toTarget:with:)`](https://developer.apple.com/documentation/foundation/thread/1415633-detachnewthreadselector) 或者 [`start()`](https://developer.apple.com/documentation/foundation/thread/1418166-start) 方法。这些方法的后续调用不会发布此通知。此通知的观察者在主线程中调用了他们的通知方法，而不是新线程。观察者通知方法总是在新线程开始执行之前执行。

[`static let PKPassLibraryDidChange: PKPassLibraryNotificationName`](https://developer.apple.com/documentation/passkit/pkpasslibrarynotificationname/1617102-pkpasslibrarydidchange)
在更改通行证库后发布。

[`static let PKPassLibraryRemotePaymentPassesDidChange: PKPassLibraryNotificationName`](https://developer.apple.com/documentation/passkit/pkpasslibrarynotificationname/1617075-pkpasslibraryremotepaymentpasses)
在与当前iOS设备（例如Apple Watch）配对的设备中添加或删除Apple Pay卡时发布。

[`static let announcementDidFinishNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiaccessibility/1620202-announcementdidfinishnotificatio)
当系统阅读完公告后由uikit发布。

[`static let elementFocusedNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiaccessibility/1620210-elementfocusednotification)
当辅助技术关注某个元素时，由uikit发布。

[`static let ABPeoplePickerDisplayedPropertyDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1458299-abpeoplepickerdisplayedpropertyd)
更改记录列表中显示的属性时发布。

[`static let ABPeoplePickerGroupSelectionDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1458530-abpeoplepickergroupselectiondidc)
更改组列表中的选择时发布。

[`static let ABPeoplePickerNameSelectionDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1458587-abpeoplepickernameselectiondidch)
在更改名称列表中的选择时发布。

[`static let ABPeoplePickerValueSelectionDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1458721-abpeoplepickervalueselectiondidc)
在更改多值属性中的选择时发布。

[`static let ACAccountStoreDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1493946-acaccountstoredidchange)
此帐户存储管理的帐户在数据库中更改时发布。没有与此通知关联的 `userInfo` 字典

[`static let AVAssetChapterMetadataGroupsDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1386794-avassetchaptermetadatagroupsdidc)
当表示AVAsset章节的定时元数据组数组集合更改以及定时元数据组的任何内容更改时发布，但仅限于@"availableChapterLocales"值的状态达到AVKeyValueStatusLoaded后发生的更改。

[`static let AVAssetContainsFragmentsDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1387022-avassetcontainsfragmentsdidchang)
在加载@"containsFragments"的值并将AVFragmentedAsset添加到AVFragmentedAssetMinder之后发布，无论是在以下情况下：1）在磁盘上的资产中检测到碎片（之前未包含任何碎片）还是在2）在磁盘上的资产中检测不到碎片（之前包含一个或多个碎片）。

[`static let AVAssetDurationDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1386249-avassetdurationdidchange)
当AVFragmentedAsset的持续时间在被AVFragmentedAssetMinder关注时发生更改，但仅当@"duration"值的状态达到AVKeyValueStatusLoaded后发生更改时发布。

[`static let AVAssetMediaSelectionGroupsDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1387984-avassetmediaselectiongroupsdidch)
当由AVAsset提供的媒体选择组集合更改以及其媒体选择组的任何内容更改时发布，但仅当@"availableMediaCharacteristicsWithMediaSelectionOptions"的值状态达到AVKeyValueStatusLoaded后发生的更改。

[`static let AVAssetTrackSegmentsDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1386848-avassettracksegmentsdidchange)
当AVFragmentedAssetTrack的段数组更改时发布，而AVFragmentedAsset的关联实例正由AVFragmentedAssetMinder处理，但仅限于@"segments"的值状态达到AVKeyValueStatusLoaded后发生的更改。

[`static let AVAssetTrackTimeRangeDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1385765-avassettracktimerangedidchange)
当AVFragmentedAssetTrack的时间范围发生更改，而AVFragmentedAsset的关联实例正由AVFragmentedAssetMinder处理时发布，但仅限于@"timeRange"的值状态达到AVKeyValueStatusLoaded后发生的更改。

[`static let AVAssetTrackTrackAssociationsDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1388487-avassettracktrackassociationsdid)
当AVAssetTrack的跟踪关联集合更改时发布，但仅限于@"AvailableTrackAssociationTypes"值状态达到AVKeyValueStatusLoaded后发生的更改。

[`static let AVAssetWasDefragmented: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1389894-avassetwasdefragmented)
当对磁盘上的资产进行碎片整理而AVFragmentedAsset正由AVFragmentedAssetMinder处理时发布，但仅当碎片整理发生在@"canContainFragments" 值的状态达到AVKeyValueStatusLoaded之后。
在发布此通知后，资产属性canContainFragments和containsFragments的值都将为NO。

[`static let AVCaptureDeviceWasConnected: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1389018-avcapturedevicewasconnected)
当新设备可用时发布。

[`static let AVCaptureDeviceWasDisconnected: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1387782-avcapturedevicewasdisconnected)
当现有设备不可用时发布。

[`static let AVCaptureInputPortFormatDescriptionDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1390288-avcaptureinputportformatdescript)
如果捕获输入端口的[`formatDescription`](https://developer.apple.com/documentation/avfoundation/avcaptureinput/port/1385890-formatdescription)属性值发生更改，则发布。

[`static let AVCaptureSessionDidStartRunning: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1387835-avcapturesessiondidstartrunning)
在捕获会话开始时发布。

[`static let AVCaptureSessionDidStopRunning: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1389889-avcapturesessiondidstoprunning)
在捕获会话停止时发布。

[`static let AVCaptureSessionRuntimeError: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1389738-avcapturesessionruntimeerror)
在捕获会话期间发生错误时发布。

[`static let AVPlayerItemDidPlayToEndTime: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1386566-avplayeritemdidplaytoendtime)
当项目播放到其结束时间时发布的通知。

[`static let AVPlayerItemFailedToPlayToEndTime: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1388007-avplayeritemfailedtoplaytoendtim)
当项目未能播放到其结束时间时发布的通知。

[`static let AVPlayerItemNewAccessLogEntry: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1388553-avplayeritemnewaccesslogentry)
在添加新的访问日志条目时发布的通知。

[`static let AVPlayerItemNewErrorLogEntry: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1388450-avplayeritemnewerrorlogentry)
在添加新的错误日志条目时发布的通知。

[`static let AVPlayerItemPlaybackStalled: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1387661-avplayeritemplaybackstalled)
当某些媒体没有及时到达继续播放时发布的通知。


[`static let AVPlayerItemTimeJumped: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1390911-avplayeritemtimejumped)
当项目的当前时间不连续更改时发布的通知。

[`static let AVSampleBufferDisplayLayerFailedToDecode: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1390290-avsamplebufferdisplaylayerfailed)
缓冲区显示层解码失败时发布。

[`static let GCControllerDidConnect: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1458856-gccontrollerdidconnect)
新控制器连接到设备后立即发布。


[`static let GCControllerDidDisconnect: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1458875-gccontrollerdiddisconnect)
控制器与设备断开后立即发布。

[`static let IKFilterBrowserFilterDoubleClick: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1503796-ikfilterbrowserfilterdoubleclick)
当用户双击过滤器浏览器中的过滤器时发布。

[`static let IKFilterBrowserFilterSelected: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1504335-ikfilterbrowserfilterselected)
当用户单击过滤器浏览器中的过滤器名称时发布。

[`static let IKFilterBrowserWillPreviewFilter: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1503727-ikfilterbrowserwillpreviewfilter)
在显示筛选器预览之前发布，允许应用程序设置筛选器的参数。

[`static let NEFilterConfigurationDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1406656-nefilterconfigurationdidchange)
在网络扩展首选项中存储的筛选器配置更改后发布。

[`static let NEVPNConfigurationChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1406509-nevpnconfigurationchange)
在网络扩展首选项中存储的VPN配置更改后发布。

[`static let NEVPNStatusDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1406683-nevpnstatusdidchange)
在VPN连接状态更改时发布。

[`class let didProcessEditingNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/nstextstorage/1525483-didprocesseditingnotification)
在文本存储完成处理 [`processEditing()`](https://developer.apple.com/documentation/uikit/nstextstorage/1525980-processediting)中的编辑后发布。

[`class let willProcessEditingNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/nstextstorage/1529695-willprocesseditingnotification)
在文本存储完成处理 [`processEditing()`](https://developer.apple.com/documentation/uikit/nstextstorage/1525980-processediting)中的编辑之前发布。

[`static let PDFDocumentDidBeginFind: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1436055-pdfdocumentdidbeginfind)
[`beginFindString(_:withOptions:)`](https://developer.apple.com/documentation/pdfkit/pdfdocument/1436078-beginfindstring) 方法或 [`findString(_:withOptions:)`](https://developer.apple.com/documentation/pdfkit/pdfdocument/1436060-findstring) 方法开始查找时发布。

[`static let PDFDocumentDidBeginPageFind: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1436027-pdfdocumentdidbeginpagefind)
查找操作开始在文档的新页上工作的通知。

[`static let PDFDocumentDidBeginPageWrite: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1436072-pdfdocumentdidbeginpagewrite)
写操作开始在文档的一页上工作的通知。

[`static let PDFDocumentDidBeginWrite: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1436047-pdfdocumentdidbeginwrite)
写操作开始在文档上工作的通知。

[`static let PDFDocumentDidEndFind: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1436083-pdfdocumentdidendfind)

[`beginFindString(_:withOptions:)`](https://developer.apple.com/documentation/pdfkit/pdfdocument/1436078-beginfindstring) 方法或 [`findString(_:withOptions:)`](https://developer.apple.com/documentation/pdfkit/pdfdocument/1436060-findstring) 方法结束查找时发布。

[`static let PDFDocumentDidEndPageFind: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1436067-pdfdocumentdidendpagefind)
当对文档中某一页查找操作完成时的通知。

[`static let PDFDocumentDidEndPageWrite: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1436037-pdfdocumentdidendpagewrite)
当对文档中某一页写操作完成时的通知。

[`static let PDFDocumentDidEndWrite: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1436026-pdfdocumentdidendwrite)
当对文档写操作完成时的通知。

[`static let PDFDocumentDidFindMatch: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1436045-pdfdocumentdidfindmatch)
在文档中找到字符串匹配的通知。

[`static let PDFDocumentDidUnlock: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1436052-pdfdocumentdidunlock)
当文档在 [`unlock(withPassword:)`](https://developer.apple.com/documentation/pdfkit/pdfdocument/1436033-unlock) 消息后解锁的通知。

[`static let PDFThumbnailViewDocumentEdited: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1503417-pdfthumbnailviewdocumentedited)
No overview available.

[`static let PDFViewAnnotationHit: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1504809-pdfviewannotationhit)
当用户单击注释时发布的通知。

[`static let PDFViewAnnotationWillHit: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1503445-pdfviewannotationwillhit)
在用户单击注释之前发布的通知。

[`static let PDFViewChangedHistory: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1504592-pdfviewchangedhistory)
页面历史记录更改时发布的通知。

[`static let PDFViewCopyPermission: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1503486-pdfviewcopypermission)
当用户试图在没有适当权限的情况下复制到粘贴板时发布的通知。

[`static let PDFViewDisplayBoxChanged: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1503746-pdfviewdisplayboxchanged)
显示框更改时发布的通知。

[`static let PDFViewDisplayModeChanged: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1505055-pdfviewdisplaymodechanged)
滚动视图滚动到新页面边界时的通知。

[`static let PDFViewDocumentChanged: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1503832-pdfviewdocumentchanged)
当新文档与视图关联时发布的通知。

[`static let PDFViewPageChanged: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1505038-pdfviewpagechanged)
当新页面成为当前页面时发布的通知。


[`static let PDFViewPrintPermission: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1503871-pdfviewprintpermission)
当用户尝试在没有适当权限的情况下打印时发布的通知。


[`static let PDFViewScaleChanged: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1503538-pdfviewscalechanged)
尺寸比例系数更改时发布的通知。

[`static let PDFViewSelectionChanged: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1504693-pdfviewselectionchanged)
当前所选内容更改时发布的通知。

[`static let PDFViewVisiblePagesChanged: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1503651-pdfviewvisiblepageschanged)
可见页面更改时发布的通知。

[`static let EAAccessoryDidConnect: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1613827-eaaccessorydidconnect)
当附件连接并可供应用程序使用时发布的通知。

[`static let EAAccessoryDidDisconnect: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1613901-eaaccessorydiddisconnect)
当附件断开连接且不再可供应用程序使用时发布的通知。

StoreKit

[`static let SKCloudServiceCapabilitiesDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1620626-skcloudservicecapabilitiesdidcha)
用于指示与设备上的音乐库关联的功能更改的通知名称。

[`static let SKStorefrontIdentifierDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1620636-skstorefrontidentifierdidchange)
用于指示与设备关联的店面标识符更改的通知名称。

[`static let assistiveTouchStatusDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiaccessibility/1648473-assistivetouchstatusdidchangenot)
当系统首选项中辅助功能的启用状态发生更改时，由UIKit发布。

[`static let boldTextStatusDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiaccessibility/1615152-boldtextstatusdidchangenotificat)
当系统的粗体文本设置更改时，由UIKit发布。

[`static let closedCaptioningStatusDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiaccessibility/1615101-closedcaptioningstatusdidchangen)
关闭字幕设置更改时，由UIKit发布。

[`static let darkerSystemColorsStatusDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiaccessibility/1615177-darkersystemcolorsstatusdidchang)
当系统的暗颜色设置更改时，由UIKit发布。

[`static let grayscaleStatusDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiaccessibility/1615085-grayscalestatusdidchangenotifica)
当系统的灰度设置更改时，由UIKit发布。

[`static let guidedAccessStatusDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiaccessibility/1615105-guidedaccessstatusdidchangenotif)
在引导访问会话开始或结束时，由UIKit发布。

[`static let hearingDevicePairedEarDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiaccessibility/1648478-hearingdevicepairedeardidchangen)
当当前配对的听力设备发生变化时，由UIKit发布。

[`static let invertColorsStatusDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiaccessibility/1615196-invertcolorsstatusdidchangenotif)
当反转颜色的设置发生变化时，由UIKit发布。

[`static let monoAudioStatusDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiaccessibility/1615185-monoaudiostatusdidchangenotifica)
当系统音频从立体声变为单声道时，由UIKit发布。

[`static let reduceMotionStatusDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiaccessibility/1615204-reducemotionstatusdidchangenotif)
当系统的减少运动设置改变时，由UIKit发布。

[`static let reduceTransparencyStatusDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiaccessibility/1615125-reducetransparencystatusdidchang)
当系统的降低透明度系统设置发生更改时，由UIKit发布。

[`static let shakeToUndoDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiaccessibility/1615095-shaketoundodidchangenotification)
当系统的Shake to Undo功能启用或禁用时，由UIKit发布。

[`static let speakScreenStatusDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiaccessibility/1615097-speakscreenstatusdidchangenotifi)
当系统的语音屏幕设置更改时，由UIKit发布。

[`static let speakSelectionStatusDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiaccessibility/1615127-speakselectionstatusdidchangenot)
当系统的语音选择设置更改时，由UIKit发布。

[`static let switchControlStatusDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiaccessibility/1615099-switchcontrolstatusdidchangenoti)
当系统的开关控制设置更改时，由UIKit发布。

[`class let didBecomeActiveNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiapplication/1622953-didbecomeactivenotification)
当应用程序激活时发布。

[`class let didEnterBackgroundNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiapplication/1623071-didenterbackgroundnotification)
当应用程序进入后台时发布。

[`class let didFinishLaunchingNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiapplication/1622971-didfinishlaunchingnotification)
应用程序启动后立即发布。

[`class let didReceiveMemoryWarningNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiapplication/1622920-didreceivememorywarningnotificat)
当应用程序收到操作系统关于低内存可用性的警告时发布。

[`class let significantTimeChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiapplication/1623059-significanttimechangenotificatio)
当时间发生重大变化时发布，例如，更改为新的一天（午夜）、运营商时间更新以及更改为夏令时或从夏令时更改为夏令时。

[`class let userDidTakeScreenshotNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiapplication/1622966-userdidtakescreenshotnotificatio)
当用户按下Home和Lock按钮进行屏幕截图时发布。

[`class let willEnterForegroundNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiapplication/1622944-willenterforegroundnotification)
在一个应用离开后台状态进入活动应用程序之前不久发布。

[`class let willResignActiveNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiapplication/1622973-willresignactivenotification)
当应用程序不再活动并失去焦点时发布。

[`class let willTerminateNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiapplication/1623061-willterminatenotification)
在应用程序即将终止时发布。

[`static let didChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uicontentsizecategory/1622948-didchangenotification)
当用户更改首选内容大小设置时发布。

[`class let proximityStateDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uidevice/1620046-proximitystatedidchangenotificat)
当接近传感器的状态改变时发布。

[`class let brightnessDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiscreen/1617832-brightnessdidchangenotification)
当屏幕亮度发生变化时，将发布此通知。

[`class let didConnectNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiscreen/1617826-didconnectnotification)
当新屏幕连接到设备时，会发布此通知。

[`class let didDisconnectNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiscreen/1617837-diddisconnectnotification)
当屏幕与设备断开连接时，会发布此通知。

[`class let modeDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiscreen/1617840-modedidchangenotification)
当屏幕的当前模式更改时，将发布此通知。

[`class let selectionDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uitableview/1614958-selectiondidchangenotification)
在“过账表”视图中选定的行更改时过账。

[`class let textDidBeginEditingNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uitextfield/1619616-textdidbegineditingnotification)
通知观察员在文本字段中开始了编辑会话。受影响的文本字段存储在通知的 `object`参数中。未使用`userInfo`字典。

[`class let textDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uitextfield/1619640-textdidchangenotification)
通知观察员文本字段中的文本已更改。受影响的文本字段存储在通知的 `object`参数中。

[`class let textDidEndEditingNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uitextfield/1619633-textdidendeditingnotification)
通知观察员文本字段的编辑会话已结束。受影响的文本字段存储在通知的 `object`参数中。未使用`userInfo`字典。

[`class let currentInputModeDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uitextinputmode/1614517-currentinputmodedidchangenotific)
当前输入模式更改时发布。

[`class let textDidBeginEditingNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uitextview/1618612-textdidbegineditingnotification)
通知观察员在文本视图中开始了编辑会话。受影响的视图存储在通知的 `object`参数中。未使用`userInfo`字典。

[`class let textDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uitextview/1618609-textdidchangenotification)
通知观察者文本视图中的文本已更改。受影响的视图存储在通知的 `object`参数中。未使用`userInfo`字典。

[`class let textDidEndEditingNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uitextview/1618625-textdidendeditingnotification)
通知观察员文本视图的编辑会话已结束。受影响的视图存储在通知的`object`参数中。未使用`userInfo`字典。

[`class let showDetailTargetDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiviewcontroller/1621368-showdetailtargetdidchangenotific)
在展开或折叠拆分视图控制器时发布。

[`class let didBecomeHiddenNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiwindow/1621617-didbecomehiddennotification)
当 `UIWindow` 对象变为隐藏时发布。

[`class let didBecomeKeyNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiwindow/1621607-didbecomekeynotification)
当 `UIWindow` 对象成为关键窗口时发布。

[`class let didBecomeVisibleNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiwindow/1621621-didbecomevisiblenotification)
当 `UIWindow` 对象可见时发布。

[`class let didResignKeyNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiwindow/1621591-didresignkeynotification)
当 `UIWindow` 对象重新将其状态设置为主窗口时发布。

[`static let AVCaptureDeviceSubjectAreaDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1624619-avcapturedevicesubjectareadidcha)
当 `AVCaptureDevice` 的实例检测到视频主题区域有实质性变化时发布。

[`static let AVCaptureSessionInterruptionEnded: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1620472-avcapturesessioninterruptionende)
在捕获会话中断完成时发布。

[`static let AVCaptureSessionWasInterrupted: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1620491-avcapturesessionwasinterrupted)
在捕获会话中断时发布。

[`static let MFMessageComposeViewControllerTextMessageAvailabilityDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1614064-mfmessagecomposeviewcontrollerte)
当 [`canSendText()`](https://developer.apple.com/documentation/messageui/mfmessagecomposeviewcontroller/1614072-cansendtext) 类方法返回的值更改时发布。

[`static let MPMediaLibraryDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1621283-mpmedialibrarydidchange)
指示媒体库已更改。

[`static let MPMusicPlayerControllerNowPlayingItemDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1624257-mpmusicplayercontrollernowplayin)
在当前播放的媒体项发生更改时发布。

[`static let MPMusicPlayerControllerPlaybackStateDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1624162-mpmusicplayercontrollerplaybacks)
以编程方式或用户操作更改播放状态时发布。

[`static let MPMusicPlayerControllerVolumeDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1624238-mpmusicplayercontrollervolumedid)
当音乐播放器的音频播放音量改变时发布。

[`class let backgroundRefreshStatusDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiapplication/1623085-backgroundrefreshstatusdidchange)
当应用程序在后台下载内容的状态更改时发布。

[`class let batteryLevelDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uidevice/1620060-batteryleveldidchangenotificatio)
当电池电量变化时发布。

[`class let batteryStateDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uidevice/1620052-batterystatedidchangenotificatio)
电池状态改变时发布。

[`class let orientationDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uidevice/1620025-orientationdidchangenotification)
当设备方向改变时发布。

[`class let stateChangedNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uidocument/1619945-statechangednotification)
当文档状态发生更改时由文档对象发布。

[`class let keyboardDidChangeFrameNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiresponder/1621619-keyboarddidchangeframenotificati)
在键盘框架发生变化后立即发布。

[`class let keyboardDidHideNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiresponder/1621579-keyboarddidhidenotification)
删除键盘后立即发布。

[`class let keyboardDidShowNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiresponder/1621602-keyboarddidshownotification)
显示键盘后立即发布。

[`class let keyboardWillChangeFrameNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiresponder/1621623-keyboardwillchangeframenotificat)
在键盘框架发生变化之前立即发布。

[`class let keyboardWillHideNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiresponder/1621606-keyboardwillhidenotification)
在删除键盘前立即发布。

[`class let keyboardWillShowNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiresponder/1621576-keyboardwillshownotification)
在键盘显示前立即发布。

[`class let didHideMenuNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uimenucontroller/1622825-didhidemenunotification)
由菜单控制器在隐藏菜单后发布。

[`class let didShowMenuNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uimenucontroller/1622814-didshowmenunotification)
显示菜单后，由菜单控制器发布。

[`class let menuFrameDidChangeNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uimenucontroller/1622834-menuframedidchangenotification)
当可见菜单的框架更改时发布。

[`class let willHideMenuNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uimenucontroller/1622818-willhidemenunotification)
在隐藏菜单之前由菜单控制器发布。

[`class let willShowMenuNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uimenucontroller/1622830-willshowmenunotification)
由菜单控制器在显示菜单之前发布。

[`class let changedNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uipasteboard/1622104-changednotification)
当内容更改时由粘贴板对象发布。

[`class let removedNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uipasteboard/1622082-removednotification)
在应用程序删除粘贴板对象之前发布。

[`class let protectedDataDidBecomeAvailableNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiapplication/1623039-protecteddatadidbecomeavailablen)
当受保护的文件可供代码访问时发布。

[`class let protectedDataWillBecomeUnavailableNotification: NSNotification.Name`](https://developer.apple.com/documentation/uikit/uiapplication/1623058-protecteddatawillbecomeunavailab)
在受保护的文件被锁定并无法访问之前不久发布。

[`static let MPMusicPlayerControllerQueueDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/2815063-mpmusicplayercontrollerqueuedidc)
表示音乐播放器的队列已更改。

[`static let ASAuthorizationAppleIDProviderCredentialRevoked: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/3175424-asauthorizationappleidprovidercr)
No overview available.

[`static let AVPlayerAvailableHDRModesDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/2936888-avplayeravailablehdrmodesdidchan)
每当可用的hdrmodes更改时激发的通知。

[`static let AVRouteDetectorMultipleRoutesDetectedDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/2915761-avroutedetectormultipleroutesdet)
当[`multipleRoutesDetected`](https://developer.apple.com/documentation/avfoundation/avroutedetector/2915760-multipleroutesdetected) 的值更改时发布。

[`static let AVSampleBufferAudioRendererWasFlushedAutomatically: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/2921578-avsamplebufferaudiorendererwasfl)
当由于调用-flush方法以外的原因刷新接收器的排队媒体数据时，该通知将激发。

[`static let CTServiceRadioAccessTechnologyDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/3024509-ctserviceradioaccesstechnologydi)
无线接入技术改变时的一种广播。

[`static let GKPlayerAuthenticationDidChangeNotificationName: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1515396-gkplayerauthenticationdidchangen)
发布在共享本地玩家更改[`isAuthenticated`](https://developer.apple.com/documentation/gamekit/gklocalplayer/1515402-isauthenticated) 对象之后。此通知的对象属性是`GKLocalPlayer`对象。传递 `nil` 提供标准通知中心行为，用于接收任何对象的通知。

[`static let GKPlayerDidChangeNotificationName: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/1520710-gkplayerdidchangenotificationnam)
当玩家对象的数据更改时发布。

[`static let NEDNSProxyConfigurationDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/2880182-nednsproxyconfigurationdidchange)
当DNS代理配置更改时发布的通知。

[`static let NSPersistentStoreRemoteChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/3180044-nspersistentstoreremotechange)
NSPersistentStoreRemoteChangeNotification是所有交叉张贴写的存储过程。
有效载荷是在商店，商店的 UUID (NSStoreUUIDKey), URL (NSPersistentStoreURLKey), 和 NSPersistentHistoryToken 的事务（如果NSPersistentHistoryTrackingKey 也被设置了)。

[`static let SKStorefrontCountryCodeDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/2909077-skstorefrontcountrycodedidchange)
用于指示与设备关联的店面国家/地区代码更改的通知名称。

[`static let UIAccessibilityOnOffSwitchLabelsDidChange: NSNotification.Name`](https://developer.apple.com/documentation/foundation/nsnotification/name/3131974-uiaccessibilityonoffswitchlabels)
No overview available.

