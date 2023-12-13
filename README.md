#include <stdio.h>

int main() {
    int plakaKodu;

    printf("Lütfen il plaka kodunu girin: ");
    scanf("%d", &plakaKodu);

    if (plakaKodu == 1) {
        printf("İstanbul\n");
    } else if (plakaKodu == 34) {
        printf("İstanbul (Bağcılar, Güngören, Bahçelievler gibi ilçeler)\n");
    } else if (plakaKodu == 6) {
        printf("Ankara\n");
    } else if (plakaKodu == 35) {
        printf("İzmir\n");
    } else {
        printf("Bilinmeyen plaka kodu\n");
    }

    return 0;
}
