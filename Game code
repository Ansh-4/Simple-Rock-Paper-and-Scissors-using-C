/*simple rock paper scissors game in c language*/
#include <stdio.h>
#include <math.h>
#include <stdlib.h>
#include <time.h>

/*funtion for win, losing or draw*/
int game(char player, char computer)
{
    /*using logical operators*/
    /*from this code all the draw outcomes will be accounted for*/
    
    /*returning -1 for draw, returnig 0 for a win and returning 1 for a lose*/
    
    if (player==computer)
    return -1;
    /*now for all the win and lose outcomes*/
    
    if (player=='s'&&computer=='p')
    return 0;
    else if (player=='p'&&computer=='s')
    return 1;

    if(player=='r'&&computer=='s')
    return 0;
    else if (player=='s'&&computer=='r')
    return 1;

    if (player=='s'&&computer=='p')
    return 0;
    else if (player=='p'&&computer=='s')
    return 1;
}

/*fuction calling code*/

int main()
{
    int n;
    char player, computer, result;

    srand(time(NULL));/*for generation of a random number*/
    n=rand()%100;
    /*making the random number less than 100*/

    if (n<33)
    computer='r';
    else if (n>33&&n<66)
    computer='p';
    else 
    computer='s';

    printf("Enter r for rock or p for paper and s for scissors : ");
    scanf("%c",&player);

    result=game(player,computer);

    if (result==-1) {
    printf("draw!");
    } 
    else if (result==0) {
    printf("You Win! :)");
    }
    else{
    printf("You lose! :(");
    }
    printf("Player chose : %c and computer chose : %c\n",player,computer);

    return 0;
}
