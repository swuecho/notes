##  Moose::Meta::Attribute::Native::Trait::Array 
```perl
count
is_empty
elements
get($index)
pop
push($value1, $value2, value3 ...)
shift
unshift($value1, $value2, value3 ...)
splice($offset, $length, @values)
first( sub { ... } )
first_index( sub { ... } )
grep( sub { ... } )
map( sub { ... } )
reduce( sub { ... } )
sort
sort( sub { ... } )
sort_in_place
sort_in_place( sub { ... } )
shuffle
uniq
join($str)
set($index, $value)
delete($index)
insert($index, $value)
clear
accessor($index)
accessor($index, $value)
natatime($n)
natatime($n, $code)
shallow_clone
```
## Moose::Meta::Attribute::Native::Trait::Hash
```perl
get($key, $key2, $key3...)
set($key => $value, $key2 => $value2...)
delete($key, $key2, $key3...)
keys
exists($key)
defined($key)
values
kv
elements
clear
count
is_empty
accessor($key)
accessor($key, $value)
```
