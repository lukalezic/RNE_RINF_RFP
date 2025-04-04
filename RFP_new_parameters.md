# PROPOSED PARAMETERS FROM RFP TO BE ADDED TO ERA ONTOLOGY
## Problem setting

As part of RNE’s work supporting the IMs digitalising their network statement, RNE has been
contracted to study, define and propose additional infrastructure parameters which would be
needed for RINF to effectively cover the nature of the infrastructure part of the Rail-FacilitiesPortal. After comparison between the parameters of the RFP with those of the RINF Register of
Infrastructure and ERA Vocabulary, RNE proposed the following parameters to enrich ERA Ontology and as inputs for future developments of the RINF application.

## Proposed solution
# Classes
## Service Facility

Represents a facility that offers services to trains.

**IRI**: http://data.europa.eu/949/ServiceFacility

### Is a

* http://data.europa.eu/949/OperationalPoint

### Has Properties

* **Facility Type** - A type of Service Facility, identified by a number.
  
* **Facility Owner** - The owner of the service facility.

### Additional Information

**General explanation**:

The installation, including ground area, building and equipment, which has been specially arranged, as a whole or in part, to allow the supply of one or more services referred to in points 2 to 4 of Annex II.

**Regulation**: n/a

# Object-Properties
## Facility Owner
The owner of the service facility.
### General Information

**Number**: 1.1.1.5.1.1

**XML Name**: SF_Owner

**Deadline**:  xx

