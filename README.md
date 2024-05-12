Task1 -- Linear Regression Dataset:
i) test:

Id	MSSubClass	MSZoning	LotFrontage	LotArea	Street	Alley	LotShape	LandContour	Utilities	LotConfig	LandSlope	Neighborhood	Condition1	Condition2	BldgType	HouseStyle	OverallQual	OverallCond	YearBuilt	YearRemodAdd	RoofStyle	RoofMatl	Exterior1st	Exterior2nd	MasVnrType	MasVnrArea	ExterQual	ExterCond	Foundation	BsmtQual	BsmtCond	BsmtExposure	BsmtFinType1	BsmtFinSF1	BsmtFinType2	BsmtFinSF2	BsmtUnfSF	TotalBsmtSF	Heating	HeatingQC	CentralAir	Electrical	1stFlrSF	2ndFlrSF	LowQualFinSF	GrLivArea	BsmtFullBath	BsmtHalfBath	FullBath	HalfBath	BedroomAbvGr	KitchenAbvGr	KitchenQual	TotRmsAbvGrd	Functional	Fireplaces	FireplaceQu	GarageType	GarageYrBlt	GarageFinish	GarageCars	GarageArea	GarageQual	GarageCond	PavedDrive	WoodDeckSF	OpenPorchSF	EnclosedPorch	3SsnPorch	ScreenPorch	PoolArea	PoolQC	Fence	MiscFeature	MiscVal	MoSold	YrSold	SaleType	SaleCondition
1461	20	RH	80	11622	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NAmes	Feedr	Norm	1Fam	1Story	5	6	1961	1961	Gable	CompShg	VinylSd	VinylSd	None	0	TA	TA	CBlock	TA	TA	No	Rec	468	LwQ	144	270	882	GasA	TA	Y	SBrkr	896	0	0	896	0	0	1	0	2	1	TA	5	Typ	0	NA	Attchd	1961	Unf	1	730	TA	TA	Y	140	0	0	0	120	0	NA	MnPrv	NA	0	6	2010	WD	Normal
1462	20	RL	81	14267	Pave	NA	IR1	Lvl	AllPub	Corner	Gtl	NAmes	Norm	Norm	1Fam	1Story	6	6	1958	1958	Hip	CompShg	Wd Sdng	Wd Sdng	BrkFace	108	TA	TA	CBlock	TA	TA	No	ALQ	923	Unf	0	406	1329	GasA	TA	Y	SBrkr	1329	0	0	1329	0	0	1	1	3	1	Gd	6	Typ	0	NA	Attchd	1958	Unf	1	312	TA	TA	Y	393	36	0	0	0	0	NA	NA	Gar2	12500	6	2010	WD	Normal
1463	60	RL	74	13830	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Gilbert	Norm	Norm	1Fam	2Story	5	5	1997	1998	Gable	CompShg	VinylSd	VinylSd	None	0	TA	TA	PConc	Gd	TA	No	GLQ	791	Unf	0	137	928	GasA	Gd	Y	SBrkr	928	701	0	1629	0	0	2	1	3	1	TA	6	Typ	1	TA	Attchd	1997	Fin	2	482	TA	TA	Y	212	34	0	0	0	0	NA	MnPrv	NA	0	3	2010	WD	Normal
1464	60	RL	78	9978	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Gilbert	Norm	Norm	1Fam	2Story	6	6	1998	1998	Gable	CompShg	VinylSd	VinylSd	BrkFace	20	TA	TA	PConc	TA	TA	No	GLQ	602	Unf	0	324	926	GasA	Ex	Y	SBrkr	926	678	0	1604	0	0	2	1	3	1	Gd	7	Typ	1	Gd	Attchd	1998	Fin	2	470	TA	TA	Y	360	36	0	0	0	0	NA	NA	NA	0	6	2010	WD	Normal
1465	120	RL	43	5005	Pave	NA	IR1	HLS	AllPub	Inside	Gtl	StoneBr	Norm	Norm	TwnhsE	1Story	8	5	1992	1992	Gable	CompShg	HdBoard	HdBoard	None	0	Gd	TA	PConc	Gd	TA	No	ALQ	263	Unf	0	1017	1280	GasA	Ex	Y	SBrkr	1280	0	0	1280	0	0	2	0	2	1	Gd	5	Typ	0	NA	Attchd	1992	RFn	2	506	TA	TA	Y	0	82	0	0	144	0	NA	NA	NA	0	1	2010	WD	Normal
1466	60	RL	75	10000	Pave	NA	IR1	Lvl	AllPub	Corner	Gtl	Gilbert	Norm	Norm	1Fam	2Story	6	5	1993	1994	Gable	CompShg	HdBoard	HdBoard	None	0	TA	TA	PConc	Gd	TA	No	Unf	0	Unf	0	763	763	GasA	Gd	Y	SBrkr	763	892	0	1655	0	0	2	1	3	1	TA	7	Typ	1	TA	Attchd	1993	Fin	2	440	TA	TA	Y	157	84	0	0	0	0	NA	NA	NA	0	4	2010	WD	Normal
1467	20	RL	NA	7980	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Gilbert	Norm	Norm	1Fam	1Story	6	7	1992	2007	Gable	CompShg	HdBoard	HdBoard	None	0	TA	Gd	PConc	Gd	TA	No	ALQ	935	Unf	0	233	1168	GasA	Ex	Y	SBrkr	1187	0	0	1187	1	0	2	0	3	1	TA	6	Typ	0	NA	Attchd	1992	Fin	2	420	TA	TA	Y	483	21	0	0	0	0	NA	GdPrv	Shed	500	3	2010	WD	Normal
1468	60	RL	63	8402	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Gilbert	Norm	Norm	1Fam	2Story	6	5	1998	1998	Gable	CompShg	VinylSd	VinylSd	None	0	TA	TA	PConc	Gd	TA	No	Unf	0	Unf	0	789	789	GasA	Gd	Y	SBrkr	789	676	0	1465	0	0	2	1	3	1	TA	7	Typ	1	Gd	Attchd	1998	Fin	2	393	TA	TA	Y	0	75	0	0	0	0	NA	NA	NA	0	5	2010	WD	Normal
1469	20	RL	85	10176	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Gilbert	Norm	Norm	1Fam	1Story	7	5	1990	1990	Gable	CompShg	HdBoard	HdBoard	None	0	TA	TA	PConc	Gd	TA	Gd	GLQ	637	Unf	0	663	1300	GasA	Gd	Y	SBrkr	1341	0	0	1341	1	0	1	1	2	1	Gd	5	Typ	1	Po	Attchd	1990	Unf	2	506	TA	TA	Y	192	0	0	0	0	0	NA	NA	NA	0	2	2010	WD	Normal
1470	20	RL	70	8400	Pave	NA	Reg	Lvl	AllPub	Corner	Gtl	NAmes	Norm	Norm	1Fam	1Story	4	5	1970	1970	Gable	CompShg	Plywood	Plywood	None	0	TA	TA	CBlock	TA	TA	No	ALQ	804	Rec	78	0	882	GasA	TA	Y	SBrkr	882	0	0	882	1	0	1	0	2	1	TA	4	Typ	0	NA	Attchd	1970	Fin	2	525	TA	TA	Y	240	0	0	0	0	0	NA	MnPrv	NA	0	4	2010	WD	Normal
1471	120	RH	26	5858	Pave	NA	IR1	Lvl	AllPub	FR2	Gtl	NAmes	Norm	Norm	TwnhsE	1Story	7	5	1999	1999	Gable	CompShg	MetalSd	MetalSd	None	0	Gd	TA	PConc	Gd	TA	No	GLQ	1051	BLQ	0	354	1405	GasA	Ex	Y	SBrkr	1337	0	0	1337	1	0	2	0	2	1	Gd	5	Typ	1	Fa	Attchd	1999	Fin	2	511	TA	TA	Y	203	68	0	0	0	0	NA	NA	NA	0	6	2010	WD	Normal
1472	160	RM	21	1680	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	BrDale	Norm	Norm	Twnhs	2Story	6	5	1971	1971	Gable	CompShg	HdBoard	HdBoard	BrkFace	504	TA	TA	CBlock	TA	TA	No	Rec	156	Unf	0	327	483	GasA	TA	Y	SBrkr	483	504	0	987	0	0	1	1	2	1	TA	5	Typ	0	NA	Detchd	1971	Unf	1	264	TA	TA	Y	275	0	0	0	0	0	NA	NA	NA	0	2	2010	COD	Normal
1473	160	RM	21	1680	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	BrDale	Norm	Norm	Twnhs	2Story	5	5	1971	1971	Gable	CompShg	HdBoard	HdBoard	BrkFace	492	TA	TA	CBlock	TA	TA	No	Rec	300	Unf	0	225	525	GasA	TA	Y	SBrkr	525	567	0	1092	0	0	1	1	3	1	TA	6	Typ	0	NA	Detchd	1997	Unf	1	320	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	3	2010	WD	Normal
1474	160	RL	24	2280	Pave	NA	Reg	Lvl	AllPub	FR2	Gtl	NPkVill	Norm	Norm	Twnhs	2Story	6	6	1975	1975	Gable	CompShg	Plywood	Brk Cmn	None	0	TA	TA	CBlock	TA	TA	No	ALQ	514	Unf	0	341	855	GasA	TA	Y	SBrkr	855	601	0	1456	0	0	2	1	3	1	Gd	6	Typ	1	TA	Attchd	1975	Unf	2	440	TA	TA	Y	173	0	0	0	0	0	NA	NA	NA	0	6	2010	WD	Normal
1475	120	RL	24	2280	Pave	NA	Reg	Lvl	AllPub	FR2	Gtl	NPkVill	Norm	Norm	Twnhs	1Story	7	6	1975	1975	Gable	CompShg	Plywood	Brk Cmn	None	0	TA	TA	CBlock	Gd	TA	No	Unf	0	Unf	0	836	836	GasA	Ex	Y	SBrkr	836	0	0	836	0	0	1	0	2	1	TA	4	Typ	0	NA	Attchd	1975	Unf	1	308	TA	TA	Y	0	30	0	0	0	0	NA	NA	NA	0	6	2010	WD	Normal
1476	60	RL	102	12858	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	NridgHt	Norm	Norm	1Fam	2Story	9	5	2009	2010	Gable	CompShg	VinylSd	VinylSd	Stone	162	Ex	TA	PConc	Ex	TA	No	Unf	0	Unf	0	1590	1590	GasA	Ex	Y	SBrkr	1627	707	0	2334	0	0	2	1	3	1	Ex	10	Typ	1	Gd	Attchd	2009	Fin	3	751	TA	TA	Y	144	133	0	0	0	0	NA	NA	NA	0	1	2010	New	Partial
1477	20	RL	94	12883	Pave	NA	IR1	Lvl	AllPub	Corner	Gtl	NridgHt	Norm	Norm	1Fam	1Story	8	5	2009	2010	Gable	CompShg	VinylSd	VinylSd	Stone	256	Gd	TA	PConc	Gd	TA	No	Unf	0	Unf	0	1544	1544	GasA	Ex	Y	SBrkr	1544	0	0	1544	0	0	2	0	3	1	Gd	7	Typ	0	NA	Attchd	2009	RFn	3	868	TA	TA	Y	0	35	0	0	0	0	NA	NA	NA	0	6	2010	New	Partial
1478	20	RL	90	11520	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NridgHt	PosN	Norm	1Fam	1Story	9	5	2005	2005	Hip	CompShg	VinylSd	VinylSd	BrkFace	615	Gd	TA	PConc	Ex	TA	No	GLQ	110	Unf	0	1588	1698	GasA	Ex	Y	SBrkr	1698	0	0	1698	0	0	2	0	3	1	Ex	7	Typ	1	Gd	Attchd	2005	Fin	3	730	TA	TA	Y	192	74	0	0	0	0	NA	NA	NA	0	6	2010	WD	Normal
1479	20	RL	79	14122	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	NridgHt	Norm	Norm	1Fam	1Story	8	5	2005	2006	Hip	CompShg	CemntBd	CmentBd	BrkFace	240	Gd	TA	PConc	Ex	TA	No	GLQ	28	Unf	0	1794	1822	GasA	Ex	Y	SBrkr	1822	0	0	1822	0	0	2	0	3	1	Ex	8	Typ	1	Gd	Attchd	2005	RFn	3	678	TA	TA	Y	0	119	0	0	0	0	NA	NA	NA	0	2	2010	WD	Normal
1480	20	RL	110	14300	Pave	NA	Reg	HLS	AllPub	Inside	Mod	NridgHt	Norm	Norm	1Fam	1Story	9	5	2003	2004	Hip	CompShg	VinylSd	VinylSd	BrkFace	1095	Ex	TA	PConc	Ex	TA	Gd	GLQ	1373	Unf	0	1473	2846	GasA	Ex	Y	SBrkr	2696	0	0	2696	1	0	2	1	3	1	Ex	10	Typ	2	Gd	Attchd	2003	Fin	3	958	TA	TA	Y	220	150	0	0	0	0	NA	NA	NA	0	6	2010	WD	Normal
1481	60	RL	105	13650	Pave	NA	Reg	Lvl	AllPub	Corner	Gtl	NridgHt	Norm	Norm	1Fam	2Story	8	5	2002	2002	Gable	CompShg	VinylSd	VinylSd	BrkFace	232	Gd	TA	PConc	Gd	TA	Gd	GLQ	578	Unf	0	1093	1671	GasA	Ex	Y	SBrkr	1687	563	0	2250	1	0	2	1	3	1	Gd	7	Typ	1	Ex	Attchd	2002	Fin	3	756	TA	TA	Y	238	130	0	0	0	0	NA	NA	NA	0	6	2010	WD	Normal
1482	120	RL	41	7132	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	NridgHt	Norm	Norm	TwnhsE	1Story	8	5	2006	2006	Gable	CompShg	VinylSd	VinylSd	Stone	178	Gd	TA	PConc	Gd	TA	Mn	GLQ	24	Unf	0	1346	1370	GasA	Ex	Y	SBrkr	1370	0	0	1370	0	0	2	0	2	1	Gd	6	Typ	1	Gd	Attchd	2006	RFn	2	484	TA	TA	Y	120	49	0	0	0	0	NA	NA	NA	0	4	2010	WD	Normal
1483	20	RL	100	18494	Pave	NA	IR1	Lvl	AllPub	Corner	Gtl	Gilbert	Norm	Norm	1Fam	1Story	6	5	2005	2005	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	TA	No	Unf	0	Unf	0	1324	1324	GasA	Ex	Y	SBrkr	1324	0	0	1324	0	0	2	0	3	1	Gd	6	Typ	0	NA	Attchd	2005	Fin	2	430	TA	TA	Y	36	23	0	0	0	0	NA	NA	NA	0	1	2010	WD	Normal
1484	120	RL	43	3203	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Blmngtn	Norm	Norm	TwnhsE	1Story	7	5	2006	2006	Gable	CompShg	VinylSd	VinylSd	BrkFace	14	Gd	TA	PConc	Gd	TA	Av	GLQ	16	Unf	0	1129	1145	GasA	Ex	Y	SBrkr	1145	0	0	1145	0	0	2	0	2	1	Gd	6	Typ	0	NA	Attchd	2006	Fin	2	437	TA	TA	Y	100	116	0	0	0	0	NA	NA	NA	0	1	2010	WD	Normal
1485	80	RL	67	13300	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Gilbert	Norm	Norm	1Fam	SLvl	7	5	2004	2004	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	TA	No	GLQ	326	Unf	0	58	384	GasA	Ex	Y	SBrkr	744	630	0	1374	1	0	2	1	3	1	Gd	7	Typ	1	Gd	BuiltIn	2004	Fin	2	400	TA	TA	Y	100	0	0	0	0	0	NA	NA	NA	0	6	2010	WD	Normal
1486	60	RL	63	8577	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Gilbert	Norm	Norm	1Fam	2Story	7	5	2004	2004	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	TA	No	Unf	0	Unf	0	847	847	GasA	Ex	Y	SBrkr	847	886	0	1733	0	0	2	1	3	1	Gd	7	Typ	1	Gd	BuiltIn	2004	Fin	2	433	TA	TA	Y	144	48	0	0	0	0	NA	NA	NA	0	4	2010	WD	Normal
1487	60	RL	60	17433	Pave	NA	IR2	Lvl	AllPub	CulDSac	Gtl	NoRidge	Norm	Norm	1Fam	2Story	8	5	1998	1998	Hip	CompShg	VinylSd	VinylSd	BrkFace	114	Gd	TA	PConc	Ex	TA	No	Unf	0	Unf	0	1629	1629	GasA	Ex	Y	SBrkr	1645	830	0	2475	0	0	2	1	4	1	Gd	7	Typ	1	TA	Attchd	1998	Fin	3	962	TA	TA	Y	23	172	0	0	256	0	NA	NA	NA	0	1	2010	WD	Normal
1488	20	RL	73	8987	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Somerst	Norm	Norm	1Fam	1Story	8	5	2005	2006	Gable	CompShg	VinylSd	VinylSd	BrkFace	226	Gd	TA	PConc	Gd	TA	NA	Unf	0	Unf	0	1595	1595	GasA	Ex	Y	SBrkr	1595	0	0	1595	0	0	2	0	2	1	Gd	6	Typ	1	Gd	Attchd	2005	RFn	3	880	TA	TA	Y	144	0	0	0	0	0	NA	NA	NA	0	5	2010	WD	Normal
1489	20	FV	92	9215	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Somerst	Norm	Norm	1Fam	1Story	7	5	2009	2010	Hip	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	TA	No	Unf	0	Unf	0	1218	1218	GasA	Ex	Y	SBrkr	1218	0	0	1218	0	0	2	0	2	1	Gd	4	Typ	0	NA	Attchd	2009	RFn	2	676	TA	TA	Y	0	136	0	0	0	0	NA	NA	NA	0	4	2010	New	Partial
1490	20	FV	84	10440	Pave	NA	Reg	Lvl	AllPub	Corner	Gtl	Somerst	Norm	Norm	1Fam	1Story	6	5	2005	2005	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Ex	TA	No	GLQ	1414	Unf	0	54	1468	GasA	Ex	Y	SBrkr	1468	0	0	1468	1	0	2	0	2	1	Gd	6	Typ	1	Gd	Attchd	2005	Fin	2	528	TA	TA	Y	0	102	0	0	216	0	NA	NA	NA	0	5	2010	WD	Normal
1491	60	RL	70	11920	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	SawyerW	Norm	Norm	1Fam	2Story	7	5	2004	2004	Gable	CompShg	VinylSd	VinylSd	BrkFace	122	Gd	TA	PConc	Gd	TA	Av	Unf	0	Unf	0	831	831	GasA	Ex	Y	SBrkr	831	828	0	1659	0	0	2	1	3	1	Gd	8	Typ	0	NA	Attchd	2004	RFn	2	484	TA	TA	Y	144	68	0	0	0	0	NA	NA	NA	0	4	2010	WD	Normal
1492	30	RH	70	9800	Pave	NA	Reg	Lvl	AllPub	Corner	Gtl	SawyerW	Feedr	Norm	1Fam	1Story	5	5	1920	1950	Gable	CompShg	Wd Sdng	Wd Sdng	None	0	TA	Fa	BrkTil	TA	TA	No	Unf	0	Unf	0	816	816	GasA	TA	N	FuseA	1012	0	0	1012	0	0	1	0	2	1	TA	5	Typ	0	NA	Detchd	1920	Unf	1	429	TA	TA	Y	121	0	80	0	0	0	NA	NA	NA	0	4	2010	WD	Normal
1493	20	RL	39	15410	Pave	NA	IR1	Lvl	AllPub	CulDSac	Gtl	Sawyer	RRNe	Norm	1Fam	1Story	6	6	1974	2002	Hip	CompShg	Plywood	Plywood	BrkCmn	250	TA	Gd	CBlock	TA	TA	Gd	BLQ	126	GLQ	859	223	1208	GasA	Ex	Y	SBrkr	1494	0	0	1494	1	0	2	0	3	1	TA	7	Typ	2	Fa	Attchd	1974	Fin	2	461	TA	TA	Y	296	0	186	0	0	0	NA	GdPrv	NA	0	4	2010	WD	Abnorml
1494	60	RL	85	13143	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	NoRidge	Norm	Norm	1Fam	2Story	8	5	1993	1993	Gable	CompShg	HdBoard	ImStucc	BrkFace	504	Gd	TA	PConc	Gd	TA	No	LwQ	250	GLQ	981	0	1231	GasA	Ex	Y	SBrkr	1251	1098	0	2349	1	0	2	1	4	1	Gd	9	Typ	1	TA	Attchd	1993	RFn	3	762	TA	TA	Y	32	130	0	0	0	0	NA	NA	NA	0	6	2010	WD	Normal
1495	60	RL	88	11134	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NoRidge	Norm	Norm	1Fam	2Story	8	5	1992	1993	Gable	CompShg	HdBoard	HdBoard	BrkFace	180	Gd	TA	PConc	Gd	TA	No	GLQ	1129	Unf	0	261	1390	GasA	Ex	Y	SBrkr	1402	823	0	2225	1	0	2	1	4	1	Gd	7	Typ	1	TA	Attchd	1992	RFn	3	713	TA	TA	Y	198	30	0	0	0	0	NA	NA	NA	0	6	2010	WD	Normal
1496	120	FV	25	4835	Pave	NA	IR1	Lvl	AllPub	CulDSac	Gtl	Somerst	Norm	Norm	TwnhsE	1Story	7	5	2004	2005	Gable	CompShg	MetalSd	MetalSd	None	0	Gd	TA	PConc	Ex	TA	Av	GLQ	1298	Unf	0	190	1488	GasA	Ex	Y	SBrkr	1488	0	0	1488	1	0	2	0	2	1	Gd	6	Typ	1	Gd	Attchd	2004	Fin	2	506	TA	TA	Y	168	50	0	0	0	0	NA	NA	NA	0	3	2010	WD	Normal
1497	160	FV	39	3515	Pave	Pave	Reg	Lvl	AllPub	Inside	Gtl	Somerst	Norm	Norm	TwnhsE	2Story	7	5	2004	2004	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	TA	No	Unf	0	Unf	0	840	840	GasA	Ex	Y	SBrkr	840	840	0	1680	0	0	2	1	2	1	Gd	3	Typ	0	NA	Attchd	2004	RFn	2	588	TA	TA	Y	0	111	0	0	0	0	NA	NA	NA	0	1	2010	WD	Normal
1498	160	FV	30	3215	Pave	Pave	Reg	Lvl	AllPub	Inside	Gtl	Somerst	Norm	Norm	TwnhsE	2Story	7	5	2004	2004	Gable	CompShg	MetalSd	MetalSd	BrkFace	120	Gd	TA	PConc	Gd	TA	Av	GLQ	280	Unf	0	320	600	GasA	Ex	Y	SBrkr	600	600	0	1200	0	0	2	1	2	1	Gd	4	Typ	0	NA	Detchd	2004	RFn	2	480	TA	TA	Y	0	172	0	0	0	0	NA	NA	NA	0	4	2010	ConLD	Normal
1499	160	FV	24	2544	Pave	Pave	Reg	Lvl	AllPub	Inside	Gtl	Somerst	Norm	Norm	Twnhs	2Story	7	5	2004	2005	Gable	CompShg	MetalSd	MetalSd	None	0	Gd	TA	PConc	Gd	TA	No	GLQ	368	ALQ	42	190	600	GasA	Ex	Y	SBrkr	600	600	0	1200	1	0	2	1	2	1	Gd	4	Typ	0	NA	Detchd	2004	RFn	2	480	TA	TA	Y	0	172	0	0	0	0	NA	NA	NA	0	2	2010	WD	Normal
1500	160	FV	24	2544	Pave	Pave	Reg	Lvl	AllPub	Inside	Gtl	Somerst	Norm	Norm	Twnhs	2Story	6	5	2005	2005	Gable	CompShg	VinylSd	VinylSd	BrkFace	216	Gd	TA	PConc	Gd	TA	No	GLQ	376	Unf	0	224	600	GasA	Ex	Y	SBrkr	600	636	0	1236	1	0	2	1	2	1	Gd	4	Typ	0	NA	Detchd	2005	RFn	2	480	TA	TA	Y	0	166	0	0	0	0	NA	NA	NA	0	5	2010	WD	Normal
1501	160	FV	NA	2980	Pave	NA	Reg	Lvl	AllPub	Corner	Gtl	Somerst	Norm	Norm	TwnhsE	2Story	6	5	2000	2000	Gable	CompShg	MetalSd	MetalSd	BrkFace	1159	Gd	TA	PConc	Gd	TA	No	GLQ	466	Unf	0	290	756	GasA	Ex	Y	SBrkr	756	756	0	1512	1	0	2	1	2	1	Gd	5	Typ	0	NA	Detchd	2000	Unf	2	440	TA	TA	Y	0	32	0	0	0	0	NA	NA	NA	0	5	2010	WD	Normal
1502	160	FV	NA	2403	Pave	NA	IR1	Lvl	AllPub	FR2	Gtl	Somerst	Norm	Norm	TwnhsE	2Story	7	5	2003	2003	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	TA	No	GLQ	244	Unf	0	286	530	GasA	Ex	Y	SBrkr	530	550	0	1080	0	0	2	1	2	1	Gd	4	Typ	0	NA	Attchd	2003	RFn	2	496	TA	TA	Y	0	50	0	0	0	0	NA	NA	NA	0	6	2010	WD	Normal
1503	20	FV	57	12853	Pave	Pave	IR1	Lvl	AllPub	Inside	Gtl	Somerst	Norm	Norm	1Fam	1Story	8	5	2010	2010	Gable	CompShg	CemntBd	CmentBd	None	0	Gd	TA	PConc	Ex	Po	No	GLQ	1032	Unf	0	610	1642	GasA	Ex	Y	SBrkr	1418	0	0	1418	1	0	1	1	1	1	Gd	6	Typ	1	Gd	Attchd	2010	RFn	3	852	TA	TA	Y	160	192	0	224	0	0	NA	NA	NA	0	4	2010	New	Partial
1504	60	FV	68	7379	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Somerst	Norm	Norm	1Fam	2Story	8	5	2000	2000	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	TA	No	GLQ	484	Unf	0	491	975	GasA	Ex	Y	SBrkr	975	873	0	1848	1	0	2	1	3	1	Gd	7	Typ	1	TA	Attchd	2000	RFn	2	592	TA	TA	Y	280	184	0	0	0	0	NA	NA	NA	0	4	2010	WD	Normal
1505	20	FV	80	8000	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Somerst	Norm	Norm	1Fam	1Story	7	5	2002	2002	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	TA	No	GLQ	833	Unf	0	659	1492	GasA	Ex	Y	SBrkr	1492	0	0	1492	1	0	2	0	3	1	Gd	6	Typ	1	Gd	Attchd	2002	RFn	2	596	TA	TA	Y	277	137	0	0	0	0	NA	NA	NA	0	4	2010	WD	Normal
1506	20	RL	NA	10456	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	NWAmes	Norm	Norm	1Fam	1Story	6	6	1967	1967	Hip	CompShg	HdBoard	HdBoard	BrkFace	120	TA	TA	CBlock	TA	TA	No	GLQ	506	Unf	0	1323	1829	GasA	Gd	Y	SBrkr	1829	0	0	1829	1	0	2	0	4	1	TA	8	Typ	0	NA	Attchd	1967	RFn	2	535	TA	TA	Y	0	76	0	0	0	0	NA	NA	NA	0	5	2010	WD	Normal
1507	60	RL	80	10791	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NWAmes	Norm	Norm	1Fam	2Story	6	5	1993	1993	Gable	CompShg	MetalSd	MetalSd	None	0	TA	TA	PConc	Gd	TA	Mn	GLQ	1137	Unf	0	143	1280	GasA	Ex	Y	SBrkr	1280	1215	0	2495	1	0	2	1	4	1	Gd	9	Typ	1	TA	Attchd	1993	Unf	2	660	TA	TA	Y	224	32	0	0	0	0	NA	NA	NA	0	3	2010	WD	Normal
1508	50	RL	NA	18837	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	NWAmes	Norm	Norm	1Fam	1.5Fin	6	5	1978	1978	Gable	CompShg	MetalSd	MetalSd	None	0	TA	TA	PConc	Gd	TA	Mn	ALQ	687	LwQ	46	491	1224	GasA	TA	Y	SBrkr	1287	604	0	1891	0	1	3	0	3	1	TA	7	Typ	1	TA	Attchd	1978	RFn	2	678	TA	TA	Y	0	69	0	0	0	0	NA	NA	NA	0	4	2010	WD	Normal
1509	60	RL	80	9600	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NWAmes	Norm	Norm	1Fam	2Story	6	6	1971	1971	Gable	CompShg	MetalSd	MetalSd	None	0	TA	TA	CBlock	TA	TA	No	ALQ	329	Unf	0	386	715	GasA	TA	Y	SBrkr	930	715	0	1645	0	0	1	2	4	1	TA	7	Typ	0	NA	Attchd	1971	RFn	2	441	TA	TA	Y	0	78	0	0	0	0	NA	GdWo	NA	0	6	2010	WD	Normal
1510	20	RL	80	9600	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NAmes	Norm	Norm	1Fam	1Story	5	5	1966	1966	Hip	CompShg	VinylSd	VinylSd	BrkFace	172	TA	TA	CBlock	TA	TA	No	Rec	698	Unf	0	534	1232	GasA	TA	Y	SBrkr	1232	0	0	1232	1	0	1	1	3	1	TA	6	Typ	0	NA	Attchd	1966	RFn	2	490	TA	TA	Y	0	224	0	0	0	0	NA	NA	NA	0	4	2010	WD	Normal
1511	20	RL	90	9900	Pave	NA	Reg	Lvl	AllPub	Corner	Gtl	NAmes	Norm	Norm	1Fam	1Story	5	5	1966	1966	Hip	CompShg	HdBoard	HdBoard	None	0	TA	TA	PConc	Gd	TA	No	BLQ	1059	Unf	0	150	1209	GasA	Gd	Y	SBrkr	1209	0	0	1209	1	0	1	0	3	1	TA	6	Typ	0	NA	Attchd	1966	RFn	2	504	TA	TA	Y	0	0	120	0	0	0	NA	NA	NA	0	4	2010	ConLD	Normal
1512	20	RL	88	9680	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NAmes	Norm	Norm	1Fam	1Story	5	6	1967	1967	Gable	CompShg	Wd Sdng	Plywood	BrkFace	268	TA	TA	CBlock	TA	TA	No	BLQ	1010	Unf	0	500	1510	GasA	Ex	Y	SBrkr	1510	0	0	1510	1	0	2	0	3	1	Gd	6	Typ	0	NA	Attchd	1967	RFn	2	517	TA	TA	Y	0	40	0	0	204	0	NA	GdPrv	NA	0	4	2010	WD	Normal
1513	80	RL	NA	10600	Pave	Pave	IR1	Lvl	AllPub	Inside	Gtl	NAmes	Norm	Norm	1Fam	SLvl	6	5	1964	1964	Gable	CompShg	HdBoard	HdBoard	None	0	TA	TA	CBlock	TA	TA	No	Unf	0	Unf	0	533	533	GasA	TA	Y	SBrkr	1131	644	0	1775	0	0	2	0	3	1	TA	8	Typ	0	NA	Attchd	1964	Unf	2	480	TA	TA	Y	0	172	0	0	0	0	NA	NA	NA	0	5	2010	COD	Family
1514	90	RL	98	13260	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	NAmes	Norm	Norm	Duplex	1Story	5	6	1962	2001	Hip	CompShg	HdBoard	HdBoard	BrkFace	144	TA	TA	CBlock	TA	TA	No	BLQ	1500	Unf	0	228	1728	GasA	TA	Y	SBrkr	1728	0	0	1728	2	0	2	0	6	2	TA	10	Typ	0	NA	NA	NA	NA	0	0	NA	NA	Y	0	0	0	0	0	0	NA	NA	NA	0	1	2010	Oth	Abnorml
1515	50	RL	68	9724	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NAmes	Norm	Norm	1Fam	1.5Fin	5	7	1952	2002	Gable	CompShg	MetalSd	MetalSd	BrkFace	265	Gd	TA	CBlock	TA	TA	No	LwQ	670	Unf	0	470	1140	GasA	Gd	Y	SBrkr	1929	532	0	2461	0	0	2	0	3	1	TA	7	Min2	2	Gd	Detchd	1994	Unf	2	400	TA	TA	Y	0	0	0	0	0	0	NA	GdWo	NA	0	3	2010	WD	Normal
1516	50	RL	120	17360	Pave	NA	Reg	Lvl	AllPub	Corner	Gtl	NAmes	Artery	Norm	1Fam	1.5Fin	6	6	1949	1950	Gable	CompShg	MetalSd	MetalSd	Stone	340	TA	Gd	CBlock	TA	TA	No	Rec	300	Unf	0	482	782	GasA	TA	Y	SBrkr	1019	537	0	1556	0	0	2	0	3	1	TA	6	Typ	1	Gd	Attchd	1949	Unf	2	470	TA	TA	Y	0	0	150	0	0	0	NA	NA	NA	0	1	2010	WD	Normal
1517	85	RL	75	11380	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	NAmes	Norm	Norm	1Fam	SFoyer	6	8	1966	2008	Gable	CompShg	HdBoard	HdBoard	BrkFace	216	TA	TA	CBlock	TA	TA	Gd	GLQ	944	Unf	0	136	1080	GasA	Gd	Y	SBrkr	1128	0	0	1128	1	0	1	0	2	1	Gd	5	Typ	1	Gd	Attchd	1966	Unf	1	315	TA	TA	Y	238	0	0	0	0	0	NA	NA	Shed	1500	1	2010	WD	Normal
1518	90	RL	70	8267	Pave	NA	Reg	Lvl	AllPub	Corner	Gtl	NAmes	Feedr	Norm	Duplex	1Story	5	5	1958	1958	Gable	CompShg	HdBoard	HdBoard	None	0	TA	TA	CBlock	TA	TA	No	Unf	0	Unf	0	1604	1604	GasA	TA	Y	SBrkr	1604	0	0	1604	0	0	2	0	4	2	TA	8	Typ	0	NA	Attchd	1958	Unf	2	576	TA	TA	Y	42	0	0	0	0	0	NA	NA	NA	0	3	2010	WD	Normal
1519	20	RL	70	8197	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NAmes	Norm	Norm	1Fam	1Story	7	5	2003	2009	Gable	CompShg	VinylSd	VinylSd	BrkFace	506	Gd	TA	PConc	Gd	TA	No	GLQ	1188	Unf	0	292	1480	GasA	Ex	Y	SBrkr	1480	0	0	1480	1	0	2	0	3	1	Gd	7	Typ	0	NA	Attchd	2003	RFn	2	620	TA	TA	Y	252	73	0	0	0	0	NA	MnPrv	Shed	300	2	2010	WD	Normal
1520	20	RL	NA	8050	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	NAmes	Norm	Norm	1Fam	1Story	5	5	1959	1959	Hip	CompShg	MetalSd	MetalSd	BrkFace	150	TA	TA	CBlock	TA	TA	No	BLQ	856	Rec	162	125	1143	GasA	TA	Y	SBrkr	1143	0	0	1143	1	0	1	0	3	1	TA	6	Typ	0	NA	Attchd	1959	RFn	1	308	TA	TA	Y	0	0	0	0	0	0	NA	GdPrv	NA	0	5	2010	WD	Normal
1521	20	RL	87	10725	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	NAmes	Norm	Norm	1Fam	1Story	5	5	1959	1959	Hip	CompShg	MetalSd	MetalSd	BrkFace	91	TA	TA	CBlock	TA	TA	No	Rec	936	Unf	0	270	1206	GasA	Fa	Y	SBrkr	1206	0	0	1206	0	0	1	0	3	1	TA	6	Typ	0	NA	Attchd	1959	RFn	1	312	TA	TA	Y	0	21	0	0	0	0	NA	NA	NA	0	5	2010	WD	Normal
1522	20	RL	80	10032	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NAmes	Norm	Norm	1Fam	1Story	6	5	1959	1959	Gable	CompShg	Wd Sdng	Wd Sdng	Stone	432	TA	TA	CBlock	TA	TA	No	Rec	734	Unf	0	510	1244	GasA	Ex	Y	SBrkr	1580	0	0	1580	1	0	1	1	3	1	TA	6	Typ	2	Gd	Attchd	1956	Unf	2	440	TA	TA	Y	0	28	0	0	160	0	NA	GdWo	NA	0	6	2010	WD	Normal
1523	50	RL	60	8382	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NAmes	Norm	Norm	1Fam	1.5Fin	4	5	1956	1956	Gable	CompShg	MetalSd	MetalSd	None	0	TA	TA	CBlock	TA	TA	No	Unf	0	Unf	0	832	832	GasA	TA	Y	FuseA	832	505	0	1337	0	0	1	0	3	1	TA	5	Typ	0	NA	Attchd	1956	Unf	1	263	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	2	2010	WD	Normal
1524	20	RL	60	10950	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NAmes	Norm	Norm	1Fam	1Story	5	7	1952	1952	Gable	CompShg	WdShing	Wd Shng	None	0	TA	TA	CBlock	TA	TA	No	BLQ	339	Unf	0	525	864	GasA	TA	Y	SBrkr	1064	0	0	1064	0	1	1	0	2	1	Fa	4	Typ	0	NA	Detchd	1952	Unf	1	318	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	5	2010	WD	Normal
1525	20	RL	119	10895	Pave	NA	Reg	Lvl	AllPub	Corner	Gtl	NAmes	Norm	Norm	1Fam	1Story	5	6	1955	1955	Gable	CompShg	MetalSd	MetalSd	None	0	TA	Gd	CBlock	TA	TA	No	Rec	648	Unf	0	324	972	GasA	TA	Y	SBrkr	972	0	0	972	0	0	1	0	3	1	TA	5	Typ	0	NA	Attchd	1955	Unf	1	305	TA	TA	Y	0	0	205	0	0	0	NA	GdWo	NA	0	6	2010	WD	Normal
1526	190	RL	70	13587	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NAmes	Norm	Norm	2fmCon	1Story	5	5	1958	1958	Gable	CompShg	MetalSd	MetalSd	None	0	TA	TA	CBlock	TA	TA	Av	Rec	532	Unf	0	456	988	GasA	TA	Y	SBrkr	988	0	0	988	1	0	1	0	2	1	TA	5	Typ	0	NA	Attchd	1958	Unf	1	264	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	4	2010	WD	Abnorml
1527	30	RL	65	7898	Pave	NA	Reg	Lvl	AllPub	Corner	Gtl	NAmes	Norm	Norm	1Fam	1Story	4	7	1920	1994	Gable	CompShg	MetalSd	MetalSd	None	0	TA	TA	BrkTil	TA	TA	No	Unf	0	Unf	0	576	576	GasA	Gd	Y	SBrkr	985	0	0	985	0	1	1	0	2	1	TA	4	Typ	0	NA	Detchd	1989	Unf	2	676	TA	TA	N	0	0	0	0	0	0	NA	NA	NA	0	4	2010	WD	Normal
1528	50	RL	60	8064	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NAmes	Artery	Norm	1Fam	1.5Fin	6	8	1948	2004	Gable	CompShg	WdShing	Wd Shng	None	0	TA	TA	CBlock	TA	TA	No	ALQ	481	Rec	174	161	816	GasA	TA	Y	SBrkr	816	408	0	1224	1	0	1	0	3	1	TA	5	Typ	0	NA	Detchd	1950	Unf	1	280	TA	TA	Y	414	0	0	0	0	0	NA	GdWo	NA	0	5	2010	WD	Normal
1529	20	RL	81	7635	Pave	NA	IR1	Lvl	AllPub	Corner	Gtl	NAmes	Norm	Norm	1Fam	1Story	5	6	1960	1960	Gable	CompShg	BrkFace	Wd Sdng	None	0	TA	TA	CBlock	TA	TA	No	Rec	588	LwQ	350	237	1175	GasA	Ex	Y	SBrkr	1175	0	0	1175	0	0	1	1	3	1	TA	6	Typ	0	NA	Detchd	1960	RFn	2	484	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	6	2010	WD	Normal
1530	20	RL	80	9760	Pave	NA	Reg	Lvl	AllPub	Inside	Mod	NAmes	Norm	Norm	1Fam	1Story	6	7	1963	1984	Hip	CompShg	Wd Sdng	Wd Sdng	BrkFace	218	TA	TA	CBlock	TA	TA	Gd	BLQ	717	LwQ	263	415	1395	GasA	TA	Y	SBrkr	1395	0	0	1395	1	0	1	0	2	1	TA	7	Min1	1	TA	Attchd	1963	RFn	2	440	TA	TA	Y	657	0	113	0	240	0	NA	NA	NA	0	5	2010	WD	Normal
1531	50	RM	60	4800	Pave	NA	Reg	Lvl	AllPub	Corner	Gtl	OldTown	Norm	Norm	1Fam	1.5Fin	4	5	1900	1954	Hip	CompShg	Wd Sdng	Wd Sdng	BrkFace	771	TA	TA	PConc	TA	TA	No	ALQ	48	Unf	0	661	709	GasA	TA	Y	SBrkr	1157	687	0	1844	1	0	1	0	3	1	TA	9	Min2	2	Gd	Basment	1900	Unf	1	240	TA	TA	Y	84	0	0	0	0	0	NA	NA	NA	0	1	2010	COD	Abnorml
1532	30	RM	56	4485	Pave	Grvl	Reg	Lvl	AllPub	Inside	Gtl	OldTown	Artery	Norm	1Fam	1Story	5	7	1920	1950	Gable	CompShg	Wd Sdng	Wd Sdng	None	0	TA	TA	PConc	TA	TA	No	BLQ	579	Unf	0	357	936	GasA	TA	Y	SBrkr	936	0	0	936	1	0	1	0	2	1	TA	5	Typ	1	Gd	NA	NA	NA	0	0	NA	NA	P	51	0	135	0	0	0	NA	MnPrv	NA	0	5	2010	WD	Normal
1533	20	RM	69	5805	Pave	Grvl	Reg	Bnk	AllPub	Inside	Mod	OldTown	Norm	Norm	1Fam	1Story	5	7	1957	1957	Hip	CompShg	MetalSd	MetalSd	None	0	TA	TA	CBlock	TA	TA	Mn	BLQ	274	Rec	1073	0	1347	GasA	Gd	Y	SBrkr	1347	0	0	1347	1	1	1	0	3	1	Gd	6	Typ	0	NA	Detchd	1957	Unf	2	551	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	6	2010	WD	Normal
1534	45	RM	50	6900	Pave	NA	Reg	Lvl	AllPub	Corner	Gtl	OldTown	Norm	Norm	1Fam	1.5Fin	6	7	1938	2000	Gable	CompShg	MetalSd	MetalSd	None	0	TA	TA	PConc	Gd	TA	No	Unf	0	Unf	0	827	827	GasA	Gd	Y	SBrkr	827	424	0	1251	0	0	1	0	3	1	Fa	6	Typ	0	NA	Detchd	1938	Unf	1	240	Fa	TA	N	0	0	0	0	0	0	NA	NA	NA	0	1	2010	WD	Normal
1535	50	RM	69	11851	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	OldTown	Artery	Norm	1Fam	1.5Fin	5	7	1948	2009	Gable	CompShg	VinylSd	VinylSd	None	0	TA	Gd	BrkTil	TA	TA	No	BLQ	780	Unf	0	247	1027	GasA	Ex	Y	SBrkr	1027	606	0	1633	0	0	1	0	3	1	Gd	7	Typ	1	Gd	Detchd	1948	Unf	1	240	TA	TA	Y	0	100	126	0	0	0	NA	NA	NA	0	6	2010	WD	Normal
1536	50	RM	NA	8239	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	OldTown	Artery	Norm	1Fam	1.5Fin	5	6	1920	1962	Gable	CompShg	MetalSd	MetalSd	None	0	TA	TA	BrkTil	TA	TA	No	Rec	176	Unf	0	832	1008	GasA	TA	Y	SBrkr	1060	185	0	1245	0	0	1	0	3	1	TA	6	Typ	0	NA	Detchd	1962	Unf	1	315	TA	TA	Y	0	0	334	0	0	0	NA	NA	NA	0	3	2010	WD	Normal
1537	30	RM	68	9656	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	OldTown	Norm	Norm	1Fam	1Story	2	2	1923	1970	Gable	CompShg	AsbShng	AsbShng	None	0	TA	Fa	BrkTil	Fa	Fa	No	Unf	0	Unf	0	678	678	GasA	TA	N	SBrkr	832	0	0	832	0	0	1	0	2	1	TA	5	Typ	1	Gd	Detchd	1928	Unf	2	780	Fa	Fa	N	0	0	0	0	0	0	NA	NA	NA	0	6	2010	WD	Abnorml
1538	70	RM	60	9600	Pave	Grvl	Reg	Lvl	AllPub	Corner	Gtl	OldTown	Norm	Norm	1Fam	2Story	8	9	1900	2003	Gable	CompShg	Wd Sdng	Wd Sdng	None	0	Gd	Gd	BrkTil	TA	TA	No	Unf	0	Unf	0	930	930	GasW	TA	N	SBrkr	930	636	0	1566	0	0	2	0	3	1	Gd	7	Typ	0	NA	Detchd	1930	Unf	1	288	TA	TA	Y	54	228	246	0	0	0	NA	NA	NA	0	4	2010	WD	Abnorml
1539	70	RM	50	9000	Pave	Grvl	Reg	Lvl	AllPub	Inside	Gtl	OldTown	Norm	Norm	1Fam	2Story	8	9	1890	2002	Gable	CompShg	Wd Sdng	Wd Sdng	None	0	Gd	Gd	Stone	Fa	Fa	No	Unf	0	Unf	0	346	346	GasA	Ex	Y	SBrkr	1157	1111	0	2268	0	0	3	0	3	1	Gd	7	Typ	0	NA	Detchd	2003	Unf	2	624	TA	TA	N	0	108	0	0	0	0	NA	NA	NA	0	4	2010	WD	Normal
1540	190	RM	100	9045	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	OldTown	Norm	Norm	2fmCon	2Story	5	3	1910	1950	Gable	CompShg	MetalSd	MetalSd	None	0	TA	Fa	BrkTil	TA	TA	Mn	Unf	0	Unf	0	840	840	Grav	Fa	N	FuseF	1128	1128	0	2256	0	0	2	0	4	2	Fa	12	Typ	0	NA	NA	NA	NA	0	0	NA	NA	N	0	18	18	0	0	0	NA	NA	NA	0	6	2010	WD	Abnorml
1541	70	RM	60	10560	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	OldTown	Norm	Norm	1Fam	2Story	6	7	1922	1994	Gable	CompShg	Wd Sdng	Wd Sdng	None	0	TA	TA	CBlock	Fa	TA	No	Rec	283	Unf	0	455	738	GasA	Ex	Y	SBrkr	868	602	0	1470	0	0	1	1	2	1	TA	6	Min1	0	NA	Detchd	1970	Unf	2	624	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	6	2010	WD	Normal
1542	50	RM	53	5830	Pave	NA	Reg	Lvl	AllPub	Corner	Gtl	BrkSide	Feedr	Feedr	1Fam	1.5Fin	5	6	1950	1997	Gable	CompShg	MetalSd	MetalSd	None	0	TA	Gd	CBlock	TA	TA	No	Rec	788	Unf	0	200	988	GasA	Ex	Y	SBrkr	1030	582	0	1612	0	0	1	1	3	1	TA	7	Typ	0	NA	Detchd	1950	Unf	1	363	TA	TA	Y	0	0	0	0	0	0	NA	MnPrv	NA	0	3	2010	WD	Normal
1543	75	RL	NA	7793	Pave	NA	IR1	Bnk	AllPub	Corner	Gtl	BrkSide	Norm	Norm	1Fam	2.5Unf	7	7	1922	2005	Gable	CompShg	Wd Sdng	Wd Sdng	None	0	TA	TA	BrkTil	Gd	TA	No	BLQ	474	Unf	0	634	1108	GasA	TA	N	FuseA	1160	908	0	2068	0	0	1	1	3	1	Gd	8	Typ	1	Gd	Detchd	1928	Unf	1	315	TA	TA	Y	0	0	60	0	0	0	NA	NA	NA	0	5	2010	WD	Normal
1544	30	RM	50	5000	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	BrkSide	Feedr	Norm	1Fam	1Story	4	7	1925	1950	Gable	CompShg	MetalSd	MetalSd	None	0	TA	TA	BrkTil	TA	TA	No	Rec	188	Unf	0	577	765	GasA	TA	N	FuseF	765	0	0	765	1	0	1	0	2	1	Gd	4	Typ	0	NA	Detchd	1926	Unf	1	200	Fa	TA	P	135	0	41	0	0	0	NA	MnPrv	NA	0	4	2010	WD	Normal
1545	50	RM	50	6000	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	BrkSide	Norm	Norm	1Fam	1.5Fin	6	7	1939	1950	Gable	CompShg	MetalSd	MetalSd	None	0	TA	TA	BrkTil	TA	Gd	No	BLQ	452	LwQ	12	144	608	GasA	TA	Y	SBrkr	608	524	0	1132	1	0	1	0	2	1	TA	5	Typ	0	NA	Detchd	1939	Unf	1	240	TA	TA	Y	0	0	128	0	0	0	NA	MnPrv	NA	0	4	2010	WD	Abnorml
1546	50	RM	50	6000	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	BrkSide	Norm	Norm	1Fam	1.5Fin	6	6	1940	1950	Gable	CompShg	MetalSd	MetalSd	None	0	TA	Gd	CBlock	TA	TA	No	LwQ	264	Unf	0	308	572	GasA	Ex	Y	FuseA	848	348	0	1196	0	1	1	1	3	1	TA	6	Typ	2	Gd	Detchd	1973	Unf	2	576	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	3	2010	WD	Normal
1547	50	RM	53	6360	Pave	NA	Reg	Lvl	AllPub	Corner	Gtl	BrkSide	Feedr	Norm	1Fam	1.5Fin	5	6	1942	1950	Gable	CompShg	MetalSd	MetalSd	Stone	300	TA	TA	CBlock	TA	TA	No	Rec	360	LwQ	159	316	835	GasA	TA	Y	FuseA	955	498	0	1453	0	0	1	1	3	1	Gd	7	Min2	2	Fa	Detchd	1942	Unf	1	240	TA	TA	Y	0	0	35	0	148	0	NA	NA	NA	0	3	2010	WD	Normal
1548	50	RM	50	6000	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	BrkSide	Norm	Norm	1Fam	1.5Fin	6	7	1948	1950	Gable	CompShg	Wd Sdng	Wd Sdng	None	0	TA	TA	CBlock	TA	TA	No	Rec	300	Unf	0	480	780	GasA	TA	Y	SBrkr	780	636	0	1416	0	0	1	1	3	1	TA	6	Typ	0	NA	Detchd	1948	Unf	1	312	TA	TA	P	221	0	48	0	0	0	NA	NA	NA	0	3	2010	WD	Normal
1549	50	RM	52	6240	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	BrkSide	Norm	Norm	1Fam	1.5Fin	5	7	1936	1980	Gable	CompShg	VinylSd	VinylSd	None	0	TA	TA	CBlock	TA	Fa	No	Rec	276	Unf	0	252	528	GasA	Gd	Y	SBrkr	548	492	0	1040	0	0	1	0	2	1	TA	5	Typ	0	NA	Detchd	1979	Fin	2	624	TA	TA	P	306	0	32	0	0	0	NA	NA	NA	0	5	2010	WD	Normal
1550	50	RM	52	6240	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	BrkSide	Norm	Norm	1Fam	1.5Fin	5	5	1930	1950	Gable	CompShg	MetalSd	MetalSd	None	0	TA	TA	BrkTil	TA	TA	No	LwQ	448	Unf	0	480	928	GasA	TA	Y	FuseF	928	608	0	1536	0	0	2	0	4	1	TA	7	Typ	1	Gd	Detchd	1930	Unf	2	480	TA	TA	Y	0	10	0	0	0	0	NA	MnPrv	NA	0	3	2010	WD	Normal
1551	30	RM	51	6120	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	OldTown	Artery	Norm	1Fam	1Story	6	5	1923	1950	Gable	CompShg	Wd Sdng	Wd Sdng	None	0	TA	TA	BrkTil	Fa	Fa	No	ALQ	960	Unf	0	164	1124	GasA	TA	Y	SBrkr	1068	0	0	1068	1	0	1	0	2	1	TA	5	Typ	1	Gd	Detchd	1923	Unf	1	288	TA	TA	Y	0	0	128	0	0	0	NA	NA	NA	0	3	2010	WD	Normal
1552	50	RM	57	8094	Pave	Grvl	Reg	Lvl	AllPub	Inside	Gtl	OldTown	Norm	Norm	1Fam	1.5Fin	4	5	1915	1950	Gable	CompShg	MetalSd	MetalSd	None	0	TA	Fa	CBlock	TA	TA	No	Unf	0	Unf	0	888	888	GasA	Ex	Y	SBrkr	888	1074	0	1962	0	0	1	1	4	1	TA	9	Typ	1	TA	Detchd	1915	Unf	2	572	TA	TA	Y	160	0	364	0	0	0	NA	GdPrv	NA	0	6	2010	WD	Normal
1553	70	RM	60	12900	Pave	Grvl	Reg	Lvl	AllPub	Inside	Gtl	OldTown	Norm	Norm	1Fam	2Story	6	8	1912	2009	Gable	CompShg	Wd Sdng	Wd Sdng	None	0	Gd	Gd	PConc	TA	TA	No	Unf	0	Unf	0	780	780	GasA	Ex	Y	SBrkr	780	780	0	1560	0	0	1	1	3	1	Gd	7	Typ	0	NA	NA	NA	NA	0	0	NA	NA	N	344	0	0	0	168	0	NA	NA	NA	0	5	2010	WD	Normal
1554	70	RM	52	3068	Pave	Grvl	Reg	Lvl	AllPub	Inside	Gtl	OldTown	Norm	Norm	1Fam	2Story	6	8	1920	1993	Gable	CompShg	VinylSd	VinylSd	None	0	TA	Gd	BrkTil	TA	TA	No	Unf	0	Unf	0	662	662	GasA	Ex	Y	SBrkr	662	662	0	1324	0	1	1	0	3	1	TA	6	Typ	0	NA	Detchd	1920	Unf	1	180	TA	TA	Y	0	0	112	0	0	0	NA	GdPrv	NA	0	2	2010	WD	Normal
1555	20	RL	100	15263	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	ClearCr	Feedr	Norm	1Fam	1Story	5	5	1959	1959	Gable	CompShg	HdBoard	HdBoard	BrkFace	90	TA	TA	CBlock	Gd	TA	No	Rec	766	Unf	0	656	1422	GasA	Gd	Y	SBrkr	1675	0	0	1675	0	0	2	0	3	1	TA	8	Typ	2	Gd	Attchd	1959	Unf	1	365	TA	TA	Y	0	132	0	0	0	0	NA	NA	NA	0	5	2010	WD	Normal
1556	50	RL	72	10632	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	ClearCr	Norm	Norm	1Fam	1.5Fin	5	3	1917	1950	Gable	CompShg	Wd Sdng	Wd Sdng	None	0	TA	TA	BrkTil	Gd	Fa	No	Unf	0	Unf	0	689	689	GasA	Gd	N	SBrkr	725	499	0	1224	0	0	1	1	3	1	NA	6	Mod	0	NA	Detchd	1917	Unf	1	180	Fa	Fa	N	0	0	248	0	0	0	NA	NA	NA	0	1	2010	COD	Normal
1557	190	RL	60	9900	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	SWISU	Norm	Norm	2fmCon	1.5Fin	5	4	1915	1950	Gable	CompShg	Wd Sdng	Wd Shng	None	0	Fa	Fa	BrkTil	TA	TA	No	Rec	1026	Unf	0	186	1212	GasA	TA	N	SBrkr	1212	180	0	1392	1	0	1	0	3	1	TA	6	Typ	0	NA	NA	NA	NA	0	0	NA	NA	N	0	0	168	0	0	0	NA	NA	NA	0	2	2010	ConLD	Normal
1558	50	RL	65	6001	Pave	NA	IR1	Bnk	AllPub	Inside	Mod	SWISU	Norm	Norm	1Fam	1.5Fin	6	5	1940	1950	Gable	CompShg	VinylSd	VinylSd	None	0	TA	TA	CBlock	Fa	TA	No	LwQ	368	Unf	0	232	600	GasA	Ex	N	SBrkr	600	319	0	919	0	0	1	0	3	1	TA	5	Typ	0	NA	Detchd	1940	Unf	1	231	TA	TA	Y	0	0	45	0	0	0	NA	MnPrv	NA	0	3	2010	WD	Normal
1559	70	C (all)	NA	6449	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	SWISU	Norm	Norm	1Fam	2Story	4	1	1907	1950	Gambrel	CompShg	Wd Sdng	Stucco	None	0	TA	TA	CBlock	TA	TA	No	Rec	73	Unf	0	634	707	GasW	TA	N	SBrkr	942	942	0	1884	0	0	1	1	4	1	TA	7	Typ	0	NA	NA	NA	NA	0	0	NA	NA	N	0	0	239	0	0	0	NA	NA	NA	0	3	2010	WD	Abnorml
1560	190	RH	60	6048	Pave	NA	Reg	Lvl	AllPub	Corner	Gtl	SWISU	Artery	Norm	2fmCon	1.5Fin	5	7	1910	1950	Gable	CompShg	Wd Sdng	Wd Sdng	None	0	TA	Gd	BrkTil	TA	TA	Mn	LwQ	736	Unf	0	120	856	GasA	Gd	Y	SBrkr	936	744	0	1680	1	0	2	0	2	2	TA	7	Typ	1	Gd	Detchd	1910	Unf	2	450	TA	Fa	P	56	144	0	0	0	0	NA	NA	NA	0	6	2010	COD	Normal
1561	90	RL	72	10773	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Sawyer	Norm	Norm	Duplex	1Story	4	3	1967	1967	Gable	Tar&Grv	Plywood	Plywood	BrkFace	72	Fa	Fa	CBlock	TA	TA	No	ALQ	704	Unf	0	1128	1832	GasA	TA	N	SBrkr	1832	0	0	1832	2	0	2	0	4	2	TA	8	Typ	0	NA	NA	NA	NA	0	0	NA	NA	Y	0	58	0	0	0	0	NA	NA	NA	0	5	2010	WD	Normal
1562	20	RL	65	7800	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Sawyer	Norm	Norm	1Fam	1Story	5	7	1966	2008	Hip	CompShg	HdBoard	HdBoard	BrkFace	47	TA	TA	CBlock	TA	TA	Mn	BLQ	240	Rec	474	150	864	GasA	Ex	Y	SBrkr	892	0	0	892	1	0	1	0	3	1	Gd	5	Typ	0	NA	Detchd	1966	Unf	1	416	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	6	2010	WD	Normal
1563	20	RL	65	7832	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Sawyer	Norm	Norm	1Fam	1Story	5	5	1968	1968	Hip	CompShg	HdBoard	HdBoard	None	0	TA	TA	CBlock	TA	TA	No	GLQ	775	Unf	0	89	864	GasA	Ex	Y	SBrkr	864	0	0	864	1	0	1	0	2	1	TA	4	Typ	0	NA	Detchd	1969	Unf	1	280	TA	TA	Y	226	0	0	0	0	0	NA	NA	NA	0	5	2010	WD	Normal
1564	90	RL	NA	7424	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Sawyer	Norm	Norm	Duplex	SFoyer	5	5	1978	1978	Gable	CompShg	Plywood	Plywood	None	0	TA	TA	CBlock	Gd	TA	Av	GLQ	1319	Unf	0	0	1319	GasA	TA	Y	SBrkr	1373	0	0	1373	1	0	1	0	3	1	TA	5	Typ	2	TA	Attchd	1978	Fin	2	591	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	5	2010	WD	Normal
1565	60	RL	86	11227	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Sawyer	Norm	Norm	1Fam	2Story	5	5	1968	1968	Gable	CompShg	HdBoard	HdBoard	None	0	TA	Gd	CBlock	TA	Gd	No	Rec	267	ALQ	453	0	720	GasA	Ex	Y	SBrkr	720	720	0	1440	0	0	1	1	4	1	TA	7	Typ	2	TA	Attchd	1968	Unf	2	480	TA	TA	Y	192	38	0	0	0	0	NA	MnPrv	NA	0	3	2010	WD	Normal
1566	20	RL	NA	20062	Pave	NA	IR1	Low	AllPub	Inside	Mod	ClearCr	Norm	Norm	1Fam	1Story	7	7	1977	2001	Hip	CompShg	Wd Sdng	Wd Sdng	None	0	Gd	Gd	CBlock	Gd	TA	Gd	ALQ	1092	Unf	0	328	1420	GasA	Gd	Y	SBrkr	1483	0	0	1483	1	0	1	1	1	1	TA	4	Typ	2	TA	Attchd	1977	RFn	2	690	TA	TA	Y	496	0	0	0	0	0	NA	NA	NA	0	4	2010	WD	Normal
1567	30	RL	94	9259	Pave	NA	Reg	Lvl	AllPub	Corner	Gtl	Sawyer	Feedr	Norm	1Fam	1Story	4	4	1927	1950	Gable	CompShg	Wd Sdng	Wd Sdng	None	0	TA	TA	BrkTil	Fa	TA	No	Unf	0	Unf	0	660	660	GasA	TA	N	SBrkr	756	0	0	756	0	0	1	0	2	1	TA	4	Typ	0	NA	Detchd	1945	Unf	2	440	TA	TA	N	80	0	0	0	0	0	NA	NA	NA	0	6	2010	WD	Normal
1568	60	RL	NA	17082	Pave	NA	IR1	Low	AllPub	CulDSac	Mod	ClearCr	Norm	Norm	1Fam	2Story	6	5	1978	1992	Gable	CompShg	VinylSd	VinylSd	BrkFace	288	TA	TA	PConc	Gd	TA	Av	ALQ	964	Unf	0	153	1117	GasA	Ex	Y	SBrkr	1117	864	0	1981	1	0	2	1	4	1	Gd	8	Typ	1	TA	Attchd	1978	Fin	2	522	TA	TA	Y	336	104	0	0	0	0	NA	NA	NA	0	5	2010	WD	Normal
1569	50	RL	124	18600	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Edwards	Norm	Norm	1Fam	1.5Fin	3	4	1938	1990	Gable	CompShg	Wd Sdng	Wd Sdng	None	0	TA	TA	CBlock	TA	TA	Mn	BLQ	288	LwQ	684	0	972	GasA	TA	Y	FuseA	1052	558	0	1610	0	1	2	0	4	1	Fa	8	Typ	1	Gd	Attchd	1938	RFn	1	480	TA	TA	Y	0	0	60	0	0	0	NA	NA	Shed	450	6	2010	WD	Normal
1570	20	RL	65	11479	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Edwards	Norm	Norm	1Fam	1Story	6	7	1950	1987	Gable	CompShg	Wd Sdng	Plywood	None	0	TA	TA	CBlock	TA	TA	No	GLQ	104	Rec	387	172	663	GasA	Ex	Y	SBrkr	1074	0	0	1074	1	0	1	0	3	1	Gd	6	Typ	1	TA	Attchd	1987	Unf	1	467	TA	TA	Y	0	52	52	0	0	0	NA	MnPrv	NA	0	6	2010	WD	Normal
1571	50	RL	50	9350	Pave	NA	Reg	Bnk	AllPub	Inside	Gtl	Edwards	Norm	Norm	1Fam	1.5Fin	4	6	1947	1979	Gable	CompShg	WdShing	Wd Shng	None	0	TA	TA	CBlock	TA	Fa	No	LwQ	192	Unf	0	564	756	GasA	Ex	Y	SBrkr	1169	0	362	1531	0	0	1	0	3	1	TA	8	Typ	1	TA	Detchd	1947	Unf	1	209	Fa	TA	Y	0	0	0	0	0	0	NA	MnPrv	NA	0	6	2010	WD	Normal
1572	20	RL	75	9525	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Edwards	Norm	Norm	1Fam	1Story	5	7	1954	1998	Gable	CompShg	WdShing	Wd Shng	None	0	TA	TA	CBlock	TA	TA	Av	BLQ	954	Unf	0	218	1172	GasA	TA	Y	SBrkr	1172	0	0	1172	1	0	1	0	3	1	TA	5	Typ	0	NA	Attchd	1954	Fin	1	366	TA	TA	Y	240	0	0	0	0	0	NA	NA	NA	0	6	2010	WD	Normal
1573	20	RL	44	17485	Pave	NA	IR2	Lvl	AllPub	Inside	Gtl	Edwards	Norm	Norm	1Fam	1Story	7	5	2009	2010	Gable	CompShg	VinylSd	VinylSd	Stone	96	Gd	TA	PConc	Gd	TA	Gd	GLQ	1346	Unf	0	162	1508	GasA	Ex	Y	SBrkr	1508	0	0	1508	1	0	1	0	1	1	Gd	5	Typ	2	TA	Attchd	2009	RFn	2	572	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	1	2010	Con	Partial
1574	20	RL	NA	11200	Pave	NA	IR1	Lvl	AllPub	CulDSac	Gtl	Edwards	Norm	Norm	1Fam	1Story	5	3	1964	1964	Gable	CompShg	Wd Sdng	Wd Sdng	None	0	TA	Fa	CBlock	TA	TA	Mn	Unf	0	Unf	0	1250	1250	GasA	Ex	Y	SBrkr	1298	0	0	1298	0	0	2	0	3	1	TA	5	Typ	0	NA	Detchd	1964	Unf	2	504	TA	Fa	N	0	144	0	0	0	0	NA	NA	NA	0	6	2010	COD	Normal
1575	20	RL	83	11980	Pave	NA	Reg	Low	AllPub	Inside	Mod	SawyerW	Norm	Norm	1Fam	1Story	7	5	1987	1987	Gable	CompShg	Plywood	Plywood	BrkFace	177	Gd	TA	CBlock	Gd	TA	Gd	GLQ	1433	Unf	0	0	1433	GasA	Ex	Y	SBrkr	1433	0	0	1433	1	0	1	1	1	1	Gd	4	Typ	2	TA	Attchd	1987	RFn	2	528	Gd	Gd	Y	0	278	0	0	266	0	NA	MnPrv	NA	0	6	2010	WD	Normal
1576	60	RL	87	12361	Pave	NA	IR1	Lvl	AllPub	CulDSac	Gtl	SawyerW	Norm	Norm	1Fam	2Story	6	7	1993	1993	Gable	CompShg	VinylSd	VinylSd	BrkFace	85	Gd	Gd	PConc	Gd	TA	No	GLQ	860	Unf	0	86	946	GasA	Ex	Y	SBrkr	964	838	0	1802	0	1	2	1	3	1	Gd	8	Typ	1	Gd	2Types	2000	RFn	4	1017	TA	TA	Y	450	92	0	0	0	0	NA	NA	NA	0	5	2010	WD	Normal
1577	20	RL	64	7360	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	CollgCr	Norm	Norm	1Fam	1Story	7	5	2010	2010	Gable	CompShg	VinylSd	VinylSd	Stone	80	Gd	TA	PConc	Gd	TA	No	GLQ	24	Unf	0	1198	1222	GasA	Ex	Y	SBrkr	1222	0	0	1222	0	0	2	0	2	1	Gd	6	Typ	0	NA	Attchd	2009	RFn	2	615	TA	TA	Y	0	54	0	0	0	0	NA	NA	NA	0	3	2010	WD	Normal
1578	50	RL	82	14235	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	SawyerW	Norm	Norm	1Fam	1.5Fin	6	8	1900	1993	Gable	CompShg	Wd Sdng	Plywood	None	0	TA	TA	PConc	Fa	Gd	No	Unf	0	Unf	0	676	676	GasA	TA	Y	SBrkr	831	614	0	1445	0	0	2	0	3	1	TA	6	Typ	0	NA	Detchd	1957	Unf	2	484	TA	TA	N	0	59	0	0	0	0	NA	NA	NA	0	3	2010	WD	Normal
1579	85	RL	82	11105	Pave	NA	Reg	Lvl	AllPub	Corner	Gtl	CollgCr	Norm	Norm	1Fam	SFoyer	5	5	1996	1996	Gable	CompShg	VinylSd	VinylSd	None	0	TA	Gd	PConc	Gd	Fa	Av	GLQ	870	Unf	0	0	870	GasA	Gd	Y	SBrkr	965	0	0	965	1	0	1	0	2	1	TA	4	Typ	0	NA	Attchd	1998	Unf	2	580	Gd	TA	Y	71	0	0	0	0	0	NA	GdPrv	NA	0	7	2010	WD	Normal
1580	60	RL	NA	9337	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	CollgCr	Norm	Norm	1Fam	2Story	7	5	1997	1998	Gable	CompShg	VinylSd	VinylSd	None	0	TA	TA	PConc	Gd	TA	No	ALQ	353	Unf	0	525	878	GasA	Ex	Y	SBrkr	892	800	0	1692	0	0	2	1	3	1	TA	8	Typ	1	TA	Attchd	1997	RFn	2	513	TA	TA	Y	0	39	0	0	0	0	NA	NA	NA	0	4	2010	WD	Normal
1581	20	RL	38	15240	Pave	NA	IR1	Lvl	AllPub	FR2	Gtl	CollgCr	Norm	Norm	1Fam	1Story	5	8	1977	2004	Gable	CompShg	CemntBd	CmentBd	None	0	Gd	Gd	CBlock	Gd	TA	No	GLQ	198	Rec	688	140	1026	GasA	Ex	Y	SBrkr	1026	0	0	1026	1	0	1	1	3	1	TA	5	Typ	0	NA	Attchd	1977	Unf	1	308	TA	TA	Y	316	85	0	0	0	0	NA	MnPrv	NA	0	6	2010	WD	Normal
1582	20	RL	68	7480	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	CollgCr	Norm	Norm	1Fam	1Story	5	6	1972	1972	Gable	CompShg	Wd Sdng	Wd Sdng	None	0	TA	TA	CBlock	TA	TA	Av	ALQ	480	Unf	0	396	876	GasA	TA	Y	SBrkr	876	0	0	876	1	0	1	0	3	1	TA	5	Typ	0	NA	Detchd	1977	Unf	2	484	TA	TA	Y	0	0	0	0	0	0	NA	MnPrv	NA	0	6	2010	WD	Normal
1583	20	RL	80	10389	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	CollgCr	Norm	Norm	1Fam	1Story	8	5	2003	2003	Hip	CompShg	CemntBd	CmentBd	BrkFace	320	Gd	TA	PConc	Gd	TA	No	GLQ	1682	Unf	0	296	1978	GasA	Ex	Y	SBrkr	1978	0	0	1978	1	0	2	1	3	1	Gd	8	Typ	1	Gd	Attchd	2003	RFn	3	850	TA	TA	Y	188	25	0	0	0	0	NA	NA	NA	0	5	2010	WD	Normal
1584	60	RL	75	9375	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	CollgCr	Norm	Norm	1Fam	2Story	7	5	1997	1997	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	TA	No	Unf	0	Unf	0	1040	1040	GasA	Ex	Y	SBrkr	1044	1054	0	2098	0	0	2	1	4	1	Gd	9	Typ	1	TA	Attchd	1997	Fin	2	621	TA	TA	Y	331	38	0	0	0	0	NA	NA	NA	0	4	2010	WD	Normal
1585	120	RM	NA	4435	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	CollgCr	Norm	Norm	TwnhsE	1Story	6	5	2003	2003	Gable	CompShg	VinylSd	VinylSd	BrkFace	170	Gd	TA	PConc	Gd	TA	Av	GLQ	672	Unf	0	176	848	GasA	Ex	Y	SBrkr	848	0	0	848	1	0	1	0	1	1	Gd	4	Typ	0	NA	Attchd	2003	Fin	2	420	TA	TA	Y	140	0	0	0	0	0	NA	NA	NA	0	4	2010	WD	Normal
1586	30	RL	67	8777	Pave	NA	Reg	Lvl	AllPub	Inside	Mod	Edwards	Feedr	Norm	1Fam	1Story	3	6	1945	2007	Gable	CompShg	VinylSd	VinylSd	None	0	TA	Gd	CBlock	NA	NA	NA	NA	0	NA	0	0	0	GasA	TA	N	SBrkr	640	0	0	640	0	0	1	0	2	1	TA	5	Min1	0	NA	Detchd	1945	Unf	1	240	TA	TA	N	0	0	0	0	0	0	NA	NA	NA	0	4	2010	ConLD	Normal
1587	20	RL	68	8842	Pave	NA	Reg	Lvl	AllPub	Corner	Gtl	Edwards	Norm	Norm	1Fam	1Story	5	6	1954	1954	Gable	CompShg	VinylSd	VinylSd	None	0	TA	Gd	CBlock	Fa	TA	No	Unf	0	Unf	0	381	381	GasA	Ex	Y	SBrkr	992	0	0	992	0	0	1	0	3	1	TA	6	Typ	0	NA	Detchd	1954	Unf	1	319	TA	TA	Y	60	0	56	0	0	0	NA	MnPrv	NA	0	1	2010	Oth	Abnorml
1588	20	RL	60	10044	Pave	NA	IR1	Low	AllPub	CulDSac	Gtl	Edwards	Norm	Norm	1Fam	1Story	5	6	1968	1968	Gable	CompShg	MetalSd	MetalSd	None	0	TA	TA	CBlock	Gd	TA	Gd	ALQ	1070	Unf	0	126	1196	GasA	TA	Y	SBrkr	1196	0	0	1196	1	0	1	0	3	1	TA	6	Typ	0	NA	Attchd	1968	RFn	1	336	TA	TA	Y	257	0	168	0	0	0	NA	MnPrv	NA	0	6	2010	WD	Normal
1589	50	RL	89	11792	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Edwards	Norm	Norm	1Fam	1.5Fin	4	5	1948	1950	Gable	CompShg	VinylSd	VinylSd	None	0	TA	TA	CBlock	TA	TA	No	Unf	0	Unf	0	744	744	GasA	Ex	N	FuseF	792	328	0	1120	0	0	1	0	2	1	Fa	5	Typ	0	NA	Detchd	1956	Unf	2	480	TA	Fa	P	0	0	0	0	160	0	NA	NA	NA	0	6	2010	WD	Abnorml
1590	80	RL	65	6305	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Edwards	Norm	Norm	1Fam	SLvl	6	6	1975	1975	Gable	CompShg	Plywood	Plywood	None	0	TA	TA	CBlock	TA	TA	Av	ALQ	528	Unf	0	480	1008	GasA	TA	Y	SBrkr	1096	0	0	1096	1	0	1	0	3	1	TA	5	Typ	1	Fa	Detchd	1975	Unf	1	352	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	6	2010	WD	Normal
1591	20	RL	64	6410	Pave	NA	Reg	HLS	AllPub	Inside	Gtl	Edwards	Norm	Norm	1Fam	1Story	4	5	1958	1958	Hip	CompShg	WdShing	Wd Shng	None	0	TA	TA	CBlock	TA	TA	No	Unf	0	Unf	0	960	960	GasA	Ex	Y	SBrkr	960	0	0	960	0	0	1	0	3	1	TA	5	Typ	0	NA	NA	NA	NA	0	0	NA	NA	Y	0	0	0	0	0	0	NA	MnPrv	NA	0	5	2010	WD	Normal
1592	30	RL	67	4853	Pave	NA	Reg	Bnk	AllPub	Inside	Gtl	SWISU	Artery	Norm	1Fam	1Story	5	6	1924	1999	Gable	CompShg	MetalSd	VinylSd	BrkFace	203	TA	TA	BrkTil	TA	TA	Mn	Rec	133	Unf	0	974	1107	GasA	Fa	N	FuseA	1296	0	0	1296	0	0	2	0	2	1	Fa	5	Typ	1	Gd	Detchd	1979	Unf	1	260	TA	TA	Y	0	0	36	0	0	0	NA	MnPrv	NA	0	5	2010	WD	Normal
1593	30	RL	NA	7890	Pave	NA	Reg	Lvl	AllPub	Corner	Gtl	SWISU	Norm	Norm	1Fam	1Story	6	6	1939	1950	Gable	CompShg	Wd Sdng	Wd Sdng	None	0	TA	TA	CBlock	TA	TA	No	Rec	238	Unf	0	618	856	GasA	TA	Y	SBrkr	856	0	0	856	1	0	1	0	2	1	TA	4	Typ	1	Gd	Detchd	1939	Unf	2	399	TA	TA	Y	0	0	0	0	166	0	NA	NA	NA	0	3	2010	WD	Normal
1594	90	RH	60	7200	Pave	Pave	Reg	Lvl	AllPub	Inside	Gtl	SWISU	Norm	Norm	Duplex	2Story	4	6	1967	1967	Flat	Tar&Grv	Plywood	CBlock	None	0	TA	TA	Slab	NA	NA	NA	NA	0	NA	0	0	0	GasA	TA	Y	SBrkr	862	1788	0	2650	0	0	3	0	6	2	TA	10	Min2	0	NA	NA	NA	NA	0	0	NA	NA	Y	0	0	0	0	0	0	NA	NA	Shed	500	2	2010	WD	Normal
1595	50	RL	51	9839	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	SWISU	Feedr	Norm	1Fam	1.5Fin	5	2	1931	1950	Gable	CompShg	VinylSd	VinylSd	None	0	TA	TA	PConc	TA	Fa	No	Unf	0	Unf	0	894	894	GasA	Ex	Y	SBrkr	894	772	0	1666	1	0	1	0	3	1	TA	7	Typ	1	Gd	NA	NA	NA	0	0	NA	NA	N	0	156	0	0	0	0	NA	NA	NA	0	5	2010	WD	Normal
1596	50	RL	78	10452	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Crawfor	Norm	Norm	1Fam	1.5Fin	7	6	1941	1985	Gable	CompShg	Wd Sdng	Wd Sdng	BrkFace	371	Gd	Gd	BrkTil	Gd	TA	No	ALQ	426	BLQ	252	850	1528	GasA	Ex	Y	SBrkr	1225	908	0	2133	1	0	1	1	4	1	TA	8	Typ	2	TA	Attchd	1941	Unf	1	312	TA	TA	Y	0	0	86	0	0	0	NA	NA	NA	0	7	2010	WD	Normal
1597	90	RL	78	15600	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Crawfor	Norm	Norm	Duplex	2Story	5	6	1950	1991	Gable	CompShg	VinylSd	VinylSd	BrkFace	430	TA	Gd	CBlock	TA	TA	No	ALQ	375	Unf	0	657	1032	GasA	Ex	Y	SBrkr	1102	1075	0	2177	0	0	2	1	5	2	TA	11	Typ	0	NA	Detchd	1950	Unf	2	484	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	3	2010	WD	Normal
1598	80	RL	85	19645	Pave	NA	IR1	Lvl	AllPub	FR2	Gtl	Crawfor	Norm	Norm	1Fam	SLvl	7	6	1994	2007	Gable	CompShg	VinylSd	VinylSd	BrkFace	44	TA	TA	PConc	Gd	TA	No	GLQ	343	Unf	0	80	423	GasA	Ex	Y	SBrkr	896	756	0	1652	1	0	2	1	3	1	Gd	6	Typ	0	NA	BuiltIn	1994	RFn	2	473	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	6	2010	WD	Normal
1599	120	RM	35	3907	Pave	NA	IR1	HLS	AllPub	Inside	Mod	Blueste	Norm	Norm	TwnhsE	1Story	8	6	1989	1989	Gable	CompShg	HdBoard	HdBoard	None	0	Gd	TA	CBlock	Gd	TA	Gd	GLQ	747	Unf	0	235	982	GasA	Gd	Y	SBrkr	1034	0	0	1034	1	0	1	0	1	1	Gd	4	Typ	1	TA	Attchd	1989	Fin	2	598	TA	TA	Y	141	36	0	0	0	0	NA	NA	NA	0	4	2010	WD	Normal
1600	120	RM	35	3907	Pave	NA	IR1	HLS	AllPub	Inside	Mod	Blueste	Norm	Norm	TwnhsE	1Story	8	5	1989	1989	Gable	CompShg	HdBoard	HdBoard	None	0	Gd	TA	CBlock	Gd	TA	Av	GLQ	76	Unf	0	1115	1191	GasA	Gd	Y	SBrkr	1191	0	0	1191	0	0	2	0	2	1	Gd	5	Typ	1	TA	Attchd	1989	Unf	2	531	TA	TA	Y	112	81	0	0	0	0	NA	NA	NA	0	3	2010	WD	Normal
1601	30	RM	58	8154	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	IDOTRR	Norm	Norm	1Fam	1Story	2	5	1941	1950	Gable	CompShg	Wd Sdng	Wd Sdng	None	0	TA	TA	BrkTil	TA	TA	No	BLQ	480	Unf	0	0	480	GasA	TA	Y	SBrkr	540	0	0	540	0	0	1	0	1	1	TA	4	Typ	0	NA	Detchd	1951	Unf	1	200	Fa	Fa	N	0	0	0	0	0	0	NA	NA	NA	0	4	2010	ConLw	Normal
1602	50	RM	50	9140	Pave	NA	Reg	HLS	AllPub	Inside	Gtl	IDOTRR	Norm	Norm	1Fam	1.5Fin	6	5	1921	1975	Gable	CompShg	Wd Sdng	Wd Sdng	None	0	TA	TA	BrkTil	TA	TA	Mn	BLQ	308	Unf	0	321	629	GasA	Fa	Y	SBrkr	727	380	0	1107	0	0	1	0	2	1	TA	5	Typ	0	NA	Detchd	1950	Unf	1	625	TA	TA	Y	0	56	0	0	200	0	NA	MnPrv	NA	0	4	2010	COD	Normal
1603	30	C (all)	66	8712	Grvl	NA	Reg	Lvl	AllPub	Corner	Gtl	IDOTRR	Norm	Norm	1Fam	1Story	4	7	1896	1950	Hip	CompShg	Wd Sdng	Wd Sdng	None	0	Fa	Fa	CBlock	TA	TA	No	Unf	0	Unf	0	756	756	GasA	Gd	Y	SBrkr	952	0	0	952	0	0	1	0	3	1	TA	5	Typ	0	NA	Detchd	1896	RFn	1	330	TA	TA	N	0	0	265	0	0	0	NA	NA	NA	0	6	2010	WD	Alloca
1604	120	RM	44	3811	Pave	NA	IR1	HLS	AllPub	Corner	Mod	Crawfor	Artery	Norm	TwnhsE	1Story	8	5	2004	2005	Hip	CompShg	CemntBd	CmentBd	Stone	186	Gd	TA	PConc	Ex	TA	Gd	GLQ	1373	Unf	0	221	1594	GasA	Ex	Y	SBrkr	1646	0	0	1646	1	1	2	0	2	1	Gd	5	Typ	1	Gd	Attchd	2004	Fin	2	525	TA	TA	Y	128	53	0	0	155	0	NA	NA	NA	0	5	2010	WD	Normal
1605	60	RL	85	11050	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Mitchel	Norm	Norm	1Fam	2Story	8	5	1998	1999	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	TA	No	GLQ	615	Unf	0	434	1049	GasA	Ex	Y	SBrkr	1036	880	0	1916	1	0	2	1	3	1	Gd	8	Typ	1	TA	Attchd	1998	Unf	3	741	TA	TA	Y	0	70	0	0	0	0	NA	NA	NA	0	5	2010	WD	Normal
1606	80	RL	74	9620	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Mitchel	Norm	Norm	1Fam	SLvl	6	7	1977	1977	Gable	CompShg	Plywood	Plywood	None	0	TA	TA	CBlock	TA	TA	No	ALQ	679	Unf	0	564	1243	GasA	TA	Y	SBrkr	1285	0	0	1285	0	1	2	0	3	1	Gd	6	Typ	1	Fa	Attchd	1977	Unf	2	473	TA	TA	Y	375	26	0	0	0	0	NA	GdPrv	Shed	80	5	2010	WD	Normal
1607	90	RL	NA	12760	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Mitchel	Norm	Norm	Duplex	1Story	6	5	1976	1976	Gable	CompShg	Plywood	Plywood	None	0	TA	TA	CBlock	TA	TA	No	Unf	0	Unf	0	1958	1958	GasA	TA	Y	SBrkr	2048	0	0	2048	0	0	3	0	5	2	TA	9	Typ	0	NA	2Types	1976	Unf	2	776	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	3	2010	ConLD	Normal
1608	20	RL	88	11896	Pave	NA	IR1	Lvl	AllPub	Corner	Gtl	Timber	Norm	Norm	1Fam	1Story	7	5	2008	2008	Gable	CompShg	VinylSd	VinylSd	Stone	60	Gd	TA	PConc	Gd	TA	No	GLQ	78	Unf	0	1258	1336	GasA	Ex	Y	SBrkr	1346	0	0	1346	1	0	2	0	3	1	Gd	6	Typ	1	TA	Attchd	2008	Fin	3	660	TA	TA	Y	100	48	0	0	0	0	NA	NA	NA	0	5	2010	WD	Normal
1609	20	RL	73	9803	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Timber	Norm	Norm	1Fam	1Story	7	5	2009	2010	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	TA	No	Unf	0	Unf	0	1214	1214	GasA	Ex	Y	SBrkr	1214	0	0	1214	0	0	2	0	2	1	Gd	6	Typ	0	NA	Attchd	2010	RFn	2	520	TA	TA	Y	0	25	0	0	0	0	NA	NA	NA	0	1	2010	New	Partial
1610	60	RL	73	9802	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Timber	Norm	Norm	1Fam	2Story	5	5	2006	2007	Gable	CompShg	VinylSd	VinylSd	None	0	TA	TA	PConc	Gd	TA	No	Unf	0	Unf	0	384	384	GasA	Gd	Y	SBrkr	744	700	0	1444	0	0	2	1	3	1	TA	7	Typ	0	NA	BuiltIn	2007	Fin	2	400	TA	TA	Y	100	0	0	0	0	0	NA	NA	NA	0	4	2010	WD	Normal
1611	20	RL	85	15300	Pave	NA	Reg	Bnk	AllPub	Inside	Gtl	Mitchel	Norm	Norm	1Fam	1Story	5	5	1965	1977	Hip	CompShg	Plywood	HdBoard	None	0	TA	TA	CBlock	TA	TA	No	Rec	42	Unf	0	1026	1068	GasA	TA	Y	SBrkr	1264	0	0	1264	1	0	1	0	2	1	TA	7	Typ	1	TA	Attchd	1965	Unf	2	528	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	6	2010	WD	Normal
1612	20	RL	93	10114	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Mitchel	Norm	Norm	1Fam	1Story	5	5	2004	2005	Gable	CompShg	VinylSd	VinylSd	None	0	TA	TA	PConc	Ex	TA	Av	Unf	0	Unf	0	1430	1430	GasA	Ex	Y	SBrkr	1430	0	0	1430	0	0	2	0	3	1	Gd	7	Typ	0	NA	Attchd	2004	RFn	2	624	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	3	2010	WD	Normal
1613	20	RL	NA	11875	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Mitchel	Norm	Norm	1Fam	1Story	5	5	1999	1999	Gable	CompShg	VinylSd	VinylSd	None	0	TA	TA	PConc	Gd	TA	No	Unf	0	Unf	0	1344	1344	GasA	Ex	Y	SBrkr	1344	0	0	1344	0	0	2	0	3	1	TA	7	Typ	1	Gd	Attchd	2001	Unf	2	686	TA	TA	Y	328	0	0	0	0	0	NA	NA	NA	0	6	2010	WD	Normal
1614	120	RM	31	2394	Pave	NA	Reg	Low	AllPub	Inside	Mod	MeadowV	Norm	Norm	Twnhs	1Story	5	6	1973	1973	Gable	CompShg	CemntBd	CmentBd	None	0	TA	TA	CBlock	Gd	TA	Gd	GLQ	915	Unf	0	30	945	GasA	Ex	Y	SBrkr	945	0	0	945	1	1	1	0	2	1	TA	5	Typ	1	Po	Attchd	1973	RFn	1	253	TA	TA	Y	174	0	56	0	108	0	NA	NA	NA	0	5	2010	WD	Normal
1615	160	RM	21	1476	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	MeadowV	Norm	Norm	Twnhs	2Story	4	7	1970	1970	Gable	CompShg	CemntBd	CmentBd	None	0	TA	TA	CBlock	TA	TA	No	GLQ	176	Unf	0	370	546	GasA	Ex	Y	SBrkr	546	546	0	1092	0	0	1	1	3	1	TA	5	Typ	0	NA	NA	NA	NA	0	0	NA	NA	Y	200	26	0	0	0	0	NA	NA	NA	0	3	2010	WD	Normal
1616	160	RM	21	1900	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	MeadowV	Norm	Norm	TwnhsE	2Story	4	4	1970	1970	Gable	CompShg	CemntBd	CmentBd	None	0	TA	TA	CBlock	TA	TA	No	Unf	0	Unf	0	546	546	GasA	Ex	Y	SBrkr	546	546	0	1092	0	0	1	1	3	1	TA	5	Typ	0	NA	NA	NA	NA	0	0	NA	NA	Y	0	0	0	0	0	0	NA	NA	NA	0	6	2010	WD	Normal
1617	160	RM	21	1890	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	MeadowV	Norm	Norm	TwnhsE	2Story	4	6	1972	1972	Gable	CompShg	CemntBd	CmentBd	None	0	TA	TA	CBlock	TA	TA	No	Rec	294	Unf	0	252	546	GasA	TA	Y	SBrkr	546	546	0	1092	0	0	1	1	3	1	TA	5	Typ	0	NA	Attchd	1972	Unf	1	286	TA	TA	Y	0	0	64	0	0	0	NA	NA	NA	0	6	2010	WD	Normal
1618	20	RL	50	6953	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Mitchel	Norm	Norm	1Fam	1Story	5	7	1971	2004	Gable	CompShg	VinylSd	VinylSd	None	0	TA	Gd	CBlock	TA	TA	No	ALQ	469	Unf	0	395	864	GasA	Ex	Y	SBrkr	874	0	0	874	0	0	1	0	3	1	TA	5	Typ	0	NA	Detchd	1971	Unf	1	352	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	6	2010	ConLD	Normal
1619	20	RL	76	12887	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Mitchel	Norm	Norm	1Fam	1Story	5	7	1984	1984	Gable	CompShg	VinylSd	VinylSd	None	0	TA	TA	CBlock	Gd	TA	Mn	Rec	207	GLQ	590	36	833	GasA	TA	Y	SBrkr	833	0	0	833	1	0	1	0	2	1	Gd	5	Typ	0	NA	Attchd	1984	Unf	2	495	TA	TA	Y	431	0	0	0	0	0	NA	MnPrv	NA	0	4	2010	WD	Normal
1620	90	RL	70	7700	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Mitchel	Norm	Norm	Duplex	2Story	5	2	1985	1986	Gable	CompShg	HdBoard	HdBoard	None	0	TA	Po	PConc	TA	TA	No	Unf	0	Unf	0	1216	1216	GasA	Gd	Y	SBrkr	1216	1216	0	2432	0	0	4	2	4	2	TA	10	Typ	0	NA	Attchd	1985	Unf	2	616	TA	Fa	Y	200	0	0	0	0	0	NA	NA	Shed	600	2	2010	WD	Normal
1621	60	RL	63	10475	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Mitchel	Norm	Norm	1Fam	2Story	5	5	1991	1991	Gable	CompShg	HdBoard	HdBoard	None	0	TA	TA	PConc	Gd	TA	No	Rec	458	Unf	0	166	624	GasA	Gd	Y	SBrkr	624	650	0	1274	0	0	1	1	3	1	TA	6	Typ	0	NA	Detchd	1993	Unf	2	576	TA	TA	Y	22	0	0	0	0	0	NA	GdWo	NA	0	3	2010	WD	Normal
1622	50	RL	68	10544	Pave	NA	IR1	Lvl	AllPub	Inside	Mod	Mitchel	Norm	Norm	1Fam	1.5Fin	5	5	1969	1969	Gable	CompShg	HdBoard	HdBoard	None	0	TA	TA	CBlock	TA	TA	Av	BLQ	476	Unf	0	388	864	GasA	TA	Y	SBrkr	864	615	0	1479	0	0	2	0	5	1	TA	8	Typ	0	NA	Attchd	1969	Fin	1	275	TA	TA	Y	287	0	280	0	0	0	NA	NA	NA	0	4	2010	WD	Normal
1623	20	RL	76	9892	Pave	NA	Reg	Lvl	AllPub	Inside	Mod	Mitchel	Norm	Norm	1Fam	1Story	8	5	1994	1995	Hip	CompShg	VinylSd	VinylSd	None	0	Gd	Gd	PConc	Gd	Gd	Gd	GLQ	1341	LwQ	284	54	1679	GasA	Ex	Y	SBrkr	1803	0	0	1803	1	1	2	1	3	1	Gd	6	Typ	2	TA	Attchd	1994	Unf	2	482	TA	TA	Y	129	64	222	0	0	0	NA	GdWo	NA	0	2	2010	WD	Normal
1624	60	RL	74	12961	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Mitchel	Norm	Norm	1Fam	2Story	6	5	1993	1994	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	Gd	PConc	Gd	TA	Mn	GLQ	944	Unf	0	208	1152	GasA	Ex	Y	SBrkr	1152	645	0	1797	1	0	2	1	3	1	Gd	7	Typ	1	Fa	Attchd	1993	Fin	2	616	TA	TA	Y	162	312	0	0	0	0	NA	NA	NA	0	3	2010	WD	Normal
1625	20	RL	74	13008	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	NAmes	Norm	Norm	1Fam	1Story	6	5	1956	1956	Gable	CompShg	MetalSd	MetalSd	None	0	TA	TA	CBlock	Fa	Fa	No	Rec	564	Unf	0	318	882	GasA	TA	Y	SBrkr	882	0	0	882	0	0	1	0	2	1	TA	5	Typ	0	NA	Attchd	1956	Unf	1	502	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	10	2009	WD	Normal
1626	20	RL	85	10200	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NAmes	Norm	Norm	1Fam	1Story	6	5	1974	1974	Hip	CompShg	Plywood	Plywood	BrkFace	440	TA	TA	CBlock	TA	TA	No	LwQ	844	Unf	0	590	1434	GasA	TA	Y	SBrkr	1434	0	0	1434	1	0	2	0	4	1	TA	7	Typ	1	Gd	Attchd	1974	RFn	2	528	TA	TA	Y	80	21	0	0	0	0	NA	NA	NA	0	6	2009	WD	Normal
1627	60	RL	88	10179	Pave	NA	IR1	Lvl	AllPub	Corner	Gtl	Gilbert	Norm	Norm	1Fam	2Story	6	5	1997	1997	Gable	CompShg	VinylSd	VinylSd	None	0	TA	TA	PConc	Gd	TA	No	ALQ	847	Unf	0	98	945	GasA	Ex	Y	SBrkr	945	663	0	1608	0	0	2	1	3	1	TA	7	Typ	1	TA	Attchd	1997	Fin	2	470	TA	TA	Y	252	30	0	0	0	0	NA	NA	NA	0	7	2009	WD	Normal
1628	60	RL	NA	11792	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Gilbert	Norm	Norm	1Fam	2Story	8	5	2003	2003	Gable	CompShg	VinylSd	VinylSd	BrkFace	188	Gd	TA	PConc	Gd	TA	Gd	GLQ	850	Unf	0	158	1008	GasA	Ex	Y	SBrkr	1008	1275	0	2283	0	0	2	1	4	1	Gd	9	Typ	1	Gd	BuiltIn	2003	Fin	3	632	TA	TA	Y	120	46	0	0	0	0	NA	NA	NA	0	8	2009	WD	Normal
1629	80	RL	60	8400	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Gilbert	Norm	Norm	1Fam	SLvl	7	5	1996	1997	Gable	CompShg	HdBoard	HdBoard	BrkFace	32	TA	TA	PConc	Gd	TA	No	GLQ	284	Unf	0	100	384	GasA	Gd	Y	SBrkr	958	670	0	1628	0	0	2	1	3	1	TA	7	Typ	1	TA	BuiltIn	1996	Fin	2	390	TA	TA	Y	48	72	0	0	0	0	NA	NA	Shed	490	6	2009	WD	Normal
1630	120	RL	28	7296	Pave	NA	IR1	Lvl	AllPub	CulDSac	Gtl	StoneBr	Norm	Norm	TwnhsE	1Story	8	5	2004	2005	Gable	CompShg	CemntBd	CmentBd	None	0	Gd	TA	PConc	Ex	TA	Av	GLQ	1965	Unf	0	243	2208	GasA	Ex	Y	SBrkr	2522	0	0	2522	1	0	2	0	1	1	Gd	8	Typ	1	Gd	Attchd	2004	Fin	2	564	TA	TA	Y	182	57	0	0	0	0	NA	NA	NA	0	11	2009	WD	Normal
1631	120	RL	61	7380	Pave	NA	IR1	Lvl	AllPub	Corner	Gtl	StoneBr	Norm	Norm	1Fam	1Story	8	5	1998	1998	Gable	CompShg	CemntBd	CmentBd	None	0	TA	TA	PConc	Gd	TA	Av	GLQ	341	Unf	0	1077	1418	GasA	Ex	Y	SBrkr	1478	0	0	1478	1	0	2	0	2	1	TA	5	Typ	0	NA	Attchd	1998	Fin	2	495	TA	TA	Y	168	43	0	0	0	0	NA	NA	NA	0	7	2009	WD	Normal
1632	120	RL	57	8013	Pave	NA	IR1	Lvl	AllPub	Corner	Gtl	StoneBr	Norm	Norm	TwnhsE	1Story	8	5	1995	1996	Gable	CompShg	CemntBd	CmentBd	None	0	Gd	TA	PConc	Gd	TA	No	GLQ	741	Unf	0	846	1587	GasA	Ex	Y	SBrkr	1734	0	0	1734	1	0	2	0	2	1	Gd	6	Typ	0	NA	Attchd	1995	RFn	2	528	TA	TA	Y	52	50	0	0	0	0	NA	NA	NA	0	9	2009	WD	Normal
1633	80	RL	57	8923	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Gilbert	Norm	Norm	1Fam	SLvl	7	5	1998	1998	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	TA	No	GLQ	189	Unf	0	195	384	GasA	Gd	Y	SBrkr	751	631	0	1382	0	0	2	1	3	1	TA	7	Typ	1	TA	BuiltIn	1998	Fin	2	396	TA	TA	Y	256	0	0	0	0	0	NA	NA	NA	0	2	2009	WD	Normal
1634	60	RL	60	7500	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Gilbert	Norm	Norm	1Fam	2Story	6	5	1998	1999	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	TA	No	GLQ	476	Unf	0	476	952	GasA	Gd	Y	SBrkr	952	684	0	1636	1	0	2	1	3	1	TA	7	Typ	1	TA	Attchd	1998	Fin	2	440	TA	TA	Y	0	84	0	0	0	0	NA	NA	NA	0	10	2009	WD	Normal
1635	60	RL	NA	8803	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Gilbert	Norm	Norm	1Fam	2Story	6	5	1994	1995	Gable	CompShg	HdBoard	HdBoard	None	0	TA	TA	PConc	Gd	TA	No	GLQ	600	Unf	0	107	707	GasA	Gd	Y	SBrkr	707	809	0	1516	1	0	2	1	3	1	Gd	7	Typ	1	TA	Attchd	1994	Fin	2	409	TA	TA	Y	0	46	0	0	0	0	NA	NA	NA	0	7	2009	WD	Normal
1636	20	RL	58	7250	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Gilbert	Norm	Norm	1Fam	1Story	6	5	1993	1993	Gable	CompShg	HdBoard	HdBoard	BrkFace	45	TA	TA	PConc	Gd	TA	No	Unf	0	Unf	0	1181	1181	GasA	Ex	Y	SBrkr	1190	0	0	1190	0	0	2	0	3	1	Gd	6	Typ	1	TA	Attchd	1993	Unf	2	430	TA	TA	Y	0	21	0	0	0	0	NA	NA	NA	0	11	2009	WD	Normal
1637	60	RL	85	11900	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Gilbert	Norm	Norm	1Fam	2Story	5	6	1977	1977	Gable	CompShg	HdBoard	Wd Sdng	BrkFace	157	TA	TA	PConc	Gd	TA	No	ALQ	400	Unf	0	722	1122	GasA	Ex	Y	SBrkr	946	988	0	1934	1	0	2	1	3	1	TA	6	Typ	1	TA	Attchd	1977	Unf	2	567	TA	TA	P	0	176	0	0	200	0	NA	NA	NA	0	7	2009	WD	Normal
1638	60	RL	NA	13250	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	NWAmes	RRNn	Norm	1Fam	2Story	7	6	1978	1978	Gable	CompShg	HdBoard	HdBoard	BrkFace	256	TA	TA	CBlock	Gd	TA	No	Unf	0	Unf	0	832	832	GasA	TA	Y	SBrkr	1154	896	0	2050	0	0	2	1	4	1	Gd	8	Typ	1	TA	Attchd	1978	RFn	2	529	TA	TA	Y	192	192	0	0	0	0	NA	NA	NA	0	5	2009	WD	Abnorml
1639	20	RL	80	10928	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NWAmes	Norm	Norm	1Fam	1Story	6	6	1978	1986	Gable	CompShg	VinylSd	VinylSd	BrkFace	101	TA	TA	PConc	TA	TA	No	LwQ	363	Unf	0	1064	1427	GasA	TA	Y	SBrkr	1671	0	0	1671	0	0	2	0	3	1	TA	7	Typ	1	TA	Attchd	1978	RFn	2	484	TA	TA	Y	252	55	0	0	0	0	NA	NA	NA	0	8	2009	WD	Normal
1640	60	RL	NA	12388	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	NWAmes	Norm	Norm	1Fam	2Story	7	7	1980	1991	Gable	CompShg	Plywood	Plywood	BrkFace	229	TA	TA	CBlock	Gd	TA	No	ALQ	602	Unf	0	441	1043	GasA	TA	Y	SBrkr	1539	1134	0	2673	0	0	2	1	4	1	Gd	9	Typ	1	TA	BuiltIn	1980	RFn	2	441	TA	TA	Y	178	84	0	0	0	0	NA	NA	NA	0	8	2009	WD	Normal
1641	20	RL	80	11088	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NWAmes	Norm	Norm	1Fam	1Story	6	5	1978	1998	Gable	CompShg	HdBoard	HdBoard	BrkFace	144	TA	TA	PConc	TA	TA	No	ALQ	832	Unf	0	308	1140	GasA	Gd	Y	SBrkr	1707	0	0	1707	0	0	2	0	3	1	TA	7	Typ	1	TA	Attchd	1978	Fin	2	479	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	5	2009	WD	Normal
1642	60	FV	70	7000	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Somerst	Norm	Norm	1Fam	2Story	7	5	2003	2003	Gable	CompShg	CemntBd	CmentBd	None	0	Gd	TA	PConc	Gd	TA	Mn	GLQ	622	Unf	0	304	926	GasA	Ex	Y	SBrkr	1016	868	0	1884	1	0	2	1	3	1	Ex	7	Typ	1	Ex	Attchd	2003	RFn	2	581	TA	TA	Y	0	35	0	0	0	0	NA	NA	NA	0	6	2009	WD	Normal
1643	60	FV	NA	7500	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Somerst	RRNn	Norm	1Fam	2Story	8	5	2000	2001	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	TA	No	Unf	0	Unf	0	1058	1058	GasA	Ex	Y	SBrkr	1058	816	0	1874	0	0	2	1	3	1	Gd	7	Typ	1	TA	Attchd	2000	Fin	2	588	TA	TA	Y	0	134	0	0	0	0	NA	NA	NA	0	3	2009	WD	Normal
1644	60	FV	NA	8470	Pave	NA	Reg	Lvl	AllPub	Corner	Gtl	Somerst	Norm	Norm	1Fam	2Story	8	5	2002	2002	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	TA	No	GLQ	225	ALQ	276	471	972	GasA	Ex	Y	SBrkr	972	839	0	1811	0	0	2	1	3	1	Gd	7	Typ	1	Gd	Attchd	2002	RFn	2	565	TA	TA	Y	225	48	0	0	0	0	NA	NA	NA	0	10	2009	WD	Normal
1645	20	RL	NA	9373	Pave	NA	IR1	Lvl	AllPub	CulDSac	Gtl	NWAmes	PosN	Norm	1Fam	1Story	5	7	1975	1975	Gable	CompShg	HdBoard	HdBoard	BrkFace	161	TA	TA	CBlock	Gd	TA	Av	ALQ	1333	LwQ	168	120	1621	GasA	TA	Y	SBrkr	1621	0	0	1621	1	0	2	0	3	1	TA	7	Typ	2	Fa	Attchd	1975	RFn	2	478	TA	TA	Y	0	0	0	0	490	0	NA	NA	NA	0	6	2009	WD	Normal
1646	20	RL	78	10140	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NWAmes	Norm	Norm	1Fam	1Story	6	6	1974	1974	Hip	CompShg	Plywood	Plywood	BrkFace	196	TA	TA	CBlock	TA	TA	No	ALQ	888	Unf	0	228	1116	GasA	Ex	Y	SBrkr	1116	0	0	1116	1	0	2	0	3	1	TA	6	Typ	1	TA	Attchd	1974	RFn	2	528	TA	TA	Y	0	0	0	0	0	0	NA	GdWo	NA	0	4	2009	WD	Normal
1647	20	RL	85	11050	Pave	NA	IR1	Lvl	AllPub	Corner	Gtl	NWAmes	Norm	Norm	1Fam	1Story	7	5	1975	1975	Gable	CompShg	Plywood	Plywood	None	0	TA	TA	CBlock	TA	TA	No	ALQ	636	Unf	0	540	1176	GasA	Fa	Y	SBrkr	1193	0	0	1193	0	0	2	0	3	1	TA	5	Typ	1	TA	Attchd	1975	Unf	2	506	TA	TA	Y	40	0	0	0	0	0	NA	NA	NA	0	8	2009	WD	Normal
1648	20	RL	NA	7830	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	NAmes	Norm	Norm	1Fam	1Story	5	5	1970	1970	Gable	CompShg	HdBoard	HdBoard	None	0	TA	TA	CBlock	TA	TA	No	Unf	0	Unf	0	1180	1180	GasA	TA	Y	SBrkr	1180	0	0	1180	0	0	1	1	2	1	TA	6	Typ	0	NA	Attchd	1970	RFn	2	477	TA	TA	Y	0	45	0	0	0	0	NA	NA	NA	0	3	2009	COD	Normal
1649	20	RL	NA	8510	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	NAmes	Norm	Norm	1Fam	1Story	5	7	1971	1971	Gable	CompShg	Plywood	Plywood	BrkFace	178	TA	TA	CBlock	Gd	TA	No	ALQ	500	Unf	0	543	1043	GasA	Ex	Y	SBrkr	1050	0	0	1050	1	0	1	1	3	1	TA	6	Typ	0	NA	Attchd	1971	Unf	1	336	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	7	2009	WD	Normal
1650	20	RL	60	7038	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NAmes	Norm	Norm	1Fam	1Story	4	6	1970	1970	Gable	CompShg	VinylSd	VinylSd	None	0	TA	TA	CBlock	TA	TA	No	ALQ	726	Unf	0	138	864	GasA	TA	Y	SBrkr	864	0	0	864	1	0	1	0	3	1	TA	5	Typ	0	NA	Detchd	2001	Unf	2	576	TA	TA	Y	210	0	0	0	0	0	NA	GdPrv	NA	0	9	2009	WD	Abnorml
1651	20	RL	60	9000	Pave	NA	Reg	Lvl	AllPub	FR2	Gtl	NAmes	Norm	Norm	1Fam	1Story	4	7	1971	2006	Gable	CompShg	VinylSd	VinylSd	None	0	TA	Gd	CBlock	TA	TA	No	ALQ	240	Unf	0	624	864	GasA	Gd	Y	SBrkr	864	0	0	864	0	0	1	0	3	1	TA	5	Typ	0	NA	Detchd	1986	Unf	2	576	TA	TA	Y	200	0	0	0	0	0	NA	GdWo	NA	0	7	2009	WD	Normal
1652	160	RM	21	1680	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	BrDale	Norm	Norm	Twnhs	2Story	6	5	1973	1973	Gable	CompShg	HdBoard	HdBoard	BrkFace	504	TA	TA	CBlock	TA	TA	No	BLQ	254	Unf	0	229	483	GasA	TA	Y	SBrkr	483	504	0	987	1	0	1	1	2	1	TA	5	Typ	0	NA	Detchd	1973	Unf	1	264	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	7	2009	WD	Normal
1653	160	RM	21	1680	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	BrDale	Norm	Norm	Twnhs	2Story	6	6	1972	1972	Gable	CompShg	HdBoard	HdBoard	BrkFace	425	TA	TA	CBlock	TA	TA	No	Rec	110	LwQ	294	79	483	GasA	TA	Y	SBrkr	483	504	0	987	1	0	1	1	2	1	TA	5	Typ	0	NA	Detchd	1972	Unf	1	288	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	7	2009	WD	Normal
1654	160	RL	24	2308	Pave	NA	Reg	Lvl	AllPub	FR2	Gtl	NPkVill	Norm	Norm	TwnhsE	2Story	6	5	1976	1976	Gable	CompShg	Plywood	Brk Cmn	None	0	TA	TA	CBlock	Gd	TA	No	ALQ	306	Unf	0	498	804	GasA	TA	Y	SBrkr	804	744	0	1548	0	0	2	1	3	1	TA	7	Typ	1	TA	Detchd	1976	RFn	2	440	TA	TA	Y	108	0	0	0	0	0	NA	NA	NA	0	9	2009	WD	Normal
1655	120	RL	24	2280	Pave	NA	Reg	Lvl	AllPub	FR2	Gtl	NPkVill	Norm	Norm	Twnhs	1Story	7	5	1975	1975	Gable	CompShg	Plywood	Brk Cmn	None	0	TA	TA	CBlock	Gd	TA	No	ALQ	435	LwQ	622	0	1057	GasA	TA	Y	SBrkr	1055	0	0	1055	0	1	2	0	2	1	TA	4	Typ	1	Fa	Attchd	1975	RFn	2	440	TA	TA	Y	0	27	0	0	0	0	NA	NA	NA	0	8	2009	WD	Normal
1656	160	RL	24	2349	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NPkVill	Norm	Norm	Twnhs	2Story	6	5	1977	1977	Gable	CompShg	Plywood	Brk Cmn	None	0	TA	TA	CBlock	Gd	TA	No	ALQ	389	Unf	0	466	855	GasA	TA	Y	SBrkr	855	601	0	1456	0	0	2	1	3	1	TA	6	Typ	1	TA	Attchd	1977	Unf	2	440	TA	TA	Y	0	28	0	0	0	0	NA	NA	NA	0	5	2009	WD	Normal
1657	160	RL	24	2364	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NPkVill	Norm	Norm	TwnhsE	2Story	6	5	1978	1978	Gable	CompShg	Plywood	Brk Cmn	None	0	TA	TA	CBlock	Gd	TA	No	ALQ	320	Unf	0	484	804	GasA	TA	Y	SBrkr	804	744	0	1548	0	1	2	1	3	1	TA	7	Typ	1	TA	Detchd	1978	Unf	2	440	TA	TA	Y	108	0	0	0	0	0	NA	NA	NA	0	7	2009	WD	Normal
1658	160	RL	24	2364	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NPkVill	Norm	Norm	TwnhsE	2Story	6	5	1978	1978	Gable	CompShg	Plywood	Brk Cmn	None	0	Gd	TA	CBlock	Gd	TA	No	ALQ	279	Unf	0	576	855	GasA	TA	Y	SBrkr	855	601	0	1456	0	0	2	1	3	1	TA	6	Typ	1	TA	Attchd	1978	Fin	2	440	TA	TA	Y	147	0	0	0	0	0	NA	NA	NA	0	4	2009	WD	Normal
1659	120	RL	24	2104	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NPkVill	Norm	Norm	TwnhsE	1Story	7	6	1976	1976	Gable	CompShg	Plywood	Brk Cmn	None	0	TA	TA	CBlock	TA	TA	No	ALQ	536	Unf	0	300	836	GasA	TA	Y	SBrkr	836	0	0	836	0	1	1	0	2	1	TA	5	Typ	0	NA	Attchd	1976	Unf	1	345	TA	TA	Y	150	20	0	0	0	0	NA	NA	NA	0	10	2009	WD	Normal
1660	20	RL	NA	10710	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NAmes	Norm	Norm	1Fam	1Story	5	7	1966	2004	Hip	CompShg	HdBoard	HdBoard	BrkFace	165	Gd	TA	PConc	TA	TA	No	BLQ	644	Unf	0	220	864	GasA	Ex	Y	SBrkr	1120	0	0	1120	0	1	1	0	3	1	TA	5	Typ	1	TA	Attchd	1966	RFn	2	656	TA	TA	Y	0	162	0	0	0	0	NA	NA	Shed	1200	7	2009	WD	Normal
1661	60	RL	110	14257	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NridgHt	PosN	Norm	1Fam	2Story	9	5	2007	2007	Hip	CompShg	VinylSd	VinylSd	Stone	726	Ex	TA	PConc	Ex	TA	No	GLQ	1360	Unf	0	416	1776	GasA	Ex	Y	SBrkr	1794	978	0	2772	1	0	3	1	4	1	Ex	10	Typ	3	Gd	BuiltIn	2007	Fin	3	754	TA	TA	Y	135	64	0	0	0	0	NA	NA	NA	0	6	2009	WD	Normal
1662	60	RL	95	12350	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NridgHt	Norm	Norm	1Fam	2Story	9	5	2009	2009	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Ex	TA	No	GLQ	986	Unf	0	379	1365	GasA	Ex	Y	SBrkr	1365	1325	0	2690	1	0	2	1	3	1	Ex	8	Typ	1	Gd	Attchd	2009	RFn	3	864	TA	TA	Y	0	197	0	0	0	0	NA	NA	NA	0	7	2009	New	Partial
1663	20	RL	95	12350	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NridgHt	Norm	Norm	1Fam	1Story	9	5	2008	2008	Hip	CompShg	VinylSd	VinylSd	Stone	450	Ex	TA	PConc	Ex	TA	Av	GLQ	1232	Unf	0	788	2020	GasA	Ex	Y	SBrkr	2020	0	0	2020	1	0	2	0	3	1	Ex	7	Typ	1	Gd	Attchd	2008	RFn	3	896	TA	TA	Y	192	98	0	0	0	0	NA	NA	NA	0	5	2009	WD	Normal
1664	20	RL	105	13693	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NridgHt	PosA	PosA	1Fam	1Story	10	5	2007	2007	Hip	CompShg	VinylSd	VinylSd	Stone	472	Ex	TA	PConc	Ex	TA	Gd	GLQ	2288	Unf	0	342	2630	GasA	Ex	Y	SBrkr	2674	0	0	2674	2	0	2	1	2	1	Ex	8	Typ	2	Gd	Attchd	2007	Fin	3	762	TA	TA	Y	360	50	0	0	0	0	NA	NA	NA	0	3	2009	WD	Normal
1665	20	RL	95	11578	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NridgHt	Norm	Norm	1Fam	1Story	9	5	2008	2008	Gable	CompShg	VinylSd	VinylSd	Stone	302	Ex	TA	PConc	Ex	TA	No	Unf	0	Unf	0	1736	1736	GasA	Ex	Y	SBrkr	1736	0	0	1736	0	0	2	0	3	1	Ex	7	Typ	1	Gd	Attchd	2008	RFn	3	834	TA	TA	Y	319	90	0	0	0	0	NA	NA	NA	0	7	2009	WD	Normal
1666	20	RL	129	16870	Pave	NA	IR1	Lvl	AllPub	FR3	Gtl	NridgHt	Norm	Norm	1Fam	1Story	8	5	2004	2005	Hip	CompShg	VinylSd	VinylSd	BrkFace	238	Gd	TA	PConc	Ex	TA	Gd	GLQ	1531	Unf	0	251	1782	GasA	Ex	Y	SBrkr	1782	0	0	1782	1	0	2	0	3	1	Gd	7	Typ	2	Gd	Attchd	2004	Fin	3	932	TA	TA	Y	99	82	0	0	0	0	NA	NA	NA	0	4	2009	WD	Normal
1667	60	RL	59	23303	Pave	NA	IR3	Lvl	AllPub	CulDSac	Gtl	NridgHt	Norm	Norm	1Fam	2Story	8	5	2007	2007	Gable	CompShg	VinylSd	VinylSd	Stone	20	Gd	TA	PConc	Ex	TA	Av	GLQ	1230	Unf	0	278	1508	GasA	Ex	Y	SBrkr	1508	1012	0	2520	1	0	2	1	5	1	Ex	10	Typ	1	Gd	BuiltIn	2007	Fin	3	640	TA	TA	Y	192	273	0	0	0	0	NA	NA	NA	0	6	2009	WD	Family
1668	20	RL	87	10367	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	NridgHt	Norm	Norm	1Fam	1Story	9	5	2008	2008	Hip	CompShg	VinylSd	VinylSd	Stone	284	Ex	TA	PConc	Ex	TA	Mn	GLQ	1015	Unf	0	724	1739	GasA	Ex	Y	SBrkr	1743	0	0	1743	1	0	2	0	3	1	Ex	8	Typ	1	Gd	Attchd	2008	RFn	3	927	TA	TA	Y	168	45	0	0	0	0	NA	NA	NA	0	6	2009	ConLI	Normal
1669	20	RL	77	10872	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	NridgHt	Norm	Norm	1Fam	1Story	9	5	2006	2006	Gable	CompShg	VinylSd	VinylSd	Stone	122	Gd	TA	PConc	Ex	Gd	Av	GLQ	1037	Unf	0	467	1504	GasA	Ex	Y	SBrkr	1531	0	0	1531	1	0	2	0	2	1	Ex	6	Typ	1	Gd	Attchd	2006	Fin	3	700	TA	TA	Y	184	52	0	0	0	0	NA	NA	NA	0	2	2009	WD	Normal
1670	20	RL	102	13514	Pave	NA	IR1	Lvl	AllPub	Corner	Gtl	NridgHt	Norm	Norm	1Fam	1Story	9	5	2008	2008	Hip	CompShg	VinylSd	VinylSd	None	285	Ex	TA	PConc	Ex	TA	No	GLQ	1142	Unf	0	632	1774	GasA	Ex	Y	SBrkr	1808	0	0	1808	1	0	2	0	3	1	Ex	7	Typ	1	Gd	Attchd	2008	Fin	3	850	TA	TA	Y	200	26	0	0	0	0	NA	NA	NA	0	3	2009	WD	Normal
1671	20	RL	90	12878	Pave	NA	IR1	Lvl	AllPub	Corner	Gtl	NridgHt	Norm	Norm	1Fam	1Story	7	5	2003	2004	Hip	CompShg	VinylSd	VinylSd	BrkFace	418	Gd	TA	PConc	Gd	TA	No	ALQ	1262	Unf	0	498	1760	GasA	Ex	Y	SBrkr	1760	0	0	1760	1	0	2	0	3	1	Gd	8	Typ	1	Gd	Attchd	2003	Fin	2	583	TA	TA	Y	165	190	0	0	0	0	NA	NA	NA	0	6	2009	WD	Normal
1672	20	RL	110	15274	Pave	NA	IR1	Lvl	AllPub	Corner	Gtl	NridgHt	Norm	Norm	1Fam	1Story	9	5	2003	2003	Hip	CompShg	VinylSd	VinylSd	BrkFace	724	Gd	TA	PConc	Ex	TA	No	GLQ	1972	Unf	0	480	2452	GasA	Ex	Y	SBrkr	2452	0	0	2452	2	0	2	0	3	1	Ex	10	Typ	1	Gd	Attchd	2003	Fin	3	886	TA	TA	Y	0	116	0	0	0	0	NA	MnPrv	NA	0	7	2009	WD	Normal
1673	60	RL	96	13262	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	NridgHt	Norm	Norm	1Fam	2Story	8	5	2003	2004	Gable	CompShg	VinylSd	VinylSd	Stone	186	Gd	TA	PConc	Gd	TA	No	Unf	0	Unf	0	1082	1082	GasA	Ex	Y	SBrkr	1105	1295	0	2400	0	0	3	1	4	1	Gd	10	Typ	1	Gd	BuiltIn	2003	Fin	3	730	TA	TA	Y	114	40	0	0	0	0	NA	NA	NA	0	6	2009	WD	Normal
1674	20	RL	70	9658	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	NridgHt	Norm	Norm	1Fam	1Story	8	5	2006	2006	Gable	CompShg	VinylSd	VinylSd	Stone	383	Gd	TA	PConc	Gd	TA	No	Unf	0	Unf	0	1598	1598	GasA	Gd	Y	SBrkr	1606	0	0	1606	0	0	2	0	3	1	Gd	6	Typ	1	Gd	Attchd	2006	RFn	3	871	TA	TA	Y	230	60	0	0	0	0	NA	NA	NA	0	7	2009	WD	Normal
1675	120	RL	47	6904	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	NridgHt	Norm	Norm	TwnhsE	1Story	6	5	2005	2005	Gable	CompShg	VinylSd	VinylSd	Stone	240	Gd	TA	PConc	Gd	TA	Av	ALQ	836	Unf	0	522	1358	GasA	Ex	Y	SBrkr	1358	0	0	1358	0	0	2	0	2	1	Gd	6	Typ	1	Gd	Attchd	2005	RFn	2	484	TA	TA	Y	192	36	0	0	0	0	NA	NA	NA	0	8	2009	WD	Normal
1676	120	RL	34	5122	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	NridgHt	Norm	Norm	Twnhs	1Story	6	5	2005	2005	Gable	CompShg	VinylSd	VinylSd	Stone	135	Gd	TA	PConc	Gd	TA	Av	GLQ	881	Unf	0	425	1306	GasA	Ex	Y	SBrkr	1306	0	0	1306	1	0	2	0	1	1	Gd	5	Typ	1	Gd	Attchd	2005	RFn	2	624	TA	TA	Y	170	63	0	0	0	0	NA	NA	NA	0	3	2009	WD	Normal
1677	120	RL	80	10307	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	NridgHt	Norm	Norm	TwnhsE	1Story	7	5	2007	2008	Gable	CompShg	VinylSd	VinylSd	Stone	176	Gd	TA	PConc	Gd	TA	No	GLQ	876	Unf	0	474	1350	GasA	Ex	Y	SBrkr	1358	0	0	1358	1	0	2	0	2	1	Gd	6	Typ	1	Gd	Attchd	2008	RFn	2	484	TA	TA	Y	192	26	0	0	0	0	NA	NA	NA	0	5	2009	WD	Normal
1678	20	RL	100	14836	Pave	NA	IR1	HLS	AllPub	Inside	Mod	NridgHt	Norm	Norm	1Fam	1Story	10	5	2004	2005	Hip	CompShg	CemntBd	CmentBd	Stone	730	Ex	TA	PConc	Ex	TA	Gd	GLQ	2146	Unf	0	346	2492	GasA	Ex	Y	SBrkr	2492	0	0	2492	1	0	2	1	2	1	Ex	8	Typ	1	Ex	Attchd	2004	Fin	3	949	TA	TA	Y	226	235	0	0	0	0	NA	NA	NA	0	2	2009	WD	Abnorml
1679	20	RL	117	15262	Pave	NA	IR1	Lvl	AllPub	Corner	Gtl	NridgHt	Norm	Norm	1Fam	1Story	8	5	2003	2004	Hip	CompShg	VinylSd	VinylSd	BrkFace	470	Gd	TA	PConc	Ex	TA	Gd	GLQ	1557	Unf	0	643	2200	GasA	Ex	Y	SBrkr	2200	0	0	2200	1	0	2	1	3	1	Ex	8	Typ	1	Gd	Attchd	2003	Fin	3	685	TA	TA	Y	208	55	0	0	0	0	NA	NA	NA	0	7	2009	WD	Normal
1680	120	RL	44	7390	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	NridgHt	Norm	Norm	TwnhsE	1Story	9	5	2008	2009	Hip	CompShg	MetalSd	MetalSd	BrkFace	308	Ex	TA	PConc	Ex	TA	No	GLQ	800	Unf	0	1084	1884	GasA	Ex	Y	SBrkr	1884	0	0	1884	1	0	2	0	2	1	Ex	6	Typ	1	Gd	Attchd	2008	Fin	2	649	TA	TA	Y	231	90	0	0	0	0	NA	NA	NA	0	5	2009	New	Partial
1681	120	RL	48	6472	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NridgHt	Norm	Norm	TwnhsE	1Story	9	5	2008	2008	Hip	CompShg	VinylSd	VinylSd	BrkFace	500	Ex	TA	PConc	Ex	TA	No	Unf	0	Unf	0	1451	1451	GasA	Ex	Y	SBrkr	1456	0	0	1456	0	0	2	0	2	1	Ex	6	Typ	1	Gd	Attchd	2008	RFn	2	539	TA	TA	Y	192	42	0	0	0	0	NA	NA	NA	0	4	2009	WD	Normal
1682	20	RL	129	16770	Pave	NA	Reg	Lvl	AllPub	Corner	Gtl	NridgHt	Norm	Norm	1Fam	1Story	8	5	2002	2003	Hip	CompShg	VinylSd	VinylSd	BrkFace	270	Gd	TA	PConc	Ex	TA	Gd	GLQ	1196	Unf	0	516	1712	GasA	Ex	Y	SBrkr	1712	0	0	1712	1	0	2	0	3	1	Gd	8	Typ	1	Gd	Attchd	2002	RFn	3	701	TA	TA	Y	218	183	0	0	0	0	NA	NA	NA	0	9	2009	WD	Normal
1683	120	RL	48	3480	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NridgHt	Norm	Norm	TwnhsE	1Story	7	5	2003	2003	Gable	CompShg	VinylSd	VinylSd	Stone	163	Gd	TA	PConc	Gd	TA	No	Unf	0	Unf	0	1405	1405	GasA	Ex	Y	SBrkr	1405	0	0	1405	0	0	2	0	2	1	Gd	6	Typ	1	TA	Attchd	2003	RFn	2	478	TA	TA	Y	148	36	0	0	0	0	NA	NA	NA	0	11	2009	WD	Normal
1684	60	RL	63	10928	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Gilbert	RRAn	Norm	1Fam	2Story	7	5	2005	2005	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	Gd	No	Unf	0	Unf	0	728	728	GasA	Ex	Y	SBrkr	728	728	0	1456	0	0	2	1	3	1	Gd	8	Typ	1	Gd	Attchd	2005	Fin	2	390	TA	TA	Y	100	0	0	0	0	0	NA	NA	NA	0	6	2009	WD	Normal
1685	60	RL	57	8918	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Gilbert	Norm	Norm	1Fam	2Story	6	5	2005	2006	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	TA	Av	Unf	0	Unf	0	745	745	GasA	Ex	Y	SBrkr	745	745	0	1490	0	0	2	1	3	1	Gd	7	Typ	1	Gd	Attchd	2005	Fin	2	392	TA	TA	Y	36	20	0	0	0	0	NA	NA	NA	0	7	2009	WD	Normal
1686	120	RL	43	3182	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Blmngtn	Norm	Norm	TwnhsE	1Story	7	5	2005	2006	Gable	CompShg	VinylSd	VinylSd	BrkFace	16	Gd	TA	PConc	Gd	TA	Av	GLQ	16	Unf	0	1204	1220	GasA	Ex	Y	SBrkr	1220	0	0	1220	0	0	2	0	2	1	Gd	5	Typ	1	Gd	Attchd	2005	Fin	2	397	TA	TA	Y	100	16	0	0	0	0	NA	NA	NA	0	8	2009	WD	Normal
1687	80	RL	59	9434	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Gilbert	Norm	Norm	1Fam	SLvl	7	5	2004	2005	Gable	CompShg	WdShing	Wd Shng	None	0	Gd	TA	PConc	Gd	TA	Mn	Unf	0	Unf	0	384	384	GasA	Ex	Y	SBrkr	744	630	0	1374	0	0	2	1	3	1	Gd	6	Typ	1	Gd	BuiltIn	2004	Fin	2	400	TA	TA	Y	100	0	0	0	0	0	NA	NA	NA	0	8	2009	WD	Normal
1688	60	RL	62	7984	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Gilbert	Norm	Norm	1Fam	2Story	7	5	2004	2005	Gable	CompShg	VinylSd	VinylSd	BrkFace	200	Gd	TA	PConc	Gd	TA	No	Unf	0	Unf	0	868	868	GasA	Ex	Y	SBrkr	868	762	0	1630	0	0	2	1	3	1	Gd	7	Typ	1	Gd	BuiltIn	2004	Fin	2	436	TA	TA	Y	120	48	0	0	0	0	NA	NA	NA	0	9	2009	WD	Normal
1689	60	RL	61	10125	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Gilbert	Norm	Norm	1Fam	2Story	7	5	2004	2004	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	TA	Mn	Unf	0	Unf	0	846	846	GasA	Ex	Y	SBrkr	846	748	0	1594	0	0	2	1	3	1	Gd	7	Typ	1	Gd	Attchd	2004	Fin	2	434	TA	TA	Y	300	48	0	0	0	0	NA	MnPrv	NA	0	7	2009	WD	Normal
1690	60	RL	NA	8965	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Gilbert	Norm	Norm	1Fam	2Story	7	5	2003	2003	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	TA	No	GLQ	652	Unf	0	130	782	GasA	Ex	Y	SBrkr	806	683	0	1489	1	0	2	1	3	1	Gd	8	Typ	1	Gd	Attchd	2003	Fin	2	400	TA	TA	Y	0	75	0	0	0	0	NA	NA	NA	0	6	2009	WD	Normal
1691	60	RL	NA	8174	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Gilbert	Norm	Norm	1Fam	2Story	7	5	2003	2003	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	TA	No	GLQ	494	Unf	0	204	698	GasA	Ex	Y	SBrkr	698	644	0	1342	1	0	2	1	3	1	Gd	7	Typ	1	TA	Attchd	2003	Fin	2	393	TA	TA	Y	100	56	0	0	0	0	NA	NA	NA	0	5	2009	WD	Normal
1692	60	RL	NA	12891	Pave	NA	IR1	Lvl	AllPub	Corner	Gtl	Gilbert	Norm	Norm	1Fam	2Story	8	5	2002	2002	Gable	CompShg	VinylSd	VinylSd	NA	NA	Gd	TA	PConc	Ex	TA	No	GLQ	651	Unf	0	219	870	GasA	Ex	Y	SBrkr	878	1126	0	2004	1	0	2	1	4	1	Gd	8	Typ	1	Gd	BuiltIn	2002	Fin	3	644	TA	TA	Y	0	48	0	0	0	0	NA	NA	NA	0	7	2009	WD	Normal
1693	80	RL	61	9734	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Gilbert	RRAn	Norm	1Fam	SLvl	7	5	2004	2004	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	TA	Mn	GLQ	241	Rec	113	30	384	GasA	Ex	Y	SBrkr	744	630	0	1374	0	0	2	1	3	1	Gd	7	Typ	0	NA	BuiltIn	2004	Fin	2	400	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	5	2009	WD	Normal
1694	60	RL	42	8433	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Gilbert	Norm	Norm	1Fam	2Story	6	5	2000	2000	Gable	CompShg	VinylSd	VinylSd	None	0	TA	TA	PConc	Gd	TA	No	GLQ	683	Unf	0	111	794	GasA	Ex	Y	SBrkr	819	695	0	1514	1	0	2	1	3	1	TA	7	Typ	1	TA	Attchd	2000	Fin	2	394	TA	TA	Y	0	72	0	0	0	0	NA	NA	NA	0	6	2009	WD	Normal
1695	80	RL	62	7750	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Gilbert	Norm	Norm	1Fam	SLvl	7	5	1999	2000	Gable	CompShg	VinylSd	VinylSd	None	0	TA	TA	PConc	Gd	TA	No	Unf	0	Unf	0	384	384	GasA	Ex	Y	SBrkr	774	656	0	1430	0	0	2	1	3	1	TA	7	Typ	1	TA	BuiltIn	1999	RFn	2	400	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	3	2009	WD	Normal
1696	60	RL	NA	15896	Pave	NA	IR2	Lvl	AllPub	CulDSac	Gtl	Gilbert	RRNn	Norm	1Fam	2Story	7	5	1999	1999	Gable	CompShg	VinylSd	VinylSd	BrkFace	210	Gd	TA	PConc	Gd	TA	No	ALQ	913	Unf	0	264	1177	GasA	Ex	Y	SBrkr	1223	1089	0	2312	1	0	2	1	4	1	Gd	8	Typ	1	TA	BuiltIn	1999	Fin	3	658	TA	TA	Y	298	0	0	0	0	0	NA	NA	NA	0	5	2009	WD	Normal
1697	80	RL	64	7848	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Gilbert	Norm	Norm	1Fam	SLvl	7	6	1999	1999	Gable	CompShg	VinylSd	VinylSd	None	0	TA	TA	PConc	TA	TA	No	Unf	0	Unf	0	384	384	GasA	Ex	Y	SBrkr	774	656	0	1430	0	0	2	1	3	1	TA	7	Typ	1	TA	BuiltIn	1999	Fin	2	410	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	6	2009	WD	Normal
1698	60	RL	106	12720	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NoRidge	Norm	Norm	1Fam	2Story	8	5	2000	2000	Gable	CompShg	VinylSd	VinylSd	BrkFace	150	Gd	TA	PConc	Gd	TA	Mn	GLQ	1173	Unf	0	282	1455	GasA	Ex	Y	SBrkr	1466	1221	0	2687	1	0	2	1	4	1	Gd	10	Typ	2	TA	BuiltIn	2000	RFn	3	810	TA	TA	Y	252	30	0	0	0	0	NA	NA	NA	0	9	2009	WD	Normal
1699	20	RL	NA	10750	Pave	NA	IR1	Lvl	AllPub	CulDSac	Gtl	NoRidge	Norm	Norm	1Fam	1Story	8	5	1994	1995	Hip	CompShg	Wd Sdng	Wd Sdng	BrkFace	634	Gd	TA	PConc	Gd	TA	Av	BLQ	236	GLQ	1526	262	2024	GasA	Ex	Y	SBrkr	2063	0	0	2063	1	0	2	0	3	1	Gd	7	Typ	2	Gd	Attchd	1994	Fin	3	815	TA	TA	Y	182	56	0	0	0	0	NA	NA	NA	0	6	2009	WD	Normal
1700	60	RL	79	9085	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NoRidge	Norm	Norm	1Fam	2Story	7	5	1995	1996	Gable	CompShg	VinylSd	VinylSd	BrkFace	286	Gd	TA	PConc	Gd	TA	No	GLQ	816	Unf	0	254	1070	GasA	Ex	Y	SBrkr	1094	967	0	2061	1	0	2	1	3	1	Gd	7	Typ	1	TA	Attchd	1995	Fin	2	647	TA	TA	Y	296	102	209	0	0	0	NA	NA	NA	0	11	2009	WD	Normal
1701	60	RL	NA	11692	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	NoRidge	Norm	Norm	1Fam	2Story	8	5	1993	1994	Gable	CompShg	HdBoard	HdBoard	BrkFace	372	Gd	TA	PConc	Gd	TA	No	GLQ	624	Unf	0	549	1173	GasA	Ex	Y	SBrkr	1215	1017	0	2232	1	0	2	1	3	1	Gd	8	Typ	1	TA	Attchd	1993	RFn	2	623	TA	TA	Y	173	165	0	0	0	0	NA	NA	NA	0	10	2009	WD	Normal
1702	20	RL	86	11194	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Somerst	PosN	Norm	1Fam	1Story	8	5	2008	2008	Gable	CompShg	VinylSd	VinylSd	Stone	240	Gd	TA	PConc	Gd	TA	Mn	Unf	0	Unf	0	1696	1696	GasA	Ex	Y	SBrkr	1696	0	0	1696	0	0	2	0	3	1	Gd	7	Typ	0	NA	Attchd	2008	RFn	3	972	TA	TA	Y	120	56	0	0	0	0	NA	NA	NA	0	9	2009	WD	Normal
1703	20	RL	78	10206	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Somerst	PosN	Norm	1Fam	1Story	8	5	2008	2008	Gable	CompShg	VinylSd	VinylSd	BrkFace	294	Gd	TA	PConc	Gd	TA	No	Unf	0	Unf	0	1614	1614	GasA	Ex	Y	SBrkr	1658	0	0	1658	0	0	2	1	3	1	Gd	7	Typ	1	Gd	Attchd	2008	Fin	3	726	TA	TA	Y	144	44	0	0	0	0	NA	NA	NA	0	9	2009	WD	Normal
1704	20	RL	85	10130	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Somerst	Norm	Norm	1Fam	1Story	8	5	2007	2007	Gable	CompShg	VinylSd	VinylSd	Stone	260	Gd	TA	PConc	Gd	TA	Av	GLQ	1294	Unf	0	408	1702	GasA	Ex	Y	SBrkr	1702	0	0	1702	1	0	2	0	3	1	Gd	7	Typ	1	Gd	Attchd	2007	RFn	3	844	TA	TA	Y	0	69	0	0	0	0	NA	NA	NA	0	3	2009	WD	Normal
1705	20	RL	76	9139	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Somerst	Norm	Norm	1Fam	1Story	8	5	2006	2006	Hip	CompShg	VinylSd	VinylSd	Stone	206	Gd	TA	PConc	Ex	TA	Av	GLQ	379	Unf	0	1043	1422	GasA	Ex	Y	SBrkr	1432	0	0	1432	0	0	2	0	3	1	Gd	7	Typ	1	Gd	Attchd	2006	Fin	2	492	TA	TA	Y	297	50	0	0	0	0	NA	NA	NA	0	9	2009	WD	Normal
1706	20	RL	85	11128	Pave	NA	Reg	Lvl	AllPub	Corner	Gtl	Somerst	PosN	PosN	1Fam	1Story	9	5	2005	2006	Hip	CompShg	VinylSd	VinylSd	Stone	198	Ex	TA	PConc	Ex	TA	Gd	GLQ	2158	Unf	0	300	2458	GasA	Ex	Y	SBrkr	2490	0	0	2490	1	0	2	0	2	1	Ex	9	Typ	2	Gd	Attchd	2005	Fin	3	795	TA	TA	Y	70	226	0	0	0	0	NA	GdPrv	NA	0	10	2009	WD	Normal
1707	20	FV	90	7993	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Somerst	Norm	Norm	1Fam	1Story	7	5	2008	2009	Gable	CompShg	VinylSd	VinylSd	NA	NA	Gd	TA	PConc	Ex	TA	No	Unf	0	Unf	0	1436	1436	GasA	Ex	Y	SBrkr	1436	0	0	1436	0	0	2	0	3	1	Gd	6	Typ	0	NA	Attchd	2008	Fin	2	529	TA	TA	Y	0	121	0	0	0	0	NA	NA	NA	0	10	2009	New	Partial
1708	20	FV	72	8640	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Somerst	Norm	Norm	1Fam	1Story	7	5	2008	2008	Hip	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	TA	No	Unf	0	Unf	0	1402	1402	GasA	Ex	Y	SBrkr	1402	0	0	1402	0	0	2	0	3	1	Gd	7	Typ	0	NA	Attchd	2008	RFn	2	625	TA	TA	Y	205	126	0	0	0	0	NA	NA	NA	0	5	2009	WD	Normal
1709	20	FV	112	12606	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Somerst	Norm	Norm	1Fam	1Story	9	5	2007	2008	Gable	CompShg	VinylSd	VinylSd	Stone	120	Gd	TA	PConc	Gd	TA	Av	Unf	0	Unf	0	1530	1530	GasA	Ex	Y	SBrkr	1530	0	0	1530	0	0	2	0	3	1	Gd	7	Typ	1	Gd	Attchd	2008	RFn	3	984	TA	TA	Y	212	136	0	0	0	0	NA	NA	NA	0	5	2009	WD	Normal
1710	20	FV	75	7500	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Somerst	Norm	Norm	1Fam	1Story	8	5	2006	2007	Gable	CompShg	VinylSd	VinylSd	Stone	238	Gd	TA	PConc	Gd	TA	No	GLQ	24	Unf	0	1348	1372	GasA	Ex	Y	SBrkr	1448	0	0	1448	0	0	2	0	2	1	Gd	6	Typ	1	Gd	Attchd	2006	RFn	2	692	TA	TA	Y	0	140	0	0	0	0	NA	NA	NA	0	6	2009	WD	Normal
1711	60	FV	84	10603	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Somerst	Norm	Norm	1Fam	2Story	8	5	2006	2006	Hip	CompShg	VinylSd	VinylSd	Stone	121	Gd	TA	PConc	Ex	Gd	No	GLQ	682	Unf	0	218	900	GasA	Ex	Y	SBrkr	909	886	0	1795	1	0	2	1	3	1	Gd	8	Typ	1	Gd	Attchd	2006	Fin	3	782	TA	TA	Y	168	45	0	0	0	0	NA	NA	NA	0	7	2009	WD	Normal
1712	20	FV	65	8125	Pave	NA	Reg	Lvl	AllPub	Corner	Gtl	Somerst	Norm	Norm	1Fam	1Story	8	5	2008	2009	Hip	CompShg	VinylSd	VinylSd	BrkFace	288	Gd	TA	PConc	Gd	TA	No	Unf	0	Unf	0	1836	1836	GasA	Ex	Y	SBrkr	1836	0	0	1836	0	0	2	0	3	1	Gd	8	Typ	1	Gd	Attchd	2009	Fin	2	517	TA	TA	Y	0	175	0	0	0	0	NA	NA	NA	0	10	2009	New	Partial
1713	20	FV	85	10625	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Somerst	Norm	Norm	1Fam	1Story	7	5	2006	2007	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	TA	No	GLQ	1430	Unf	0	222	1652	GasA	Ex	Y	SBrkr	1662	0	0	1662	1	0	2	0	3	1	Ex	8	Typ	1	Gd	Attchd	2006	RFn	3	711	TA	TA	Y	168	120	0	0	0	0	NA	NA	NA	0	3	2009	WD	Normal
1714	20	FV	68	8736	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Somerst	Norm	Norm	1Fam	1Story	7	5	2003	2004	Gable	CompShg	VinylSd	Wd Shng	None	0	Gd	TA	PConc	Gd	TA	No	GLQ	771	ALQ	360	422	1553	GasA	Ex	Y	SBrkr	1553	0	0	1553	1	0	2	0	3	1	Gd	6	Typ	0	NA	Attchd	2003	RFn	2	588	TA	TA	Y	192	88	0	0	0	0	NA	NA	NA	0	8	2009	WD	Normal
1715	60	FV	65	8127	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Somerst	Norm	Norm	1Fam	2Story	7	5	2003	2003	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	TA	No	GLQ	410	Unf	0	402	812	GasA	Ex	Y	SBrkr	812	841	0	1653	1	0	2	1	3	1	Gd	6	Typ	0	NA	Attchd	2003	RFn	2	628	TA	TA	Y	0	45	0	0	0	0	NA	NA	NA	0	3	2009	WD	Normal
1716	20	RL	80	9605	Pave	NA	Reg	Lvl	AllPub	Corner	Gtl	SawyerW	Norm	Norm	1Fam	1Story	7	6	2007	2007	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	TA	No	Unf	0	Unf	0	1218	1218	GasA	Ex	Y	SBrkr	1218	0	0	1218	0	0	1	1	3	1	Gd	6	Typ	0	NA	Detchd	2007	RFn	2	576	TA	TA	Y	0	178	0	0	0	0	NA	NA	NA	0	4	2009	WD	Normal
1717	20	RL	63	7500	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	SawyerW	Norm	Norm	1Fam	1Story	7	5	2006	2006	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	Gd	No	GLQ	54	Unf	0	1087	1141	GasA	Ex	Y	SBrkr	1141	0	0	1141	1	0	1	1	3	1	Gd	6	Typ	0	NA	Detchd	2006	RFn	2	484	TA	TA	Y	182	0	0	0	0	0	NA	NA	NA	0	6	2009	WD	Normal
1718	20	RL	63	7500	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	SawyerW	Norm	Norm	1Fam	1Story	6	5	2004	2004	Gable	CompShg	VinylSd	VinylSd	None	0	TA	TA	PConc	Gd	TA	No	Unf	0	Unf	0	1158	1158	GasA	Ex	Y	SBrkr	1158	0	0	1158	0	0	1	1	3	1	Gd	5	Typ	0	NA	NA	NA	NA	0	0	NA	NA	Y	0	50	0	0	0	0	NA	NA	NA	0	8	2009	WD	Normal
1719	60	RL	96	10628	Pave	NA	IR1	Lvl	AllPub	Corner	Gtl	SawyerW	Norm	Norm	1Fam	2Story	7	5	2004	2004	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	TA	Gd	Unf	0	Unf	0	835	835	GasA	Ex	Y	SBrkr	871	941	0	1812	0	0	2	1	3	1	Gd	8	Typ	0	NA	BuiltIn	2004	RFn	2	478	TA	TA	Y	146	91	0	0	0	0	NA	NA	NA	0	1	2009	WD	Normal
1720	20	RL	76	10141	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	SawyerW	Norm	Norm	1Fam	1Story	8	5	2004	2004	Gable	Tar&Grv	VinylSd	VinylSd	BrkFace	264	Gd	TA	PConc	Gd	TA	Gd	BLQ	516	Rec	774	222	1512	GasA	Ex	Y	SBrkr	1512	0	0	1512	0	0	2	0	3	1	Gd	6	Typ	0	NA	Attchd	2004	RFn	3	845	TA	TA	Y	210	36	0	0	0	0	NA	NA	NA	0	1	2009	WD	Normal
1721	20	RL	63	13072	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	SawyerW	RRAe	Norm	1Fam	1Story	7	5	2004	2005	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	TA	No	Unf	0	Unf	0	1114	1114	GasA	Ex	Y	SBrkr	1114	0	0	1114	0	0	1	1	3	1	Gd	6	Typ	0	NA	Detchd	2005	Unf	2	576	TA	TA	Y	248	102	0	0	0	0	NA	NA	NA	0	5	2009	WD	Normal
1722	20	RL	63	13072	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	SawyerW	RRAe	Norm	1Fam	1Story	5	5	2004	2004	Gable	CompShg	VinylSd	VinylSd	None	0	TA	TA	PConc	Gd	TA	No	Unf	0	Unf	0	1114	1114	GasA	Ex	Y	SBrkr	1114	0	0	1114	0	0	1	1	3	1	Gd	6	Typ	0	NA	NA	NA	NA	0	0	NA	NA	Y	0	39	0	0	0	0	NA	NA	NA	0	8	2009	WD	Normal
1723	20	RL	60	12450	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	SawyerW	RRAe	Norm	1Fam	1Story	5	5	2003	2004	Gable	CompShg	VinylSd	VinylSd	None	0	TA	TA	PConc	Gd	TA	No	GLQ	836	Unf	0	278	1114	GasA	Ex	Y	SBrkr	1114	0	0	1114	1	0	2	0	3	1	Gd	6	Typ	0	NA	Detchd	2004	Unf	2	576	TA	TA	Y	0	42	0	0	0	0	NA	NA	NA	0	6	2009	WD	Normal
1724	20	RL	61	7328	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	SawyerW	Norm	Norm	1Fam	1Story	7	5	2008	2009	Gable	CompShg	VinylSd	VinylSd	BrkFace	140	Gd	TA	PConc	Gd	TA	No	Unf	0	Unf	0	1450	1450	GasA	Ex	Y	SBrkr	1450	0	0	1450	0	0	2	0	2	1	Gd	6	Typ	0	NA	Attchd	2008	RFn	3	788	TA	TA	Y	0	93	0	0	0	0	NA	NA	NA	0	2	2009	New	Partial
1725	60	RL	43	11492	Pave	NA	IR1	Lvl	AllPub	CulDSac	Gtl	SawyerW	Norm	Norm	1Fam	2Story	7	5	1996	1997	Gable	CompShg	VinylSd	VinylSd	BrkFace	132	Gd	TA	PConc	Gd	TA	No	GLQ	637	Unf	0	276	913	GasA	Ex	Y	SBrkr	913	1209	0	2122	1	0	2	1	4	1	Gd	8	Typ	1	TA	Attchd	1997	RFn	2	559	TA	TA	Y	0	74	0	0	0	0	NA	NA	NA	0	4	2009	WD	Normal
1726	60	RL	70	7703	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	SawyerW	Norm	Norm	1Fam	2Story	6	6	1992	1992	Gable	CompShg	HdBoard	HdBoard	None	0	Gd	Gd	PConc	Gd	Gd	No	GLQ	52	Rec	364	400	816	GasA	Ex	Y	SBrkr	833	897	0	1730	0	0	2	1	3	1	Gd	6	Typ	0	NA	Attchd	1992	RFn	2	528	TA	TA	Y	0	91	0	0	168	0	NA	NA	NA	0	11	2009	WD	Normal
1727	120	RL	50	7175	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	SawyerW	Norm	Norm	TwnhsE	1Story	6	5	1990	1991	Gable	CompShg	Plywood	ImStucc	None	0	Gd	TA	PConc	Gd	TA	No	Unf	0	Unf	0	1332	1332	GasA	Gd	Y	SBrkr	1332	0	0	1332	0	0	2	0	2	1	Gd	5	Typ	0	NA	Attchd	1990	RFn	2	542	TA	TA	Y	0	60	0	0	0	0	NA	NA	NA	0	2	2009	WD	Normal
1728	60	RL	70	9109	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	SawyerW	RRAe	Norm	1Fam	2Story	7	5	1994	1994	Gable	CompShg	VinylSd	VinylSd	None	0	Gd	TA	PConc	Gd	TA	No	LwQ	36	GLQ	596	122	754	GasA	Ex	Y	SBrkr	754	786	0	1540	1	0	2	1	3	1	Gd	6	Typ	0	NA	Attchd	1994	RFn	2	495	TA	TA	Y	140	32	0	0	0	0	NA	NA	NA	0	10	2009	WD	Normal
1729	60	RL	NA	10274	Pave	NA	IR1	Lvl	AllPub	CulDSac	Gtl	SawyerW	Norm	Norm	1Fam	2Story	6	7	1986	1986	Gable	CompShg	VinylSd	VinylSd	BrkFace	141	TA	Gd	CBlock	Gd	TA	No	Rec	331	Unf	0	345	676	GasA	TA	Y	SBrkr	698	702	0	1400	0	0	2	1	3	1	TA	6	Typ	0	NA	Attchd	1986	RFn	2	465	TA	TA	Y	0	48	0	0	0	0	NA	NA	NA	0	7	2009	WD	Normal
1730	90	RL	75	8250	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	SawyerW	Norm	Norm	Duplex	2Story	6	7	1981	1981	Gable	CompShg	Wd Sdng	Wd Shng	None	0	TA	TA	Slab	NA	NA	NA	NA	0	NA	0	0	0	GasA	TA	Y	SBrkr	964	918	0	1882	0	0	2	0	4	2	TA	8	Typ	2	TA	Attchd	1981	Unf	2	612	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	5	2009	WD	Normal
1731	20	RL	63	9750	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Sawyer	Norm	Norm	1Fam	1Story	5	5	1962	1962	Hip	CompShg	HdBoard	Plywood	None	0	TA	TA	CBlock	TA	TA	No	LwQ	68	BLQ	884	28	980	GasA	Gd	Y	SBrkr	980	0	0	980	1	0	1	0	3	1	TA	5	Typ	0	NA	Detchd	1969	Unf	2	400	TA	TA	Y	0	28	0	0	0	0	NA	MnPrv	NA	0	11	2009	WD	Normal
1732	20	RL	NA	8499	Pave	NA	IR1	Lvl	AllPub	Corner	Gtl	Sawyer	Feedr	Norm	1Fam	1Story	5	6	1961	1961	Gable	CompShg	MetalSd	MetalSd	None	0	TA	TA	CBlock	TA	TA	No	GLQ	660	Unf	0	204	864	GasA	Ex	Y	SBrkr	864	0	0	864	1	0	1	0	3	1	TA	5	Typ	0	NA	Detchd	1982	Unf	2	732	TA	TA	Y	0	312	0	0	0	0	NA	NA	NA	0	6	2009	WD	Normal
1733	20	RL	NA	9079	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Sawyer	Norm	Norm	1Fam	1Story	5	5	1961	1961	Gable	CompShg	Wd Sdng	Plywood	None	0	TA	TA	CBlock	TA	TA	No	BLQ	864	Unf	0	0	864	GasA	TA	Y	SBrkr	864	0	0	864	0	0	1	0	2	1	TA	5	Typ	0	NA	Attchd	1961	Unf	1	440	TA	TA	Y	158	0	0	0	0	0	NA	NA	NA	0	7	2009	WD	Normal
1734	20	RL	NA	9316	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Sawyer	Norm	Norm	1Fam	1Story	5	5	1965	1965	Gable	CompShg	HdBoard	Plywood	None	0	TA	TA	CBlock	TA	TA	No	Rec	544	Unf	0	480	1024	GasA	Gd	Y	SBrkr	1020	0	0	1020	0	0	2	0	3	1	TA	5	Typ	0	NA	Attchd	1965	Unf	1	288	TA	TA	Y	171	0	0	0	0	0	NA	MnPrv	NA	0	5	2009	Oth	Family
1735	20	RL	NA	7791	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Sawyer	RRAe	Norm	1Fam	1Story	5	8	1963	1995	Gable	CompShg	Plywood	Plywood	None	0	Gd	Gd	CBlock	TA	TA	No	ALQ	624	Unf	0	288	912	GasA	Ex	Y	SBrkr	912	0	0	912	1	0	1	0	3	1	Gd	6	Typ	0	NA	Attchd	1963	RFn	1	300	TA	TA	Y	0	0	0	0	0	0	NA	GdWo	NA	0	10	2009	WD	Normal
1736	20	RL	65	7150	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Sawyer	Feedr	Norm	1Fam	1Story	5	6	1962	1962	Gable	CompShg	VinylSd	VinylSd	BrkFace	60	TA	TA	CBlock	TA	TA	No	LwQ	140	BLQ	590	182	912	GasA	Gd	Y	SBrkr	912	0	0	912	0	1	1	0	3	1	TA	6	Typ	0	NA	Attchd	1962	Unf	1	252	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	10	2009	WD	Normal
1737	20	RL	NA	15676	Pave	NA	IR1	Low	AllPub	Inside	Gtl	Veenker	Norm	Norm	1Fam	1Story	8	8	1980	1980	Gable	CompShg	VinylSd	VinylSd	BrkFace	115	Gd	Gd	CBlock	Gd	Gd	Gd	ALQ	1733	Rec	92	189	2014	GasA	Gd	Y	SBrkr	2014	0	0	2014	1	0	2	0	2	1	Gd	6	Maj1	2	Gd	Attchd	1980	RFn	3	864	TA	TA	Y	462	0	0	255	0	0	NA	MnPrv	NA	0	4	2009	WD	Normal
1738	60	RL	NA	11949	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NoRidge	Norm	Norm	1Fam	2Story	7	8	1991	2008	Gable	CompShg	VinylSd	VinylSd	BrkFace	196	Gd	Gd	PConc	Gd	TA	No	GLQ	601	ALQ	216	158	975	GasA	Ex	Y	SBrkr	975	780	0	1755	0	1	2	1	3	1	Gd	7	Typ	1	TA	Attchd	1991	Unf	2	524	TA	TA	Y	502	60	0	0	0	0	NA	GdPrv	NA	0	7	2009	WD	Normal
1739	160	FV	32	2880	Pave	Pave	Reg	Lvl	AllPub	Inside	Gtl	Somerst	Norm	Norm	Twnhs	2Story	7	5	2004	2005	Gable	CompShg	MetalSd	MetalSd	None	0	Gd	TA	PConc	Gd	TA	No	Unf	0	Unf	0	1376	1376	GasA	Ex	Y	SBrkr	1376	1629	0	3005	0	0	2	1	3	1	Gd	9	Mod	1	TA	BuiltIn	2004	Fin	3	704	TA	TA	Y	0	177	0	0	0	0	NA	NA	NA	0	7	2009	WD	Normal
1740	120	FV	NA	3830	Pave	Pave	IR1	Lvl	AllPub	Inside	Gtl	Somerst	Norm	Norm	TwnhsE	1Story	6	5	2008	2008	Gable	CompShg	VinylSd	VinylSd	Stone	280	Gd	TA	PConc	Gd	TA	No	Unf	0	Unf	0	1726	1726	GasA	Ex	Y	SBrkr	1726	0	0	1726	0	0	2	1	2	1	Gd	6	Typ	1	Gd	Attchd	2008	Fin	2	561	TA	TA	Y	0	254	0	0	0	0	NA	NA	NA	0	1	2009	New	Partial
1741	120	FV	NA	4217	Pave	Pave	IR1	Lvl	AllPub	Inside	Gtl	Somerst	Norm	Norm	TwnhsE	1Story	6	5	2008	2008	Gable	CompShg	VinylSd	VinylSd	Stone	252	Gd	TA	PConc	Gd	TA	No	GLQ	962	Unf	0	183	1145	GasA	Ex	Y	SBrkr	1256	0	0	1256	1	0	1	1	1	1	Gd	5	Typ	1	Gd	Attchd	2008	Fin	2	641	TA	TA	Y	0	169	0	0	0	0	NA	NA	NA	0	3	2009	WD	Normal
1742	160	FV	34	2998	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Somerst	Norm	Norm	TwnhsE	2Story	6	5	2000	2000	Gable	CompShg	MetalSd	MetalSd	BrkFace	513	Gd	TA	PConc	Gd	TA	No	GLQ	507	Unf	0	249	756	GasA	Ex	Y	SBrkr	756	756	0	1512	1	0	2	1	2	1	Gd	4	Typ	0	NA	Detchd	2000	Unf	2	440	TA	TA	Y	0	32	0	0	0	0	NA	NA	NA	0	8	2009	WD	Normal
1743	160	FV	35	3768	Pave	NA	Reg	Lvl	AllPub	FR2	Gtl	Somerst	Norm	Norm	TwnhsE	2Story	7	5	1999	1999	Hip	CompShg	MetalSd	MetalSd	BrkFace	218	Gd	TA	PConc	Gd	TA	No	GLQ	549	Unf	0	142	691	GasA	Ex	Y	SBrkr	713	739	0	1452	1	0	2	1	3	1	Gd	6	Typ	0	NA	Detchd	1999	Unf	2	506	TA	TA	Y	0	34	0	0	0	0	NA	NA	NA	0	9	2009	WD	Normal
1744	20	RL	NA	14694	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	Veenker	Norm	Norm	1Fam	1Story	8	9	1977	2008	Gable	CompShg	MetalSd	MetalSd	BrkFace	450	Ex	Ex	CBlock	Gd	Gd	Gd	GLQ	1252	ALQ	136	306	1694	GasA	Ex	Y	SBrkr	1694	0	0	1694	1	0	2	0	2	1	Ex	5	Typ	1	Gd	Attchd	1977	Fin	2	642	TA	TA	Y	501	120	0	225	0	0	NA	NA	NA	0	6	2009	WD	Normal
1745	20	RL	110	15417	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	Veenker	Norm	Norm	1Fam	1Story	7	5	1981	1981	Gable	CompShg	BrkFace	BrkFace	None	0	Gd	TA	CBlock	Gd	TA	Mn	LwQ	121	Unf	0	1619	1740	GasA	TA	Y	SBrkr	1740	0	0	1740	0	0	1	1	2	1	Gd	7	Typ	0	NA	Attchd	1981	RFn	2	540	TA	TA	Y	228	20	218	0	0	0	NA	NA	NA	0	6	2009	WD	Normal
1746	80	RL	80	9600	Pave	NA	Reg	Low	AllPub	FR2	Mod	Veenker	Feedr	Norm	1Fam	SLvl	8	5	1976	1976	Gable	CompShg	Plywood	Plywood	BrkFace	200	Gd	Gd	CBlock	TA	TA	No	Unf	0	Unf	0	392	392	GasA	Ex	Y	SBrkr	1487	1012	0	2499	0	0	2	1	4	1	TA	5	Typ	1	Gd	Attchd	1976	Unf	2	527	TA	TA	Y	0	64	0	0	0	0	NA	NA	NA	0	1	2009	WD	Abnorml
1747	60	RL	NA	12732	Pave	NA	IR1	Lvl	AllPub	CulDSac	Gtl	NWAmes	PosN	Norm	1Fam	2Story	7	6	1974	1974	Gable	CompShg	VinylSd	VinylSd	None	0	TA	TA	CBlock	TA	TA	Mn	GLQ	560	LwQ	42	150	752	GasA	TA	Y	SBrkr	1285	782	0	2067	0	0	2	1	3	1	Gd	7	Typ	2	TA	Attchd	1974	RFn	2	784	TA	TA	Y	297	40	0	0	0	0	NA	NA	NA	0	6	2009	WD	Normal
1748	60	RL	80	10400	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NWAmes	PosA	Norm	1Fam	2Story	6	7	1967	1997	Gable	CompShg	MetalSd	MetalSd	BrkFace	256	TA	TA	PConc	TA	TA	No	Unf	0	Unf	0	932	932	GasA	Gd	Y	SBrkr	1271	1369	0	2640	0	0	2	1	5	1	Gd	8	Typ	1	TA	Attchd	1967	RFn	2	515	TA	TA	Y	0	120	0	0	168	0	NA	NA	NA	0	5	2009	WD	Normal
1749	20	RL	80	9600	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NWAmes	Feedr	Norm	1Fam	1Story	5	5	1969	1969	Gable	CompShg	HdBoard	HdBoard	BrkFace	128	TA	TA	CBlock	Gd	TA	Mn	ALQ	553	Rec	147	588	1288	GasA	TA	Y	SBrkr	1336	0	0	1336	0	1	2	0	3	1	TA	6	Typ	1	Fa	Attchd	1969	RFn	2	502	TA	TA	Y	312	11	0	0	0	0	NA	NA	Shed	650	8	2009	WD	Normal
1750	20	RL	75	9000	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NWAmes	Feedr	Norm	1Fam	1Story	6	5	1969	1969	Gable	CompShg	HdBoard	HdBoard	BrkFace	200	TA	TA	CBlock	TA	TA	Av	BLQ	955	Unf	0	261	1216	GasA	TA	Y	SBrkr	1216	0	0	1216	1	0	1	0	3	1	TA	5	Typ	0	NA	Attchd	1969	Unf	1	336	TA	TA	Y	0	0	0	0	0	0	NA	MnPrv	NA	0	8	2009	WD	Abnorml
1751	60	RL	NA	13774	Pave	NA	IR1	Lvl	AllPub	Inside	Gtl	NWAmes	Norm	Norm	1Fam	2Story	7	7	1977	1992	Hip	CompShg	HdBoard	HdBoard	BrkFace	283	TA	Gd	PConc	Gd	TA	No	GLQ	432	Unf	0	476	908	GasA	Ex	Y	SBrkr	1316	972	0	2288	0	0	1	2	4	1	Gd	8	Typ	2	TA	Attchd	1977	RFn	2	520	TA	TA	Y	321	72	0	0	156	0	NA	NA	NA	0	11	2009	WD	Normal
1752	20	RL	62	7130	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NAmes	Norm	Norm	1Fam	1Story	5	6	1967	1967	Gable	CompShg	HdBoard	HdBoard	None	0	TA	TA	PConc	TA	TA	No	BLQ	648	Unf	0	216	864	GasA	TA	Y	SBrkr	864	0	0	864	0	1	1	0	2	1	TA	5	Typ	0	NA	Attchd	1967	Fin	1	312	TA	TA	Y	0	0	0	0	0	0	NA	GdPrv	NA	0	6	2009	WD	Normal
1753	20	RL	80	9600	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NAmes	Norm	Norm	1Fam	1Story	5	5	1967	1967	Hip	CompShg	HdBoard	HdBoard	None	0	TA	TA	CBlock	TA	TA	No	Unf	0	Unf	0	1568	1568	GasA	TA	Y	SBrkr	1568	0	0	1568	0	0	1	1	3	1	TA	7	Typ	0	NA	Attchd	1967	Unf	2	440	TA	TA	Y	160	40	0	0	0	0	NA	NA	NA	0	3	2009	COD	Normal
1754	60	RL	80	9600	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NWAmes	Norm	Norm	1Fam	2Story	7	5	1974	1974	Gable	CompShg	Plywood	Plywood	BrkFace	252	TA	TA	CBlock	TA	TA	No	ALQ	698	Unf	0	467	1165	GasA	Gd	Y	SBrkr	1165	896	0	2061	0	1	2	1	4	1	TA	8	Typ	1	TA	Attchd	1974	RFn	2	498	TA	TA	Y	0	77	0	0	196	0	NA	NA	NA	0	5	2009	COD	Abnorml
1755	85	RL	NA	16500	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NWAmes	Norm	Norm	1Fam	SFoyer	6	5	1971	1971	Hip	CompShg	HdBoard	HdBoard	BrkFace	509	TA	TA	CBlock	Gd	TA	Av	GLQ	962	Unf	0	270	1232	GasA	Fa	Y	SBrkr	1320	0	0	1320	0	1	2	0	3	1	TA	5	Typ	1	Gd	Attchd	1971	RFn	2	495	TA	TA	Y	0	20	0	0	0	0	NA	NA	NA	0	5	2009	WD	Normal
1756	20	RL	60	7436	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NAmes	Norm	Norm	1Fam	1Story	4	7	1960	1960	Gable	CompShg	VinylSd	VinylSd	None	0	TA	TA	CBlock	TA	TA	No	ALQ	734	Unf	0	160	894	GasA	Gd	Y	SBrkr	894	0	0	894	1	0	1	0	2	1	TA	5	Typ	1	Po	Detchd	1988	Unf	2	396	TA	TA	Y	0	0	0	360	0	0	NA	GdWo	NA	0	8	2009	WD	Normal
1757	20	RL	65	8125	Pave	NA	Reg	Lvl	AllPub	Inside	Gtl	NAmes	Norm	Norm	1Fam	1Story	5	7	1959	1959	Hip	CompShg	MetalSd	MetalSd	None	0	TA	TA	CBlock	TA	TA	No	BLQ	403	Unf	0	461	864	GasA	Ex	Y	SBrkr	864	0	0	864	0	0	1	0	3	1	TA	5	Typ	0	NA	Detchd	1960	Unf	1	308	TA	TA	Y	0	0	0	0	0	0	NA	NA	NA	0	9	2009	WD	Normal
1758	20	RL	NA	9450	Pave	NA	IR1	Lvl	AllPub	Corner	Gtl	NAmes	Norm	Norm	1Fam	1Story	4	5	1957	1957	Gable	CompShg	Wd Sdng	Wd Sdng	BrkFace	160	TA	TA	CBlock	TA	TA	No	BLQ	775	Unf	0	265	1040	GasA	TA	Y	SBrkr	1362	0	0	1362	1	0	1	0	3	1	TA	6	Typ	1	Gd	Attchd	1982	RFn	3	768	TA	TA	Y	0	0	84	0	0	0	NA	MnPrv	NA	0	5	2009	WD	Normal
1759	20	RL	NA	13495	Pave	NA	IR1	Lvl	AllPub	Corner	Gtl	NAmes	Norm	Norm	1Fam	1Story	5	6	1956	1956	Gable	CompShg	Wd Sdng	Wd Sdng	BrkFace	70	TA	Gd	CBlock	TA	TA	No	BLQ	625	LwQ	201	222	1048	GasA	Fa	Y	SBrkr	1728	0	0	1728	1	0	2	0	3	1	TA	7	Min1	1	Gd	Detchd	1956	Unf	2	576	TA	TA	Y	0	99	0	0	0	0	NA	NA	NA	0	7	2009	WD	Normal

