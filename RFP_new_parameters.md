# PROPOSED PARAMETERS FROM RFP TO BE ADDED TO ERA ONTOLOGY
## Problem setting

As part of RNE’s work supporting the IMs digitalising their network statement, RNE has been
contracted to study, define and propose additional infrastructure parameters which would be
needed for RINF to effectively cover the nature of the infrastructure part of the Rail-FacilitiesPortal. After comparison between the parameters of the RFP with those of the RINF Register of
Infrastructure and ERA Vocabulary, RNE proposed the following parameters to enrich ERA Ontology and as inputs for future developments of the RINF application.

## Parameters needed

## id
Internal system facility ID
### General Information

**Number**: 1.1.4.9.19

**XML Name**: id

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/id
* **Values**
  By system.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	By system

* **Regulation**: 
	None

------------------------------------------------------------

## mainDataSource
Main Data Source
### General Information

**Number**: 1.1.8.3.81

**XML Name**: mainDataSource

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/mainDataSource
* **Values**
Free text entry, name of the organisation providing the data.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
  	This property is considered as Type 1 property (General Information).
	Free text entry, name organisation providing the data

* **Regulation**: 
	None

------------------------------------------------------------

## facilityType
Facility type
### General Information

**Number**: 1.1.7.6.94

**XML Name**: facilityType

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/facilityType
* **Values**

| Code | Value |
|------|-------|
| 1    | Passenger station     |
| 2    | Intermodal terminal     |
| 3    | Multifunctional rail terminal     |
| 4    | Public siding     |
| 5    | Private siding     |
| 6    | Marshalling yard     |
| 7    | Storage siding     |
| 8    | Maintenance facility     |
| 9    | Other technical facility     |
| 10   | Relief facility    |
| 11   | Refuelling facility    |
| 12   | Mobile service provider    |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
  	This property is considered as Type 1 property (General Information).
  
  1 = Passenger station - Train station for passenger traffic, equipped with specific facilities for the access of the passengers and providing related services.
  
  2 = Intermodal terminal - Location which provides the space, equipment and operational environment under which the loading units (freight containers, swap bodies, semi-trailers or trailers) transfer takes place.
  
  3 = Multifunctional rail terminal - 
  
  4 = Public siding - Any track(s) within an operational point which is not used for operational routing of a train.

  5 = Private siding - Privately operated pieces of rail infrastructure, connecting loading facilities (normally industry and other manufacturing sites) to the public rail network.
  
  6 = Marshalling yard - Site especially equipped with a number of tracks or other equipment for railway vehicle marshalling (switching) operations. Sometimes also referred to as classification yard.
  
  7 = Storage siding - Sidings specifically dedicated to temporary parking of railway vehicles between two assignments.
  
  8 = Maintenance facility - 
  
  9 = Other technical facility
  
  10 = Relief facility
  
  11 = Refuelling facility
  
  12 = Mobile service provider

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 1 of Reg. 2017/2177) 

------------------------------------------------------------

## facilityName
Facility Name
### General Information

**Number**: 1.1.3.7.25

**XML Name**: facilityName

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/facilityName
* **Values**
Free text entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information). It is a free text entry

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 1 of Reg. 2017/2177) 

------------------------------------------------------------

## areaSeaport
Is the facility located in Sea Port area?
### General Information

**Number**: 1.1.6.2.7

**XML Name**: areaSeaport

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/areaSeaport
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	Mandatory by law (point 2 (g) of Annex II to Dir. 2012/34/EU)

------------------------------------------------------------

## areaInlandPort
Inland Port area.
### General Information

**Number**: 1.1.4.1.92

**XML Name**: areaInlandPort

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/areaInlandPort
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	Mandatory by law (point 2 (g) of Annex II to Dir. 2012/34/EU)

------------------------------------------------------------

## areaFreightVillage
Freight Village area.
### General Information

**Number**: 1.1.8.9.53

**XML Name**: areaFreightVillage

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/areaFreightVillage
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	None

------------------------------------------------------------

## exempted
Facility/operator exempted according Reg. (EU) 2017/2177, Art. 2.
### General Information

**Number**: 1.1.7.5.17

**XML Name**: exempted

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/exempted
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	5-[4]

------------------------------------------------------------

## linkToAdditionalDocuments
Link where additional documents are published.
### General Information

**Number**: 1.1.2.2.82

**XML Name**: linkToAdditionalDocuments

**Deadline**: xx

### Data Format
* **Data Presentation**
*Hyperlink*
* **Taxonomy Reference**
http://data.europa.eu/949/linkToAdditionalDocuments
* **Values**
Free text entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	None

------------------------------------------------------------

## purposeOfSfDeclaration
Purpose of this SF description.
### General Information

**Number**: 1.1.6.7.30

**XML Name**: purposeOfSfDeclaration

**Deadline**: xx

### Data Format
* **Data Presentation**

* **Taxonomy Reference**
http://data.europa.eu/949/purposeOfSfDeclaration
* **Values**
Link/text file attachment.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	Mandatory by law (Art. 3 (3) and Art. 4 of Reg. 2017/2177)

------------------------------------------------------------

## briefPresentation
Brief presentation of the SF.
### General Information

**Number**: 1.1.2.9.28

**XML Name**: briefPresentation

**Deadline**: xx

### Data Format
* **Data Presentation**

* **Taxonomy Reference**
http://data.europa.eu/949/briefPresentation
* **Values**
Link/text file attachment.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	None

------------------------------------------------------------

## operatorName
Facility operator (name).
### General Information

**Number**: 1.1.2.6.21

**XML Name**: operatorName

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/operatorName
* **Values**
Free text entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	Mandatory by law (Art. 3 (12) of Dir. 2012/34)

------------------------------------------------------------

## operator
Facility operator (RICS).
### General Information

**Number**: 1.1.5.7.12

**XML Name**: operator

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/operator
* **Values**
Free text entry, enter SF operator's UIC company code RICS

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	None

------------------------------------------------------------

## operatorType
Type of operator.
### General Information

**Number**: 1.1.9.5.62

**XML Name**: operatorType

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/operatorType
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Incumbent railway undertaking and companies related to it     |
| 2    | Infrastructure manager     |
| 3    | Railway undertaking     |
| 4    | Integrated company     |
| 5    | Government     |
| 6    | Other     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	Mandatory by law but limited to public or private entity only (Art. 3 (12) of Dir. 2012/34). 


------------------------------------------------------------

## operatorOtherType
Other type of operator.
### General Information

**Number**: 1.1.7.7.26

**XML Name**: operatorOtherType

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/operatorOtherType
* **Values**
Free text entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	None

------------------------------------------------------------

## operatorContact
Contact person.
### General Information

