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

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
Is the facility located int Sea Port Area?
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
Is the facility located int in Land port Area 
### General Information

**Number**: 1.1.4.1.92

**XML Name**: areaInlandPort

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/areaInlandPort

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The areafreightvillage
### General Information

**Number**: 1.1.8.9.53

**XML Name**: areaFreightVillage

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/areaFreightVillage

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The exempted
### General Information

**Number**: 1.1.7.5.17

**XML Name**: exempted

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/exempted

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The linktoadditionaldocuments
### General Information

**Number**: 1.1.2.2.82

**XML Name**: linkToAdditionalDocuments

**Deadline**: xx

### Data Format
* **Data Presentation**
*Hyperlink*
* **Taxonomy Reference**
http://data.europa.eu/949/linkToAdditionalDocuments

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The purposeofsfdeclaration
### General Information

**Number**: 1.1.6.7.30

**XML Name**: purposeOfSfDeclaration

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/purposeOfSfDeclaration

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The briefpresentation
### General Information

**Number**: 1.1.2.9.28

**XML Name**: briefPresentation

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/briefPresentation

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The operatorname
### General Information

**Number**: 1.1.2.6.21

**XML Name**: operatorName

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/operatorName

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The operator
### General Information

**Number**: 1.1.5.7.12

**XML Name**: operator

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/operator

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The operatortype
### General Information

**Number**: 1.1.9.5.62

**XML Name**: operatorType

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/operatorType

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The operatorothertype
### General Information

**Number**: 1.1.7.7.26

**XML Name**: operatorOtherType

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/operatorOtherType

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The operatorcontact
### General Information

**Number**: 1.1.4.1.99

**XML Name**: operatorContact

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/operatorContact

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The operatorphone
### General Information

**Number**: 1.1.1.8.44

**XML Name**: operatorPhone

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/operatorPhone

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The operatorfax
### General Information

**Number**: 1.1.8.9.13

**XML Name**: operatorFax

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/operatorFax

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The operatoremail
### General Information

**Number**: 1.1.3.7.86

**XML Name**: operatorEmail

**Deadline**: xx

### Data Format
* **Data Presentation**
*Hyperlink*
* **Taxonomy Reference**
http://data.europa.eu/949/operatorEmail

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The operatorwebsite
### General Information

**Number**: 1.1.6.5.42

**XML Name**: operatorWebsite

**Deadline**: xx

### Data Format
* **Data Presentation**
*Hyperlink*
* **Taxonomy Reference**
http://data.europa.eu/949/operatorWebsite

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The facilityowner
### General Information

**Number**: 1.1.9.3.64

**XML Name**: facilityOwner

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
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
	This property is considered as Type 1 property (General Information).

* **Regulation**: 
	None

------------------------------------------------------------

## ownerType
The ownertype
### General Information

**Number**: 1.1.4.5.98

**XML Name**: ownerType

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/ownerType

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The ownerothertype
### General Information

**Number**: 1.1.4.6.17

**XML Name**: ownerOtherType

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/ownerOtherType

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The operatorsrelation
### General Information

**Number**: 1.1.9.6.37

**XML Name**: operatorsRelation

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/operatorsRelation

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The sfdatavaliduntil
### General Information

**Number**: 1.1.6.1.75

**XML Name**: sfDataValidUntil

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/sfDataValidUntil

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The sfdataupdateprocedure
### General Information

**Number**: 1.1.7.8.59

**XML Name**: sfDataUpdateProcedure

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/sfDataUpdateProcedure

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The dateforupdate
### General Information

**Number**: 1.1.7.9.38

**XML Name**: dateForUpdate

**Deadline**: xx

### Data Format
* **Data Presentation**
*Datetime*
* **Taxonomy Reference**
http://data.europa.eu/949/dateForUpdate

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The applycompliance
### General Information

**Number**: 1.1.9.5.2

**XML Name**: applyCompliance

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/applyCompliance

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The complianceconfirmed
### General Information

**Number**: 1.1.8.8.42

