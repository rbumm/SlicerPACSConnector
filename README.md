# SlicerPACSConnector

The SlicerPACSConnector is a 3D Slicer extension that offers a simple and clear interface between 3D Slicer and your local or remote PACS.  
You can choose between a simple "query" as well as a "query and retrieve from PACS" including the transfer of the image data to Slicers' DICOM database.

Supported query filters:

*   PatientID (required)
*   Modality
*   AccessionNumber
*   Series Description (projected)
*   Date of Examination

This extension (and Slicer) supports reading from PACS only. SlicerPACSConnector undergoes continuous testing with a hospital GEPACS as well as public PACS servers.  

Slicer 4.13.xx and a recent CTK are required.

_This project is in active development and is not FDA approved_
