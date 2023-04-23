# ShivangSingh_PythonEngineer

## Created this for Data Engineer assignment for SteelEye 

Brief:

* The requirement needs to be developed in Python 3
* From the xml, please parse through to the first download link whose file_type is DLTINS and download the zip
* Please provide github link for review.

Requirement:

* Download the xml from this link
* From the xml, please parse through to the first download link whose file_type is DLTINS and download the zip
* Extract the xml from the zip.
* Convert the contents of the xml into a CSV with the following header:
* FinInstrmGnlAttrbts.Id
* FinInstrmGnlAttrbts.FullNm
* FinInstrmGnlAttrbts.ClssfctnTp
* FinInstrmGnlAttrbts.CmmdtyDerivInd
* FinInstrmGnlAttrbts.NtnlCcy
* Issr
* Store the csv from step 4) in an AWS S3 bucket
* The above function should be run as an AWS Lambda (Optional)

## Steps to get your aws_access_key_id and aws_secret_access_key_id
* You should have aws account
* Go to security credentials from your account and click on create aws_access_key [note your secret_access_key as it will created only once]
* If you are not root user go to users and create the key for whcih user you want

## DLTINS_20210117_01of01.xml this file and zip i was not able to upload as it was exciding 100 mb which is limit of GitHub
<img src = "Screenshot 2023-04-22 191732.png">
