{\rtf1\ansi\ansicpg1252\cocoartf2822
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fnil\fcharset0 .SFNS-Regular_wdth_opsz180000_GRAD_wght2580000;\f1\fnil\fcharset0 HelveticaNeue;\f2\fnil\fcharset0 .SFNS-Regular_wdth_opsz110000_GRAD_wght2580000;
\f3\fnil\fcharset0 AppleColorEmoji;\f4\froman\fcharset0 Times-Roman;\f5\fnil\fcharset0 .SFNS-Regular_wdth_opsz140000_GRAD_wght2580000;
}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;\red255\green255\blue255;}
{\*\expandedcolortbl;;\cssrgb\c0\c0\c0\c90196;\cssrgb\c100000\c100000\c100000;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid1\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid1}
{\list\listtemplateid2\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid101\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid2}
{\list\listtemplateid3\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid201\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid3}
{\list\listtemplateid4\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid301\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid4}
{\list\listtemplateid5\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid401\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid5}
{\list\listtemplateid6\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid501\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid6}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}{\listoverride\listid2\listoverridecount0\ls2}{\listoverride\listid3\listoverridecount0\ls3}{\listoverride\listid4\listoverridecount0\ls4}{\listoverride\listid5\listoverridecount0\ls5}{\listoverride\listid6\listoverridecount0\ls6}}
\paperw11900\paperh16840\margl1440\margr1440\vieww28900\viewh15200\viewkind0
\deftab720
\pard\pardeftab720\sa320\partightenfactor0

\f0\b\fs48 \cf2 \cb3 \expnd0\expndtw0\kerning0
Introduction\
\pard\pardeftab720\sa640\partightenfactor0

\f1\b0\fs32 \cf2 As part of my continuous learning in cloud computing, I recently completed a practical project on 
\f2\b Microsoft Azure
\f1\b0  where I deployed a 
\f2\b high-availability web infrastructure
\f1\b0  using 
\f2\b two Virtual Machines (VMs)
\f1\b0  and a 
\f2\b Load Balancer
\f1\b0 . This hands-on experience helped me understand how traffic can be automatically distributed and redirected to ensure uninterrupted service.\
\pard\pardeftab720\partightenfactor0
\cf2 \
\pard\pardeftab720\sa320\partightenfactor0

\f0\b\fs48 \cf2 Project Overview\
\pard\pardeftab720\sa640\partightenfactor0

\f3\b0\fs32 \cf2 \uc0\u55357 \u56633 
\f1  
\f2\b Objective
\f1\b0 : To build a fault-tolerant web setup using Azure free-tier services by:\
\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa160\partightenfactor0
\ls1\ilvl0\cf2 \cb1 \kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Deploying 2 Linux-based virtual machines\
\ls1\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Installing Apache2 web servers with individual messages\
\ls1\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Distributing traffic via a public load balancer\
\ls1\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Monitoring traffic flow and availability using Azure Monitor\
\pard\pardeftab720\sa240\partightenfactor0

\f4\fs24 \cf0 \
\pard\pardeftab720\sa640\partightenfactor0

\f3\fs32 \cf2 \cb3 \uc0\u55357 \u56633 
\f1  
\f2\b Technologies Used
\f1\b0 :\
\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa160\partightenfactor0
\ls2\ilvl0\cf2 \cb1 \kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Azure Virtual Machines (Ubuntu 22.04 LTS)\
\ls2\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Azure Basic Load Balancer\
\ls2\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Azure Monitor & Log Analytics\
\ls2\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Apache Web Server\
\pard\pardeftab720\sa240\partightenfactor0

\f4\fs24 \cf0 \
\pard\pardeftab720\sa320\partightenfactor0

\f0\b\fs48 \cf2 \cb3 Implementation Steps\
\pard\pardeftab720\sa640\partightenfactor0

\f3\b0\fs32 \cf2 \uc0\u9989 
\f1  
\f2\b Created Resource Group
\f1\b0 : Grouped all resources for better management and cost tracking.\

\f3 \uc0\u9989 
\f1  
\f2\b Deployed Two Virtual Machines
\f1\b0 :\
\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa160\partightenfactor0
\ls3\ilvl0\cf2 \cb1 \kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Installed Apache2\
\ls3\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Configured custom web pages: \'93Hello from VM1\'94 & \'93Hello from VM2\'94\
\pard\pardeftab720\sa240\partightenfactor0

\f4\fs24 \cf0 \
\pard\pardeftab720\sa640\partightenfactor0

\f3\fs32 \cf2 \cb3 \uc0\u9989 
\f1  
\f2\b Configured Load Balancer
\f1\b0 :\
\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa160\partightenfactor0
\ls4\ilvl0\cf2 \cb1 \kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Setup health probe on port 80\
\ls4\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Added both VMs to backend pool\
\ls4\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Created load balancing rule to distribute web traffic\
\pard\pardeftab720\sa240\partightenfactor0

\f4\fs24 \cf0 \
\pard\pardeftab720\sa640\partightenfactor0

\f3\fs32 \cf2 \cb3 \uc0\u9989 
\f1  
\f2\b Monitored Traffic
\f1\b0 :\
\
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa160\partightenfactor0
\ls5\ilvl0\cf2 \cb1 \kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Used Azure Monitor to check logs and VM health\
\ls5\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Verified that stopping one VM redirected traffic to the other automatically\
\pard\pardeftab720\sa240\partightenfactor0

\f4\fs24 \cf0 \
\pard\pardeftab720\sa320\partightenfactor0

\f5\b\fs40 \cf2 \cb3 Insights Gained\
\pard\pardeftab720\sa640\partightenfactor0

\f1\b0\fs32 \cf2 \
\pard\tx220\tx720\pardeftab720\li720\fi-720\sa160\partightenfactor0
\ls6\ilvl0\cf2 \cb1 \kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Working with virtual networks and compute resources.\
\ls6\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Configuring and testing load balancer behavior \
\ls6\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Installing and managing web servers on Linux.\
\ls6\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Monitoring traffic patterns using Azure Monitor.s\
\ls6\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\uc0\u8226 	}\expnd0\expndtw0\kerning0
Troubleshooting permissions and SSH access issuezs\
\pard\pardeftab720\sa240\partightenfactor0

\f4\fs24 \cf0 \
}