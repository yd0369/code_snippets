# code_snippets

#### Vector Elements Swap Function
```cpp
void swap(const int &a, const int &b, vector<int> &v) {
        int tmp;
        tmp = v[a];
        v[a] = v[b];
        v[b] = tmp;
}
```
