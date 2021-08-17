# Untitled

## 

{% tabs %}
{% tab title="C++" %}
```cpp
Conditional Statements
```
{% endtab %}

{% tab title="Code" %}
```cpp
#include <iostream>

using namespace std;

int main(){
    int inp;

    cin>>inp;

    switch(inp){
        case 1:
            cout<<"one";
            break;
        case 2:
            cout<<"two";
            break;
        case 3:
            cout<<"three";
            break;
        case 4:
            cout<<"four";
            break;
        case 5:
            cout<<"five";
            break;
        case 6:
            cout<<"six";
            break;
        case 7:
            cout<<"seven";
            break;
        case 8:
            cout<<"eight";
            break;
        case 9:
            cout<<"nine";
            break;
        default:
            cout<<"Greater than 9";
            break;
    }
}
```
{% endtab %}
{% endtabs %}

{% tabs %}
{% tab title="C++" %}
```
Pointer
```
{% endtab %}

{% tab title="Code" %}
```cpp
#include <stdio.h>
#include <math.h>

void update(int *a,int *b) {
    // Complete this function 
    *a = *a + *b;
    *b = (*a) - 2*(*b);  
    *b = abs(*b); 
}

int main() {
    int a, b;
    int *pa = &a, *pb = &b;
    
    scanf("%d %d", &a, &b);
    update(pa, pb);
    printf("%d\n%d", a, b);

    return 0;
}
```
{% endtab %}
{% endtabs %}



