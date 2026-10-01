# **Annex A** 

# **Protocol Requirements List Table (PRL)**

In addition to the Conformance and Support columns discussed in Sections 3.10.1.1 and 3.10.1.3, the PRL table contains columns for the Need ID, Need, Req ID, Requirements, Conformance, Support, and Additional Specifications. These are described as follows:

* **Need ID.** The number assigned to the user need statement. The needs are defined within Section 2 and the PRL is based upon the user needs within that Section.
* **Need.** A short descriptive title identifying the user need.
* **Req ID.** The number assigned to the requirement statement. The requirements are defined within Section 3, and the PRL traces the relationship between needs and the corresponding requirements.
* **Requirement.** A short descriptive title identifying the requirement.
* **Conformance.** Identifies whether the requirement is mandatory or optional, and notes any conformance dependencies.
* **Support.** Used by specification developers to identify whether the requirement should be supported.
* **Additional Specifications.** Identifies other requirements to satisfy, including user-selectable range values. The "Additional Specifications" column may (and should) be used in procurement specifications to provide additional notes and requirements for the product to be procured or by an implementer to detail the implementation. In some cases, default text may already exist in this field and should be completed to fully specify the equipment. Additional text can be added to this field as needed to further detail a feature.


## Table 6. Protocol Requirements List
<div class="landscape-table" markdown="1">

