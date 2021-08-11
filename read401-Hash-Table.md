# Hash Tables:

## What is a Hashtable?
  - **Hash:** A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.
  - **Buckets:** A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.
  - **Collisions:** A collision is what happens when more than one key gets hashed to the same location of the hashtable.


## What Are they?
  - **Hashtables** are a data structure that utilize key value pairs. This means every Node or Bucket has both a key, and a value.
  - The basic idea of a hashtable is the ability to store the key into this data structure, and quickly retrieve the value. This is done through what we call a hash. A hash is the ability to encode the key that will eventually map to a specific location in the data structure that we can look at directly to retrieve the value.
  - Since we are able to hash our key and determine the exact location where our value is stored, we can do a lookup in an O(1) time complexity. This is ideal when quick lookups are required.


## Hash function:
  - A hash function is any function that can be used to map a data set of an arbitrary size to a data set of a fixed size, which falls into the hash table. The values returned by a hash function are called hash values, hash codes, hash sums, or simply hashes.
  - To achieve a good hashing mechanism, It is important to have a good hash function with the following basic requirements:
    - Easy to compute: It should be easy to compute and must not become an algorithm in itself.
    - Uniform distribution: It should provide a uniform distribution across the hash table and should not result in clustering.
    - Less collisions: Collisions occur when pairs of elements are mapped to the same hash value. These should be avoided.

## Structure:
### Hashing:
  - Basically, a hash code turns a key into an integer. It’s very important that hash codes are deterministic: their output is determined only by their input. Hash codes should never have randomness to them. The same key should always produce the same hash code.

### Creating a Hash:
  - A hashtable traditionally is created from an array. I always like the size 1024. this is important for index placement. After you have created your array of the appropriate size, do some sort of logic to turn that “key” into a numeric number value. Here is a possible suggestion:
     - Add or multiply all the ASCII values together.
     - Multiply it by a prime number such as 599.
     - Use modulo to get the remainder of the result, when divided by the total size of the array.
     - Insert into the array at that index.


## Collisions:
  - A collision occurs when more than one key hashes to the same index in an array. As mentioned earlier, a “perfect hash” will never have any collisions. To put this into perspective, the worst possible hash is one that hashes every single key to the same exact index of an array. The more keys you have hashed to a specific index, the more key/value pair combos you can potentially have.

## Hash tables are made up of two parts:

   - Object: An object with the table where the data is stored. The array holds all the key-value entries in the table. The size of the array should be set according to the amount of data expected.
   - Hash function (or mapping function): This function determines the index of our key-value pair. It should be a one-way function and produce the a different hash for each key.


   ![image](https://user-images.githubusercontent.com/79833733/129062550-7fd3f5b3-849f-4f1f-91ed-50e064b5087a.png)


## Hash tables vs. trees:
  - Hashing and trees perform similar jobs, but various factors in your program determine when to use one over the other.

  - Trees are more useful when an application needs to order data in a specific sequence. Hash tables are the smarter choice for randomly sorted data due to its key-value pair organization.

  - Hash tables can perform in constant time, while trees usually work in O(log n)O(logn). In the worst-case scenario, the performance of hash tables can be as low as O(n)O(n). An AVL tree, however, would maintain O(log n)O(logn) in the worst case. An efficient hash table requires a hash function to distribute keys. A tree is simpler, since it accesses extra space only when needed and does not require a hash function.


  
 




