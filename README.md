# itkhmerglossary
សទ្ទានុក្រម



# file pobo structure
## root key rule
key=value \
key name= any value 

*Ex1:* \
hello= love mom \
world= is our place for living 

*Ex2:* \
hello= love mom | world= is our place for living 

*JSON Comparison:* \
{"hello": "love mom", "world": "is our place for living"}

## sub key rule
key= value > subkey1= sub value \
key= value >> subkey1= sub value \
key= value >>> subkey1= sub value 

*Ex1:* \
dog = is animal who stay close with us \
container > \
panel1= a smaller board \
panel2= is bigger than spot 

*Ex2:* \
dog = is animal who stay close with us | container > panel1= a smaller board | panel2= is bigger than spot 

*JSON Comparison:* \
{"dog":"is animal who stay close with us", "container": {"panel1":"a smaller container", "panel2": "is bigger than spot"}}

