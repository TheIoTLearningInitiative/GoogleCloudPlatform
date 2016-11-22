# Introduction

> Google Cloud Platform. Build What's Next. Better software. Faster. [Homepage](https://cloud.google.com/)

- [Google Cloud Platform Github](https://github.com/GoogleCloudPlatform)
- [Cloud Vision API Python samples](https://github.com/GoogleCloudPlatform/python-docs-samples)
- [Google API Python Client](https://github.com/google/google-api-python-client)

> - Try Compute Engine. Create a Linux virtual machine instance in Compute Engine in this guided walkthrough.
> - Learn to use Cloud Storage. Cloud Storage is a powerful and simple storage service. In this tutorial you’ll learn the basics by creating a storage bucket, and then uploading and sharing a sample file as a public URL link.
> - Try App Engine. Create and deploy a Hello World app
> - Learn Google Cloud Platform. Take an interactive tutorial now and learn how to deploy and build simple applications.
> - Use Google APIs. enable APIS, create credentials and track your usage.
> - Create a Cloud SWL Interface. CloudSQL is a MySQL database that runs in Google's cloud, with no installation and maintenance required
> - Documentation

```sh
root@edison:~/CodeLabs/EkBalam# wget http://pngimg.com/upload/face_PNG5660.png
--2016-11-22 04:05:58--  http://pngimg.com/upload/face_PNG5660.png
Resolving pngimg.com... 104.28.15.90, 104.28.14.90, 2400:cb00:2048:1::681c:e5a, ...
root@edison:~# curl https://sdk.cloud.google.com | bash
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100   421    0   421    0     0    712      0 --:--:-- --:--:-- --:--:--   860
Downloading Google Cloud SDK install script: https://dl.google.com/dl/cloudsdk/channels/rapid/install_google_cloud_sdk.bah
######################################################################## 100.0%
Running install script from: /tmp/tmp.kCrXrUtLHV/install_google_cloud_sdk.bash
which curl
curl -# -f https://dl.google.com/dl/cloudsdk/channels/rapid/google-cloud-sdk.tar.gz
######################################################################## 100.0%

Installation directory (this will create a google-cloud-sdk subdirectory) (/home/root): 
mkdir -p /home/root
tar -C /home/root -zxvf /tmp/tmp.8Z05HN2VwS/google-cloud-sdk.tar.gz
google-cloud-sdk/
...
...
google-cloud-sdk/.install/.download/

/home/root/google-cloud-sdk/install.sh
Welcome to the Google Cloud SDK!

To help improve the quality of this product, we collect anonymized usage data
 and anonymized stacktraces when crashes are encountered.. You may choose to opt
 out of this collection now (by choosing 'N' at the below prompt), or at any
 time in the future by running the following command:
    gcloud config set disable_usage_reporting true

Do you want to help improve the Google Cloud SDK (Y/n)?  Y

```