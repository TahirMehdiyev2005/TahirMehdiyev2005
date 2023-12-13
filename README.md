#include <stdio.h>

int main() {
    printf("3 ve 5'e tam bölünen, ancak 7'ye tam bölünmeyen sayılar (100 ile 200 arasında):\n");

    for (int i = 100; i <= 200; ++i) {
        if ((i % 3 == 0) && (i % 5 == 0) && (i % 7 != 0)) {
            printf("%d\n", i);
        }
    }

    return 0;
}
