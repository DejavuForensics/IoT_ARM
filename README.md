# IoT_ARM
Retrieval Internet of Thing for  ARM Malware Analysis

## Commercial Antivirus Limitation

Technically, the modus operandi for the identification of malicious files and servers refers to consult in named blacklist databases. The VirusTotal platform issues the diagnoses regarding malignant characteristics related to files and web servers.

When it comes to suspicious files, VirusTotal issues the diagnostics provided by the world's leading commercial antivirus products. Regarding suspicious web servers, VirusTotal uses the database responsible for sensing virtual addresses with malicious practices.

VirusTotal has Application Programming Interface (APIs) that allow programmers to query the platform in an automated way and without the use of the graphical web interface. The proposed paper employs two of the APIs made available by VirusTotal. The first one is responsible for sending the investigated files to the platform server. The second API, in turn, makes commercial antivirus diagnostics available for files submitted to the platform by the first API.

Initially, the executable malwares are sent to the server belonging to the VirusTotal platform. After that, the executables are analyzed by the 86 commercial antiviruses linked to VirusTotal. Therefore, the antivirus provides its diagnostics for the executables submitted to the platform. VirusTotal allows the possibility of issuing three different types of diagnostics: malware, benign and omission.

Then, through the VirusTotal platform, the proposed paper investigates 77 commercial antiviruses with their respective results presented in Table 2. We used 1600 malicious executables for ANDROID obtained from the REFADE database. The goal of the work is to check the number of virtual pests cataloged by antivirus. The motivation is that the acquisition of new virtual plagues plays an important role in combating malicious applications. Therefore, the larger the database of malwares blacklisted, the better it tends to be the defense provided by the antivirus.

As for the first possibility of VirusTotal, the antivirus detects the malignity of the suspicious file. In the proposed experimental environment, all submitted executables are public domain malwares. Therefore, in the proposed study, the antivirus hits when it detects the malignity of the investigated executable. Malware detection indicates that the antivirus provides a robust service against cyber-intrusions. As larger the blacklist database, better tends to be the defense provided by the antivirus.

In the second possibility, the antivirus attests to the benignity of the investigated file. Therefore, in the proposed study, when the antivirus attests the benignity of the file, it is a case of a false negative – since all the samples are malicious. That is, the investigated executable is a malware; however, the antivirus attests to benignity in the wrong way.

In the third possibility, the antivirus does not emit opinion about the suspect executable. The omission indicates that the file investigated has never been evaluated by the antivirus neither it has the robustness to evaluate it in real time. The omission of the diagnosis by the antivirus points to its limitation on large-scale services.

In the third possibility, the antivirus does not emit opinion about the suspect executable. The omission indicates that the file investigated has never been evaluated by the antivirus neither it has the robustness to evaluate it in real time. The omission of the diagnosis by the antivirus points to its limitation on large-scale services.

Table 2 shows the results of the evaluated 86 antivirus products. Only two of these antiviruses scored above 90%. These antiviruses were: Symantec Mobile Insight and K7GW. Malware detection indicates that these antivirus programs provide an efficient service against cyber-intrusions.

A major adversity in combating malicious applications is the fact that antivirus makers do not share their malware blacklists due to commercial disputes. Through Table 2 analyse, the proposed paper points to an aggravating factor of this adversity: the same antivirus vendor does not even share its databases between its different antivirus programs. Note, for example, that McAfee and McAfee-GW-Edition antiviruses belong to the same company. Their blacklists, though robust, are not shared with each other. Therefore, the commercial strategies of the same company hinder the confrontation with malware. It complements that antivirus vendors are not necessarily concerned with avoiding cyber-invasions, but with optimizing their business income.

Malware detection ranged from 0% to 93,71%, depending on the antivirus being investigated. On average, the 77 antiviruses were able to detect 32,60% of the evaluated virtual pests, with a standard deviation of 38,43. The high standard deviation indicates that the detection of malicious executables may suffer abrupt variations depending on the antivirus chosen. It is determined that the protection, against cybernetic invasions, is due to the choice of a robust antivirus with a large and updated blacklist.

