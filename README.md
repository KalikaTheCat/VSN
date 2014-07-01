# Vision

The central plugin for Vision Network

### Coding Conventions

- Please have new lines at the end of **all** files.
- Indent properly (use **4** spaces, **not tabs**)
- Add a new lines between methods, constructors, and global variable declarations. Example:
  ```java
public class Example<K, V> {
    private final K key;
    private final V value;

    public Entry(k k, V v) {
        key = k;
        value = v;
    }

    public K getKey() {
        return key;
    }

    public V getValue() {
        return value;
    }
}

### Folder Organization

If you plan to add addition plugins, be sure to put them in the `plugins` folder. Additionally, keep all classes under their appropriate plugin's folder. This is to ensure we don't have directories and files in the same folder.

`Reminder:` We have no use of **empty directories**; please do not create them.
