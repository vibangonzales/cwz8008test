### 2.5.1	Architectural Needs
This section, outlining the architectural needs of CWZs, is organized into sub-sections as follows:
•	Backward Compatibility
•	GeoJSON Data Exchange [Constraint]
•	GeoJSON Data Format [Constraint]
•	GeoJSON Data Validation
•	Frequency of Data Updates
•	UTC Date-Time Format [Constraint]

Note: The term “CWZ Deployer” is used sparingly throughout Section 2.5 (Needs) when neither a data provider nor data consumer can be identified as an actor. This happens, for example, in the description of the architectural needs below. 
#### 2.5.1.1	Architectural Need – Compatibility with the WZDx Specification
CWZ deployers need to describe and implement a mechanism to support compatibility with the design elements specified in WZDx v4.2. 
#### 2.5.1.2	Architectural Need – GeoJSON Data Exchange [Constraint]
##### 2.5.1.2.1	GeoJSON Data Exchange – Poll for Data [Constraint]
CWZ deployers need to share the current status of work zone information in the GeoJSON data format. Poll for Data is a synchronous method of data communications.
#### 2.5.1.3	Architectural Need – GeoJSON Data Format [Constraint]
CWZ deployers must continue using the GeoJSON data format (as applied in the WZDx specification). A JSON schema is used to describe the GeoJSON format and can also validate the conformance of work zone data to the specification described in the JSON schema

Feedback from CWZ deployers indicates that the JSON schema and GeoJSON data format work well, as follows:
•	The GeoJSON data format provides a framework to support the geospatial information value chain.
•	The GeoJSON data format works well for high-bandwidth communications (e.g., internet connections).
•	The GeoJSON data format provides outputs that support data visualization. For example, the data can be used with off-the-shelf GIS tools directly “out of the box. 
#### 2.5.1.4	Architectural Need – GeoJSON Data Validation [Constraint]
CWZ deployers need to verify conformance of work zone data against the design. Currently, the verification of work zone data (e.g., a WZDx WorkZoneFeed) is accomplished using off-the-shelf software that verifies the work zone data against the specification's JSON Schema.

#### 2.5.1.5	Architectural Need – Frequency of Data Updates
CWZ data providers use the frequency of updates time to reflect how often real-time work zone condition information is made available. 

CWZ data consumers need to know the frequency of work zone data updates when new information is available.

#### 2.5.1.6	Architectural Need – UTC Date-Time Format Specification [Constraint]
CWZ deployers need to exchange date-time data in a standardized format.
 
CWZ deployers need to continue using the UTC Date-Time format specification. 
