JavadaDogruB-linenYanlis
========================

Java'da metotlara gonderilen parametre tipi..
 Bilgi : Java tamamen call by value mantigiyla calisir . Call by
 *         referance mantigi bir yanılgıdır. Onemli olan nokta sudur ki :
 *         Primitif(int,long vs) tipler metotlara parametre olarak
 *         gonderildiginde nasil ki deger'i kopyalanir , nesne referansalari
 *         için de ayni durum soz konsudur . Nesne referansi , method icin
 *         olusturulan stack'e kopyalanir. Referans bir göstergedir (C'de
 *         pointer gibi) . Bir methoda referans deger kopyalandiginda toplam
 *         ayni seyi refere eden iki referans olusur . Method'da bu referans
 *         degiskeni ile yapilan degisikler , ayni seyi refere ettigi icin
 *         orjinal referans degiskeninde de etkisi gorülür . Cunki iki göstergeç
 *         de ayni şeyi gostermektedir. Java spesifikasyonunda gecen su cumle
 *         bunun kanitidir . " When the method or constructor is invoked
 *         (15.12), the values of the actual argument expressions initialize
 *         newly created parameter variables, each of the declared Type, before
 *         execution of the body of the method or constructor. The Identifier
 *         that appears in the DeclaratorId may be used as a simple name in the
 *         body of the method or constructor to refer to the formal parameter. "
 *         Simdi bir ornek yapalim :) . Ornegimiz'de iki tane overloaded method
 *         bulunuyor . Birine deger , birine referans kopyalacagiz ve sonuclari
 *         gorecegiz..Orneklerde goruldugu gibi iki islem de de degiskenin
 *         degerini degistirdik. Ama birisi degere , digeri referansa sahip buna
 *         dikkat edelim ... 
 *	   Calistigim ve yararlandigim kaynagi da ekliyeyim ,
 *         kaynak bildirmek bir erdemdir. 
 *	   Kaynak : http://www.kurumsaljava.com/2012/07/08/javada-bilinmeyenler/
