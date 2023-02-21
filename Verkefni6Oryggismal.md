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
#### 5) Did you receive an error message on PC-2? If so, what was the Error message? Já villu skilaboðinn sögðu að ég gat ekki tengt við hina tölvunna
#### 6) re-open printer and file sharing can you now connect to PC1? já gat það núna vegna þess að file og printer sharing var ekki lengur blockað af fire wallinu
#### 7) List the short name of four services that are available in the Customize Service Settnigs window: AeLookupSvc, Appinfo, ALG, AppMgmt 
#### 8) List four of the Specific ICMP types. Echo Reply, Unassigned  Unassigned, Destination Unreachable.
#### 9) What are some possible reasons you may need to make firewall changes? default stillingin á firewallinu er með flest öpp blockuð, þú gætir þurft að hleypa sumum í geng til að þau virki almennilega
### Lab 13.3.3.6 Configure Users and Groups in Windows
#### 1) What are the names of the accounts listed? Administrator, DefaultAccount, Faraam, Guest, Hreimur, Mohammed, Nemandi, oli, swaggertemp og User1
#### 2) Select the Groups folder, Name five groups from the list. Guest, Replicator, Administrator, Power Users og Device Owners.
#### 3) Which group does your account belong to? Users og Administrators
#### 4) What is Student01 required to do when logging in the first time? hann þarft að breyta lykilorðinnu sínu
#### 5) What group does User01 belong to? Users
#### 6) What does it say in the description of the Users group? Users are prevented from makin accidental or intentional system wide changes and can run most applications.
#### 7) Who are the group members? á tölvunni eru til dæmis: Hreimur, Mohammed, Student01 og User1
#### 8) Go onto User1 and try to create a new account, what happens? fékk skilaboð sem segja Access Denied. getur ekki gert account útaf þú er í user groupunni, eitthvað svoleiðs
#### 9) Were you able to navigate to www.cisco.com? Explain. Já gat það, sem user getur þú notað flest öll forrit á tölvunni 
#### 10) With the group ITEStaff highlighted, what can the members do in this folder? memberar af ITEStaff groupunni hafa read & execute, lista folder fjölda og read leyfi
#### 11) Which additional checkbox would you select? þú myndir checka í Full Control checkbox.
#### 12) Navigate to C\Students and create a folder named Student02, log in as Student02, Create a text document in Student02 Were you successful? Explain. Já sem partur af ITEStudent groupunni, Student02 hefur flest réttindi hér
#### 13) Now go to C\ and try to create a text document, Were you successful? Explain. Nei útaf því að Student02 hefur ekki réttindi hér til að búa til file. Útaf því hann er ekki með ITEStaff groupuna
#### 14) as Student01 can you edit the file in Student02 and place a text document in the Staff folder? Já og nei, þú getur breytt fileinu í Student02 þar sem hann hefur rétt þar, en þar sem hann er ekki með ITEStaff groupið getur hann ekki gert neitt í Staff folderinnu.
#### 15) Now go on Student02 and try to change files in Student01 and Student02 folders, can you do it? Hann getur bara breytt í Studnet02 eftir að við breyttum 
#### 16) As Staff01 Were you able to access the content in the folders Staff, Student\Student01 and Student\Student02? Explain. Já þar sem Staff01 er með grouppið ITEStaff kemst hann í bæði folderinn.
#### 17) Disable Staff02, can you log in as Staff02? Nei þar sem hann er disabled kemur hann ekki einu sinni upp á listanum af userum og þú getur ekki loggað þig inn.
#### 18) How would you give administrative privileges on the local computer to all the members of ITEStaff? Þú gerir það með að bæta ITEStaff hópnum í Administrator hópinn
#### 19) How would you deny access to a file for everyone except the owner? þú gerir það með að fara í security á folderinnu og gefur fulla stjórn á eigandann og stillir þannig að einginn annar hefur aðgang
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