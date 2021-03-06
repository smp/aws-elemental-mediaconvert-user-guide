# Including SCTE\-35 Markers in AWS Elemental MediaConvert Outputs<a name="including-scte-35-markers"></a>

In a transport stream asset, SCTE\-35 markers indicate where downstream systems can insert other content \(usually advertisements or local programs\)\. In HLS outputs, the manifest might contain SCTE\-35 metadata as well\. 

With this feature, you have three options:

+ Pass markers through from the input to the output\.

+ Include SCTE\-35 information in your HLS manifest\.

+ Blank out content during ad avails\.

By default, the service removes SCTE\-35 markers from the output, and therefore doesn't include SCTE\-35 information in HLS manifests or do ad avail blanking\.

**Note**  
AWS Elemental MediaConvert does not process information from input manifests\.