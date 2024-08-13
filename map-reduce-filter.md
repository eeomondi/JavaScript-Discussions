
### Discussion Topic: Understanding JavaScript Array Methods - `reduce`, `filter`, and `map`

#### Introduction:
JavaScript provides several powerful methods to manipulate arrays, three of the most commonly used are `reduce`, `filter`, and `map`. Understanding the differences between these methods is crucial for writing efficient and effective code. Let's dive into a discussion that explores how each method works, their use cases, and how they differ from one another.

#### Questions to Consider:
1. **Purpose and Functionality:**
   - What is the primary purpose of each method (`reduce`, `filter`, and `map`)? 
   - How does each method process the elements of an array? Can you describe what happens to the array elements during the execution of these methods?

2. **Output Differences:**
   - What type of output does each method produce? Does `map`, `filter`, or `reduce` always return an array, or can they return different data types?

3. **Use Cases:**
   - Can you think of practical scenarios or examples where you would use `reduce` over `map`, or `filter` over `reduce`? 
   - How would you decide which method to use when given a specific problem?

4. **Performance Considerations:**
   - Are there any performance implications when using one method over the others? For example, in terms of time complexity, how do these methods compare?

5. **Combination of Methods:**
   - How can these methods be combined in a single operation to achieve more complex data transformations? Can you give an example where you might use two or more of these methods together?

#### Activity:
Try to refactor the following code snippets using different array methods. Discuss with your peers how each method changes the approach and the outcome.

1. **Example 1:**
   ```javascript
   const numbers = [1, 2, 3, 4, 5];
   let sum = 0;
   for (let i = 0; i < numbers.length; i++) {
       sum += numbers[i];
   }
   console.log(sum);
   ```

2. **Example 2:**
   ```javascript
   const numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9];
   const evenNumbers = [];
   for (let i = 0; i < numbers.length; i++) {
       if (numbers[i] % 2 === 0) {
           evenNumbers.push(numbers[i]);
       }
   }
   console.log(evenNumbers);
   ```

3. **Example 3:**
   ```javascript
   const numbers = [1, 2, 3, 4, 5];
   const doubleNumbers = [];
   for (let i = 0; i < numbers.length; i++) {
       doubleNumbers.push(numbers[i] * 2);
   }
   console.log(doubleNumbers);
   ```
