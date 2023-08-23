     

### <a id="documentation-body"></a>

![Hackolade image](/DAH_Markdown/image1.png?raw=true)

JSON Physical Model
-------------------

#### Schema for:

Model name: DAH WSAPI

Author:

Version:

File name: DAH\_hackolade.json

File path: C:\\gitRepos\\RKKP.afdDI.Webservice.DAH\\DAH\_hackolade.json

Printed On: Wed Aug 23 2023 12:14:45 GMT+0200 (Centraleuropæisk sommertid)

Created with: [Hackolade](https://hackolade.com/) - Polyglot data modeling for NoSQL databases, storage formats, REST APIs, and JSON in RDBMS

### <a id="contents"></a>

*   [Table of Contents](#contents)
*   [1\. Model](#model)
*   [2\. Groups](#containers)
    *   [2.1 DAH](#3991a47e-ed5c-4874-8551-543877fb3bd4)
        
        [2.1.2. Documents](#3991a47e-ed5c-4874-8551-543877fb3bd4-children)
        
        [2.1.2.1 DAH](#17f74ea6-64e2-49bc-9f74-d237d212ca37)
        

### <a id="model"></a>

##### 1\. Model

##### 1.1 Model **DAH WSAPI**

##### 1.1.1 **DAH WSAPI** Entity Relationship Diagram

![Hackolade image](/DAH_Markdown/image2.png?raw=true)

##### 1.1.2 **DAH WSAPI** Properties

##### 1.1.2.1 **Details** tab

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td><span>Model name</span></td><td>DAH WSAPI</td></tr><tr><td><span>Technical name</span></td><td></td></tr><tr><td><span>Description</span></td><td><div class="docs-markdown"></div></td></tr><tr><td><span>Author</span></td><td></td></tr><tr><td><span>Target</span></td><td>JSON</td></tr><tr><td><span>Draft version</span></td><td>2019-09</td></tr><tr><td><span>Version</span></td><td></td></tr><tr><td><span>Synchronization Id</span></td><td></td></tr><tr><td><span>Lineage capture</span></td><td></td></tr><tr><td><span>Polyglot models</span></td><td></td></tr><tr><td><span>Comments</span></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.3 **DAH WSAPI** DB Definitions

### <a id="containers"></a>

##### 2\. Groups

### <a id="3991a47e-ed5c-4874-8551-543877fb3bd4"></a>2.1 Group **DAH**

![Hackolade image](/DAH_Markdown/image3.png?raw=true)

##### 2.1.1 **DAH** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Group name</td><td>DAH</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="3991a47e-ed5c-4874-8551-543877fb3bd4-children"></a>2.1.2 **DAH** Documents

### <a id="17f74ea6-64e2-49bc-9f74-d237d212ca37"></a>2.1.2.1 Document **DAH**

##### 2.1.2.1.1 **DAH** Tree Diagram

![Hackolade image](/DAH_Markdown/image4.png?raw=true)

##### 2.1.2.1.2 **DAH** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Document name</td><td>DAH</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>$ref</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Group</td><td><a href=#3991a47e-ed5c-4874-8551-543877fb3bd4><span class="name-container">DAH</span></a></td></tr><tr><td>Pulsar topic name</td><td></td></tr><tr><td>Is non-persistent Pulsar topic</td><td></td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Unevaluated properties</td><td></td></tr><tr><td>Dependent schemas</td><td></td></tr><tr><td>Examples</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr><tr><td>Skema version</td><td>1.0.0</td></tr></tbody></table>

##### 2.1.2.1.3 **DAH** Fields

<table><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#6630a072-09af-4aef-81c4-783c55592168 class="margin-0">Courses</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#464f0966-bd83-45e1-aef0-f1a999973946 class="margin-0">Activities</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#c28f4842-6075-4b91-be89-17540d8001cc class="margin-0">Observations</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#652016de-d9e4-4e1b-a2f8-ee200e5f2835 class="margin-5">PainEvaluation</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e17cfdfb-b657-41a6-8fb0-e9290f298d59 class="margin-10">ResultCode</a></td><td class="no-break-word">ResultCode</td><td>false</td><td></td><td><div class="docs-markdown"><p>Note: Bruges ved anden type af smertescore (ResultCode)</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#9d2d8eb7-ce0a-4845-ae4b-dcacd1f8435b class="margin-5">OxygenSaturation</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#2f3675de-5c88-49f8-832d-c35ea10bf2eb class="margin-10">ResultValue</a></td><td class="no-break-word">ResultValue</td><td>false</td><td></td><td><div class="docs-markdown"><p>Unit = %</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#9d19b322-1bd3-474b-a39a-31d0634ddffd class="margin-5">SystolicBloodPressure</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#cc391974-580c-4e6a-b538-5a2a1d7ef223 class="margin-10">ResultValue</a></td><td class="no-break-word">ResultValue</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#11b91e55-abe8-4329-b663-554399fd3953 class="margin-5">GlascowComaScale</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#9924d95a-ccd2-4b0d-be9d-fb4f9a139c30 class="margin-10">ResultValue</a></td><td class="no-break-word">ResultValue</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#66175611-a488-4e6c-b467-2e39141dbd13 class="margin-5">AVPUScale</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#8fcccd89-e548-4229-84fb-c8f24e0c23ee class="margin-10">ResultCode</a></td><td class="no-break-word">ResultCode</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#c5d6eb05-b61f-4d83-9520-39ff9178cacc class="margin-5">Triage</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#0d5fcdbc-8fe5-4d54-a6c2-54e5c64ca027 class="margin-10">ResultCode</a></td><td class="no-break-word">ResultCode</td><td>false</td><td></td><td><div class="docs-markdown"><p>R = Red O = Orange Y = Yellow G = Green B = Blue</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#0d9f7eec-a1c5-4428-ab58-0bf2a6a33e38 class="margin-5">OxygenDemand</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#1cf4c2e9-fa57-4bbf-bb47-57691673cbe1 class="margin-10">ResultCode</a></td><td class="no-break-word">ResultCode</td><td>false</td><td></td><td><div class="docs-markdown"><p>Y = Yes N = No</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#3d3c960b-0d07-42a3-8c93-386e79154a50 class="margin-5">RespiratoryRate</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"><p>First respiratory rate</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#c683b39c-1724-4af0-a4ac-fc367b034168 class="margin-10">ResultValue</a></td><td class="no-break-word">ResultValue</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#7c54fcb1-9eba-42f1-a2f8-41a3bfff2d4e class="margin-5">Temperature</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"><p>First temperature</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#40cbd3d2-2814-402c-9e10-7af41dfce866 class="margin-10">ResultValue</a></td><td class="no-break-word">ResultValue</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#7a349cb6-2fd9-4e78-87eb-4ec3184e0f5a class="margin-5">PulseRate</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"><p>First pulse rate</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#36c2391d-6822-43a2-bba6-875f6419c2bc class="margin-10">ResultValue</a></td><td class="no-break-word">ResultValue</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#f591215b-960f-4f9d-9263-9613b577d37d class="margin-0">Contacts</a></td><td class="no-break-word">Gruppe</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#20913ec5-c079-4706-958b-74ac9b4f2bf4 class="margin-5">NoteType</a></td><td class="no-break-word">Contact</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#12a5e029-14ab-41e1-9757-145016696779 class="margin-0">Diagnosis</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="6630a072-09af-4aef-81c4-783c55592168"></a>2.1.2.1.3.1 Field **Courses**

##### 2.1.2.1.3.1.1 **Courses** Tree Diagram

![Hackolade image](/DAH_Markdown/image5.png?raw=true)

##### 2.1.2.1.3.1.2 **Courses** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>Courses</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Anchor</td><td></td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependent required</td><td></td></tr><tr><td>Required</td><td></td></tr><tr><td>Dependent schemas</td><td></td></tr><tr><td>Min Properties</td><td></td></tr><tr><td>Max Properties</td><td></td></tr><tr><td>ReadOnly</td><td></td></tr><tr><td>WriteOnly</td><td></td></tr><tr><td>Deprecated</td><td></td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Unevaluated properties</td><td></td></tr><tr><td><span>Property names</span></td><td></td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Relationship name</td><td></td></tr><tr><td>Cardinality</td><td></td></tr><tr><td>Examples</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="464f0966-bd83-45e1-aef0-f1a999973946"></a>2.1.2.1.3.2 Field **Activities**

##### 2.1.2.1.3.2.1 **Activities** Tree Diagram

![Hackolade image](/DAH_Markdown/image6.png?raw=true)

##### 2.1.2.1.3.2.2 **Activities** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>Activities</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Anchor</td><td></td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependent required</td><td></td></tr><tr><td>Required</td><td></td></tr><tr><td>Dependent schemas</td><td></td></tr><tr><td>Min Properties</td><td></td></tr><tr><td>Max Properties</td><td></td></tr><tr><td>ReadOnly</td><td></td></tr><tr><td>WriteOnly</td><td></td></tr><tr><td>Deprecated</td><td></td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Unevaluated properties</td><td></td></tr><tr><td><span>Property names</span></td><td></td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Relationship name</td><td></td></tr><tr><td>Cardinality</td><td></td></tr><tr><td>Examples</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="c28f4842-6075-4b91-be89-17540d8001cc"></a>2.1.2.1.3.3 Field **Observations**

##### 2.1.2.1.3.3.1 **Observations** Tree Diagram

![Hackolade image](/DAH_Markdown/image7.png?raw=true)

##### 2.1.2.1.3.3.2 **Observations** Hierarchy

Parent field: **DAH**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#652016de-d9e4-4e1b-a2f8-ee200e5f2835 class="margin-NaN">PainEvaluation</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#9d2d8eb7-ce0a-4845-ae4b-dcacd1f8435b class="margin-NaN">OxygenSaturation</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#9d19b322-1bd3-474b-a39a-31d0634ddffd class="margin-NaN">SystolicBloodPressure</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#11b91e55-abe8-4329-b663-554399fd3953 class="margin-NaN">GlascowComaScale</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#66175611-a488-4e6c-b467-2e39141dbd13 class="margin-NaN">AVPUScale</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#c5d6eb05-b61f-4d83-9520-39ff9178cacc class="margin-NaN">Triage</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#0d9f7eec-a1c5-4428-ab58-0bf2a6a33e38 class="margin-NaN">OxygenDemand</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#3d3c960b-0d07-42a3-8c93-386e79154a50 class="margin-NaN">RespiratoryRate</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"><p>First respiratory rate</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#7c54fcb1-9eba-42f1-a2f8-41a3bfff2d4e class="margin-NaN">Temperature</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"><p>First temperature</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#7a349cb6-2fd9-4e78-87eb-4ec3184e0f5a class="margin-NaN">PulseRate</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"><p>First pulse rate</p></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.1.3.3.3 **Observations** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>Observations</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Anchor</td><td></td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependent required</td><td></td></tr><tr><td>Required</td><td></td></tr><tr><td>Dependent schemas</td><td></td></tr><tr><td>Min Properties</td><td></td></tr><tr><td>Max Properties</td><td></td></tr><tr><td>ReadOnly</td><td></td></tr><tr><td>WriteOnly</td><td></td></tr><tr><td>Deprecated</td><td></td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Unevaluated properties</td><td></td></tr><tr><td><span>Property names</span></td><td></td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Relationship name</td><td></td></tr><tr><td>Cardinality</td><td></td></tr><tr><td>Examples</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="652016de-d9e4-4e1b-a2f8-ee200e5f2835"></a>2.1.2.1.3.4 Field **PainEvaluation**

##### 2.1.2.1.3.4.1 **PainEvaluation** Tree Diagram

![Hackolade image](/DAH_Markdown/image8.png?raw=true)

##### 2.1.2.1.3.4.2 **PainEvaluation** Hierarchy

Parent field: **Observations**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#e17cfdfb-b657-41a6-8fb0-e9290f298d59 class="margin-NaN">ResultCode</a></td><td class="no-break-word">ResultCode</td><td>false</td><td></td><td><div class="docs-markdown"><p>Note: Bruges ved anden type af smertescore (ResultCode)</p></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.1.3.4.3 **PainEvaluation** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="e17cfdfb-b657-41a6-8fb0-e9290f298d59"></a>2.1.2.1.3.5 Field **ResultCode**

##### 2.1.2.1.3.5.1 **ResultCode** Tree Diagram

![Hackolade image](/DAH_Markdown/image9.png?raw=true)

##### 2.1.2.1.3.5.2 **ResultCode** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="9d2d8eb7-ce0a-4845-ae4b-dcacd1f8435b"></a>2.1.2.1.3.6 Field **OxygenSaturation**

##### 2.1.2.1.3.6.1 **OxygenSaturation** Tree Diagram

![Hackolade image](/DAH_Markdown/image10.png?raw=true)

##### 2.1.2.1.3.6.2 **OxygenSaturation** Hierarchy

Parent field: **Observations**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#2f3675de-5c88-49f8-832d-c35ea10bf2eb class="margin-NaN">ResultValue</a></td><td class="no-break-word">ResultValue</td><td>false</td><td></td><td><div class="docs-markdown"><p>Unit = %</p></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.1.3.6.3 **OxygenSaturation** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="2f3675de-5c88-49f8-832d-c35ea10bf2eb"></a>2.1.2.1.3.7 Field **ResultValue**

##### 2.1.2.1.3.7.1 **ResultValue** Tree Diagram

![Hackolade image](/DAH_Markdown/image11.png?raw=true)

##### 2.1.2.1.3.7.2 **ResultValue** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="9d19b322-1bd3-474b-a39a-31d0634ddffd"></a>2.1.2.1.3.8 Field **SystolicBloodPressure**

##### 2.1.2.1.3.8.1 **SystolicBloodPressure** Tree Diagram

![Hackolade image](/DAH_Markdown/image12.png?raw=true)

##### 2.1.2.1.3.8.2 **SystolicBloodPressure** Hierarchy

Parent field: **Observations**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#cc391974-580c-4e6a-b538-5a2a1d7ef223 class="margin-NaN">ResultValue</a></td><td class="no-break-word">ResultValue</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.1.3.8.3 **SystolicBloodPressure** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="cc391974-580c-4e6a-b538-5a2a1d7ef223"></a>2.1.2.1.3.9 Field **ResultValue**

##### 2.1.2.1.3.9.1 **ResultValue** Tree Diagram

![Hackolade image](/DAH_Markdown/image13.png?raw=true)

##### 2.1.2.1.3.9.2 **ResultValue** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="11b91e55-abe8-4329-b663-554399fd3953"></a>2.1.2.1.3.10 Field **GlascowComaScale**

##### 2.1.2.1.3.10.1 **GlascowComaScale** Tree Diagram

![Hackolade image](/DAH_Markdown/image14.png?raw=true)

##### 2.1.2.1.3.10.2 **GlascowComaScale** Hierarchy

Parent field: **Observations**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#9924d95a-ccd2-4b0d-be9d-fb4f9a139c30 class="margin-NaN">ResultValue</a></td><td class="no-break-word">ResultValue</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.1.3.10.3 **GlascowComaScale** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="9924d95a-ccd2-4b0d-be9d-fb4f9a139c30"></a>2.1.2.1.3.11 Field **ResultValue**

##### 2.1.2.1.3.11.1 **ResultValue** Tree Diagram

![Hackolade image](/DAH_Markdown/image15.png?raw=true)

##### 2.1.2.1.3.11.2 **ResultValue** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="66175611-a488-4e6c-b467-2e39141dbd13"></a>2.1.2.1.3.12 Field **AVPUScale**

##### 2.1.2.1.3.12.1 **AVPUScale** Tree Diagram

![Hackolade image](/DAH_Markdown/image16.png?raw=true)

##### 2.1.2.1.3.12.2 **AVPUScale** Hierarchy

Parent field: **Observations**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#8fcccd89-e548-4229-84fb-c8f24e0c23ee class="margin-NaN">ResultCode</a></td><td class="no-break-word">ResultCode</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.1.3.12.3 **AVPUScale** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="8fcccd89-e548-4229-84fb-c8f24e0c23ee"></a>2.1.2.1.3.13 Field **ResultCode**

##### 2.1.2.1.3.13.1 **ResultCode** Tree Diagram

![Hackolade image](/DAH_Markdown/image17.png?raw=true)

##### 2.1.2.1.3.13.2 **ResultCode** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="c5d6eb05-b61f-4d83-9520-39ff9178cacc"></a>2.1.2.1.3.14 Field **Triage**

##### 2.1.2.1.3.14.1 **Triage** Tree Diagram

![Hackolade image](/DAH_Markdown/image18.png?raw=true)

##### 2.1.2.1.3.14.2 **Triage** Hierarchy

Parent field: **Observations**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#0d5fcdbc-8fe5-4d54-a6c2-54e5c64ca027 class="margin-NaN">ResultCode</a></td><td class="no-break-word">ResultCode</td><td>false</td><td></td><td><div class="docs-markdown"><p>R = Red O = Orange Y = Yellow G = Green B = Blue</p></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.1.3.14.3 **Triage** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="0d5fcdbc-8fe5-4d54-a6c2-54e5c64ca027"></a>2.1.2.1.3.15 Field **ResultCode**

##### 2.1.2.1.3.15.1 **ResultCode** Tree Diagram

![Hackolade image](/DAH_Markdown/image19.png?raw=true)

##### 2.1.2.1.3.15.2 **ResultCode** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="0d9f7eec-a1c5-4428-ab58-0bf2a6a33e38"></a>2.1.2.1.3.16 Field **OxygenDemand**

##### 2.1.2.1.3.16.1 **OxygenDemand** Tree Diagram

![Hackolade image](/DAH_Markdown/image20.png?raw=true)

##### 2.1.2.1.3.16.2 **OxygenDemand** Hierarchy

Parent field: **Observations**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#1cf4c2e9-fa57-4bbf-bb47-57691673cbe1 class="margin-NaN">ResultCode</a></td><td class="no-break-word">ResultCode</td><td>false</td><td></td><td><div class="docs-markdown"><p>Y = Yes N = No</p></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.1.3.16.3 **OxygenDemand** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="1cf4c2e9-fa57-4bbf-bb47-57691673cbe1"></a>2.1.2.1.3.17 Field **ResultCode**

##### 2.1.2.1.3.17.1 **ResultCode** Tree Diagram

![Hackolade image](/DAH_Markdown/image21.png?raw=true)

##### 2.1.2.1.3.17.2 **ResultCode** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="3d3c960b-0d07-42a3-8c93-386e79154a50"></a>2.1.2.1.3.18 Field **RespiratoryRate**

##### 2.1.2.1.3.18.1 **RespiratoryRate** Tree Diagram

![Hackolade image](/DAH_Markdown/image22.png?raw=true)

##### 2.1.2.1.3.18.2 **RespiratoryRate** Hierarchy

Parent field: **Observations**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#c683b39c-1724-4af0-a4ac-fc367b034168 class="margin-NaN">ResultValue</a></td><td class="no-break-word">ResultValue</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.1.3.18.3 **RespiratoryRate** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="c683b39c-1724-4af0-a4ac-fc367b034168"></a>2.1.2.1.3.19 Field **ResultValue**

##### 2.1.2.1.3.19.1 **ResultValue** Tree Diagram

![Hackolade image](/DAH_Markdown/image23.png?raw=true)

##### 2.1.2.1.3.19.2 **ResultValue** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="7c54fcb1-9eba-42f1-a2f8-41a3bfff2d4e"></a>2.1.2.1.3.20 Field **Temperature**

##### 2.1.2.1.3.20.1 **Temperature** Tree Diagram

![Hackolade image](/DAH_Markdown/image24.png?raw=true)

##### 2.1.2.1.3.20.2 **Temperature** Hierarchy

Parent field: **Observations**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#40cbd3d2-2814-402c-9e10-7af41dfce866 class="margin-NaN">ResultValue</a></td><td class="no-break-word">ResultValue</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.1.3.20.3 **Temperature** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="40cbd3d2-2814-402c-9e10-7af41dfce866"></a>2.1.2.1.3.21 Field **ResultValue**

##### 2.1.2.1.3.21.1 **ResultValue** Tree Diagram

![Hackolade image](/DAH_Markdown/image25.png?raw=true)

##### 2.1.2.1.3.21.2 **ResultValue** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="7a349cb6-2fd9-4e78-87eb-4ec3184e0f5a"></a>2.1.2.1.3.22 Field **PulseRate**

##### 2.1.2.1.3.22.1 **PulseRate** Tree Diagram

![Hackolade image](/DAH_Markdown/image26.png?raw=true)

##### 2.1.2.1.3.22.2 **PulseRate** Hierarchy

Parent field: **Observations**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#36c2391d-6822-43a2-bba6-875f6419c2bc class="margin-NaN">ResultValue</a></td><td class="no-break-word">ResultValue</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.1.3.22.3 **PulseRate** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="36c2391d-6822-43a2-bba6-875f6419c2bc"></a>2.1.2.1.3.23 Field **ResultValue**

##### 2.1.2.1.3.23.1 **ResultValue** Tree Diagram

![Hackolade image](/DAH_Markdown/image27.png?raw=true)

##### 2.1.2.1.3.23.2 **ResultValue** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="f591215b-960f-4f9d-9263-9613b577d37d"></a>2.1.2.1.3.24 Field **Contacts**

##### 2.1.2.1.3.24.1 **Contacts** Tree Diagram

![Hackolade image](/DAH_Markdown/image28.png?raw=true)

##### 2.1.2.1.3.24.2 **Contacts** Hierarchy

Parent field: **DAH**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#20913ec5-c079-4706-958b-74ac9b4f2bf4 class="margin-NaN">NoteType</a></td><td class="no-break-word">Contact</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.1.3.24.3 **Contacts** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="20913ec5-c079-4706-958b-74ac9b4f2bf4"></a>2.1.2.1.3.25 Field **NoteType**

##### 2.1.2.1.3.25.1 **NoteType** Tree Diagram

![Hackolade image](/DAH_Markdown/image29.png?raw=true)

##### 2.1.2.1.3.25.2 **NoteType** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="12a5e029-14ab-41e1-9757-145016696779"></a>2.1.2.1.3.26 Field **Diagnosis**

##### 2.1.2.1.3.26.1 **Diagnosis** Tree Diagram

![Hackolade image](/DAH_Markdown/image30.png?raw=true)

##### 2.1.2.1.3.26.2 **Diagnosis** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>Diagnosis</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Anchor</td><td></td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependent required</td><td></td></tr><tr><td>Required</td><td></td></tr><tr><td>Dependent schemas</td><td></td></tr><tr><td>Min Properties</td><td></td></tr><tr><td>Max Properties</td><td></td></tr><tr><td>ReadOnly</td><td></td></tr><tr><td>WriteOnly</td><td></td></tr><tr><td>Deprecated</td><td></td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Unevaluated properties</td><td></td></tr><tr><td><span>Property names</span></td><td></td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Relationship name</td><td></td></tr><tr><td>Cardinality</td><td></td></tr><tr><td>Examples</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 2.1.2.1.4 **DAH** JSON Schema

```
{
    "$schema": "http://json-schema.org/draft-04/schema#",
    "type": "object",
    "title": "DAH",
    "properties": {
        "Courses": {
            "type": "object",
            "additionalProperties": false
        },
        "Activities": {
            "type": "object",
            "additionalProperties": false
        },
        "Observations": {
            "type": "object",
            "properties": {
                "PainEvaluation": {
                    "type": "object",
                    "properties": {
                        "ResultCode": {
                            "type": "string",
                            "description": "Note: Bruges ved anden type af smertescore (ResultCode)",
                            "enum": [
                                {
                                    "id": "cc972a94-9740-4c72-b123-539b5ec5fb11",
                                    "Udfald": "VAS"
                                },
                                {
                                    "id": "6fb6b428-d6a6-4c27-af0d-c296b1ea2650",
                                    "Udfald": "NRS"
                                },
                                {
                                    "id": "1b564105-32aa-4113-b238-0f1b264373d0",
                                    "Udfald": "VRS"
                                },
                                {
                                    "id": "724981d6-881e-4038-879c-acb05171cf3c",
                                    "Udfald": "Andet"
                                }
                            ]
                        }
                    }
                },
                "OxygenSaturation": {
                    "type": "object",
                    "properties": {
                        "OXYSAT": {
                            "type": "number",
                            "title": "ResultValue",
                            "description": "Unit = %"
                        }
                    }
                },
                "SystolicBloodPressure": {
                    "type": "object",
                    "properties": {
                        "ResultValue": {
                            "type": "number"
                        }
                    }
                },
                "GlascowComaScale": {
                    "type": "object",
                    "properties": {
                        "GCS": {
                            "type": "number",
                            "title": "ResultValue"
                        }
                    }
                },
                "AVPUScale": {
                    "type": "object",
                    "properties": {
                        "AVPU": {
                            "type": "string",
                            "title": "ResultCode",
                            "enum": [
                                {
                                    "id": "07cbd71a-7256-4237-ae28-fbe7db9fc5bc",
                                    "Udfald": "A"
                                },
                                {
                                    "id": "f66657ad-2023-4814-a01f-476b9355c700",
                                    "Udfald": "V"
                                },
                                {
                                    "id": "5a2d6b45-47df-4281-af88-60ea919c047c",
                                    "Udfald": "P"
                                },
                                {
                                    "id": "1d22a47c-191d-4fd6-b070-38c2ce17da63",
                                    "Udfald": "U"
                                }
                            ]
                        }
                    }
                },
                "Triage": {
                    "type": "object",
                    "properties": {
                        "Triage": {
                            "type": "string",
                            "title": "ResultCode",
                            "description": "R = Red\nO = Orange\nY = Yellow\nG = Green\nB = Blue",
                            "enum": [
                                {
                                    "id": "48512388-4ab3-43fa-892c-385812264bdb",
                                    "Udfald": "R"
                                },
                                {
                                    "id": "2ec6f116-22ca-46a0-a0a5-fffd31fa7199",
                                    "Udfald": "O"
                                },
                                {
                                    "id": "354f5a2c-687f-4e19-9b20-897b11bf722c",
                                    "Udfald": "Y"
                                },
                                {
                                    "id": "fe1a8e82-d2fc-4a2d-a5ec-c6416aca3dab",
                                    "Udfald": "G"
                                },
                                {
                                    "id": "66356154-9035-41af-b01f-dd1ddd866077",
                                    "Udfald": "B"
                                }
                            ]
                        }
                    }
                },
                "OxygenDemand": {
                    "type": "object",
                    "properties": {
                        "OXYDEM": {
                            "type": "string",
                            "title": "ResultCode",
                            "description": "Y = Yes\nN = No",
                            "enum": [
                                {
                                    "id": "f9cd161c-e6cf-47e8-8acd-c133cb7b5790",
                                    "Udfald": "Y"
                                },
                                {
                                    "id": "3a4ddfd9-f956-4451-b574-c1dd12c6447c",
                                    "Udfald": "N"
                                }
                            ]
                        }
                    }
                },
                "RespiratoryRate": {
                    "type": "object",
                    "description": "First respiratory rate",
                    "properties": {
                        "ResultValue": {
                            "type": "number"
                        }
                    }
                },
                "Temperature": {
                    "type": "object",
                    "description": "First temperature",
                    "properties": {
                        "ResultValue": {
                            "type": "number"
                        }
                    }
                },
                "PulseRate": {
                    "type": "object",
                    "description": "First pulse rate",
                    "properties": {
                        "ResultValue": {
                            "type": "number"
                        }
                    }
                }
            },
            "additionalProperties": false
        },
        "Contacts": {
            "type": "object",
            "properties": {
                "NoteType": {
                    "type": "object"
                }
            }
        },
        "Diagnosis": {
            "type": "object",
            "additionalProperties": false
        }
    },
    "additionalProperties": false
}
```

##### 2.1.2.1.5 **DAH** JSON data

```
{
    "Courses": {},
    "Activities": {},
    "Observations": {
        "PainEvaluation": {
            "ResultCode": {
                "id": "724981d6-881e-4038-879c-acb05171cf3c",
                "Udfald": "Andet"
            }
        },
        "OxygenSaturation": {
            "OXYSAT": 35
        },
        "SystolicBloodPressure": {
            "ResultValue": 48
        },
        "GlascowComaScale": {
            "GCS": -60
        },
        "AVPUScale": {
            "AVPU": {
                "id": "1d22a47c-191d-4fd6-b070-38c2ce17da63",
                "Udfald": "U"
            }
        },
        "Triage": {
            "Triage": {
                "id": "66356154-9035-41af-b01f-dd1ddd866077",
                "Udfald": "B"
            }
        },
        "OxygenDemand": {
            "OXYDEM": {
                "id": "3a4ddfd9-f956-4451-b574-c1dd12c6447c",
                "Udfald": "N"
            }
        },
        "RespiratoryRate": {
            "ResultValue": -20
        },
        "Temperature": {
            "ResultValue": 90
        },
        "PulseRate": {
            "ResultValue": 82
        }
    },
    "Contacts": {
        "NoteType": {}
    },
    "Diagnosis": {}
}
```

### <a id="edges"></a>