### Lab 13.2.3.7 - Bitlocker and Bitlocker To Go
#### 1) Why is it important to save a Bitlocker recovery key? recovery lykilinn þarftu að geyma hjá þér ef t.d. þú gleymir lykilorðinu af driveinu og þú læsist úti þá þarftu að nota recovery key til að komast aftur inn.
#### 2) What is the function of a TPM in relation to BitLocker? TPM eða Trusted Platform Module er notað til að geyma encryption lykillinn af disk til að tengja hann við ákveðna tölvu
### Lab 13.3.2.5 Configure Windows Local Security Policy
| Policy     | Security Setting |
| :---        |    :----   |
| Enforce password history    | 8  |
| Maximum password age   |  90 dagar  |
| Minimum password age      | 1 sinni á dag |
| Minimum password length        |  8 stafir   |
| Password must meet complexity requirements     | Enabled   |
| Store password using reversible encryption   | Disabled     |
#### 2) according to the security policy how many times is a user allowed to attempt to login before the account is locked? Hann má reyna 5 sinnum áður en accountinum verður læst
#### 3) How long should the user have to wait before attempting to lag back in? Hann þarf að bíða í 5 mínútur
#### 4) Are there any settings you would change in User rights assignment? Why? Ég myndi kannski breyta "Access this computer from the network" bara ef þú ert með magar vélar á netinnu þá ef þú missir "stjórn" (einhver hackar sig inn) getur hann ekki komist á fleirri tölvur
| Policy     | Security Setting |
| :---        |    :----   |
| Interactive Logon: Machine inactivity limit    | 1800 seconds  |
| Devices: Allow undock without having to log on   |  Disabled  |
| Interactive logon: Message title for users attempting to log on      | Caution: |
| Change the Interactive logon: Message text for users attempting to log on |  Your activity is monitored. This computer is for business use only.   |
| Interactive logon: Prompt user to change password before expiration | 7 Days  |
### Lab 13.3.4.6 Lab - Configure Windows Firewall (Tveir hópar saman) - Með Mikeal
#### 1) Under PC-1 can you see the Cisco folder? já get séð folderið
#### 2) What are the benefits of Windows Firewall? það getur varið tölvunna þína frá hökkurum eða forritum sem geta skemmt tölvunna með að stoppa tengingar við tölvunna í gengum netið.
#### 3) Describe a negative consequence of having too many exceptions? einfaltlega sagt það gerir það bara léttara fyrir hakkara að komast inn, getur horft á það að gera magar holur í vegginn, bara léttara að komast inn
#### 4) can you connect to PC-1? nei gat það ekki eftir að hann breytti stillingum
#### 
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####
####