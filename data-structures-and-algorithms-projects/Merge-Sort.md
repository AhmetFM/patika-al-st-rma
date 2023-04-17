### [16,21,11,8,12,22]

[16,21,11] ---- [8,12,22] 1.Aşamada dizi ortadan ikiye bölünür.

[16] - [21,11] ----- [8] - [12,22] 2.Aşamada alt bölümler tekra ikiye bölünür.

[16] -[21] - [11] ---- [8] - [12]- [22] 3.Aşamada Dizi elemanları tekrar bölündü ve tek eleman olmuş oldu.

[16] - [11,21] ---- [8] - [12,22] 4.Aşamada sıralamaya başlandı

[11,16,21] ---- [8,12,22] 5.Aşamada bölümler tekrar kendi aralarında sıralandı.

[8,11,12,16,21,22] 6.Aşamada Sıralanarak tekrar birleştirildi.

##### Big-O Gösterimi: O(nlogn)