 Destination Port numarası ve Source IP Adres bilgileri doğrudan label ile eşleştiğinden, trainde kullanımamasıgerekmektedir, Bana göre Flow ID,	Src IP,	Src Port, Dst IP,Dst Port, ve Tmestamp, kolonlarının tamamının trainde kullanılmaması daha doğru olacak gibi ama, bir bilene sormak lazım!



- Aynı CWE_ID (OSCI) kategorisindeki CVE-ID (CVE_2019_15107, CVE_2019_16662) 'ye sahip toplamda 6 atağın rastgele ardışık(serial) olacak şekilde birer kez arda düzenlendiği senaryonun (Scenario-III) testlerinin 4 ayrı çalıştırmasının sonucunda elde eilen Flow dosyalarını içermektedir.

- test&train için dosyalar uc uca eklenerek kullanılabilir.


- Port bilgisi doğrudan sınıflandırma için kullanılabilir, (Scenario-II için manuel label kolonlarını yetiştiremedim ama port no bilgisinin kontrolü daha kolay zaten, onu label olarak kullanabilirsiniz)

	CWE-22

	CVE-2020-17518  ->    port:30006
	CVE-2021-26086  ->    port: 30010


	CWE-78

	 CVE-2019-15107  ->   port: 30003
	 CVE-2019-16662  ->    port: 30004 


- İKİ CWE kategorisini classify etmek (CWE-22,  CWE-78)