As for the false negatives, BitDefender, Baidu and Panda antiviruses, wrongly stated that malware was benign in more than 95% of cases. On average, antiviruses attested false negatives in 43,34% of the cases, with a standard deviation of 41,22. Tackling the benignity of malware can lead to irrecoverable damage. A person or institution, for example, would rely on a particular malicious application when, in fact, it is malware.

Acronis, eScan, Palo Alto Networks, Sophos AV-Sophos, SentinelOne (Static-ML), SecureAge APEX, CrowdStrike Falcon, Sangfor Engine Zero, Sophos ML and Trapmine antivirus companies have not omitted opinion on any of the 1600 samples malicious. Therefore, about 13% of antivirus softwares were not able to diagnose any of the malicious samples. On average, the antiviruses were missing in 24.06% of the cases, with a standard deviation of 41.33. The omission of the diagnosis points to the limitation of these antiviruses that have limited blacklists for detection of malware in real time.

It is included as adversity, in the combat to malicious applications, the fact of the commercial antiviruses do not possess a pattern in the classification of the malwares as seen in Table 3. We choose 3 of 1600 REWEMA malwares samples in order to exemplify the miscellaneous classifications of commercial antiviruses. The chosen malware are VirusShare_0d1b1736b6b210f5e036c35278db4fbc, VirusShare_0d2ca61588afc2c98798333dae466775 and VirusShare_0d00ec451b1aa695055f43e355442c89. In this way, the time when manufacturers react to a new virtual plague is affected dramatically. As there is no a pattern, antiviruses give the names that they want, for example, a company can identify a malware as "Malware.1" and a second company identify it as "Malware12310". Therefore, the lack of a pattern, besides the no-sharing of information among the antivirus manufacturers, hinders the fast and effective detection of a malicious application.

###### Table 2 Results of 77 commercial antiviruses:

Antivirus |	Deteccion (%) |	False Negative (%) |	Omission (%)
--------- | ------------- | ------------------ | -------------
ESET-NOD32 |	82.6% |	17.3% |	0.1% |
MicroWorld-eScan |	79,9	| 20,1 | 0 |
Ad-Aware	79,9	19,9	0,2
BitDefender	79,8	19,9	0,3
Emsisoft	79,2	20,5	0,3
NANO-Antivirus	79,2	20,8	0
FireEye	79,1	19,8	1,1
GData	78,9	19,3	1,8
Tencent	78,8	21	0,2
Zillya	78,7	20,1	1,2
McAfee-GW-Edition	78,5	20,2	1,3
McAfee	78,1	21,3	0,6
Avast-Mobile	78	22	0
Kaspersky	77,9	21,3	0,8
DrWeb	77,5	22,4	0,1
Symantec	77,3	21,4	1,3
TrendMicro-HouseCall	77,3	22,5	0,2
AVG	77,1	0,4	22,5
Microsoft	76,8	22	1,2
ClamAV	76,7	22,3	1
Avira	76,6	23,4	0
Cynet	76,6	23,4	0
Ikarus	76,6	16,3	7,1
TrendMicro	76,2	23,3	0,5
Avast	75,8	22,1	2,1
Fortinet	75,3	24,7	0
MAX	74,8	25,1	0,1
Rising	74,5	24,9	0,6
ALYac	73,3	17,9	8,8
ZoneAlarm	72,6	26,9	0,5
Arcabit	71,5	28,5	0
Qihoo-360	71,5	28,2	0,3
AhnLab-V3	71,2	28,8	0
BitDefenderTheta	70,2	28,8	1
Antiy-AVL	66,6	28,3	5,1
Sophos	64,6	35,3	0,1
F-Secure	63,1	36,5	0,4
Lionic	62,6	36,3	1,1
Cyren	61,1	38,8	0,1
Comodo	58,9	40,7	0,4
Jiangmin	52	14	34
MaxSecure	41,5	56	2,5
Sangfor	27,1	71,7	1,2
CAT-QuickHeal	8,5	91,5	0
SymantecMobileInsight	4,1	0	95,9
Gridinsoft	3,1	96,5	0,4
Yandex	1,1	98,9	0
VIPRE	1	98,8	0,2
ViRobot	0,6	99,4	0
Panda	0,3	99,7	0
Bkav	0,2	99,4	0,4
K7GW	0,2	99,8	0
K7AntiVirus	0,2	99,8	0
VBA32	0,1	99,9	0
Zoner	0,1	98,9	1
Acronis	0	99,2	0,8
Kingsoft	0	96,9	3,1
TACHYON	0	100	0
CMC	0	100	0
SUPERAntiSpyware	0	99,9	0,1
Baidu	0	99,1	0,9
Malwarebytes	0	99,9	0,1
TotalDefense	0	89,8	10,2
F-Prot	0	0,3	99,7
eGambit	0	5,8	94,2
CrowdStrike	0	0,4	99,6
Invincea	0	0,1	99,9

