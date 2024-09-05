#include <stdio.h>
float u,v,a,t;
int main() {
    printf("u: ");
    scanf("%f", &u);
    printf("v: ");
    scanf("%f", &v);
    printf("a:");
    scanf("%f", &a);
    t=(v-u)/a;
    printf("t:%.2fs\n",t);
    return 0;
}
