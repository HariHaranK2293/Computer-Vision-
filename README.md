# Computer-Vision
The outcome of the project is to identify the sleeves, chest area, collar area and neck area. 
The output is achived by using labelimg. Using it we can generate XML file using pascalVOC.
Then the XML file is parsed using xml.etree to find the xmin, ymin, xmax, ymax.
By using cv2 we can read the image and mark the objects from the names and obj in XML.
The object is marked by using the parsed XML and the image given.