**XML Name**: complianceConfirmed

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/complianceConfirmed

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The locomotivecleaning
### General Information

**Number**: 1.1.9.5.53

**XML Name**: locomotiveCleaning

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/locomotiveCleaning

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The wagoncleaning
### General Information

**Number**: 1.1.5.1.95

**XML Name**: wagonCleaning

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/wagonCleaning

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The locomotiveparking
### General Information

**Number**: 1.1.3.3.6

**XML Name**: locomotiveParking

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/locomotiveParking

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The wagonparking
### General Information

**Number**: 1.1.4.4.52

**XML Name**: wagonParking

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/wagonParking

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The locomotiverepairmaintenancelight
### General Information

**Number**: 1.1.8.6.45

**XML Name**: locomotiveRepairMaintenanceLight

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/locomotiveRepairMaintenanceLight

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The locomotiverepairmaintenanceheavy
### General Information

**Number**: 1.1.7.1.6

**XML Name**: locomotiveRepairMaintenanceHeavy

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/locomotiveRepairMaintenanceHeavy

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The wagonrepairmaintenancelight
### General Information

**Number**: 1.1.4.6.92

**XML Name**: wagonRepairMaintenanceLight

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/wagonRepairMaintenanceLight

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The wagonrepairmaintenanceheavy
### General Information

**Number**: 1.1.2.3.10

**XML Name**: wagonRepairMaintenanceHeavy

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/wagonRepairMaintenanceHeavy

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The technicalinspectionofrollingstock
### General Information

**Number**: 1.1.5.4.89

**XML Name**: technicalInspectionOfRollingStock

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/technicalInspectionOfRollingStock

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The refuelling
### General Information

**Number**: 1.1.3.9.47

**XML Name**: refuelling

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/refuelling

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The shunting
### General Information

**Number**: 1.1.3.5.84

**XML Name**: shunting

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/shunting

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The provisionemergencyequipment
### General Information

**Number**: 1.1.2.1.69

**XML Name**: provisionEmergencyEquipment

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/provisionEmergencyEquipment

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The securityservices
### General Information

**Number**: 1.1.2.1.31

**XML Name**: securityServices

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/securityServices

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The tractioncurrent
### General Information

**Number**: 1.1.4.6.37

**XML Name**: tractionCurrent

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/tractionCurrent

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The accesstotelecommunicationnetworks
### General Information

**Number**: 1.1.3.8.87

**XML Name**: accessToTelecommunicationNetworks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/accessToTelecommunicationNetworks

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The provisionsupplementaryinformation
### General Information

**Number**: 1.1.6.2.4

**XML Name**: provisionSupplementaryInformation

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/provisionSupplementaryInformation

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The otherservices
### General Information

**Number**: 1.1.9.4.22

**XML Name**: otherServices

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/otherServices

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The descriptionofservices
### General Information

**Number**: 1.1.4.6.35

**XML Name**: descriptionOfServices

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/descriptionOfServices

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The timetableservicetrains
### General Information

**Number**: 1.1.9.1.67

**XML Name**: timetableServiceTrains

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/timetableServiceTrains

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The facilitycertificates
### General Information

**Number**: 1.1.4.6.44

**XML Name**: facilityCertificates

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/facilityCertificates

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The loadingunloadingtranshipment
### General Information

**Number**: 1.1.7.5.89

**XML Name**: loadingUnloadingTranshipment

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/loadingUnloadingTranshipment

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The loadingunitcleaning
### General Information

**Number**: 1.1.9.6.74

**XML Name**: loadingUnitCleaning

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/loadingUnitCleaning

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The loadingunitfumigationdisinfection
### General Information

**Number**: 1.1.4.9.82

**XML Name**: loadingUnitFumigationDisinfection

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/loadingUnitFumigationDisinfection

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The loadingunitrepairmaintenance
### General Information

**Number**: 1.1.2.4.22

**XML Name**: loadingUnitRepairMaintenance

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/loadingUnitRepairMaintenance

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The loadingunitventilation
### General Information

**Number**: 1.1.6.2.82

