
># Vectores de Ataque - La inseguridad de las redes inalámbricas
>Con el uso creciente de tecnologías de comunicación inalámbrica, como la identificación por radiofrecuencia (RFID), Bluetooth Low Energy (BLE), ZigBee y las redes celulares, el riesgo de ataques por radiofrecuencia (RF) se ha convertido en una preocupación importante para la privacidad y la seguridad.

> La tecnología inalámbrica es una poderosa tecnología central que permite nuestra infraestructura digital global. Las redes Wi-Fi son susceptibles a ataques en WEP (Wired Equivalent Privacy), el acceso protegido por Wi-Fi (WPA) y WPA2. Estas firmas de ataque se pueden perfilar en un sistema que se defiende contra tales ataques sobre la base de sus características inherentes.

>Las vulnerabilidades de las redes móviles ad hoc (MANET) lo hacen sujeto a un gran número de ataques. Con el fin de comprender la naturaleza y el comportamiento de tales ataques, se han propuesto muchos esquemas de clasificación y taxonomías para los ataques MANET. Este documento propone una nueva taxonomía para los ataques MANET. La taxonomía tiene como objetivo proporcionar un medio consistente para clasificar los ataques, así como permitir que el conocimiento previo se aplique a nuevos ataques y proporcionar una forma estructurada de ver dichos ataques.

>## SDR
>Radio definida por software o SDR ( del Inglés Software Defined Radio) es un sistema de radiocomunicaciones donde varios de los componentes típicamente implementados en hardware (mezcladores, filtros, moduladores/demoduladores, detectores, etc) son implementados en software, utilizando un ordenador personal u otros dispositivos de computación embebidos.

> A continuación se presentan algunos trabajos académicos, repositoris de GitHub, videos y otra información relacionada con ataques a medios de comunicación inalámbricos
> 

