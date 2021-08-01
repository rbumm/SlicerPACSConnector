# PACS Connector

The  PACS Connector is a 3D Slicer extension that offers a simple and clear interface between 3D Slicer and your local or remote PACS.  
You can choose between a simple "query" as well as a "query and retrieve from PACS" including the transfer of the image data to Slicers' DICOM database.

Supported query filters:

*   PatientID (required)
*   Modality
*   AccessionNumber
*   Series Description (projected)
*   Date of Examination

The possibility to query PACS data according to their AccessionNumber (new) is helpful because this key identifies the order in the DICOM worklist. 

Adding a query substring to Series Description (new) allows to retrieve smaller datasets with only the series that you need to import into Slicer.   

This extension (and Slicer) supports reading from PACS only. SlicerPACSConnector undergoes continuous testing with a hospital GEPACS as well as public PACS servers.  

Slicer 4.13.xx and a recent CTK are required.

_This project is in active development and is not FDA approved_

_Screenshot:_

![](https://user-images.githubusercontent.com/18140094/127771219-393deea0-c531-4592-bd1f-0a988a55f400.png)
