# Monitoring AWS Elemental MediaConvert Jobs<a name="monitoring-overview"></a>

You can keep on top of your AWS Elemental MediaConvert jobs in these ways:

+ The *AWS Elemental MediaConvert Recent Jobs* page shows the status of your jobs\. Access it by opening the AWS Elemental MediaConvert console and choosing **Jobs** in the navigation pane\. You might need to choose the menu icon \(the three\-bar icon\) in the upper\-left corner of the console to open this navigation pane\.

+ *Amazon CloudWatch* monitors your AWS resources and the applications that you run on AWS in real\-time\. You can collect and track metrics, create customized dashboards, and set alarms that notify you or that take actions when a specified metric reaches a threshold that you specify\. For example, you can have CloudWatch track the number of successful jobs over a specified period of time\. For more information, see the [Amazon CloudWatch User Guide](http://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/)\. For a list of the AWS Elemental MediaConvert metrics that CloudWatch tracks, see [[ERROR] BAD/MISSING LINK TEXT](MediaConvert-metrics.md)\.

+ *Amazon CloudWatch Events* delivers a near real\-time stream of system events that describe changes in AWS resources\. You can use CloudWatch Events to set up notifications for your job status changes\. For more information and a tutorial on setting up job notifications, see [[ERROR] BAD/MISSING LINK TEXT](cloudwatch_events.md)\.

  You can also use CloudWatch Events to trigger automated actions in other AWS services when these events happen\. A common use case for CloudWatch Events with AWS Elemental MediaConvert is to trigger a Lambda function to initiate your postprocessing\. For more information, see the [Amazon CloudWatch Events User Guide](http://docs.aws.amazon.com/AmazonCloudWatch/latest/events/)\.

+ *AWS CloudTrail* captures API calls and related events made by or on behalf of your AWS account and delivers the log files to an Amazon S3 bucket that you specify\. You can identify which users and accounts called AWS, the source IP address from which the calls were made, and when the calls occurred\. For more information, see [](logging-using-cloudtrail.md)\.