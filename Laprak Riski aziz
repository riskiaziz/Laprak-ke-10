class Node:
    def __init__(self, data):
        self.data = data
        self.next = None

class LinkedList:
    def __init__(self):
        self.head = None

    def add(self, data):
        new_node = Node(data)
        if not self.head:
            self.head = new_node
        else:
            current = self.head
            while current.next:
                current = current.next
            current.next = new_node

    def show(self):
        current = self.head
        while current:
            print(current.data, end=" -> ")
            current = current.next
        print("None")

# Menghubungkan array ke linked list
array = [10, 20, 30, 40]  # Data dalam array
linked_list = LinkedList()  # Buat linked list kosong

# Memindahkan data dari array ke linked list
for item in array:
    linked_list.add(item)

print("Isi linked list:")
linked_list.show()