**XML Name**: loadingUnitVentilation

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/loadingUnitVentilation

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The orderpickingwarehousing
### General Information

**Number**: 1.1.4.8.65

**XML Name**: orderPickingWarehousing

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/orderPickingWarehousing

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The storagecontainersgeneralcargo
### General Information

**Number**: 1.1.7.1.4

**XML Name**: storageContainersGeneralCargo

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/storageContainersGeneralCargo

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The storagedangerousgoods
### General Information

**Number**: 1.1.8.9.8

**XML Name**: storageDangerousGoods

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/storageDangerousGoods

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The storageridclasses
### General Information

**Number**: 1.1.4.2.6

**XML Name**: storageRidClasses

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/storageRidClasses

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The storagehandlingreefers
### General Information

**Number**: 1.1.3.3.22

**XML Name**: storageHandlingReefers

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/storageHandlingReefers

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The stuffingstripping
### General Information

**Number**: 1.1.4.6.90

**XML Name**: stuffingStripping

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/stuffingStripping

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The containerlashing
### General Information

**Number**: 1.1.2.9.18

**XML Name**: containerLashing

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/containerLashing

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The weighingwagonsloadingunits
### General Information

**Number**: 1.1.5.9.34

**XML Name**: weighingWagonsLoadingUnits

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/weighingWagonsLoadingUnits

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The containersalesleasing
### General Information

**Number**: 1.1.4.3.56

**XML Name**: containerSalesLeasing

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/containerSalesLeasing

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The customsclearance
### General Information

**Number**: 1.1.3.2.37

**XML Name**: customsClearance

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/customsClearance

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The trucking
### General Information

**Number**: 1.1.6.3.49

**XML Name**: trucking

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/trucking

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The tailormadecontractsdangerousgoods
### General Information

**Number**: 1.1.1.8.21

**XML Name**: tailormadeContractsDangerousGoods

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/tailormadeContractsDangerousGoods

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The tailormadecontractsabnormaltrains
### General Information

**Number**: 1.1.8.9.52

**XML Name**: tailormadeContractsAbnormalTrains

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/tailormadeContractsAbnormalTrains

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The trainboardingdeboarding
### General Information

**Number**: 1.1.5.7.99

**XML Name**: trainBoardingDeboarding

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/trainBoardingDeboarding

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The ticketingservices
### General Information

**Number**: 1.1.8.5.94

**XML Name**: ticketingServices

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/ticketingServices

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The assistanceforpersonswithreducedmobility
### General Information

**Number**: 1.1.8.2.44

**XML Name**: assistanceForPersonsWithReducedMobility

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/assistanceForPersonsWithReducedMobility

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The lostandfound
### General Information

**Number**: 1.1.7.3.45

**XML Name**: lostAndFound

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/lostAndFound

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The luggagestoring
### General Information

**Number**: 1.1.4.1.32

**XML Name**: luggageStoring

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/luggageStoring

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The waitingareasandweaterprotection
### General Information

**Number**: 1.1.3.1.91

**XML Name**: waitingAreasAndWeaterProtection

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/waitingAreasAndWeaterProtection

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The iceprotection
### General Information

**Number**: 1.1.8.9.95

**XML Name**: iceProtection

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/iceProtection

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The preheatingprecooling
### General Information

**Number**: 1.1.2.1.85

**XML Name**: preHeatingPreCooling

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/preHeatingPreCooling

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The sewagedisposalwatersupply
### General Information

**Number**: 1.1.6.7.54

**XML Name**: sewageDisposalWaterSupply

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/sewageDisposalWaterSupply

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The useofmotorailfacilities
### General Information

**Number**: 1.1.8.3.31

**XML Name**: useOfMotorailFacilities

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/useOfMotorailFacilities

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The longitude
### General Information

**Number**: 1.1.4.7.54

**XML Name**: longitude

**Deadline**: xx

### Data Format
* **Data Presentation**
*Real*
* **Taxonomy Reference**
http://data.europa.eu/949/longitude

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The latitude
### General Information

