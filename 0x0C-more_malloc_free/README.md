## Quiz questions 
<br>
<br>

### Question #0 

To allocate enough space for an array of 10 integers (on a 64bit, Linux machine), I can use:

    malloc(64 * 10)

    malloc(10 * int)

    malloc(10 * sizeof(int))

---
### Question #1
 Question #1

What will you see on the terminal?

    int main(void)
    {
    int *ptr;

    *ptr = 98;
    printf("%d\n", *ptr);
    return (0);
    }
<br> 
     
    Segmentation Fault

    0

    98

    It doesn’t compile
    
   ---

## Question 2
malloc returns an address?

    False

    True

---
## Question 3
The memory space reserved when calling malloc is on:

    The heap

    The stack

---
## Question 4
You can do this:

free("Best School");

    No

    Yes
---
## Question 5
You can do this:

    char *s;

    s = strdup("Best School");
    if (s != NULL)
    {
    free(s);
    }
<br>

    No

    Yes

---
## Question 6
If I want to copy the string “Best School” into a new space in memory, I can use this statement to reserve enough space for it (select all valid answers):

    malloc(strlen(“Best School”))

    malloc(sizeof(“Best School”) + 1)

    malloc(12)

    malloc(strlen(“Best School”) + 1)

    malloc(sizeof(“Best School”))

    malloc(11)


---
## Question 7

What is wrong with this code:


    
    int cp(void)
    {  
    char *s;

    s = malloc(12);
    strcpy(s, "Best School");
    return (0);
    }

<br> 

    malloc can fail so we should check its return value all the time before using the pointers returned by the function.

    You don’t have enough space to store the copy of the string “Best School”

    There is no comment

    You can’t call strcpy with a string literal

---
## Question 8 
malloc returns a pointer

    False

    True

---
## Question 9
You can do this:

    char str[] = "Best School";

    free (str);

<br>

    No

    Yes
---
---

# Answers

|zero|one|two|three|four|five|six|seven|eight|nine|
|---|---|---|---|---|---|---|---|---|---|
|`malloc(10 * sizeof(int))`|` Segmentation Fault`|`false`|`The heap`|`No`|`Yes`|`malloc(12) & alloc(sizeof(“Best School”)&malloc(strlen(“Best School”) + 1)`|`malloc can fail so we should check its return value all the time before using the pointers returned by the function &&There is no comment`| `true`|`yes`|