**Number**: 1.1.4.1.99

**XML Name**: operatorContact

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/operatorContact
* **Values**
Free text entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	Mandatory by law (Art. 4 (2)(b) of Reg. 2017/2177)

------------------------------------------------------------

## operatorPhone
Phone.
### General Information

**Number**: 1.1.1.8.44

**XML Name**: operatorPhone

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/operatorPhone
* **Values**
Free text entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	Mandatory by law (Art. 4 (2)(b) of Reg. 2017/2177)

------------------------------------------------------------

## operatorFax
Fax.
### General Information

**Number**: 1.1.8.9.13

**XML Name**: operatorFax

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/operatorFax
* **Values**
Free text entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	If any - mandatory by law (Art. 4 (2)(b) of Reg. 2017/2177) 

------------------------------------------------------------

## operatorEmail
Email.
### General Information

**Number**: 1.1.3.7.86

**XML Name**: operatorEmail

**Deadline**: xx

### Data Format
* **Data Presentation**
*Hyperlink*
* **Taxonomy Reference**
http://data.europa.eu/949/operatorEmail
* **Values**
Free text entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	Mandatory by law (Art. 4 (2)(b) of Reg. 2017/2177)

------------------------------------------------------------

## operatorWebsite
Website.
### General Information

**Number**: 1.1.6.5.42

**XML Name**: operatorWebsite

**Deadline**: xx

### Data Format
* **Data Presentation**
*Hyperlink*
* **Taxonomy Reference**
http://data.europa.eu/949/operatorWebsite
* **Values**
Free text entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	Mandatory by law (Art. 4 (2)(b) of Reg. 2017/2177)

------------------------------------------------------------

## facilityOwner
Facility owner (name).
### General Information

**Number**: 1.1.9.3.64

**XML Name**: facilityOwner

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/facilityOwner
* **Values**
Free text entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	None

------------------------------------------------------------

## ownerType
Type of owner.
### General Information

**Number**: 1.1.4.5.98

**XML Name**: ownerType

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/ownerType
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Incumbent railway undertaking and companies related to it     |
| 2    | Infrastructure manager     |
| 3    | Railway undertaking     |
| 4    | Integrated company     |
| 5    | Government     |
| 6    | Other     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	None

------------------------------------------------------------

## ownerOtherType
Other type of owner.
### General Information

**Number**: 1.1.4.6.17

**XML Name**: ownerOtherType

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/ownerOtherType
* **Values**
Free text entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	None

------------------------------------------------------------

## operatorsRelation
Explanation of the relation between several operators, if relevant.
### General Information

**Number**: 1.1.9.6.37

**XML Name**: operatorsRelation

**Deadline**: xx

### Data Format
* **Data Presentation**

* **Taxonomy Reference**
http://data.europa.eu/949/operatorsRelation
* **Values**
Link/text file attachment.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	None

------------------------------------------------------------

## sfDataValidUntil
SF data is valid until.
### General Information

**Number**: 1.1.6.1.75

**XML Name**: sfDataValidUntil

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/sfDataValidUntil
* **Values**
Free date entry or selection from calendar    YYYY-MM-DD

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	Mandatory by law (Art. 5 of Reg. 2017/2177)

------------------------------------------------------------

## sfDataUpdateProcedure
Describe how the SF data is updated.
### General Information

**Number**: 1.1.7.8.59

**XML Name**: sfDataUpdateProcedure

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/sfDataUpdateProcedure
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | The data is updated yearly at the time of the Network Statement publication, unless changes in its content require extraordinary updates     |
| 2    | The data is updated yearly at month [Date], unless changes in its content require extraordinary updates     |
| 3    | The data is updated when necessary     |
  
### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	Mandatory by law (Art. 5 of Reg. 2017/2177)

------------------------------------------------------------

## dateForUpdate
Date for update.
### General Information

**Number**: 1.1.7.9.38

**XML Name**: dateForUpdate

**Deadline**: xx

### Data Format
* **Data Presentation**
*Datetime*
* **Taxonomy Reference**
http://data.europa.eu/949/dateForUpdate
* **Values**
Free date entry or selection from calendar

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	Mandatory by law (Art. 5 of Reg. 2017/2177)
------------------------------------------------------------

## applyCompliance
Data provision according to Reg. (EU) 2017/2177.
### General Information

**Number**: 1.1.9.5.2

**XML Name**: applyCompliance

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/applyCompliance
* **Values**
Button "Apply for compliance with regulation 2017/2177"

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	None

------------------------------------------------------------

## complianceConfirmed
Data provided according to Reg. (EU) 2017/2177.
### General Information

**Number**: 1.1.8.8.42

**XML Name**: complianceConfirmed

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/complianceConfirmed
* **Values**
By system, if compliance check was successful

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	NOTE: If the SFO has chosen the RFP as a first option for fulfilling its obligation under Art. 5 of Reg. 2017/2177, there are no exceptions envisaged in the law for not providing the full set of data (see e.g., Art. 31(10) and point 6 of Annex IV to Directive 2012/34/EU, recital 7 of Reg. 2017/2177, etc.)  

------------------------------------------------------------

## locomotiveCleaning
Locomotive cleaning.
### General Information

**Number**: 1.1.9.5.53

**XML Name**: locomotiveCleaning

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/locomotiveCleaning
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## wagonCleaning
Wagon cleaning.
### General Information

**Number**: 1.1.5.1.95

**XML Name**: wagonCleaning

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/wagonCleaning
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 1 of Reg. 2017/2177) 

------------------------------------------------------------

## locomotiveParking
Locomotive parking.
### General Information

**Number**: 1.1.3.3.6

**XML Name**: locomotiveParking

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/locomotiveParking
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## wagonParking
Wagon parking.
### General Information

**Number**: 1.1.4.4.52

**XML Name**: wagonParking

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/wagonParking
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## locomotiveRepairMaintenanceLight
Locomotive repair/maintenance (light maintenance).
### General Information

**Number**: 1.1.8.6.45

**XML Name**: locomotiveRepairMaintenanceLight

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/locomotiveRepairMaintenanceLight
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## locomotiveRepairMaintenanceHeavy
Locomotive repair/maintenance (heavy maintenance).
### General Information

**Number**: 1.1.7.1.6

**XML Name**: locomotiveRepairMaintenanceHeavy

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/locomotiveRepairMaintenanceHeavy
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 


------------------------------------------------------------

## wagonRepairMaintenanceLight
Wagon repair/maintenance (light maintenance).
### General Information

**Number**: 1.1.4.6.92

**XML Name**: wagonRepairMaintenanceLight

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/wagonRepairMaintenanceLight
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## wagonRepairMaintenanceHeavy
Wagon repair/maintenance (heavy maintenance).
### General Information

