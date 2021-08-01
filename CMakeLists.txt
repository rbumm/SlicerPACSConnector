cmake_minimum_required(VERSION 3.13.4)

project(SlicerPACSConnector)

#-----------------------------------------------------------------------------
# Extension meta-information
set(EXTENSION_HOMEPAGE "https://www.slicer.org/wiki/Documentation/Nightly/Extensions/SlicerPACSConnector")
set(EXTENSION_CATEGORY "Utilities")
set(EXTENSION_CONTRIBUTORS "Rudolf Bumm (KSGR)")
set(EXTENSION_DESCRIPTION "The PACS Connector extension enables querying your local or remote PACS from a clear and easily accessible interface within 3D Slicer and offers new filter parameters.")
set(EXTENSION_ICONURL "https://raw.githubusercontent.com/rbumm/SlicerPACSConnector/master/SlicerPACSConnector.png")
set(EXTENSION_SCREENSHOTURLS "https://user-images.githubusercontent.com/18140094/127771219-393deea0-c531-4592-bd1f-0a988a55f400.png")
set(EXTENSION_DEPENDS "NA") # Specified as a list or "NA" if no dependencies

#-----------------------------------------------------------------------------
# Extension dependencies
find_package(Slicer REQUIRED)
include(${Slicer_USE_FILE})

#-----------------------------------------------------------------------------
# Extension modules
add_subdirectory(SlicerPACSConnector)
## NEXT_MODULE

#-----------------------------------------------------------------------------
include(${Slicer_EXTENSION_GENERATE_CONFIG})
include(${Slicer_EXTENSION_CPACK})
