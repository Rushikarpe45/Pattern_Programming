# Pattern_Programming
# H
for i in range(5):
    for j in range(5):
        if j == 0 or j == 4 or i == 2:
            print("*", end="")
        else:
            print(" ", end="")
    print("  ", end="")  
    
    # E
    for j in range(5):
        if i == 0 or i == 2 or i == 4 or j == 0:
            print("*", end="")
        else:
            print(" ", end="")
    print("  ", end="")

    # L
    for j in range(5):
        if j == 0 or i == 4:
            print("*", end="")
        else:
            print(" ", end="")
    print("  ", end="")

    # L
    for j in range(5):
        if j == 0 or i == 4:
            print("*", end="")
        else:
            print(" ", end="")
    print("  ", end="")

    # O
    for j in range(5):
        if (i == 0 or i == 4) or (j == 0 or j == 4):
            print("*", end="")
        else:
            print(" ", end="")
    print()


*   *  *****  *      *      *****
*   *  *      *      *      *   *
*****  *****  *      *      *   *
*   *  *      *      *      *   *
*   *  *****  *****  *****  *****
