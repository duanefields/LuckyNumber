Just playing around with Serverless and Alexa. Couple of weird things:

  * it didn't seem to show the ARN to me unless you deploy with --verbose
  * the arn had a ":2" on the end, that wasn't present in the lamda console, and thus was invalid
  * you have to prefix the app name when you ask Alexa, "Ask Lucky Number XXXX"