|Título/Title  |Resumen/Abstract  |
|--|--|
| [A technical review of wireless security for the internet of things: Software defined radio perspective](https://www.sciencedirect.com/science/article/pii/S1319157821000896) | This paper presents a review of the vulnerabilities on [wireless technologies](https://www.sciencedirect.com/topics/computer-science/wireless-technologies "Learn more about wireless technologies from ScienceDirect's AI-generated Topic Pages") that gives connectivity to IoT, and the experiences using  [Software Defined Radio](https://www.sciencedirect.com/topics/computer-science/software-defined-radio "Learn more about Software Defined Radio from ScienceDirect's AI-generated Topic Pages") SDR for implementing  [wireless attacks](https://www.sciencedirect.com/topics/computer-science/wireless-attack "Learn more about wireless attacks from ScienceDirect's AI-generated Topic Pages")  to IoT technologies are assessed |
|[breaking-into-software-defined-radio](https://bishopfox.com/blog/breaking-into-software-defined-radio)|In this article, we’ll review the hardware and software components you need for a functional SDR setup without spending a fortune. Then, we’ll go into demoing the software so you’re set up for success. And finally, we’ll show you how you can begin reverse engineering radio signals once you have the right foundation in place.|
|[rtl-sdr](https://osmocom.org/projects/rtl-sdr/wiki)|rtl-sdr turns your Realtek RTL2832 based DVB dongle into a SDR receiver|
|[Attacks Against Industrial Machines via Vulnerable Radio Remote Controllers: Security Analysis and Recommendations](https://www.trendmicro.com/vinfo/us/security/news/vulnerabilities-and-exploits/attacks-against-industrial-machines-via-vulnerable-radio-remote-controllers-security-analysis-and-recommendations)|In our research and vulnerability discoveries, we found that weaknesses in the controllers can be (easily) taken advantage of to move full-sized machines such as cranes used in construction sites and factories. - [Download paper](https://documents.trendmicro.com/assets/white_papers/wp-a-security-analysis-of-radio-remote-controllers.pdf)|


## Repositorios de GitHub
|Título/Title|Resumen/Abstract  |
|--|--|
| [EMEye_Tutorial](https://github.com/longyan97/EMEye_Tutorial) | This repository is the tutorial of eavesdropping on camera video from camera circuit's electromagnetic (EM) leakage, which is presented in the NDSS'24 paper "**EM Eye: Characterizing Electromagnetic Side-channel Eavesdropping on Embedded Cameras**" |
| [rtl-sdr](https://github.com/osmocom/rtl-sdr)|rtl-sdr turns your Realtek RTL2832 based DVB dongle into a SDR receiver|
|[Universal Radio Hacker - URH](https://github.com/jopohl/urh)|The Universal Radio Hacker (URH) is a complete suite for wireless protocol investigation with native support for [many](https://github.com/jopohl/urh/wiki/Supported-devices) common **Software Defined Radios**.|
|[deep-tempest](https://github.com/emidan19/deep-tempest)|In this project we have extended the original [**gr-tempest**](https://github.com/git-artes/gr-tempest) (a.k.a. [Van Eck Phreaking](https://en.wikipedia.org/wiki/Van_Eck_phreaking) or simply TEMPEST; i.e. spying on a video display from its unintended electromagnetic emanations) by using deep learning to improve the quality of the spied images.|

## Ejercicio práctico - copiado de señal de control remoto

**Videos de ejercicio**



## Videos SDR

**Video Introducción**

 - [SDR Basics for HACKERS!](https://www.youtube.com/watch?v=wa8mnAGm-vk)

 **UHR**
 - [Universal Radio Hacker - 01: Record a signal](https://www.youtube.com/watch?v=kuubkTDAxwA&list=PLlKjreY6G-1EKKBs9sucMdk8PwzcFuIPB)
 - [Universal Radio Hacker - 02: Interpretation](https://www.youtube.com/watch?v=QqVvEOzKPCs&list=PLlKjreY6G-1EKKBs9sucMdk8PwzcFuIPB&index=2)
 - [Universal Radio Hacker - 03: Analysis](https://www.youtube.com/watch?v=IF-tO1wMDUg&list=PLlKjreY6G-1EKKBs9sucMdk8PwzcFuIPB&index=3)
 - [Universal Radio Hacker - 04: Generation (bad audio quality)](https://www.youtube.com/watch?v=ODJRpDTxFvs&list=PLlKjreY6G-1EKKBs9sucMdk8PwzcFuIPB&index=4)
 - [Universal Radio Hacker - 05: Simulation](https://www.youtube.com/watch?v=j8vce1jujrM&list=PLlKjreY6G-1EKKBs9sucMdk8PwzcFuIPB&index=5)
 - [A Security Analysis of Radio Remote Controllers for Industrial Applications](https://youtu.be/XY7MDhE3tfE)
 - [Analyzing Vulnerabilities in Industrial Radio Frequency Protocols](https://youtu.be/WXHVA9gGh4o)

**Aplicaciones prácticas**

- [Easvesdropping on HDMI with TEMPESTSDR and SDRplay](https://www.rtl-sdr.com/easvesdropping-on-hdmi-with-tempestsdr-and-sdrplay/) - [Video](https://youtu.be/Z_VmQXZP9Vw)
- [Deep-Tempest: Eavesdropping on HDMI via SDR and Deep Learning](https://www.rtl-sdr.com/deep-tempest-eavesdropping-on-hdmi-via-sdr-and-deep-learning/)
- [How To Replay RF Signals Using SDR](https://www.blackhillsinfosec.com/how-to-replay-rf-signals-using-sdr/)
- [Passive GSM Sniffing with Software Defined Radio](https://payatu.com/blog/passive-gsm-sniffing-with-software-defined-radio/)
- [HACKING GSM SIGNALS WITH AN RTL-SDR AND TOPGUW](https://www.rtl-sdr.com/hacking-gsm-signals-with-an-rtl-sdr-and-topguw/)

**Infraestructuras físicas**

[RFDIDS: Radio Frequency-based Distributed Intrusion Detection System for the Power Grid](https://repository.gatech.edu/server/api/core/bitstreams/9d196e8b-35cb-47ed-a185-d252cd21c807/content)
[Shekari slides](https://www.ndss-symposium.org/wp-content/uploads/ndss2019_07A-2_Shekari_slides.pdf)


>## Artículo Técnicos

| Título/Title |Resumen/Abstract  | Año|
|--|--|--|
| [The Insecurity of Wireless Networks](https://www.researchgate.net/publication/260635283_The_Insecurity_of_Wireless_Networks) | The article discusses methods of intrusion detection and prevention in the context of cyberphysical protection of critical Internet infrastructure. The basis for this research is a specialized (and undoubtedly incomplete) taxonomy of Wi-Fi attacks and their adaptations to existing countermeasures and protocol revisions. Ultimately, this article aims to provide a clearer picture of how and why wireless protection protocols and encryption must achieve a more scientific basis for detecting and preventing such attacks.  |2012|
[Universal Radio Hacker: A Suite for Analyzing and Attacking Stateful Wireless Protocols](https://www.usenix.org/system/files/conference/woot18/woot18-paper-pohl.pdf) | In this paper, we present the Universal Radio Hacker (URH), an open source tool which is designed for protocol analysis from the ground up and implements a full workflow including interfaces for SDRs, intuitive demodulation, customizable decodings, fuzzing support and a simulation component|2018|
|[Resistance to Replay Attacks of Remote Control Protocols using the 433 MHz Radio Channel](https://ceur-ws.org/Vol-3654/paper9.pdf) |This study focuses on the analysis of replay attacks, which pose a significant risk to remote control systems using the 433 MHz radio frequency band. Proceedings of the Workshop Cybersecurity Providing in Information and Telecommunication Systems (CPITS 2024), Kyiv, Ukraine, February 28, 2024 ([online](https://ceur-ws.org/Vol-3654/paper9.pdf)). Edited by: Volodymyr Sokolov, Vasyl Ustimenko, Tamara Radivilova, Mariya Nazarkevych. Submitted by: Volodymyr Sokolov. Published on CEUR-WS: 20-Mar-2024. [ARCHIVE](http://sunsite.informatik.rwth-aachen.de/ftp/pub/publications/CEUR-WS/Vol-3654.zip)|2024|
|[EM Eye: Characterizing Electromagnetic Side-channel Eavesdropping on Embedded Cameras](https://www.rtl-sdr.com/em-eye-eavesdropping-on-security-camera-via-unintentional-rf-emissions/)|This repository is the tutorial of eavesdropping on camera video from camera circuit's electromagnetic (EM) leakage, which is presented in the NDSS'24 paper "**EM Eye: Characterizing Electromagnetic Side-channel Eavesdropping on Embedded Cameras**"|2024|
|[Unlocking Security Risks: Exploring Vulnerabilities inSoftware-Defined Radio with RTL-SDR](https://www.ijraset.com/research-paper/unlocking-security-risks-exploring-vulnerabilities-in-software-defined-radio-with-rtl-sdr)|This study illustrates potential avenues for exploitation by utilizing RTL-SDR dongles to reveal Software-Defined Radio's (SDR) vulnerabilities. Using replay attacks, the study reveals the weakness of car key unlocking techniques, concentrating on static codes.|2024|
|[Frequency Attack](https://www.sciencedirect.com/topics/computer-science/frequency-attack)|Frequency attack is a type of hardware-based attack where attackers use variations in frequency to extract sensitive information from a biometric device.|2023|
|[The Impact of Radio Frequency (RF) Attacks on Security and Privacy: A Comprehensive Review](https://www.researchgate.net/publication/375622124_The_Impact_of_Radio_Frequency_RF_Attacks_on_Security_and_Privacy_A_Comprehensive_Review)|This paper provides a comprehensive review of the impact of RF attacks on security and privacy. We start by providing an overview of RF attacks and their potential impacts on different types of wireless systems, including RFID/NFC, ADS-B, BLE, ZigBee, cellular networks, satellite communication, and 433/315 MHz communication.|2023|


## Otros vínculos
[https://www.kali.org/tools/rtlsdr-scanner/](https://www.kali.org/tools/rtlsdr-scanner/)
[INCIBE - SDR and its role in cybersecurity](https://www.incibe.es/en/incibe-cert/blog/sdr-and-its-role-cybersecurity)


>## Noticias de ataques por RF
>
>### Ataques sector industrial
>[RAM Signals Expose Air-Gapped Networks to Attacks](https://www.bankinfosecurity.com/ram-signals-expose-air-gapped-networks-to-attacks-a-26258)
>[New RAMBO Attack Uses RAM Radio Signals to Steal Data from Air-Gapped Networks](https://thehackernews.com/2024/09/new-rambo-attack-uses-ram-radio-signals.html)

>### Ataques sector militar
>[How Lebanon's wireless paging system was weaponized to make Hezbollah devices explode](https://www.voanews.com/a/how-lebanon-s-wireless-paging-system-was-weaponized-to-make-hezbollah-devices-explode/7791044.html)
>[How did Hezbollah’s pagers explode in Lebanon?](https://www.aljazeera.com/news/2024/9/17/how-did-hezbollahs-pagers-explode-in-lebanon)
>[Nine killed, 2,750 wounded across Lebanon as Hezbollah pagers explode](https://www.aljazeera.com/news/2024/9/17/dozens-of-hezbollah-members-wounded-after-pagers-explode-in-lebanon)
>[]()

>### Ataque sector médico

 - [The Guardian - Hacking risk leads to recall of 500,000 pacemakers due to patient death fears](https://www.theguardian.com/technology/2017/aug/31/hacking-risk-recall-pacemakers-patient-death-fears-fda-firmware-update) 
 - [CBS Morning - Health concerns loomed over Dick Cheney while in office](https://www.youtube.com/watch?v=JQY2QQ94Q-o&rel=0)
 - [I am the calvary - PATCH Act will Mark Significant Step in Regulating Medical Device Cybersecurity](https://iamthecavalry.org/2023/04/11/introduction-of-patch-act-will-mark-significant-step-in-regulating-medical-device-cybersecurity/)
 - [AHA | ASA - Pacemaker Recall Highlights Security Concerns for Implantable Devicese](https://www.ahajournals.org/doi/10.1161/CIRCULATIONAHA.118.037331)
