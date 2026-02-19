# CS50-PSET-1.2
Problem Set 1.2

#include <stdio.h>
#include <cs50.h>

int main(void)
{
    int h;
    do
    {
        h = get_int("Height: ");
    }
    while (h < 1 || h > 8);

    for (int i = 0; i < h; i++)
    {
            for (int s = 0; s < h - i - 1; s++)
            {
                printf(" ");
            }
            for (int j = 0; j < i + 1; j++)

            {
                printf("#");
            }
            printf("\n");
    }
}
