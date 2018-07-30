# Nucleus-Annotation-3D
A plugin for ImageJ that helps in annotating nuclei in a 3D image stack

A Fiji plugin set to annotate image stacks of 3D spheroids.

The Nucleus Annotation 3D plugin can be used to annotate the centres of the nuclei in the image. The user selects the nucleus channel and with mouse clicks in the image sets the centre point of each nucleus. In order to help the user remember which nuclei have been handled, the user can add a top-to-bottom visualization to annotated nuclei. This display is saved as well and can be used as a separate annotation. Finally, the user can also assign a migration mode to the nucleus.
The Sphroid annotation 3D plugin is used to create an approximation of the edge of the spheroid. The user can add four points to the image at the edge of the spheroid and the plugin will create a sphere through these points. The user can adjust the sphere to better fit the spheroid edge. The annotated sphere can be used in the Feature Extractor 3D plugin of the 
This project uses the following dependencies:

My Utils base package for these types of plugins
The ImageJ IJ package
Please note that the current pom uses a local system path to various of the dependencies as they do not have a proper maven repository yet. Please update these paths to your own system if you wish to use this pom file