**Number**: 1.1.2.3.10

**XML Name**: wagonRepairMaintenanceHeavy

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/wagonRepairMaintenanceHeavy
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## technicalInspectionOfRollingStock
Technical inspection of rolling stock.
### General Information

**Number**: 1.1.5.4.89

**XML Name**: technicalInspectionOfRollingStock

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/technicalInspectionOfRollingStock
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## refuelling
Refuelling.
### General Information

**Number**: 1.1.3.9.47

**XML Name**: refuelling

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/refuelling
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## shunting
Shunting.
### General Information

**Number**: 1.1.3.5.84

**XML Name**: shunting

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/shunting
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## provisionEmergencyEquipment
Provision of emergency equipment.
### General Information

**Number**: 1.1.2.1.69

**XML Name**: provisionEmergencyEquipment

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/provisionEmergencyEquipment
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## securityServices
Security services.
### General Information

**Number**: 1.1.2.1.31

**XML Name**: securityServices

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/securityServices
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## tractionCurrent
Traction current (extra charges).
### General Information

**Number**: 1.1.4.6.37

**XML Name**: tractionCurrent

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/tractionCurrent
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## accessToTelecommunicationNetworks
Access to telecommunication networks.
### General Information

**Number**: 1.1.3.8.87

**XML Name**: accessToTelecommunicationNetworks

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/accessToTelecommunicationNetworks
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## provisionSupplementaryInformation
Provision of supplementary information.
### General Information

**Number**: 1.1.6.2.4

**XML Name**: provisionSupplementaryInformation

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/provisionSupplementaryInformation
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## otherServices
Other services.
### General Information

**Number**: 1.1.9.4.22

**XML Name**: otherServices

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/otherServices
* **Values**
Free text entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## descriptionOfServices
Description of services.
### General Information

**Number**: 1.1.4.6.35

**XML Name**: descriptionOfServices

**Deadline**: xx

### Data Format
* **Data Presentation**

* **Taxonomy Reference**
http://data.europa.eu/949/descriptionOfServices
* **Values**
Link/text file attachment.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## timetableServiceTrains
Timetable for service trains.
### General Information

**Number**: 1.1.9.1.67

**XML Name**: timetableServiceTrains

**Deadline**: xx

### Data Format
* **Data Presentation**

* **Taxonomy Reference**
http://data.europa.eu/949/timetableServiceTrains
* **Values**
Link/text file attachment.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## facilityCertificates
Facility certificates.
### General Information

**Number**: 1.1.4.6.44

**XML Name**: facilityCertificates

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/facilityCertificates
* **Values**
Free text entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## loadingUnloadingTranshipment
Loading/unloading/transhipment.
### General Information

**Number**: 1.1.7.5.89

**XML Name**: loadingUnloadingTranshipment

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/loadingUnloadingTranshipment
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## loadingUnitCleaning
Loading unit cleaning.
### General Information

**Number**: 1.1.9.6.74

**XML Name**: loadingUnitCleaning

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/loadingUnitCleaning
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## loadingUnitFumigationDisinfection
Loading unit fumigation, disinfection.
### General Information

**Number**: 1.1.4.9.82

**XML Name**: loadingUnitFumigationDisinfection

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/loadingUnitFumigationDisinfection
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## loadingUnitRepairMaintenance
Loading unit repair/maintenance.
### General Information

**Number**: 1.1.2.4.22

**XML Name**: loadingUnitRepairMaintenance

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/loadingUnitRepairMaintenance
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## loadingUnitVentilation
Loading unit ventilation.
### General Information

**Number**: 1.1.6.2.82

**XML Name**: loadingUnitVentilation

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/loadingUnitVentilation
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## orderPickingWarehousing
Order picking, warehousing.
### General Information

**Number**: 1.1.4.8.65

**XML Name**: orderPickingWarehousing

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/orderPickingWarehousing
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## storageContainersGeneralCargo
Storage of containers/general cargo.
### General Information

**Number**: 1.1.7.1.4

**XML Name**: storageContainersGeneralCargo

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/storageContainersGeneralCargo
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## storageDangerousGoods
Storage of dangerous goods.
### General Information

**Number**: 1.1.8.9.8

**XML Name**: storageDangerousGoods

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/storageDangerousGoods
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## storageRidClasses
RID classes.
### General Information

**Number**: 1.1.4.2.6

**XML Name**: storageRidClasses

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/storageRidClasses
* **Values**
Free text entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## storageHandlingReefers
Storage and handling of Reefers.
### General Information

**Number**: 1.1.3.3.22

**XML Name**: storageHandlingReefers

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/storageHandlingReefers
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## stuffingStripping
Stuffing/Stripping.
### General Information

**Number**: 1.1.4.6.90

**XML Name**: stuffingStripping

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/stuffingStripping
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## containerLashing
Container lashing.
### General Information

**Number**: 1.1.2.9.18

**XML Name**: containerLashing

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/containerLashing
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## weighingWagonsLoadingUnits
Weighing of wagons/Loading units.
### General Information

**Number**: 1.1.5.9.34

**XML Name**: weighingWagonsLoadingUnits

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/weighingWagonsLoadingUnits
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## containerSalesLeasing
Container sales/leasing.
### General Information

**Number**: 1.1.4.3.56

**XML Name**: containerSalesLeasing

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/containerSalesLeasing
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## customsClearance
Customs clearance.
### General Information

**Number**: 1.1.3.2.37

**XML Name**: customsClearance

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/customsClearance
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## trucking
Trucking (Organisation Pre-/End-haulage).
### General Information

**Number**: 1.1.6.3.49

**XML Name**: trucking

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/trucking
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## tailormadeContractsDangerousGoods
Tailor-made contracts for control of transport of dangerous goods.
### General Information

**Number**: 1.1.1.8.21

**XML Name**: tailormadeContractsDangerousGoods

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/tailormadeContractsDangerousGoods
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## tailormadeContractsAbnormalTrains
Tailor-made contracts for assistance in running abnormal trains.
### General Information

**Number**: 1.1.8.9.52

**XML Name**: tailormadeContractsAbnormalTrains

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/tailormadeContractsAbnormalTrains
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## trainBoardingDeboarding
Train boarding and deboarding.
### General Information

**Number**: 1.1.5.7.99

**XML Name**: trainBoardingDeboarding

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/trainBoardingDeboarding
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## ticketingServices
Ticketing services.
### General Information

**Number**: 1.1.8.5.94

**XML Name**: ticketingServices

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/ticketingServices
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## assistanceForPersonsWithReducedMobility
Assistance for persons with reduced mobility.
### General Information

**Number**: 1.1.8.2.44

