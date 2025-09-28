# STL-
STL from DSA in cpp

### inserting one elem
```cpp
#include <iostream>
#include <vector>

using namespace std;

int main() {
    vector<int> vec; //0
    vec.push_back(1);
    cout << vec.size() << endl;
    return 0;
}
```
### inseting qn list of elem

```cpp
#include<iostream>
#include <vector>

using namespace std;

int main() {
    vector<int> vec = {1, 2, 3, 4, 5};
    for(int val:vec) {
        cout << val << " ";
    }
    cout << endl;
    return 0;
}

```
### second method of insertion 

```cpp
#include<iostream>
#include <vector>

using namespace std;

int main() {
    vector<int> vec(3, 10);
    for(int val: vec) {
        cout << val <<<<< val << " ";
        
    }
    cout << endl;
}

```

### remove first elem

```cpp
#include <iostream>
#include <vector>

using namespace std;

int main() {
    vector<int> vec = {1, 2, 3, 4, 5};
    vec.erase (vec.begin());
    for(int val: vec) {
        cout << val << 11 " ";
    }
    cout << endl;
    return 0;
}
```

```cpp
#include <iostream>
#include <vector>

using namespace std;

int main() {
    vector<int> vec = {1, 2, 3, 4, 5};
    vec.erase (vec.begin() + 1,vec.begin() + 3);
    for(int val: vec) {
        cout << val << " ";
    }
    cout << endl;
    return 0;
}
```

### insert a elem
```cpp
#include <iostream>
#include <vector>

using namespace std;

int main() {
    vector<int> vec = {1, 2, 3, 4, 5};
    vec.insert (vec.begin() + 1,100);
    for(int val: vec) {
        cout << val << " ";
    }
    cout << endl;
    return 0;
}
```
### clear vector 

```cpp
#include <iostream>
#include <vector>

using namespace std;

int main() {
    vector<int> vec = {1, 2, 3, 4, 5};
    vec.clear();
    for(int val: vec) {
        cout << val << " ";
    }
    cout << endl;
    return 0;
}
```

### size and capacity 
```cpp
#include <iostream>
#include <vector>

using namespace std;

int main() {
    vector<int> vec = {1, 2, 3, 4, 5};
    vec.clear();
    for(int val: vec) {
        cout << val << " ";
    }
    cout << endl;
    
    cout << "size : " <<vec.size() << endl;
    cout << "cap : " << vec.capacity() << endl;

    return 0;
}
```
### is empty 

```cpp
#include <iostream>
#include <vector>

using namespace std;

int main() {
    vector<int> vec = {1, 2, 3, 4, 5};
    vec.clear();
    for(int val: vec) {
        cout << val << " ";
    }
    cout << endl;
    
    cout << "is empty: " << vec.empty() << endl;

    return 0;
}
```

### returning a value

```cpp
#include <iostream>
#include <vector>

using namespace std;

int main() {
    vector<int> vec = {1, 2, 3, 4, 5};
    
    cout << "vec.begin: " << *(vec.begin()) << endl;
    
    return 0;
}
```

### vector end 
```cpp
//end return 0 as it points to location after the elements
#include <iostream>
#include <vector>

using namespace std;

int main() {
    vector<int> vec = {1, 2, 3, 4, 5};
    
    cout << "vec.end: " << *(vec.end()) << endl;
    
    return 0;
}

```

### inserting element through loop

```cpp
#include <iostream>
#include <vector>

using namespace std;

int main() {
    vector<int> vec = {1, 2, 3, 4, 5};
    
    vector<int>::iterator it;
    for(it = vec.begin(); it!=vec.end(); it++) {
        cout << *(it) << endl;
    }
    
    return 0;
}

for(auto it = vec.rbegin(); it!=vec.rend(); it++) {
    cout << *(it) << endl;
}
```