| **Need ID**| **Need** | **Req ID** | **Requirement** | **Conformance** | **Support** | **Additional Specifications** |
| ------------- | ------------------- | ---------- | ----------- | --------------- | ----------- | -------------- |
| **2.5.1** | [**Architectural Needs**](concept-of-operations.md#251-architectural-needs) ||||||
| **2.5.1.1**| [**Compatibility with the WZDx Specification**](concept-of-operations.md#2511-architectural-need-compatibility-with-the-wzdx-specification) ||||||
||| **3.2** | [**Architectural Requirements**](system-requirements.md#32-architectural-requirements)||||
||| **3.2.1** | [**Compatibility with the WZDx Specification**](system-requirements.md#321-compatibility-with-the-wzdx-specification) | M| Yes||
||| **3.2.2** | [**GeoJSON Data Format**](system-requirements.md#322-geojson-data-format) | M| Yes||
||| **3.2.3** | [**GeoJSON Data Validation**](system-requirements.md#323-geojson-data-validation)| M| Yes||
||| **3.2.4** | [**Business Rules**](system-requirements.md#324-business-rules) | **M** | **Yes** ||
||| 3.2.4.1 | [Event Segments Follow Attribute Changes](system-requirements.md#3241-event-segments-follow-attribute-changes) | M| Yes||
||| 3.2.4.2 | [WorkZoneRoadEvent Lanes](system-requirements.md#3242-workzoneroadevent-lanes)| M| Yes||
||| 3.2.4.3 | [Lane Order](system-requirements.md#3243-lane-order)| M| Yes||
||| 3.2.4.4 | [Data Source ID Referential Integrity](system-requirements.md#3244-data-source-id-referential-integrity) | M| Yes||
||| 3.2.4.5 | [UTC Date-Time Format Specification](system-requirements.md#3245-utc-date-time-format-specification) | M| Yes||
||| 3.2.4.6 | [UUID Format Specification](system-requirements.md#3246-uuid-format-specification) | M| Yes||
||| **3.5.1** | [**Contents of FeedInfo**](system-requirements.md#351-contents-of-feedinfo)||||
||| 3.5.1 f)| [version](system-requirements.md#351f)| M| Yes||
||| **3.3** | [**Data Exchange Requirements**](system-requirements.md#33-data-exchange-requirements)||||
||| **3.3.1** | [**Exchange WorkZoneFeed Information**](system-requirements.md#331-exchange-workzonefeed-information)||||
||| 3.3.1.1 | [Send WorkZoneFeed Information Upon Request](system-requirements.md#3311-send-workzonefeed-upon-request) | M| Yes||
||| **3.3.2** | [**Exchange DeviceFeed Information**](system-requirements.md#332-exchange-devicefeed-information) ||||
||| 3.3.2.1 | [Send DeviceFeed Information Upon Request](system-requirements.md#3321-send-devicefeed-upon-request) | M| Yes||
||| **3.4** | [**WorkZoneFeed Requirements**](system-requirements.md#34-workzonefeed-requirements)||||
||| **3.4.1** | [**Contents of WorkZoneFeed**](system-requirements.md#341-contents-of-workzonefeed) ||||
||| 3.4.1 a)| [feed\_info](system-requirements.md#341a)| M| Yes||
||| 3.4.1 b)| [type](system-requirements.md#341b)| M| Yes||
||| 3.4.1 c)| [features](system-requirements.md#341c) | M| Yes||
||| 3.4.1 d)| [bbox](system-requirements.md#341d)| O| Yes / No ||
||| **3.5** | [**FeedInfo Requirements**](system-requirements.md#35-feedinfo-requirements) ||||
||| **3.5.1** | [**Contents of FeedInfo**](system-requirements.md#351-contents-of-feedinfo)||||
||| 3.5.1 a)| [publisher](system-requirements.md#351a) | M| Yes||
||| 3.5.1 b)| [contact\_name](system-requirements.md#351b)| O| Yes / No ||
||| 3.5.1 c)| [contact\_email](system-requirements.md#351c) | O| Yes / No ||
||| 3.5.1 d)| [update\_frequency](system-requirements.md#351d) | O| Yes / No ||
||| 3.5.1 e)| [update\_date](system-requirements.md#351e) | M| Yes||
||| 3.5.1 f)| [version](system-requirements.md#351f)| M| Yes||
||| 3.5.1 g)| [license](system-requirements.md#351g)| O| Yes / No ||
||| 3.5.1 h)| [data\_sources](system-requirements.md#351h)| M| Yes||
||| **3.5.2** | [**Contents of FeedDataSource**](system-requirements.md#352-contents-of-feeddatasource) ||||
||| 3.5.2 a)| [data\_source\_id](system-requirements.md#352a)| M| Yes||
||| 3.5.2 b)| [organization\_name](system-requirements.md#352b) | M| Yes||
||| 3.5.2 c)| [contact\_name](system-requirements.md#352c)| O| Yes / No ||
||| 3.5.2 d)| [contact\_email](system-requirements.md#352d) | O| Yes / No ||
||| 3.5.2 e)| [update\_frequency](system-requirements.md#352e) | M| Yes||
||| 3.5.2 f)| [update\_date](system-requirements.md#352f) | M| Yes||
||| **3.6** | [**RoadEventFeature Requirements**](system-requirements.md#36-roadeventfeature-requirements)||||
||| **3.6.1** | [**Contents of RoadEventFeature**](system-requirements.md#361-contents-of-roadeventfeature) ||||
||| 3.6.1 a)| [id](system-requirements.md#361a)| M| Yes||
||| 3.6.1 b)| [type](system-requirements.md#361b)| M| Yes||
||| 3.6.1 c)| [properties](system-requirements.md#361c)| M| Yes||
||| 3.6.1 d)| [geometry](system-requirements.md#361d) | M| Yes||
||| 3.6.1 e)| [bbox](system-requirements.md#361e)| O| Yes / No ||
||| **3.6.2** | [**Contents of WorkZoneRoadEvent**](system-requirements.md#362-contents-of-workzoneroadevent) ||||
||| 3.6.2 a)| [core\_details](system-requirements.md#362a)| M| Yes||
||| 3.6.2 b)| [beginning\_cross\_street](system-requirements.md#362b)| O| Yes / No ||
||| 3.6.2 c)| [ending\_cross\_street](system-requirements.md#362c)| O| Yes / No ||
||| 3.6.2 d)| [beginning\_reference\_post](system-requirements.md#362d) | O| Yes / No ||
||| 3.6.2 e)| [ending\_reference\_post](system-requirements.md#362e) | O| Yes / No ||
||| 3.6.2 f)| [reference\_post\_unit](system-requirements.md#362f)| RefPost:O | Yes / No ||
||| 3.6.2 g)| [is\_start\_position\_verified](system-requirements.md#362g) | M| Yes||
||| 3.6.2 h)| [is\_end\_position\_verified](system-requirements.md#362h)| M| Yes||
||| 3.6.2 i)| [start\_date](system-requirements.md#362i) | M| Yes||
||| 3.6.2 j)| [end\_date](system-requirements.md#362j) | M| Yes||
||| 3.6.2 k)| [is\_start\_date\_verified](system-requirements.md#362k) | M| Yes||
||| 3.6.2 l)| [is\_end\_date\_verified](system-requirements.md#362l) | M| Yes||
||| 3.6.2 m)| [work\_zone\_type](system-requirements.md#362m)| O| Yes / No ||
||| 3.6.2 n)| [vehicle\_impact](system-requirements.md#362n) | M| Yes||
||| 3.6.2 o)| [location\_method](system-requirements.md#362o)| M| Yes||
||| 3.6.2 p)| [worker\_presence](system-requirements.md#362p)| O| Yes / No ||
||| 3.6.2 q)| [reduced\_speed\_limit\_kph](system-requirements.md#362q) | O| Yes / No ||
||| 3.6.2 r)| [restrictions](system-requirements.md#362r) | O| Yes / No ||
||| 3.6.2 s)| [types\_of\_work](system-requirements.md#362s) | O| Yes / No ||
||| 3.6.2 t)| [lanes](system-requirements.md#362t) | O| Yes / No ||
||| 3.6.2 u)| [impacted\_cds\_curb\_zones](system-requirements.md#362u) | O| Yes / No ||
||| **3.6.3** | [**Contents of DetourRoadEvent**](system-requirements.md#363-contents-of-detourroadevent)||||
||| 3.6.3 a)| [core\_details](system-requirements.md#363a)| M| Yes||
||| 3.6.3 b)| [beginning\_cross\_street](system-requirements.md#363b)| O| Yes / No ||
||| 3.6.3 c)| [ending\_cross\_street](system-requirements.md#363c)| O| Yes / No ||
||| 3.6.3 d)| [beginning\_reference\_post](system-requirements.md#363d) | O| Yes / No ||
||| 3.6.3 e)| [ending\_reference\_post](system-requirements.md#363e) | O| Yes / No ||
||| 3.6.3 f)| [reference\_post\_unit](system-requirements.md#363f)| RefPost:O | Yes / No ||
||| 3.6.3 g)| [start\_date](system-requirements.md#363g) | M| Yes||
||| 3.6.3 h)| [end\_date](system-requirements.md#363h) | M| Yes||
||| 3.6.3 i)| [is\_start\_date\_verified](system-requirements.md#363i) | M| Yes||
||| 3.6.3 j)| [is\_end\_date\_verified](system-requirements.md#363j) | M| Yes||
||| **3.6.4** | [**Contents of RoadEventCoreDetails**](system-requirements.md#364-contents-of-roadeventcoredetails) ||||
||| 3.6.4 a)| [data\_source\_id](system-requirements.md#364a)| M| Yes||
||| 3.6.4 b)| [event\_type](system-requirements.md#364b) | M| Yes||
||| 3.6.4 c)| [related\_road\_events](system-requirements.md#364c)| O| Yes / No ||
||| 3.6.4 e)| [road\_names](system-requirements.md#364e) | M| Yes||
||| 3.6.4 f)| [direction](system-requirements.md#364f) | M| Yes||
||| 3.6.4 g)| [name](system-requirements.md#364g)| O| Yes / No ||
||| 3.6.4 h)| [description](system-requirements.md#364h) | O| Yes / No ||
||| 3.6.4 i)| [creation\_date](system-requirements.md#364i) | O| Yes / No ||
||| 3.6.4 j)| [update\_date](system-requirements.md#364j) | O| Yes / No ||
||| **3.6.5** | [**Enumeration of LocationMethod**](system-requirements.md#365-enumeration-of-locationmethod) | **NA** |||
||| **3.6.6** | [**Contents of RelatedRoadEvent**](system-requirements.md#366-contents-of-relatedroadevent) ||||
||| 3.6.6 a)| [type](system-requirements.md#366a)| M| Yes||
||| 3.6.6 b)| [id](system-requirements.md#366b)| M| Yes||
||| **3.6.7** | [**Contents of TypeOfWork**](system-requirements.md#367-contents-of-typeofwork) ||||
||| 3.6.7 a)| [type\_name](system-requirements.md#367a)| M| Yes||
||| 3.6.7 b)| [is\_architectural\_change](system-requirements.md#367b) | O| Yes / No ||
||| **3.6.8** | [**Contents of Lane**](system-requirements.md#368-contents-of-lane)||||
||| 3.6.8 a)| [order](system-requirements.md#368a) | M| Yes||
||| 3.6.8 b)| [status](system-requirements.md#368b) | M| Yes||
||| 3.6.8 c)| [type](system-requirements.md#368c)| M| Yes||
||| 3.6.8 d)| [restrictions](system-requirements.md#368d) | O| Yes / No ||
||| **3.6.9** | [**Contents of Restriction**](system-requirements.md#369-contents-of-restriction)||||
||| 3.6.9 a)| [type](system-requirements.md#369a)| M| Yes||
||| 3.6.9 b)| [value](system-requirements.md#369b) | O| Yes / No ||
||| 3.6.9 c)| [unit](system-requirements.md#369c)| ResValue:O| Yes / No ||
||| **3.6.10** | [**Contents of CdsCurbZonesReference**](system-requirements.md#3610-contents-of-cdscurbzonesreference) ||||
||| 3.6.10 a) | [cds\_curb\_zone\_ids](system-requirements.md#3610a)| M| Yes||
||| 3.6.10 b) | [cds\_curbs\_api\_url](system-requirements.md#3610b)| M| Yes||
||| **3.6.11** | [**Contents of WorkerPresence**](system-requirements.md#3611-contents-of-workerpresence) ||||
||| 3.6.11 a) | [are\_workers\_present](system-requirements.md#3611a) | M| Yes||
||| 3.6.11 b) | [method](system-requirements.md#3611b)| O| Yes / No ||
||| 3.6.11 c) | [worker\_presence\_last\_confirmed\_date](system-requirements.md#3611c) | O| Yes / No ||
||| 3.6.11 d) | [confidence](system-requirements.md#3611d) | O| Yes / No ||
||| **3.6.12** | [**Enumeration of EventType**](system-requirements.md#3612-enumeration-of-eventtype)| **NA** |||
||| **3.6.13** | [**Enumeration of WorkZoneType**](system-requirements.md#3613-enumeration-of-workzonetype) | **NA** |||
||| **3.6.14** | [**Enumeration of VehicleImpact**](system-requirements.md#3614-enumeration-of-vehicleimpact)| **NA** |||
||| **3.6.15** | [**Enumeration of RestrictionType**](system-requirements.md#3615-enumeration-of-restrictiontype) | **NA** |||
||| **3.6.16** | [**Enumeration of WorkTypeName**](system-requirements.md#3616-enumeration-of-worktypename) | **NA** |||
||| **3.6.17** | [**Enumeration of LaneStatus**](system-requirements.md#3617-enumeration-of-lanestatus)| **NA** |||
||| **3.6.18** | [**Enumeration of LaneType**](system-requirements.md#3618-enumeration-of-lanetype) | **NA** |||
||| **3.6.19** | [**Enumeration of UnitOfMeasurement**](system-requirements.md#3619-enumeration-of-unitofmeasurement) | **NA** |||
||| **3.6.20** | [**Enumeration of WorkerPresenceMethod**](system-requirements.md#3620-enumeration-of-workerpresencemethod)| **NA** |||
||| **3.6.21** | [**Enumeration of WorkerPresenceDefinition**](system-requirements.md#3621-enumeration-of-workerpresencedefinition) | **NA** |||
||| **3.6.22** | [**Enumeration of WorkerPresenceConfidence**](system-requirements.md#3622-enumeration-of-workerpresenceconfidence) | **NA** |||
||| **3.6.23** | [**Enumeration of RelatedRoadEventType**](system-requirements.md#3623-enumeration-of-relatedroadeventtype)| **NA** |||
||| **3.7** | [**DeviceFeed Requirements**](system-requirements.md#37-devicefeed-requirements) ||||
||| **3.7.1** | [**Contents of DeviceFeed**](system-requirements.md#371-contents-of-devicefeed)||||
||| 3.7.1 a)| [feed\_info](system-requirements.md#371a)| M| Yes||
||| 3.7.1 b)| [type](system-requirements.md#371b)| M| Yes||
||| 3.7.1 c)| [features](system-requirements.md#371c) | M| Yes||
||| 3.7.1 d)| [bbox](system-requirements.md#371d)| O| Yes / No ||
||| **3.7.2** | [**Contents of FieldDeviceFeature**](system-requirements.md#372-contents-of-fielddevicefeature)||||
||| 3.7.2 a)| [id](system-requirements.md#372a)| M| Yes||
||| 3.7.2 b)| [type](system-requirements.md#372b)| M| Yes||
||| 3.7.2 c)| [properties](system-requirements.md#372c)| M| Yes||
||| 3.7.2 d)| [geometry](system-requirements.md#372d) | M| Yes||
||| 3.7.2 e)| [bbox](system-requirements.md#372e)| O| Yes / No ||
||| **3.7.3** | [**Contents of FieldDeviceCoreDetails**](system-requirements.md#373-contents-of-fielddevicecoredetails) ||||
||| 3.7.3 a)| [device\_type](system-requirements.md#373a) | M| Yes||
||| 3.7.3 b)| [data\_source\_id](system-requirements.md#373b)| M| Yes||
||| 3.7.3 c)| [device\_status](system-requirements.md#373c) | M| Yes||
||| 3.7.3 d)| [update\_date](system-requirements.md#373d) | M| Yes||
||| 3.7.3 e)| [has\_automatic\_location](system-requirements.md#373e)| M| Yes||
||| 3.7.3 f)| [road\_direction](system-requirements.md#373f) | O| Yes / No ||
||| 3.7.3 g)| [road\_names](system-requirements.md#373g) | O| Yes / No ||
||| 3.7.3 h)| [name](system-requirements.md#373h)| O| Yes / No ||
||| 3.7.3 i)| [description](system-requirements.md#373i) | O| Yes / No ||
||| 3.7.3 j)| [status\_messages](system-requirements.md#373j)| O| Yes / No ||
||| 3.7.3 k)| [is\_moving](system-requirements.md#373k)| O| Yes / No ||
||| 3.7.3 l)| [road\_event\_ids](system-requirements.md#373l)| O| Yes / No ||
||| 3.7.3 n)| [reference\_post](system-requirements.md#373n) | O| Yes / No ||
||| 3.7.3 o)| [reference\_post\_unit](system-requirements.md#373o)| RefPost:O | Yes / No ||
||| 3.7.3 p)| [make](system-requirements.md#373p)| O| Yes / No ||
||| 3.7.3 q)| [model](system-requirements.md#373q) | O| Yes / No ||
||| 3.7.3 r)| [serial\_number](system-requirements.md#373r) | O| Yes / No ||
||| 3.7.3 s)| [firmware\_version](system-requirements.md#373s) | O| Yes / No ||
||| 3.7.3 t)| [velocity\_kph](system-requirements.md#373t)| O| Yes / No ||
||| 3.7.3 u)| [is\_in\_transport\_position](system-requirements.md#373u)| O| Yes / No ||
||| **3.7.4** | [**Contents of ArrowBoard**](system-requirements.md#374-contents-of-arrowboard)||||
||| 3.7.4 a)| [core\_details](system-requirements.md#374a)| M| Yes||
||| 3.7.4 b)| [pattern](system-requirements.md#374b)| M| Yes||
||| **3.7.5** | [**Contents of Camera**](system-requirements.md#375-contents-of-camera) ||||
||| 3.7.5 a)| [core\_details](system-requirements.md#375a)| M| Yes||
||| 3.7.5 b)| [image\_url](system-requirements.md#375b)| O| Yes / No ||
||| 3.7.5 c)| [is\_image\_url\_public](system-requirements.md#375c) | O| Yes / No ||
||| 3.7.5 d)| [image\_timestamp](system-requirements.md#375d)| ImgURL:O | Yes / No ||
||| 3.7.5 e)| [video\_url](system-requirements.md#375e)| O| Yes / No ||
||| 3.7.5 f)| [is\_video\_url\_public](system-requirements.md#375f) | O| Yes / No ||
||| 3.7.5 g)| [video\_update\_frequency](system-requirements.md#375g)| VideoUrl:O| Yes / No ||
||| **3.7.6** | [**Contents of DynamicMessageSign**](system-requirements.md#376-contents-of-dynamicmessagesign)||||
||| 3.7.6 a)| [core\_details](system-requirements.md#376a)| M| Yes||
||| 3.7.6 b)| [message\_multi\_string](system-requirements.md#376b) | M| Yes||
||| **3.7.7** | [**Contents of FlashingBeacon**](system-requirements.md#377-contents-of-flashingbeacon) ||||
||| 3.7.7 a)| [core\_details](system-requirements.md#377a)| M| Yes||
||| 3.7.7 b)| [function](system-requirements.md#377b) | M| Yes||
||| 3.7.7 c)| [is\_flashing](system-requirements.md#377c) | O| Yes / No ||
||| 3.7.7 d)| [sign\_text](system-requirements.md#377d)| O| Yes / No ||
||| **3.7.8** | [**Contents of HybridSign**](system-requirements.md#378-contents-of-hybridsign)||||
||| 3.7.8 a)| [core\_details](system-requirements.md#378a)| M| Yes||
||| 3.7.8 b)| [dynamic\_message\_function](system-requirements.md#378b) | M| Yes||
||| 3.7.8 c)| [dynamic\_message\_text](system-requirements.md#378c) | O| Yes / No ||
||| 3.7.8 d)| [static\_sign\_text](system-requirements.md#378d) | O| Yes / No ||
||| **3.7.9** | [**Contents of LocationMarker**](system-requirements.md#379-contents-of-locationmarker) ||||
||| 3.7.9 a)| [core\_details](system-requirements.md#379a)| M| Yes||
||| 3.7.9 b)| [marked\_locations](system-requirements.md#379b) | M| Yes||
||| **3.7.10** | [**Contents of MarkedLocation**](system-requirements.md#3710-contents-of-markedlocation) ||||
||| 3.7.10 a) | [type](system-requirements.md#3710a) | M| Yes||
||| 3.7.10 b) | [road\_event\_id](system-requirements.md#3710b)| O| Yes / No ||
||| **3.7.11** | [**Contents of TrafficSensor**](system-requirements.md#3711-contents-of-trafficsensor)||||
||| 3.7.11 a) | [core\_details](system-requirements.md#3711a) | M| Yes||
||| 3.7.11 b) | [collection\_interval\_start\_date](system-requirements.md#3711b) | M| Yes||
||| 3.7.11 c) | [collection\_interval\_end\_date](system-requirements.md#3711c) | M| Yes||
||| 3.7.11 d) | [average\_speed\_kph](system-requirements.md#3711d) | O| Yes / No ||
||| 3.7.11 e) | [volume\_vph](system-requirements.md#3711e) | O| Yes / No ||
||| 3.7.11 f) | [occupancy\_percent](system-requirements.md#3711f)| O| Yes / No ||
||| 3.7.11 g) | [lane\_data](system-requirements.md#3711g) | O| Yes / No ||
||| **3.7.12** | [**Contents of TrafficSensorLaneData**](system-requirements.md#3712-contents-of-trafficsensorlanedata)||||
||| 3.7.12 a) | [lane\_order](system-requirements.md#3712a) | M| Yes||
||| 3.7.12 b) | [road\_event\_id](system-requirements.md#3712b)| O| Yes / No ||
||| 3.7.12 c) | [average\_speed\_kph](system-requirements.md#3712c) | O| Yes / No ||
||| 3.7.12 d) | [volume\_vph](system-requirements.md#3712d) | O| Yes / No ||
||| 3.7.12 e) | [occupancy\_percent](system-requirements.md#3712e)| O| Yes / No ||
||| **3.7.13** | [**Contents of TrafficSignal**](system-requirements.md#3713-contents-of-trafficsignal)||||
||| 3.7.13 a) | [core\_details](system-requirements.md#3713a) | M| Yes||
||| 3.7.13 b) | [mode](system-requirements.md#3713b) | M| Yes||
||| **3.7.16** | [**Enumeration of ArrowBoardPattern**](system-requirements.md#3716-enumeration-of-arrowboardpattern) | **NA** |||
||| **3.7.17** | [**Enumeration of FieldDeviceType**](system-requirements.md#3717-enumeration-of-fielddevicetype)| **NA** |||
||| **3.7.18** | [**Enumeration of FieldDeviceStatus**](system-requirements.md#3718-enumeration-of-fielddevicestatus) | **NA** |||
||| **3.7.19** | [**Enumeration of FlashingBeaconFunction**](system-requirements.md#3719-enumeration-of-flashingbeaconfunction) | **NA** |||
||| **3.7.20** | [**Enumeration of HybridSignDynamicMessageFunction**](system-requirements.md#3720-enumeration-of-hybridsigndynamicmessagefunction)| **NA** |||
||| **3.7.21** | [**Enumeration of MarkedLocationType**](system-requirements.md#3721-enumeration-of-markedlocationtype)| **NA** |||
||| **3.7.22** | [**Enumeration of TrafficSignalMode**](system-requirements.md#3722-enumeration-of-trafficsignalmode) | **NA** |||
||| **3.8** | [**Direction Requirements**](system-requirements.md#38-direction-requirements)||||
||| **3.8.1** | [**Enumeration of Direction**](system-requirements.md#381-enumeration-of-direction) | **NA** |||
||| **3.9** | [**BoundingBox Requirements**](system-requirements.md#39-boundingbox-requirements) ||||
||| **3.9.1** | [**Contents of BoundingBox**](system-requirements.md#391-contents-of-boundingbox) | **O** |||
| **2.5.1.2**| [**GeoJSON Data Exchange**](concept-of-operations.md#2512-architectural-need-geojson-data-exchange-constraint) ||||||
| **2.5.1.2.1** | [**Poll for Data**](concept-of-operations.md#25121-geojson-data-exchange-poll-for-data-constraint)||||||
||| 3.3.1.1 | [Send WorkZoneFeed Information Upon Request](system-requirements.md#3311-send-workzonefeed-upon-request) | M| Yes||
||| 3.3.2.1 | [Send DeviceFeed Information Upon Request](system-requirements.md#3321-send-devicefeed-upon-request)| M| Yes||
| **2.5.1.3**| [**GeoJSON Data Format**](concept-of-operations.md#2513-architectural-need-geojson-data-format-constraint) ||||||
||| **3.2.2** | [**GeoJSON Data Format**](system-requirements.md#322-geojson-data-format)| M| Yes||
| **2.5.1.4**| [**GeoJSON Data Validation**](concept-of-operations.md#2514-architectural-need-geojson-data-validation-constraint) ||||||
||| **3.2.3** | [**GeoJSON Data Validation**](system-requirements.md#323-geojson-data-validation)| M| Yes||
| **2.5.1.5**| [**Frequency of Updates**](concept-of-operations.md#2515-architectural-need-frequency-of-data-updates)||||||
||| **3.5.2** | [**Contents of FeedDataSource**](system-requirements.md#352-contents-of-feeddatasource) | M| Yes||
||| 3.5.2 e)| [update\_frequency](system-requirements.md#352e) | M| Yes||
||| 3.5.2 f)| [update\_date](system-requirements.md#352f) | M| Yes||
| **2.5.1.6**| [**UTC Date-Time Format Specification**](concept-of-operations.md#2516-architectural-need-utc-date-time-format-specification-constraint) ||||||
||| 3.2.4.5 | [UTC Date-Time Format Specification](system-requirements.md#3245-utc-date-time-format-specification) | M| Yes||
| **2.5.2** | [**Data Exchange Needs**](concept-of-operations.md#252-data-exchange-needs) ||||||
| **2.5.2.1**| [**Zone Metadata**](concept-of-operations.md#2521-zone-metadata)||||||
| 2.5.2.1.1 | [Zone Data Standard Version](concept-of-operations.md#25211-zone-metadata--zone-data-standard-version) ||||||
||| **3.5.1** | [**Contents of FeedInfo**](system-requirements.md#351-contents-of-feedinfo)||||
||| 3.5.1 f)| [version](system-requirements.md#351f)| M| Yes||
| 2.5.2.1.2 | [Zone Identifier](concept-of-operations.md#25212-zone-metadata--zone-identifier) ||||||
| 2.5.2.1.2.1| [Support Zone Identifier for Zones](concept-of-operations.md#252121-support-zone-identifier-for-zones) ||||||
||| 3.2.4.4 | [Data Source ID Referential Integrity](system-requirements.md#3244-data-source-id-referential-integrity) | M| Yes||
||| 3.2.4.6 | [UUID Format Specification](system-requirements.md#3246-uuid-format-specification) | M| Yes||
||| **3.6.1** | [**Contents of RoadEventFeature**](system-requirements.md#361-contents-of-roadeventfeature) ||||
||| 3.6.1 a)| [id](system-requirements.md#361a)| M| Yes||
| 2.5.2.1.2.2| [Support Unique Zone Identifiers](concept-of-operations.md#252122-support-unique-zone-identifiers)||||||
||| 3.2.4.6 | [UUID Format Specification](system-requirements.md#3246-uuid-format-specification)| M| Yes||
||| **3.6.1** | [**Contents of RoadEventFeature**](system-requirements.md#361-contents-of-roadeventfeature) ||||
||| 3.6.1 a)| [id](system-requirements.md#361a)| M| Yes||
| 2.5.2.1.2.3| [Support Unique Zone Group Identifiers](concept-of-operations.md#252123-support-unique-zone-group-identifiers)||||||
||| **3.6.4** | [**Contents of RoadEventCoreDetails**](system-requirements.md#364-contents-of-roadeventcoredetails) ||||
||| 3.6.4 d)| [project\_id](system-requirements.md#364d) | O| Yes / No ||
||| **3.7.3** | [**Contents of FieldDeviceCoreDetails**](system-requirements.md#373-contents-of-fielddevicecoredetails)||||
||| 3.7.3 m)| [project\_id](system-requirements.md#373m) | O| Yes / No ||
| 2.5.2.1.2.4| [Zone Identifier for VRUs, Devices, Work Zone Vehicles, Lanes, Speed Limit Zones](concept-of-operations.md#252124-support-zone-identifiers-for-vrus-devices-work-zone-vehicles-lanes-and-speed-limit-zones)||||||
||| 3.2.4.6 | [UUID Format Specification](system-requirements.md#3246-uuid-format-specification) | M| Yes||
||| **3.6.1** | [**Contents of RoadEventFeature**](system-requirements.md#361-contents-of-roadeventfeature) ||||
||| 3.6.1 a)| [id](system-requirements.md#361a)| M| Yes||
| 2.5.2.1.3 | [Zone Activity Type](concept-of-operations.md#25213-zone-metadata--zone-activity-type) ||||||
||| **3.6.2** | [**Contents of WorkZoneRoadEvent**](system-requirements.md#362-contents-of-workzoneroadevent) ||||
||| 3.6.2 s)| [types\_of\_work](system-requirements.md#362s) | O| Yes / No ||
| 2.5.2.1.4 | [Zone Data Timestamp](concept-of-operations.md#25214-zone-metadata--zone-data-timestamp) ||||||
||| **3.6.4** | [**Contents of RoadEventCoreDetails**](system-requirements.md#364-contents-of-roadeventcoredetails) ||||
||| 3.6.4 i)| [creation\_date](system-requirements.md#364i) | O| Yes / No ||
||| 3.6.4 j)| [update\_date](system-requirements.md#364j) | O| Yes / No ||
| 2.5.2.1.5 | [Zone Data Source](concept-of-operations.md#25215-zone-metadata--zone-data-source) ||||||
||| 3.2.4.4 | [Data Source ID Referential Integrity](system-requirements.md#3244-data-source-id-referential-integrity) | M| Yes||
||| **3.5.1** | [**Contents of FeedInfo**](system-requirements.md#351-contents-of-feedinfo)||||
||| 3.5.1 h)| [data\_sources](system-requirements.md#351h)| M| Yes||
||| **3.6.4** | [**Contents of RoadEventCoreDetails**](system-requirements.md#364-contents-of-roadeventcoredetails) ||||
||| 3.6.4 a)| [data\_source\_id](system-requirements.md#364a)| M| Yes||
| **2.5.2.2**| [**Zone Location**](concept-of-operations.md#2522-zone-location)||||||
| 2.5.2.2.1 | [Zone Geometry](concept-of-operations.md#25221-zone-location--geometry) ||||||
||| 3.2.4.1 | [Event Segments Follow Attribute Changes](system-requirements.md#3241-event-segments-follow-attribute-changes) | M| Yes||
||| **3.6.1** | [**Contents of RoadEventFeature**](system-requirements.md#361-contents-of-roadeventfeature) ||||
||| 3.6.1 d)| [geometry](system-requirements.md#361d) | M| Yes||
||| **3.6.2** | [**Contents of WorkZoneRoadEvent**](system-requirements.md#362-contents-of-workzoneroadevent) ||||
||| 3.6.2 g)| [is\_start\_position\_verified](system-requirements.md#362g) | M| Yes||
||| 3.6.2 h)| [is\_end\_position\_verified](system-requirements.md#362h)| M| Yes||
| **2.5.2.3**| [**Zone Schedule**](concept-of-operations.md#2523-zone-schedule)||||||
| 2.5.2.3.1 | [Date Times](concept-of-operations.md#25231-zone-schedule--date-times) ||||||
||| **3.6.2** | [**Contents of WorkZoneRoadEvent**](system-requirements.md#362-contents-of-workzoneroadevent) ||||
||| 3.6.2 i)| [start\_date](system-requirements.md#362i) | M| Yes||
||| 3.6.2 j)| [end\_date](system-requirements.md#362j) | M| Yes||
||| 3.6.2 k)| [is\_start\_date\_verified](system-requirements.md#362k) | M| Yes||
||| 3.6.2 l)| [is\_end\_date\_verified](system-requirements.md#362l) | M| Yes||
| **2.5.2.4**| [**Zone Segmentation**](concept-of-operations.md#2524-zone-segmentation) ||||||
| 2.5.2.4.1 | [Geometry](concept-of-operations.md#25241-zone-segmentation--geometry)||||||
||| **3.6.4** | [**Contents of RoadEventCoreDetails**](system-requirements.md#364-contents-of-roadeventcoredetails) ||||
||| 3.6.4 d)| [project\_id](system-requirements.md#364d) | O| Yes / No ||
||| **3.7.3** | [**Contents of FieldDeviceCoreDetails**](system-requirements.md#373-contents-of-fielddevicecoredetails)||||
||| 3.7.3 m)| [project\_id](system-requirements.md#373m) | O| Yes / No ||
| 2.5.2.4.2 | [Date Times](concept-of-operations.md#25242-zone-segmentation--date-times) ||||||
||| **3.6.4** | [**Contents of RoadEventCoreDetails**](system-requirements.md#364-contents-of-roadeventcoredetails) ||||
||| 3.6.4 d)| [project\_id](system-requirements.md#364d) | O| Yes / No ||
||| **3.7.3** | [**Contents of FieldDeviceCoreDetails**](system-requirements.md#373-contents-of-fielddevicecoredetails)||||
||| 3.7.3 m)| [project\_id](system-requirements.md#373m) | O| Yes / No ||
| **2.5.2.5**| [**Zone Status**](concept-of-operations.md#2525-zone-status) ||||||
| 2.5.2.5.1 | [Is Active](concept-of-operations.md#25251-zone-status--is-active) ||||||
||| **3.6.2** | [**Contents of WorkZoneRoadEvent**](system-requirements.md#362-contents-of-workzoneroadevent) ||||
||| 3.6.2 k)| [is\_start\_date\_verified](system-requirements.md#362k) | M| Yes||
||| 3.6.2 l)| [is\_end\_date\_verified](system-requirements.md#362l) | M| Yes||
| 2.5.2.5.2 | [Length](concept-of-operations.md#25252-zone-status--length) ||||||
||| **3.6.1** | [**Contents of RoadEventFeature**](system-requirements.md#361-contents-of-roadeventfeature) ||||
||| 3.6.1 d)| [geometry](system-requirements.md#361d) | M| Yes| Calculated using coordinate information contained in the linestring |
| 2.5.2.5.3 | [Number of Lanes Open](concept-of-operations.md#25253-zone-status--number-of-lanes-open)||||||
||| **3.6.8** | [**Contents of Lane**](system-requirements.md#368-contents-of-lane)||||
||| 3.6.8 b)| [status](system-requirements.md#368b) | M| Yes||
||| **3.6.17** | [**Enumeration of LaneStatus**](system-requirements.md#3617-enumeration-of-lanestatus)||||
| 2.5.2.5.4 | [Ad-hoc (Unscheduled/Unplanned)](concept-of-operations.md#25254-zone-status--ad-hoc-unscheduledunplanned) ||||||
||| **3.6.14** | [**Enumeration of VehicleImpact**](system-requirements.md#3614-enumeration-of-vehicleimpact)||||
||| **3.6.15** | [**Enumeration of RestrictionType**](system-requirements.md#3615-enumeration-of-restrictiontype) ||||
| 2.5.2.5.5 | [Is Rolling/Moving](concept-of-operations.md#25255-zone-status--is-rollingmoving)||||||
||| **3.6.2** | [**Contents of WorkZoneRoadEvent**](system-requirements.md#362-contents-of-workzoneroadevent) ||||
||| 3.6.2 m)| [work\_zone\_type](system-requirements.md#362m)| O| Yes / No ||
||| **3.6.8** | [**Contents of Lane**](system-requirements.md#368-contents-of-lane)||||
||| 3.6.8 a)| [order](system-requirements.md#368a) | M| Yes||
||| **3.6.13** | [**Enumeration of WorkZoneType**](system-requirements.md#3613-enumeration-of-workzonetype) ||||
| **2.5.2.6**| [**Zone Lanes**](concept-of-operations.md#2526-zone-lanes)||||||
| 2.5.2.6.1 | [Numbering and Identification](concept-of-operations.md#25261-zone-lanes--numbering-and-identification)||||||
||| 3.2.4.2 | [WorkZoneRoadEvent Lanes](system-requirements.md#3242-workzoneroadevent-lanes)| M| Yes||
| 2.5.2.6.1.1| [Nationally Consistent Method of Lane Numbering](concept-of-operations.md#252611-lane-information) ||||||
||| 3.2.4.3 | [Lane Order](system-requirements.md#3243-lane-order) | M| Yes||
||| **3.6.2** | [**Contents of WorkZoneRoadEvent**](system-requirements.md#362-contents-of-workzoneroadevent) ||||
||| 3.6.2 t)| [lanes](system-requirements.md#362t) | O| Yes / No ||
||| **3.6.8** | [**Contents of Lane**](system-requirements.md#368-contents-of-lane)||||
||| 3.6.8 a)| [order](system-requirements.md#368a) | M| Yes||
| 2.5.2.6.1.2| [Lane Numbering is Left-to-Right or Right-to-Left](concept-of-operations.md#252612-lane-numbering-is-left-to-right-or-right-to-left)||||||
||| **3.6.2** | [**Contents of WorkZoneRoadEvent**](system-requirements.md#362-contents-of-workzoneroadevent) ||||
||| 3.6.2 t)| [lanes](system-requirements.md#362t) | O| Yes / No ||
||| **3.6.8** | [**Contents of Lane**](system-requirements.md#368-contents-of-lane)||||
||| 3.6.8 a)| [order](system-requirements.md#368a) | M| Yes||
| 2.5.2.6.2 | [Lane Type](concept-of-operations.md#25262-zone-lanes--lane-type) ||||||
||| **3.6.2** | [**Contents of WorkZoneRoadEvent**](system-requirements.md#362-contents-of-workzoneroadevent) ||||
||| 3.6.2 t)| [lanes](system-requirements.md#362t) | O| Yes / No ||
||| **3.6.8** | [**Contents of Lane**](system-requirements.md#368-contents-of-lane)||||
||| 3.6.8 a)| [order](system-requirements.md#368a) | M| Yes||
||| 3.6.8 c)| [type](system-requirements.md#368c)| M| Yes||
||| **3.6.17** | [**Enumeration of LaneStatus**](system-requirements.md#3617-enumeration-of-lanestatus)||||
||| **3.6.18** | [**Enumeration of LaneType**](system-requirements.md#3618-enumeration-of-lanetype) ||||
| 2.5.2.6.2.1| [Lane is Drivable](concept-of-operations.md#252621-zone-lanes--lane-is-drivable) ||||||
||| **3.6.2** | [**Contents of WorkZoneRoadEvent**](system-requirements.md#362-contents-of-workzoneroadevent) ||||
||| 3.6.2 t)| [lanes](system-requirements.md#362t) | O| Yes / No ||
||| **3.6.8** | [**Contents of Lane**](system-requirements.md#368-contents-of-lane)||||
||| 3.6.8 a)| [order](system-requirements.md#368a) | M| Yes||
||| 3.6.8 c)| [type](system-requirements.md#368c)| M| Yes||
||| **3.6.17** | [**Enumeration of LaneStatus**](system-requirements.md#3617-enumeration-of-lanestatus)||||
||| **3.6.18** | [**Enumeration of LaneType**](system-requirements.md#3618-enumeration-of-lanetype) ||||
| 2.5.2.6.2.2| [Special Use Lane](concept-of-operations.md#252622-zone-lanes--special-use) ||||||
||| **3.6.2** | [**Contents of WorkZoneRoadEvent**](system-requirements.md#362-contents-of-workzoneroadevent) ||||
||| 3.6.2 t)| [lanes](system-requirements.md#362t) | O| Yes / No ||
||| **3.6.8** | [**Contents of Lane**](system-requirements.md#368-contents-of-lane)||||
||| 3.6.8 a)| [order](system-requirements.md#368a) | M| Yes||
||| 3.6.8 c)| [type](system-requirements.md#368c)| M| Yes||
||| **3.6.17** | [**Enumeration of LaneStatus**](system-requirements.md#3617-enumeration-of-lanestatus)||||
||| **3.6.18** | [**Enumeration of LaneType**](system-requirements.md#3618-enumeration-of-lanetype) ||||
| 2.5.2.6.2.3| [Reversible Lane](concept-of-operations.md#252623-zone-lanes--reversible-lane) ||||||
||| **3.6.2** | [**Contents of WorkZoneRoadEvent**](system-requirements.md#362-contents-of-workzoneroadevent) ||||
||| 3.6.2 t)| [lanes](system-requirements.md#362t) | O| Yes / No ||
||| **3.6.8** | [**Contents of Lane**](system-requirements.md#368-contents-of-lane)||||
||| 3.6.8 a)| [order](system-requirements.md#368a) | M| Yes||
||| 3.6.8 c)| [type](system-requirements.md#368c)| M| Yes||
||| **3.6.17** | [**Enumeration of LaneStatus**](system-requirements.md#3617-enumeration-of-lanestatus)||||
||| **3.6.18** | [**Enumeration of LaneType**](system-requirements.md#3618-enumeration-of-lanetype) ||||
| 2.5.2.6.3 | [CVE Roadside Safety Applications](concept-of-operations.md#25263-zone-lanes--connected-vehicle-environment-roadside-safety-applications) ||||||
||| **3.6.1** | [**Contents of RoadEventFeature**](system-requirements.md#361-contents-of-roadeventfeature) ||||
||| 3.6.1 d)| [geometry](system-requirements.md#361d) | M| Yes||
||| **3.7.14** | [**Contents of RoadsideUnit**](system-requirements.md#3714-contents-of-roadsideunit)||||
||| 3.7.14 b) | [message\_types](system-requirements.md#3714b) | O| Yes / No ||
| 2.5.2.6.4 | [Lane Tapers](concept-of-operations.md#25264-zone-lanes--lane-tapers)||||||
||| 3.2.4.1 | [Event Segments Follow Lane Geometry Changes](system-requirements.md#3241-event-segments-follow-attribute-changes)| M| Yes||
||| **3.6.2** | [**Contents of WorkZoneRoadEvent**](system-requirements.md#362-contents-of-workzoneroadevent) ||||
||| 3.6.2 n)| [vehicle\_impact](system-requirements.md#362n) | M| Yes||
||| **3.6.17** | [**Enumeration of LaneStatus**](system-requirements.md#3617-enumeration-of-lanestatus)||||
| 2.5.2.6.5 | [Lane Closure Status](concept-of-operations.md#25265-zone-lanes--lane-closure-status) ||||||
||| **3.6.2** | [**Contents of WorkZoneRoadEvent**](system-requirements.md#362-contents-of-workzoneroadevent) ||||
||| 3.6.2 t)| [lanes](system-requirements.md#362t) | O| Yes / No ||
||| **3.6.8** | [**Contents of Lane**](system-requirements.md#368-contents-of-lane)||||
||| 3.6.8 a)| [order](system-requirements.md#368a) | M| Yes||
||| 3.6.8 b)| [status](system-requirements.md#368b) | M| Yes||
||| **3.6.17** | [**Enumeration of LaneStatus**](system-requirements.md#3617-enumeration-of-lanestatus)||||
| **2.5.2.7**| [**Zone Speed Limit**](concept-of-operations.md#2527-zone-speed-limit)||||||
| 2.5.2.7.1 | [Position/Geometry](concept-of-operations.md#25271-zone-speed-limit--positionsgeometry)||||||
||| **3.6.1** | [**Contents of RoadEventFeature**](system-requirements.md#361-contents-of-roadeventfeature) ||||
||| 3.6.1 d)| [geometry](system-requirements.md#361d) | M| Yes||
| 2.5.2.7.2 | [Speed Limit Change](concept-of-operations.md#25272-zone-speed-limit--speed-limit-change) ||||||
||| **3.6.2** | [**Contents of WorkZoneRoadEvent**](system-requirements.md#362-contents-of-workzoneroadevent) ||||
||| 3.6.2 q)| [reduced\_speed\_limit\_kph](system-requirements.md#362q) | O| Yes / No ||
| **2.5.2.8**| [**Zone Traffic Data**](concept-of-operations.md#2528-zone-traffic-data) ||||||
| 2.5.2.8.1 | [Speed, Volume, and Occupancy](concept-of-operations.md#25281-zone-traffic--speed-volume-and-occupancy)||||||
||| **3.7.11** | [**Contents of Traffic Sensor**](system-requirements.md#3711-contents-of-trafficsensor) ||||
||| 3.7.11 d) | [average\_speed\_kph](system-requirements.md#3711d) | O| Yes / No ||
||| 3.7.11 e) | [volume\_vph](system-requirements.md#3711e) | O| Yes / No ||
||| 3.7.11 f) | [occupancy\_percent](system-requirements.md#3711f)| O| Yes / No ||
| 2.5.2.8.2 | [Queue Warning](concept-of-operations.md#25282-zone-traffic--queue-warning) ||||||
||| **3.7.19** | [**Enumeration of FlashingBeaconFunction**](system-requirements.md#3719-enumeration-of-flashingbeaconfunction)||||
| **2.5.2.9**| [**Zone Device**](concept-of-operations.md#2529-zone-device) ||||||
| 2.5.2.9.1 | [Inventory and Status](concept-of-operations.md#25291-zone-device--inventory-and-status)||||||
||| **3.7.2** | [**Contents of FieldDeviceFeature**](system-requirements.md#372-contents-of-fielddevicefeature)||||
||| 3.7.2 d)| [geometry](system-requirements.md#372d) | M| Yes||
||| **3.7.3** | [**Contents of FieldDeviceCoreDetails**](system-requirements.md#373-contents-of-fielddevicecoredetails)||||
||| 3.7.3 a)| [device\_type](system-requirements.md#373a) | M| Yes||
||| 3.7.3 c)| [device\_status](system-requirements.md#373c) | M| Yes||
||| 3.7.3 l)| [road\_event\_ids](system-requirements.md#373l)| O| Yes / No ||
||| **3.7.17** | [**Enumeration of FieldDeviceType**](system-requirements.md#3717-enumeration-of-fielddevicetype) ||||
||| **3.7.18** | [**Enumeration of FieldDeviceStatus**](system-requirements.md#3718-enumeration-of-fielddevicestatus) ||||
||| **3.7.21** | [**Enumeration of MarkedLocationType**](system-requirements.md#3721-enumeration-of-markedlocationtype) ||||
| 2.5.2.9.2 | [Location Marker Type](concept-of-operations.md#25292-zone-device--location-marker-type)||||||
||| **3.7.21** | [**Enumeration of MarkedLocationType**](system-requirements.md#3721-enumeration-of-markedlocationtype) ||||
| 2.5.2.9.3 | [Device Type](concept-of-operations.md#25293-zone-device--device-type)||||||
||| **3.7.3** | [**Contents of FieldDeviceCoreDetails**](system-requirements.md#373-contents-of-fielddevicecoredetails)||||
||| 3.7.3 a)| [device\_type](system-requirements.md#373a) | M| Yes||
||| **3.7.17** | [**Enumeration of FieldDeviceType**](system-requirements.md#3717-enumeration-of-fielddevicetype) ||||
| 2.5.2.9.4 | [Position/Geometry](concept-of-operations.md#25294-zone-device--positiongeometry)||||||
||| **3.7.2** | [**Contents of FieldDeviceFeature**](system-requirements.md#372-contents-of-fielddevicefeature)||||
||| 3.7.2 d)| [geometry](system-requirements.md#372d) | M| Yes||
| 2.5.2.9.5 | [Device Status](concept-of-operations.md#25295-zone-device--device-status) ||||||
||| **3.7.3** | [**Contents of FieldDeviceCoreDetails**](system-requirements.md#373-contents-of-fielddevicecoredetails)||||
||| 3.7.3 c)| [device\_status](system-requirements.md#373c) | M| Yes||
||| **3.7.18** | [**Enumeration of FieldDeviceStatus**](system-requirements.md#3718-enumeration-of-fielddevicestatus) ||||
| 2.5.2.9.6 | [Zone Identifier](concept-of-operations.md#25296-zone-device--zone-identifier) ||||||
||| **3.7.3** | [**Contents of FieldDeviceCoreDetails**](system-requirements.md#373-contents-of-fielddevicecoredetails)||||
||| 3.7.3 l)| [road\_event\_ids](system-requirements.md#373l)| O| Yes / No ||
| **2.5.2.10** | [**Zone VRU Device**](concept-of-operations.md#25210-zone-vulnerable-road-users-vru-device) ||||||
| 2.5.2.10.1 | [Worker Presence Status/Activity](concept-of-operations.md#252101-zone-vru-device--worker-presence-statusactivity)||||||
||| **3.6.2** | [**Contents of WorkZoneRoadEvent**](system-requirements.md#362-contents-of-workzoneroadevent) ||||
||| 3.6.2 p)| [worker\_presence](system-requirements.md#362p)| O| Yes / No ||
||| **3.6.11** | [**Contents of WorkerPresence**](system-requirements.md#3611-contents-of-workerpresence) ||||
||| 3.6.11 a) | [are\_workers\_present](system-requirements.md#3611a) | M| Yes||
||| 3.6.11 b) | [method](system-requirements.md#3611b)| O| Yes / No ||
||| 3.6.11 c) | [worker\_presence\_last\_confirmed\_date](system-requirements.md#3611c) | O| Yes / No ||
||| 3.6.11 d) | [confidence](system-requirements.md#3611d) | O| Yes / No ||
||| 3.6.11 e) | [definition](system-requirements.md#3611e) | O| Yes / No ||
||| 3.6.11 f) | [other\_method](system-requirements.md#3611f) | WorkerMethod:O | Yes / No ||
| 2.5.2.10.2 | [VRU Position/Geometry](concept-of-operations.md#252102-zone-vru-device--positiongeometry)||||||
||| **3.7.2** | [**Contents of FieldDeviceFeature**](system-requirements.md#372-contents-of-fielddevicefeature)||||
||| 3.7.2 d)| [Geometry](system-requirements.md#372d) | M| Yes||
||| **3.7.21** | [**Enumeration of MarkedLocationType**](system-requirements.md#3721-enumeration-of-markedlocationtype) ||||
| **2.5.2.11** | [**Zone Work Vehicle Device**](concept-of-operations.md#25211-zone-work-vehicle-device)||||||
| 2.5.2.11.1 | [Vehicle Type](concept-of-operations.md#252111-zone-work-vehicle-device--vehicle-type) ||||||
||| **3.7.21** | [**Enumeration of MarkedLocationType**](system-requirements.md#3721-enumeration-of-markedlocationtype) ||||
| 2.5.2.11.2 | [Vehicle Position](concept-of-operations.md#252112-zone-work-vehicle-device--vehicle-position) ||||||
||| **3.7.2** | [**Contents of FieldDeviceFeature**](system-requirements.md#372-contents-of-fielddevicefeature)||||
||| 3.7.2 d)| [geometry](system-requirements.md#372d) | M| Yes||
||| **3.7.21** | [**Enumeration of MarkedLocationType**](system-requirements.md#3721-enumeration-of-markedlocationtype) ||||

</div>