ii) Sample submission
Id	SalePrice
1461	169277.0525
1462	187758.394
1463	183583.6836
1464	179317.4775
1465	150730.08
1466	177150.9892
1467	172070.6592
1468	175110.9565
1469	162011.6988
1470	160726.2478
1471	157933.2795
1472	145291.245
1473	159672.0176
1474	164167.5183
1475	150891.6382
1476	179460.9652
1477	185034.6289
1478	182352.1926
1479	183053.4582
1480	187823.3393
1481	186544.1143
1482	158230.7752
1483	190552.8293
1484	147183.6749
1485	185855.3009
1486	174350.4707
1487	201740.6207
1488	162986.3789
1489	162330.1991
1490	165845.9386
1491	180929.6229
1492	163481.5015
1493	187798.0767
1494	198822.1989
1495	194868.4099
1496	152605.2986
1497	147797.7028
1498	150521.969
1499	146991.6302
1500	150306.3078
1501	151164.3725
1502	151133.707
1503	156214.0425
1504	171992.7607
1505	173214.9125
1506	192429.1873
1507	190878.6951
1508	194542.5441
1509	191849.4391
1510	176363.7739
1511	176954.1854
1512	176521.217
1513	179436.7048
1514	220079.7568
1515	175502.9181
1516	188321.0738
1517	163276.3245
1518	185911.3663
1519	171392.831
1520	174418.207
1521	179682.7096
1522	179423.7516
1523	171756.9181
1524	166849.6382
1525	181122.1687
1526	170934.4627
1527	159738.2926
1528	174445.7596
1529	174706.3637
1530	164507.6725
1531	163602.5122
1532	154126.2702
1533	171104.8535
1534	167735.3927
1535	183003.6133
1536	172580.3812
1537	165407.8891
1538	176363.7739
1539	175182.9509
1540	190757.1778
1541	167186.9958
1542	167839.3768
1543	173912.4212
1544	154034.9174
1545	156002.9558
1546	168173.9433
1547	168882.4371
1548	168173.9433
1549	157580.1776
1550	181922.1526
1551	155134.2278
1552	188885.5733
1553	183963.193
1554	161298.7623
1555	188613.6676
1556	175080.1118
1557	174744.4003
1558	168175.9113
1559	182333.4726
1560	158307.2067
1561	193053.0555
1562	175031.09
1563	160713.2946
1564	173186.215
1565	191736.7598
1566	170401.631
1567	164626.5779
1568	205469.4094
1569	209561.7842
1570	182271.5031
1571	178081.5494
1572	178425.9561
1573	162015.3185
1574	181722.4204
1575	156705.7302
1576	182902.4203
1577	157574.5954
1578	184380.7391
1579	169364.4692
1580	175846.1798
1581	189673.2953
1582	174401.3177
1583	179021.4487
1584	189196.8453
1585	139647.0957
1586	161468.1983
1587	171557.3232
1588	179447.368
1589	169611.619
1590	172088.8727
1591	171190.6241
1592	154850.5084
1593	158617.6557
1594	209258.3369
1595	177939.0276
1596	194631.1003
1597	213618.8716
1598	198342.5042
1599	138607.9715
1600	150778.959
1601	146966.2303
1602	162182.5962
1603	176825.941
1604	152799.8124
1605	180322.3221
1606	177508.0272
1607	208029.6427
1608	181987.2825
1609	160172.728
1610	176761.3177
1611	176515.4975
1612	176270.4531
1613	183050.8463
1614	150011.1021
1615	159270.5378
1616	163419.6637
1617	163399.9833
1618	173364.1615
1619	169556.8359
1620	183690.596
1621	176980.9149
1622	204773.3622
1623	174728.656
1624	181873.4582
1625	177322.0008
1626	193927.939
1627	181715.6227
1628	199270.8412
1629	177109.59
1630	153909.5783
1631	162931.2033
1632	166386.7567
1633	173719.3038
1634	179757.9257
1635	179007.602
1636	180370.8086
1637	185102.6167
1638	198825.5635
1639	184294.576
1640	200443.7921
1641	181294.7845
1642	174354.3363
1643	172023.6778
1644	181666.9229
1645	179024.4913
1646	178324.1916
1647	184534.6767
1648	159397.2504
1649	178430.9667
1650	177743.7994
1651	179395.3055
1652	151713.3847
1653	151713.3847
1654	168434.978
1655	153999.1003
1656	164096.0974
1657	166335.403
1658	163020.7254
1659	155862.5107
1660	182760.6511
1661	201912.2706
1662	185988.234
1663	183778.4489
1664	170935.8592
1665	184468.9084
1666	191569.0897
1667	232991.0256
1668	180980.7214
1669	164279.1305
1670	183859.4604
1671	185922.4657
1672	191742.7781
1673	199954.0725
1674	180690.2748
1675	163099.3096
1676	140791.9225
1677	166481.8665
1678	172080.4345
1679	191719.1617
1680	160741.0986
1681	157829.5469
1682	196896.7486
1683	159675.424
1684	182084.7909
1685	179233.9264
1686	155774.2709
1687	181354.3267
1688	179605.5637
1689	181609.3487
1690	178221.5316
1691	175559.9207
1692	200328.8228
1693	178630.0606
1694	177174.5352
1695	172515.6874
1696	204032.9929
1697	176023.2328
1698	202202.0733
1699	181734.4801
1700	183982.159
1701	188007.9424
1702	185922.9668
1703	183978.5449
1704	177199.6186
1705	181878.648
1706	173622.0887
1707	180728.1686
1708	176477.0266
1709	184282.2667
1710	162062.4754
1711	182550.071
1712	180987.9496
1713	178173.7976
1714	179980.6359
1715	173257.6378
1716	177271.2911
1717	175338.3554
1718	177548.1405
1719	175969.9166
1720	175011.482
1721	185199.3726
1722	188514.0502
1723	185080.1453
1724	157304.4026
1725	194260.8595
1726	181262.33
1727	157003.2927
1728	182924.4994
1729	181902.5864
1730	188985.3717
1731	185290.9045
1732	177304.4258
1733	166274.9005
1734	177807.4205
1735	180330.6248
1736	179069.1122
1737	175943.3718
1738	185199.0506
1739	167350.9108
1740	149315.3119
1741	139010.8478
1742	155412.1518
1743	171308.314
1744	176220.5433
1745	177643.435
1746	187222.6533
1747	185635.1321
1748	206492.5342
1749	181681.0211
1750	180500.1981
1751	206486.1709
1752	161334.3012
1753	176156.5583
1754	191642.2235
1755	191945.808
1756	164146.306
1757	179883.0571
1758	178071.1377
1759	188241.6379
![image](https://github.com/JDjaga/PRODIGY_TrackCode_TaskNumber/assets/115528054/11b4a26e-a7e4-4f80-ba08-777c8910d04e)

