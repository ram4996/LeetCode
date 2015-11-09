class Stack {
public:
    // Push element x onto stack.
    void push(int x) {
        Stack *tmp = new Stack;
        tmp->data = x;
        tmp->next = head;
        head = tmp;
    }

    // Removes the element on top of the stack.
    void pop() {
        if(!head) return;
        head = head->next;
    }

    // Get the top element.
    int top() {
        return head->data;
    }

    // Return whether the stack is empty.
    bool empty() {
        if(!head) return 1;
        else return 0;
    }
    
private:
    int data;
    Stack *next;
    Stack *head = NULL;
};
