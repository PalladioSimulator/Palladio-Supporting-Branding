Branding Plug-In for Palladio Projects
--------------------------------------

Author: Sebastian Lehrig
Date: 2015/07/04

Features using this plug-in as a "branding plug-in" will be listed as Palladio
Simulator features in the Eclipse "about" dialog. Note that the branding plug-in
has also to be added to the feature's plug-in dependencies.

Limitations:
- Under "installation details", the branding plug-in overrides the "feature name"
  This behavior is actually a bug:
  https://bugs.eclipse.org/bugs/show_bug.cgi?id=163169

Additional information about branding plug-ins are here:
- Brief introduction: https://ekkescorner.wordpress.com/2010/06/13/brand-your-feature-and-be-part-of-about-eclipse/
- Detailed introduction: https://eclipse.org/articles/Article-Branding/branding-your-application.html
- Best practices: https://wiki.eclipse.org/Modeling_Project_Releng/Plugin_And_Feature_Files
