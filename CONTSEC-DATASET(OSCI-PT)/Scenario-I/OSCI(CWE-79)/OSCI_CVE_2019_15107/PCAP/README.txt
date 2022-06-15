- Aynı CVE-ID (CVE_2019_15107) 'ye sahip 3 atağın ayrı ayrı ardışık(single) olacak şekilde birer kez düzenlendiği senaryonun (Scenario-I) testlerinin tek sefer çalıştırmasının sonucunda elde eilen PCAP dosyalarını içermektedir.


144.122.71.217 (Attacker1)
144.122.71.208 (Attacker2)
144.122.71.213 (Attacker3)


cd PCAP
sudo tcpdump -i eno1 src 144.122.71.217 and dst 144.122.71.18 -vv -w CVE-2019-15107_Attacker1.pcap

cd PCAP
sudo tcpdump -i eno1 src 144.122.71.208 and dst 144.122.71.18 -vv -w CVE-2019-15107_Attacker2.pcap

cd PCAP
sudo tcpdump -i eno1 src 144.122.71.213 and dst 144.122.71.18 -vv -w CVE-2019-15107_Attacker3.pcap
