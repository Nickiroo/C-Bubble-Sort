# C-Bubble-Sort
Sorting algorithm and swap method:

```
void sort(int *arr) {
    for (int i = 0; i < MAX-1; i++){
        for (int j = 0; j < MAX-1; j++) {
            if (*(arr+j) > *(arr+j+1)){
                swap(arr+ j,arr+j+1);
                printValues(arr);
            }
        }
    }
        
};

void swap(int *a, int *b) {
    int temp = *a;
    *a = *b;
    *b = temp;
};
```