**XML Name**: assistanceForPersonsWithReducedMobility

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/assistanceForPersonsWithReducedMobility
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## lostAndFound
Lost & Found.
### General Information

**Number**: 1.1.7.3.45

**XML Name**: lostAndFound

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/lostAndFound
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## luggageStoring
Luggage storing.
### General Information

**Number**: 1.1.4.1.32

**XML Name**: luggageStoring

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/luggageStoring
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## waitingAreasAndWeaterProtection
Waiting areas and weather protection.
### General Information

**Number**: 1.1.3.1.91

**XML Name**: waitingAreasAndWeaterProtection

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/waitingAreasAndWeaterProtection
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## iceProtection
Ice protection
### General Information

**Number**: 1.1.8.9.95

**XML Name**: iceProtection

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/iceProtection
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## preHeatingPreCooling
Pre-heating and pre-cooling of passenger trains.
### General Information

**Number**: 1.1.2.1.85

**XML Name**: preHeatingPreCooling

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/preHeatingPreCooling
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## sewageDisposalWaterSupply
Sewage disposal and water supply.
### General Information

**Number**: 1.1.6.7.54

**XML Name**: sewageDisposalWaterSupply

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/sewageDisposalWaterSupply
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## useOfMotorailFacilities
Use of motorail facilities.
### General Information

**Number**: 1.1.8.3.31

**XML Name**: useOfMotorailFacilities

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/useOfMotorailFacilities
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Basic service     |
| 2    | Additional service     |
| 3    | Ancillary service     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 4 of Reg. 2017/2177) 

------------------------------------------------------------

## longitude
Longitude.
### General Information

**Number**: 1.1.4.7.54

**XML Name**: longitude

**Deadline**: xx

### Data Format
* **Data Presentation**
*Real*
* **Taxonomy Reference**
http://data.europa.eu/949/longitude
* **Values**
Free entry or calculation from post adress.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## latitude
Latitude.
### General Information

**Number**: 1.1.6.9.39

**XML Name**: latitude

**Deadline**: xx

### Data Format
* **Data Presentation**
*Real*
* **Taxonomy Reference**
http://data.europa.eu/949/latitude
* **Values**
Free entry or calculation from post adress.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## crdPrimaryLocation
CRD primary  location ID.
### General Information

**Number**: 1.1.6.9.20

**XML Name**: crdPrimaryLocation

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/crdPrimaryLocation
* **Values**
Selection list with search possibility:

	+ all primary location IDs
	+ +associated location name

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	2

------------------------------------------------------------

## crdSubsidiaryLocation
CRD subsidiary location ID.
### General Information

**Number**: 1.1.8.9.74

**XML Name**: crdSubsidiaryLocation

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/crdSubsidiaryLocation
* **Values**
Restricted selection list with search possibility:

	+ all subsidiary location IDs for the selected primary location
	+ +associated location name

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## rinfOperationalPoint
RINF operational point.
### General Information

**Number**: 1.1.5.4.50

**XML Name**: rinfOperationalPoint

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/rinfOperationalPoint
* **Values**
Selection list with search possibility:

	+ all RINF IDs
	+ +associated location name

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	2

------------------------------------------------------------

## facilityStreet
Street, house number
### General Information

**Number**: 1.1.4.6.35

**XML Name**: facilityStreet

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/facilityStreet
* **Values**
Free text entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) of Reg. 2017/2177) 

------------------------------------------------------------

## facilityZip
ZIP code.
### General Information

**Number**: 1.1.2.5.72

**XML Name**: facilityZip

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/facilityZip
* **Values**
Free text entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) of Reg. 2017/2177) 

------------------------------------------------------------

## facilityTown
Town.
### General Information

**Number**: 1.1.9.6.43

**XML Name**: facilityTown

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/facilityTown
* **Values**
Free text entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) of Reg. 2017/2177) 

------------------------------------------------------------

## facilityCountry
Country.
### General Information

**Number**: 1.1.2.5.43

**XML Name**: facilityCountry

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/facilityCountry
* **Values**
Free text entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) of Reg. 2017/2177) 

------------------------------------------------------------

## connectionToPublicRailNetwork
Connection of facility to public rail network.
### General Information

**Number**: 1.1.4.1.54

**XML Name**: connectionToPublicRailNetwork

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/connectionToPublicRailNetwork
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Direct connection of facility to public rail network     |
| 2    | Connection of facility to public rail network via access line      |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## facilityLocatedOnRfc
Facility located on RFC.
### General Information

**Number**: 1.1.4.3.45

**XML Name**: facilityLocatedOnRfc

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/facilityLocatedOnRfc
* **Values**

| Code | Value |
|------|-------|
| 0    | not located on any RFC     |
| 1    | located on RFC 1     |
| 2    | located on RFC 2     |
| 3    | located on RFC 3     |
| 4    | located on RFC 4     |
| 5    | located on RFC 5     |
| 6    | located on RFC 6     |
| 7    | located on RFC 7     |
| 8    | located on RFC 8     |
| 9    | located on RFC 9     |
| 10    | located on RFC 10     |
| 11    | located on RFC 11     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## roadAccessConditions
Conditions for road access.
### General Information

**Number**: 1.1.9.6.76

**XML Name**: roadAccessConditions

**Deadline**: xx

### Data Format
* **Data Presentation**

* **Taxonomy Reference**
http://data.europa.eu/949/roadAccessConditions
* **Values**
Link/text file attachment.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## operationStatus
Facility operation status.
### General Information

**Number**: 1.1.7.2.62

**XML Name**: operationStatus

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/operationStatus
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | In operation     |
| 2    | Currently out of operation     |
| 3    | Planned     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## openingTimes
Facility opening times.
### General Information

**Number**: 1.1.3.5.81

**XML Name**: openingTimes

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/openingTimes
* **Values**
Free text entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) of Reg. 2017/2177) 

------------------------------------------------------------

## openOnDemand
Facility open on demand.
### General Information

**Number**: 1.1.7.6.51

**XML Name**: openOnDemand

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/openOnDemand
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) of Reg. 2017/2177) 

------------------------------------------------------------

## totalNumberOfTracks
All facility tracks: number.
### General Information

**Number**: 1.1.8.6.33

**XML Name**: totalNumberOfTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/totalNumberOfTracks
* **Values**
* 
Calculation, to sum up:
+ [totalNumberOfPlatformTracks]
+ [totalNumberOfTranshipmentTracks]
+ [totalNumberOfStorageTracks]
+ [totalNumberOfShuntingTracks]
+ [totalNumberOfInboundOutboundTracks]
+ [totalNumberOfAllocationTracks]
+ [totalNumberOfOtherTracks]

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## totalNumberOfPlatformTracks
Platform tracks: number.
### General Information

