# MultiPar

v1.3.1.0 is public

 This version has a new feature; 1-pass processing File IO at creating recovery files. 
It will read source data once, when source files exist on HDD. 
Also, it will write recovery data once, after the data is calculated. 
As compared to old 2-pass processing mode, 
1-pass processing mode is faster on a slow drive (such like HDD) by decreasing file access. 
jetelina promoted [this idea on issue page](https://github.com/Yutaka-Sawada/MultiPar/issues/3). 
Thanks jetelina and Slava46 for their help. 

 Because this new implementation isn't tested so much, there may be a bug or problem. 
It should work mostly, but I might mistake something or would forget rare case. 
Be careful to use this for important usage. 
If someone finds a bug, an odd behavior, or a strange problem, 
please report me by e-mail or GitHub issue page. 
I will fix, solve, or support as possible as I can. 


[ Changes from 1.3.0.7 to 1.3.1.0 ]

* GUI update  

Change  
 It supports different output style of new PAR2 client.  

* PAR2 client update  

New  
 At creation, 1-pass processing File IO is possible for source files on HDD.  

Change  
 GPU encoder will write recovery data on files after finish encoding.  
 On Windows 7 or later, it may recognize SSD for faster processing.  

Bug fix  
 It might fail to allocate memory, when free memory was few or fragmented.  


[ Hash value ]

MultiPar1310.zip  
MD5 : 92A1665AD5DA10E9AC56AE682A61EE69  
SHA-1 : EE60349EB5F6AEF0CD388E6336011B5018B7D06D  

MultiPar1310_setup.exe  
MD5: 3CD232E49859AB5A510E79CBFB74B6D0  
SHA1: 06D86D57C5D88CD659EF531F75E694DFEB99D666  



[ Hash value of other source code packages ]
 Old versions and source code packages are available at [OneDrive](https://1drv.ms/u/s!AtGhNMUyvbWOaSo1n_R8awJ_hg0?e=4V0gXu) now.  

MultiPar_par2j_1310.7z  
MD5: AE58C04D40D72B4169BE3C60FDCF88EA  
SHA1: F8C890197312174D854B6FC6AEA2393B96EDCE87  

MultiPar_par2j_2pass_1310.7z  
MD5: A62518006207385436D03DB85AA8C3DC  
SHA1: 31647749D1DC1322DA71FAFDC4B3562EBE2F4AAD  

MultiPar_par2j_extra_1294.7z  
MD5: 6D165CDA2645924ACAFE902F02FAD309  
SHA1: D77D4EA778423D5D8F820B8EAF97F733950F9FB1  

MultiPar_par1j_1300.7z  
MD5: 6C38E0E713D3D68D398C9A51363D153E  
SHA1: 33675AF52D58B350792937FFBAD55C5401B06EAA  

MultiPar_sfv_md5_1300.7z  
MD5: 284A62C612F8FAF6325E258845ECA645  
SHA1: C2F4F136571083EEDB0713D0B42E58EE36CF1805  

MultiPar_ShlExt_1298.7z  
MD5: BE0F04DF1A6B936F23F6F01930562248  
SHA1: 52818266B45ECE135EECFF12D8DA2640A6AD5075  

MultiPar_ResUI_1306.7z  
MD5: 94533C7023ECC1EBBF695553E1A76E49  
SHA1: 90B329BF1EA54D74CD85F39EEDC9B2A8CF7125FE  

MultiPar_Help_1307.7z  
MD5: B9BA3E9E06A6F5C79C32CB88C96AEC08  
SHA1: E7B2D5D0CD6B9704D0D9B9BEE803C9E5EC20F42F  

