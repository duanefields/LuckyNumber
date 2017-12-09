Just playing around with Serverless and Alexa. Couple of weird things:

  * it didn't seem to show the ARN to me unless you deploy with --verbose
  * alternative, `sls info -v`
  * the arn had a ":2" (version number) on the end, which should not be included
  * you have to prefix the app name when you ask Alexa, "Ask Lucky Number XXXX"