**Number**: 1.1.3.6.63

**XML Name**: totalNumberOfPlatformTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/totalNumberOfPlatformTracks
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## thereofElectrifiedPlatformTracks
Platform tracks: thereof electrified.
### General Information

**Number**: 1.1.1.6.16

**XML Name**: thereofElectrifiedPlatformTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/thereofElectrifiedPlatformTracks
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | None     |
| 1    | Some     |
| 2    | All     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## maxUsableLengthPlatformTracks
Platform tracks: max. usable length [m]
### General Information

**Number**: 1.1.5.8.79

**XML Name**: maxUsableLengthPlatformTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/maxUsableLengthPlatformTracks
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## totalNumberOfTranshipmentTracks
Transhipment tracks: number.
### General Information

**Number**: 1.1.2.8.56

**XML Name**: totalNumberOfTranshipmentTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/totalNumberOfTranshipmentTracks
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## thereofElectrifiedTranshipmentTracks
Transhipment tracks: thereof electrified.
### General Information

**Number**: 1.1.4.6.35

**XML Name**: thereofElectrifiedTranshipmentTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/thereofElectrifiedTranshipmentTracks
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | None     |
| 1    | Some     |
| 2    | All     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## maxUsableLengthTranshipmentTracks
Transhipment tracks: max. usable length [m].
### General Information

**Number**: 1.1.4.5.38

**XML Name**: maxUsableLengthTranshipmentTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/maxUsableLengthTranshipmentTracks
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## totalNumberOfStorageTracks
Storage tracks: number.
### General Information

**Number**: 1.1.9.9.87

**XML Name**: totalNumberOfStorageTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/totalNumberOfStorageTracks
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## thereofElectrifiedStorageTracks
Storage tracks: thereof electrified.
### General Information

**Number**: 1.1.3.1.91

**XML Name**: thereofElectrifiedStorageTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/thereofElectrifiedStorageTracks
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | None     |
| 1    | Some     |
| 2    | All     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## maxUsableLengthStorageTracks
Storage tracks: max. usable length [m].
### General Information

**Number**: 1.1.6.1.20

**XML Name**: maxUsableLengthStorageTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/maxUsableLengthStorageTracks
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## totalNumberOfShuntingTracks
Shunting tracks: number.
### General Information

**Number**: 1.1.2.3.27

**XML Name**: totalNumberOfShuntingTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/totalNumberOfShuntingTracks
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## thereofElectrifiedShuntingTracks
Shunting tracks: thereof electrified.
### General Information

**Number**: 1.1.1.3.35

**XML Name**: thereofElectrifiedShuntingTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/thereofElectrifiedShuntingTracks
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | None     |
| 1    | Some     |
| 2    | All     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## maxUsableLengthShuntingTracks
Shunting tracks: max. usable length [m]
### General Information

**Number**: 1.1.3.8.63

**XML Name**: maxUsableLengthShuntingTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/maxUsableLengthShuntingTracks
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## totalNumberOfInboundOutboundTracks
Inbound + Outbound tracks: number.
### General Information

**Number**: 1.1.3.7.38

**XML Name**: totalNumberOfInboundOutboundTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/totalNumberOfInboundOutboundTracks
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## thereofElectrifiedInboundOutboundTracks
Inbound + Outbound tracks: thereof electrified.
### General Information

**Number**: 1.1.5.1.56

**XML Name**: thereofElectrifiedInboundOutboundTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/thereofElectrifiedInboundOutboundTracks
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | None     |
| 1    | Some     |
| 2    | All     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## maxUsableLengthInboundOutboundTracks
Inbound + Outbound tracks: max. usable length [m].
### General Information

**Number**: 1.1.9.4.38

**XML Name**: maxUsableLengthInboundOutboundTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/maxUsableLengthInboundOutboundTracks
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## totalNumberOfAllocationTracks
Allocation tracks: number.
### General Information

**Number**: 1.1.9.2.51

**XML Name**: totalNumberOfAllocationTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/totalNumberOfAllocationTracks
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## thereofElectrifiedAllocationTracks
Allocation tracks: thereof electrified.
### General Information

**Number**: 1.1.6.2.22

**XML Name**: thereofElectrifiedAllocationTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/thereofElectrifiedAllocationTracks
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | None     |
| 1    | Some     |
| 2    | All     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## maxUsableLengthAllocationTracks
Allocation tracks: max. usable length [m].
### General Information

**Number**: 1.1.3.2.96

**XML Name**: maxUsableLengthAllocationTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/maxUsableLengthAllocationTracks
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## totalNumberOfOtherTracks
Other tracks: number.
### General Information

**Number**: 1.1.6.6.57

**XML Name**: totalNumberOfOtherTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/totalNumberOfOtherTracks
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## thereofElectrifiedOtherTracks
Other tracks: thereof electrified.
### General Information

**Number**: 1.1.3.2.49

**XML Name**: thereofElectrifiedOtherTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/thereofElectrifiedOtherTracks
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | None     |
| 1    | Some     |
| 2    | All     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## maxUsableLengthOtherTracks
Other tracks: max. usable length [m].
### General Information

**Number**: 1.1.3.7.16

**XML Name**: maxUsableLengthOtherTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/maxUsableLengthOtherTracks
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## descriptionOfTechnicalCharacteristics
Description of the technical characteristics of the facility.
### General Information

**Number**: 1.1.9.6.34

**XML Name**: descriptionOfTechnicalCharacteristics

**Deadline**: xx

### Data Format
* **Data Presentation**

* **Taxonomy Reference**
http://data.europa.eu/949/descriptionOfTechnicalCharacteristics
* **Values**
Link/text file attachment.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## technicalMap
Technical map.
### General Information

**Number**: 1.1.7.4.94

**XML Name**: technicalMap

**Deadline**: xx

### Data Format
* **Data Presentation**

* **Taxonomy Reference**
http://data.europa.eu/949/technicalMap
* **Values**
Link/text file attachment.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## brakeTestFacility
Brake test facility.
### General Information

**Number**: 1.1.8.1.56

**XML Name**: brakeTestFacility

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/brakeTestFacility
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## compressedAirSupply
Compressed air supply.
### General Information

**Number**: 1.1.1.2.64

**XML Name**: compressedAirSupply

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/compressedAirSupply
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## turntable
Turntable.
### General Information

**Number**: 1.1.9.5.8

**XML Name**: turntable

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/turntable
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## locomotiveWashingCleaning
Washing/cleaning equipment for locomotives.
### General Information

**Number**: 1.1.4.7.31

**XML Name**: locomotiveWashingCleaning

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/locomotiveWashingCleaning
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## wagonWashingCleaning
Washing/cleaning equipment for  wagons.
### General Information

