#include <iostream>
using namespace std;

class link {
public:
    int data;
    link* next;

    // constructor to initialize node
    link(int num) {
        data = num ;
        next = NULL;
    }
};
void insert_head(link*&head, int data){
    link* new_node = new link(data);
    new_node -> next=head ;
    head = new_node ;
}
void disp(link*head){
    link* temp =head;
    while(temp!=NULL){
        cout<<temp->data<<"-";
        temp=temp->next;
    }
    cout<<"NULL"<<endl;
}

int main() {

    link*head=NULL; //declare and intialize
    insert_head(head,30);
    disp(head);
    insert_head(head,32);
    disp(head);
    insert_head(head,35);
    disp(head);
}

/*
output
30-NULL
32-30-NULL
35-32-30-NULL
*/

