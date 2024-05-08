# TUTORIAL - 9
## Refleksi

__1.2 Understanding how it works__
![image](https://github.com/rhaken/Timer/assets/39646450/31bd8964-dfcf-4e80-b881-7ea5fb5e979e)



Berdasarkan hasil outputnya, dapat dipahami bahwa fungsi async akan dieksekusi di luar fungsi utama yang memanggilnya. Sebagai hasilnya, kemungkinan outpul " ... hey hey" akan muncul sebelum ".. howdy!" dan "... done!" karena kode "... hey hey" berada di luar fungsi async. 

Ini terjadi karena program akan melanjutkan eksekusi dan mencetak "hey hey" sedangkan fungsi async masih menunggu hasil dari future.
