# dita_keys_examples
A set of DITA examples displaying how keys can be deployed step-by-step. Designed to illustrate how keys can be used. 

The original target document for this is an out-of-copyright version of a manual for the TRS-80 Expansion Interface, dating to the late 1970s. The original version of it can be found on the Project Gutenberg website at: https://www.gutenberg.org/ebooks/27469. The content has been lightly "DITA-fied", just enough to hopefully make it effective as a set of sample files. It also shows how far technical communications has come since the time this was originally published!

*An Explanation for Each Set of Files*
01 - TRS80 Expansion Pack (No Keys)	
The original, non-keyed version of the manual.

01b - TRS80 Expansion Pack (Keys Values Defined in Map)
Key values for company name, product name, etc. are defined directly in the map. This version is labelled "b" as the following sets of files do not continue with this approach.

02 - TRS80 Expansion Pack (Conkeyrefs for Product Names)	
Building upon the original "01" example, conkeyres are used for such things as company name, product name, etc. Demonstrates the interaction between the keydef in the map that points to a topic holding these values, which are then "called" within the other topics within the same map at output.

03 - TRS80 Expansion Pack (Images Warehoused)
Building upon the previous "02" example, demonstrates how to build an "image warehouse" for storing keys that reference all of the images that are used in the manual.

04 - TRS80 Expansion Pack (Topicrefs Keyed)
Building upon the previous "03" example, this version takes things a step further and builds a key-based "warehouse" topic that holds all of the content topics used in the manual.

05 - TRS80 Expansion Pack (Conditionalized)
Building upon the previous "04" version, this example sets conditions for product="TRS80" or product="TRS90" in the keydefs that are set in the map, which build two different versions of the manual at output when used in conjunction with either of the two ditavals that are provided.
