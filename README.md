# Securing Network with  OpenSSL

## What is SSL

- SSL stands for Secure Socket Layer
- Network Protocol which runs on in between presentation layer and Transport layer
- Now SSL has  successor which is  called  TLS  stands for Transport Layer Security
![image](https://raw.githubusercontent.com/95keshav/openssl/main/Figure1.%20OSI%20Layers%20and%20Protocols%20used.png)


## Why We need SSL/TLS

- SSL/TLS is used for securing connection between systems so that they can share important information and no one other can read or modify it.

- SSL/TLS basically use encryption algorithms to encrypt that data and share keys only to system who are communicating with each other
![alt text](https://raw.githubusercontent.com/95keshav/openssl/main/Figure%202.%20SSL%20Client-Server%20communication.png) <br />
[To Get more information on SSL click here](https://www.youtube.com/watch?v=iQsKdtjwtYI)

## How To Get SSL Certificate?

Its Easy, as there are many companies which sell SSL encryption certificate service.
[Go daady](https://ca.godaddy.com/offers/ssl-certificate/month?isc=sshl5ca18&countryview=1&currencytype=CAD&gclid=Cj0KCQiA1pyCBhCtARIsAHaY_5c0At-wdCdfLCOA5i0WMMxTheGqqBCbsLGrQLa4z-5VjQnd03dQJLsaAlPtEALw_wcB&gclsrc=aw.ds)
[Comodo SSl](https://comodosslstore.com/promoads/cheap-comodo-ssl-certificates.aspx?gclid=Cj0KCQiA1pyCBhCtARIsAHaY_5e4SS0meZ14zKfxrpohuZkCtUGKtH9eKy7dR2JhFINq5N28rm2yQkwaAh4ZEALw_wcB)
[Digicert](https://www.digicert.com/tls-ssl/compare-certificates?ef_id=Cj0KCQiA1pyCBhCtARIsAHaY_5eLOU_wn5_iGycf_FAMDTZnA3NFnWhCFkLvcjKr2sZqpop_mak2bSUaArzWEALw_wcB:G:s&s_kwcid=AL!6100!3!389968107068!e!!g!!digicert&campaignid=197469053&adgroupid=13418307173&gclid=Cj0KCQiA1pyCBhCtARIsAHaY_5eLOU_wn5_iGycf_FAMDTZnA3NFnWhCFkLvcjKr2sZqpop_mak2bSUaArzWEALw_wcB)
[Entrust Datacard](https://www.entrust.com/digital-security/certificate-solutions/products/digital-certificates/tls-ssl-certificates/advantage-ssl)
[ssl.com](https://www.ssl.com/certificates/premiumssl/)

## Various Open-Source SSL certificate Service
- All these come under open-source license.
- Can be commercially used for free
- No hidden charges
[OpenSSL](https://www.openssl.org/source/)
[Let's Crypt](https://letsencrypt.org/)
[zero SSL](https://zerossl.com/)
[Certbot](https://certbot.eff.org/)
[SSL for free](https://www.sslforfree.com/)


## What is OpenSSL

- It is open-source cryptographic library.
- Written  in C, Assembly and Perl
- It  is  used  for  data  encryption
- It  has  various encryption algorithm and provide many encryption tools
- SSL/TLS  is  one  of  encryption tool provided by OpenSSL <br />
[for more information click here](https://www.openssl.org/)

## History Of OpenSSL

- Released on 23 December 1998 by OpenSSL Project Team
- In  2019  OpenSSL  is  managed  by  OpenSSL  management  committee
- This project budget is around one million per year which primarily completed by donations <br />
[Get more information on wikipedia](https://en.wikipedia.org/wiki/OpenSSL)

## How OpenSSL is Work
Open SSL architecture is divided into 4 parts
1. libcrypto
2. libssl
3. Engine
4. Application Component

### Libcrypto
- It is general purpose cryptographic library which contains all various cryptographic services used in OpenSSL
- It  also  provide supporting services which are used by libssl  which  handle  SSL/TLS  in  OpenSSL
![image](https://raw.githubusercontent.com/95keshav/openssl/main/supporting%20services.png)
### Libssl
- This library depends upon libcrypto
- It handle the TLS protocols and its execution
![image](https://raw.githubusercontent.com/95keshav/openssl/main/libssl.png)

### Engine
- They are Dynamically modules registered with libcrypto to help it to run cryptographic algorithms
- It is  the  hardware and software implementations  used to run cryptographic algorithms
- Used  as  hardware accelerator for these algorithms

### Application Component
*“Applications are  set  of  command  –line tools  that  use  the  underlaying  libcrypto and libssl components to provide cryptographic and other features like*[[1]](#1)

1. *Key and parameter generation and inspection*
2.  *Certificate  generation and inspection*
3.  *SSL/TSL test  tools*
4. *ASN.1 Inspection”*


## OpenSSL Module
![image](https://raw.githubusercontent.com/95keshav/openssl/main/openssl%20modules.png) <br />
[Get more information on OpenSSL Architechture](https://www.openssl.org/docs/OpenSSLStrategicArchitecture.html)
