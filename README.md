Rangkuman Week1



Unix Commad Line

 
 •	Shell
Agar bisa terhubung dengan komputer maka user akan memerlukan penerjemah. Maka dari itu user memerlukan yang namanya shell. Definisi shell secara harfiah sendiri adalah program yang digunakan untuk berkomunikasi atau memerintah sistem.

•	CLI (Command Line Interface)
Merupakan sebuah program yang memungkinkan user mengetik perintah atau command yang akan mmemerintahkan perangkat komputer untuk melakukan suatu tugas tertentu.

•	Terminal
User dan komputer dihubungkan dengan namanya terminal, yaitu tempat/aplikasi dimana user dapat mengetikan atau memberikan suatu perintah. Disinilah tempat dimana shell akan berperan.


Command


  	pwd (print working directory), fungsinya untuk melihat current working directory

  	Dir (directory), untuk melihat directory

  	Cd (change directory), untuk berpindah dari satu direktori ke directory lain

  	Is (list), untuk melihat isi file di dalam directory

  	Touch, untuk membuat file directorycp (copy), untuk menyalin file directory

  	Mv (move), untuk memindahkan file directory

  	Rm (remove), untuk menghapus file directory


Git & GitHub(GIT adalah Tools untuk programmer)



GIT 

  sebagai Version Control System (dalah mencatat setiap perubahan pada File)Git adalah aplikasi yang dapat melacak setiap perubahan yang terjadi pada suatu folder atau file.Git biasanya digunakan oleh para programmer sebagai tempat penyimpanan file pemrograman mereka, karena lebih efektif.File -file yg disimpan menggunakan git akan terlacak seluruh perubahannya, termasuk siapa yang mengubah.


•	Github
Merupakan vendor penyedia layanan git yang dimiliki oleh microsoft atau secara definisi merupakan layanan hosting berbasis web sebagai repositori git.


WHY’ should use GIT and Github?


   Dengan menggunakan GIT dan Github, kamu akan bisa bekerja dalam sebuat tim. Tujuan besarnya adalah kamu bisa berkolaborasi mengerjakan proyek yang sama tanpa harus repot copy paste folder aplikasi yang terupdate.

Setup Awal GIT

 •	Konfigurasi git
 

 •	Melihat hasil konfigurasi dengan git config –list
 

 •	Membuat Repository
 

 •	git init (dilakukan didalam folder yang dibuat)
 

 •	git Status digunakan untuk melihat apakah terjadi perubahan atau tidak pada Git
 

 •	git add untuk menambah file baru/file yang telah diubah pada Git
 

 •	git remote menghubungkan remote repository dengan project local yang telah kita buat direktorinya
 

 •	git commit -m commit message digunakan untuk menyimpan perubahan pada Git
 

 •	git push-u origin master digunakan untuk mengirimkan/perubahan file ke remote repository git branch-b [nama branch] digunakan untuk membuat branch baru
 

 •	git checkout digunakan untuk berpindah branch
 

 •	git merge digunakan untuk menggabungkan branch cabang ke branch master



DEFINISI HTML

HTML adalah singkatan dari Hypertext Markup Language. HTML digunakan untuk menampilkan konten pada browser.Contoh konten yang dapat ditampilkan seperti Text, Image, Video, Link, dan masih banyak lainnya.


 • Tools yang dibutuhkan untuk untuk membuat HTML yaitu web browser dan code editor 
 • Visual Studio Code merupakan salah satu code editor yang dibuat oleh Misrosoft
 • Keunggulan dari Visual Studio Code yaitu Intellisense, Run and Debug, Built in Git, Extensions
 • HTML Structure
     
 
 
Contoh tag HTML


Tag HTML

• Untuk menampilkan tulisan miring/tebal

	<b></b>
	<i></i>
 
• Untuk membuat tulisan dengan link

	<a href=""></a>
 
• Untuk menampilkan gambar

	<img src=""></img>
 
• Untuk membuat paragraph
	<p></p>




CSS



Cara Menggunakan CSS


•	
Inline Styles

Kita menambahkann CSS  langsung pada atribut HTML
 
 
 
 <p style="color:red">Tulisan ini berwarna merah</p>
 
 
• Internal CSS

