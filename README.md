# HashPrinter

HashPrinter will turn an arbitrary length hexadecimal string into
human-readable text. It can be used to efficiently and reliably
communicate hash codes over voice communication systems.

One Application example might be the validation of a recevied
Public Key by phone call between originator and the receiver
of the public key.

Example Use:

    bash-3.2$ shasum ~/.ssh/id_rsa.pub 
    b06dcc5549fdc1eab8ffff5780c0aca64589a472  /Users/frank/.ssh/id_rsa.pub
    bash-3.2$ ./sprprog.exe b06dcc5549fdc1eab8ffff5780c0aca64589a472
    wild boar eats stone.
    weasel grinds dandelion.
    dog crushs nettle.
    squirrel sucks cornflower.
    roe deer plucks red clover.
    badger collects raspberry.
    wildcat sucks crosswort.
    wildcat crushs wheat.
    tiger eats dandelion.
    man harvests dandelion.
    badger reaps nettle.
    dog drys honey.
    badger likes wheat.
    boy.


    bash-3.2$ ./sprprog.exe ABCD
    badger collects dandelion.
    weasel.
    bash-3.2$ ./sprprog.exe 1234
    woman binds birchtree.
    cat.
    bash-3.2$

    (sprprog.exe is the name if the HashPrinter executable here)
