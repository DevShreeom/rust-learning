- in rust we use [let] to define variable
eg. 
```
let x = 1;
```

- basically all variable in rust by default are immutable which means the variable value doesn't chage.

- to make it mutable we add [mut]

```
let apples = 5; // immutable
let mut bananas = 5; // mutable

```

- The :: syntax in the ::new line indicates that new is an associated function of the String type.

- read_line method on the standard input handle to get input from the user
- The & indicates that this argument is ref,  which gives you a way to let multiple parts of your code access one piece of data without needing to copy that data into memory multiple times. 
lol ig it's memory saver!

- references are immutable by default. Hence, you need to write [&mut] guess rather than [&guess] to make it mutable
- you call a method with the .method_name() syntax.
- read_line puts whatever the user enters into the string we pass to it, but it also returns a Result


---


u32 is unassingned 32 bit integer 
i32 us 32bit integer

same for i64
