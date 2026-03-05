# Certificates

All scripts in this directory have something to do with certificates.

Currently no scripts modify certs, only read them and output them:

## analyze\_cert: 
              This script reads all certificates in a file and outputs :
              name, issuer, startdate, enddate. Typicly used to check if
              a certificate chain matches in the file.

## compare\_keycert: 
              This script compares if the first certificate in the file
              has been signed by the key in the file. Other certificates
              are ignored.
