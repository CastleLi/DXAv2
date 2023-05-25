
**Please read this carefully**
1. The Template file should be saved in “.csv” format.
2. Empty cells in the tables of DXA reports may lead to unexpected mistakes in the outputs **unless those cells are at the end of each row**.
3. Currently the DXA<sup>2</sup>v2 is not applicable for the DXA machine GE Prodigy – enCORE v.12. Please use the earlier version [DXA<sup>2</sup>](https://github.com/DXA-Data-Xtraction-Assistant/DXA-Data-Xtraction-Assistant/) to process the DXA reports if you are using DXA machine GE Prodigy – enCORE v.12.


# Creating your own template
The template table is composed of table headers in each type of DXA scans (Fig 1).

![Fig 1](https://github.com/CastleLi/DXAv2/blob/main/Template/Figs/Fig1.jpg) 


The first row indicates type of DXA reports, **ScanType**, and the remaining rows are table headers in the corresponding DXA report. We recommend naming the type of DXA scans as follows:

*Table 1: Guide for how to rename DXA reports for use with DXA<sup>2</sup>.*

| Scan Type	| Main Report	| Needed file name format	| Enhanced Report	| Needed file name format|
|---|---|---|---|---|
|Total Body	| Total Body Densitometry	| PatientID\_visit#\_Bone	| Total Body Densitometry Enhanced Analysis	| PatientID\_visit#\_BoneExt |
| |Total Body Composition	| PatientID\_visit#\_BC	| Total Body Composition Enhanced Analysis	| PatientID\_visit#\_BCExt |
| Lumbar Spine	| Lumbar Spine Densitometry	| PatientID\_visit#\_LS	| Lumbar Spine Densitometry Enhanced Analysis	| PatientID\_visit#\_LSExt |
| Proximal Femur	| Dual Total Hip Densitometry |	PatientID\_visit#\_DH	| Dual Total Hip Densitometry Enhanced Analysis	| PatientID\_visit#\_DHExt |
| Proximal Femur	| Left/Right Total Hip Densitometry |	PatientID\_visit#\_LH or PatientID\_visit#\_RH	| Single Total Hip Densitometry Enhanced Analysis	| PatientID\_visit#\_LHExt or PatientID\_visit#\_RHExt |
| Radius	| L or R Radial Densitometry	| PatientID\_visit#\_Rad	| only the left OR the right radial scans can be processed at a time in the application.| |

Once you have determined the **ScanType**, open the DXA report and type/copy the table headers into the template file (Fig 2).

![Fig 2](https://github.com/CastleLi/DXAv2/blob/main/Template/Figs/Fig2.jpg) 



