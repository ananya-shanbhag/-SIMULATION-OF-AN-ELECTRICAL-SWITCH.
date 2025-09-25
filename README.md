# -SIMULATION-OF-AN-ELECTRICAL-SWITCH.
#include <stdio.h>
void main() {
    int light_switch;
    printf("To turn the light ON enter 1 or enter 0 to turn the light OFF\n");
    scanf("%d",&light_switch);
    if(light_switch==1){
        printf("Light is ON");
    
    }
    else if(light_switch==0) {
        printf("Light is OFF");

    }
    else{
        printf("Error invalid input\n");
    }
}
