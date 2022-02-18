# hse_hw1_meth

Целью данного домашнего задания является изучение глобального изменения уровня CpG метилирования ДНК при раннем эмбриональном развитии мыши. Считается, что при развитии эмбриона происходят так называемые волны деметилирования-метилирования, т.е. на ранних стадиях CpG метилирование уменьшается до некоторого минимума (около 25%), а затем по мере дифференцировки тканей, оно сильно увеличивается (около 90%) и остается таким на протяжении всей жизни организма.


Для выполнения данной задачи мы будем изучать следующие образцы WGBS (Whole genome bisulfite sequencing), соответствующие разным стадиям эмбрионального развития мыши:

SRR5836473 - 8cell – 8-клеточный эмбрион, примерно 2.25 дня после оплодотворения яйцеклетки

SRR5836475 - ICM – внутренняя клеточная масса бластоциста, примерно 3.5 дня после оплодотворения яйцеклетки

SRR3824222 - Epiblast – стадия эпибласта, примерно 6.5 дней после оплодотворения яйцеклетки

# 1. FastQC

Отчёт FastQC показал отклоения по 3 параметрам.

***1) Per base sequence content (SRR5836473_1/SRR5836473_2)***

![image](https://user-images.githubusercontent.com/93263861/154757782-2d4bb201-cee8-4511-9d2b-2953fd0249f5.png)

![image](https://user-images.githubusercontent.com/93263861/154758487-5c20cb7e-1a7a-4c16-aba7-e10c6e200aff.png)


***2) Per sequence GC content (SRR5836473_1/SRR5836473_2)***

![image](https://user-images.githubusercontent.com/93263861/154757824-6052d54c-ded1-45b6-ad94-931b195e7abe.png)

![image](https://user-images.githubusercontent.com/93263861/154758520-e39579a2-d2e7-4539-b4c8-31102954c91c.png)


***3) Sequence Length Distribution (SRR5836473_1/SRR5836473_2)***

![image](https://user-images.githubusercontent.com/93263861/154757906-f76b23b8-7075-4521-a2c3-6876f8d493f4.png)

![image](https://user-images.githubusercontent.com/93263861/154758554-28b577db-15bf-46f6-81eb-fc5f3f0f3605.png)



# 2. a, b)

***a) Число ридов, закартированных на участки 11347700-11367700; 40185800-40195800.***

***b) Процент дуплицированных прочтений в каждом из образцов. (Бонус)***

![image](https://user-images.githubusercontent.com/93263861/154711269-42a75855-6b63-492a-8565-d3dd24a5730e.png)


# d) M-bias plot.

***SRR3824222***

![image](https://user-images.githubusercontent.com/93263861/154754977-d1183588-3e69-4419-a811-534ab69240a5.png)

![image](https://user-images.githubusercontent.com/93263861/154755003-691814f8-f440-456b-b528-5e459a97d8f4.png)


***SRR5836473***

![image](https://user-images.githubusercontent.com/93263861/154754843-e8edc312-18b5-4327-9741-39a106fe4cff.png)

![image](https://user-images.githubusercontent.com/93263861/154754886-afd33deb-5e2a-493b-b3d7-99a8c26f8b3a.png)


***SRR5836475***

![image](https://user-images.githubusercontent.com/93263861/154754705-42eb85a6-74d3-450b-b73a-73d1ce4a51fd.png)

![image](https://user-images.githubusercontent.com/93263861/154754735-768edba8-b700-4821-b2d0-e1e4956196df.png)


# e) Гистограммы распределения метилирования цитозинов по хромосоме 

![image](https://user-images.githubusercontent.com/93263861/154755553-4f37fc42-fab0-431b-9b5b-c910ec3244c1.png)


![image](https://user-images.githubusercontent.com/93263861/154755523-4e2a9c92-1c2d-4ed7-bb54-c9fa46980b39.png)


![image](https://user-images.githubusercontent.com/93263861/154755494-ebdd8b68-ece1-4536-aa4e-a494b5868c94.png)


# f) pyGenomeTracks

***Метилирование***
![image](https://user-images.githubusercontent.com/93263861/154756195-31f98798-881f-477d-af80-0151c144dcf6.png)

***Покрытие***
![image](https://user-images.githubusercontent.com/93263861/154756554-ebca998a-0492-4c82-aeb5-754a7c8413df.png)
