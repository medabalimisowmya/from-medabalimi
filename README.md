# from-medabalimi
# Sowmya
###### Kho-Kho

This is a **paragraph**. Since my 5th standard I love playing **Kho-Kho game**, I play it very well . I am the captain of our school Kho-Kho team and our school team stood in the **first place** in the zones held all over the town in 2017.

---

### Ordered and Unordered lists
1. Virat 
2. Dhoni
3. jadeja
* Kolkata
* Hyderbad
* Bangalore

In detail [My Favorite Dish](MyDish.md)

---

### Table showing players and the game they are good at

By having a glance into the following table you can have an idea about the restaurants you can find in common all over the United States.

| Restaurant Name | Reason for Recommendation                              | Location       |
|-----------------|--------------------------------------------------------|----------------|
| MacDonald's     |For the way of diaplaying menu and easy way for ordering| Nation wide    |
| Subway          |For the customisable sandwiches                         | Nation wide    |
| Starbucks       |For the best taste of coffee and tea                    | Nation wide    |
| Taco Bell       |Because of its late-night menu                          | Nation wide
 
 ---

 > "The fool doth think he is wise, but the wise man knows himself to be a fool."

 > "A fool thinks himself to be wise, but a wise man knows himself to be a fool."

 > *Author:Shakespeare*

 ---

Below is the python code which exlains the abstraction method. In this code there is a class named BaseClass and an abstract method is delcared.

 ```
 from abc import ABCMeta, abstractmethod
class BaseClass(metaclass=ABCMeta):
    @abstractmethod
    def foo(self):
        pass

    @abstractmethod
    def bar(self):
        pass

class ConcreteClass(BaseClass):
    def foo(self):
        pass

    def bar(self):
        pass

instance = ConcreteClass() 
```
[You can find he code snippet here](https://code.pieces.app/collections/python)