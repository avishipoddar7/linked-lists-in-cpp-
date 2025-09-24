#include <iostream>
using namespace std;

class node {
public:
    int val;
    node* next;

    // constructor to initialize node
    node(int data) {
        val = data;
        next = NULL;
    }
};

int main() {
    // create 3 nodes
    node* n1 = new node(1);
    node* n2 = new node(2);
    node* n3 = new node(3);

    //link nodes together
    n1->next=n2;//1000->2000
    n2->next=n3;//2000->3000

    //n3 is null

    //print linked list
    node *temp = n1 ; //start from head
    while(temp!= NULL){
        cout <<temp->val <<" " ;
        temp=temp->next;

}
 cout<<endl;
    return 0;
}

//output 1000 2000 3000
