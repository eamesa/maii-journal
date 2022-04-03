---
layout: post
title: Three things I learned from The Ruby Koans
---

Here are (at least) three things I learned from [The Ruby Koans](http://rubykoans.com/):

- assert test, "error message"

- For Arrays array[2,5] means start at the element 2 and take 5 elements.

```rb
assert_equal [1,2,3,4,5], (1..5).to_a
assert_equal [1,2,3,4], (1...5).to_a
```

- The splat operator does something to arrays?

- what is assert_raise useful for?

- hash2 = Hash.new("dos") "dos" is the default value.

- Didn't understand this one
```sh
  def test_default_value_with_block
    hash = Hash.new {|hash, key| hash[key] = [] }

    hash[:one] << "uno"
    hash[:two] << "dos"

    assert_equal ["uno"], hash[:one]
    assert_equal ["dos"], hash[:two]
    assert_equal nil, hash[:three]
  end
  ```
- Didn't understand constants