**Number**: 1.1.6.7.74

**XML Name**: wagonWashingCleaning

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/wagonWashingCleaning
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## loadingUnitWashingCleaning
Washing/cleaning equipment for loading units.
### General Information

**Number**: 1.1.3.4.84

**XML Name**: loadingUnitWashingCleaning

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/loadingUnitWashingCleaning
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## maintenanceShopLight
Maintenance shop (light maintenance).
### General Information

**Number**: 1.1.3.7.89

**XML Name**: maintenanceShopLight

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/maintenanceShopLight
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## maintenanceShopHeavy
Maintenance shop (heavy maintenance).
### General Information

**Number**: 1.1.5.6.2

**XML Name**: maintenanceShopHeavy

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/maintenanceShopHeavy
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## otherEquipment
Other Equipment.
### General Information

**Number**: 1.1.1.4.48

**XML Name**: otherEquipment

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/otherEquipment
* **Values**
Free text entry. Multiple entries must be possible.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## descriptionTechnicalEquipment
Description of technical equipment (particularly washing, maintenance).
### General Information

**Number**: 1.1.2.7.43

**XML Name**: descriptionTechnicalEquipment

**Deadline**: xx

### Data Format
* **Data Presentation**

* **Taxonomy Reference**
http://data.europa.eu/949/descriptionTechnicalEquipment
* **Values**
Link/text file attachment.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## numberOfGantryCranes
Number of (gantry) cranes.
### General Information

**Number**: 1.1.5.6.83

**XML Name**: numberOfGantryCranes

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/numberOfGantryCranes
* **Values**
Free data input.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## numberOfMobileCranes
Number of mobile cranes.
### General Information

**Number**: 1.1.3.8.71

**XML Name**: numberOfMobileCranes

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/numberOfMobileCranes
* **Values**
Free data input.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## horizontalTranshipmentSystems
Horizontal transhipment systems.
### General Information

**Number**: 1.1.3.9.47

**XML Name**: horizontalTranshipmentSystems

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/horizontalTranshipmentSystems
* **Values**

| Code | Value |
|------|-------|
| 0    | none     |
| 1    | CargoBeamer     |
| 2    | ISU     |
| 3    | Modalohr     |
| 4    | NIKRASA     |
| 5    | other     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## headRamp
Head ramp.
### General Information

**Number**: 1.1.8.5.84

**XML Name**: headRamp

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/headRamp
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## sideRamp
Side ramp.
### General Information

**Number**: 1.1.5.8.94

**XML Name**: sideRamp

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/sideRamp
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## loadingLane
Loading Lane.
### General Information

**Number**: 1.1.7.2.97

**XML Name**: loadingLane

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/loadingLane
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## hump
Hump.
### General Information

**Number**: 1.1.8.8.15

**XML Name**: hump

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/hump
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## trackScale
Trackscale.
### General Information

**Number**: 1.1.2.5.78

**XML Name**: trackScale

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/trackScale
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## opticalCharacterRecognition
Optical character recognition.
### General Information

**Number**: 1.1.5.7.59

**XML Name**: opticalCharacterRecognition

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/opticalCharacterRecognition
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## numberOfReeferConnections
Number of reefer connections.
### General Information

**Number**: 1.1.3.2.16

**XML Name**: numberOfReeferConnections

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/numberOfReeferConnections
* **Values**
Free data input.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## storageAreaM2
Storage area [m²].
### General Information

**Number**: 1.1.2.9.22

**XML Name**: storageAreaM2

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/storageAreaM2
* **Values**
Free data input.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## storageAreaTeu
Storage area [TEU].
### General Information

**Number**: 1.1.8.8.5

**XML Name**: storageAreaTeu

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/storageAreaTeu
* **Values**
Free data input.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## emptyContainerDepot
Empty container depot.
### General Information

**Number**: 1.1.2.5.88

**XML Name**: emptyContainerDepot

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/emptyContainerDepot
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## numberOfPlatforms
Number of platforms.
### General Information

**Number**: 1.1.2.1.90

**XML Name**: numberOfPlatforms

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/numberOfPlatforms
* **Values**
Free data input.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## maxPlatformLength
Max. platform length [m].
### General Information

**Number**: 1.1.9.6.50

**XML Name**: maxPlatformLength

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/maxPlatformLength
* **Values**
Free data input.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## maxPlatformHeight
Max. platform height [mm].
### General Information

**Number**: 1.1.7.5.37

**XML Name**: maxPlatformHeight

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/maxPlatformHeight
* **Values**
Free data input.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## minPlatformHeight
Min. platform height [mm].
### General Information

**Number**: 1.1.6.1.44

**XML Name**: minPlatformHeight

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/minPlatformHeight
* **Values**
Free data input.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## escalatorRampForPlatformAccess
Escalator/ramp for platform access.
### General Information

**Number**: 1.1.2.3.74

**XML Name**: escalatorRampForPlatformAccess

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/escalatorRampForPlatformAccess
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## weatherProtectionForPassengers
Weather protection for passengers.
### General Information

**Number**: 1.1.6.4.56

**XML Name**: weatherProtectionForPassengers

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/weatherProtectionForPassengers
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(1)(a) and (c) of Reg. 2017/2177) 

------------------------------------------------------------

## plannedChangesTechnicalCharacteristics
Planned changes in technical characteristics.
### General Information

**Number**: 1.1.4.3.75

**XML Name**: plannedChangesTechnicalCharacteristics

**Deadline**: xx

### Data Format
* **Data Presentation**

* **Taxonomy Reference**
http://data.europa.eu/949/plannedChangesTechnicalCharacteristics
* **Values**
Link/text file attachment.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(l) of Reg. 2017/2177) 

------------------------------------------------------------

## informationOnCharges
Information on charges.
### General Information

**Number**: 1.1.4.2.55

**XML Name**: informationOnCharges

**Deadline**: xx

### Data Format
* **Data Presentation**

* **Taxonomy Reference**
http://data.europa.eu/949/informationOnCharges
* **Values**
Link/text file attachment.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 4 property (Charges).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(m) of Reg. 2017/2177) 

------------------------------------------------------------

## informationOnDiscounts
Information on discounts.
### General Information

**Number**: 1.1.1.8.31

**XML Name**: informationOnDiscounts

**Deadline**: xx

### Data Format
* **Data Presentation**

* **Taxonomy Reference**
http://data.europa.eu/949/informationOnDiscounts
* **Values**
Link/text file attachment.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 4 property (Charges).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(n) of Reg. 2017/2177) 

------------------------------------------------------------

## publicAccessibility
Public accessibility.
### General Information

**Number**: 1.1.8.3.56

