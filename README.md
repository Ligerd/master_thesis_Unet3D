# Application of Unet3D to predict individualized dose distribution in radiotherapy planning


1. Cel pracy (opis motywacji - radioterapia wiązką zewnętrzną, proces planowania radioterapii, próby jego uproszczenia)

2. Przegląd literatury - próby automatycznej generacji zindywidualizowanego rozkładu dawki

3. Wstęp teoretyczny

4. Opis wykorzystywanych danych - struktura, podział na zbiór uczący/walidacyjny/ testowy; ew. augmentacja danych

5. Architektura sieci Unet3D; metoda implementacji

6. Trening sieci - ustawienie odpowiednich parametrów rozmiar batcha, funkcja celu, liczba warstw (?) itp;

7. Ocena wyników: porównanie przy pomocy miar graficznych z referencją - mIoU, porównanie z wynikami uzyskanymi przez inną sieć ( rezultaty od nas); ew. wyliczenie miar klinicznych

8. Podsumowanie, wnioski


# Links
Artykuły:
https://arxiv.org/pdf/1606.06650.pdf

https://towardsdatascience.com/review-3d-u-net-volumetric-segmentation-medical-image-segmentation-8b592560fac1

https://towardsdatascience.com/review-u-net-biomedical-image-segmentation-d02bf06ca760

Code 
https://catalog.ngc.nvidia.com/orgs/nvidia/resources/unet3d_medical_for_tensorflow

DataSet for tests: 
https://github.com/as791/Multimodal-Brain-Tumor-Segmentation
