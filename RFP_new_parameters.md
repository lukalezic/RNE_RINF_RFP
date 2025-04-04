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
