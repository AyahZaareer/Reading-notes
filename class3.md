# Lists and Keys:
## Basic List Component
### Usually you would render lists inside a component.

### We can refactor the previous example into a component that accepts an array of numbers and outputs a list of elements.

![image](https://user-images.githubusercontent.com/79833733/116164542-91a1b800-a702-11eb-9279-f7e5e6795859.png)



### When you run this code, you’ll be given a warning that a key should be provided for list items. A “key” is a special string attribute you need to include when creating lists of elements. We’ll discuss why it’s important in the next section.

## Keys:
### Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity:

![image](https://user-images.githubusercontent.com/79833733/116164734-f9f09980-a702-11eb-870d-483b7ce9463c.png)

### The best way to pick a key is to use a string that uniquely identifies a list item among its siblings. Most often you would use IDs from your data as keys:
![image](https://user-images.githubusercontent.com/79833733/116164904-55228c00-a703-11eb-9392-6dd43d872454.png)
### When you don’t have stable IDs for rendered items, you may use the item index as a key as a last resort:
![image](https://user-images.githubusercontent.com/79833733/116164991-869b5780-a703-11eb-8ac2-2f202768870a.png)
### We don’t recommend using indexes for keys if the order of items may change. This can negatively impact performance and may cause issues with component state. Check out Robin Pokorny’s article for an in-depth explanation on the negative impacts of using an index as a key. If you choose not to assign an explicit key to list items then React will default to using indexes as keys.

![image](https://user-images.githubusercontent.com/79833733/116165055-ab8fca80-a703-11eb-80c0-ab8743f315e9.png)



![image](https://user-images.githubusercontent.com/79833733/116165070-b8acb980-a703-11eb-99a3-bdd7d19caf6b.png)


### Embedding map() in JSX:

![image](https://user-images.githubusercontent.com/79833733/116165221-14774280-a704-11eb-910b-1adb0c88b30c.png)
