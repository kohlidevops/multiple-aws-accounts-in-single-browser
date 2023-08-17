# multiple-aws-accounts-in-single-browser
To access the multiple AWS Accounts from single browser

Download the granted installer to your local machine

**If your are using Windows machine, then**

https://releases.commonfate.io/granted/v0.14.1/granted_0.14.1_windows_x86_64.zip

**If you are using Linux machine, then**

#curl -OL releases.commonfate.io/granted/v0.14.1/granted_0.14.1_linux_x86_64.tar.gz
#sudo tar -zxvf ./granted_0.14.1_linux_x86_64.tar.gz -C /usr/local/bin/

**If you are using Mac machine, then**

#brew tap common-fate/granted
#brew install granted

**Once installed you can check with "granted" command**

<img width="665" alt="image" src="https://github.com/kohlidevops/multiple-aws-accounts-in-single-browser/assets/100069489/f965ba89-76c8-4539-85c9-c63000ad2074">

**>granted -v**

I assuming you have multiple AWS accounts, and created accesskey and secretkey to configure in local machine

Here, I have two accounts - Latchu and Samira. You should installed AWS CLI in your local machine.

**>aws configure --profile Latchu**

**>aws configure --profile Samira**

Once you configured, then you can use "assume" command to select default browser to open aws account to access.

**>assume**

Finally you can play now.

<img width="727" alt="image" src="https://github.com/kohlidevops/multiple-aws-accounts-in-single-browser/assets/100069489/0bcd94a0-83e1-4235-86a4-c8e70ffc8df3">

**>assume -c**

Here we go, I can open and access the two different aws accounts

<img width="923" alt="image" src="https://github.com/kohlidevops/multiple-aws-accounts-in-single-browser/assets/100069489/10d464dd-4e7f-42d6-bc14-e32e6dcae3e6">

<img width="911" alt="image" src="https://github.com/kohlidevops/multiple-aws-accounts-in-single-browser/assets/100069489/5b3731d7-e54d-4cb2-8ab9-314fa9389357">

I hope, you can associate your AWS SSO. However, Don't forget that you are using AWS accesskey and secretkey in your machine.

<img width="959" alt="image" src="https://github.com/kohlidevops/multiple-aws-accounts-in-single-browser/assets/100069489/72b65ae4-2eb6-490a-baf9-db6c240e7206">


