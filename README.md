#Gloater Gem

After struggling a long time with a programming problem, and using the `puts` debugging technique, I finally found what I had been looking for:
```bash
 => #<Bacon:0x007ffc8433a5a8>
```

While it was satisfying to leave behind the nil errors I was getting (I am not _trying_ to call :chunky on nil, I am _trying_ to call :chunky on `#<Bacon:0x007ffc8433a5a8>` ), the expressionless class object left me out in the cold. I wanted the programmatic equivalent of a fist-bump from my program!

#Usage
Wherever you need a bit of celebratory goodness
```ruby
require 'gloater'
# crufty spaghetti code in state of refactor
Gloater.gloat(5)
```

#Result
```bash
I rock!
I rock!
I rock!
I rock!
I rock!
```