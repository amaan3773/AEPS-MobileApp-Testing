# Adhaar Enabled Payment System:
Equitas AEPS is Android based application which gives a Service of AEPS System. With this application user can do AEPS supported transactions like: Balance Enquiry,Mini statement, cash Withdrawal, Cash deposit etc and Fund transfer tx like : Adhaar to Adhaar & Adhaar to Account (Onus and Offus transactions).It interfaces finger scanner device (RD Mantra's Device) for authentication (for approving authentication legs).
    AEPS (Adhaar Enabled Payment System) empowers bank customers to access their bank accounts with the help of their Adhaar number. It offers wife range of services from on-boarding a customer (via eKYC) to enabling customers to access their accounts using their Aadhaar number. 
    Sarvatra MicroATM has functional integration with AEPS andar EKYC, in addition to allowing Rupay cardbased Onus and Offus transactions on Micro ATMs (POS Terminals).
    Best Finger Detection (BFD) -UIDAI has come up with the BFD service for better biometric match during Authentication.
    After completion of transaction, user gets a receipt of detailed transaction information which includes Signatory, RRN , Amount and response code , status etc.
    Whatever transactions gets done, Its detail log(XML log) comes at switch/server end.
    Using that log, user can see all the detailed parameters of log.
# AEPS application Images:
![image](https://github.com/amaan3773/AEPS-MobileApp-Testing/assets/170299266/f151d2b8-b660-4426-b3ae-a830c34cd1cf)


# RD Mantras Device:
- It is used for secure authenticaton
![image](https://github.com/amaan3773/AEPS-MobileApp-Testing/assets/170299266/60df9997-d75a-489e-ab3b-8928f0dadd16)

# Test Cases:
The test cases cover the following scenarios:
### User Authentication
- Valid Aadhaar number and fingerprint
- Invalid Aadhaar number
- Incorrect fingerprint
### Balance Enquiry
- Successful balance enquiry
- Failed balance enquiry due to network issues
### Cash Withdrawal
- Successful cash withdrawal
- Insufficient funds
### Mini Statement
- Retrieve recent transactions

 # Challenges Faced:
- While checking the logs as per ISO8583 at AEPS Server for transaction status, it provides too much tricky information in the form of data elements.When transactions get failed or absorted, log gives complicated info about that transaction.
- As per RTM , executing all test cases in stipulated sprint time was challenging.  
  