**Number**: 1.1.6.9.39

**XML Name**: latitude

**Deadline**: xx

### Data Format
* **Data Presentation**
*Real*
* **Taxonomy Reference**
http://data.europa.eu/949/latitude

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The crdprimarylocation
### General Information

**Number**: 1.1.6.9.20

**XML Name**: crdPrimaryLocation

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/crdPrimaryLocation

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The crdsubsidiarylocation
### General Information

**Number**: 1.1.8.9.74

**XML Name**: crdSubsidiaryLocation

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/crdSubsidiaryLocation

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The rinfoperationalpoint
### General Information

**Number**: 1.1.5.4.50

**XML Name**: rinfOperationalPoint

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/rinfOperationalPoint

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The facilitystreet
### General Information

**Number**: 1.1.4.6.35

**XML Name**: facilityStreet

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/facilityStreet

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The facilityzip
### General Information

**Number**: 1.1.2.5.72

**XML Name**: facilityZip

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/facilityZip

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The facilitytown
### General Information

**Number**: 1.1.9.6.43

**XML Name**: facilityTown

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/facilityTown

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The facilitycountry
### General Information

**Number**: 1.1.2.5.43

**XML Name**: facilityCountry

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/facilityCountry

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The connectiontopublicrailnetwork
### General Information

**Number**: 1.1.4.1.54

**XML Name**: connectionToPublicRailNetwork

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/connectionToPublicRailNetwork

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The facilitylocatedonrfc
### General Information

**Number**: 1.1.4.3.45

**XML Name**: facilityLocatedOnRfc

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/facilityLocatedOnRfc

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The roadaccessconditions
### General Information

**Number**: 1.1.9.6.76

**XML Name**: roadAccessConditions

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/roadAccessConditions

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The operationstatus
### General Information

**Number**: 1.1.7.2.62

**XML Name**: operationStatus

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/operationStatus

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The openingtimes
### General Information

**Number**: 1.1.3.5.81

**XML Name**: openingTimes

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/openingTimes

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The openondemand
### General Information

**Number**: 1.1.7.6.51

**XML Name**: openOnDemand

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/openOnDemand

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The totalnumberoftracks
### General Information

**Number**: 1.1.8.6.33

**XML Name**: totalNumberOfTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/totalNumberOfTracks

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The totalnumberofplatformtracks
### General Information

**Number**: 1.1.3.6.63

**XML Name**: totalNumberOfPlatformTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/totalNumberOfPlatformTracks

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The thereofelectrifiedplatformtracks
### General Information

**Number**: 1.1.1.6.16

**XML Name**: thereofElectrifiedPlatformTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/thereofElectrifiedPlatformTracks

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The maxusablelengthplatformtracks
### General Information

**Number**: 1.1.5.8.79

**XML Name**: maxUsableLengthPlatformTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/maxUsableLengthPlatformTracks

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The totalnumberoftranshipmenttracks
### General Information

**Number**: 1.1.2.8.56

**XML Name**: totalNumberOfTranshipmentTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/totalNumberOfTranshipmentTracks

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The thereofelectrifiedtranshipmenttracks
### General Information

**Number**: 1.1.4.6.35

**XML Name**: thereofElectrifiedTranshipmentTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/thereofElectrifiedTranshipmentTracks

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The maxusablelengthtranshipmenttracks
### General Information

**Number**: 1.1.4.5.38

**XML Name**: maxUsableLengthTranshipmentTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/maxUsableLengthTranshipmentTracks

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The totalnumberofstoragetracks
### General Information

**Number**: 1.1.9.9.87

**XML Name**: totalNumberOfStorageTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/totalNumberOfStorageTracks

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The thereofelectrifiedstoragetracks
### General Information

**Number**: 1.1.3.1.91

**XML Name**: thereofElectrifiedStorageTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/thereofElectrifiedStorageTracks

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The maxusablelengthstoragetracks
### General Information

**Number**: 1.1.6.1.20

