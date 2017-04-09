# Sets

```java
package com.kopimi;

interface Set<T> {
  /**
   * Check if the contains the given element.
   */
  boolean contains(T element);
}
```

```java
package com.kopimi;

interface MutableSet<T> extends Set<T> {
  /**
   * Add an element to this set.
   *
   * @return {@code true} if the element added was already present in this set.
   */
  boolean add(T element);

  /**
   * Remove an element.
   * @return {@code true} if the element removed was present in this set.
   */
  boolean remove(T element);
}
```