**XML Name**: publicAccessibility

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/publicAccessibility
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Open access for all market bodies (RU, forwarder, logistics provider...)     |
| 2    | Public access under special conditions     |
| 3    | Access limited to owner/operator     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(f) of Reg. 2017/2177) 

------------------------------------------------------------

## legalRequirements
Legal requirements.
### General Information

**Number**: 1.1.4.8.22

**XML Name**: legalRequirements

**Deadline**: xx

### Data Format
* **Data Presentation**

* **Taxonomy Reference**
http://data.europa.eu/949/legalRequirements
* **Values**
Link/text file attachment.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(i) of Reg. 2017/2177) 

------------------------------------------------------------

## electrifiedRailAccessPossible
Electrified rail access possible.
### General Information

**Number**: 1.1.8.5.43

**XML Name**: electrifiedRailAccessPossible

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/electrifiedRailAccessPossible
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## maxPermittedTrainLength
Max. permitted train length [m].
### General Information

**Number**: 1.1.6.2.50

**XML Name**: maxPermittedTrainLength

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/maxPermittedTrainLength
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## maxPermittedAxleLoad
Max. permitted axle load [t].
### General Information

**Number**: 1.1.2.7.51

**XML Name**: maxPermittedAxleLoad

**Deadline**: xx

### Data Format
* **Data Presentation**
*Real*
* **Taxonomy Reference**
http://data.europa.eu/949/maxPermittedAxleLoad
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## minTrackRadius
Min. track radius [m].
### General Information

**Number**: 1.1.3.4.16

**XML Name**: minTrackRadius

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/minTrackRadius
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## clearanceGauge
Clearance gauge.
### General Information

**Number**: 1.1.1.8.62

**XML Name**: clearanceGauge

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/clearanceGauge
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | GA     |
| 2    | GB     |
| 3    | GC     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## lengthOfAccessBranchLine
Length of access/branch line [km].
### General Information

**Number**: 1.1.7.4.10

**XML Name**: lengthOfAccessBranchLine

**Deadline**: xx

### Data Format
* **Data Presentation**
*Real*
* **Taxonomy Reference**
http://data.europa.eu/949/lengthOfAccessBranchLine
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## accessLineElectrification
Access line electrification.
### General Information

**Number**: 1.1.3.1.25

**XML Name**: accessLineElectrification

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/accessLineElectrification
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## accessLineMaxPermittedTrainLength
Access line max. train length [m].
### General Information

**Number**: 1.1.5.5.97

**XML Name**: accessLineMaxPermittedTrainLength

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/accessLineMaxPermittedTrainLength
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## accessLineMaxAxleLoad
Access line max. axle load [t].
### General Information

**Number**: 1.1.8.7.71

**XML Name**: accessLineMaxAxleLoad

**Deadline**: xx

### Data Format
* **Data Presentation**
*Real*
* **Taxonomy Reference**
http://data.europa.eu/949/accessLineMaxAxleLoad
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## accessLineMinTrackRadius
Access line min. track radius [m].
### General Information

**Number**: 1.1.4.8.30

**XML Name**: accessLineMinTrackRadius

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/accessLineMinTrackRadius
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## accessLineClearanceGauge
Access line clearance gauge.
### General Information

**Number**: 1.1.2.9.60

**XML Name**: accessLineClearanceGauge

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/accessLineClearanceGauge
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | GA     |
| 2    | GB     |
| 3    | GC     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## accessLineMaxIncline
Access line max. incline [‰].
### General Information

**Number**: 1.1.8.6.27

**XML Name**: accessLineMaxIncline

**Deadline**: xx

### Data Format
* **Data Presentation**
*Real*
* **Taxonomy Reference**
http://data.europa.eu/949/accessLineMaxIncline
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## containerAcceptance
Container acceptance.
### General Information

**Number**: 1.1.4.4.50

**XML Name**: containerAcceptance

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/containerAcceptance
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No containers accepted     |
| 1    | ISO containers accepted     |
| 2    | Continental containers accepted     |
| 3    | All container types accepted     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## containerSizeLimit
Container size limit [ft].
### General Information

**Number**: 1.1.5.9.70

**XML Name**: containerSizeLimit

**Deadline**: xx

### Data Format
* **Data Presentation**
*Real*
* **Taxonomy Reference**
http://data.europa.eu/949/containerSizeLimit
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## containerWeightLimit
Container weight limit [t].
### General Information

**Number**: 1.1.4.5.31

**XML Name**: containerWeightLimit

**Deadline**: xx

### Data Format
* **Data Presentation**
*Real*
* **Taxonomy Reference**
http://data.europa.eu/949/containerWeightLimit
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## swapBodyAcceptance
Swap body acceptance.
### General Information

**Number**: 1.1.4.7.90

**XML Name**: swapBodyAcceptance

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/swapBodyAcceptance
* **Values**
| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No swap bodies accepted     |
| 1    | Swap bodies accepted     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## swapBodySizeLimit
Swap body size limit [m].
### General Information

**Number**: 1.1.9.8.51

**XML Name**: swapBodySizeLimit

**Deadline**: xx

### Data Format
* **Data Presentation**
*Real*
* **Taxonomy Reference**
http://data.europa.eu/949/swapBodySizeLimit
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## swapBodyWeightLimit
Swap body weight limit [t].
### General Information

**Number**: 1.1.1.5.50

**XML Name**: swapBodyWeightLimit

**Deadline**: xx

### Data Format
* **Data Presentation**
*Real*
* **Taxonomy Reference**
http://data.europa.eu/949/swapBodyWeightLimit
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## trailerAcceptance
Trailer acceptance.
### General Information

**Number**: 1.1.6.5.25

**XML Name**: trailerAcceptance

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/trailerAcceptance
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No trailers accepted     |
| 1    | Craneable trailers accepted     |
| 2    | Non-craneable trailers accepted     |
| 3    | Craneable and non-craneable trailers accepted     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## trailerSizeLimit
Trailer size limit [m].
### General Information

**Number**: 1.1.3.3.43

**XML Name**: trailerSizeLimit

**Deadline**: xx

### Data Format
* **Data Presentation**
*Real*
* **Taxonomy Reference**
http://data.europa.eu/949/trailerSizeLimit
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## trailerWeightLimit
Trailer weight limit [t].
### General Information

**Number**: 1.1.8.5.9

**XML Name**: trailerWeightLimit

**Deadline**: xx

### Data Format
* **Data Presentation**
*Real*
* **Taxonomy Reference**
http://data.europa.eu/949/trailerWeightLimit
* **Values**
Free data entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## truckTrailerAcceptance
Truck + trailer (Rola) acceptance.
### General Information

**Number**: 1.1.2.2.45