### Data Format
* **Data Presentation**
[Organization](https://linkedvocabs.org/data/era-ontology/3.1.0/appGuide/index-en.html#Organization)
* **Taxonomy Reference**
http://data.europa.eu/949/facilityOwner

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

# Data-Properties
### Facility Type

A type of Service Facility, identified by a number.
### General Information

**Number**: 1.1.1.5.1.2

**XML Name**: SF_Type

**Deadline**:  xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/facilityType
* **Values**

| Code | Value |
|------|-------|
| 1    | 1     |
| 2    | 2     |
| 3    | 3     |
| 4    | 4     |
| 5    | 5     |
| 6    | 6     |
| 7    | 7     |
| 8    | 8     |
| 9    | 9     |
| 10   | 10    |
| 11   | 11    |
| 12   | 12    |

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	The possible values are:

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
  
  11 = Refueling facility
  
  12 = Mobile service provider

* **Regulation**: 
	Mandatory by law (points 2, 3 and 4 of Annex II to Dir. 2012/34/EU and Art. 1 of Reg. 2017/2177)

------------------------------------------------------------

## id
Internal system facility ID
### General Information

**Number**: 1.1.4.9.19

**XML Name**: id

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
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

http://data.europa.eu/949/ServiceFacility

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
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/mainDataSource
* **Values**
Free text entry, name organisation providing the data.

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

http://data.europa.eu/949/ServiceFacility

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
*Integer*
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

http://data.europa.eu/949/ServiceFacility

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
  
  11 = Refueling facility
  
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
*String*
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

http://data.europa.eu/949/ServiceFacility

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
*Integer*
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

http://data.europa.eu/949/ServiceFacility

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
*Integer*
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

http://data.europa.eu/949/ServiceFacility

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
*Integer*
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

http://data.europa.eu/949/ServiceFacility

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
*Integer*
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

http://data.europa.eu/949/ServiceFacility

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

http://data.europa.eu/949/ServiceFacility

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
-
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	None

------------------------------------------------------------

## briefPresentation
Brief presentation of the SF.
### General Information

**Number**: 1.1.2.9.28

**XML Name**: briefPresentation

**Deadline**: xx

### Data Format
* **Data Presentation**
-
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

http://data.europa.eu/949/ServiceFacility

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
*String*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	None

------------------------------------------------------------

## operator
Facility operator (RICS).
### General Information

**Number**: 1.1.5.7.12

**XML Name**: operator

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
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

http://data.europa.eu/949/ServiceFacility

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
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	None

------------------------------------------------------------

## operatorOtherType
Other type of operator.
### General Information

**Number**: 1.1.7.7.26

**XML Name**: operatorOtherType

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
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

http://data.europa.eu/949/ServiceFacility

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
*String*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	None

------------------------------------------------------------

## operatorPhone
Phone.
### General Information

**Number**: 1.1.1.8.44

**XML Name**: operatorPhone

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	None

------------------------------------------------------------

## operatorFax
Fax.
### General Information

**Number**: 1.1.8.9.13

**XML Name**: operatorFax

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	None

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	None

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	None

------------------------------------------------------------

## facilityOwner
Facility owner (name).
### General Information

**Number**: 1.1.9.3.64

**XML Name**: facilityOwner

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
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

http://data.europa.eu/949/ServiceFacility

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
*Integer*
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

http://data.europa.eu/949/ServiceFacility

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
*String*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	None

------------------------------------------------------------

## operatorsRelation
Explanantion of the relation between several operators, if relevant.
### General Information

**Number**: 1.1.9.6.37

**XML Name**: operatorsRelation

**Deadline**: xx

### Data Format
* **Data Presentation**
-
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

http://data.europa.eu/949/ServiceFacility

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
*String*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	None

------------------------------------------------------------

## sfDataUpdateProcedure
Describe how the SF data is updated.
### General Information

**Number**: 1.1.7.8.59

**XML Name**: sfDataUpdateProcedure

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	None

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	None

------------------------------------------------------------

## applyCompliance
Data provision according to Reg. (EU) 2017/2177.
### General Information

**Number**: 1.1.9.5.2

**XML Name**: applyCompliance

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

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
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	None

------------------------------------------------------------

## locomotiveCleaning
Locomotive cleaning.
### General Information

**Number**: 1.1.9.5.53

**XML Name**: locomotiveCleaning

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## wagonCleaning
Wagon cleaning.
### General Information

**Number**: 1.1.5.1.95

**XML Name**: wagonCleaning

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## locomotiveParking
Locomotive parking.
### General Information

**Number**: 1.1.3.3.6

**XML Name**: locomotiveParking

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## wagonParking
Wagon parking.
### General Information

**Number**: 1.1.4.4.52

**XML Name**: wagonParking

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## locomotiveRepairMaintenanceLight
Locomotive repair/maintenance (light maintenance).
### General Information

**Number**: 1.1.8.6.45

**XML Name**: locomotiveRepairMaintenanceLight

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## locomotiveRepairMaintenanceHeavy
Locomotive repair/maintenance (heavy maintenance).
### General Information

**Number**: 1.1.7.1.6

**XML Name**: locomotiveRepairMaintenanceHeavy

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## wagonRepairMaintenanceLight
Wagon repair/maintenance (light maintenance).
### General Information

**Number**: 1.1.4.6.92

**XML Name**: wagonRepairMaintenanceLight

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## wagonRepairMaintenanceHeavy
Wagon repair/maintenance (heavy maintenance).
### General Information

**Number**: 1.1.2.3.10

**XML Name**: wagonRepairMaintenanceHeavy

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## technicalInspectionOfRollingStock
Technical inspection of rolling stock.
### General Information

**Number**: 1.1.5.4.89

**XML Name**: technicalInspectionOfRollingStock

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## refuelling
Refuelling.
### General Information

**Number**: 1.1.3.9.47

**XML Name**: refuelling

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## shunting
Shunting.
### General Information

**Number**: 1.1.3.5.84

**XML Name**: shunting

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## provisionEmergencyEquipment
Provision of emergency equipment.
### General Information

**Number**: 1.1.2.1.69

**XML Name**: provisionEmergencyEquipment

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## securityServices
Security services.
### General Information

**Number**: 1.1.2.1.31

**XML Name**: securityServices

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## tractionCurrent
Traction current (extra charges).
### General Information

**Number**: 1.1.4.6.37

**XML Name**: tractionCurrent

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## accessToTelecommunicationNetworks
Access to telecommunication networks.
### General Information

**Number**: 1.1.3.8.87

**XML Name**: accessToTelecommunicationNetworks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## provisionSupplementaryInformation
Provision of supplementary information.
### General Information

**Number**: 1.1.6.2.4

**XML Name**: provisionSupplementaryInformation

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## otherServices
Other services.
### General Information

**Number**: 1.1.9.4.22

**XML Name**: otherServices

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## descriptionOfServices
Description of services.
### General Information

**Number**: 1.1.4.6.35

**XML Name**: descriptionOfServices

**Deadline**: xx

### Data Format
* **Data Presentation**
-
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## timetableServiceTrains
Timetable for service trains.
### General Information

**Number**: 1.1.9.1.67

**XML Name**: timetableServiceTrains

**Deadline**: xx

### Data Format
* **Data Presentation**
-
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## facilityCertificates
Facility certificates.
### General Information

**Number**: 1.1.4.6.44

**XML Name**: facilityCertificates

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
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

http://data.europa.eu/949/ServiceFacility

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
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## loadingUnitCleaning
Loading unit cleaning.
### General Information

**Number**: 1.1.9.6.74

**XML Name**: loadingUnitCleaning

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## loadingUnitFumigationDisinfection
Loading unit fumigation, disinfection.
### General Information

**Number**: 1.1.4.9.82

**XML Name**: loadingUnitFumigationDisinfection

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## loadingUnitRepairMaintenance
Loading unit repair/maintenance.
### General Information

**Number**: 1.1.2.4.22

**XML Name**: loadingUnitRepairMaintenance

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## loadingUnitVentilation
Loading unit ventilation.
### General Information

**Number**: 1.1.6.2.82

**XML Name**: loadingUnitVentilation

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## orderPickingWarehousing
Order picking, warehousing.
### General Information

**Number**: 1.1.4.8.65

**XML Name**: orderPickingWarehousing

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## storageContainersGeneralCargo
Storage of containers/general cargo.
### General Information

**Number**: 1.1.7.1.4

**XML Name**: storageContainersGeneralCargo

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## storageDangerousGoods
Storage of dangerous goods.
### General Information

**Number**: 1.1.8.9.8

**XML Name**: storageDangerousGoods

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## storageRidClasses
RID classes.
### General Information

**Number**: 1.1.4.2.6

**XML Name**: storageRidClasses

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
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

http://data.europa.eu/949/ServiceFacility

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
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## stuffingStripping
Stuffing/Stripping.
### General Information

**Number**: 1.1.4.6.90

**XML Name**: stuffingStripping

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## containerLashing
Container lashing.
### General Information

**Number**: 1.1.2.9.18

**XML Name**: containerLashing

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## weighingWagonsLoadingUnits
Weighing of wagons/Loading units.
### General Information

**Number**: 1.1.5.9.34

**XML Name**: weighingWagonsLoadingUnits

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## containerSalesLeasing
Container sales/leasing.
### General Information

**Number**: 1.1.4.3.56

**XML Name**: containerSalesLeasing

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## customsClearance
Customs clearance.
### General Information

**Number**: 1.1.3.2.37

**XML Name**: customsClearance

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## trucking
Trucking (Organisation Pre-/End-haulage).
### General Information

**Number**: 1.1.6.3.49

**XML Name**: trucking

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## tailormadeContractsDangerousGoods
Tailor-made contracts for control of transport of dangerous goods.
### General Information

**Number**: 1.1.1.8.21

**XML Name**: tailormadeContractsDangerousGoods

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## tailormadeContractsAbnormalTrains
Tailor-made contracts for assistance in running abnormal trains.
### General Information

**Number**: 1.1.8.9.52

**XML Name**: tailormadeContractsAbnormalTrains

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## trainBoardingDeboarding
Train boarding and deboarding.
### General Information

**Number**: 1.1.5.7.99

**XML Name**: trainBoardingDeboarding

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## ticketingServices
Ticketing services.
### General Information

**Number**: 1.1.8.5.94

**XML Name**: ticketingServices

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## assistanceForPersonsWithReducedMobility
Assistance for persons with reduced mobility.
### General Information

**Number**: 1.1.8.2.44

**XML Name**: assistanceForPersonsWithReducedMobility

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## lostAndFound
Lost & Found.
### General Information

**Number**: 1.1.7.3.45

**XML Name**: lostAndFound

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## luggageStoring
Luggage storing.
### General Information

**Number**: 1.1.4.1.32

**XML Name**: luggageStoring

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## waitingAreasAndWeaterProtection
Waiting areas and weather protection.
### General Information

**Number**: 1.1.3.1.91

**XML Name**: waitingAreasAndWeaterProtection

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## iceProtection
Ice protection
### General Information

**Number**: 1.1.8.9.95

**XML Name**: iceProtection

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## preHeatingPreCooling
Pre-heating and pre-cooling of passenger trains.
### General Information

**Number**: 1.1.2.1.85

**XML Name**: preHeatingPreCooling

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## sewageDisposalWaterSupply
Sewage disposal and water supply.
### General Information

**Number**: 1.1.6.7.54

**XML Name**: sewageDisposalWaterSupply

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

------------------------------------------------------------

## useOfMotorailFacilities
Use of motorail facilities.
### General Information

**Number**: 1.1.8.3.31

**XML Name**: useOfMotorailFacilities

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 2 property (Services provided).

* **Regulation**: 
	None

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

http://data.europa.eu/949/ServiceFacility

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

http://data.europa.eu/949/ServiceFacility

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
*String*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## crdSubsidiaryLocation
CRD subsidiary location ID.
### General Information

**Number**: 1.1.8.9.74

**XML Name**: crdSubsidiaryLocation

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/crdSubsidiaryLocation
* **Values**

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

http://data.europa.eu/949/ServiceFacility

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
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/rinfOperationalPoint
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## facilityStreet
Street, house number
### General Information

**Number**: 1.1.4.6.35

**XML Name**: facilityStreet

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## facilityZip
ZIP code.
### General Information

**Number**: 1.1.2.5.72

**XML Name**: facilityZip

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## facilityTown
Town.
### General Information

**Number**: 1.1.9.6.43

**XML Name**: facilityTown

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## facilityCountry
Country.
### General Information

**Number**: 1.1.2.5.43

**XML Name**: facilityCountry

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## connectionToPublicRailNetwork
Connection of facility to public rail network.
### General Information

**Number**: 1.1.4.1.54

**XML Name**: connectionToPublicRailNetwork

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/connectionToPublicRailNetwork
* **Values**

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

http://data.europa.eu/949/ServiceFacility

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
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/facilityLocatedOnRfc
* **Values**

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

http://data.europa.eu/949/ServiceFacility

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
-
* **Taxonomy Reference**
http://data.europa.eu/949/roadAccessConditions
* **Values**

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

http://data.europa.eu/949/ServiceFacility

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
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/operationStatus
* **Values**

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

http://data.europa.eu/949/ServiceFacility

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
*String*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## openOnDemand
Facility open on demand.
### General Information

**Number**: 1.1.7.6.51

**XML Name**: openOnDemand

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/openOnDemand
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## totalNumberOfTracks
All facility tracks: number.
### General Information

**Number**: 1.1.8.6.33

**XML Name**: totalNumberOfTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/totalNumberOfTracks
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## totalNumberOfPlatformTracks
Platform tracks: number.
### General Information

**Number**: 1.1.3.6.63

**XML Name**: totalNumberOfPlatformTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## thereofElectrifiedPlatformTracks
Platform tracks: thereof electrified.
### General Information

**Number**: 1.1.1.6.16

**XML Name**: thereofElectrifiedPlatformTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/thereofElectrifiedPlatformTracks
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## maxUsableLengthPlatformTracks
Platform tracks: max. usable length [m]
### General Information

**Number**: 1.1.5.8.79

**XML Name**: maxUsableLengthPlatformTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/maxUsableLengthPlatformTracks
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## totalNumberOfTranshipmentTracks
Transhipment tracks: number.
### General Information

**Number**: 1.1.2.8.56

**XML Name**: totalNumberOfTranshipmentTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/totalNumberOfTranshipmentTracks
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## thereofElectrifiedTranshipmentTracks
Transhipment tracks: thereof electrified.
### General Information

**Number**: 1.1.4.6.35

**XML Name**: thereofElectrifiedTranshipmentTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/thereofElectrifiedTranshipmentTracks
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## maxUsableLengthTranshipmentTracks
Transhipment tracks: max. usable length [m].
### General Information

**Number**: 1.1.4.5.38

**XML Name**: maxUsableLengthTranshipmentTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/maxUsableLengthTranshipmentTracks
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## totalNumberOfStorageTracks
Storage tracks: number.
### General Information

**Number**: 1.1.9.9.87

**XML Name**: totalNumberOfStorageTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/totalNumberOfStorageTracks
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## thereofElectrifiedStorageTracks
Storage tracks: thereof electrified.
### General Information

**Number**: 1.1.3.1.91

**XML Name**: thereofElectrifiedStorageTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/thereofElectrifiedStorageTracks
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## maxUsableLengthStorageTracks
Storage tracks: max. usable length [m].
### General Information

**Number**: 1.1.6.1.20

**XML Name**: maxUsableLengthStorageTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/maxUsableLengthStorageTracks
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## totalNumberOfShuntingTracks
Shunting tracks: number.
### General Information

**Number**: 1.1.2.3.27

**XML Name**: totalNumberOfShuntingTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/totalNumberOfShuntingTracks
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## thereofElectrifiedShuntingTracks
Shunting tracks: thereof electrified.
### General Information

**Number**: 1.1.1.3.35

**XML Name**: thereofElectrifiedShuntingTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/thereofElectrifiedShuntingTracks
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## maxUsableLengthShuntingTracks
Shunting tracks: max. usable length [m]
### General Information

**Number**: 1.1.3.8.63

**XML Name**: maxUsableLengthShuntingTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/maxUsableLengthShuntingTracks
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## totalNumberOfInboundOutboundTracks
Inbound + Outbound tracks: number.
### General Information

**Number**: 1.1.3.7.38

**XML Name**: totalNumberOfInboundOutboundTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/totalNumberOfInboundOutboundTracks
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## thereofElectrifiedInboundOutboundTracks
Inbound + Outbound tracks: thereof electrified.
### General Information

**Number**: 1.1.5.1.56

**XML Name**: thereofElectrifiedInboundOutboundTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/thereofElectrifiedInboundOutboundTracks
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## maxUsableLengthInboundOutboundTracks
Inbound + Outbound tracks: max. usable length [m].
### General Information

**Number**: 1.1.9.4.38

**XML Name**: maxUsableLengthInboundOutboundTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/maxUsableLengthInboundOutboundTracks
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## totalNumberOfAllocationTracks
Allocation tracks: number.
### General Information

**Number**: 1.1.9.2.51

**XML Name**: totalNumberOfAllocationTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/totalNumberOfAllocationTracks
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## thereofElectrifiedAllocationTracks
Allocation tracks: thereof electrified.
### General Information

**Number**: 1.1.6.2.22

**XML Name**: thereofElectrifiedAllocationTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/thereofElectrifiedAllocationTracks
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## maxUsableLengthAllocationTracks
Allocation tracks: max. usable length [m].
### General Information

**Number**: 1.1.3.2.96

**XML Name**: maxUsableLengthAllocationTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/maxUsableLengthAllocationTracks
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## totalNumberOfOtherTracks
Other tracks: number.
### General Information

**Number**: 1.1.6.6.57

**XML Name**: totalNumberOfOtherTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/totalNumberOfOtherTracks
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## thereofElectrifiedOtherTracks
Other tracks: thereof electrified.
### General Information

**Number**: 1.1.3.2.49

**XML Name**: thereofElectrifiedOtherTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/thereofElectrifiedOtherTracks
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## maxUsableLengthOtherTracks
Other tracks: max. usable length [m].
### General Information

**Number**: 1.1.3.7.16

**XML Name**: maxUsableLengthOtherTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/maxUsableLengthOtherTracks
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## descriptionOfTechnicalCharacteristics
Description of the technical characteristics of the facility.
### General Information

**Number**: 1.1.9.6.34

**XML Name**: descriptionOfTechnicalCharacteristics

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/descriptionOfTechnicalCharacteristics
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## technicalMap
Technical map.
### General Information

**Number**: 1.1.7.4.94

**XML Name**: technicalMap

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/technicalMap
* **Values**

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

http://data.europa.eu/949/ServiceFacility

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
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/brakeTestFacility
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## compressedAirSupply
Compressed air supply.
### General Information

**Number**: 1.1.1.2.64

**XML Name**: compressedAirSupply

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/compressedAirSupply
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## turntable
Turntable.
### General Information

**Number**: 1.1.9.5.8

**XML Name**: turntable

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/turntable
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## locomotiveWashingCleaning
Washing/cleaning equipment for locomotives.
### General Information

**Number**: 1.1.4.7.31

**XML Name**: locomotiveWashingCleaning

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/locomotiveWashingCleaning
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## wagonWashingCleaning
Washing/cleaning equipment for  wagons.
### General Information

**Number**: 1.1.6.7.74

**XML Name**: wagonWashingCleaning

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/wagonWashingCleaning
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## loadingUnitWashingCleaning
Washing/cleaning equipment for loading units.
### General Information

**Number**: 1.1.3.4.84

**XML Name**: loadingUnitWashingCleaning

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/loadingUnitWashingCleaning
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## maintenanceShopLight
Maintenance shop (light maintenance).
### General Information

**Number**: 1.1.3.7.89

**XML Name**: maintenanceShopLight

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/maintenanceShopLight
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## maintenanceShopHeavy
Maintenance shop (heavy maintenance).
### General Information

**Number**: 1.1.5.6.2

**XML Name**: maintenanceShopHeavy

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/maintenanceShopHeavy
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## otherEquipment
Other Equipment.
### General Information

**Number**: 1.1.1.4.48

**XML Name**: otherEquipment

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/otherEquipment
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## descriptionTechnicalEquipment
Description of technical equipment (particularly washing, maintenance).
### General Information

**Number**: 1.1.2.7.43

**XML Name**: descriptionTechnicalEquipment

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/descriptionTechnicalEquipment
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## numberOfGantryCranes
Number of (gantry) cranes.
### General Information

**Number**: 1.1.5.6.83

**XML Name**: numberOfGantryCranes

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/numberOfGantryCranes
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## numberOfMobileCranes
Number of mobile cranes.
### General Information

**Number**: 1.1.3.8.71

**XML Name**: numberOfMobileCranes

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/numberOfMobileCranes
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## horizontalTranshipmentSystems
Horizontal transhipment systems.
### General Information

**Number**: 1.1.3.9.47

**XML Name**: horizontalTranshipmentSystems

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/horizontalTranshipmentSystems
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## headRamp
Head ramp.
### General Information

**Number**: 1.1.8.5.84

**XML Name**: headRamp

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/headRamp
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## sideRamp
Side ramp.
### General Information

**Number**: 1.1.5.8.94

**XML Name**: sideRamp

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/sideRamp
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## loadingLane
Loading Lane.
### General Information

**Number**: 1.1.7.2.97

**XML Name**: loadingLane

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/loadingLane
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## hump
Hump.
### General Information

**Number**: 1.1.8.8.15

**XML Name**: hump

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/hump
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## trackScale
Trackscale.
### General Information

**Number**: 1.1.2.5.78

**XML Name**: trackScale

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/trackScale
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## opticalCharacterRecognition
Optical character recognition.
### General Information

**Number**: 1.1.5.7.59

**XML Name**: opticalCharacterRecognition

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/opticalCharacterRecognition
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## numberOfReeferConnections
Number of reefer connections.
### General Information

**Number**: 1.1.3.2.16

**XML Name**: numberOfReeferConnections

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/numberOfReeferConnections
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## storageAreaM2
Storage area [m²].
### General Information

**Number**: 1.1.2.9.22

**XML Name**: storageAreaM2

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/storageAreaM2
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## storageAreaTeu
Storage area [TEU].
### General Information

**Number**: 1.1.8.8.5

**XML Name**: storageAreaTeu

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/storageAreaTeu
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## emptyContainerDepot
Empty container depot.
### General Information

**Number**: 1.1.2.5.88

**XML Name**: emptyContainerDepot

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/emptyContainerDepot
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## numberOfPlatforms
Number of platforms.
### General Information

**Number**: 1.1.2.1.90

**XML Name**: numberOfPlatforms

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/numberOfPlatforms
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## maxPlatformLength
Max. platform length [m].
### General Information

**Number**: 1.1.9.6.50

**XML Name**: maxPlatformLength

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/maxPlatformLength
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## maxPlatformHeight
Max. platform height [mm].
### General Information

**Number**: 1.1.7.5.37

**XML Name**: maxPlatformHeight

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/maxPlatformHeight
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## minPlatformHeight
Min. platform height [mm].
### General Information

**Number**: 1.1.6.1.44

**XML Name**: minPlatformHeight

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/minPlatformHeight
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## escalatorRampForPlatformAccess
Escalator/ramp for platform access.
### General Information

**Number**: 1.1.2.3.74

**XML Name**: escalatorRampForPlatformAccess

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/escalatorRampForPlatformAccess
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## weatherProtectionForPassengers
Weather protection for passengers.
### General Information

**Number**: 1.1.6.4.56

**XML Name**: weatherProtectionForPassengers

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/weatherProtectionForPassengers
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## plannedChangesTechnicalCharacteristics
Planned changes in technical characteristics.
### General Information

**Number**: 1.1.4.3.75

**XML Name**: plannedChangesTechnicalCharacteristics

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/plannedChangesTechnicalCharacteristics
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 3 property (Service Facility Description).

* **Regulation**: 
	None

------------------------------------------------------------

## informationOnCharges
Information on charges.
### General Information

**Number**: 1.1.4.2.55

**XML Name**: informationOnCharges

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/informationOnCharges
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 4 property (Charges).

* **Regulation**: 
	None

------------------------------------------------------------

## informationOnDiscounts
Information on discounts.
### General Information

**Number**: 1.1.1.8.31

**XML Name**: informationOnDiscounts

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/informationOnDiscounts
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 4 property (Charges).

* **Regulation**: 
	None

------------------------------------------------------------

## publicAccessibility
Public accessibility.
### General Information

**Number**: 1.1.8.3.56

**XML Name**: publicAccessibility

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/publicAccessibility
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

------------------------------------------------------------

## legalRequirements
Legal requirements.
### General Information

**Number**: 1.1.4.8.22

**XML Name**: legalRequirements

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/legalRequirements
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

------------------------------------------------------------

## electrifiedRailAccessPossible
Electrified rail access possible.
### General Information

**Number**: 1.1.8.5.43

**XML Name**: electrifiedRailAccessPossible

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/electrifiedRailAccessPossible
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

------------------------------------------------------------

## maxPermittedTrainLength
Max. permitted train length [m].
### General Information

**Number**: 1.1.6.2.50

**XML Name**: maxPermittedTrainLength

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/maxPermittedTrainLength
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

------------------------------------------------------------

## minTrackRadius
Min. track radius [m].
### General Information

**Number**: 1.1.3.4.16

**XML Name**: minTrackRadius

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/minTrackRadius
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

------------------------------------------------------------

## clearanceGauge
Clearance gauge.
### General Information

**Number**: 1.1.1.8.62

**XML Name**: clearanceGauge

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/clearanceGauge
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

------------------------------------------------------------

## accessLineElectrification
Access line electrification.
### General Information

**Number**: 1.1.3.1.25

**XML Name**: accessLineElectrification

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/accessLineElectrification
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

------------------------------------------------------------

## accessLineMaxPermittedTrainLength
Access line max. train length [m].
### General Information

**Number**: 1.1.5.5.97

**XML Name**: accessLineMaxPermittedTrainLength

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/accessLineMaxPermittedTrainLength
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

------------------------------------------------------------

## accessLineMinTrackRadius
Access line min. track radius [m].
### General Information

**Number**: 1.1.4.8.30

**XML Name**: accessLineMinTrackRadius

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/accessLineMinTrackRadius
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

------------------------------------------------------------

## accessLineClearanceGauge
Access line clearance gauge.
### General Information

**Number**: 1.1.2.9.60

**XML Name**: accessLineClearanceGauge

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/accessLineClearanceGauge
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

------------------------------------------------------------

## containerAcceptance
Container acceptance.
### General Information

**Number**: 1.1.4.4.50

**XML Name**: containerAcceptance

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/containerAcceptance
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

------------------------------------------------------------

## swapBodyAcceptance
Swap body acceptance.
### General Information

**Number**: 1.1.4.7.90

**XML Name**: swapBodyAcceptance

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/swapBodyAcceptance
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

------------------------------------------------------------

## trailerAcceptance
Trailer acceptance.
### General Information

**Number**: 1.1.6.5.25

**XML Name**: trailerAcceptance

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/trailerAcceptance
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

------------------------------------------------------------

## truckTrailerAcceptance
Truck + trailer (Rola) acceptance.
### General Information

**Number**: 1.1.2.2.45

**XML Name**: truckTrailerAcceptance

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/truckTrailerAcceptance
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

------------------------------------------------------------

## conventionalCargoAcceptance
Conventional cargo acceptance.
### General Information

**Number**: 1.1.2.2.55

**XML Name**: conventionalCargoAcceptance

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/conventionalCargoAcceptance
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

------------------------------------------------------------

## palletisedGoods
Palletised goods.
### General Information

**Number**: 1.1.1.9.32

**XML Name**: palletisedGoods

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/palletisedGoods
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

------------------------------------------------------------

## bulk
Bulk
### General Information

**Number**: 1.1.4.3.59

**XML Name**: bulk

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/bulk
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

------------------------------------------------------------

## fluidsAndGas
Fluids and gas.
### General Information

**Number**: 1.1.9.5.47

**XML Name**: fluidsAndGas

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/fluidsAndGas
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

------------------------------------------------------------

## dangerousGoods
Dangerous goods.
### General Information

**Number**: 1.1.3.3.54

**XML Name**: dangerousGoods

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/dangerousGoods
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

------------------------------------------------------------

## ridClasses
RID classes.
### General Information

**Number**: 1.1.1.1.89

**XML Name**: ridClasses

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

------------------------------------------------------------

## wood
Wood.
### General Information

**Number**: 1.1.6.9.63

**XML Name**: wood

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/wood
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

------------------------------------------------------------

## heavyLoads
Heavy loads.
### General Information

**Number**: 1.1.2.9.61

**XML Name**: heavyLoads

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/heavyLoads
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

------------------------------------------------------------

## reeferCargo
Rreefer cargo.
### General Information

**Number**: 1.1.6.6.52

**XML Name**: reeferCargo

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/reeferCargo
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

------------------------------------------------------------

## otherCargoTypes
Other cargo types.
### General Information

**Number**: 1.1.8.3.89

**XML Name**: otherCargoTypes

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

------------------------------------------------------------

## selfSupplyOfRailRelatedServices
Self-supply of rail-related services.
### General Information

**Number**: 1.1.9.7.73

**XML Name**: selfSupplyOfRailRelatedServices

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/selfSupplyOfRailRelatedServices
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

------------------------------------------------------------

## itSystems
IT systems.
### General Information

**Number**: 1.1.1.9.48

**XML Name**: itSystems

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/itSystems
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 5 property (Access Conditions).

* **Regulation**: 
	None

------------------------------------------------------------

## requestsForAccessOrServices
Requests for access or services.
### General Information

**Number**: 1.1.7.5.73

**XML Name**: requestsForAccessOrServices

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/requestsForAccessOrServices
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 6 property (Capacity Allocation).

* **Regulation**: 
	None

------------------------------------------------------------

## bookingConditions
Booking forms, time limits for booking, cancellation conditions, special requirements
### General Information

**Number**: 1.1.6.5.10

**XML Name**: bookingConditions

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/bookingConditions
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 6 property (Capacity Allocation).

* **Regulation**: 
	None

------------------------------------------------------------

## responseToRequests
Response to requests.
### General Information

**Number**: 1.1.2.1.41

**XML Name**: responseToRequests

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/responseToRequests
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 6 property (Capacity Allocation).

* **Regulation**: 
	None

------------------------------------------------------------

## availableCapacity
Information on available capacity.
### General Information

**Number**: 1.1.4.9.50

**XML Name**: availableCapacity

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/availableCapacity
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 6 property (Capacity Allocation).

* **Regulation**: 
	None

------------------------------------------------------------

## temporaryCapacityRestrictions
Information on temporary capacity restrictions.
### General Information

**Number**: 1.1.9.1.2

**XML Name**: temporaryCapacityRestrictions

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/temporaryCapacityRestrictions
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 6 property (Capacity Allocation).

* **Regulation**: 
	None

------------------------------------------------------------

## cooperationBetweenSfAndIm
Cooperation between the SF and IMs.
### General Information

**Number**: 1.1.5.4.45

**XML Name**: cooperationBetweenSfAndIm

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/cooperationBetweenSfAndIm
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	This property is considered as Type 6 property (Capacity Allocation).

* **Regulation**: 
	None

------------------------------------------------------------

## statusChange
Deactivate data record.
### General Information

**Number**: 1.1.9.8.20

**XML Name**: statusChange

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/statusChange
* **Values**

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

http://data.europa.eu/949/ServiceFacility

### Additional Information

* **General explanation**:
	None

* **Regulation**: 
	None

------------------------------------------------------------
