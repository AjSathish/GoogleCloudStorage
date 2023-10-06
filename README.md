# GoogleCloudStorage

## Description:

This module can be used to generate an Access Token, create and delete buckets in Google Cloud Platform Cloud Storage. Additionally, you can upload images and files, copy objects from one bucket to another, delete objects, retrieve objects from the bucket, and retrieve a list of all buckets.

## Dependencies

Mendix Version 10.1.1 or Higher
Community Commons

## How to configure:

1. Update the ClientID, ClientSecret, and ProjectID Constants provided in the Constants folder.
2. Configure the Generate_AccessToken page to obtain the necessary access token.
3. Configure the Bucket_Operations page to perform bucket-based operations.
4. Update the RedirectUri constant based on 'Callback' service provided in the module under Resources folder.
Example of RedirectUri value ('http://localhost:8081/rest/myservice/v1/callback')
