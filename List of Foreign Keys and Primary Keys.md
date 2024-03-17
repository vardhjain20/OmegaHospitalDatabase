# <a name="_cjyoqzwo8ufr"></a>**Main Tables**
# <a name="_qnga138p3che"></a>**OMEGA** – Data for Each Inpatient Encounter
**Primary Key:** PAT\_NO

**Foreign Keys:** 


|**Foreign Key**|**Descriptor Name**|
| :-: | :-: |
|ADM\_SOURCE |SOURCE|
|ADM\_SVC |SERVICE|
|ADM\_DIAG\_9|9DX11|
|CCSTAY |Yes\_No|
|PRINCPL\_DX|9DX11|
|AUTOPSY |YES\_NO|
|CORONER |YES\_NO|
|DIED\_WI\_48|YES\_NO|
|DIED\_IN\_OR |YES\_NO|
|DIESD\_PSTOP |YES\_NO|
|DOA |YES\_NO|
|ER\_DEATH |YES\_NO|
|DISPOSTN |DISPOSTIN|
|DRG |DRG|
|PREPRC\_TST |YES\_NO|
|TISSUE |TISSUE|
|ORGAN\_DON |ORGAN|

**CRIT** – ICU Stays 

**Primary Key:** PAT\_NO

No foreign keys

**OMEGA\_DX** – Patient Diagnosis Data

**Primary Key:** PAT\_NO

**Foreign keys:** DIAGNOSIS – 9DX11 Table 

**OMEGA\_PX**  – Patient Operative Data

**Primary Key:** PAT\_NO

**Foreign keys:** OP\_PROC\_9 -- 9OP11 Table


**Descriptor Tables:** 

**9DX11** – ICD-9-CM Diagnostic Codes

**Primary Keys:** DIAG

**9OP11** – ICD-9-CM Operative Codes

**Primary Keys:** OP

**DISPOSTN** – Disposition Codes (identifies where the patient is being discharged to at the end of their facility stay or transferred to such as an acute/post-acute facility.)

**Primary Keys:** DISPOSTN
# <a name="_9dhd1uycbclx"></a>**DRG**
**Primary Key:** DRG

**ORGAN** – Organ Donation Codes

**Primary Key:** ORGAN\_DON 

**SERVICE** – Service Codes

**Primary Key:** SERVICE

**SOURCE** –  Admission Source 

**Primary Key:** ADM\_SOURCE

**TISSUE** – TISSUE

**Primary Key:** TISSUE

**YES NO** – Yes/No Designation 

**Primary Key:** TAG













