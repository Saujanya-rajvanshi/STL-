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
