# JCassDefaultRoadModel V2

 Updated Version for the V1 [Default Road Network Model](https://lonrix-limited.github.io/jcass_nzla_models_v2_docs/). 
 This model is identical to the V1 model, but with
 inputs refactored to suit the input structure for Juno Cassandra web. This version will not work on the
 now deprecated Windows Forms Desktop  application. It will, however, work with Juno Cassandra Web version
 and with the Command Line Interface (CLI) desktop version of Cassandra.

 ## This Release

 A key change in this model is that - with Juno Cassandra Web versionb - unit rates for treatments are no
 longer held in the model setup file, but rather on the 'lkp_unit-rates'sheet of the mandatory 'lookups.xlsx'
 file in your 'inputs' folder. This allows you to specify unit rates for all treatments at the project level
 and in one single place.


 

 