**XML Name**: maxUsableLengthStorageTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/maxUsableLengthStorageTracks

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The totalnumberofshuntingtracks
### General Information

**Number**: 1.1.2.3.27

**XML Name**: totalNumberOfShuntingTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/totalNumberOfShuntingTracks

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The thereofelectrifiedshuntingtracks
### General Information

**Number**: 1.1.1.3.35

**XML Name**: thereofElectrifiedShuntingTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/thereofElectrifiedShuntingTracks

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The maxusablelengthshuntingtracks
### General Information

**Number**: 1.1.3.8.63

**XML Name**: maxUsableLengthShuntingTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/maxUsableLengthShuntingTracks

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The totalnumberofinboundoutboundtracks
### General Information

**Number**: 1.1.3.7.38

**XML Name**: totalNumberOfInboundOutboundTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/totalNumberOfInboundOutboundTracks

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The thereofelectrifiedinboundoutboundtracks
### General Information

**Number**: 1.1.5.1.56

**XML Name**: thereofElectrifiedInboundOutboundTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/thereofElectrifiedInboundOutboundTracks

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The maxusablelengthinboundoutboundtracks
### General Information

**Number**: 1.1.9.4.38

**XML Name**: maxUsableLengthInboundOutboundTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/maxUsableLengthInboundOutboundTracks

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The totalnumberofallocationtracks
### General Information

**Number**: 1.1.9.2.51

**XML Name**: totalNumberOfAllocationTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/totalNumberOfAllocationTracks

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The thereofelectrifiedallocationtracks
### General Information

**Number**: 1.1.6.2.22

**XML Name**: thereofElectrifiedAllocationTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/thereofElectrifiedAllocationTracks

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The maxusablelengthallocationtracks
### General Information

**Number**: 1.1.3.2.96

**XML Name**: maxUsableLengthAllocationTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/maxUsableLengthAllocationTracks

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The totalnumberofothertracks
### General Information

**Number**: 1.1.6.6.57

**XML Name**: totalNumberOfOtherTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/totalNumberOfOtherTracks

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The thereofelectrifiedothertracks
### General Information

**Number**: 1.1.3.2.49

**XML Name**: thereofElectrifiedOtherTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/thereofElectrifiedOtherTracks

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The maxusablelengthothertracks
### General Information

**Number**: 1.1.3.7.16

**XML Name**: maxUsableLengthOtherTracks

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/maxUsableLengthOtherTracks

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The descriptionoftechnicalcharacteristics
### General Information

**Number**: 1.1.9.6.34

**XML Name**: descriptionOfTechnicalCharacteristics

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/descriptionOfTechnicalCharacteristics

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The technicalmap
### General Information

**Number**: 1.1.7.4.94

**XML Name**: technicalMap

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/technicalMap

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The braketestfacility
### General Information

**Number**: 1.1.8.1.56

**XML Name**: brakeTestFacility

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/brakeTestFacility

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The compressedairsupply
### General Information

**Number**: 1.1.1.2.64

**XML Name**: compressedAirSupply

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/compressedAirSupply

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The turntable
### General Information

**Number**: 1.1.9.5.8

**XML Name**: turntable

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/turntable

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The locomotivewashingcleaning
### General Information

**Number**: 1.1.4.7.31

**XML Name**: locomotiveWashingCleaning

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/locomotiveWashingCleaning

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The wagonwashingcleaning
### General Information

**Number**: 1.1.6.7.74

**XML Name**: wagonWashingCleaning

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/wagonWashingCleaning

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The loadingunitwashingcleaning
### General Information

**Number**: 1.1.3.4.84

**XML Name**: loadingUnitWashingCleaning

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/loadingUnitWashingCleaning

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The maintenanceshoplight
### General Information

**Number**: 1.1.3.7.89

**XML Name**: maintenanceShopLight

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/maintenanceShopLight

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The maintenanceshopheavy
### General Information

**Number**: 1.1.5.6.2

**XML Name**: maintenanceShopHeavy

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/maintenanceShopHeavy

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The otherequipment
### General Information

