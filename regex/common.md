# Common regex
1. ^((?!town).)*$ `Except exclude`
2. (?=(\d{3})+(?!\d)) `Format number`
3. \d(?=px) positive lookahead `2px => 2`
4. (?<=\<span>)(.*\n?)(?=\<\/span>)
=> \?<=\ positive lookbehind
ex: (?<=abc)\d+ `avc123abc456` => `123`
