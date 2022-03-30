# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (firstName, lastName, age){
  const person = {
    firstName: firstName,
    lastName: lastName,
    age: age,
  }

  return person
}
```

| Input | Output |
| ----- | ------ |
| "Efrain", "Tinoco", 42      | { firstName: "Efrain", lastName: "Tinoco", age: 42 } | 
| "Marisa", "Tinoco", 14      | { firstName: "Marisa", lastName: "Tinoco", age: 14 } | 
| "Jordan", "Tinoco", 18      | { firstName: "Jordan", lastName: "Tinoco", age: 18 } | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This function is returning the values for three inputs and then returns it as an object with values inputed for firstName, lastName, and age.
Whatever value you give the keys will return when function runs. </td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
