### Lab 13.2.3.7 - Bitlocker and Bitlocker To Go
#### 1) Why is it important to save a Bitlocker recovery key? recovery lykilinn þarftu að geyma hjá þér ef t.d. þú gleymir lykilorðinu af driveinu og þú læsist úti þá þarftu að nota recovery key til að komast aftur inn.
#### 2) What is the function of a TPM in relation to BitLocker? TPM eða Trusted Platform Module er notað til að geyma encryption lykillinn af disk til að tengja hann við ákveðna tölvu
### Lab 13.3.2.5 Configure Windows Local Security Policy
| Policy     | Security Setting |
| :---        |    :----   |
| Enforce password history    | 8  |
| Maximum password age   |  90 dagar  |
| mMinimum password age      | 1 sinni á dag |
| Minimum password length        |  8 stafir   |
| Password must meet complexity requirements     | Enabled   |
| Store password using reversible encryption   | Disabled     |
#### 2) according to the security policy how many times is a user allowed to attempt to login before the account is locked? Hann má reyna 5 sinnum áður en accountinum verður læst