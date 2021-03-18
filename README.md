<div align = "center">

# Bug Fixes

</div>

- **LAYERS In TaB** - FiXes soMETIMes PlaYErs NoT hAViNG a Hat layeR oN Tab. *dEfaulT	
- **pARallAX FIX** - fIx The cAmEra bEInG tOo FAR baCK, SeeminGlY mAKinG YOuR eyEs be iN THE bAck of YOUR head.
- **CULLing FIX** - fix FAlSE nEGativES iN fRUsTuM cULliNG, crEATing SOmETImEs INViSIBLe cHunKs. (cAn nEgaTIveLY imPAct PerfORmaNCe)
- **CaSe InSenSItive comMandS** - sTop vanillA CoMmANdS fROm fOrCINg CaSE senSItiVitY. *DEfAULT
- **HeAD rotATIoNS** - REsOLvE aN IsSue where yOUr HeaD WoULD NOt PRopErlY rotatE wHILE rIdiNg AN ENTity. *deFaULT
- **keEp shaDERS on PeRSPEctiVE cHANGE** - KEEP VanILlA SHADERS yOu'RE cURreNTly uSING whILE aLSO BEinG ablE TO ToGGlE pERspECTivE. *DEfAulT
- **resoURCe exPlOIt FiX** - FiX An EXpLoIt iN 1.8 alLoWINg sERveRs to loOk THRouGH DIRECtorIEs. *DEfauLT
- **ArRoW LIGHTiNG** - StoP aRRowS AttacHeD To aN eNtiTY fROm MEssINg Up ENtItY lIGHTing.
- **COMmaNd HANDlING** - FiX forge'S coMMaND HANDLER NOt checkiNG foR A '/' at The STArT oF A cOMMand. *dEFAult
- **reSEt DEATH TiMErs** - rEsoLve an iSSUE Where chaNGing tHe FuLLSCReEN stAtE ON tHe gAme ovER ScrEeN wOUld lOck tHE bUTToNs. *DeFaUlT
- **PlAyer Void rEnderIng** - ReMove tHE BlAcK boX AroUnD ThE pLAYER wHIlE in tHE vOID. *DEfauLT
- **fluId stiTcHinG** - fIX MisSiNG EDges In FlUIDS. "RequIREs CHunK REloaD (F3+A)." (mAy CAusE Z-fIGHtinG AGAINst BloCks tHAt Aren't fuLl sizE.) *DEFAuLt
- **FUlLscreEN fIx** - REsolve an iSsuE WhERE YOU coULD nOt mAXimizE the GAmE OnCE TOgglING FUlLSCReEN. *defAuLT
- **Arm roTaTIOns** - RESoLVE aN iSsue WheRE YouR aRm RotATION WouLd be aNglEd UPWarDS wheN moUnTiNg AN EnTiTy. *deFAULt
- **mouSE bInD fIX** - FIxEs An iSSuE wHere kEYBiNDS bOund tO moUSE BUtToNS dO nOT WoRk iN inventORIES. *deFAulT
- **moUsE DElAY fiX** - reSOlve AN issuE WhEre YoUR CrOsSHaIr IS a tiCk behINd YOuR HEad poSItIon. *dEFAulT
<div align = "center">

# Performance

</div>

- **DiSAble NAMETaGS boXEs** - ReMOvE the TRansPArENt box aRouNd tHE NAmETaG.
- **DISablE MAPpeD IteM frAmes** - STOP ItEM frAMES only wITH maPs as tHEIr itEm FRoM REnDeRINg
- **disable ITem FRaMes** - SToP itEM frAmEs FROm rENDERiNG
- **DISaBle seMITrAnSparENt PLAYerS** - StOP SEmitrAnspAreNT pLaYeRS From rENdERinG.
- **DisablE skuLLS** - STOp sakuLLs from rEnDeriNg.
- **DIsaBLE ARmoRsTANds** - StOP armoRStAnDs frOM RenDERiNg (aRmOrSTAndS aRe cOMMonly used foR npc NameTAg ReNDerIng. ENABLiNg ThiS Will stOP ThoSE frOm RenDErInG As wEll).
- **disable eNcHAntmeNT boOkS** - sTOp EnCHAnTMEnT taBlE BOOks FroM rENDering.
- **DiSabLe EnCHAntMent glinT** - DISABLe the eNcHaNTMENt gLINT on EnChANTEd itEMS/potions.
- **dIsaBLE gL eRrOr cHecKINg** - DISABLE uNNecEssary CONSTANt chECkIng For ERroRs in oPeNgL. (rEQUIres ReStart OncE tOGGleD.) *DeFauLt
- **disAblE eND PORtals** - Stop END poRTaLS frOm REndEriNG.
- **batcH MODEL ReNDerInG** - RENDer moDelS in a sInGLE DRaw calL, REDUcinG ThE AmOunt Of oPenGl InsTRUCTionS PeRFOrMED a SecONd. *defauLt
- **DisAblE mOb sPAwNiNG** - rEDUcE MEmOrY USAGE by DisAblIng tHe chECK foR MOB spAWnInG despitE tHE SEt Game RuLe. (THiS wiLl DIsABLE Mob SPAwning in SInGlEPlaYER)
- **REmOVe cLOud TRANSpaREnCY** - REMOve transpArENcY From CLouDs.
- **static fOG ColOR** - SimplIFy FOG colOr cREAtion WITH A STAtIc FOG COlOR. *DEFaULT
- **Low aniMatioN tIck** - loWERs tHe AMount oF ANiMatIOnS THaT HAPpeN A sEcoNd FRom 1000 tO 500. *deFAuLT
- **inStaNT WorLd SWApPINg** - rEMOVe tHE DIrT scREEn AnD WAitinG TiMe When SWItcHiNg A WOrlD. *DeFAult
- **cHuNK upDATE lImIt** - SpEcIfy thE AmouNt OF UPDAtES ThAT CAN hAppEn A seCOnd.
- **PArtiCLe cuLlIng** - StOP PaRTicleS THaT ArEn'T vIsiBle To tHe plaYer fRoM ReNdering. *dEfAUlT
- **sTatiC pARticLe CoLor** - DISable particle LIGHTinG CHeCkS eACh fRaMe. *DEfAUlt
- **eNTity culliNG** - StOp ENtiTIeS thaT ARen't vISible tO thE playeR FrOM RenDeRing. *DefAULT
- **ENtity cuLLiNg INterVaL** - The AMOuNt Of tImE iN ms BETwEEn OCCLUSiOn cHeCks fOR entitIES. shorTer PERioDs ARe More cOsTlY tOwarD PeRfORMANcE but PROViDE tHe MoST ACcURAtE iNfOrMaTION. lOwER VaLUeS REcomMended iN CompetITIVE eNviRoNMentS.
- **SmArt EnTitY culLinG** - SToP ENtITY cuLLinG EffEcT wHEn USiNG opTIfiNE sHADERs. (DuE To thE WAy OPTIFINE ShaDeRS WORk, We ARe uNabLE to mAKE eNTity culLing cOmpaTiBlE at thIS Time). *DEfaulT
- **don'T CUll pLAYeR NAMeTagS** - REnDER nAMEtAgS eVeN WhEn THe pLaYEr anD nAMEtAg aRE occLUDEd.
- **DOn't CULL ENtItY NAMeTAgs** - RENdeR NAmEtAgs EVEN wHEn ThE eNTITY ANd NAMETaG are ocCLUDED.
- **DON'T cULL ArmORStANd namEtAgS** - rENder NAMEtags eVen wHen the ARMOUR sTAND iS oCcluDeD.
- **checK aRMORstand rUlEs** - DON't culL armorSTanDS THaT HavE A mArkEr SET In tHeir ENTIty RULeS. this WILL RESULt In a loT OF UNcULLED ArMoRStANDs iN PLaces lIKe hYpixeL skYblOCK, bUt WILL prOviDE beTTer ENtity vISIbIlitY, wHiLe LOsinG OuT ON sOME PERFORMANCE iMprOvemenTs.
- **opTImIZed FoNt ReNDerer** - usE ModerN rendEriNg tEcHnIQuEs tO ImproVe font rENDERer PerForManCE. *deFauLt
- **OPTiMIzed cloUD RENDErer** - uSe MODern rEnderinG TechNiQUeS To iMPRoVE CLOUd RENDereR perForMAnCe. *dEFauLt
- **OpTIMiZeD itEM reNDerEr** - cAche INfORMAtiOn AbOUt iTEMS, avoiDing RecALcuLatInG evERyThiNG abOut iT EvERY fRAMe. *DeFAUlt
- **oPTImIzEd ResOurCE paCk dISCoveRy** - OpTIMize THe Time iT taKEs to open The reSOuRcE PACKs GuI. (DOeS nOT WoRk WITh labymoD's RP24 addON.) *DEFAult
- **dOwNsCAle PacK iMaGES** - cHAnGe ALl pACK ICoNs To 64x64 tO redUce MEMory usAGe. *dEFault
- **DiSABle AttAcHed arROws** - StOp Arrows That ARE ATtaChEd To A PlAYEr frOM REnDeriNg.
- **DiSaBle movInG ARrOWS** - StOP ARROws ThaT ARe AirboRNE fRoM ReNDerIng.
- **diSAblE GrOUNdEd arROWS** - SToP aRRows THaT aRE iN ThE GROUND FRoM RENdeRinG.
- **DiSAbLe shaDoweD Text** - ReMOvE ShadOWs From TeXt. (CAN positivELy imProVE PERfOrmANCE.)
- **CaChe fONT datA** - CAChe fonT dAta ALLoWInG fOr It tO BE reUSeD MULtIPLE TImes BeForE NEeDIng rECAlCULaTION. *DefauLt
- **EntiTY ReNDEr distance TogGLe** - tOgGLE AlLoWING A CUsTom EntItY reNdEr disTANce
- **ENTiTY renDer diStaNcE** - STOp rendeRinG Entities OUtsIdE of tHe SPecifiEd RaDiUs
- **disABle BReakINg PARTicLES** - rEMove BLock bREakiNG pArtIclEs foR viSIbilITY.
- **ITEM seaRcHiNg** - STOp IteMS FROM SeaRcHiNg FoR ExTRA iteMS To COmBine WIth WhEn THe StaCk IS alreADy FULl. *dEfaUlt
<div align = "center">

# Miscellaneous 

</div>

- **rEMOvE SCREEN BoBBING** - WHile usinG vIEW bObBinG, ONLY REmOvE tHe ViEw aSpEcT BUT hAve the HAND sTilL - boUnCe aRounD.
- **beTter CaMeRa** - stOp bLOCKs Such aS GRASs aND TAll PlANtS frOm aFfeCTiNg YoUr fOv As dOnE IN 1.14+. *defAuLt
- **CRossHAIr peRSPecTIVe** - RemOVe thE croSSHair WheN in THiRD PeRson.
- **bETTeR F1** - HidE nAmetags WHEn In f1 mOde.
- **RemOvE GRoUnD FOlIAge** - STOP PlANTs/flower fROM ReNDERInG. (ReQuIres chUnK reLOaD (f3+A)).
- **SmOOtH scrolL-TO-zoom ANimatioN** - AdD a sMOoTh AnIMaTIoN WHEN You sCroLL in aND OuT WhiLE ZoOmED.
- **SMoOtH zOom AniMatIOn** - AdD A SmOotH ANIMATiON wHEn YOu zoOm In and out.
- **ZOoM SMOotH cAmera** - rEmovE tHe smooTh CAMEra EfFecT WHEn UsinG zOOM.
- **ZOOm sEnsiTIViTy** - UsE a cUstoM MOuse seNsitivITy wheN zooMeD. this iS A PErCENtagE of your NormAl SenSITiVITy
- **SmooTh zoOm FUNCTIoN** - CHAnGe THe sMOothing FunCTIoN uSeD In THe SMOoth zoOmInG aNiMaTIoN.
- **ZoOM aDjUstMeNT** - ScrOll WhEN UsiNG optIFiNE'S zOOM TO adJUSt tHE zOOM LEVel.
- **ToGGLE tO zOOm** - maKE Optifine'S zoom Key A toggle InSTeaD oF ReQUiRING yOU TO HoLD it
- **SIMPLIFy fps cOuNTeR** - remOVE THe ADDItioNs oPTiFiNE L5 aNd abOvE mAkES tO tHE debug sCReeN FpS CoUNTEr. *default
- **rEMovE wAteR OvERLAy** - RemoVE THe WAtEr teXTURE OVerlAY when undeRwateR.
- **sHoW OwN nAMEtAG** - seE YOUr oWn NAmETAG In ThIRD peRsON.
- **cLEan View** - STOp renDeRinG yOuR OWn pOTIoN efFEcT paRTIcLes.
- **dIsaBle TEXt ShAdOW** - rEMoVE ShADoWs FrOM text. (CAN PoSiTivELY iMpAct peRforMaNCE).
- **AlteRnaTe TeXt shaDow** - ChanGE the TeXT sHADow TO ONly mOvE dowN RaTheR THAN MOviNg To THe sidE.
- **ADd TExt SHaDow TO NAMeTaGs** - rENDER nAmeTaG with shaDoWed TEXt.
- **NuMericAL EnCHAnTMenTs** - usE rEaDabLE numBers INsTEad OF Roman NUMeRAlS on enCHAnts. *DeFaULT
<div align = "center">

# Quality of Life

</div>

- **FIRe OveRlAy HEIght** - chANGE tHE hEIGhT Of tHe fIre OvErlay.
- **dAMaGe GlANCe** - ViEw tHe DAmAGE vaLUe oF tHE CUrRENTLy HelD iTem aboVe YoUR hOtbar. *deFaUlt
- **ITeM CoUNt glANCE** - VIew tHE aMoUNt OF thE CuRReNTlY hELd ITeM aBove YOUr hoTbAr. *dEFauLT
- **eNcHaNtMENt glANCe** - VIew THE eNChANTmENtS OF the currENtly Held ITem above yOUR hoTbAr. *DEFAulT
- **pROtEctIOn PErCeNTAGE** - VIew how muCh ToTAL Armor PROTeCtioN yOU HAVE iNsIde OF YOuR InVEntoRy. *DEFaULT
- **PrOJECtiLE prOteCtION PErCENTAGE** - viEw hOw mUCH TotAl pROJecTILE PrOtECTION You hAvE iNsiDe OF yOUR INVentOry. *DEfaULt
- **1.12 Farm SElECTIon boXEs** - repLAcE The selEctioN Box fOR CrOps wItH thE 1.12 vaRiAnt. (oNLY WorKs ON hYpiXEL & SINGLEpLAYEr.) *dEFAulT
- **LOG OPtimizEr** - DElEtE ANy fiLEs iN THE LOgS FOLder. aS tHIS uSUAlLy cAn tAKe up a loT OF spAce. (thESe FiLeS aRe NOT recOVERaBLe ONCE DElEted.)
- **lOG OTIMIzER AmOUnt** - ChoOse hoW MaNy days OLD A fILE must Be BeFOre dEletEd.
- **ImaGe prEvIeW** - pREViEW IMagE lInKS WHeN hoVerINg ovER A supporteD UrL. PREsS SHIFT TO uSE FullscreeN cONtROL to reNDEr in nAtIVE Image RESOlUTIon. (cUrRENtly SUPported: ImGUr, dISCoRd, BaDLiON SCreenSHOTs.)
- **IMaGe pREvIew wIDTH** - the % Of ScReEN WIdth TO Be usED foR IMaGe PREvIeW.
- **dISabLE AcHiEVeMentS** - rEMOve achiEVEMeNt nOTIficatioN.
- **StaRTuP notifiCATIon** - NOtIFy hOW LONG ThE gAMe toOK To StartUP With a NoTIFICAtION *dEfAULT
- **smArt discoNnECt -** cHOOsE BetwEen DIsCoNNectiNg OR reLOggING when CLICking THE DIsCoNnEct BUTTON. (OnlY WOrKS on mUlTIpLayeR seRVErs.)
- **nAuSea eFfEct** - REMove The NeTheR pORtAL apPEaRinG wHEN clearIng NAusEA.
- **CONtainEr BAckGROundS** - REmoVe tHE DARk baCkgroUNd iNSidE Of A cOnTaInEr.
- **InvEnTORy pOSItIoN** - stoP potIOn efFEcts fRoM sHifTinG YoUr InVeNtorY TO thE rIgHT. *deFaulT
- **fOV moDIfIeR** - alLow For mODiFYIng FOV ChAnGe stATes.
- **spRiNtinG FoV** - MODIFy yOUr fOV WHeN sPRInTIng.
- **Bow Fov** - ModIfY YOUR foV WHEN PuLLInG BAck A BOW.
- **SPEed fOV** - MoDIFY yOUR FOv WhEN HAVIng ThE Speed eFFECt.
- **sLOwneSS fOv** - MODiFY yOur fov When HavIng ThE SLOWneSS efFeCt.
- **remOVe WAtEr FOv** - REMOVE tHE cHaNGE Of fOV WhEN UnDerwatER (DoeS noT REquirE FOV modifiER TO be ENAbled)
- **REMOVE InVErTED colOrS FrOM cRossHair** - ReMOve THe INvErTED CoLOR EFfEct oN tHe CROSshAir.
- **CLEAN MaIN MeNu** - RemoVE tHE ReAlms BuTTON On THE maIN MenU AS you NeeD to be oN the laTeST MNecRAfT VERsiOn To use ReaLms. *defAulT
- **skin REFReshEr** - ADD a butToN TO THe Escape MEnu to RefREsh yOUR CURrent SKin WIthOUT NEeDiNG to LeAVE tHE sErVer. (aLso aCCesSiBlE WITh ThE coMmaNd "/refRESHSkiN".)
- **gui croSsHAIR** - SToP rendERING THE cRosShaIr When iN a GuI.
- **rEplacE oPEn tO lAN** - REMovE tHe Open To LaN ButtON whEn iN MuLtiplAYEr SeRver WItH A butTon to quicklY OPEN Your SErVER LISt. (Will be REWoRkED in ThE futurE to nOt KiCk yOu frOM thE SeRVer.)
- **repLACeD MoDs WARning** - DisPlay on StArtuP whAT MOds yOu MaY HavE tHat ArE RePLacED By pAtCHEr. *dEfAuLt
- **bETTer KeYbiNd HANDlING** - MAKE KEYs re-ReGisTEr WHEN cLoSiNg a Gui, likE IN 1.12+. *dEFAUlt
- fullBRighT - remove LIghTiNG uPDAtEs, InCReaSiNG VIsIbilItY. (REqUirEs ChUNK rEloAD (f3+a)). (CaN pOsItively iMpAct PErFOrmAnCE.) *deFAuLT
- **sMART fulLbRIghT** - aUtoMAtIcaLlY DisabLe THe FulLBriGht EFfeCT WheN USinG OPtIfINe sHadErs. (REQuirEs fULLBrIGHt)
- **sKy HeIght** - rEmOve ThE fLIckERING EffeCT FRom the voID wHEN PaSSING BETWeEN Y lEVeL 63. *defAULt
- **tab height** - MOVe ThE Tab OVerlAY DoWn N AmoUNt of pIxelS WHeN thERE'S AN AcTIvE boSsbar.
- **SET tAb hEIGHt** - cHoOSe HOw mANY Pixels Down the TaB WIlL gO whEN thERE'S aN aCTiVe BoSsBar
- **taB OpaCity** - alLOW fOR cUsTOmiZIng Tab opAciTy.
- **CuSToM TAB OPaCiTY** - ChAnge THe tAb list oPAciTY.
- **ToGgLE TAb** - Hold taB opeN wiThoUT NEEdiNG tO HOLD dOwN tHe tAb Key.
- **NuMBER PING** - Show A REaDabLe PiNg nUMBer iN TAB insTeAd Of bARS.
- **InsTaNT fUlLscREEN** (WINdoWs OnLy) - iNSTanT SwITchiNG beTWEEN FuLl screEn And NON FULLsCrEen mOdeS. (WInDOwED FULlscrEen mUSt aLsO be eNabLEd fOR tHis To WORK.)
- **wInDOwEd fUllSCreEN** - iMpLEMeNT wiNDowed fuLLscrEEN in MINecRaFT aLLOWinG you To DRaG Your MouSE oUtSIDE The WIndow
<div align = "center">

# Chat

</div>

- **CHAT kEepeR** - KEep cHAt WHEn tOgGlInG FUlLsCREEN. *dEFAult
- **cHAT PosiTiON** - MOvE ThE ChAT uP 12 PIXeLs tO STOp iT from oVeRlAPPIng ThE heAlTh bAR, aS DOne In 1.12+.
- **cOmPAcT cHAt** - clEAn Up cHaT By sTacKInG DupLicATe mESSAges (does not WOrK wItH labYMod.) *DEfAuLt
- **CoMPaCT CHaT tiMe** - CHaNGe HOw long BeFoRe OlD mEsSAGES are NO LoNGER CoMpAcTeD. (MeasurEd iN sEcONDs.)
- **croSS CHaT** - sTOp CLEariNG cHaT whEN SWiTcHiNG SERVERS. *DEfault
- **sAFe chaT ClICks** - sHow the cOMMmaNd Or lINK THat is RAN/oPeNEd On CliCK.
- **ShifT chAt** - hOldING ShIft wHiLe PReSSing eNtER WIll kEEp chat oPeN.
- **tRAnSPArEnT cHat** - remoVE The BaCkGROunD frOm chAt. (cAn POsItIvEly ImpaCT PeRfoRmance)
- **TRaNSpArENT CHat inpUt FIElD** - rEMOve tHE BACkgroUNd fRoM CHAT's iNPUt FIeld. (cAn PoSItIveLy IMPACT PerFoRMAnCE)
- **aNti cLeaR CHat** - REMOvE BLaNK MeSsaGeS frOm Chat.
- **Chat tiMESTAMpS** - aDd tIMesTAmps BEFore A MEssAGe.
- **cHAT TiMESTampS forMaT** - CHANGe THE TIMe Format oF cHAT tiMestAMPS, exAMPlEs: [3:24 PM] sTevE: HEY!, [15:24] stEvE: hey!
<div align = "center">

# Screenshot

</div>

- **No feEDbACk** - REMovE The MesSAGEs FRoM SCReenshots EntIREly.
- **CompACt rESPOnsE** - ComPact THe meSsagE giVen whEn scrEENshoTtiNG.
- **sCREenSHOt ManAgER** - ChaNge tHe waY ScrEenShotTInG wOrKs aS A WhOLe, cReatiNg a wHoLE NEW pRocEsS TO ScrEensHOTTing SuCH aS upLoaDing tO IMGuR, COPYING to cliPbOArD, Etc. *dEFaULT
- **prEViEw tiMe** - ADjust How lONG tHE PrevIew ShOuLD stAy On sCREen bEFORE slIdING Out. TiMe Is MeasurEd In sEcONdS.
- **preVIEW ScALE** - CHAngE thE sCaLE of The prEvIeW. sMalLeR NuMbER is BiggEr.
- **sCReEnSHOt PrEVIEW** - PReVIew tHE LOOk of yOUr SCREENSHOt when TaKEN iN The BOTToM riGht corNEr.
- **pREVIEw ANImAtion** - SELECT aN anIMatioN styLE foR THe scREensHOt prEvIeW.
- **aUTo COpY ScrEENShot** - aUToMAtIcally COpy ScREenSHOTS to the CLIPBOarD WhEN TakEN
<div align = "center">

# Patcher FunFacts

</div>

- **Fastchat**, **Fast Language Swap**, **Better Keybind Handling** pretty much all **OptiFine zoom stuff** were added by Llamalad7 along with fixing ssmanager by making it take priority over VanillaEnhancements since it completely broke it

- **Fire Overlay Height** option was originally named Fire Height then got renamed with the release of Patcher 1.1 beta 1

- **Downscale Pack Images** option was originally named Pack Images then later on got renamed with the release of Patcher 1.1 beta 7

- With the release of Patcher 1.1 beta 9 they Renamed /blacklist to /pblacklist and Removed /history alias to name history later on in Patcher 3 beta 16 they Renamed /name to /pname due to it potentially messing up normal server/client commands

- In Patcher 3 beta 14 the disable armorstands option's description was extended to note that this setting will also disable most NPC names on most servers due to a ton of idiots complaining 

- In Patcher 1.3.1 beta 1 the Blaze Culling Algorithm was released which performs some extra checks to see if entities are hidden behind others to not render anything to later on get removed in 
Patcher 1.4 beta 1 then integrated in entity culling after it being redone in Unknown Patcher Version

- Speaking of Patcher 1.4 beta 1 this version had 24+ vanilla bugs that were reported there is others that were unreported including the hitbox rendering of Cactus after x/z +/// 1677216, and other related floating precision point issues.

- In Patcher 1.4 beta 6 the file size got reduce by an incredible amount from 3.3mb to ~600kb by asbyth requesting permission from sk1er to bundle coroutines and caffeine then removing them from the Patcher jar

- In Patcher 1.5 beta 3 they Removed Chunk Lighting Fix due to complaints of stuttering 

- The Compact Chat rewrite and Limit Chunk Updates were pretty much done by [Moulberry](moulberry.codes/)
---
## Patcher has 49 Default options and 136 options in general, 16 of those are bug fixes, (note that those are the only bug fixes that you can enable and disable there is over 70 bug fixes which are force enabled) 41 QOL features and 41 Performance features (note that again those are the only visible ones) and Patcher also [replaces](https://github.com/LunaNotdev/Patcher-Explanation#mods-patcher-replaces) 17 mods

## Patcher also had/has options that arent in the config which are 

- **Scoreboard Patch** - which fixed log spam but now is force enabled 
- **Scoreboard Optimization** - Render the whole scoreboard in one draw call, rather than creating a separate rectangle for every score. which at the time wasnt compatible with Powns & Canelex's scoreboard mod.
- **Disable Constant Fog Color Checking** - still a thing but renamed to static fov color which simplifies fog color creation with a static fog color.
- **Startup Optimization** - Don't refresh resources twice during startup.
- **PathFinding optimization** (Cleanup blockaccess once processed).
- **TileEntity optimization** (cleanup removable tile//entities).
- **Cleanup resources when leaving a world**, fixing a vanilla OpenGL buffer leak.
- **Optimizations made to GameRules$Value and EntityOtherPlayerMP**.
- **Improve faster annotation searching**.
- **Rewrote data table search**.
- **Fix typo in Forge's mod list** by changing "Search:\\" to "Search:".
- **Note that this is all public information and there is many many stuff that are in the code but are not made public**.

## Known Planned features for patcher
- **Entity backface culling** -  hides parts of the entity model that you cant see.
- **Chat timestamps on hover** - Show timestamp for messages when you hover over them like [this](https://i.imgur.com/pR3aDv4.png) **(this isnt a concrete example its just to show the idea of what the final feature might look like)**
- **Fixed Entity Culling trying to cull particles causing some performance issues**
- **The ability to change entity render distance separately per category, globally, players, hostile mobs, passive mods**
- **Fix Scoreboard fix not fixing Scoreboard log spam bug**
- **1.12.2 Farm Selection Boxes now supports the hypixel.io ip**
- **Fix z-fighting issues with fluid stitching**
- **Fix some** [**formatting issues**](https://media.discordapp.net/attachments/485175582854873132/799656306599919636/unknown.png)
- **Fixed some smooth lighting issues** - Fix [this](https://media.discordapp.net/attachments/728064513605369866/820918408643870720/unknown.png).
- **Port chat send delay** - Port the new chat send delay feature [Example](https://imgur.com/a/ewt6Gq1).
- **Improvements related to resource pack discovery menu** - Unknown.
- **Horse transparency when riding it** - Like [this](https://media.discordapp.net/attachments/411620521382510592/803366568658337812/unknown.png) and [this](https://media.discordapp.net/attachments/411620521382510592/803369980405219388/unknown.png) .
-  **Added unfocused fps & sound volume** - Mostly unknown but i assume unfocused fps means when the game is unfocused you have a slider to lock fps to reduce unneeded performance hogging and a slider for volume when the game is unfocused.
- **Fixed DebugFPS feature killing performance** - The feature to debug fps significantly [drops fps](https://media.discordapp.net/attachments/728064513605369866/820912978500386866/unknown.png) by a ton and its now fixed, [Line responsible](https://media.discordapp.net/attachments/411620521382510592/801545071568748584/unknown.png), [Before](https://media.discordapp.net/attachments/411620521382510592/801550165474541630/unknown.png), [After](https://media.discordapp.net/attachments/411620521382510592/801550190536294470/unknown.png).
- **Renamed anti clear chat to remove blank messages**
- **Renamed container backgrounds to remove container backgrounds**
- **Reworked a lot of option descriptions**
- **Force enabled some options** - Unknown
## Mods patcher replaces
[CaseCommands](https://sk1er.club/mods/case_commands) - Sk1er LLC

[CommandPatcher](https://sk1er.club/mods/command_patcher) - Sk1er LLC

[CompactChat](https://sk1er.club/mods/compactchat) - Sk1er LLC

[CrossChat](https://sk1er.club/mods/cross_chat) - Sk1er LLC

[Frames+](https://frames.sk1er.club/) - Sk1er LLC

[ItemOptimizations](https://sk1er.club/mods/item_optimization) - Sk1er LLC

[MouseBindFix](https://sk1er.club/mods/mousebindfix) - Sk1er LLC

[ResourceExploitFix](https://sk1er.club/mods/resourceexploitfix) - Sk1er LLC

[WindowedFullscreen](https://sk1er.club/mods/sk1er_fullscreen) - Sk1er LLC

[CleanView](https://www.curseforge.com/minecraft/mc-mods/cleanview) - LainMI

[FastChat](https://2pi.pw/mods/fastchat) - 2Pi

[MemoryFix](https://prplz.io/memoryfix/) - prplz

[MouseDelayFix](https://prplz.io/mousedelayfix/) - prplz

[NoCloseMyChat](https://hypixel.net/threads/forge-modification-noclosemychat-for-mc-1-8.1260752/) - Cecer

[VanillaEnhancements](https://www.curseforge.com/minecraft/mc-mods/vanilla-enhancements) - OrangeMarshall

[VoidChat](https://skyerzz.com/minecraft/mods/voidchat/) - skyerzz

[BetterScaledGUI](https://www.youtube.com/watch?v=E1VsQ3-xkF8) - Moulberry

# Credits to [Asbyth](https://gist.github.com/asbyth/bcdb67d8f0ed18878c3916f15f4ddf9b)
<div align = "center">

# The End.

</div>