**XML Name**: truckTrailerAcceptance

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/truckTrailerAcceptance
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No Truck + trailer accepted     |
| 1    | Truck + trailer accepted     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## conventionalCargoAcceptance
Conventional cargo acceptance.
### General Information

**Number**: 1.1.2.2.55

**XML Name**: conventionalCargoAcceptance

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/conventionalCargoAcceptance
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## palletisedGoods
Palletised goods.
### General Information

**Number**: 1.1.1.9.32

**XML Name**: palletisedGoods

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/palletisedGoods
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## bulk
Bulk
### General Information

**Number**: 1.1.4.3.59

**XML Name**: bulk

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/bulk
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## fluidsAndGas
Fluids and gas.
### General Information

**Number**: 1.1.9.5.47

**XML Name**: fluidsAndGas

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/fluidsAndGas
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## dangerousGoods
Dangerous goods.
### General Information

**Number**: 1.1.3.3.54

**XML Name**: dangerousGoods

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/dangerousGoods
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## ridClasses
RID classes.
### General Information

**Number**: 1.1.1.1.89

**XML Name**: ridClasses

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/ridClasses
* **Values**
Free text entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## wood
Wood.
### General Information

**Number**: 1.1.6.9.63

**XML Name**: wood

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/wood
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## heavyLoads
Heavy loads.
### General Information

**Number**: 1.1.2.9.61

**XML Name**: heavyLoads

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/heavyLoads
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## reeferCargo
Rreefer cargo.
### General Information

**Number**: 1.1.6.6.52

**XML Name**: reeferCargo

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/reeferCargo
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No     |
| 1    | Yes     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## otherCargoTypes
Other cargo types.
### General Information

**Number**: 1.1.8.3.89

**XML Name**: otherCargoTypes

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/otherCargoTypes
* **Values**
Free text entry.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(c) and (d) of Reg. 2017/2177) 

------------------------------------------------------------

## selfSupplyOfRailRelatedServices
Self-supply of rail-related services.
### General Information

**Number**: 1.1.9.7.73

**XML Name**: selfSupplyOfRailRelatedServices

**Deadline**: xx

### Data Format
* **Data Presentation**

* **Taxonomy Reference**
http://data.europa.eu/949/selfSupplyOfRailRelatedServices
* **Values**
Link/text file attachment.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 3(8) and Art. 4(2)(e) of Reg. 2017/2177) 

------------------------------------------------------------

## itSystems
IT systems.
### General Information

**Number**: 1.1.1.9.48

**XML Name**: itSystems

**Deadline**: xx

### Data Format
* **Data Presentation**

* **Taxonomy Reference**
http://data.europa.eu/949/itSystems
* **Values**
Link/text file attachment.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(j) of Reg. 2017/2177) 

------------------------------------------------------------

## requestsForAccessOrServices
Requests for access or services.
### General Information

**Number**: 1.1.7.5.73

**XML Name**: requestsForAccessOrServices

**Deadline**: xx

### Data Format
* **Data Presentation**

* **Taxonomy Reference**
http://data.europa.eu/949/requestsForAccessOrServices
* **Values**
Link/text file attachment.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 6 property (Capacity Allocation).

* **Regulation**: 
	Mandatory by law (Art. 4(2) letters (f),(g)and (h) of Reg. 2017/2177) 

------------------------------------------------------------

## bookingConditions
Booking forms, time limits for booking, cancellation conditions, special requirements
### General Information

**Number**: 1.1.6.5.10

**XML Name**: bookingConditions

**Deadline**: xx

### Data Format
* **Data Presentation**

* **Taxonomy Reference**
http://data.europa.eu/949/bookingConditions
* **Values**
Link/text file attachment.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 6 property (Capacity Allocation).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(f) and (h) of Reg. 2017/2177) 


------------------------------------------------------------

## responseToRequests
Response to requests.
### General Information

**Number**: 1.1.2.1.41

**XML Name**: responseToRequests

**Deadline**: xx

### Data Format
* **Data Presentation**

* **Taxonomy Reference**
http://data.europa.eu/949/responseToRequests
* **Values**
Link/text file attachment.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 6 property (Capacity Allocation).

* **Regulation**: 
	Mandatory by law (Art. 4(2)letters (f),(h) and (k) of Reg. 2017/2177) 

------------------------------------------------------------

## availableCapacity
Information on available capacity.
### General Information

**Number**: 1.1.4.9.50

**XML Name**: availableCapacity

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/availableCapacity
* **Values**

| Code | Value |
|------|-------|
| -1    | Unknown     |
| 0    | No capacity information     |
| 1    | Sufficient capacity to accommodate any kind of request     |
| 2    | Limited remaining capacity     |
| 3    | Facility is full     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 6 property (Capacity Allocation).

* **Regulation**: 
	Mandatory by law (Art. 3(4) and Art. 6(2) of Reg. 2017/2177) 

------------------------------------------------------------

## temporaryCapacityRestrictions
Information on temporary capacity restrictions.
### General Information

**Number**: 1.1.9.1.2

**XML Name**: temporaryCapacityRestrictions

**Deadline**: xx

### Data Format
* **Data Presentation**
[string](https://www.w3.org/2001/XMLSchema#string)
* **Taxonomy Reference**
http://data.europa.eu/949/temporaryCapacityRestrictions
* **Values**
Free text input.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 6 property (Capacity Allocation).

* **Regulation**: 
	Mandatory by law (Art. 4(2)(l) of Reg. 2017/2177) 

------------------------------------------------------------

## cooperationBetweenSfAndIm
Cooperation between the SF and IMs.
### General Information

**Number**: 1.1.5.4.45

**XML Name**: cooperationBetweenSfAndIm

**Deadline**: xx

### Data Format
* **Data Presentation**

* **Taxonomy Reference**
http://data.europa.eu/949/cooperationBetweenSfAndIm
* **Values**
Link/text file attachment.

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	This property is considered as Type 6 property (Capacity Allocation).

* **Regulation**: 
	Mandatory by law (Art. 7 of Reg. 2017/2177) 

------------------------------------------------------------

## statusChange
Deactivate data record.
### General Information

**Number**: 1.1.9.8.20

**XML Name**: statusChange

**Deadline**: xx

### Data Format
* **Data Presentation**
[integer](https://www.w3.org/2001/XMLSchema#integer)
* **Taxonomy Reference**
http://data.europa.eu/949/statusChange
* **Values**

| Code | Value |
|------|-------|
| 0    | will leave the facility as is     |
| 1    | reactivate the facility (Internal system facility ID must be set)     |
| 2    | deactivate the facility     |
| 3    | delete the facility     |

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

### Validation

* **Validation Rules**:
	None

* **Validation Messages**:
	None

### OPE TSI References

* **Appendix D2 Index**
	None

### Parameter of



### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------
