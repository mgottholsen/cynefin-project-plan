# Project Cynefin

Cynefin is a Welsh word meaning haunt, habitat, acquainted, accustomed, familiar. It carries with it a sense of rootedness--temporal, physical, cultural or spiritual. The word is similar in meaning to Heimat in German and has been compared to the Maori word turangawaewae, a place to stand. The idea of the Cynefin framework is that it offers decision-makers a "sense of place" from which to view their perceptions.

--------------------------------------------------------------------------------

## Brief

The goal of this project is to utilize, analyze and store multiple streams of raster & vector location related data, to create a multi-modal remote sensing platform for Louisville Metro Government.

## Immediate Enterprise Use Cases

There are any number of use cases for leveraging image-related data within a governmental body. This Innovation Project not only leverages existing or low cost commodity hardware for remote sensing & data collection, it also proves that low cost and intelligent smart city technology is in the reach of most cities.

- General: Environmental GIS data capture

- General: Built Environment Analytics

- General: Vehicle Make/Model Analytics

- Public Safety: Real Time Crime Center

- Public Works: Asset Identification & Cataloging

- Traffic: Flow & Usage Analysis

- Predictive Pavement Condition

- PARC: Enforcement

- Sustainability: Tree Identification

- Air Pollution Control District: Vehicle Make/Model Analytics for Pollution

## Example Uses Cases

### Mapillary

- <https://blog.mapillary.com/update/2018/01/12/helsingborg.html>
- <https://blog.mapillary.com/update/2018/01/15/autonomous-intelligent-driving-mapillary-vistas.html>

## Data Sources

### KYTC

KYTC has a photolog viewer from their asset collection vehicles. I believe they run interstates once a year and state routes every 2\. Chad Shive (Chad.Shive@ky.gov) is the engineer over that program but it appears Jason Watson is the Technician that oversees it.

<https://transportation.ky.gov/Maintenance/Pages/Pavement-Data-Collection.aspx>

<http://roadview-images.kytc.ky.gov/Van3_Mandli_Data_6/03-23-2017/2017_V3_100-KY-2298N/2017_V3_100-KY-2298N/Front/Dir_000/F_00001.jpg>

<http://maps.kytc.ky.gov/photolog/?config=Photolog&x1=5114935.959483551&y1=3868453.589951066&x2=5427435.959483551&y2=3971969.214951066&MODE=PL>

--------------------------------------------------------------------------------

### Long Term Integration Phases

_Proof of Concept_

- Commodity based modified hardware

  - Yi 4K Action Camera

_Public Safety Pilot_

Real Time Crime Center Axis camera integration

_Phase 1_

- Existing Public Safety video sensor network (potential DeepLens hook?)
- Drone imagery

_Phase 2_

- Axon (Taser) video sensors
- Multiple LIDAR sources

--------------------------------------------------------------------------------

### Technical Considerations

--------------------------------------------------------------------------------

### Process Flow

--------------------------------------------------------------------------------

### Long Term Maintenance & Requirements

--------------------------------------------------------------------------------

### Architecture

#### Metro Assets

#### Amazon Web Services

- S3 block storage
- Machine learning services

  - Amazon SageMaker (build ML training models)
  - Amazon Rekognition

#### SaaS (Software as a Service, cloud based)

- [Mapillary]()
- [OpenALPR]()

--------------------------------------------------------------------------------

### Costs

--------------------------------------------------------------------------------

#### Labor

#### SaaS (Software as a Service, cloud based)

OpenALPR

Requests  |      Cost
--------- | --------:
2,000     |      Free
50,000    | $49/month
250,000   |      $195
2,000,000 |      $995

Mapillary

Requests |    Cost
-------- | ------:
50,000   |    Free
500,000  |    $250
500,000+ | Contact

--------------------------------------------------------------------------------

### Available Grants & Funding Strategies

--------------------------------------------------------------------------------

### Policy

--------------------------------------------------------------------------------

#### Privacy

#### Retention

--------------------------------------------------------------------------------

## Definitions

Remote sensing

GIS

LIDAR

AWS

Machine Learning

--------------------------------------------------------------------------------
