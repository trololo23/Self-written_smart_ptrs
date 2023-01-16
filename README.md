# Self-written-smart-ptrs

My own implementation of all smart pointers in C++ according to the C++20 standard

# Немного о проекте

Иногда объект, созданный на хипе, нужно передавать в кучу функций, методов, etc. В такой ситуации становится сложно уследить за лайфтаймом объекта и моментом, когда нужно освобождать выделенную под объект память.

Хотелось бы воспользоваться удобной обёрткой, которая автоматически выделит память при создании объекта и освободит память, когда объект больше не используется --- ровно для этого и существуют умные указатели.

Умные указатели бывают разные. В рамках этого задания мы рассмотрим три типа, которые отличаются между собой семантикой владения:
