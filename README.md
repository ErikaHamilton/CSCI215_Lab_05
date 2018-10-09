# Lab_05
DOM manipulation

Name: Erika Hamilton

## DUE: 9 Oct 2018 @ 11:59 pm

## Instructions:
In this lab we'll use JavaScript to access to the DOM and dynamically add element, attribute, and text nodes. After completing each task result will look like the image in _____.


## Task 4:
 1. Using the `createElement` method, create a new ordered list (\<ol\>) node and then assign the returned node object to new variable named `olNode`.
 2. Using the `createElement` method, create a new list item (\<li\>) node and then assign the returned node object to a new variable named `liNode1`.
 3. Using the `createElement` method, create a new list item (\<li\>) node and then assign the returned node object to a new variable named `liNode2`.
 4. Using the `createTextNode` method, create a new text node with value "Read Assignment" and then assign the returned node object to a new variable named `liTextNode2`.
 5. Using the `createTextNode` method, create a new text node with value "Code Assignment" and then assign the returned node object to a new variable named `liTextNode2`.
 6. Using the `appendChild` method, append the child node `liTextNode1` to parent node `liNode1`.
 7. Using the `appendChild` method, append the child node `liTextNode2` to parent noed `liNode2`.
 8. Using the `appendChild` method, append the child node `liNode1` to parent node `olNode`.
 9. Using the `appendChild` method, append the child node `liNode2` to parent node `olNode`.
 10. Using the `appendChild` method, append child node `olNode` to parent node `divNode`.

## Task 5:
 1. Using the `createElement` method, create a new image (\<img\>) node and then assign the returned node object to a new variable named `imgNode`.
 2. Using the `createAttribute` method, create a new attribute named "src" and then assign the returned node object to a new variable named `srcAttr`.
 3. Set the value of the `srcAttr` (i.e. `srcAttr.value`) to "http://munsellb.people.cofc.edu/img/prettypicture.jpg".
 4. Using the `setAttributeNode` method, add child node `srcAttr` to parent node `imgNode`.
 5. Using the `appendChild` method, append child node `imgNode` to parent node `divNode`.
