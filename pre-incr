#include<iostream>
using namespace std;
class A
{
    int x;
    public:
    void input();
    A operator++();
    void output();
};
void A::input()
{
    cout<<"\n Enter a  no:";
    cin>>x;
}
 A A::operator++()
{
    A o;
    o.x=++x;
    return o;
}
void A::output()
{
    cout<<"\n given value="<<x;
}

int main()
{
    A m,n;
    m.input();
    cout<<"\nEnter 1st object:";
    m.output();
    n=++m;
    cout<<"\nnext objext:";
    n.output();
    cout<<"\n 1st object value:";
    m.output();
    return 0;
}
