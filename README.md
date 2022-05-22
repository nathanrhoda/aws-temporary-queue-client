# aws-temporary-queue-client
Amazon SQS Nodes Js Temporary Queue Client

This repository contains code that will allow you to send a message to aws sqs based on the payload you supply 
you can either receive the name of the sqs queue where you can find the response or return the message from that queue immediately
to faciliate a request response experience.

Clients endpoint options
1) sendAndReceiveMessage
2) sendMessage

Example of how to use this client can be found in example folder

Building blocks to convert this into a AWS layer can also be found in layer folder