Kita menggunakan element/tag <style> untuk menyisipkan kode CSS.element/tag <style> diletakkan di dalam element <head>
 
                <!DOCTYPE html>
         <html>
          <head>
            <title>Website Pertamaku</title>
            <style>
              body {
                background-color: yellow;
              }
              h1 {
                color: blue;
              }
              p {
                color: red;
              }
            </style>
          </head>
          <body>
            <h1>Website Pertamaku</h1>
            <p>Selamat Datang</p>
          </body>
        </html>
 
 
•Eksternal CSS

Kita akan menyisipkan kode CSS dengan cara membuat file CSS terpisah, 	dan lalu menyambungkannya dengan file HTML dengan menggunakan 	element . Element tersebut diletakkan di dalam element





• CSS Syntax


CSS Syntax adalah syntax yang digunakan untuk menunjuk 	atau memilih HTML element mana yang ingin diberi style 	(dihias). CSS syntax terdiri dari selector, property, dan value.
 
 
Syntaxnya seperti ini:


p {
	
  color: blue;
	
}


	
 flexbox
	
• Flexbox adalah suatu cara untuk mengatur layout atau tata letak
	
	
• Flexbox terdiri 1 parent (container) dan bisa beberapa child
	
	
•Flex di rection digunakan untuk mengatur letak child
	
	
• Flex wrap mengatur tata letak child pada 1 line
	
	
• Flex flow yaitu digunakan sebagai shortcut untuk set up flex-direction dan flex-wrap secara bersamaan
	
	
• Order digunakan untuk ordering item yang ingin diatur posisinya
	
	
• Justify content digunakan untuk mengatur täta letak antar item child secara horizontal
	
	
• Align content digunakan untuk mengatur tata letak antar item child secara vertikal atau cross axis
	
	
• Flex-grow digunakan untuk mengatur size suatu item child pada flexbox
	
	
• Flex-shrink digunakan untuk memperkecil size suatu item child secara relatif terhadap item child lamnya
	

	
	

    
 Algoritma dan Struktur Data
   

	
	
Algoritma
	
	
• Algortima Adalah deskripsi berupa step-step yang dibutuhkan untuk menyelesaikan suatu masalah. Untuk menyelesaikan suatu masalah, tentunya kita harus mempunyai data struktur, nah data inilah yang akan kita gunakan untuk menyelesaikan suatu masalah dengan menggunakan algoritma.
	
	
 
• Mengapa kita memerlukan algoritma?
	
Manfaat algoritma antara lain:
	
	
o Membantu menyederhanakan suatu program yang rumit dan juga besar.
	
	
o Mempermudah pembuatan program yang dapat menyelesaikan masalah tertentu.
	
	
o Membantu menyelesaikan suatu masalah dengan logika dan juga sistematis.
	
	

Kualitas Algortima
	
	
Kualitas wajib dari algoritma
	
	
	
o Input dan output harus didefinisikan terlebih dahulu dengan tepat
	
	
o Setiap step harus benar-benar clear dan tidak ambigu
	
	
o Algoritma seharusnya tidak mengandung suatu code pada bahasa pemograman tertentu.
	
	
o Algoritma harus dibuat agar dapat digunakan dalam bahasa pemograman apapun.
	
	
	

Soal

Buatlah Algoritma untuk menyelesaikan problem ini
David memiliki program yang membutuhkan untuk convert data dari jumlah jam ke detik



Contohnya jika program memiliki input 2 jam maka output yang diharapkan adalah 7200 detik

	
	
