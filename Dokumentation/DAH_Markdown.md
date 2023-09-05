     

### <a id="documentation-body"></a>

![Hackolade image](/DAH_Markdown/image1.png?raw=true)

JSON Physical Model
-------------------

#### Schema for:

Model name: DAH WSAPI

Author:

Version:

File name: DAH\_hackolade\_v1.0.0.json

File path: C:\\GITrep\\RKKP.afdDI.Webservice.DAH\\DAH\_hackolade\_v1.0.0.json

Printed On: Tue Sep 05 2023 15:03:21 GMT+0200 (Centraleuropæisk sommertid)

Created with: [Hackolade](https://hackolade.com/) - Polyglot data modeling for NoSQL databases, storage formats, REST APIs, and JSON in RDBMS

### <a id="contents"></a>

*   [Table of Contents](#contents)
*   [1\. Groups](#containers)
    *   [1.1 DAH](#3991a47e-ed5c-4874-8551-543877fb3bd4)
        
        [1.1.2. Documents](#3991a47e-ed5c-4874-8551-543877fb3bd4-children)
        
        [1.1.2.1 DAH](#17f74ea6-64e2-49bc-9f74-d237d212ca37)
        

### <a id="containers"></a>

##### 1\. Groups

### <a id="3991a47e-ed5c-4874-8551-543877fb3bd4"></a>1.1 Group **DAH**

![Hackolade image](/DAH_Markdown/image2.png?raw=true)

##### 1.1.1 **DAH** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Group name</td><td>DAH</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="3991a47e-ed5c-4874-8551-543877fb3bd4-children"></a>1.1.2 **DAH** Documents

### <a id="17f74ea6-64e2-49bc-9f74-d237d212ca37"></a>1.1.2.1 Document **DAH**

##### 1.1.2.1.1 **DAH** Tree Diagram

![Hackolade image](/DAH_Markdown/image3.png?raw=true)

##### 1.1.2.1.2 **DAH** Properties

<table class="collection-properties-table"><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Document name</td><td>DAH</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>$ref</td><td></td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Group</td><td><a href=#3991a47e-ed5c-4874-8551-543877fb3bd4><span class="name-container">DAH</span></a></td></tr><tr><td>Pulsar topic name</td><td></td></tr><tr><td>Is non-persistent Pulsar topic</td><td></td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Unevaluated properties</td><td></td></tr><tr><td>Dependent schemas</td><td></td></tr><tr><td>Examples</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr><tr><td>Skema version</td><td>1.0.0</td></tr></tbody></table>

##### 1.1.2.1.3 **DAH** Fields

<table><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#6630a072-09af-4aef-81c4-783c55592168 class="margin-0">Courses</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#464f0966-bd83-45e1-aef0-f1a999973946 class="margin-0">Activities</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#c28f4842-6075-4b91-be89-17540d8001cc class="margin-0">Observations</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#652016de-d9e4-4e1b-a2f8-ee200e5f2835 class="margin-5">PainEvaluation</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"><p>Første smertemåling. Hvis der angives 'Andet' i type, er det muligt at indsende yderligere information i 'Note' elementet.</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#e17cfdfb-b657-41a6-8fb0-e9290f298d59 class="margin-10">ResultCode</a></td><td class="no-break-word">ResultCode</td><td>false</td><td></td><td><div class="docs-markdown"><p>Note: Bruges ved anden type af smertescore (ResultCode)</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#bcdc8afd-e8f0-47be-8469-9cd8540f68fb class="margin-10">ResultValue</a></td><td class="no-break-word">ResultValue</td><td>false</td><td></td><td><div class="docs-markdown"><p>Værdi for smertescore</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#9d2d8eb7-ce0a-4845-ae4b-dcacd1f8435b class="margin-5">OxygenSaturation</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"><p>Første iltmætningsmåling.</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#2f3675de-5c88-49f8-832d-c35ea10bf2eb class="margin-10">ResultValue</a></td><td class="no-break-word">ResultValue</td><td>false</td><td></td><td><div class="docs-markdown"><p>Enhed = %</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#9d19b322-1bd3-474b-a39a-31d0634ddffd class="margin-5">SystolicBloodPressure</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"><p>Blodtryksmåling (stystolisk).</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#cc391974-580c-4e6a-b538-5a2a1d7ef223 class="margin-10">ResultValue</a></td><td class="no-break-word">ResultValue</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#11b91e55-abe8-4329-b663-554399fd3953 class="margin-5">GlascowComaScale</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"><p>Første Glascow Coma Scale måling.</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#9924d95a-ccd2-4b0d-be9d-fb4f9a139c30 class="margin-10">ResultValue</a></td><td class="no-break-word">ResultValue</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#66175611-a488-4e6c-b467-2e39141dbd13 class="margin-5">AVPUScale</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"><p>Første AVPU skala (bevidsthed).</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#8fcccd89-e548-4229-84fb-c8f24e0c23ee class="margin-10">ResultCode</a></td><td class="no-break-word">ResultCode</td><td>false</td><td></td><td><div class="docs-markdown"><p>A = Alert, V = Verbal, P = Pain, U = Unresponsive</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#c5d6eb05-b61f-4d83-9520-39ff9178cacc class="margin-5">Triage</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"><p>Første Triage kategorisering.</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#0d5fcdbc-8fe5-4d54-a6c2-54e5c64ca027 class="margin-10">ResultCode</a></td><td class="no-break-word">ResultCode</td><td>false</td><td></td><td><div class="docs-markdown"><p>R = Red, O = Orange, Y = Yellow, G = Green, B = Blue</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#0d9f7eec-a1c5-4428-ab58-0bf2a6a33e38 class="margin-5">OxygenDemand</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"><p>Første iltbehov.</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#1cf4c2e9-fa57-4bbf-bb47-57691673cbe1 class="margin-10">ResultCode</a></td><td class="no-break-word">ResultCode</td><td>false</td><td></td><td><div class="docs-markdown"><p>Y = Yes, N = No</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#3d3c960b-0d07-42a3-8c93-386e79154a50 class="margin-5">RespiratoryRate</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"><p>Første respirationsfrekvens måling.</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#c683b39c-1724-4af0-a4ac-fc367b034168 class="margin-10">ResultValue</a></td><td class="no-break-word">ResultValue</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#7c54fcb1-9eba-42f1-a2f8-41a3bfff2d4e class="margin-5">Temperature</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"><p>Første temperatur måling.</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#40cbd3d2-2814-402c-9e10-7af41dfce866 class="margin-10">ResultValue</a></td><td class="no-break-word">ResultValue</td><td>false</td><td></td><td><div class="docs-markdown"><p>Enhed = grader</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#7a349cb6-2fd9-4e78-87eb-4ec3184e0f5a class="margin-5">PulseRate</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"><p>Første pulsmåling.</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#36c2391d-6822-43a2-bba6-875f6419c2bc class="margin-10">ResultValue</a></td><td class="no-break-word">ResultValue</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#f591215b-960f-4f9d-9263-9613b577d37d class="margin-0">Contacts</a></td><td class="no-break-word">Gruppe</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#20913ec5-c079-4706-958b-74ac9b4f2bf4 class="margin-5">NoteType</a></td><td class="no-break-word">Contact</td><td>false</td><td></td><td><div class="docs-markdown"><p>Dato for første afsluttet lægenotat samt notattype (angives i elementet 'Note')</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#12a5e029-14ab-41e1-9757-145016696779 class="margin-0">Diagnosis</a></td><td class="no-break-word">object</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="6630a072-09af-4aef-81c4-783c55592168"></a>1.1.2.1.3.1 Field **Courses**

##### 1.1.2.1.3.1.1 **Courses** Tree Diagram

![Hackolade image](/DAH_Markdown/image4.png?raw=true)

##### 1.1.2.1.3.1.2 **Courses** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>Courses</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Anchor</td><td></td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependent required</td><td></td></tr><tr><td>Required</td><td></td></tr><tr><td>Dependent schemas</td><td></td></tr><tr><td>Min Properties</td><td></td></tr><tr><td>Max Properties</td><td></td></tr><tr><td>ReadOnly</td><td></td></tr><tr><td>WriteOnly</td><td></td></tr><tr><td>Deprecated</td><td></td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Unevaluated properties</td><td></td></tr><tr><td><span>Property names</span></td><td></td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Relationship name</td><td></td></tr><tr><td>Cardinality</td><td></td></tr><tr><td>Examples</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="464f0966-bd83-45e1-aef0-f1a999973946"></a>1.1.2.1.3.2 Field **Activities**

##### 1.1.2.1.3.2.1 **Activities** Tree Diagram

![Hackolade image](/DAH_Markdown/image5.png?raw=true)

##### 1.1.2.1.3.2.2 **Activities** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>Activities</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Anchor</td><td></td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependent required</td><td></td></tr><tr><td>Required</td><td></td></tr><tr><td>Dependent schemas</td><td></td></tr><tr><td>Min Properties</td><td></td></tr><tr><td>Max Properties</td><td></td></tr><tr><td>ReadOnly</td><td></td></tr><tr><td>WriteOnly</td><td></td></tr><tr><td>Deprecated</td><td></td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Unevaluated properties</td><td></td></tr><tr><td><span>Property names</span></td><td></td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Relationship name</td><td></td></tr><tr><td>Cardinality</td><td></td></tr><tr><td>Examples</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="c28f4842-6075-4b91-be89-17540d8001cc"></a>1.1.2.1.3.3 Field **Observations**

##### 1.1.2.1.3.3.1 **Observations** Tree Diagram

![Hackolade image](/DAH_Markdown/image6.png?raw=true)

##### 1.1.2.1.3.3.2 **Observations** Hierarchy

Parent field: **DAH**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#652016de-d9e4-4e1b-a2f8-ee200e5f2835 class="margin-NaN">PainEvaluation</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"><p>Første smertemåling. Hvis der angives 'Andet' i type, er det muligt at indsende yderligere information i 'Note' elementet.</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#9d2d8eb7-ce0a-4845-ae4b-dcacd1f8435b class="margin-NaN">OxygenSaturation</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"><p>Første iltmætningsmåling.</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#9d19b322-1bd3-474b-a39a-31d0634ddffd class="margin-NaN">SystolicBloodPressure</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"><p>Blodtryksmåling (stystolisk).</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#11b91e55-abe8-4329-b663-554399fd3953 class="margin-NaN">GlascowComaScale</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"><p>Første Glascow Coma Scale måling.</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#66175611-a488-4e6c-b467-2e39141dbd13 class="margin-NaN">AVPUScale</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"><p>Første AVPU skala (bevidsthed).</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#c5d6eb05-b61f-4d83-9520-39ff9178cacc class="margin-NaN">Triage</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"><p>Første Triage kategorisering.</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#0d9f7eec-a1c5-4428-ab58-0bf2a6a33e38 class="margin-NaN">OxygenDemand</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"><p>Første iltbehov.</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#3d3c960b-0d07-42a3-8c93-386e79154a50 class="margin-NaN">RespiratoryRate</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"><p>Første respirationsfrekvens måling.</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#7c54fcb1-9eba-42f1-a2f8-41a3bfff2d4e class="margin-NaN">Temperature</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"><p>Første temperatur måling.</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#7a349cb6-2fd9-4e78-87eb-4ec3184e0f5a class="margin-NaN">PulseRate</a></td><td class="no-break-word">Observation</td><td>false</td><td></td><td><div class="docs-markdown"><p>Første pulsmåling.</p></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.1.3.3.3 **Observations** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>Observations</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Anchor</td><td></td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependent required</td><td></td></tr><tr><td>Required</td><td></td></tr><tr><td>Dependent schemas</td><td></td></tr><tr><td>Min Properties</td><td></td></tr><tr><td>Max Properties</td><td></td></tr><tr><td>ReadOnly</td><td></td></tr><tr><td>WriteOnly</td><td></td></tr><tr><td>Deprecated</td><td></td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Unevaluated properties</td><td></td></tr><tr><td><span>Property names</span></td><td></td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Relationship name</td><td></td></tr><tr><td>Cardinality</td><td></td></tr><tr><td>Examples</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

### <a id="652016de-d9e4-4e1b-a2f8-ee200e5f2835"></a>1.1.2.1.3.4 Field **PainEvaluation**

##### 1.1.2.1.3.4.1 **PainEvaluation** Tree Diagram

![Hackolade image](/DAH_Markdown/image7.png?raw=true)

##### 1.1.2.1.3.4.2 **PainEvaluation** Hierarchy

Parent field: **Observations**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#e17cfdfb-b657-41a6-8fb0-e9290f298d59 class="margin-NaN">ResultCode</a></td><td class="no-break-word">ResultCode</td><td>false</td><td></td><td><div class="docs-markdown"><p>Note: Bruges ved anden type af smertescore (ResultCode)</p></div></td><td><div class="docs-markdown"></div></td></tr><tr><td><a href=#bcdc8afd-e8f0-47be-8469-9cd8540f68fb class="margin-NaN">ResultValue</a></td><td class="no-break-word">ResultValue</td><td>false</td><td></td><td><div class="docs-markdown"><p>Værdi for smertescore</p></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.1.3.4.3 **PainEvaluation** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="e17cfdfb-b657-41a6-8fb0-e9290f298d59"></a>1.1.2.1.3.5 Field **ResultCode**

##### 1.1.2.1.3.5.1 **ResultCode** Tree Diagram

![Hackolade image](/DAH_Markdown/image8.png?raw=true)

##### 1.1.2.1.3.5.2 **ResultCode** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="bcdc8afd-e8f0-47be-8469-9cd8540f68fb"></a>1.1.2.1.3.6 Field **ResultValue**

##### 1.1.2.1.3.6.1 **ResultValue** Tree Diagram

![Hackolade image](/DAH_Markdown/image9.png?raw=true)

##### 1.1.2.1.3.6.2 **ResultValue** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="9d2d8eb7-ce0a-4845-ae4b-dcacd1f8435b"></a>1.1.2.1.3.7 Field **OxygenSaturation**

##### 1.1.2.1.3.7.1 **OxygenSaturation** Tree Diagram

![Hackolade image](/DAH_Markdown/image10.png?raw=true)

##### 1.1.2.1.3.7.2 **OxygenSaturation** Hierarchy

Parent field: **Observations**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#2f3675de-5c88-49f8-832d-c35ea10bf2eb class="margin-NaN">ResultValue</a></td><td class="no-break-word">ResultValue</td><td>false</td><td></td><td><div class="docs-markdown"><p>Enhed = %</p></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.1.3.7.3 **OxygenSaturation** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="2f3675de-5c88-49f8-832d-c35ea10bf2eb"></a>1.1.2.1.3.8 Field **ResultValue**

##### 1.1.2.1.3.8.1 **ResultValue** Tree Diagram

![Hackolade image](/DAH_Markdown/image11.png?raw=true)

##### 1.1.2.1.3.8.2 **ResultValue** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="9d19b322-1bd3-474b-a39a-31d0634ddffd"></a>1.1.2.1.3.9 Field **SystolicBloodPressure**

##### 1.1.2.1.3.9.1 **SystolicBloodPressure** Tree Diagram

![Hackolade image](/DAH_Markdown/image12.png?raw=true)

##### 1.1.2.1.3.9.2 **SystolicBloodPressure** Hierarchy

Parent field: **Observations**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#cc391974-580c-4e6a-b538-5a2a1d7ef223 class="margin-NaN">ResultValue</a></td><td class="no-break-word">ResultValue</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.1.3.9.3 **SystolicBloodPressure** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="cc391974-580c-4e6a-b538-5a2a1d7ef223"></a>1.1.2.1.3.10 Field **ResultValue**

##### 1.1.2.1.3.10.1 **ResultValue** Tree Diagram

![Hackolade image](/DAH_Markdown/image13.png?raw=true)

##### 1.1.2.1.3.10.2 **ResultValue** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="11b91e55-abe8-4329-b663-554399fd3953"></a>1.1.2.1.3.11 Field **GlascowComaScale**

##### 1.1.2.1.3.11.1 **GlascowComaScale** Tree Diagram

![Hackolade image](/DAH_Markdown/image14.png?raw=true)

##### 1.1.2.1.3.11.2 **GlascowComaScale** Hierarchy

Parent field: **Observations**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#9924d95a-ccd2-4b0d-be9d-fb4f9a139c30 class="margin-NaN">ResultValue</a></td><td class="no-break-word">ResultValue</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.1.3.11.3 **GlascowComaScale** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="9924d95a-ccd2-4b0d-be9d-fb4f9a139c30"></a>1.1.2.1.3.12 Field **ResultValue**

##### 1.1.2.1.3.12.1 **ResultValue** Tree Diagram

![Hackolade image](/DAH_Markdown/image15.png?raw=true)

##### 1.1.2.1.3.12.2 **ResultValue** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="66175611-a488-4e6c-b467-2e39141dbd13"></a>1.1.2.1.3.13 Field **AVPUScale**

##### 1.1.2.1.3.13.1 **AVPUScale** Tree Diagram

![Hackolade image](/DAH_Markdown/image16.png?raw=true)

##### 1.1.2.1.3.13.2 **AVPUScale** Hierarchy

Parent field: **Observations**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#8fcccd89-e548-4229-84fb-c8f24e0c23ee class="margin-NaN">ResultCode</a></td><td class="no-break-word">ResultCode</td><td>false</td><td></td><td><div class="docs-markdown"><p>A = Alert, V = Verbal, P = Pain, U = Unresponsive</p></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.1.3.13.3 **AVPUScale** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="8fcccd89-e548-4229-84fb-c8f24e0c23ee"></a>1.1.2.1.3.14 Field **ResultCode**

##### 1.1.2.1.3.14.1 **ResultCode** Tree Diagram

![Hackolade image](/DAH_Markdown/image17.png?raw=true)

##### 1.1.2.1.3.14.2 **ResultCode** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="c5d6eb05-b61f-4d83-9520-39ff9178cacc"></a>1.1.2.1.3.15 Field **Triage**

##### 1.1.2.1.3.15.1 **Triage** Tree Diagram

![Hackolade image](/DAH_Markdown/image18.png?raw=true)

##### 1.1.2.1.3.15.2 **Triage** Hierarchy

Parent field: **Observations**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#0d5fcdbc-8fe5-4d54-a6c2-54e5c64ca027 class="margin-NaN">ResultCode</a></td><td class="no-break-word">ResultCode</td><td>false</td><td></td><td><div class="docs-markdown"><p>R = Red, O = Orange, Y = Yellow, G = Green, B = Blue</p></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.1.3.15.3 **Triage** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="0d5fcdbc-8fe5-4d54-a6c2-54e5c64ca027"></a>1.1.2.1.3.16 Field **ResultCode**

##### 1.1.2.1.3.16.1 **ResultCode** Tree Diagram

![Hackolade image](/DAH_Markdown/image19.png?raw=true)

##### 1.1.2.1.3.16.2 **ResultCode** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="0d9f7eec-a1c5-4428-ab58-0bf2a6a33e38"></a>1.1.2.1.3.17 Field **OxygenDemand**

##### 1.1.2.1.3.17.1 **OxygenDemand** Tree Diagram

![Hackolade image](/DAH_Markdown/image20.png?raw=true)

##### 1.1.2.1.3.17.2 **OxygenDemand** Hierarchy

Parent field: **Observations**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#1cf4c2e9-fa57-4bbf-bb47-57691673cbe1 class="margin-NaN">ResultCode</a></td><td class="no-break-word">ResultCode</td><td>false</td><td></td><td><div class="docs-markdown"><p>Y = Yes, N = No</p></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.1.3.17.3 **OxygenDemand** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="1cf4c2e9-fa57-4bbf-bb47-57691673cbe1"></a>1.1.2.1.3.18 Field **ResultCode**

##### 1.1.2.1.3.18.1 **ResultCode** Tree Diagram

![Hackolade image](/DAH_Markdown/image21.png?raw=true)

##### 1.1.2.1.3.18.2 **ResultCode** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="3d3c960b-0d07-42a3-8c93-386e79154a50"></a>1.1.2.1.3.19 Field **RespiratoryRate**

##### 1.1.2.1.3.19.1 **RespiratoryRate** Tree Diagram

![Hackolade image](/DAH_Markdown/image22.png?raw=true)

##### 1.1.2.1.3.19.2 **RespiratoryRate** Hierarchy

Parent field: **Observations**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#c683b39c-1724-4af0-a4ac-fc367b034168 class="margin-NaN">ResultValue</a></td><td class="no-break-word">ResultValue</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.1.3.19.3 **RespiratoryRate** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="c683b39c-1724-4af0-a4ac-fc367b034168"></a>1.1.2.1.3.20 Field **ResultValue**

##### 1.1.2.1.3.20.1 **ResultValue** Tree Diagram

![Hackolade image](/DAH_Markdown/image23.png?raw=true)

##### 1.1.2.1.3.20.2 **ResultValue** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="7c54fcb1-9eba-42f1-a2f8-41a3bfff2d4e"></a>1.1.2.1.3.21 Field **Temperature**

##### 1.1.2.1.3.21.1 **Temperature** Tree Diagram

![Hackolade image](/DAH_Markdown/image24.png?raw=true)

##### 1.1.2.1.3.21.2 **Temperature** Hierarchy

Parent field: **Observations**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#40cbd3d2-2814-402c-9e10-7af41dfce866 class="margin-NaN">ResultValue</a></td><td class="no-break-word">ResultValue</td><td>false</td><td></td><td><div class="docs-markdown"><p>Enhed = grader</p></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.1.3.21.3 **Temperature** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="40cbd3d2-2814-402c-9e10-7af41dfce866"></a>1.1.2.1.3.22 Field **ResultValue**

##### 1.1.2.1.3.22.1 **ResultValue** Tree Diagram

![Hackolade image](/DAH_Markdown/image25.png?raw=true)

##### 1.1.2.1.3.22.2 **ResultValue** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="7a349cb6-2fd9-4e78-87eb-4ec3184e0f5a"></a>1.1.2.1.3.23 Field **PulseRate**

##### 1.1.2.1.3.23.1 **PulseRate** Tree Diagram

![Hackolade image](/DAH_Markdown/image26.png?raw=true)

##### 1.1.2.1.3.23.2 **PulseRate** Hierarchy

Parent field: **Observations**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#36c2391d-6822-43a2-bba6-875f6419c2bc class="margin-NaN">ResultValue</a></td><td class="no-break-word">ResultValue</td><td>false</td><td></td><td><div class="docs-markdown"></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.1.3.23.3 **PulseRate** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="36c2391d-6822-43a2-bba6-875f6419c2bc"></a>1.1.2.1.3.24 Field **ResultValue**

##### 1.1.2.1.3.24.1 **ResultValue** Tree Diagram

![Hackolade image](/DAH_Markdown/image27.png?raw=true)

##### 1.1.2.1.3.24.2 **ResultValue** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="f591215b-960f-4f9d-9263-9613b577d37d"></a>1.1.2.1.3.25 Field **Contacts**

##### 1.1.2.1.3.25.1 **Contacts** Tree Diagram

![Hackolade image](/DAH_Markdown/image28.png?raw=true)

##### 1.1.2.1.3.25.2 **Contacts** Hierarchy

Parent field: **DAH**

Child field(s):

<table class="field-properties-table"><thead><tr><td>Field</td><td>Type</td><td>Req</td><td>Key</td><td>Description</td><td>Comments</td></tr></thead><tbody><tr><td><a href=#20913ec5-c079-4706-958b-74ac9b4f2bf4 class="margin-NaN">NoteType</a></td><td class="no-break-word">Contact</td><td>false</td><td></td><td><div class="docs-markdown"><p>Dato for første afsluttet lægenotat samt notattype (angives i elementet 'Note')</p></div></td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.1.3.25.3 **Contacts** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="20913ec5-c079-4706-958b-74ac9b4f2bf4"></a>1.1.2.1.3.26 Field **NoteType**

##### 1.1.2.1.3.26.1 **NoteType** Tree Diagram

![Hackolade image](/DAH_Markdown/image29.png?raw=true)

##### 1.1.2.1.3.26.2 **NoteType** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody></tbody></table>

### <a id="12a5e029-14ab-41e1-9757-145016696779"></a>1.1.2.1.3.27 Field **Diagnosis**

##### 1.1.2.1.3.27.1 **Diagnosis** Tree Diagram

![Hackolade image](/DAH_Markdown/image30.png?raw=true)

##### 1.1.2.1.3.27.2 **Diagnosis** properties

<table><thead><tr><td>Property</td><td>Value</td></tr></thead><tbody><tr><td>Name</td><td>Diagnosis</td></tr><tr><td>Technical name</td><td></td></tr><tr><td>Activated</td><td>true</td></tr><tr><td>Id</td><td></td></tr><tr><td>Anchor</td><td></td></tr><tr><td>Type</td><td>object</td></tr><tr><td>Description</td><td><div class="docs-markdown"></div></td></tr><tr><td>Dependent required</td><td></td></tr><tr><td>Required</td><td></td></tr><tr><td>Dependent schemas</td><td></td></tr><tr><td>Min Properties</td><td></td></tr><tr><td>Max Properties</td><td></td></tr><tr><td>ReadOnly</td><td></td></tr><tr><td>WriteOnly</td><td></td></tr><tr><td>Deprecated</td><td></td></tr><tr><td>Additional properties</td><td>false</td></tr><tr><td>Unevaluated properties</td><td></td></tr><tr><td><span>Property names</span></td><td></td></tr><tr><td>Foreign collection</td><td></td></tr><tr><td>Foreign field</td><td></td></tr><tr><td>Relationship type</td><td></td></tr><tr><td>Relationship name</td><td></td></tr><tr><td>Cardinality</td><td></td></tr><tr><td>Examples</td><td></td></tr><tr><td>Comments</td><td><div class="docs-markdown"></div></td></tr></tbody></table>

##### 1.1.2.1.4 **DAH** JSON Schema

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
                    "description": "Første smertemåling.\nHvis der angives 'Andet' i type, er det muligt at indsende yderligere information i 'Note' elementet.",
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
                        },
                        "ResultValue": {
                            "type": "number",
                            "description": "Værdi for smertescore"
                        }
                    }
                },
                "OxygenSaturation": {
                    "type": "object",
                    "description": "Første iltmætningsmåling.",
                    "properties": {
                        "ResultValue": {
                            "type": "number",
                            "description": "Enhed = %"
                        }
                    }
                },
                "SystolicBloodPressure": {
                    "type": "object",
                    "description": "Blodtryksmåling (stystolisk).",
                    "properties": {
                        "ResultValue": {
                            "type": "number"
                        }
                    }
                },
                "GlascowComaScale": {
                    "type": "object",
                    "description": "Første Glascow Coma Scale måling.",
                    "properties": {
                        "ResultValue": {
                            "type": "number"
                        }
                    }
                },
                "AVPUScale": {
                    "type": "object",
                    "description": "Første AVPU skala (bevidsthed).",
                    "properties": {
                        "ResultCode": {
                            "type": "string",
                            "description": "A = Alert, \nV = Verbal, \nP = Pain, \nU = Unresponsive",
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
                    "description": "Første Triage kategorisering.",
                    "properties": {
                        "ResultCode": {
                            "type": "string",
                            "description": "R = Red, \nO = Orange, \nY = Yellow, \nG = Green, \nB = Blue",
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
                    "description": "Første iltbehov.",
                    "properties": {
                        "ResultCode": {
                            "type": "string",
                            "description": "Y = Yes,\nN = No",
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
                    "description": "Første respirationsfrekvens måling.",
                    "properties": {
                        "ResultValue": {
                            "type": "number"
                        }
                    }
                },
                "Temperature": {
                    "type": "object",
                    "description": "Første temperatur måling.",
                    "properties": {
                        "ResultValue": {
                            "type": "number",
                            "description": "Enhed = grader"
                        }
                    }
                },
                "PulseRate": {
                    "type": "object",
                    "description": "Første pulsmåling.",
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
                    "type": "object",
                    "description": "Dato for første afsluttet lægenotat samt notattype (angives i elementet 'Note')"
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

##### 1.1.2.1.5 **DAH** JSON data

```
{
    "Courses": {},
    "Activities": {},
    "Observations": {
        "PainEvaluation": {
            "ResultCode": {
                "id": "724981d6-881e-4038-879c-acb05171cf3c",
                "Udfald": "Andet"
            },
            "ResultValue": -26
        },
        "OxygenSaturation": {
            "ResultValue": 35
        },
        "SystolicBloodPressure": {
            "ResultValue": 48
        },
        "GlascowComaScale": {
            "ResultValue": -60
        },
        "AVPUScale": {
            "ResultCode": {
                "id": "1d22a47c-191d-4fd6-b070-38c2ce17da63",
                "Udfald": "U"
            }
        },
        "Triage": {
            "ResultCode": {
                "id": "66356154-9035-41af-b01f-dd1ddd866077",
                "Udfald": "B"
            }
        },
        "OxygenDemand": {
            "ResultCode": {
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