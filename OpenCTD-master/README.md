# Meet the OpenCTD!

The ocean is not uniform, it its filled with swirling eddies, temperature boundaries, layers of high and low salinity, changing densities, and other physical characteristics invisible to surface observers. By measuring salinity, temperature, and depth, scientists can unlock ocean patterns hidden beneath the sea's surface. To reveal these patterns, oceanographers use a CTD—an instrument that measures Conductivity (which serves as a proxy for salinity), Temperature, and absolute pressure (used to determine water Depth). 

![OpenCTD](https://github.com/OceanographyforEveryone/OpenCTD/blob/master/Images/IMG_20190614_141121.jpg)

CTDs come in a variety of shapes, sizes, and applications. Most oceanographic vessels have a CTD connected to a rosette system, which can house other instruments and collect physical water samples in parallel with real-time data collection. CTDs are also commonly attached to moorings, autonomous underwater vehicles (AUVs), remote-operated vehicles (ROVs), and, on occasion, marine animals.  

Commercial CTDs are expensive, with the most affordable models costing as much as $6,000.00. For near-shore oceanographic research on the continental shelf, where the water depth rarely exceeds 200 meters, this can be a prohibitive cost. The expense of the CTD is a barrier-to-entry for formal and informal researchers working with limited budgets, including scientists from developing nations, citizen oceanographers, environmental educators, and students of all levels interested in understanding their local coasts and waterways. 

Climate change, ocean acidification, and sea level rise have created an urgent need for extensive, high-resolution measurements of oceanographic conditions both globally and locally. At the same time, government funding at both state and federal levels for climate change research can be unreliable, if not wholly non-existent. This creates a pressing need for low-cost alternatives to common scientific instruments that allow formal researchers to stretch the impact of extant funding awards while simultaneously allowing informal researchers (such as environmental monitoring organizations and non-governmental organizations, as well as concerned community members) to contribute water-quality measurements. The OpenCTD can help fill that need.

The OpenCTD is a low-cost, open-source CTD designed intentionally for citizen scientists, educators, and researchers working in nearshore coastal ecosystems, where entire research projects can be conducted for less than the cost of a commercial CTD. It was developed by a core team of marine ecologists in collaboration with a distributed community of scientists, engineers, makers, and conservation practitioners. It is assembled from components commonly available at large hardware stores or through major online retailers. An Arduino-based microcontroller controls a battery of sensors sealed within a PVC pipe. Power is provided by a standard 3.7V lithium polymer battery and data is stored as a tab-delimited text-file accessed via SD card. 

The OpenCTD is design to be built by the end-user, providing both access to the tools of oceanography and the skills to maintain, repair, and replace OpenCTDs. For educators looking a for novel, in-depth, hands-on STEM experience for advanced students, the process of building an OpenCTD can offer a great introduction to coding, 3D-printing, hardware prototyping, and electronics. Construction of an OpenCTD can provide a practical foundation for courses in oceanography, environmental science, or physics. 

In this repository, you will find all the support documentation necessary to construct and operrate your own OpenCTD. All software and shapefiles are released open-source with no restrictions on use. 

As you build your OpenCTD please reach out to the team at Oceanography for Everyone if you have any questions or feedback about the process. We love to keep up with the community of people constructing and using these devices. During assembly and while using an OpenCTD or other Oceanography for Everyone tools, please consider tweeting or Instagramming using the hashtag #HackTheOcean so that the community can follow your efforts.

## Core Resources

The full construction and operation manual is maintained here: __[OpenCTD Construction and Operation](https://github.com/OceanographyforEveryone/OpenCTD/blob/master/OpenCTD_Feather_Adalogger/OpenCTD_ConstructionOperation.pdf)__.

The OpenCTD core software is found here: [__OpenCTD_master_m0.ino__](https://github.com/OceanographyforEveryone/OpenCTD/tree/master/OpenCTD_Feather_Adalogger/OpenCTD_master_m0)

Support Code, including the revised Serial Protocol described in the manual and the conductivity calibration software is found here: [__Support_Code__](https://github.com/OceanographyforEveryone/OpenCTD/tree/master/OpenCTD_Feather_Adalogger/Support_Code)

3D-printable shape files can be found here: [__3D_Printer_Files_m0__](https://github.com/OceanographyforEveryone/OpenCTD/tree/master/OpenCTD_Feather_Adalogger/3D_Printer_Files_m0)
