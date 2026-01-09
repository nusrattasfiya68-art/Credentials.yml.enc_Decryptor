# Credentials.yml.enc encrypting
An "off-the-rails" (python) implementation for dencrypting **_credentials.yml.enc_** files.

## Background
"credentials.yml.enc" files are the new norm for storing Ruby on Rails ( >= v5.2) secure way.<br/>
The credential file is encrypted using  and the encryption key stored in the master.key file.<br/>

## Usage
### encryption
```
$ python decryptor.py credentials.yml.enc master.key
```

### Encryption
```
$ python encryptor.py credentials.yml master.key
```

## Requires
- python
- pyca (https://github.com/pyca/cryptography)

## To Do
- Working on python 3 compatibility