**Number**: 1.1.1.4.48

**XML Name**: otherEquipment

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/otherEquipment

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The descriptiontechnicalequipment
### General Information

**Number**: 1.1.2.7.43

**XML Name**: descriptionTechnicalEquipment

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/descriptionTechnicalEquipment

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The numberofgantrycranes
### General Information

**Number**: 1.1.5.6.83

**XML Name**: numberOfGantryCranes

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/numberOfGantryCranes

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The numberofmobilecranes
### General Information

**Number**: 1.1.3.8.71

**XML Name**: numberOfMobileCranes

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/numberOfMobileCranes

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The horizontaltranshipmentsystems
### General Information

**Number**: 1.1.3.9.47

**XML Name**: horizontalTranshipmentSystems

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/horizontalTranshipmentSystems

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The headramp
### General Information

**Number**: 1.1.8.5.84

**XML Name**: headRamp

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/headRamp

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The sideramp
### General Information

**Number**: 1.1.5.8.94

**XML Name**: sideRamp

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/sideRamp

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The loadinglane
### General Information

**Number**: 1.1.7.2.97

**XML Name**: loadingLane

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/loadingLane

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The hump
### General Information

**Number**: 1.1.8.8.15

**XML Name**: hump

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/hump

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The trackscale
### General Information

**Number**: 1.1.2.5.78

**XML Name**: trackScale

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/trackScale

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The opticalcharacterrecognition
### General Information

**Number**: 1.1.5.7.59

**XML Name**: opticalCharacterRecognition

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/opticalCharacterRecognition

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The numberofreeferconnections
### General Information

**Number**: 1.1.3.2.16

**XML Name**: numberOfReeferConnections

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/numberOfReeferConnections

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The storageaream2
### General Information

**Number**: 1.1.2.9.22

**XML Name**: storageAreaM2

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/storageAreaM2

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The storageareateu
### General Information

**Number**: 1.1.8.8.5

**XML Name**: storageAreaTeu

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/storageAreaTeu

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The emptycontainerdepot
### General Information

**Number**: 1.1.2.5.88

**XML Name**: emptyContainerDepot

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/emptyContainerDepot

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The numberofplatforms
### General Information

**Number**: 1.1.2.1.90

**XML Name**: numberOfPlatforms

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/numberOfPlatforms

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The maxplatformlength
### General Information

**Number**: 1.1.9.6.50

**XML Name**: maxPlatformLength

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/maxPlatformLength

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The maxplatformheight
### General Information

**Number**: 1.1.7.5.37

**XML Name**: maxPlatformHeight

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/maxPlatformHeight

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The minplatformheight
### General Information

**Number**: 1.1.6.1.44

**XML Name**: minPlatformHeight

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/minPlatformHeight

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The escalatorrampforplatformaccess
### General Information

**Number**: 1.1.2.3.74

**XML Name**: escalatorRampForPlatformAccess

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/escalatorRampForPlatformAccess

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The weatherprotectionforpassengers
### General Information

**Number**: 1.1.6.4.56

**XML Name**: weatherProtectionForPassengers

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/weatherProtectionForPassengers

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The plannedchangestechnicalcharacteristics
### General Information

**Number**: 1.1.4.3.75

**XML Name**: plannedChangesTechnicalCharacteristics

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/plannedChangesTechnicalCharacteristics

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The informationoncharges
### General Information

**Number**: 1.1.4.2.55

**XML Name**: informationOnCharges

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/informationOnCharges

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The informationondiscounts
### General Information

**Number**: 1.1.1.8.31

**XML Name**: informationOnDiscounts

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/informationOnDiscounts

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The publicaccessibility
### General Information

**Number**: 1.1.8.3.56

**XML Name**: publicAccessibility

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/publicAccessibility

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The legalrequirements
### General Information

**Number**: 1.1.4.8.22

**XML Name**: legalRequirements

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/legalRequirements

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The electrifiedrailaccesspossible
### General Information

**Number**: 1.1.8.5.43

