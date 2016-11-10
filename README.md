# Hashopoly

## Objectives

1. Build simple hashes.
2. Build nested hashes.
3. Access and modify data stored in a hash.
4. Add new data to a hash.

## Instructions

The series of tests will require you to build methods that build up a nested hash, one layer (or "level") at a time, in a similar way to how we built our `epic_tragedy` hash in the previous lesson. Read the test output very carefully; it will guide you through building the necessary methods. Don't forget to return the hash, if necessary! At the end of the exercise, your multidimensional monopoly hash should look like this:

```ruby
monopoly =  {
  :railroads=>
  {
    :pieces=>4,
    :rent_in_dollars=>
    {
      :one_piece_owned=>25,
      :two_pieces_owned=>50,
      :three_pieces_owned=>100,
      :four_pieces_owned=>200
    },
    :names=>
    {
      :reading_railroad=>
      {
        "mortgage_value"=>"$100"
      },
      :pennsylvania_railroad=>
      {
        "mortgage_value"=>"$200"
      },
      :b_and_o_railroad=>
      {
        "mortgage_value"=>"$400"
      },
      :shortline=>
      {
        "mortgage_value"=>"$800"
      }
    }
  }
}
```

**Don't Forget!** 

Remember that you can use `binding.pry` to help you get inside your methods and understand what is going on if you need to debug. Remember to google questions that you have if you get stuck!

## Resources
1. [What is a Hash in Ruby?](http://ruby.about.com/od/rubyfeatures/a/hashes.htm)
2. [Ruby Documentation on Hashes](http://ruby-doc.org/core-2.1.3/Hash.html)
