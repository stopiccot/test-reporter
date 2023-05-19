![Tests passed successfully](https://img.shields.io/badge/tests-47%20passed-success)
## ✅ <a id="user-content-r0" href="#r0">fixtures/dotnet-nunit.xml</a>
**47** tests were completed in **1s** with **47** passed, **0** failed and **0** skipped.
|Test suite|Passed|Failed|Skipped|Time|
|:---|---:|---:|---:|---:|
|[TripledotPlatform.TripleDotPlatform.Tests.Editor.dll.TripleDot.Tests.Editor](#r0s0)|47✅|||1s|
### ✅ <a id="user-content-r0s0" href="#r0s0">TripledotPlatform.TripleDotPlatform.Tests.Editor.dll.TripleDot.Tests.Editor</a>
```
AppsFlyerAnalyticsTrackerTests
  ✅ InitEventWhiteList_AllowListContainsDuplicates_InitDoesntContainsDuplicates
  ✅ InitEventWhiteList_UseAllowAndWhiteLists_InitSuccessFromAllowList
  ✅ InitEventWhiteList_UseAllowList_InitSuccess
  ✅ InitEventWhiteList_UseWhiteList_InitSuccess
  ✅ InitEventWhiteList_WhiteListContainsDuplicates_InitDoesntContainsDuplicates
AssertExceptionTests
  ✅ DoesNotThrow_NoExceptions_TestPassed
  ✅ DoesNotThrow_ThrowException_TestFailed
  ✅ DoesNotThrow_ThrowExceptionBeforeTest_TestPassed
  ✅ DoesNotThrow_UseUnityLogHandler_TestFailed
  ✅ Throws_NoExceptions_TestFailed
  ✅ Throws_ThrowException_TestPassed
  ✅ Throws_ThrowExceptionBeforeTest_TestFailed
  ✅ Throws_ThrowNonSuitException_TestFailed
  ✅ Throws_UseUnityLogHandler_TestFailed
BinaryQueueTests
  ✅ Add1000Events_ElementsCountEquals1000
  ✅ Add100Events_Dequeue50Events_Deserialize50EventsSuccess
  ✅ Add5Events_QueueBufferSizeExpanded
  ✅ Add5Events_ThenDequeue5Events_ThenAdd5Events_QueueRinged
  ✅ CheckDefaultDataSize
  ✅ DequeueNegativeNumber_ThrowsException
  ✅ DeserializeEmptyQueue_DoesNotThrow
  ✅ LastRingedElementCloseToFirstElement_AddBigEvent_QueueUnringed
  ✅ RingQueue_DequeueAllEvents_QueueIsUnringed
  ✅ RingQueue_DequeueEvents_DeserializeSuccess
BinaryQueueTests-AddNEvents_DequeueMEvents_ElementsCountEqualsDifference
  ✅ AddNEvents_DequeueMEvents_ElementsCountEqualsDifference(100,50)
  ✅ AddNEvents_DequeueMEvents_ElementsCountEqualsDifference(1,1)
  ✅ AddNEvents_DequeueMEvents_ElementsCountEqualsDifference(10,0)
BinaryQueueTests-DequeueMoreThanHave_ThrowsException
  ✅ DequeueMoreThanHave_ThrowsException(0)
  ✅ DequeueMoreThanHave_ThrowsException(15)
DictionaryExTests
  ✅ Merge_ToDictIsNull_ReturnFromDict
  ✅ MergeTwoDictionary_SuccessfullyMerged
  ✅ MergeTwoDictionary_ValuesCollide_FromOverridesTo
JsonTests
  ✅ DeserializeJsonWithAdditionalData_DataSavedToAdditionalDataProperty
  ✅ DeserializeWithDefaultValue_CorrectJson_DeserializedJsonReturned
  ✅ DeserializeWithDefaultValue_DefaultValueReturned
  ✅ DeserializeWithDefaultValue_ExplicitDefaultValueReturned
  ✅ DeserializeWithDefaultValue_WrongJson_DefaultValueReturned
SafeInvokeTests
  ✅ InvokeAction_ThrowException
  ✅ SafeInvokeAction_AllMethodsCalledInRightOrder
  ✅ SafeInvokeAction_DoesNotThrowException
  ✅ SafeInvokeAction_LogException
  ✅ SafeInvokeFewTimes_DoesntThrowExceptions
StatTests
  ✅ DeserializeFromVersion5_ParseCorrectly
  ✅ DeserializeFromVersion6_ParseCorrectly
  ✅ DeserializeFromVersion7_JsonNotNull
  ✅ DeserializeFromVersion7_ParseCorrectly
UnityHttpClientTests
  ✅ GetQueryTest
```