**XML Name**: electrifiedRailAccessPossible

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/electrifiedRailAccessPossible

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The maxpermittedtrainlength
### General Information

**Number**: 1.1.6.2.50

**XML Name**: maxPermittedTrainLength

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/maxPermittedTrainLength

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The maxpermittedaxleload
### General Information

**Number**: 1.1.2.7.51

**XML Name**: maxPermittedAxleLoad

**Deadline**: xx

### Data Format
* **Data Presentation**
*Real*
* **Taxonomy Reference**
http://data.europa.eu/949/maxPermittedAxleLoad

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The mintrackradius
### General Information

**Number**: 1.1.3.4.16

**XML Name**: minTrackRadius

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/minTrackRadius

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The clearancegauge
### General Information

**Number**: 1.1.1.8.62

**XML Name**: clearanceGauge

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/clearanceGauge

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The lengthofaccessbranchline
### General Information

**Number**: 1.1.7.4.10

**XML Name**: lengthOfAccessBranchLine

**Deadline**: xx

### Data Format
* **Data Presentation**
*Real*
* **Taxonomy Reference**
http://data.europa.eu/949/lengthOfAccessBranchLine

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The accesslineelectrification
### General Information

**Number**: 1.1.3.1.25

**XML Name**: accessLineElectrification

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/accessLineElectrification

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The accesslinemaxpermittedtrainlength
### General Information

**Number**: 1.1.5.5.97

**XML Name**: accessLineMaxPermittedTrainLength

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/accessLineMaxPermittedTrainLength

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The accesslinemaxaxleload
### General Information

**Number**: 1.1.8.7.71

**XML Name**: accessLineMaxAxleLoad

**Deadline**: xx

### Data Format
* **Data Presentation**
*Real*
* **Taxonomy Reference**
http://data.europa.eu/949/accessLineMaxAxleLoad

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The accesslinemintrackradius
### General Information

**Number**: 1.1.4.8.30

**XML Name**: accessLineMinTrackRadius

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/accessLineMinTrackRadius

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The accesslineclearancegauge
### General Information

**Number**: 1.1.2.9.60

**XML Name**: accessLineClearanceGauge

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/accessLineClearanceGauge

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The accesslinemaxincline
### General Information

**Number**: 1.1.8.6.27

**XML Name**: accessLineMaxIncline

**Deadline**: xx

### Data Format
* **Data Presentation**
*Real*
* **Taxonomy Reference**
http://data.europa.eu/949/accessLineMaxIncline

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The containeracceptance
### General Information

**Number**: 1.1.4.4.50

**XML Name**: containerAcceptance

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/containerAcceptance

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The containersizelimit
### General Information

**Number**: 1.1.5.9.70

**XML Name**: containerSizeLimit

**Deadline**: xx

### Data Format
* **Data Presentation**
*Real*
* **Taxonomy Reference**
http://data.europa.eu/949/containerSizeLimit

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The containerweightlimit
### General Information

**Number**: 1.1.4.5.31

**XML Name**: containerWeightLimit

**Deadline**: xx

### Data Format
* **Data Presentation**
*Real*
* **Taxonomy Reference**
http://data.europa.eu/949/containerWeightLimit

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The swapbodyacceptance
### General Information

**Number**: 1.1.4.7.90

**XML Name**: swapBodyAcceptance

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/swapBodyAcceptance

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The swapbodysizelimit
### General Information

**Number**: 1.1.9.8.51

**XML Name**: swapBodySizeLimit

**Deadline**: xx

### Data Format
* **Data Presentation**
*Real*
* **Taxonomy Reference**
http://data.europa.eu/949/swapBodySizeLimit

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The swapbodyweightlimit
### General Information

**Number**: 1.1.1.5.50

**XML Name**: swapBodyWeightLimit

**Deadline**: xx

### Data Format
* **Data Presentation**
*Real*
* **Taxonomy Reference**
http://data.europa.eu/949/swapBodyWeightLimit

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The traileracceptance
### General Information

**Number**: 1.1.6.5.25