###### Table 3 Miscellaneous classifications of commercial antiviruses:

Antivírus |	VirusShare_0d1b1736b6b210f5e036c35278db4fbc |	VirusShare_0d2ca61588afc2c98798333dae466775 |	VirusShare_0d00ec451b1aa695055f43e355442c89
--------- | ------------------------------------------- | ------------------------------------------- | --------------------------------------------
ESET-NOD32 |  | | |
MicroWorld-eScan
Ad-Aware
BitDefender
Emsisoft
NANO-Antivirus
FireEye
GData
Tencent
Zillya
McAfee-GW-Edition
McAfee
Avast-Mobile
Kaspersky
DrWeb
Symantec
TrendMicro-HouseCall
AVG
Microsoft
ClamAV
Avira
Cynet
Ikarus
TrendMicro
Avast
Fortinet
MAX
Rising
ALYac
ZoneAlarm
Arcabit
Qihoo-360
AhnLab-V3
BitDefenderTheta
Antiy-AVL
Sophos
F-Secure
Lionic
Cyren
Comodo
Jiangmin
MaxSecure
Sangfor
CAT-QuickHeal
SymantecMobileInsight
Gridinsoft
Yandex
VIPRE
ViRobot
Panda
Bkav
K7GW
K7AntiVirus
VBA32
Zoner
Acronis
Kingsoft
TACHYON
CMC
SUPERAntiSpyware
Baidu
Malwarebytes
TotalDefense
F-Prot
eGambit
CrowdStrike
Invincea



## Materials and Methods

This paper proposes a database aiming at the classification of Android benign and malware executables. The database is referred to as REFADE. There are 1600 malicious executables, and 1600 other benign executables. Therefore, the REFADE base is suitable for learning with artificial intelligence, since both classes of executables have the same amount.

For the construction of a pattern recognition AI (artificial intelligence), the conventional method used for its training is the use of classes and counter classes of a certain filetype. The designation chosen to refer to the categories was "benign files" for serious and safe applications and "malignant files" for applications that can be a threat to the user. The malwares samples are executables files for Android (.apk). The virtual plages were extracted from databases made avaiable by enthusiastic groups about the study of malwares through the digital plataform VirusShare. It should be noted that all benign executables were submitted to VirusTotal and all were its benign attested by the main commercial antivirus worldwide. The diagnostics, provided by VirusTotal, corresponding to the benign and malware executables are available in the virtual address of the REFADE database.

The benign samples were extracted from Playstore, the official shop for Android devices. In addition, databases from others plataforms of benign apps were also used: APKmirror and APKpure. To avoid repeat the samples, were used authoral scripts coded in python. The scrip read the files downloaded and delete its copys.