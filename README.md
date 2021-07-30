# SlicerPACSConnector

The SlicerPACSConnector is a 3D Slicer extension that offers a simple and clear interface between 3D Slicer and your local or remote PACS.  
You can choose between a simple "query" as well as a "query and retrieve from PACS" including the transfer of the image data to Slicers's DICOM database.

Supported query filters:

*   PatientID (required)
*   Modality
*   AccessionNumber
*   Series Description (projected)
*   Date of Examination

This extension (and Slicer) supports reading from PACS only. It undergoes continuous testing with a hospital GEPACS (KSGR, Switzerland) as well as public PACS servers.  

Slicer 4.13.xx with the most recent CTK is required.