Jawaban
	
	

	Mulai

	Deklarasi variabel n, hasil_convert

	Menambahkan nilai n

	Melakukan proses (n jam = n \* 3600" lalu disimpan ke dalam hasil_convert

	Menampilkan hasil convert (n jam) = + "detik"

	Stop



Panduan menulis pseudocode: 
	
	
• Huruf kapital digunakan untuk menulis perintah
	
• 1 statement hanya terdiri dari 1 baris
	
• Menggunakan indentasi
	
• Harus bersifat spesifik dan simple
	
	
	
	Pseudocode berdasarkan kondisi masalah


	rocedural
	
	

Procedural adalah cara berpikir secara runtun. Artinya serangkaian perintah yang berurutan.
	
	

Contoh :
	
	

	

		STORE "width" with any number
		STORE "height" with any nummber
		STORE "area" without any value

		CALCULATE "width" times "height"
		SET "area" value with calculation result
		DISPLAY "area"

	
	
Conditional
	
	
	

Conditional digunakan saat dibutuhkan percabangan kasus. Komputer akan melakukan suatu tindakan jika suatu kondisi terpenuhi.
	
	
	

Jika hari ini tidak hujan, maka Bob pergi ke pasar,jika tidak maka Bob dirumah aja.
	
		IF "bright"
		DO "go to the market"
		ELSE
		DO "stay at home"
	
	
	
	
Looping
	
	
	

Komputer dapat melakukan sebuah proses yang sama berulang-ulang.
	
	

Jika membutuhkan perulangan dalam kasus tertentu, kita bisa menggunakan Looping.

	
Contoh :

	
			STORE "count" t0 1

			WHILE "count" < 11
			DISPLAY "count"
			CALCULATE "count" mod 2
			STORE "reminder" value with calculation result
			IF "reminder" equals to 0
			DISPLAY "EVEN!"
			ELSE
			DISPLAY "ODD!"
 

												
												
Recursive
												
												

Recursive adalah pola pikir dalam algoritma yang memanggil method/function didalam sebuah function

												
												
												
												
												
												
Javascript
												
												
										
• Menjalankan Javascript
												
												

Javascript dijalankan melalui browser pada device setiap user Umumnya browser Chrome dan Mozilla yang sudah support untuk semua fitur Javascript.

												
Console Log
												
												
Console Log adalah hal yang krusial bagi developer web. Console log adalah tempat kita untuk cek logic pemograman web yang kita kembangkan Console log juga tempat kita untuk melakukan debugging (mengetahui error pada code) pada pemograman web.
												
												
												


	
Ada 6 tipe data fundamental pada Javascript
												
												
											
•Number  :  Tipe data number adalah tipe data yang mengandung semua angka termasuk angka desimal.
												
												
• String : Tipe data string adalah grup karakter yang ada pada keyboard laptop/PC kita yaitu letters (huruf), number (angka), spaces (spasi), symbol, dan lainnya.
												
												
• Boolean : Tipe data boolean adalah tipe data yang hanya mempunyai 2 buah nilai.
		2 buah nilai tersebut adalah TRUE (benar) or FALSE (salah).

												
• Null : 
												
1.Tipe d ata null adalah tipe data yang diartikan bahwa sebuah variable/data tidak memiliki nilai.
												
2. Null berbeda dengan string kosong. String kosong masih memiliki tipe data string.
												
• Undefined : Tipe data undefined adalah tipe data yang merepresentasikan varibel/data yang tidak memiliki nilai.Undefined berbeda dengan null.
												
												
• Object : Tipe data object adalah koleksi data yang saling berhubungan (related). Tipe data pbject dapat menyimpan data dengan tipe data apapun (number, string, boolean, dan lainnya).Tipe data object mempunyai key dan value.
												

												
												
												
																																					
•	Variabel
	
	
		Disemua bahasa pemograman, variable adalah container/tempat untuk menyimpan sebuah nilai

												
												
•	Ada 6 tipe data fundamental pada Javascript
												
												
•	number
												
												
•	string
												
												
•	boolean
												
•	null
												
												
•	undefined
												

												
•	Object
												
		
												
												
Operator
												
												
•Assignment Operator (=)
		 										
• Mathematical Assignment Operator
												
• Arithmetic Operator
												
• Logical Operator
												
												
												

• CONDITIONAL
												
												
Conditional merupakan statement percabangan yang menggambarkan suatu kondisi. Conditional statement akan mengecek kondisi spesifik dan menjalankan perintah berdasarkan kondisi tersebut Yang dicek adalah apakah kondisi tersebut TRUE (benar).Jika TRUE maka code didalam kondisi tersebut dijalankan.

												
												
												
LOOPING
												
												
Looping adalah statement yang mengulang sebuah instruksi hingga kondisi terpenuhi atau jika kondisi stop/berhenti tercapai.


FOR LOOP
												
												
 merupakan instruksi pengulangan yang dapat kita berikan pada program yang kita kembangkan. Gunakan FOR LOOP jika kita tahu seberapa banyak nilai pasti untuk pengulangannya

												
WHILE LOOP
												
												
WHILE LOOP akan menjalankan instruksi pengulangan kondisi bernilai TRUE. Gunakan WHILE LOOP jika kita tidak mengetahui jumlah pasti pengulangan.


DO WHILE 
Terkadang kita ingin setidaknya menjalankan pengulangan 1 kali sebelum dilakukan pengecekan kondisi Jika kita membuat looping didalam looping. Maka ini dinamakan Nested Loop.
Looping pertama dianalogikan sebagai baris.
Looping kedua dianalogikan sebagai kolom

												
												
												
												
												
