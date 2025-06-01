# hse_hw4_hic

[Коллаб ноутбук](https://colab.research.google.com/drive/1jaBuN00Ibq3hNJOAwYeQ_hwRgd6ekIZW?authuser=2#scrollTo=ZH0mHx_sUTjS)

### Скриншоты HiGlass
<img width="1141" alt="Снимок экрана 2025-06-01 в 16 00 07" src="https://github.com/user-attachments/assets/a279da37-355d-4998-8943-856387cda735" />
<img width="1141" alt="Снимок экрана 2025-06-01 в 15 55 45" src="https://github.com/user-attachments/assets/acea4c09-3ae2-4954-be08-54819395cf48" />



### Сбалансированные матрицы

<p float="left">
  <img src="https://github.com/user-attachments/assets/3b00843b-6532-47f2-95ab-88f5577ce686" width="45%" />
  <img src="https://github.com/user-attachments/assets/2954be70-d5de-4498-8396-ce6d4897b53f" width="45%" />
</p>


### Таблицы *cooler dump*

<img width="1200" alt="Снимок экрана 2025-06-01 в 15 36 31" src="https://github.com/user-attachments/assets/c273b5b8-a9b1-484e-a430-9e9069ad7979" />

<img width="1200" alt="Снимок экрана 2025-06-01 в 15 36 37" src="https://github.com/user-attachments/assets/3f752a28-e0b1-4d5e-b090-c9ad60572882" />

### Таблицы с бинами 

<img width="213" alt="Снимок экрана 2025-06-01 в 15 39 11" src="https://github.com/user-attachments/assets/4c6b249e-4912-4528-8e77-9ffaae5df39c" />
<img width="213" alt="Снимок экрана 2025-06-01 в 15 39 06" src="https://github.com/user-attachments/assets/0a05e740-5f7c-49fa-b936-42285f61eab0" />

### Кривые зависимости число контактов от расстояния для выбранной хромосомы

![Unknown-4](https://github.com/user-attachments/assets/4459ae5b-5c77-435a-889d-5fa0ea271eca)

### Нахождение insulation score и границы тадов для выбранного участка для обоих файлов

| chrom | start     | end       | region | is_bad_bin | log2_insulation_score_50000 | n_valid_pixels_50000 | log2_insulation_score_75000 | n_valid_pixels_75000 | log2_insulation_score_125000 | n_valid_pixels_125000 | boundary_strength_50000 | boundary_strength_75000 | boundary_strength_125000 | is_boundary_50000 | is_boundary_75000 | is_boundary_125000 |
|--------|-----------|-----------|--------|-------------|-------------------------------|------------------------|-------------------------------|------------------------|-------------------------------|------------------------|--------------------------|--------------------------|--------------------------|-------------------|-------------------|---------------------|
| chr1   | 74875000  | 74900000  | chr1   | False       | -0.388939                     | 1.0                    | -0.335290                     | 6.0                    | -0.045276                     | 22.0                   | NaN                      | 1.237026                 | 0.189256                 | False             | True              | False               |
| chr1   | 74900000  | 74925000  | chr1   | False       | -0.108773                     | 1.0                    | -0.207536                     | 6.0                    | 0.022501                      | 22.0                   | NaN                      | NaN                      | NaN                      | False             | False             | False               |
| chr1   | 74925000  | 74950000  | chr1   | False       | -0.255332                     | 1.0                    | 0.060780                      | 6.0                    | 0.362265                      | 22.0                   | 0.146559                 | NaN                      | NaN                      | False             | False             | False               |
| chr1   | 74950000  | 74975000  | chr1   | False       | 0.482001                      | 1.0                    | 0.696801                      | 6.0                    | 0.726826                      | 17.0                   | NaN                      | NaN                      | NaN                      | False             | False             | False               |
| chr1   | 74975000  | 75000000  | chr1   | False       | 1.190109                      | 1.0                    | 0.901736                      | 6.0                    | 1.001950                      | 12.0                   | NaN                      | NaN                      | NaN                      | False             | False             | False               |


| chrom | start     | end       | region | is_bad_bin | log2_insulation_score_50000 | n_valid_pixels_50000 | log2_insulation_score_75000 | n_valid_pixels_75000 | log2_insulation_score_125000 | n_valid_pixels_125000 | boundary_strength_50000 | boundary_strength_75000 | boundary_strength_125000 | is_boundary_50000 | is_boundary_75000 | is_boundary_125000 |
|--------|-----------|-----------|--------|-------------|-------------------------------|------------------------|-------------------------------|------------------------|-------------------------------|------------------------|--------------------------|--------------------------|--------------------------|-------------------|-------------------|---------------------|
| chr1   | 74875000  | 74900000  | chr1   | False       | 0.177880                      | 1.0                    | -0.120521                     | 6.0                    | -0.009733                     | 22.0                   | NaN                      | 0.478515                 | 0.050967                 | False             | True              | False               |
| chr1   | 74900000  | 74925000  | chr1   | False       | 0.086876                      | 1.0                    | 0.003982                      | 6.0                    | 0.129577                      | 22.0                   | NaN                      | NaN                      | NaN                      | False             | False             | False               |
| chr1   | 74925000  | 74950000  | chr1   | False       | 0.041615                      | 1.0                    | 0.166647                      | 6.0                    | 0.316363                      | 22.0                   | 0.136265                 | NaN                      | NaN                      | False             | False             | False               |
| chr1   | 74950000  | 74975000  | chr1   | False       | 0.208833                      | 1.0                    | 0.467165                      | 6.0                    | 0.537672                      | 17.0                   | NaN                      | NaN                      | NaN                      | False             | False             | False               |
| chr1   | 74975000  | 75000000  | chr1   | False       | 0.381413                      | 1.0                    | 0.468778                      | 6.0                    | 0.800926                      | 12.0                   | NaN                      | NaN                      | NaN                      | False             | False             | False               |

##### 1 файл 

![Unknown-5](https://github.com/user-attachments/assets/9f646ae8-7d72-4e54-a79f-b10fd21e4bab)
<img width="943" alt="Снимок экрана 2025-06-01 в 15 27 18" src="https://github.com/user-attachments/assets/492a3bb7-8875-41ed-b5e7-80706aa7464c" />

![Unknown-7](https://github.com/user-attachments/assets/07d75527-3a0d-4685-acf3-fa1712c40748)


##### 2 файл 

![Unknown-8](https://github.com/user-attachments/assets/c465721a-58b9-4f53-8115-b859ffd92206)
<img width="943" alt="Снимок экрана 2025-06-01 в 15 27 46" src="https://github.com/user-attachments/assets/d0785ef8-659c-46ab-846e-3cf0c9bc3e88" />
![Unknown-9](https://github.com/user-attachments/assets/e01555d7-4dfe-42c7-909d-92ce97ae5d02)
![Unknown-10](https://github.com/user-attachments/assets/8cc8eaed-038f-4d25-a64e-6ca47784d806)


2 bed файла с границами ТАДов находятся в files 











