#include <stdio.h>

int main() {
    float r, luas_lingkaran;
    float phi = 3.14;

    printf("=== Program Menghitung Luas Lingkaran ===\n");
    
    // Input nilai r
    printf("Masukkan nilai jari-jari (r): ");
    scanf("%f", &r);

    // Proses perhitungan luas lingkaran (pi * r * r)
    luas_lingkaran = phi * r * r;

    // Output hasil sesuai ketentuan
    printf("\n--- Hasil Perhitungan ---\n");
    printf("Nilai r              : %.2f\n", r);
    printf("Nilai Luas Lingkaran : %.2f\n", luas_lingkaran);

    return 0;
}
