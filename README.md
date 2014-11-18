Code-bahasa-C
=============
#include <stdio.h>
int main()
{

float tinggi;
float berat;
float ukuranBerat;
float bmi;
float bantu;
float kilo;

    printf("Program berat badan ideal dengan BMI (berat massa index)\n\n");
    printf("Masukan Tinggi Badan anda : "); scanf("%f",&tinggi);
    printf("Masukan Berat tubuh anda : "); scanf("%f",&berat);

        ukuranBerat =  (tinggi-100)-(0.1*(tinggi-100));
        printf("Ukuran berat = %f\n\n",ukuranBerat);
        bantu=(tinggi*0.01);
        bmi=(berat/(bantu*bantu));
        printf("ukuran bmi anda adalah %f\n\n",bmi);

if(bmi<16){
kilo=ukuranBerat-berat;
printf("untuk menjadi ideal anda harus punya berat plus minus 5kg dari %fKg\n",ukuranBerat);
printf("%f : bmi anda terlalu sangat kurus\n",bmi);
printf("anda harus menambah berat kilo %fkg\n",kilo);
}

else if(bmi<=16.99 && bmi>=16){
kilo=ukuranBerat-berat;
printf("untuk menjadi ideal anda harus punya berat plus minus 5kg dari %fKg\n",ukuranBerat);
printf("%f : bmi anda kurus naikkan  berat badan anda\n",bmi);
printf("anda harus menambah berat kilo %fkg\n",kilo);
}

else if(bmi<=18.49 && bmi>=17){
kilo=ukuranBerat-berat;
printf("untuk menjadi ideal anda harus punya berat plus minus 5kg dari %fKg\n",ukuranBerat);
printf("%f : bmi anda agak kurus naikkan berat badan\n",bmi);
printf("anda harus menambah berat kilo %fkg\n",kilo);
}

else if(bmi<=24.99 && bmi>=18.50){
printf("%f : bmi anda Normal, anda memiliki berat badan ideal\n",bmi);
}

else if(bmi<=29.99 && bmi>=25){
kilo=berat-ukuranBerat;
printf("untuk menjadi ideal anda harus punya berat plus minus 5kg dari %fKg\n",ukuranBerat);
printf("%f : bmi anda kegemukan, ayo turunkan berat\n",bmi);
printf("Anda harus mengurangi berat badan anda %fkilo\n",kilo);
}

else if(bmi<=34.99 && bmi>=30.0){
kilo=berat-ukuranBerat;
printf("untuk menjadi ideal anda harus punya berat plus minus 5kg dari %fKg\n",ukuranBerat);
printf("%f : bmi anda Obesitas kelas 1 , terlalu gemuk\n",bmi);
printf("Anda harus mengurangi berat badan anda %fkilo\n",kilo);
}

else if(bmi<=39.99 && bmi>=35){
kilo=berat-ukuranBerat;
printf("untuk menjadi ideal anda harus punya berat plus minus 5kg dari %fKg\n",ukuranBerat);
printf("%f : bmi anda berada di kelas 2, sangat-terlalu gemuk\n",bmi);
printf("Anda harus mengurangi berat badan anda %fkilo\n",kilo);
}

else if(bmi>=40){
kilo=berat-ukuranBerat;
printf("untuk menjadi ideal anda harus punya berat plus minus 5kg dari %fKg\n",ukuranBerat);
printf("anda sudah sangat gemuk sekali, sulit untuk ideal");
printf("Anda harus mengurangi berat badan anda %fkilo\n",kilo);
}

else{
printf("bukan manusia :D\n");
}
//printf("UKURAN UNTUK MENJADI IDEAL ADALAH %f \n",ukuranBerat);

}

