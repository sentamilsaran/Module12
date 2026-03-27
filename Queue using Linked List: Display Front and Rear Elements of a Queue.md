# 🔁 Queue using Linked List: Display Front and Rear Elements of a Queue

## 🎯 Aim

To write a Python program to:
- Insert elements into a queue.
- Display the element at the **front** of the queue.
- Display the element at the **rear** of the queue.

---

## 🧠 Algorithm

1. **Initialize Queue**:
   - Create an empty list called `queue`.

2. **Insert Elements**:
   - Use the `append()` method to add `'a'`, `'b'`, `'c'`, and `'d'` to the queue.

3. **Display Initial Queue**:
   - Print `"Initial Queue:"` followed by the current state of the queue.

4. **Identify Front and Rear**:
   - Set `front = queue[0]` for the front element.
   - Set `rear = queue[-1]` for the rear element.

5. **Print Results**:
   - Display the front and rear elements with appropriate messages.

---
## Program
Add code here
queue = []

queue.append('a')

queue.append('b')

queue.append('c')

queue.append('d')

print('Initial Queue: ' + str(queue))

print("\nElement at the front of the queue is .... ",queue[0])

print("\nElement at the rear of the queue is .... ",queue[-1])
## Output
<img width="800" height="208" alt="image" src="https://github.com/user-attachments/assets/e3725c78-e445-4107-b087-1b29bd83ab30" />

## Result
The program is excuted and verified.