**XML Name**: trailerAcceptance

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/trailerAcceptance

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The trailersizelimit
### General Information

**Number**: 1.1.3.3.43

**XML Name**: trailerSizeLimit

**Deadline**: xx

### Data Format
* **Data Presentation**
*Real*
* **Taxonomy Reference**
http://data.europa.eu/949/trailerSizeLimit

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The trailerweightlimit
### General Information

**Number**: 1.1.8.5.9

**XML Name**: trailerWeightLimit

**Deadline**: xx

### Data Format
* **Data Presentation**
*Real*
* **Taxonomy Reference**
http://data.europa.eu/949/trailerWeightLimit

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The trucktraileracceptance
### General Information

**Number**: 1.1.2.2.45

**XML Name**: truckTrailerAcceptance

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/truckTrailerAcceptance

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The conventionalcargoacceptance
### General Information

**Number**: 1.1.2.2.55

**XML Name**: conventionalCargoAcceptance

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/conventionalCargoAcceptance

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The palletisedgoods
### General Information

**Number**: 1.1.1.9.32

**XML Name**: palletisedGoods

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/palletisedGoods

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The bulk
### General Information

**Number**: 1.1.4.3.59

**XML Name**: bulk

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/bulk

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The fluidsandgas
### General Information

**Number**: 1.1.9.5.47

**XML Name**: fluidsAndGas

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/fluidsAndGas

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The dangerousgoods
### General Information

**Number**: 1.1.3.3.54

**XML Name**: dangerousGoods

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/dangerousGoods

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The ridclasses
### General Information

**Number**: 1.1.1.1.89

**XML Name**: ridClasses

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/ridClasses

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The wood
### General Information

**Number**: 1.1.6.9.63

**XML Name**: wood

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/wood

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The heavyloads
### General Information

**Number**: 1.1.2.9.61

**XML Name**: heavyLoads

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/heavyLoads

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The reefercargo
### General Information

**Number**: 1.1.6.6.52

**XML Name**: reeferCargo

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/reeferCargo

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The othercargotypes
### General Information

**Number**: 1.1.8.3.89

**XML Name**: otherCargoTypes

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/otherCargoTypes

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The selfsupplyofrailrelatedservices
### General Information

**Number**: 1.1.9.7.73

**XML Name**: selfSupplyOfRailRelatedServices

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/selfSupplyOfRailRelatedServices

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The itsystems
### General Information

**Number**: 1.1.1.9.48

**XML Name**: itSystems

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/itSystems

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The requestsforaccessorservices
### General Information

**Number**: 1.1.7.5.73

**XML Name**: requestsForAccessOrServices

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/requestsForAccessOrServices

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The bookingconditions
### General Information

**Number**: 1.1.6.5.10

**XML Name**: bookingConditions

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/bookingConditions

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The responsetorequests
### General Information

**Number**: 1.1.2.1.41

**XML Name**: responseToRequests

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/responseToRequests

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The availablecapacity
### General Information

**Number**: 1.1.4.9.50

**XML Name**: availableCapacity

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/availableCapacity

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The temporarycapacityrestrictions
### General Information

**Number**: 1.1.9.1.2

**XML Name**: temporaryCapacityRestrictions

**Deadline**: xx

### Data Format
* **Data Presentation**
*String*
* **Taxonomy Reference**
http://data.europa.eu/949/temporaryCapacityRestrictions

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The cooperationbetweensfandim
### General Information

**Number**: 1.1.5.4.45

**XML Name**: cooperationBetweenSfAndIm

**Deadline**: xx

### Data Format
* **Data Presentation**
-
* **Taxonomy Reference**
http://data.europa.eu/949/cooperationBetweenSfAndIm

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
The statuschange
### General Information

**Number**: 1.1.9.8.20

**XML Name**: statusChange

**Deadline**: xx

### Data Format
* **Data Presentation**
*Integer*
* **Taxonomy Reference**
http://data.europa.eu/949/statusChange

### Belongs to parameters group

None

### Flags

* **Applicability Flags**:
Y/N/NYA

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
