# email-attachment-extractor
This is a python script to extract attachments from attachments disabled emails(with virus warning).

**Note: Gmail warned you that attachment is not safe. So make 100% sure that email attachments is safe for download before follow below process.**
**Don't blame me if anything happens wrong**
**USE AT YOUR OWN RISK**

--REQUIREMENTS--

* python3.

https://www.python.org/downloads/

--HOW TO GET THE EMAIL FILE--

1. Open gmail in your browser
2. Open the file attached email
3. Click on the 3 dots inthe right side of the email.
4. select "SHOW ORIGINAL"
5. click "Download original"

**this will download a file named *subject_name.eml*.**

--HOW TO EXTRACT ATTACHMENTS--

1. Download the *attachment_extractor.py* and copy it to the folder containing **eml file**.
2. Open command prompt/powershell(**Shift+right click -> open Powershell window here**)
 type:
3.  python attachment_extractor.py *name-of-the-email-file*.eml

**this will generate a zip file named as attachment file**
**Extract it using 7zip,winRAR etc.**
