## Kudinova Svetlana

## Contacts
* Discord: Svetlana (LittleLovelySun)#7386
* E-mail: sd.kudinova@g,ail.com
* GitHub: LittleLovelySun

## Summary
Today I`m backend-programmer and I want to know more about other side of programming (pun: back-front). I want to study it in RSSchool!

## Skills
* Python
* Docker
* Git
* C
* C++

## Code example
[Codewars task](https://www.codewars.com/kata/551f23362ff852e2ab000037)

```python

def get_new_layer(layer, prev_layer):
    new_layer = layer

    for i in range(len(new_layer)):
        new_layer[i] += max(prev_layer[max(0, i - 1): i + 1])

    return new_layer

def longest_slide_down(pyramid):
    if len(pyramid) == 1:
        return pyramid[0][0]

    sum_pyramid = []
    for i, layer in enumerate(pyramid):
        if i == 0:
            sum_pyramid.append(layer)
            continue

        sum_pyramid.append(get_new_layer(layer, sum_pyramid[-1]))

    return max(sum_pyramid[-1]) 
```

## Experience
* 2020-now: python programmer - Ivannikov Institute for System Programming of the RAS 

## Education
* Bachelor, Bauman Moscow State Technical University
    + Computational mathematics and mathematical physics
* Coursera
    + [Machine Learning](https://www.coursera.org/learn/machine-learning/home/welcome)

## Language
* Russian: native
* English: B1
