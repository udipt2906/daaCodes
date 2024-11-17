# PROGRAM TO CALCULATE DOT PRODUCT
## MATHEMATICAL EXPRESSIONS
### Dot product formula:
**$$ A \cdot B = \sum_{i=1}^{n} A_i \cdot B_i $$**
### Code Example:
```C++
vector<int> dotproduct(vector<int> a,vector<int> b){
    vector<int> ans;
    for(int i = 0;i<a.size();i++){
        ans.push_back(a[i]*b[i]);
    }
    return ans;
}
int main(){
    vector<int> a = {1,2,3};
    vector<int> b = {2,3,4};
    vector<int> ans = dotprod(a,b);
    for(int i = 0;i<ans.size();i++){
        cout<<ans[i]<<" ";
    }
}
```
## Example image
![Dot Product](https://upload.wikimedia.org/wikipedia/commons/thumb/3/3e/Dot_Product.svg/300px-Dot_Product.svg.png)

## DIFFERENT VERSION table
|  1 | 2  |
|---|---|
|  3 |  4 |
